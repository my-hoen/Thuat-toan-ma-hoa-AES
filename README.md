# Thuat-toan-ma-hoa-AES
* Mục tiêu:
- Hỗ trợ mã hóa và giải mã file một cách nhanh chóng và dễ sử dụng thông qua giao diện web
- Giúp bảo vệ dữ liệu cá nhân hoặc tài liệu quan trọng mà không cần cài đặt phần mềm phức tạp
- Cho phép người dùng tự nhập khóa mã hóa (bất kỳ độ dài nào), sử dụng AES-128, thuật toán mã hóa đối xứng phổ biến
* Các chức năng chính:
  Upload file bất kỳ từ máy tính 
 Mã hóa hoặc giải mã file bằng thuật toán AES-128 (ECB mode)
 Nhập khóa tự do: cho phép người dùng nhập chuỗi khóa tùy ý (dài bao nhiêu cũng được)
 Tải về file kết quả sau khi mã hóa hoặc giải mã
 Giao diện thân thiện, đẹp mắt sử dụng Bootstrap 5 + hiệu ứng glassmorphism
ông nghệ sử dụng
  Thành phần        Mô tả
Flask	            Framework backend Python nhẹ, nhanh
PyCryptodome     	Thư viện mã hóa AES, thay thế pycrypto
Bootstrap 5      	Thư viện CSS UI hiện đại, responsive
HTML + CSS	       Giao diện web với hiệu ứng thủy tinh (glassmorphism)
hashlib	          Băm khóa người dùng bằng SHA-256

* Tổng kết
- Bảo mật thông tin cơ bản cho người dùng phổ thông
- Xử lý file nhanh chóng mà không cần cài đặt phần mềm mã hóa chuyên dụng
![image](https://github.com/user-attachments/assets/663688cc-1f4c-436d-bea2-ef0eae039b9a)



