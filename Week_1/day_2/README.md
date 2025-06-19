# 🧪 Tổng kết Python Control Flow - Ngày 2 & Bài tập thực hành

Tài liệu này tổng hợp nội dung đã học trong ngày thứ 2 của hành trình học Python, tập trung vào **cấu trúc điều khiển (Control Flow)** với ví dụ và bài tập thực hành cụ thể.

---

## 📘 Bạn đã học gì

### ✅ Câu lệnh điều kiện (Conditional Statements)
- `if`, `elif`, `else`: kiểm soát luồng chương trình dựa trên điều kiện.
- Python **dùng thụt dòng (indentation)** thay vì `{}` để xác định khối lệnh.

**Ví dụ:** Kiểm tra một số là dương, bằng 0 hay âm bằng `if-elif-else`.

### ✅ Điều kiện lồng nhau (Nested Conditions)
- Sử dụng `if` bên trong một `if` khác để tạo điều kiện phức tạp hơn.
- Ví dụ: phân loại độ tuổi thành `young adult`, `adult`, hoặc bỏ qua nếu nhỏ hơn 18.

### 🔁 Vòng lặp (Loops)
- `for` để lặp qua:
  - Danh sách (vd: `fruits = ["apple", "banana"]`)
  - Dải số (vd: `range(5)` → từ 0 đến 4)
- `while` để lặp đến khi điều kiện sai.
- `break`: thoát vòng lặp sớm.
- `continue`: bỏ qua vòng hiện tại và chuyển sang vòng tiếp theo.

### 🧠 Một số khái niệm quan trọng khác
- Dùng `input()` để lấy dữ liệu từ người dùng.
- Sử dụng `range()`, toán tử `%` và điều kiện để xử lý logic.
- Phân biệt `break` và `continue` khi xử lý vòng lặp.

---

## ✍️ Bài tập thực hành

### 🧪 Bài 1: Kiểm tra số nguyên tố
Viết chương trình xác định xem một số người dùng nhập vào có phải là số nguyên tố hay không.
- Duyệt từ 2 đến `sqrt(n)`
- Dùng `%` để kiểm tra chia hết
- Sử dụng `break` và `else` trong vòng lặp `for`

### ➕ Bài 2: Máy tính dạng menu
Tạo chương trình máy tính đơn giản cho phép:
- Hiển thị menu: Cộng, Trừ, Nhân, Chia, Thoát
- Nhận lựa chọn và 2 số từ người dùng
- Thực hiện phép tính tương ứng qua hàm riêng
- Kiểm tra chia cho 0
- Lặp lại menu cho đến khi chọn Thoát

### 🎯 Thử thách thêm
- Viết chương trình tính **giai thừa** của một số bằng vòng lặp `while`
- Viết chương trình tìm **số lớn nhất trong danh sách** bằng vòng lặp `for`

---

> Ngày học này đã cung cấp nền tảng vững chắc về cấu trúc điều khiển trong Python, giúp bạn sẵn sàng bước vào những thử thách logic cao hơn trong thực tế!
