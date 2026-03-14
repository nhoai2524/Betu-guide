# BETU Guide - Ứng dụng điều hướng trong nhà

Ứng dụng di động hỗ trợ tìm đường trong tòa nhà Đại học Kinh tế - Công nghệ Bình Dương (BETU), được xây dựng như đồ án tốt nghiệp.

## Tính năng

- Bản đồ mặt bằng tòa nhà tương tác
- Định vị trong nhà bằng WiFi Fingerprinting
- Thuật toán KNN dự đoán vị trí người dùng
- Thuật toán A* tìm đường đi tối ưu
- Chatbot AI tích hợp Claude AI (Anthropic)
- Tìm kiếm phòng học, phòng chức năng
- Xem tin tức, thông báo của trường

## Công nghệ sử dụng

- Ứng dụng di động: Flutter / Dart
- Trang quản trị: ReactJS
- Cơ sở dữ liệu: Firebase (Firestore, Auth, Storage)
- Chatbot AI: Claude AI (Anthropic)
- Định vị trong nhà: WiFi Fingerprinting + KNN
- Tìm đường: Thuật toán A*

## Hướng dẫn cài đặt

Yêu cầu: Flutter SDK >= 3.0.0, Dart >= 3.0.0, cấu hình Firebase project.
```bash
git clone https://github.com/nhoai2524/Betu-guide.git
cd Betu-guide
flutter pub get
flutter run
```

## Tác giả

Nguyễn Ngọc Hoài  
Sinh viên IT - Đại học Kinh tế - Công nghệ Bình Dương (BETU)  
Email: ngochoainguyen2502@gmail.com

## Ghi chú

Dự án được xây dựng phục vụ mục đích học thuật - Đồ án tốt nghiệp 2025-2026.
