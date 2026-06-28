# 📘 TƯ DUY TÍNH TOÁN (Computational Thinking)
### Lý thuyết đầy đủ + 10 câu trắc nghiệm mỗi phần
**UET – VNU Hà Nội | Python Programming**

---

# PHẦN 1: GIỚI THIỆU – TƯ DUY TÍNH TOÁN

## 1.1 Tư duy tính toán là gì?

**Tư duy tính toán (Computational Thinking)** là kỹ năng phân tích và giải quyết vấn đề một cách có hệ thống theo cách mà máy tính có thể thực thi. Lập trình chỉ là công cụ để "nói" cho máy tính biết cách thực hiện giải pháp đó.

## 1.2 Bốn kỹ năng cốt lõi

| # | Kỹ năng | Định nghĩa | Ví dụ |
|---|---------|-----------|-------|
| 1 | **Phân rã (Decomposition)** | Chia bài toán lớn thành các phần nhỏ hơn, dễ quản lý hơn | Vẽ một con mèo → vẽ từng bộ phận riêng lẻ |
| 2 | **Nhận dạng mẫu (Pattern Recognition)** | Xác định các điểm tương đồng, xu hướng hoặc quy tắc trong dữ liệu | Tất cả mèo đều có mắt, đuôi, lông... |
| 3 | **Trừu tượng hóa (Abstraction)** | Tập trung vào thông tin cần thiết, bỏ qua chi tiết không quan trọng | Màu lông, độ dài đuôi cụ thể không quan trọng |
| 4 | **Thiết kế thuật toán (Algorithm Design)** | Thiết kế các bước hướng dẫn từng bước để giải quyết bài toán | Các bước chính xác để vẽ mèo cơ bản |

## 1.3 Quy trình giải quyết bài toán

```
Input → [Phân rã] → [Nhận mẫu] → [Trừu tượng] → [Thiết kế thuật toán] → Output
```

**Ví dụ thực tế: Bài toán quầy thu ngân sách (Bookstore Cashier)**
- **Input:** Danh sách sản phẩm trong giỏ hàng
- **Phân rã:** Tổng tiền = Tổng (số lượng × giá) của từng mặt hàng
- **Nhận mẫu:** Mỗi mặt hàng đều tính theo công thức: `amount = qty × price`
- **Thuật toán:**
  1. Khởi tạo `total = 0`
  2. Với mỗi mặt hàng: `total += qty × price`
  3. In tổng tiền

---

## 🔟 TRẮC NGHIỆM – PHẦN 1

**1.** Tư duy tính toán là:
- A. Kỹ năng sử dụng máy tính thành thạo
- B. Kỹ năng phân tích và giải quyết vấn đề theo cách máy tính có thể thực thi ✅
- C. Ngôn ngữ lập trình cụ thể
- D. Khả năng nhớ cú pháp Python

**2.** Kỹ năng "Decomposition" trong tư duy tính toán là:
- A. Nhận dạng các mẫu lặp lại trong dữ liệu
- B. Tập trung vào thông tin quan trọng, bỏ chi tiết thừa
- C. Chia bài toán lớn thành các phần nhỏ hơn ✅
- D. Thiết kế các bước giải quyết bài toán

**3.** Kỹ năng nào giúp nhận ra rằng "tất cả các mèo đều có đuôi, mắt và lông"?
- A. Decomposition
- B. Pattern Recognition ✅
- C. Abstraction
- D. Algorithm Design

**4.** Kỹ năng "Abstraction" có nghĩa là:
- A. Chia nhỏ vấn đề
- B. Tập trung vào thông tin thiết yếu, bỏ qua chi tiết không liên quan ✅
- C. Nhận diện mẫu
- D. Lập trình hướng đối tượng

**5.** Trong bài toán quầy thu ngân, bước "Tổng tiền = Tổng (số lượng × giá) của từng mặt hàng" thuộc kỹ năng nào?
- A. Pattern Recognition
- B. Decomposition ✅
- C. Algorithm Design
- D. Abstraction

**6.** Lập trình trong tư duy tính toán đóng vai trò gì?
- A. Thay thế hoàn toàn tư duy tính toán
- B. Là mục tiêu cuối cùng
- C. Là công cụ để diễn đạt giải pháp cho máy tính ✅
- D. Không liên quan đến tư duy tính toán

**7.** Kỹ năng nào mô tả việc thiết kế "các bước chính xác để vẽ mèo"?
- A. Decomposition
- B. Pattern Recognition
- C. Abstraction
- D. Algorithm Design ✅

**8.** Trong tư duy tính toán, bước đầu tiên khi gặp bài toán lớn là:
- A. Viết code ngay
- B. Phân rã bài toán thành phần nhỏ hơn ✅
- C. Tìm mẫu lặp lại
- D. Trừu tượng hóa dữ liệu

**9.** "Màu lông cụ thể của mèo không quan trọng khi vẽ mèo cơ bản" – điều này thể hiện kỹ năng:
- A. Algorithm Design
- B. Pattern Recognition
- C. Abstraction ✅
- D. Decomposition

**10.** Đâu là thứ tự đúng trong quy trình tư duy tính toán?
- A. Thuật toán → Phân rã → Nhận mẫu → Trừu tượng
- B. Phân rã → Nhận mẫu → Trừu tượng → Thiết kế thuật toán ✅
- C. Trừu tượng → Phân rã → Nhận mẫu → Thuật toán
- D. Nhận mẫu → Thuật toán → Phân rã → Trừu tượng

---

# PHẦN 2: LẬP TRÌNH HỖ TRỢ AI

## 2.1 AI là gì?

**Trí tuệ nhân tạo (AI)** là lĩnh vực khoa học máy tính tập trung tạo ra các hệ thống có thể thực hiện các tác vụ đòi hỏi trí thông minh của con người như: học hỏi, lập luận, giải quyết vấn đề, nhận thức và hiểu ngôn ngữ.

## 2.2 Prompt là gì?

**Prompt** là đầu vào hoặc hướng dẫn bạn đưa cho hệ thống AI để định hướng phản hồi của nó.

**Ví dụ Prompt tốt vs. xấu:**
```
Xấu: "code word count"

Tốt: "Write a Python function named count_words that takes a string 
      as input and returns the number of words in that string."
```

## 2.3 Kỹ thuật viết Prompt (Prompt Engineering)

| Thành phần | Mô tả | Ví dụ |
|-----------|-------|-------|
| **Role (Vai trò)** | Xác định vai trò AI | "Act as a Python expert..." |
| **Objective (Mục tiêu)** | Điều bạn muốn AI làm | "...explain the concept of for loops..." |
| **Rules (Quy tắc)** | Ràng buộc cần tuân theo | "...using simple examples only..." |
| **Audience (Đối tượng)** | Người đọc kết quả | "...for a programming beginner." |

## 2.4 Các loại Prompt

- **Zero-shot prompting**: Hỏi thẳng không ví dụ
- **One-shot/Few-shot prompting**: Cho 1 hoặc vài ví dụ trước
- **Role prompting**: Gán vai trò cho AI
- **Chain-of-Thought (CoT)**: Yêu cầu AI giải thích từng bước

## 2.5 Các công cụ AI phổ biến

| Công cụ | Đặc điểm | Khi nào dùng |
|---------|----------|-------------|
| **ChatGPT** | Giao diện chat, đa năng | Brainstorming, giải thích, tạo code mẫu |
| **GitHub Copilot** | Tích hợp trong editor (VS Code) | Viết code nhanh hơn trong dự án |

## 2.6 Những sai lầm phổ biến của AI

1. **Edge Cases**: Code chạy đúng với input thông thường nhưng lỗi với trường hợp đặc biệt (ví dụ: danh sách rỗng)
2. **Kém hiệu quả**: Giải pháp đúng về mặt chức năng nhưng chậm (O(n²) thay vì O(n))
3. **Lỗ hổng bảo mật**: Tái tạo các mẫu code có lỗ hổng bảo mật
4. **Hallucination (Ảo giác)**: AI "bịa" ra hàm/thư viện không tồn tại

## 2.7 Nguyên tắc sử dụng AI có trách nhiệm

1. **Transparency (Minh bạch)**: Luôn khai báo khi dùng AI
2. **Accountability (Trách nhiệm)**: Bạn chịu trách nhiệm về sản phẩm, không phải AI
3. **Understanding (Hiểu biết)**: Phải hiểu code trước khi dùng
4. **Academic Integrity (Liêm chính học thuật)**: Tuân theo quy định của khóa học

---

## 🔟 TRẮC NGHIỆM – PHẦN 2

**1.** Prompt trong bối cảnh AI là:
- A. Một loại ngôn ngữ lập trình
- B. Đầu vào hoặc hướng dẫn bạn đưa cho AI để định hướng phản hồi ✅
- C. Lỗi của AI
- D. Kết quả mà AI tạo ra

**2.** AI "hallucination" trong lập trình có nghĩa là:
- A. AI từ chối trả lời
- B. AI tạo ra thông tin sai hoặc bịa đặt một cách tự tin ✅
- C. AI chạy quá chậm
- D. AI không hiểu tiếng Anh

**3.** GitHub Copilot khác ChatGPT ở điểm nào?
- A. Copilot miễn phí còn ChatGPT trả phí
- B. Copilot tích hợp vào editor, tự động gợi ý code khi gõ ✅
- C. Copilot không thể viết code
- D. Copilot chỉ hỗ trợ JavaScript

**4.** "Act as a Python expert..." là ví dụ về thành phần nào trong Prompt Engineering?
- A. Objective
- B. Rules
- C. Role ✅
- D. Audience

**5.** Đâu là Prompt tốt hơn khi muốn AI viết hàm đếm từ?
- A. "code word count"
- B. "Write a Python function named count_words that takes a string and returns the number of words." ✅
- C. "count words please"
- D. "python words"

**6.** Khi nào KHÔNG nên dùng AI trong lập trình?
- A. Khi học khái niệm cơ bản và cần tự mình vật lộn với nó ✅
- B. Khi cần giải thích lỗi
- C. Khi muốn tạo code mẫu nhanh
- D. Khi cần brainstorm ý tưởng

**7.** Nguyên tắc "Accountability" trong sử dụng AI có trách nhiệm nghĩa là:
- A. Luôn khai báo khi dùng AI
- B. Bạn chịu trách nhiệm về sản phẩm của mình, không phải AI ✅
- C. Chỉ dùng AI có phí
- D. AI luôn đúng

**8.** Code AI tạo ra bị lỗi với danh sách rỗng là ví dụ của loại lỗi nào?
- A. Hallucination
- B. Lỗ hổng bảo mật
- C. Edge cases ✅
- D. Lỗi cú pháp

**9.** Chain-of-Thought (CoT) prompting là:
- A. Cho AI nhiều ví dụ
- B. Yêu cầu AI giải thích từng bước suy nghĩ ✅
- C. Gán vai trò cho AI
- D. Hỏi thẳng không ví dụ

**10.** Dấu hiệu nào cho thấy bạn đang phụ thuộc quá nhiều vào AI?
- A. Bạn hiểu rõ từng dòng code AI tạo ra
- B. Bạn copy-paste code AI mà không hiểu nó làm gì ✅
- C. Bạn dùng AI để kiểm tra code của mình
- D. Bạn hỏi AI giải thích khái niệm

---

# PHẦN 3: BIỂU THỨC, TOÁN TỬ & NHẬP/XUẤT

## 3.1 Biến (Variable)

**Biến** là tên được gán cho một giá trị, dùng để lưu trữ dữ liệu trong bộ nhớ.

```python
x = 5          # x là tên biến, 5 là giá trị
name = "Alice" # biến kiểu chuỗi
```

### Quy tắc đặt tên biến
- Chỉ chứa chữ cái, chữ số và dấu gạch dưới `_`
- **Không** bắt đầu bằng chữ số: `2var` ❌
- **Phân biệt hoa thường**: `myVar ≠ myvar`
- **Không** dùng từ khóa Python: `if`, `else`, `for`, `while`...

