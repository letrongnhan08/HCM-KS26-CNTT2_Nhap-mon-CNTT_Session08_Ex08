\# 📅 Ứng dụng Quản lý Lịch Học Cá nhân



Ứng dụng giúp sinh viên \*\*lên kế hoạch học tập\*\* hiệu quả.



\## 🚀 Hướng dẫn Cài đặt



```bash

git clone https://github.com/nhom5/lich-hoc-app

cd lich-hoc-app

✅ Tính năng đã hoàn thành
[x] Đăng ký / Đăng nhập tài khoản

[ ] Nhắc nhở lịch học qua email

[x] Xuất lịch ra file PDF

📊 Bảng So sánh Công nghệ:
Công nghệ:PythonBackend    ,     Markdown
             |                       |
             v                       v
Mục đích:  xử lý dữ liệu   ,       Viết tài liệu README
Phiên bản: 3.11            ,         -

#### 3. Xử lý bẫy dữ liệu (Khi hàng phân cách bảng bị xóa)

**Bảng sẽ hiển thị như thế nào?** 
  Nếu xóa hàng phân cách (dòng chứa `| --- | --- | ...`), trình phân tích cú pháp (Markdown parser) sẽ không nhận diện đây là một bảng dữ liệu hợp lệ. Do đó, toàn bộ cấu trúc bảng sẽ bị vỡ và hiển thị thành các đoạn văn bản thô (plain text) hoặc một danh sách các dòng văn bản dính liền nhau có chứa dấu gạch đứng (`|`), chứ không vẽ thành khung bảng trên giao diện GitHub.
**Tại sao?** 
  Quy chuẩn của Markdown yêu cầu phải có dòng phân cách (gồm các dấu gạch ngang `---` nằm ngay dưới dòng tiêu đề bảng) để phân biệt rõ đâu là phần **Tiêu đề bảng (Header)** và đâu là phần **Dữ liệu bảng (Rows)**. Nếu thiếu dòng này, trình biên dịch coi các dòng đó chỉ đơn giản là các ký tự văn bản thông thường.
