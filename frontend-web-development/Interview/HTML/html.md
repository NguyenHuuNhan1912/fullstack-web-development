# CÂU HỎI PHỎNG VẤN HTML
## 1. Thẻ Meta được dùng để làm gì trong hmtl5 ?
### 1.1 Định nghĩa thẻ meta
* Thẻ meta để cung cấp thông tin về tài liệu HTML
* Thẻ meta sẽ không được hiển thị trên trình duyệt 
* Thẻ meta được sử dụng để định nghĩa các thông tin cơ bản
    * Mô tả trang web
    * Từ khóa
    * Tác giả
### 1.2 Các thuộc tính của thẻ meta
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

## 2. Thẻ Iframe là gì và nó hoạt động như thế nào ?
* Thẻ Iframe là một tài liệu HTML(HTML document) được nhúng vào một trang HTML khác
* Thẻ Iframe thường được dùng để nhúng website vào website khác hoặc bản đồ định vị, youtube,..

## 3. Thuộc tính alt trong thẻ `<img>` là gì ?
* Thuộc tính alt được tạo ra có 2 mục đích
    * Để hiển thị thông tin hình ảnh trong trường hợp người dùng không xem được ảnh vì các lí do như lỗi đường dẫn hay lỗi hình ảnh
    * Thuộc tính alt cũng để cung cấp thông tin cho hình ảnh, mô tả hình ảnh
* Một số trường hợp thuộc tính alt có thể để trống 

## 4. Khai báo DOCTYPE dùng để làm gì ?
* Để trình duyệt nhận biết trang html đó được viết ở phiên bản nào
* Hiện nay phiên bản phổ biến nhất là HTML5 -> `!DOCTYPE html`
* Lưu ý `!DOCTYPE html` không phải là một thẻ trong HTML

## 5. HTML, XML và XHTML là gì sự khác biệt giữa chúng ?

### 5.1 HTML - Hyper Text Markup Language
* Là ngôn ngữ đánh dấu siêu văn bản
* Là ngôn ngữ hiển thị các thành phần và cấu trúc của một website

### 5.2 XML - eXtensible Markup Language
* XML là ngôn ngữ đánh dấu mở rộng có chức năng truyền tải dữ liệu và mô tả nhiều loại dữ liệu khác nhau
* Trong lập trình web XML được ứng dụng nhiều nhất là các API service. Các API đó sẽ trả về kết quả dưới dạng `XML` hoặc `JSON`. Hiện nay thì `JSON` được sử dụng phổ biến hơn `XML`

### 5.3 XHTML - eXtensible Hypertext Markup Language 
* Là ngôn ngữ đánh dấu siêu văn bản mở rộng là sự kết hợp giữa `XML` và `HTML` 
* Là một ngôn ngữ có cùng khả năng như HTML nhưng có cú pháp chặt chẽ hơn
    * Các phần tử phải lồng nhau đúng cách
    * Phân biệt chữ hoa chữ thường
    * Tất cả thẻ `XHTML` phải có thẻ đóng
    * Tất cả các thuộc tính phải được đặt trong dấu ngoặc kép ""
## 6. JSON là gì ?
* `JSON` hay JavaScript Object Notation
* `JSON` cũng giống như `XML` là một định dạng trao đổi dữ liệu có cú pháp tương tự như các đối tượng của JavaScript
* `JSON` được tạo ra với Javascript nhưng hiện nay `JSON` được sử dụng rộng rãi là một dạng trao đổi dữ liệu hầu hết các ngôn ngữ hiện đại như `Python`, `JavaScript`, `Java`, `PHP`.

## 7. Làm sao để comment trong HTML ?
* Sử dụng `<!-- Comment html ở đây -->`

## 8. Phân biệt `block element` và `inline element`

### 8.1 `Block element`
* Các tag `block element` là các phần tử cấp khối 
* Khi các thẻ này được tạo ra nó sẽ chiếm trọn chiều ngang của dòng mà nó đang được hiển thị
* Các `block element` -> `p`, `section`, `article`,...

### 8.2 `Inline element`
* Các tag `inline element` là các phần tử cấp nội tuyến
* Khi các thẻ này được tạo ra nó sẽ chiếm đủ phần nội dung của thẻ chứ không chiếm hết chiều ngang
* Các `inline element` -> `img`, `span`,...

## 9. Có gì mới trong HTML 5 ? và tại sao phải dùng HTML 5 ?
* Các điểm mới của `HTML5` so với các phiên bản `HTML` trước
    * `<!DOCTYPE> html` -> Chỉ định đây là tài liệu `HTML5`
    * `header`, `nav`, `footer`, `aside`, `video`, `main`, `canvas` -> Là các thẻ mới được bổ sung vào `HTML5`
    * `HTML5` không còn thuộc tính `type` trong thẻ `script` và thẻ `link`
* `HTML5` là phiên bản mới nhất và được hỗ trợ tốt nhất bởi các trình duyệt nếu sử dụng các bản `HTML4` hoặc trước đó một số thẻ sẽ không còn được hỗ trợ gây ảnh hưởng đến trang web của chúng ta
<hr>

*Made by Nguyen Huu Nhan*