### Gán giá trị
```python
# Gán cơ bản
x = 5
y = 3.14
s = "Hello"

# Gán nhiều biến cùng lúc
a = b = c = 5           # cùng giá trị
x, y, z = 1, 2.5, "Py" # khác giá trị

# Dynamic Typing (kiểu thay đổi được)
x = 10           # int
x = "Now a string"  # str
```

## 3.2 Kiểu dữ liệu (Data Types)

```python
# Số nguyên
x = 10       # int

# Số thực
y = -2.5     # float

# Boolean
b = True     # bool (True / False)

# Chuỗi
s1 = 'Hello'
s2 = "World"
s3 = "It's a good day"

# Danh sách
lst = [1, 2, 3]
lst2 = ["it's", "a", "good", "day"]

# Bộ
t = ('Math', 8.4)

# Tập hợp
st = {'Math', 'English', 'Physics'}

# Từ điển
d = {'Math': 8.4, 'English': 9.0}

# None
n = None
```

### Kiểm tra và chuyển đổi kiểu
```python
type(x)        # kiểm tra kiểu → <class 'int'>
int("42")      # chuỗi → int
float("3.14")  # chuỗi → float
str(100)       # int → chuỗi
bool(0)        # → False
bool(1)        # → True
```

## 3.3 Biến cục bộ và toàn cục

```python
counter = 0  # Biến toàn cục (global)

def show():
    print(counter)  # Đọc biến toàn cục: OK

def bad_incr():
    counter = counter + 1  # LỖI! UnboundLocalError

def good_incr():
    global counter         # khai báo dùng biến toàn cục
    counter = counter + 1  # OK
```

## 3.4 Biểu thức (Expression)

**Biểu thức** là sự kết hợp của toán tử và toán hạng để tạo ra một giá trị.

```python
x = 3 + 5           # Biểu thức đơn giản
x = (3 * 7 + 2) * 0.1  # Biểu thức phức tạp
```

## 3.5 Các loại toán tử

### 1. Toán tử số học
```python
+   # Cộng:       3 + 2 = 5
-   # Trừ:        3 - 2 = 1
*   # Nhân:       3 * 2 = 6
/   # Chia:       7 / 2 = 3.5
//  # Chia nguyên: 7 // 2 = 3
%   # Chia dư:    7 % 2 = 1
**  # Lũy thừa:   2 ** 3 = 8
```

### 2. Toán tử so sánh
```python
<   # Nhỏ hơn
<=  # Nhỏ hơn hoặc bằng
>   # Lớn hơn
>=  # Lớn hơn hoặc bằng
==  # Bằng
!=  # Không bằng
```

⚠️ **So sánh số thực không dùng `==`:**
```python
# Sai:
0.1 + 0.2 == 0.3  # → False (do sai số)
# Đúng:
import math
math.isclose(0.1 + 0.2, 0.3)  # → True
```

### 3. Toán tử logic
```python
and  # VÀ: True and True → True
or   # HOẶC: True or False → True
not  # PHỦ ĐỊNH: not True → False
```

### 4. Toán tử gán
```python
=    # Gán:       x = 5
+=   # Cộng gán:  x += 3  ↔  x = x + 3
-=   # Trừ gán:   x -= 3  ↔  x = x - 3
*=   # Nhân gán:  x *= 3  ↔  x = x * 3
/=   # Chia gán:  x /= 3  ↔  x = x / 3
%=   # Chia dư gán
```

### 5. Toán tử thành viên
```python
in      # Kiểm tra thuộc: 'a' in ['a','b'] → True
not in  # Kiểm tra không thuộc
```

### 6. Toán tử bit
```python
&   # AND bit
|   # OR bit
^   # XOR bit
~   # NOT bit
<<  # Dịch trái
>>  # Dịch phải
```

### Thứ tự ưu tiên toán tử (cao → thấp)
```
**  →  ~, +, - (unary)  →  *, /, //, %  →  +, -  →  <<, >>  →  &  →  ^  →  |  →  ==, !=, <, >, <=, >=  →  not  →  and  →  or
```

## 3.6 Nhập/Xuất dữ liệu

### Hàm input()
```python
# Mặc định trả về string
name = input("Nhập tên: ")

# Ép kiểu khi nhập số
age = int(input("Nhập tuổi: "))
salary = float(input("Nhập lương: "))

# Nhập nhiều giá trị cùng lúc
x, y = input("Nhập x y: ").split()
x, y = int(x), int(y)
```

### Hàm print()
```python
# In cơ bản
print("Hello, World!")

# In nhiều giá trị
print("x =", x, "y =", y)

# f-string (khuyến nghị)
name = "Alice"
age = 20
print(f"Tên: {name}, Tuổi: {age}")
print(f"Bình phương của 5 là: {5**2}")

# .format()
print("Tên: {}, Tuổi: {}".format(name, age))
print("Tên: {0}, Tuổi: {1}".format(name, age))

# Tham số sep và end
print("a", "b", "c", sep="-")   # a-b-c
print("Hello", end=" ")          # không xuống dòng
print("World")                   # Hello World
```

---

## 🔟 TRẮC NGHIỆM – PHẦN 3

**1.** Kết quả của `type(3.14)` là:
- A. `<class 'int'>`
- B. `<class 'float'>` ✅
- C. `<class 'str'>`
- D. `<class 'double'>`

**2.** Biểu thức `7 // 2` cho kết quả:
- A. 3.5
- B. 3 ✅
- C. 1
- D. 2

**3.** Đâu là tên biến hợp lệ trong Python?
- A. `2var`
- B. `my-var`
- C. `my_var` ✅
- D. `for`

**4.** `input()` luôn trả về kiểu dữ liệu nào?
- A. int
- B. float
- C. str ✅
- D. bool

**5.** Để nhập số nguyên từ bàn phím, câu lệnh đúng là:
- A. `x = input("Nhập: ")`
- B. `x = int(input("Nhập: "))` ✅
- C. `x = integer(input("Nhập: "))`
- D. `x = input(int("Nhập: "))`

**6.** Kết quả của `0.1 + 0.2 == 0.3` trong Python là:
- A. True
- B. False ✅
- C. None
- D. Error

**7.** In ra `Hello-World` bằng cách dùng tham số `sep`, câu lệnh đúng là:
- A. `print("Hello", "World", sep="-")` ✅
- B. `print("Hello" + "World", sep="-")`
- C. `print("Hello-World")`
- D. `print("Hello", sep="-", "World")`

**8.** Đoạn code sau in ra gì?
```python
x = 5
x += 3
print(x)
```
- A. 5
- B. 3
- C. 8 ✅
- D. 53

**9.** Để gán cùng giá trị 0 cho ba biến a, b, c, cách ngắn nhất là:
- A. `a = 0; b = 0; c = 0`
- B. `a, b, c = 0, 0, 0`
- C. `a = b = c = 0` ✅
- D. `0 = a = b = c`

**10.** Kết quả của `10 % 3` là:
- A. 3
- B. 1 ✅
- C. 0
- D. 3.33

---

# PHẦN 4: CẤU TRÚC ĐIỀU KIỆN (IF/ELSE)

## 4.1 Câu lệnh if

```python
# Cú pháp
if <biểu_thức_boolean>:
    <câu_lệnh>
    ...

# Ví dụ
if x % 2 == 0:
    print('chẵn')
```

## 4.2 Câu lệnh if-else

```python
if <biểu_thức>:
    <câu_lệnh khi True>
else:
    <câu_lệnh khi False>

# Ví dụ
if x % 2 == 0:
    print('chẵn')
else:
    print('lẻ')
```

## 4.3 Câu lệnh if-elif-else

```python
if <biểu_thức_1>:
    <câu_lệnh>
elif <biểu_thức_2>:
    <câu_lệnh>
elif <biểu_thức_3>:
    <câu_lệnh>
else:
    <câu_lệnh>

# Ví dụ phân loại điểm
if score >= 90:
    print("Xuất sắc!")
elif score >= 70:
    print("Khá!")
elif score >= 50:
    print("Đạt.")
else:
    print("Không đạt.")
```

**Lưu ý quan trọng:**
- Số lượng `elif` không giới hạn
- `else` là tùy chọn
- Python kiểm tra điều kiện **theo thứ tự**; khi tìm thấy điều kiện đúng, bỏ qua tất cả phần còn lại

## 4.4 if vs if-elif (sự khác biệt quan trọng)

```python
x = 0

# Series of If – kiểm tra TẤT CẢ điều kiện
if x == 0:
    print("x is 0!")    # In ra
if x == 0:
    print("still 0!")   # Cũng in ra
if x == 0:
    print("even still 0") # Cũng in ra

# If-Elif – chỉ chạy NHÁNH ĐẦU TIÊN đúng
if x == 0:
    print("x is 0!")    # In ra
elif x == 0:
    print("still 0!")   # KHÔNG in ra (đã tìm thấy rồi)
elif x == 0:
    print("even still 0") # KHÔNG in ra
```

## 4.5 Câu lệnh if lồng nhau (Nested if)

```python
# Điều kiện phức tạp
if raining:
    if freezing:
        print('Mặc áo mưa chống lạnh.')
    else:
        print('Mang ô.')
else:
    if freezing:
        print('Mặc áo ấm!')
    else:
        print('Mặc áo len là đủ.')
```

## 4.6 Cấu trúc chương trình vs. Luồng chương trình

- **Cấu trúc (Structure)**: Cách code được trình bày trong file
- **Luồng (Flow / Control Flow)**: Thứ tự thực thi các dòng lệnh

```python
x = 10
if x % 2 == 0:
    print('chẵn')  # Xuất hiện trong cấu trúc
else:
    print('lẻ')    # Xuất hiện trong cấu trúc nhưng KHÔNG chạy khi x=10
```

## 4.7 Kỹ thuật Debug: Trace và Watch

```python
# TRACE: Theo dõi luồng chương trình
if x_score > y_score:
    print('>>> vào nhánh if')  # trace
    winner = "x"
else:
    print('>>> vào nhánh else')  # trace
    winner = "y"

# WATCH: Theo dõi giá trị biến
print('x_score =', x_score)  # watch
print('y_score =', y_score)  # watch
```

## 4.8 Kiểm thử Code Coverage

Để đảm bảo tất cả các nhánh đều được kiểm tra:
```python
# Cần ít nhất 4 test case cho:
if score >= 90:   → score = 95  (nhánh 1)
elif score >= 70: → score = 80  (nhánh 2)
elif score >= 50: → score = 60  (nhánh 3)
else:             → score = 40  (nhánh 4)
```

---

## 🔟 TRẮC NGHIỆM – PHẦN 4

**1.** Với `score = 75`, đoạn code sau in gì?
```python
if score >= 90:
    print("A")
elif score >= 70:
    print("B")
elif score >= 50:
    print("C")
else:
    print("F")
```
- A. A
- B. B ✅
- C. C
- D. F

**2.** Sự khác biệt giữa dùng nhiều `if` và dùng `if-elif` là:
- A. Không có sự khác biệt
- B. `if-elif` kiểm tra tất cả điều kiện, `if` chỉ kiểm tra một
- C. `if` kiểm tra tất cả điều kiện, `if-elif` chỉ chạy nhánh đầu tiên đúng ✅
- D. `if-elif` chạy nhanh hơn

**3.** Đoạn code `if` lồng nhau sau xử lý trường hợp `raining=True, freezing=False`:
```python
if raining:
    if freezing:
        print("Mặc áo mưa chống lạnh")
    else:
        print("Mang ô")
else:
    print("Trời đẹp")
```
- A. Mặc áo mưa chống lạnh
- B. Mang ô ✅
- C. Trời đẹp
- D. Không in gì

**4.** "Trace print" được dùng để:
- A. Xem giá trị của biến
- B. Theo dõi luồng thực thi chương trình ✅
- C. Tối ưu hóa code
- D. Kiểm tra kiểu dữ liệu

