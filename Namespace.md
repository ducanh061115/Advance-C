# Định nghĩa
- Nhóm các định danh như tên biến, hàm, class vào một không gian tách biệt để tránh xung đột tên.
- Cú pháp: namespace name_of_namespace{
  // biến
  // hàm
  // class
  }
  ## Namespace lồng nhau
  namespace A
  {
  namespace C{
  string str = "ha"
  }
  }
  - Để gọi được C phải gọi từ A: cout << "in: " << A::C::str << endl;
  - Nếu cú pháp A::C thì không cần gọi ở dưới nữa: A::str 
