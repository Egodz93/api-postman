# Thực hành kiểm thử bằng Postman
Postman là một công cụ mạnh mẽ giúp các lập trình viên và kiểm thử viên làm việc với API một cách dễ dàng. Với giao diện trực quan và nhiều tính năng hỗ trợ, Postman giúp kiểm thử API trở nên nhanh chóng, chính xác và hiệu quả hơn.
Tính năng nổi bật
Gửi các loại yêu cầu HTTP: GET, POST, PUT, DELETE,...
Quản lý Headers, Body, và Authentication dễ dàng.
Nhận và hiển thị kết quả trả về từ server (Response).
Viết test script bằng JavaScript để kiểm tra phản hồi tự động.
Tổ chức API theo Collection, hỗ trợ chia sẻ và cộng tác nhóm.
Sử dụng biến môi trường để linh hoạt chuyển đổi giữa các môi trường (Dev, Test, Prod).
Hỗ trợ Mock Server, Monitoring, và tích hợp CI/CD.

Sử dụng API giả lập từ JSONPlaceholder.

1.1. Phương Thức HTTP (GET/POST/PUT/DELETE): GET

URL: https://jsonplaceholder.typicode.com/

Tham Số: /posts

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
![Screenshot (153)](https://github.com/user-attachments/assets/53de5052-841f-49ad-a9c9-065772eb3ba0)

1.2. Phương Thức HTTP (GET/POST/PUT/DELETE): POST

URL: https://jsonplaceholder.typicode.com/

Tham Số: posts 

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
![Screenshot (154)](https://github.com/user-attachments/assets/7f5c24d8-7a82-4725-8982-e8c0415c839e)
1.3. Phương Thức HTTP (GET/POST/PUT/DELETE): PUT

URL: https://jsonplaceholder.typicode.com/

Tham Số: posts/1

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
![Screenshot (155)](https://github.com/user-attachments/assets/746b3a14-0888-4655-8576-c2d4c5879fbf)
1.4. Phương Thức HTTP (GET/POST/PUT/DELETE): DELETE

URL: https://jsonplaceholder.typicode.com/

Tham Số: posts/1

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
![Screenshot (156)](https://github.com/user-attachments/assets/1e25740c-cffb-4838-a42d-7b7e8ef5e6be)