**5.** Để kiểm thử đủ code coverage cho cấu trúc `if/elif/else` có 3 nhánh, cần tối thiểu bao nhiêu test case?
- A. 1
- B. 2
- C. 3 ✅
- D. 6

**6.** Biểu thức boolean `(5 > 3) and (2 < 1)` cho kết quả:
- A. True
- B. False ✅
- C. None
- D. Error

**7.** Đâu là cú pháp `if-else` đúng trong Python?
- A. `if (x > 0) { print("dương") } else { print("âm") }`
- B. `if x > 0: print("dương") else: print("âm")`
- C.
  ```python
  if x > 0:
      print("dương")
  else:
      print("âm")
  ```
  ✅
- D. `if x > 0 then print("dương") end`

**8.** Biến được tạo bên trong khối `if` thì:
- A. Không tồn tại sau khi khối `if` kết thúc
- B. Vẫn tồn tại sau khối `if` nếu nhánh đó đã được thực thi ✅
- C. Trở thành biến toàn cục tự động
- D. Bị xóa ngay sau khi gán

**9.** "Watch print" được dùng để:
- A. Theo dõi luồng thực thi
- B. Xem giá trị của biến tại thời điểm nhất định ✅
- C. Đo thời gian chạy
- D. Kiểm tra cú pháp

**10.** Đoạn code sau in ra gì?
```python
x = 5
if x > 3:
    print("A")
if x > 4:
    print("B")
if x > 6:
    print("C")
```
- A. A
- B. A và B ✅
- C. A, B và C
- D. Không in gì

---

# PHẦN 5: VÒNG LẶP FOR

## 5.1 Vòng lặp for cơ bản

```python
# Cú pháp
for <biến> in <dãy>:
    <câu_lệnh>
    ...

# Duyệt qua danh sách
lst = [1, 2, 3, 4, 5]
for item in lst:
    print(item)

# Duyệt qua chuỗi
for char in "Hello":
    print(char)
```

## 5.2 Mẫu Accumulator (Biến tích lũy)

```python
# Tính tổng danh sách
def avg(lst):
    num = 0          # Khởi tạo accumulator
    for x in lst:
        num = num + x  # Cập nhật accumulator
    den = len(lst)
    return num / den

# Mẫu tổng quát
accumulator = <giá_trị_khởi_tạo>
for item in seq:
    accumulator = accumulator <toán_tử> item
# accumulator chứa kết quả cuối cùng
```

## 5.3 Hàm range()

```python
range(stop)        # 0 → stop-1
range(start, stop) # start → stop-1
range(start, stop, step)  # bước nhảy

# Ví dụ
list(range(5))          # [0, 1, 2, 3, 4]
list(range(1, 6))       # [1, 2, 3, 4, 5]
list(range(0, 10, 2))   # [0, 2, 4, 6, 8]
list(range(10, 0, -1))  # [10, 9, 8, ..., 1]
```

## 5.4 Duyệt qua chỉ số (Index)

```python
lst = [10, 20, 30]

# Duyệt qua phần tử (KHÔNG thể thay đổi lst)
for item in lst:
    item = item + 1  # Không thay đổi lst!

# Duyệt qua chỉ số (CÓ THỂ thay đổi lst)
for i in range(len(lst)):
    lst[i] = lst[i] + 1  # Thay đổi lst thành công!
```

## 5.5 enumerate()

```python
lst = ['a', 'b', 'c']
for i, item in enumerate(lst):
    print(i, item)
# Output:
# 0 a
# 1 b
# 2 c
```

## 5.6 Danh sách lồng nhau (Nested Lists)

```python
# Danh sách 2D
matrix = [[1, 2, 3],
           [4, 5, 6],
           [7, 8, 9]]

# Truy cập phần tử
matrix[0][0]  # → 1
matrix[2][1]  # → 8

# Duyệt qua 2D
for row in matrix:
    for cell in row:
        print(cell, end=" ")
    print()
```

## 5.7 Dữ liệu dạng bảng (Tabular Data)

```python
# Row-major (mỗi hàng là một list con)
table = [['Name', 'Score'],
         ['Alice', 95],
         ['Bob', 80]]

# Tính trung bình bảng số
def avg_tab(tab):
    total = 0
    count = 0
    for row in tab:
        for num in row:
            total += num
            count += 1
    return total / count

# Cộng 1 vào mọi phần tử
def add1_tab(tab):
    for r in range(len(tab)):
        for c in range(len(tab[r])):
            tab[r][c] += 1
```

---

## 🔟 TRẮC NGHIỆM – PHẦN 5

**1.** `list(range(2, 8, 2))` cho kết quả:
- A. [2, 4, 6, 8]
- B. [2, 4, 6] ✅
- C. [2, 3, 4, 5, 6, 7]
- D. [2, 8, 2]

**2.** Mẫu Accumulator thường bắt đầu bằng:
- A. Gán giá trị bất kỳ cho biến tích lũy
- B. Khởi tạo biến tích lũy với giá trị phù hợp (0 cho tổng, 1 cho tích...) ✅
- C. Không cần khởi tạo
- D. Sao chép danh sách gốc

**3.** Đâu là cách đúng để thay đổi từng phần tử trong danh sách `lst`?
- A. `for x in lst: x = x + 1`
- B. `for i in range(len(lst)): lst[i] = lst[i] + 1` ✅
- C. `for x in lst: lst.x = x + 1`
- D. `for x, i in lst: lst[i] = x + 1`

**4.** `enumerate(['a', 'b', 'c'])` tạo ra các bộ dữ liệu nào?
- A. [(1,'a'), (2,'b'), (3,'c')]
- B. [(0,'a'), (1,'b'), (2,'c')] ✅
- C. [('a',0), ('b',1), ('c',2)]
- D. ['a', 'b', 'c']

**5.** Đoạn code sau in ra gì?
```python
total = 0
for i in range(1, 5):
    total += i
print(total)
```
- A. 4
- B. 10 ✅
- C. 15
- D. 14

**6.** Truy cập phần tử hàng 1, cột 2 của `m = [[1,2,3],[4,5,6]]` là:
- A. `m[1][2]` → 6 ✅
- B. `m[2][1]` → Lỗi
- C. `m[1,2]`
- D. `m(1)(2)`

**7.** Khi dùng `for item in lst`, thay đổi `item = item + 1` bên trong vòng lặp:
- A. Thay đổi phần tử trong `lst`
- B. Không thay đổi `lst`, chỉ thay đổi biến cục bộ `item` ✅
- C. Gây ra lỗi
- D. Thêm phần tử mới vào `lst`

**8.** Để in dãy số `10, 8, 6, 4, 2`, dùng `range`:
- A. `range(10, 2, -2)` ✅
- B. `range(2, 10, 2)`
- C. `range(10, 0, -2)`
- D. `range(2, 10, -2)`

**9.** Đoạn code sau in bao nhiêu dòng?
```python
for i in range(3):
    for j in range(4):
        print(i, j)
```
- A. 3
- B. 4
- C. 7
- D. 12 ✅

**10.** `for char in 'aeiou': ...` – vòng lặp thực thi bao nhiêu lần?
- A. 4
- B. 5 ✅
- C. 6
- D. Tuỳ thuộc vào nội dung vòng lặp

---

# PHẦN 6: HÀM – ĐẶC TẢ – KIỂM THỬ

## 6.1 Tại sao dùng hàm?

- **Tổ chức code**: Nhóm các câu lệnh liên quan dưới một tên có ý nghĩa
- **Loại bỏ lặp**: Thay đổi một lần, áp dụng ở mọi nơi
- **Tái sử dụng**: Dùng lại hàm trong chương trình khác

## 6.2 Định nghĩa hàm

```python
def <tên_hàm>(<tham_số_1>, <tham_số_2>, ...):
    """Docstring mô tả hàm"""
    <câu_lệnh>
    return <giá_trị>

# Ví dụ
def inches_to_feet(inches):
    """Chuyển đổi inches sang feet.
    Tham số inches: số cần chuyển đổi (float/int)
    Trả về: giá trị tương ứng theo feet
    """
    return inches / 12
```

## 6.3 Gọi hàm

```python
result = inches_to_feet(65)  # Gọi hàm, truyền đối số
print(result)                 # Dùng kết quả trả về
```

## 6.4 Câu lệnh return

```python
def max_of_two(a, b):
    if a > b:
        return a    # Kết thúc hàm, trả về a
    return b        # Trả về b nếu không có return ở trên

# Hàm không có return → tự động trả về None
def greet(name):
    print("Xin chào,", name)   # Không có return
# greet("Alice") → None được trả về ngầm
```

## 6.5 Biến cục bộ và toàn cục trong hàm

```python
x = 10  # Biến toàn cục

def func():
    y = 5   # Biến cục bộ, chỉ tồn tại trong func()
    print(x)  # Đọc biến toàn cục: OK
    print(y)  # Đọc biến cục bộ: OK

# print(y)  # LỖI: y không tồn tại ngoài func()
```

## 6.6 Call Stack

```python
def func_b():
    print("func b")

def func_a():
    print("func a")
    func_b()

func_a()
# Call stack khi trong func_b:
# <func_b>  ← top
# <func_a>
# <main>    ← bottom
```

## 6.7 Module

```python
# Import module
import math
print(math.pi)         # 3.14159...
result = math.sqrt(25) # 5.0

# Import cụ thể
from math import sqrt, pi
print(sqrt(25))         # 5.0
print(pi)               # 3.14159...
```

**Tạo module riêng:**
```python
# File: uet_info.py
"""Module thông tin UET-VNU"""
university_name = "UET - VNU"

def get_address():
    """Trả về địa chỉ trường"""
    return "144 Xuân Thủy"
```

```python
# File: main.py
import uet_info
print(uet_info.university_name)  # UET - VNU
print(uet_info.get_address())    # 144 Xuân Thủy
```

## 6.8 Đặc tả hàm (Specification)

```python
import math

def circle_area(radius):
    """
    Trả về diện tích hình tròn với bán kính cho trước.

    Tham số:
        radius (float): Bán kính hình tròn, phải >= 0.

    Trả về:
        float: Diện tích hình tròn.
    """
    return math.pi * radius ** 2
```

## 6.9 Kiểm thử với assert

```python
assert <điều_kiện>, "Thông báo lỗi tùy chọn"

# Ví dụ
x = 10
assert x > 0, "x phải dương"  # OK, tiếp tục
assert x > 20, "x phải > 20"  # AssertionError!
```

## 6.10 Test-Driven Development (TDD)

```python
# 1. Viết đặc tả
# 2. Viết test TRƯỚC khi viết code
# test_fib.py
from fibonacci import fib

def test_first_two():
    assert fib(0) == 0
    assert fib(1) == 1

def test_small():
    assert fib(2) == 1
    assert fib(3) == 2
    assert fib(4) == 3

# 3. Viết code hàm
# fibonacci.py
def fib(n):
    if n == 0 or n == 1:
        return n
    return fib(n-1) + fib(n-2)

# 4. Chạy test → 5. Sửa cho đến khi pass
```

---

## 🔟 TRẮC NGHIỆM – PHẦN 6

**1.** Từ khóa `def` trong Python dùng để:
- A. Xác định một biến
- B. Định nghĩa một hàm ✅
- C. Import module
- D. Bắt đầu vòng lặp

**2.** Khi hàm không có câu lệnh `return`, nó trả về:
- A. 0
- B. ""
- C. None ✅
- D. False

**3.** Đâu là mục đích của docstring?
- A. Tăng tốc độ chương trình
- B. Mô tả hàm làm gì (dùng cho `help()`) ✅
- C. Khai báo kiểu dữ liệu
- D. Import thư viện

**4.** `assert x > 0, "x phải dương"` – khi `x = -5`, điều gì xảy ra?
- A. Chương trình tiếp tục bình thường
- B. In ra thông báo lỗi và tiếp tục
- C. Dừng chương trình với AssertionError ✅
- D. Gán x = 0

