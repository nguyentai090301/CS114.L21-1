<!-- Banner -->
<p align="center">
  <a href="https://www.uit.edu.vn/" title="Trường Đại học Công nghệ Thông tin" style="border: none;">
    <img src="https://i.imgur.com/WmMnSRt.png" alt="Trường Đại học Công nghệ Thông tin | University of Information Technology">
  </a>
</p>

<!-- Title -->
<h1 align="center"><b>CS114.L21 - MÁY HỌC - MACHINE LEARNING</b></h1>
<h1 align="center"><b>BÀI TẬP QUÁ TRÌNH NGÀY 26/04/2021</b></h1>

## ĐỀ BÀI:
- Tìm các ví dụ về bài toán regression ***TRONG THỰC TẾ***
- Ghi rõ input, output và cách thu thập + xử lý data

## NHÓM THỰC HIỆN:
- Hoàng Xuân Vũ - 19522531
- Nguyễn Đạt Huy Hoàng - 19521536
- Nguyễn Văn Tài - 19522154


## BÀI LÀM:

### Bài toán 1: Dự đoán cân nặng của vật nuôi(cụ thể là heo) qua số cám đã ăn
- *Input:* Số cám đã ăn của một chú heo
- *Output:* Cân nặng của chú heo đó
- *Cách thu thập data:*
  - Từ những trang trại nuôi heo
  - Từ những hộ nuôi heo quy mô hộ gia đình 
  - Từ các đại lý phân phối cám heo
  - Từ các nguồn tin cậy trên internet
- *Cách xử lý data:*
  - Lấy số cám đã ăn và cân nặng của heo định dạng thành một file .csv

### Bài toán 2: Dự đoán thời gian sử dụng của pin qua phần trăm pin tối đa (iphone)
- *Input:* Phần trăm pin tối đa của pin
- *Output:* Thời gian sử dụng pin
- *Cách thu thập data:* 
  - Khảo sát trực tiếp những người dùng đang sử dụng điện thoại iphone
  - Khảo sát online 
- *Cách xử lý data:*
  - Tách lấy số phần trăm pin tối đa và thời gian sử dung pin định dạng thành một file .csv 
### Bài toán 3: Dự đoán huyết áp
- *Input:* Liều lượng thuốc sử dụng
- *Ouput:* Chỉ số huyết áp
- *Thu thập dữ liệu:*
  - Thông tin bệnh án của bệnh nhân từ các bệnh viện
- *Xử lý data:*
  - Từ file excel lấy dữ liệu về liều thuốc sử dụng và chỉ số huyết áp định dạng thành một file .csv 
### Bài toán 4: Dự đoán thu nhập của người lao động
- *Input:* Nghề nghiệp (1: Kỹ sư, 2: Giáo viên, 3: Bác sĩ, ...) và độ tuổi
- *Output:* Thu nhập lao động
- *Thu thập dữ liệu:* 
  - Tạo form khảo sát trên các trang cá nhân hoặc các diễn đàn
  - Khảo sát trực tiếp ở các công ty, văn phòng, sau đó đưa dữ liệu vào file excel
- *Xử lý thông tin:* 
  - Làm đầy các phần dữ liệu trống(None)
  - Chuyển file excel thành định dạng .csv
