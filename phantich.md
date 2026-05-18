Post dùng để tạo mới tài nguyên

Put dùng để cập nhật toàn bộ tài nguyên

Idempotent là gửi cùng 1 request nhiều lần nhưng chỉ trả về 1 kết quả giống nhau trên server

Đồng nghiệp B đúng vì:
- Ta đang tạo mới đơn hàng
- orderId do server tự sinh
- Client ko biết trước id

Lý do ko dùng Put:
- chỉ dùng khi biết đc id cần cập nhật
- dùng khi muốn cập nhật hoặc thay thế dữ liệu