**5.** Trong TDD (Test-Driven Development), thứ tự đúng là:
- A. Viết code → viết test → sửa code
- B. Viết test → viết code → chạy test → sửa ✅
- C. Chạy test → viết code → viết test
- D. Viết đặc tả → viết code → viết test

**6.** `import math; math.sqrt(16)` trả về:
- A. 4
- B. 4.0 ✅
- C. "4"
- D. 16

**7.** Khi gọi `func_a()` và bên trong `func_a()` gọi `func_b()`, thứ tự trên call stack là:
- A. main → func_a → func_b (func_b ở trên cùng) ✅
- B. func_b → func_a → main
- C. main → func_b → func_a
- D. func_a → func_b → main

**8.** Biến cục bộ (local variable) trong hàm:
- A. Tồn tại trong suốt chương trình
- B. Chỉ tồn tại trong thời gian hàm đang thực thi ✅
- C. Có thể truy cập từ bên ngoài hàm
- D. Là biến toàn cục

**9.** Câu lệnh `from math import sqrt` cho phép:
- A. Import toàn bộ thư viện math
- B. Dùng `sqrt()` trực tiếp mà không cần `math.` ✅
- C. Chỉ dùng được trong hàm
- D. Tạo biến mới tên `sqrt`

**10.** Hàm có thể trả về nhiều giá trị bằng cách:
- A. Dùng nhiều câu lệnh `return`
- B. `return a, b` – trả về tuple ✅
- C. Không thể trả về nhiều giá trị
- D. Dùng `print()` thay cho `return`

---

# PHẦN 7: CẤU TRÚC DỮ LIỆU: LIST, TUPLE, DICTIONARY

## 7.1 List (Danh sách)

**List** là tập hợp có thứ tự, có thể thay đổi (mutable), chứa trong `[]`.

```python
# Tạo list
lst = [1, 2, 3, 4, 5]
mixed = [1, "hello", 3.14, True]
empty = []

# Truy cập (index bắt đầu từ 0)
lst[0]   # → 1  (phần tử đầu)
lst[-1]  # → 5  (phần tử cuối)

# Slicing
lst[1:3]  # → [2, 3]
lst[:2]   # → [1, 2]
lst[2:]   # → [3, 4, 5]
lst[::2]  # → [1, 3, 5] (bước 2)

# Độ dài
len(lst)  # → 5
```

### Các phương thức quan trọng của List

```python
lst = [3, 1, 4, 1, 5]

lst.append(9)        # Thêm cuối: [3, 1, 4, 1, 5, 9]
lst.insert(0, 10)    # Chèn vị trí 0: [10, 3, 1, 4, 1, 5, 9]
lst.remove(1)        # Xóa phần tử đầu tiên = 1
lst.pop()            # Xóa và trả về phần tử cuối
lst.pop(0)           # Xóa và trả về phần tử index 0
lst.sort()           # Sắp xếp tăng dần (in-place)
lst.sort(reverse=True)  # Giảm dần
lst.reverse()        # Đảo ngược
lst.index(4)         # Tìm index của 4
lst.count(1)         # Đếm số lần xuất hiện của 1
lst.extend([6, 7])   # Mở rộng với list khác
lst2 = lst.copy()    # Tạo bản sao

# Hàm built-in với list
sorted(lst)          # Trả về list mới đã sắp xếp
min(lst), max(lst)   # Giá trị nhỏ nhất/lớn nhất
sum(lst)             # Tổng các phần tử
```

## 7.2 Tuple (Bộ)

**Tuple** là tập hợp có thứ tự, **KHÔNG THỂ thay đổi** (immutable), chứa trong `()`.

```python
# Tạo tuple
point = (3, 4)
rgb = (255, 128, 0)
single = (1,)   # Tuple 1 phần tử phải có dấu phẩy!

# Truy cập (giống list)
point[0]  # → 3
point[1]  # → 4

# Tuple unpacking (giải nén)
x, y = point
print(x, y)  # 3 4

# Swap biến
a, b = 1, 2
a, b = b, a  # a=2, b=1

# Trả về nhiều giá trị từ hàm
def min_max(lst):
    return min(lst), max(lst)  # Trả về tuple

lo, hi = min_max([3, 1, 4, 1, 5])
```

### Tuple vs List

| Đặc điểm | List `[]` | Tuple `()` |
|----------|-----------|-----------|
| Cú pháp | `[1, 2, 3]` | `(1, 2, 3)` |
| Thay đổi được? | Có ✅ | Không ❌ |
| Kích thước | Biến đổi | Cố định |
| Dùng khi | Dữ liệu động | Dữ liệu cố định |

## 7.3 Dictionary (Từ điển)

**Dictionary** là tập hợp các cặp key–value, key phải là kiểu **immutable** và **duy nhất**.

```python
# Tạo dictionary
student = {'name': 'Alice', 'age': 20, 'gpa': 3.8}
empty_dict = {}

# Truy cập
student['name']        # → 'Alice'
student.get('age')     # → 20
student.get('height', 0)  # → 0 (default nếu key không tồn tại)

# Thêm/sửa
student['city'] = 'Hanoi'    # Thêm key mới
student['age'] = 21           # Sửa giá trị

# Xóa
del student['city']            # Xóa key
val = student.pop('age')       # Xóa và trả về giá trị
```

### Phương thức của Dictionary

```python
d = {'a': 1, 'b': 2, 'c': 3}

d.keys()    # dict_keys(['a', 'b', 'c'])
d.values()  # dict_values([1, 2, 3])
d.items()   # dict_items([('a', 1), ('b', 2), ('c', 3)])

len(d)           # 3
'a' in d         # True (kiểm tra KEY)
1 in d.values()  # True (kiểm tra VALUE)
```

### Duyệt qua Dictionary

```python
# Duyệt qua key (mặc định)
for key in d:
    print(key, d[key])

# Duyệt qua items
for key, val in d.items():
    print(f"{key}: {val}")

# Duyệt qua values
for val in d.values():
    print(val)
```

### Dictionary lồng nhau và làm Accumulator

```python
# Nested dict
school = {
    'class_A': {'Alice': 95, 'Bob': 80},
    'class_B': {'Charlie': 88}
}

# Dict làm accumulator (đếm ký tự)
def char_count(s):
    counts = {}
    for ch in s:
        if ch in counts:
            counts[ch] += 1
        else:
            counts[ch] = 1
    return counts

char_count('abba!')  # {'a': 2, 'b': 2, '!': 1}
```

## 7.4 So sánh List, Tuple, Dictionary

| Thuộc tính | List | Tuple | Dictionary |
|-----------|------|-------|-----------|
| Cú pháp | `[]` | `()` | `{key: val}` |
| Có thứ tự? | Có | Có | Có (Python 3.7+) |
| Thay đổi được? | Có | Không | Có |
| Truy cập bằng | Index | Index | Key |
| Cho phép trùng? | Có | Có | Key phải unique |

---

## 🔟 TRẮC NGHIỆM – PHẦN 7

**1.** `[1, 2, 3, 4, 5][1:3]` cho kết quả:
- A. `[1, 2, 3]`
- B. `[2, 3]` ✅
- C. `[2, 3, 4]`
- D. `[1, 3]`

**2.** Sự khác biệt chính giữa List và Tuple là:
- A. List dùng `[]`, Tuple dùng `()`
- B. List là mutable (thay đổi được), Tuple là immutable ✅
- C. List có thứ tự, Tuple không có
- D. Tuple nhanh hơn List

**3.** Để tạo tuple chỉ có một phần tử `5`, cú pháp đúng là:
- A. `(5)`
- B. `(5,)` ✅
- C. `[5]`
- D. `{5}`

**4.** `d = {'a': 1, 'b': 2}; d['c']` gây ra lỗi gì?
- A. IndexError
- B. KeyError ✅
- C. ValueError
- D. TypeError

**5.** Cách an toàn để lấy giá trị từ dict (tránh lỗi nếu key không tồn tại) là:
- A. `d[key]`
- B. `d.get(key, default)` ✅
- C. `d.find(key)`
- D. `d.fetch(key)`

**6.** `lst = [3, 1, 4]; lst.sort(); print(lst)` in ra:
- A. `[3, 1, 4]`
- B. `[1, 3, 4]` ✅
- C. `[4, 3, 1]`
- D. `None`

**7.** Để duyệt qua cả key và value của dict `d`, cú pháp đúng là:
- A. `for k in d: print(k, d[k])`
- B. `for k, v in d.items(): print(k, v)` ✅
- C. Cả A và B đúng ✅
- D. `for k, v in d: print(k, v)`

Đáp án đúng: **C** (cả hai đều đúng, nhưng B thường được ưa dùng hơn)

**8.** `x, y = (10, 20)` – sau lệnh này, `x` và `y` có giá trị:
- A. x=20, y=10
- B. x=10, y=20 ✅
- C. x=(10,20), y=không có
- D. Lỗi

**9.** Kết quả của `{'a': 1, 'b': 2, 'a': 3}` là:
- A. Lỗi (key trùng)
- B. `{'a': 1, 'b': 2, 'a': 3}`
- C. `{'a': 3, 'b': 2}` ✅ (key sau ghi đè key trước)
- D. `{'a': 1, 'b': 2}`

**10.** Đâu là key hợp lệ trong Dictionary?
- A. `[1, 2, 3]` (list)
- B. `{'a': 1}` (dict)
- C. `(1, 2)` (tuple) ✅
- D. Cả A, B, C

---

# PHẦN 8: ITERABLE VÀ SET

## 8.1 Iterable là gì?

**Iterable** là bất kỳ đối tượng nào hỗ trợ phép `iter()` và trả về một **iterator**.
**Iterator** là đối tượng có phương thức `next()` để lấy phần tử tiếp theo.

```python
lst = [1, 2, 3]
it = iter(lst)
print(next(it))  # 1
print(next(it))  # 2
print(next(it))  # 3
# next(it)       # → StopIteration
```

## 8.2 Sự khác biệt: Sequence vs. Iterable

| | Sequence (list, str...) | Iterable |
|-|------------------------|---------|
| Hỗ trợ | `len()` và indexing | `iter()` |
| Biết trước số lượng? | Có | Không |
| Truy cập ngẫu nhiên? | Có | Không |
| Ví dụ | list, str, tuple | list, dict, set, file |

## 8.3 Dictionary và vòng lặp for

```python
d = {'b': 2, 'a': 1}

# Duyệt qua keys (mặc định)
for key in d:
    print(key)

# Các phương thức iterable của dict:
d.keys()    # Iterable của keys
d.values()  # Iterable của values
d.items()   # Iterable của (key, value) tuples

# Chuyển thành list
list(d.keys())    # ['b', 'a']
list(d.values())  # [2, 1]
list(d.items())   # [('b', 2), ('a', 1)]
```

## 8.4 Set (Tập hợp)

**Set** là tập hợp các phần tử **duy nhất**, **không có thứ tự**.

```python
# Tạo set
s = {1, 2, 3}
s2 = set([1, 1, 2, 3])  # Tạo từ list → {1, 2, 3}
empty_set = set()        # set() – KHÔNG phải {} (đó là dict rỗng)

# Kiểm tra thành viên (O(1))
1 in s    # True
0 in s    # False

# Thêm/xóa phần tử
s.add(4)      # {1, 2, 3, 4}
s.add(1)      # Không thay đổi (1 đã có)
s.remove(2)   # {1, 3, 4} – lỗi nếu không có
s.discard(2)  # Không lỗi nếu không có

# Duyệt qua set
for item in s:
    print(item)
```

### Phép toán tập hợp

```python
a = {1, 2, 3, 4}
b = {3, 4, 5, 6}

a | b   # Hợp: {1, 2, 3, 4, 5, 6}
a & b   # Giao: {3, 4}
a - b   # Hiệu: {1, 2}
a ^ b   # Đối xứng: {1, 2, 5, 6}
```

### Tìm ký tự duy nhất

