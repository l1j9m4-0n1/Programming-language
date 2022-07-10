# PYTHON

- Các kiểu dữ liệu trong python.

1) Numbers: int, long, float, complex(số phức), ...

2) String: Dùng (*) (lặp chuỗi) ; Dùng (+) (nối chuỗi).

3) List[,,]: Dãy bao gồm có thể là cả sỗ lẫn chuỗi ; Có thể đặt lại giá trị của các phần tử ; [ : ].

4) Tuple(,,): Tương đối giống List, khác là không thể đặt lại giá trị. -> chỉ đọc.

5) Dictionary{,,}: cặp keys - values

>Không cần khai báo kiểu dữ liệu. Muốn biết kiểu dữ liệu gì print(type(<var>)).
  
- Toán tử không có gì khác các ngôn ngữ khác. Thêm `**` là tính lũy thừa a**b = a mũ b, `//` là chia lấy phần nguyên. 

  VD: 2**3 = 8 ; 9 // 2 = 4.
  
  Toán tử membership để kiểm tra xem 1 giá trị có nằm trong giá trị khác không. `in` và `not in`.
  
  VD: x = input()
      print('H' in x)
  
  Toán tử định danh
  
  VD: a = int(input())
      b = int(input())
      print(a is b)
  
  Toán tử logic giống C, Cpp.
  
- Điều kiện `if-else`.
  
```python
  if a == b:
	print("a == b")
else:
	if a > b:
		print("a > b")
	else:
		print("a < b")
```
  
- Nhập xuất.
  
```python
name = input()
print("Hello " + name)
```

>Khi nhập dữ liệu cho một biến từ keyboard thì kiểu dữ liệu đó luôn là str (kể cả nhập gái trị số cho biến đó). Muốn thay đổi kiểu dữ liệu thì phải ép kiểu.
  
```python
a = int(input())
b = float(input())
```
  
  
  
- Hàm con.

```python
def <name>(<arguments>):
# không return nghĩa là như hàm void.
```

>Note: Python3. VD: b'<string>'. u là chuỗi unicode ; b là biểu thị chuỗi kí tự byte ; r là chuỗi kí tự không thoát ra được @@.
