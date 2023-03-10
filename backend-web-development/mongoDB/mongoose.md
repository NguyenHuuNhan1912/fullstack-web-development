# MONGOOSE 
## Mongoose là gì ?
* Mongoose là một thư viện mô hình hóa đối tượng (Object Data Model - ODM) cho MongoDB và Node.js. Nó quản lý mối quan hệ giữa dữ liệu, cung cấp sự xác nhận giản đồ và được sử dụng để dịch giữa các đối tượng trong mã và biểu diễn các đối tượng trong MongoDB.
## Truy vấn có điều kiện trong Mongoose
    * ==: {key: value}
    * Nhỏ hơn: {key: {$lt: value}} 
        * vd: {age: {$lt: 18}} -> Tìm các age < 18 trong document
    * Nhỏ hơn hoặc bằng: {key: {$lte: value}}
    * Lớn hơn: {key: {$gt: value}}
    * Lớn hơn hoặc bằng: {key: {$gte: value}}
    * Khác: {key: {$ne: value}}
    * Trong khoảng: {key: {$in: [value1, value2]}}
    * Không thuộc khoảng: {key: {$nin: [value1, value2]}}
    * Hoặc(or): Tìm tất cả các document có tuổi 23 hoặc tên nguyenhuunhan -> model.find({$or: [
        {age: 23},
        {name: 'nguyenhuunhan'}
    ]})
## Các method truy vâns trong Mongoose
### find(query, projection)
    * query: là câu truy vấn
    * projection: Trả về trường mong muốn 
        + 1: Là trả về
        + 0: là không trả về
        
### findById(id) -> Tìm kiếm theo id 
    * id: là id của document

### findByIdAndDelete(id) -> Tìm kiếm theo id và xóa 
    * id: là id của document

### findByIdAndUpdate(id, dataUpdate) -> Tìm kiếm theo id và cập nhật
    * id: là id của document
    * dataUpdate: là data sẽ được cập nhật
## THAM KHẢO
* https://toidicode.com/truy-van-du-lieu-trong-mongodb-289.html