```python
def uniq_chars(s):
    """Trả về set các ký tự duy nhất trong chuỗi"""
    return set(s)

uniq_chars('couscous')  # {'c', 'o', 's', 'u'}
```

---

## 🔟 TRẮC NGHIỆM – PHẦN 8

**1.** Set khác List ở điểm gì?
- A. Set không có thứ tự và không cho phép phần tử trùng lặp ✅
- B. Set dùng `[]`, List dùng `{}`
- C. Set nhanh hơn List mọi trường hợp
- D. Set không thể duyệt qua

**2.** Tạo set rỗng bằng:
- A. `s = {}`  (sai – đây là dict rỗng)
- B. `s = set()` ✅
- C. `s = []`
- D. `s = ()`

**3.** `set([1, 1, 2, 3, 2])` cho kết quả:
- A. `[1, 2, 3]`
- B. `{1, 2, 3}` ✅
- C. `{1, 1, 2, 3, 2}`
- D. Lỗi

**4.** `{1, 2, 3} & {2, 3, 4}` (giao hai set) cho:
- A. `{1, 2, 3, 4}`
- B. `{2, 3}` ✅
- C. `{1, 4}`
- D. `{1, 2, 3, 2, 3, 4}`

**5.** Iterable khác Sequence ở điểm:
- A. Iterable hỗ trợ indexing
- B. Iterable không nhất thiết biết trước số phần tử và không hỗ trợ indexing ✅
- C. Iterable luôn chậm hơn Sequence
- D. Không có sự khác biệt

**6.** Sau `d = {'x': 1, 'y': 2}`, `list(d.items())` cho:
- A. `['x', 'y']`
- B. `[1, 2]`
- C. `[('x', 1), ('y', 2)]` ✅
- D. `[['x', 1], ['y', 2]]`

**7.** `next(iter([]))` gây ra:
- A. `None`
- B. `[]`
- C. `StopIteration` ✅
- D. `IndexError`

**8.** Cách hiệu quả nhất để kiểm tra phần tử có trong tập hợp không?
- A. Dùng `for` để duyệt qua
- B. Dùng toán tử `in` với set (O(1)) ✅
- C. Dùng `index()`
- D. Dùng `find()`

**9.** `{1, 2, 3} - {2, 3, 4}` cho:
- A. `{1, 4}`
- B. `{1}` ✅
- C. `{4}`
- D. `{}`

**10.** Dictionary là iterable vì:
- A. Nó hỗ trợ indexing bằng số
- B. Nó hỗ trợ phép `iter()` và trả về iterator trên các keys ✅
- C. Nó là một Sequence
- D. Nó có `len()`

---

# PHẦN 9: TÌM KIẾM VÀ SẮP XẾP

## 9.1 Tìm kiếm tuyến tính (Linear Search)

**Ý tưởng**: Kiểm tra từng phần tử từ đầu đến cuối.

```python
# Tìm 1 lần xuất hiện – O(n)
def linear_search(arr, value):
    for i in range(len(arr)):
        if arr[i] == value:
            return i   # Tìm thấy → trả về index
    return -1          # Không tìm thấy

# Tìm tất cả lần xuất hiện – O(n)
def linear_search_all(arr, value):
    indices = []
    for i in range(len(arr)):
        if arr[i] == value:
            indices.append(i)
    return indices  # Danh sách tất cả index
```

| Trường hợp | Độ phức tạp |
|-----------|------------|
| Tốt nhất (Best) | O(1) |
| Trung bình | O(n) |
| Tệ nhất (Worst) | O(n) |

## 9.2 Tìm kiếm nhị phân (Binary Search)

**Yêu cầu**: Mảng phải **đã được sắp xếp**.
**Ý tưởng**: Chia đôi không gian tìm kiếm mỗi bước.

```python
def binary_search(arr, value):
    left, right = 0, len(arr) - 1
    while left <= right:
        mid = (left + right) // 2
        if arr[mid] == value:
            return mid          # Tìm thấy
        elif arr[mid] < value:
            left = mid + 1      # Tìm nửa bên phải
        else:
            right = mid - 1     # Tìm nửa bên trái
    return -1                   # Không tìm thấy
```

| Trường hợp | Độ phức tạp |
|-----------|------------|
| Tốt nhất | O(1) |
| Trung bình | O(log n) |
| Tệ nhất | O(log n) |

## 9.3 So sánh Linear Search vs Binary Search

| | Linear Search | Binary Search |
|-|--------------|--------------|
| Yêu cầu | Mảng bất kỳ | Mảng đã sắp xếp |
| Độ phức tạp TB | O(n) | O(log n) |
| Cài đặt | Đơn giản | Phức tạp hơn |
| Phù hợp | Dữ liệu nhỏ, chưa sắp xếp | Dữ liệu lớn, đã sắp xếp |

## 9.4 Sắp xếp nổi bọt (Bubble Sort)

**Ý tưởng**: Liên tục hoán đổi các phần tử kề nhau nếu sai thứ tự.

```python
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        swapped = False
        for j in range(0, n - i - 1):
            if arr[j] > arr[j + 1]:
                arr[j], arr[j + 1] = arr[j + 1], arr[j]
                swapped = True
        if not swapped:
            break  # Đã sắp xếp xong sớm
```
- **Độ phức tạp**: O(n²)

## 9.5 Sắp xếp chọn (Selection Sort)

**Ý tưởng**: Mỗi lần tìm phần tử nhỏ nhất trong phần chưa sắp xếp và đưa về đầu.

```python
def selection_sort(arr):
    n = len(arr)
    for i in range(n):
        min_idx = i
        for j in range(i + 1, n):
            if arr[j] < arr[min_idx]:
                min_idx = j
        arr[i], arr[min_idx] = arr[min_idx], arr[i]
```
- **Độ phức tạp**: O(n²)

## 9.6 Sắp xếp chèn (Insertion Sort)

**Ý tưởng**: Chèn từng phần tử vào đúng vị trí trong phần đã sắp xếp.

```python
def insertion_sort(arr):
    for i in range(1, len(arr)):
        key = arr[i]
        j = i - 1
        while j >= 0 and arr[j] > key:
            arr[j + 1] = arr[j]
            j -= 1
        arr[j + 1] = key
```
- **Độ phức tạp**: O(n²)

## 9.7 Sắp xếp trộn (Merge Sort)

**Ý tưởng**: Chia đôi → sắp xếp đệ quy từng nửa → trộn lại.

```python
def merge(left, right):
    res = []
    i = j = 0
    while i < len(left) and j < len(right):
        if left[i] < right[j]:
            res.append(left[i]); i += 1
        else:
            res.append(right[j]); j += 1
    res.extend(left[i:])
    res.extend(right[j:])
    return res

def merge_sort(arr):
    if len(arr) <= 1:
        return arr
    mid = len(arr) // 2
    left = merge_sort(arr[:mid])
    right = merge_sort(arr[mid:])
    return merge(left, right)
```
- **Độ phức tạp**: O(n log n)

## 9.8 Sắp xếp nhanh (Quick Sort)

**Ý tưởng**: Chọn pivot, phân vùng, đệ quy trên hai phần.

```python
def partition(arr, low, high):
    pivot = arr[high]
    i = low - 1
    for j in range(low, high):
        if arr[j] <= pivot:
            i += 1
            arr[i], arr[j] = arr[j], arr[i]
    arr[i + 1], arr[high] = arr[high], arr[i + 1]
    return i + 1

def quick_sort(arr, low, high):
    if low < high:
        pi = partition(arr, low, high)
        quick_sort(arr, low, pi - 1)
        quick_sort(arr, pi + 1, high)
```
- **Độ phức tạp TB**: O(n log n), Worst case: O(n²)

## 9.9 So sánh các thuật toán sắp xếp

| Thuật toán | Worst | Space | Stable? |
|-----------|-------|-------|---------|
| Bubble Sort | O(n²) | O(1) | Có |
| Selection Sort | O(n²) | O(1) | Không |
| Insertion Sort | O(n²) | O(1) | Có |
| Merge Sort | O(n log n) | O(n) | Có |
| Quick Sort | O(n²) | O(log n) | Không |

---

## 🔟 TRẮC NGHIỆM – PHẦN 9

**1.** Linear Search có độ phức tạp trường hợp tệ nhất là:
- A. O(1)
- B. O(log n)
- C. O(n) ✅
- D. O(n²)

**2.** Binary Search yêu cầu:
- A. Mảng có phần tử duy nhất
- B. Mảng đã được sắp xếp ✅
- C. Mảng có kích thước cố định
- D. Mảng chứa số nguyên

**3.** Trong Binary Search với `arr = [11, 14, 25, 30, 40]` và `value = 25`, phần tử đầu tiên được so sánh là:
- A. 11
- B. 25
- C. 30 (phần tử giữa, index 2) ✅
- D. 40

**4.** Thuật toán sắp xếp nào có độ phức tạp O(n log n) trong mọi trường hợp?
- A. Bubble Sort
- B. Selection Sort
- C. Merge Sort ✅
- D. Quick Sort (worst case O(n²))

**5.** Bubble Sort với điều kiện dừng sớm (`if not swapped: break`) hữu ích khi:
- A. Mảng hoàn toàn ngẫu nhiên
- B. Mảng đã gần được sắp xếp ✅
- C. Mảng rất lớn
- D. Mảng chứa số âm

**6.** Đặc điểm của Selection Sort là:
- A. Luôn nhanh nhất
- B. Mỗi lần tìm phần tử nhỏ nhất trong phần chưa xét và đặt vào đầu ✅
- C. Ổn định (stable)
- D. Không cần hoán đổi

**7.** Merge Sort hoạt động theo nguyên lý:
- A. Hoán đổi các phần tử kề nhau
- B. Chọn pivot và phân vùng
- C. Chia đôi, sắp xếp đệ quy, trộn lại ✅
- D. Chèn từng phần tử vào đúng vị trí

**8.** Thuật toán nào phù hợp nhất với dữ liệu **gần như đã sắp xếp**?
- A. Merge Sort
- B. Quick Sort
- C. Insertion Sort ✅
- D. Bubble Sort

**9.** Quick Sort chọn pivot là phần tử cuối. Với `[4, 6, 5, 9, 10, 7]`, pivot đầu tiên là:
- A. 4
- B. 9
- C. 7 ✅
- D. 10

**10.** Thuật toán sắp xếp "stable" có nghĩa là:
- A. Không bao giờ bị lỗi
- B. Các phần tử có giá trị bằng nhau giữ nguyên thứ tự tương đối ✅
- C. Luôn có độ phức tạp O(n log n)
- D. Không cần bộ nhớ thêm

---

# PHẦN 10: CLASS, METHOD, SUBCLASS

## 10.1 Class là gì?

**Class** là bản thiết kế (blueprint) cho các **object**. Object là instance (thể hiện) của class.

```python
# Lớp đơn giản nhất
class Point3:
    pass

p = Point3()  # Tạo object
p.x = 2       # Gán thuộc tính
p.y = 3
p.z = 5
```

## 10.2 Hàm khởi tạo __init__

```python
class Point3:
    def __init__(self, x_val, y_val, z_val):
        self.x = x_val  # self = object hiện tại
        self.y = y_val
        self.z = z_val

# Tạo object
p1 = Point3(2, 3, 5)
print(p1.x)  # 2
```

**Giao thức tạo object:**
1. Python tạo object mới trong bộ nhớ
2. Gọi `__init__` với object mới làm tham số `self`
3. Trả về object

## 10.3 Phương thức (Methods)

```python
class Counter:
    def __init__(self):
        self.count = 0   # Thuộc tính

    def curr_count(self):
        return self.count

    def incr(self):
        self.count += 1

    def reset(self):
        self.count = 0

# Dùng
ctr = Counter()
ctr.incr()
ctr.incr()
print(ctr.curr_count())  # 2
```

**Cú pháp gọi method:**
```python
obj.method(args)
# Tương đương với:
ClassName.method(obj, args)
```

