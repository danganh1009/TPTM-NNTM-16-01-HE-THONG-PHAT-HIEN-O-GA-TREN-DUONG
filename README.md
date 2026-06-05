# 🏙️ HỆ THỐNG PHÁT HIỆN Ổ GÀ THÔNG MINH CHO THÀNH PHỐ VÀ NÔNG NGHIỆP


![banner](link_anh_banner.png)

---

## 📝 Giới thiệu

Hệ thống phát hiện ổ gà thông minh là một giải pháp tích hợp **AI/ML** và **Blockchain** để hỗ trợ:
- 🏙️ **Thành phố Thông Minh (Smart Cities)**: Quản lý cơ sở hạ tầng giao thông hiệu quả
- 🌾 **Nông nghiệp Thông Minh (Smart Agriculture)**: Giám sát tình trạng đường trong khu vực nông nghiệp
- 🔐 **Xác thực Blockchain**: Bảo đảm tính minh bạch và bất biến của dữ liệu

---

## 🎯 Ứng dụng trong Smart Cities

### Quản lý Hạ tầng Giao thông
Hệ thống tự động phát hiện và báo cáo tình trạng đường:
- ✅ Phát hiện ổ gà tự động từ camera trên đường
- ✅ Ghi lại tọa độ GPS chính xác
- ✅ Chia sẻ dữ liệu real-time cho cơ quan quản lý
- ✅ Giúp các nhân viên bảo trì ưu tiên sửa chữa

![Giao diện Hệ thống](anh1.png)

### Lợi ích cho Thành phố
- 📍 **Quản lý tập trung**: Bản đồ tất cả ổ gà trên toàn thành phố
- ⏱️ **Phản ứng nhanh**: Giảm thời gian phát hiện và sửa chữa
- 💰 **Tiết kiệm chi phí**: Tối ưu hóa tài nguyên sửa chữa
- 🚗 **An toàn giao thông**: Giảm tai nạn do ổ gà

---

## 🌾 Ứng dụng trong Smart Agriculture

### Giám sát Đường Nông thôn
Ổ gà ảnh hưởng đến vận chuyển nông sản:
- 🚚 Đảm bảo chất lượng vận chuyển nông sản
- 🥕 Giảm hư hại sản phẩm nông nghiệp
- 🗺️ Giám sát tình trạng đường nông thôn
- 👨‍🌾 Hỗ trợ nông dân trong quản lý cộng đồng

![Kết quả Phát hiện](anh3.png)

### Lợi ích cho Nông nghiệp
- 📊 **Theo dõi định kỳ**: Giám sát liên tục tình trạng đường
- 🤝 **Cộng đồng**: Cùng nhau báo cáo vấn đề
- 🏆 **Chất lượng**: Đảm bảo chất lượng hàng hóa nông sản
- 🌱 **Phát triển bền vững**: Nâng cao chất lượng hạ tầng nông thôn

---

## 🔐 Công nghệ Blockchain cho Xác Thực

### Tính năng Blockchain
- **Xác thực dữ liệu**: Mỗi phát hiện được ghi lại trên blockchain với hash duy nhất
- **Minh bạch & Bất biến**: Dữ liệu công khai, không thể chỉnh sửa hay xóa
- **GPS + Blockchain**: Mỗi phát hiện kèm tọa độ GPS và hash blockchain
- **Xác thực cộng đồng**: Cộng đồng có thể xác minh báo cáo

### Kiến trúc Blockchain
- **Blockchain**: Sepolia Testnet (Ethereum)
- **Smart Contract**: PotholeHashRegistry.sol
- **Dữ liệu**: Hình ảnh, vị trí GPS, hash blockchain, timestamp
- **Công khai**: Tất cả dữ liệu xem tại Blockchain Explorer

---

## 🛠️ Quy trình Hoạt động

### 1️⃣ Phát hiện
- YOLOv8 phát hiện ổ gà từ video hoặc hình ảnh
- Xác định vị trí trong khung hình (bounding box)

### 2️⃣ Định vị
- Lấy tọa độ GPS hiện tại
- Ghi lại thông tin thời gian (timestamp)

### 3️⃣ Xác thực
- Tính SHA-256 từ dữ liệu ảnh + GPS
- Ghi hash lên Sepolia Testnet thông qua PotholeHashRegistry

### 4️⃣ Chia sẻ
- Dữ liệu có sẵn công khai trên blockchain explorer
- Các cơ quan quản lý có thể xem và quản lý

---

## 💻 Công nghệ sử dụng
- **AI/ML**: YOLOv8, OpenCV, PyTorch
- **Blockchain**: Solidity, Web3.py, Sepolia Testnet
- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **GPS**: Định vị toàn cầu, Tọa độ kinh vĩ độ

---

## ✨ Ưu điểm của Hệ thống

### Cho Smart Cities
✅ **Quản lý tập trung**: Bản đồ toàn thành phố  
✅ **Phản ứng nhanh**: Giảm thời gian sửa chữa  
✅ **Tiết kiệm chi phí**: Tối ưu tài nguyên  
✅ **An toàn**: Giảm tai nạn giao thông  

### Cho Smart Agriculture
✅ **Bảo vệ nông sản**: Giảm hư hại hàng hóa  
✅ **Cộng đồng nông dân**: Cùng nhau quản lý  
✅ **Chất lượng đường**: Giám sát liên tục  
✅ **Phát triển bền vững**: Nâng cao hạ tầng nông thôn  

### Cho Xác thực Dữ liệu
✅ **Minh bạch**: Dữ liệu công khai, có thể kiểm chứng  
✅ **An toàn**: Mã hóa và bất biến  
✅ **Phân tán**: Không phụ thuộc máy chủ tập trung  
✅ **Truy cập dễ**: Bất kỳ ai cũng có thể xác minh  

---

## � Kết luận

Hệ thống phát hiện ổ gà thông minh là giải pháp toàn diện kết hợp:
- 🤖 **AI/ML**: Công nghệ nhận dạng hình ảnh tiên tiến
- 🏙️ **Smart Cities**: Quản lý hạ tầng giao thông thông minh
- 🌾 **Smart Agriculture**: Hỗ trợ phát triển nông nghiệp
- 🔐 **Blockchain**: Xác thực và chia sẻ dữ liệu minh bạch

Hệ thống không chỉ giúp phát hiện vấn đề đường xá mà còn hỗ trợ cộng đồng, quản lý công khai dữ liệu và thúc đẩy phát triển đô thị - nông thôn bền vững.

---

## 👤 Thông tin Dự án
- **Tên Dự án**: Hệ thống Phát hiện Ổ gà Thông Minh
- **Môn học**: Thành phố Thông Minh & Nông nghiệp Thông Minh
- **Tác giả**: Nguyễn Hải Đăng
- **Lớp/Khoa**: CNTT 16-04 - Đại học Đại Nam
- **Năm**: 2026  

