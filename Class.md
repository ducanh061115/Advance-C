# Định nghĩa:
- Một cấu trúc dữ liệu tự định nghĩa có thể chứa dữ liệu và các hàm thành viên liên quan
- Cú pháp: 'class _ten {}'
- Gồm 3 loại phạm vi truy cập: private, proctected, public
- property là biến, method là hàm.
- Khi khởi tạo object sẽ tự động gọi hàm constructor(hàm khởi tạo)
- object cục bộ nằm ở phân vùng stack.
## Private:
- Chỉ có thể try cập bên trong lớp
## Protected:
- Tương tự private nhưng có thể truy cập từ lớp kế thừa
## Public:
- Có thể được truy cập từ bên ngoài lớp
- Hàm thành viên có thể được định nghĩa
## constructor:
- Được tự động khởi tạo khi ta khởi tạo 1 object thuộc 1 class bất kì có tên giống với class.
## destructor(ham huy doi tượng)
- ~Hinh()
- Được gọi ra trước khi thu hồi địa chỉ của object