## 10.4 Biểu diễn đối tượng dưới dạng chuỗi

```python
class Point3:
    def __init__(self, x, y, z):
        self.x, self.y, self.z = x, y, z

    def __repr__(self):
        """Dùng trong interactive mode (dành cho lập trình viên)"""
        return f'Point3({self.x}, {self.y}, {self.z})'

    def __str__(self):
        """Dùng với str() và print() (dành cho người dùng)"""
        return f'({self.x}, {self.y}, {self.z})'

p = Point3(1, 2, 3)
print(repr(p))  # Point3(1, 2, 3)
print(str(p))   # (1, 2, 3)
print(p)        # (1, 2, 3)
```

## 10.5 Phương thức với nhiều tham số

```python
class Point3:
    def reflect(self):
        """Phản chiếu qua gốc tọa độ"""
        self.x = -self.x
        self.y = -self.y
        self.z = -self.z

    def scale(self, factor):
        """Nhân tọa độ với factor"""
        self.x *= factor
        self.y *= factor
        self.z *= factor

    def distance(self, other):
        """Khoảng cách Euclidean đến point khác"""
        import math
        return math.sqrt((other.x - self.x)**2 +
                         (other.y - self.y)**2 +
                         (other.z - self.z)**2)
```

## 10.6 Kế thừa (Inheritance)

```python
# Lớp cha (superclass)
class Account:
    def __init__(self, owner, number):
        self._owner = owner
        self._number = number
        self._balance = 0.0

    def deposit(self, amount):
        self._balance += amount

    def print_statement(self):
        print(f'Owner: {self._owner}')
        print(f'Balance: {self._balance}')

# Lớp con (subclass) kế thừa từ Account
class InterestAccount(Account):
    def add_interest(self, pct_rate):
        interest = self._balance * pct_rate
        self.deposit(interest)  # Gọi phương thức của cha

# Dùng
acct = InterestAccount('Alice', '123')
acct.deposit(1000)
acct.add_interest(0.05)
acct.print_statement()
```

**Quy tắc tìm phương thức (Bottom-up rule):**
Tìm từ lớp con → lên lớp cha → lên ông → ... → `object`

## 10.7 super() và ghi đè phương thức

```python
class CreditAccount(Account):
    def __init__(self, owner, number, limit):
        super().__init__(owner, number)  # Gọi __init__ của cha
        self._limit = limit

    def print_statement(self):  # Ghi đè (override) phương thức cha
        super().print_statement()  # Gọi version của cha
        print(f'Credit Limit: {self._limit}')
```

## 10.8 isinstance() và type()

```python
acct = InterestAccount('Alice', '123')

isinstance(acct, InterestAccount)  # True
isinstance(acct, Account)          # True (kế thừa)
isinstance(acct, object)           # True (mọi thứ)

type(acct) == InterestAccount      # True
type(acct) == Account              # False
```

## 10.9 Toán tử == và __eq__

```python
# Mặc định: == so sánh địa chỉ bộ nhớ (như is)
Point3(0,0,0) == Point3(0,0,0)  # False (2 object khác nhau)

# Override __eq__ để so sánh nội dung
class Point3:
    def __eq__(self, other):
        return (type(other) == Point3 and
                self.x == other.x and
                self.y == other.y and
                self.z == other.z)

Point3(0,0,0) == Point3(0,0,0)  # True ✅
```

---

## 🔟 TRẮC NGHIỆM – PHẦN 10

**1.** `__init__` trong Python là:
- A. Hàm để xóa object
- B. Phương thức khởi tạo, được gọi khi tạo object mới ✅
- C. Hàm main của chương trình
- D. Phương thức in đối tượng

**2.** Tham số `self` trong method là:
- A. Từ khóa bắt buộc, không thể đổi tên
- B. Tham chiếu đến object đang gọi method ✅
- C. Tham số tùy chọn
- D. Biến toàn cục

**3.** Khi gọi `p.scale(2)`, Python thực thi tương đương với:
- A. `scale(2)`
- B. `Point3.scale(2)`
- C. `Point3.scale(p, 2)` ✅
- D. `p.scale(p, 2)`

**4.** `__repr__` và `__str__` khác nhau ở điểm:
- A. `__repr__` dành cho lập trình viên, `__str__` dành cho người dùng cuối ✅
- B. `__repr__` nhanh hơn `__str__`
- C. `__str__` là bắt buộc, `__repr__` tùy chọn
- D. Không có sự khác biệt

**5.** Subclass kế thừa từ superclass nghĩa là:
- A. Subclass sao chép code của superclass
- B. Subclass có thể dùng các method của superclass ✅
- C. Superclass phụ thuộc vào subclass
- D. Subclass không thể định nghĩa method mới

**6.** `super().__init__(...)` trong __init__ của subclass dùng để:
- A. Tạo một object mới
- B. Gọi phương thức `__init__` của superclass để khởi tạo phần kế thừa ✅
- C. Xóa object hiện tại
- D. Import superclass

**7.** `isinstance(obj, SomeClass)` trả về True khi:
- A. `type(obj) == SomeClass` (chính xác)
- B. `obj` là instance của `SomeClass` hoặc bất kỳ subclass nào của nó ✅
- C. `obj` có method giống `SomeClass`
- D. `obj` và `SomeClass` ở cùng module

**8.** Ghi đè (Override) phương thức có nghĩa là:
- A. Xóa phương thức của superclass
- B. Định nghĩa lại phương thức trong subclass, ưu tiên hơn version của superclass ✅
- C. Gọi phương thức của superclass
- D. Copy phương thức từ superclass

**9.** Mặc định, `Point3(0,0,0) == Point3(0,0,0)` trả về:
- A. True
- B. False ✅ (so sánh địa chỉ bộ nhớ)
- C. None
- D. Error

**10.** Để mọi class đều có thể so sánh bằng `==` theo nội dung, ta cần:
- A. Override `__compare__`
- B. Override `__eq__` ✅
- C. Override `__str__`
- D. Dùng `is` thay vì `==`

---

# PHẦN 11: ĐỆ QUY (RECURSION)

## 11.1 Đệ quy là gì?

**Đệ quy** là kỹ thuật lập trình trong đó hàm tự gọi chính nó.

```python
def blast_off(n):
    """In đếm ngược từ n về 0"""
    if n == 0:          # Base case (trường hợp cơ sở)
        print('BLAST OFF!')
    else:               # Recursive case (trường hợp đệ quy)
        print(n)
        blast_off(n - 1)  # Gọi đệ quy

blast_off(3)
# Output: 3 → 2 → 1 → BLAST OFF!
```

## 11.2 Hai thành phần của hàm đệ quy

1. **Base case (Trường hợp cơ sở)**: Không gọi đệ quy, tính được trực tiếp
2. **Recursive case (Trường hợp đệ quy)**: Gọi chính nó với input nhỏ hơn

## 11.3 Giai thừa (Factorial)

```python
# Đệ quy: n! = n × (n-1)!, 0! = 1
def factorial_rec(n):
    if n == 0:
        return 1            # Base case
    else:
        return n * factorial_rec(n - 1)  # Recursive case

# Vòng lặp: n! = 1 × 2 × ... × n
def factorial_iter(n):
    product = 1
    for i in range(1, n + 1):
        product *= i
    return product

factorial_rec(5)  # 5 × 4 × 3 × 2 × 1 = 120
```

## 11.4 Dãy Fibonacci

```python
# Đệ quy (dễ viết, nhưng chậm – nhiều gọi trùng lặp)
def fibo_rec(n):
    if n == 0 or n == 1:
        return n           # Base case: F(0)=0, F(1)=1
    return fibo_rec(n-1) + fibo_rec(n-2)

# Vòng lặp (hiệu quả hơn)
def fibo_iter(n):
    if n == 0 or n == 1:
        return n
    a, b = 0, 1
    for i in range(2, n + 1):
        a, b = b, a + b
    return b
```

## 11.5 Đệ quy vô hạn (Infinite Recursion)

```python
# Lỗi: không có base case
def bad_func(n):
    print(n)
    bad_func(n - 1)  # → RecursionError: maximum recursion depth exceeded

# Lỗi: bước đệ quy sai
def bad_blast(n):
    if n == 0:
        print('BLAST OFF!')
    else:
        print(n)
        bad_blast(n)  # BUG: phải là n-1
```

## 11.6 Đệ quy trên dữ liệu lồng nhau

```python
# In outline lồng nhau ở độ sâu bất kỳ
def print_outline(outline, level=0):
    for item in outline:
        if isinstance(item, list):
            print_outline(item, level + 1)  # Recursive case
        else:
            print(' ' * 4 * level + item)  # Base case

outline = ['Intro', ['Part 1', ['Detail 1.1', 'Detail 1.2'], 'Part 2'], 'End']
print_outline(outline)
```

## 11.7 Mẫu lập trình đệ quy

```
Goal: Giải bài toán P trên dữ liệu data

1. Phân rã: data → piece_1, piece_2, ..., piece_n
2. Base case: Nếu piece đủ nhỏ → giải trực tiếp
3. Recursive case: Giải P(piece) → kết hợp để có đáp án
```

---

## 🔟 TRẮC NGHIỆM – PHẦN 11

**1.** Đệ quy khác vòng lặp for ở điểm:
- A. Đệ quy nhanh hơn for
- B. Đệ quy mạnh hơn for, có thể xử lý dữ liệu lồng nhau độ sâu bất kỳ ✅
- C. Đệ quy chỉ dùng cho số
- D. For không thể thay thế đệ quy

**2.** "Base case" trong đệ quy là:
- A. Trường hợp gọi lại chính hàm
- B. Trường hợp không gọi đệ quy, tính được trực tiếp ✅
- C. Trường hợp đầu vào lớn nhất
- D. Trường hợp đầu vào bằng 0

**3.** Kết quả của `factorial_rec(4)` là:
- A. 4
- B. 12
- C. 24 ✅
- D. 16

**4.** Hàm đệ quy bị `RecursionError` khi:
- A. Đầu vào quá lớn
- B. Không có base case hoặc không tiến đến base case → gọi đệ quy vô hạn ✅
- C. Hàm quá dài
- D. Dùng biến toàn cục

**5.** `fibo_rec(5)` cho kết quả:
- A. 3
- B. 5 ✅
- C. 8
- D. 4

**6.** Đệ quy tương đương về sức mạnh với:
- A. Vòng lặp for
- B. Vòng lặp while ✅
- C. Câu lệnh if-else
- D. Danh sách

**7.** Hàm sau tính gì?
```python
def mystery(n):
    if n == 0:
        return 0
    return n + mystery(n - 1)
```
- A. n!
- B. Tổng từ 0 đến n: 0+1+...+n ✅
- C. 2^n
- D. Fibonacci thứ n

**8.** Lý do `fibo_rec` chậm hơn `fibo_iter` là:
- A. Đệ quy chậm hơn vòng lặp
- B. `fibo_rec` gọi đệ quy nhiều lần với cùng giá trị n (gọi trùng lặp) ✅
- C. `fibo_iter` dùng phần cứng tốt hơn
- D. Không có sự khác biệt đáng kể

**9.** Đệ quy NHẤT THIẾT phải dùng khi:
- A. Dữ liệu là số nguyên
- B. Xử lý dữ liệu lồng nhau với độ sâu không biết trước ✅
- C. Bài toán cần vòng lặp
- D. Không bao giờ nhất thiết

**10.** Với đệ quy, "Leap of Faith" có nghĩa là:
- A. Nhảy ra khỏi vòng lặp
- B. Tin rằng lời gọi đệ quy sẽ hoạt động đúng nếu precondition được đảm bảo ✅
- C. Bỏ qua base case
- D. Gọi đệ quy không giới hạn

---

# PHẦN 12: VÒNG LẶP WHILE

## 12.1 Vòng lặp while cơ bản

