# CÂU HỎI PHỎNG VẤN HTML
## 1. Thẻ Meta được dùng để làm gì trong hmtl5 ?
### Định nghĩa thẻ meta
* Thẻ meta để cung cấp thông tin về tài liệu HTML
* Thẻ meta sẽ không được hiển thị trên trình duyệt 
* Thẻ meta được sử dụng để định nghĩa các thông tin cơ bản
    * Mô tả trang web
    * Từ khóa
    * Tác giả
### Các thuộc tính của thẻ meta
* Thẻ meta có 4 thuộc tính: httq-equiv, name, content, charset
* Thuộc tính `charset="UTF-8"`
    * charset(character set): Bộ kí tự đã được tiêu chuẩn hóa(ASCII, UTF8,...) được biểu diễn trong các file, văn bản, trang web hoặc các tài liệu khác
    * Encoding system: Là hệ thống mã hóa các bộ kí tự để chuyển về dạng 0 và 1 cho máy tính hiểu được
    * Việc sử dụng UTF-8 bởi vì đây là bộ kí tự phổ biến nhất hiện nay
* Thuộc tính `http-equiv` và `name` sử dụng cùng với thuộc tính `content`
* Thuộc tính `http-equiv`: Xác định kiểu nội dung và kiểu mã hóa ký tự của trang web và xác định việc tải lại trang
* Thuộc tính `name`: Chỉ định tên cho thẻ meta
* Thuộc tính `name` có các giá trị như `discription`, `revised`, `author`. Như đã nói thuộc tính `name` hoặc `httpequiv` phải được sử dụng cùng với thuộc tính `name`
    * `<meta name="discription" content="Đây là tài liệu phỏng vấn">` -> Mô tả nội dung trang web
    * `<meta name="revised" content="HuuNhan, 22/12/2022">` -> Mô tả ngày giờ thực hiện trang web
    * `<meta name="author" content="Nguyen Huu Nhan">` -> Mô tả tác giả trang web
* Thuộc tính `httequiv` có các giá trị như `X-UA-Compatible`, `refresh`
    * `<meta http-equiv="X-UA-Compatible" content="IE=edge">`-> Cho phép nhà phát triển web lựa chọn phiên bản của Internet Explorer(IE)
    * `<meta http-equiv="refresh" content="10; url=http://example.com">` -> Cứ 10s trôi qua thì trang web sẽ load lại 1 lần