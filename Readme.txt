# README - HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY ỨNG DỤNG

## Giới thiệu
Đây là dự án Flutter với 2 bản build:
- Ứng dụng Desktop chạy trên Windows (.exe)
- Ứng dụng Web chạy trên trình duyệt

---

## Yêu cầu
- Flutter SDK đã cài đặt (phiên bản >= 3.7.2)
- Windows 10/11 (cho bản Windows)
- Trình duyệt web hiện đại (Chrome, Edge, Firefox...) cho bản Web

---

## Gợi ý cách đăng nhập: nên đăng ký trước khi đăng nhập
Username: jungwuan
Password: 0987654321


## Build và chạy bản Windows (.exe)

### 1. Build file .exe
- Mở terminal/cmd ở thư mục dự án
- Chạy lệnh:

```bash
flutter build windows

File .exe sẽ được tạo tại:
build/windows/x64/runner/Release/cuoiki.exe

### 2. Chạy file .exe
Vào thư mục trên, chạy file cuoiki.exe

Ứng dụng sẽ khởi động và hoạt động như ứng dụng Windows bình thường

## Build và chạy bản Web
### 1. Build web
Mở terminal/cmd ở thư mục dự án

Chạy lệnh:
flutter build web

Các file web tĩnh được tạo tại thư mục:
build/web

### 2. Chạy Web App local (tùy chọn)
Để chạy thử local server, bạn có thể dùng Python HTTP server hoặc các công cụ khác

Ví dụ với Python:
cd build/web
python -m http.server 8000
Mở trình duyệt và truy cập http://localhost:8000

## Lưu ý quan trọng
Dự án không hỗ trợ build Android (.apk) do một số plugin không tương thích hoặc không cần thiết

Một số plugin như file_picker hay flutter_local_notifications có thể không hỗ trợ trên nền tảng Web

Hãy kiểm tra kỹ các tính năng trên từng nền tảng để đảm bảo hoạt động đúng

Nếu cần hỗ trợ hoặc có thắc mắc, vui lòng liên hệ với nhóm phát triển.

Cảm ơn bạn đã sử dụng dự án!