```python
# Cú pháp
while <điều_kiện>:
    <câu_lệnh>
    ...

# Ví dụ: Đoán số
still_playing = True
while still_playing:
    guess = input('Đoán số: ')
    if guess == '42':
        print('Đúng rồi!')
        still_playing = False
    else:
        print('Sai, thử lại.')
```

## 12.2 Sự khác biệt: for vs while

| | `for` | `while` |
|-|-------|---------|
| Dùng khi | Biết trước số lần lặp | Không biết trước số lần lặp |
| Điều kiện | Duyệt qua dãy | Điều kiện boolean |
| Nguy cơ | Ít | Vòng lặp vô hạn |

## 12.3 Bốn câu hỏi thiết kế while-loop

1. **Q1: Có bắt đầu đúng không?** — Các biến phải được khởi tạo đúng
2. **Q2: Có duy trì quan hệ đúng không?** — Cập nhật các biến mỗi vòng
3. **Q3: Có tiến về đích không?** — Mỗi lần lặp phải tiến gần điều kiện dừng
4. **Q4: Có dừng đúng không?** — Khi dừng phải đạt mục tiêu

## 12.4 Ví dụ vòng lặp while

```python
# Ví dụ 1: Tung xúc xắc cho đến khi được mặt đôi (Snake Eyes)
import random

def roll():
    return random.randint(1, 6)

def snake_eyes():
    count = 0
    while True:
        r1, r2 = roll(), roll()
        count += 1
        if r1 == 1 and r2 == 1:
            print(f'Snake Eyes! Sau {count} lần tung.')
            break

# Ví dụ 2: Tính toán tài chính
def double_investment(initial, rate_pct):
    amount = initial
    period = 0
    while amount < 2 * initial:
        amount = (1 + rate_pct / 100) * amount
        period += 1
    print(f'Sau {period} kỳ: ${amount:.2f}')

# Ví dụ 3: Dãy Syracuse
def syr(start):
    x = start
    lst = []
    while x != 1:
        lst.append(x)
        if x % 2 == 0:
            x = x // 2      # f(n) = n/2 nếu n chẵn
        else:
            x = 3 * x + 1   # f(n) = 3n+1 nếu n lẻ
    lst.append(x)
    return lst
```

## 12.5 Câu lệnh break

```python
# break: thoát khỏi vòng lặp ngay lập tức
while True:
    x = input('Nhập (quit để thoát): ')
    if x == 'quit':
        break
    print(x)
```

## 12.6 Vòng lặp vô hạn

```python
# Vòng lặp vô hạn chủ ý
while True:
    x = 0
    print(x)
    x += 1
# → Nhấn Ctrl+C để dừng

# Vòng lặp vô hạn ngoài ý muốn – lỗi phổ biến
n = 5
while n > 0:
    print(n)
    # Quên n -= 1 → vòng lặp mãi!
```

## 12.7 Chuyển for sang while

```python
# for x in iterable: body
# Tương đương:
iterator = iter(iterable)
while True:
    try:
        x = next(iterator)
    except StopIteration:
        break
    <body>
```

---

## 🔟 TRẮC NGHIỆM – PHẦN 12

**1.** Khi nào nên dùng `while` thay vì `for`?
- A. Khi biết trước số lần lặp
- B. Khi không biết trước số lần lặp và phụ thuộc điều kiện ✅
- C. Khi duyệt qua list
- D. Khi gọi hàm đệ quy

**2.** "Q3: Does it make progress?" trong thiết kế while-loop có nghĩa là:
- A. Vòng lặp phải nhanh
- B. Mỗi lần lặp phải tiến gần hơn đến điều kiện dừng ✅
- C. Không được có biến cục bộ
- D. Phải có câu lệnh print

**3.** Đoạn code sau in gì?
```python
a = 8; b = 12
while a != b:
    if a > b:
        a = a - b
    else:
        b = b - a
print(a)
```
- A. 8
- B. 12
- C. 4 ✅
- D. 0

**4.** `while True:` với `break` bên trong thường dùng khi:
- A. Muốn vòng lặp chạy ít nhất một lần hoặc điều kiện dừng phức tạp ✅
- B. Không biết điều kiện
- C. Muốn vòng lặp chạy 10 lần
- D. Không bao giờ nên dùng

**5.** Để dừng một vòng lặp vô hạn đang chạy trong terminal:
- A. Nhấn Enter
- B. Nhấn Ctrl+C ✅
- C. Nhấn Ctrl+Z
- D. Nhấn Ctrl+Break

**6.** Vòng lặp while sau có vấn đề gì?
```python
n = 10
while n > 0:
    print(n)
```
- A. Không có vấn đề
- B. Vòng lặp vô hạn vì `n` không bao giờ thay đổi ✅
- C. Lỗi cú pháp
- D. `n` phải là float

**7.** Dãy Syracuse `syr(6)` bắt đầu với x=6 (chẵn), bước đầu tiên tính:
- A. 3×6+1 = 19
- B. 6/2 = 3 ✅
- C. 6-1 = 5
- D. 6+1 = 7

**8.** `break` trong vòng lặp lồng nhau:
- A. Thoát khỏi tất cả vòng lặp
- B. Thoát khỏi vòng lặp trong cùng ✅
- C. Thoát khỏi vòng lặp ngoài cùng
- D. Dừng toàn bộ chương trình

**9.** While-loop mạnh hơn for-loop vì:
- A. While chạy nhanh hơn
- B. While có thể thực hiện tất cả những gì for làm được và hơn thế ✅
- C. While ít lỗi hơn
- D. While dùng ít bộ nhớ hơn

**10.** Câu lệnh nào sau đây là vòng lặp while đúng?
- A. `while x > 0 do: print(x)`
- B. `while (x > 0): print(x); x -= 1`
- C.
  ```python
  while x > 0:
      print(x)
      x -= 1
  ```
  ✅
- D. `while x > 0 then: print(x)`

---

# PHẦN 13: EXCEPTION VÀ DEBUGGING

## 13.1 Lỗi cú pháp (Syntax Error)

```python
# Lỗi cú pháp – bị phát hiện TRƯỚC khi chạy
while True
    print("Hello")
# SyntaxError: expected ':'
```

## 13.2 Exception (Ngoại lệ)

**Exception** là lỗi xảy ra **trong quá trình thực thi** chương trình.

| Exception | Nguyên nhân |
|-----------|-------------|
| `ZeroDivisionError` | Chia cho 0 |
| `IndexError` | Chỉ số ngoài phạm vi |
| `ValueError` | Giá trị không hợp lệ |
| `TypeError` | Sai kiểu dữ liệu |
| `FileNotFoundError` | File không tồn tại |
| `KeyError` | Key không có trong dict |
| `NameError` | Biến chưa được định nghĩa |

## 13.3 Xử lý exception với try-except

```python
# Cú pháp cơ bản
try:
    <câu_lệnh_có_thể_lỗi>
except:
    <xử_lý_khi_lỗi>

# Ví dụ
try:
    num = int(input('Nhập số: '))
    print('Bình phương:', num ** 2)
except ValueError:
    print('Lỗi: Vui lòng nhập số nguyên.')
```

```python
# Nhiều loại exception
try:
    x = int(input('x: '))
    y = int(input('y: '))
    print(x / y)
except ValueError:
    print('Phải nhập số nguyên')
except ZeroDivisionError:
    print('Không chia được cho 0')
except:
    print('Lỗi không xác định')
```

## 13.4 finally – Dọn dẹp sau khi kết thúc

```python
def divide(a, b):
    try:
        result = a / b
        print(f'Kết quả: {result}')
    except ZeroDivisionError:
        print('Lỗi: Chia cho 0!')
    finally:
        print('Đã hoàn thành (dù có lỗi hay không)')

# finally LUÔN chạy – dùng để đóng file, giải phóng tài nguyên
```

## 13.5 Exception lan truyền (Propagation)

```python
def str_to_int(s):
    return int(s)  # Có thể raise ValueError

def func1():
    try:
        num = str_to_int('apple')  # ValueError ở đây
    except IOError:               # KHÔNG khớp với ValueError
        print('IO Error')
    # ValueError không được xử lý → lan truyền lên trên → chương trình crash

func1()  # Crash với ValueError
```

## 13.6 raise – Tự raise exception

```python
def check_password(pwd):
    if len(pwd) < 6:
        raise ValueError("Mật khẩu phải có ít nhất 6 ký tự")
    if pwd.isalpha() or pwd.isdigit():
        raise ValueError("Mật khẩu phải có cả chữ và số")
    print("Mật khẩu hợp lệ!")

try:
    check_password("abc12")
except ValueError as e:
    print(f'Mật khẩu không hợp lệ: {e}')
```

## 13.7 Assertion

```python
# Cú pháp
assert <điều_kiện>, "Thông báo lỗi"

# Ví dụ kiểm tra precondition
def greet(name):
    assert isinstance(name, str), \
        f"name phải là str, nhưng {name} không phải"
    print("Xin chào,", name)

greet("Alice")  # OK
greet(42)       # AssertionError: name phải là str...
```

## 13.8 Debugging (Gỡ lỗi)

### Dùng print để debug

```python
def last_name_first(full_name):
    print(f'DEBUG: full_name = {repr(full_name)}')
    space_idx = full_name.index(' ')
    print(f'DEBUG: space_idx = {repr(space_idx)}')
    first = full_name[:space_idx]
    last = full_name[space_idx + 1:]
    result = last + ", " + first
    print(f'DEBUG: result = {repr(result)}')
    return result
```

### repr() – Hiển thị giá trị cho lập trình viên

```python
repr("Hello\nWorld")   # "'Hello\\nWorld'" – thấy ký tự thoát
repr(3.14)             # '3.14'
repr([1, 2, None])     # '[1, 2, None]'
```

### Dùng logging module (khuyến nghị)

```python
import logging

logging.basicConfig(level=logging.DEBUG,
                    format="%(levelname)s: %(message)s")

def calculate(x, y):
    logging.debug('x = %r, y = %r', x, y)
    result = x + y
    logging.debug('result = %r', result)
    return result

# Để tắt debug: logging.basicConfig(level=logging.WARNING)
```

---

## 🔟 TRẮC NGHIỆM – PHẦN 13

**1.** `int("abc")` gây ra ngoại lệ nào?
- A. TypeError
- B. ValueError ✅
- C. NameError
- D. IndexError

**2.** Khối `finally` trong try-except-finally:
- A. Chỉ chạy khi có exception
- B. Chỉ chạy khi không có exception
- C. Luôn chạy, dù có exception hay không ✅
- D. Chỉ chạy khi exception được xử lý

**3.** Exception lan truyền lên call stack khi:
- A. Không có câu lệnh `return`
- B. Không có try-except phù hợp để xử lý nó ✅
- C. Có nhiều hơn một except block
- D. Hàm có nhiều tham số

**4.** `raise ValueError("Không hợp lệ")` dùng để:
- A. Bắt exception
- B. Chủ động tạo và ném ra exception ✅
- C. In thông báo lỗi
- D. Bỏ qua exception

**5.** `assert x > 0` – khi x = 0 sẽ:
- A. In cảnh báo và tiếp tục
- B. Tự động sửa x thành 1
- C. Dừng chương trình với AssertionError ✅
- D. Không làm gì

**6.** `repr()` khác `str()` ở điểm:
- A. `repr()` nhanh hơn
- B. `repr()` trả về biểu diễn kỹ thuật, hữu ích khi debug (hiện rõ ký tự đặc biệt) ✅
- C. `str()` chỉ dùng cho số
- D. Không có sự khác biệt

**7.** Đoạn code sau, nếu nhập "abc", in ra gì?
```python
try:
    x = int(input("Nhập: "))
    print("OK:", x)
except ValueError:
    print("Sai kiểu")
except:
    print("Lỗi khác")
```
- A. "OK: abc"
- B. "Sai kiểu" ✅
- C. "Lỗi khác"
- D. Crash

**8.** "Syntax error" khác "Exception" ở điểm:
- A. Syntax error xảy ra khi chạy, Exception trước khi chạy
- B. Exception xảy ra khi chạy, Syntax error được phát hiện trước khi chạy ✅
- C. Cả hai đều xảy ra khi chạy
- D. Cả hai đều xảy ra trước khi chạy

