# postman

## Sử dụng postman để kiểm thử API https://jsonplaceholder.typicode.com/

### 1. Giới thiệu về Postman:

Postman là một công cụ giúp phát triển và kiểm thử các API một cách dễ dàng và hiệu quả. Nó cung cấp một giao diện người dùng đồ họa để tạo, gửi và kiểm tra các yêu cầu HTTP và HTTPS.

Các tính năng chính của Postman:

- Gửi yêu cầu HTTP (GET, POST, PUT, DELETE) đến API.
- Quản lý và tổ chức các yêu cầu trong các bộ sưu tập.
- Sử dụng biến để tái sử dụng giá trị trong các yêu cầu khác nhau.
- Tạo và chạy các kịch bản kiểm thử tự động.
- Phân tích và kiểm tra các phản hồi từ API.

### 2. Sử dụng Collections và Variables

Collections:

Tạo Collection: Rest API basics: CRUD, test and variables
Tạo ra các request với các phương thức cụ thể (GET, POST, PUT, DELETE).
(Xem ảnh list_test_method.png)

Variables:

Tạo biến base_url bằng địa chỉ của API và sử dụng biến base_url
(Xem ảnh variables.png)

### 3. Kiểm thử API cơ bản:

Các yêu cầu HTTP đến API: GET, POST, PUT, DELETE.

Chức năng của các phương thức:

- GET: dùng để lấy dữ liệu
- POST: dùng để gửi dữ liệu
- PUT: dùng để cập nhật dữ liệu
- DELETE: dùng để xoá dữ liệu

Cách sử dụng:

(Xem các ảnh get/post/put/delete_method.png)

Dữ liệu trả về:

- GET:
  Status: 200 OK => Success: lấy dữ liệu thành công
  Time: 174ms => Thời gian phản hồi request là 174ms
  Size: 1.33 KB => Dung lượng của dữ liệu là 1.33 KB

- POST:
  Status: 201 created => Success: gửi dữ liệu thành công
  Time: 1726ms => Thời gian phản hồi request là 1726ms
  Size: 1.36 KB => Dung lượng của dữ liệu là 1.36 KB

- PUT:
  Status: 200 OK => Success: cập nhật dữ liệu thành công
  Time: 279ms => Thời gian phản hồi request là 279ms
  Size: 1.25 KB => Dung lượng của dữ liệu là 1.25 KB

- DELETE:
  Status: 200 OK => Success: xoá dữ liệu thành công
  Time: 264ms => Thời gian phản hồi request là 264ms
  Size: 1.06 KB => Dung lượng của dữ liệu là 1.33 KB

### 4. Run Test

(Xem ảnh run_test.png)
Hiển thị các test đã pass, các test failed, và tổng thời gian chạy các test case.
