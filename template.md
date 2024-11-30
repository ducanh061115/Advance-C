# Định nghĩa
## Function template
- Dùng trong trường hợp có nhiều hàm trùng tên nhau và mỗi hàm phải có cùng kiểu dữ liệu của các tham số truyền vào.
- Cú pháp: template<typename T> -> T sum(T a, T b) // đây là function template
- Cách máy tính tính toán:
- cout << "sum" << sum(1,5) << endl; // Máy sẽ hiểu kiểu tham số truyền vào là kiểu int
- cout << "sum" << sum(1.5,5.5) << endl; // máy sẽ hiểu tham só truyền vào là số thực kiểu double
- Nếu muốn khác kiểu phải có 2 kiểu dữ liệu: template<typename T1, typename T2)
- Từ khóa"auto": tự động suy diễn để kiểu dữ liệu: auto sum(T1 a, T2 b);
## Class Template:
## Template non-type parameter:
```
template<typename T1, int size>
class Array
{
T arr[size]; // private
public:
void set(int index, T value)
{
if (index >= 0 && index < size) arr[index] = value
}
T getElment(int index)
{
return arr[index];
}
};
int main()
{
Array<int, 5> arr
arr.set(0,10);
return 0;
}