**9.** Khi nên dùng `logging` thay vì `print` để debug?
- A. Khi dự án nhỏ
- B. Khi cần điều khiển mức độ log và có thể tắt/bật linh hoạt trong production ✅
- C. Khi có ít hơn 10 hàm
- D. Khi không muốn thấy output

**10.** `get_item([1,2,3], 5)` trả về gì nếu:
```python
def get_item(lst, idx):
    try:
        return lst[idx]
    except:
        return 'Out of bounds'
```
- A. Lỗi IndexError
- B. None
- C. 'Out of bounds' ✅
- D. 5

---

# PHẦN 14: FILE I/O

## 14.1 Tại sao cần File I/O?

- **Lưu dữ liệu lâu dài**: Dữ liệu không mất khi chương trình kết thúc
- **Xử lý file bên ngoài**: .txt, .csv, .json...
- **Xử lý dữ liệu lớn**: Không cần load hết vào RAM
- **Ứng dụng thực tế**: Đọc cấu hình, lưu kết quả

## 14.2 Mở và đóng file

```python
# Mở file
file = open('filename.txt', 'mode')

# Đóng file (BẮT BUỘC)
file.close()
```

### Các mode mở file

| Mode | Mô tả |
|------|-------|
| `'r'` | Đọc (mặc định) – lỗi nếu file không tồn tại |
| `'w'` | Ghi – tạo mới hoặc ghi đè nếu đã tồn tại |
| `'a'` | Append – thêm vào cuối file |
| `'rb'` | Đọc nhị phân |
| `'wb'` | Ghi nhị phân |

```python
# Thuộc tính file
f = open('test.txt', 'r')
print(f.name)    # test.txt
print(f.mode)    # r
print(f.closed)  # False
f.close()
print(f.closed)  # True
```

## 14.3 Ghi file

```python
# Ghi – tạo mới hoặc ghi đè
f = open('names.txt', 'w')
f.write("Alice\n")   # write() KHÔNG tự thêm \n
f.write("Bob\n")
f.close()
```

## 14.4 Đọc file

```python
f = open('names.txt', 'r')

# Đọc toàn bộ
content = f.read()

# Đọc k ký tự
chunk = f.read(100)

# Đọc một dòng
line = f.readline()

# Đọc tất cả dòng vào list
lines = f.readlines()

f.close()
```

## 14.5 Dùng `with` (Khuyến nghị)

```python
# with tự động đóng file – KHÔNG cần gọi close()
with open('names.txt', 'r') as f:
    content = f.read()
    print(content)

# Ghi file
with open('names.txt', 'a') as f:
    f.write('Charlie\n')

# Mở nhiều file
with open('in.txt', 'r') as fin, open('out.txt', 'w') as fout:
    for line in fin:
        fout.write(line.upper())
```

## 14.6 Duyệt qua file theo dòng

```python
with open('names.txt', 'r') as f:
    for line in f:
        print(line.rstrip())  # rstrip() xóa \n cuối dòng
```

## 14.7 OS functions

```python
import os

# Thao tác file
os.rename('old.txt', 'new.txt')   # Đổi tên
os.remove('file.txt')              # Xóa file

# Thao tác thư mục
os.mkdir('newdir')                 # Tạo thư mục
os.rmdir('dirname')                # Xóa thư mục rỗng
os.chdir('dirname')                # Chuyển thư mục
os.getcwd()                        # Lấy thư mục hiện tại
os.listdir('dirname')              # Liệt kê nội dung

# Path operations
os.path.join('D:/data', 'file.txt')     # Nối path
os.path.exists('D:/data/file.txt')      # Kiểm tra tồn tại
os.path.isfile('file.txt')              # Là file?
os.path.isdir('dirname')                # Là thư mục?
```

## 14.8 File CSV

```python
# Đọc CSV thủ công
with open('students.csv', 'r') as f:
    for line in f:
        row = line.rstrip().split(',')
        print(f"{row[0]} thuộc {row[1]}")

# Dùng thư viện csv
import csv
with open('students.csv', 'r') as f:
    reader = csv.reader(f)
    for row in reader:
        print(row)

# Ghi CSV
with open('output.csv', 'w', newline='') as f:
    writer = csv.writer(f)
    writer.writerow(['Name', 'Score'])
    writer.writerow(['Alice', 95])
```

## 14.9 File JSON

```python
import json

# Đọc JSON
with open('user.json', 'r') as f:
    user = json.load(f)
print(user['name'])

# Ghi JSON
user = {'name': 'Nam', 'age': 18, 'city': 'Hanoi'}
with open('user.json', 'w') as f:
    json.dump(user, f, indent=4)  # indent để dễ đọc

# Chuyển đổi
json_str = json.dumps(user)    # dict → JSON string
obj = json.loads(json_str)     # JSON string → dict
```

## 14.10 Raw Strings cho đường dẫn Windows

```python
# Vấn đề: \n trong path được hiểu là ký tự xuống dòng
path = "C:\new_folder\test.txt"   # \n và \t gây lỗi!

# Giải pháp 1: Dùng raw string
path = r"C:\new_folder\test.txt"  # r prefix

# Giải pháp 2: Dùng /
path = "C:/new_folder/test.txt"

# Giải pháp 3: Dùng \\
path = "C:\\new_folder\\test.txt"
```

---

## 🔟 TRẮC NGHIỆM – PHẦN 14

**1.** Mode `'a'` khi mở file có nghĩa là:
- A. Ghi đè toàn bộ nội dung cũ
- B. Chỉ đọc
- C. Thêm nội dung vào cuối file ✅
- D. Đọc và ghi

**2.** Lợi ích của `with open(...) as f:` là:
- A. Tăng tốc đọc file
- B. Tự động đóng file sau khi ra khỏi block ✅
- C. Cho phép đọc nhiều file cùng lúc
- D. Mở file ở chế độ binary

**3.** `file.readline()` trả về:
- A. Toàn bộ nội dung file dưới dạng chuỗi
- B. Danh sách tất cả các dòng
- C. Một dòng tiếp theo dưới dạng chuỗi ✅
- D. Một ký tự

**4.** Để kiểm tra xem file `'data.txt'` có tồn tại không:
- A. `os.path.isfile('data.txt')` ✅
- B. `os.exists('data.txt')`
- C. `open('data.txt').exists()`
- D. `file.check('data.txt')`

**5.** `json.load(f)` với `f` là file đang mở trả về:
- A. Chuỗi JSON
- B. Đối tượng Python (dict, list...) tương ứng ✅
- C. Bytes
- D. Số dòng trong file

**6.** `line.rstrip()` khi đọc file dùng để:
- A. Xóa khoảng trắng ở đầu dòng
- B. Xóa khoảng trắng ở cuối dòng, đặc biệt ký tự `\n` ✅
- C. Xóa tất cả khoảng trắng
- D. Đổi chữ thường thành chữ hoa

**7.** Để đọc file CSV `'a,b,c\n1,2,3'` và lấy giá trị từng ô:
- A. `f.read().split()`
- B. `for line in f: row = line.rstrip().split(',')` ✅
- C. `json.load(f)`
- D. `f.readlines()`

**8.** `open('file.txt', 'w')` khi file đã tồn tại sẽ:
- A. Báo lỗi
- B. Thêm vào cuối file
- C. Ghi đè toàn bộ nội dung cũ ✅
- D. Mở file ở chế độ đọc

**9.** `r"C:\new\test.txt"` là:
- A. Hàm `r()` gọi với đường dẫn
- B. Raw string – các ký tự `\n`, `\t` không bị hiểu là ký tự đặc biệt ✅
- C. Relative path
- D. Đường dẫn chỉ đọc

**10.** Thứ tự đúng khi làm việc với file:
- A. Đọc/Ghi → Mở → Đóng
- B. Mở → Đọc/Ghi → Đóng ✅
- C. Đóng → Mở → Đọc/Ghi
- D. Không cần thứ tự

---

# 📋 BẢNG TÓM TẮT CÁC HÀM/LỆNH QUAN TRỌNG

## Hàm built-in Python

| Hàm | Công dụng | Ví dụ |
|-----|-----------|-------|
| `print(x)` | In giá trị | `print("Hello")` |
| `input(prompt)` | Nhập từ bàn phím | `x = input("Nhập: ")` |
| `int(x)` | Chuyển sang int | `int("42")` → 42 |
| `float(x)` | Chuyển sang float | `float("3.14")` → 3.14 |
| `str(x)` | Chuyển sang str | `str(42)` → "42" |
| `bool(x)` | Chuyển sang bool | `bool(0)` → False |
| `type(x)` | Lấy kiểu | `type(3.14)` → float |
| `len(x)` | Độ dài | `len([1,2,3])` → 3 |
| `range(start,stop,step)` | Dãy số | `range(1,6)` → [1,2,3,4,5] |
| `max(x)` | Lớn nhất | `max([1,3,2])` → 3 |
| `min(x)` | Nhỏ nhất | `min([1,3,2])` → 1 |
| `sum(x)` | Tổng | `sum([1,2,3])` → 6 |
| `abs(x)` | Giá trị tuyệt đối | `abs(-5)` → 5 |
| `sorted(x)` | Trả về list đã sắp xếp | `sorted([3,1,2])` → [1,2,3] |
| `enumerate(x)` | Thêm index | `enumerate(['a','b'])` |
| `zip(a,b)` | Ghép hai iterable | `zip([1,2],['a','b'])` |
| `isinstance(x, T)` | Kiểm tra kiểu | `isinstance(3, int)` → True |
| `repr(x)` | Biểu diễn kỹ thuật | `repr("Hi\n")` → `'Hi\\n'` |
| `iter(x)` | Tạo iterator | `iter([1,2,3])` |
| `next(it)` | Phần tử tiếp theo | `next(it)` |

## Phương thức List

| Phương thức | Công dụng |
|------------|-----------|
| `lst.append(x)` | Thêm x vào cuối |
| `lst.insert(i, x)` | Chèn x tại vị trí i |
| `lst.remove(x)` | Xóa phần tử x đầu tiên |
| `lst.pop(i)` | Xóa và trả về phần tử i |
| `lst.sort()` | Sắp xếp in-place |
| `lst.reverse()` | Đảo ngược in-place |
| `lst.index(x)` | Tìm index của x |
| `lst.count(x)` | Đếm số lần x xuất hiện |
| `lst.extend(lst2)` | Mở rộng với lst2 |
| `lst.copy()` | Tạo bản sao |

## Phương thức Dictionary

| Phương thức | Công dụng |
|------------|-----------|
| `d.get(key, default)` | Lấy value an toàn |
| `d.keys()` | Iterable của keys |
| `d.values()` | Iterable của values |
| `d.items()` | Iterable của (key, val) |
| `d.pop(key)` | Xóa và trả về value |
| `d.update(d2)` | Gộp dict khác vào |

## Module math

```python
import math
math.pi          # 3.14159...
math.e           # 2.71828...
math.sqrt(x)     # Căn bậc hai
math.pow(x, n)   # x^n
math.floor(x)    # Làm tròn xuống
math.ceil(x)     # Làm tròn lên
math.isclose(a, b)  # So sánh float
math.log(x)      # Logarithm tự nhiên
math.log10(x)    # Log cơ số 10
```

## File I/O

```python
open(file, mode)     # Mở file
f.read()             # Đọc toàn bộ
f.readline()         # Đọc một dòng
f.readlines()        # Đọc tất cả dòng
f.write(str)         # Ghi chuỗi
f.close()            # Đóng file
os.path.exists(p)    # Kiểm tra tồn tại
json.load(f)         # Đọc JSON
json.dump(obj, f)    # Ghi JSON
```

---

*Tài liệu được tổng hợp từ slide bài giảng môn UET.COM1050 – Computational Thinking, VNU-UET Hà Nội.*
