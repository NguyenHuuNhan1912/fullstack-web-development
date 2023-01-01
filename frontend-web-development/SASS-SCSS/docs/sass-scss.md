# <img src="../images/sass.png" width="60" height="60"> SASS/SCSS <br>

## CSS Preprocessor là gì ?
* Là một ngôn ngữ tiền xử lý của CSS(SASS/SCSS, LESS,...)
* Là một ngôn ngữ kịch bản mở rộng của CSS giúp viết code CSS nhanh hơn và có cấu trúc rõ ràng hơn 
* CSS Preprocessor giúp tiết kiệm thời gian viết CSS. Dễ dàng bảo trì và phát triển CSS

## SASS/SCSS là gì ?
* Là một chương trình tiền xử lý của CSS 
* Giúp viết code CSS như một ngôn ngữ lập trình, có cấu trúc rõ ràng 
* SASS và SCSS về bản chất vấn đề là giống nhau, chỉ khác nhau ở cách viết 
* SASS có phần mở rộng là .sass được viết theo cách thụt đầu dòng
* SCSS có phần mở rộng là .scss được viết giống như ngôn ngữ lập trình Ruby(vì nó được các lập trình viên Ruby thiết kế và phát triển)
* SCSS ra đời sau SASS nhằm mục đích thu hẹp khoảng cách giữa SASS và CSS 

## Các tính năng cơ bản của SCSS 
* `Variables(Biến)`: Các biến trong SCSS được sử dụng như các biến của các ngôn ngữ lập trình khác
* `Nesting(Lồng nhau)`: Cho phép viết các đoạn CSS lồng nhau
* `Mixin:` tương t như một function(hàm hay chương trình con) gom nhóm các thuộc tính CSS, và có thể nhận tham số để xử lý nhưng `không có giá trị trả về`
* `Functions`: Tương tự như mixin nhưng `có giá trị trả về(return)`
* `Extends(Kế thừa)`: Kế thừa là một khái niệm khá phổ biến trong lập trình hướng đối tượng(OOP) và kế thừa trong SCSS cũng có tính năng này 
* `Loop(Vòng lặp)`: Vòng lặp cũng được sử dụng trong SCSS
* `If else(Câu điều kiện)`: Ngoài vòng lặp câu điều điện cũng được sử dụng

## Cài đặt SASS/SCSS
* Bước 1: Cài đặt `NodeJs` để sử dụng được `npm` của `NodeJs`
    * `NodeJs`: Là một nền tảng chạy phía Server xử lý phần `backend` của website
    * `NPM(Node package manager)`: Là một công cụ tạo và quản lý các thư viện lập trình Javascript cho NodeJs. `SASS` khi cài đặt sẽ được `NPM` quản lý
* Bước 2: Cài đặt `SASS` bằng dòng lệnh 
    * Mở terminal gõ lệnh `npm install -g sass`

## Biên dịch SASS/SCSS thành CSS
* Biên dịch bằng câu lệnh `sass file.scss(file.sass) file.css --watch`
    * `--watch`: Giám sát sự thay đổi và tự cập nhật khi có chỉnh sửa

<br>

*Made by Nguyen Huu Nhan*