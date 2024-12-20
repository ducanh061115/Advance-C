# Định nghĩa
- Hàm cục bộ có thể sử dụng trực tiếp hoặc gán cho biến
- Sử dụng 1 lần duy nhất trong chương trình
- Cú pháp: [capture] (parameters) -> <return_type>
- Capture: cho biết cách các biến ở phạm vi bên ngoài được sử dụng trong lambda
  {
  };
- Ví dụ:
  ```
  auto greet = []()
  {
  cout << "Hello world"";
  };
  greet();
  ```
  - Ví dụ 2 có tham số truyền vào:
  ```
  auto sum = [](int a, int b) -> int // a b nằm ở stack và là biến toàn cục với hàm nhưng là biến cục bố với hàm main
  {
  return a+b
  };
  cout << "Sum: " << sum(3,5) << endl;
  ```
  - Có thể tạo biến a và b ở bên ngoài
  ## Khác biệt với function:
  - Chỉ sử dụng 1 lần
  - Là hàm cục bộ
  - không có giá trị trả về
