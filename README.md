# 💰 Ứng Dụng Quản Lý Chi Tiêu Cá Nhân (Finance Tracker)

Một ứng dụng di động được xây dựng bằng **Flutter**, giúp người dùng theo dõi thu nhập, chi tiêu, xem thống kê dòng tiền và quản lý các mục tiêu tiết kiệm cá nhân một cách hiệu quả và trực quan.

![App Screenshot](path/to/your/screenshot.png)
*(Bạn có thể thay thế dòng trên bằng đường dẫn ảnh chụp màn hình ứng dụng của bạn sau khi upload lên GitHub)*

## ✨ Tính Năng Chính

* **Quản Lý Thu Chi:** Thêm nhanh các khoản thu/chi với danh mục cụ thể (Ăn uống, Di chuyển, Lương, Thưởng...).
* **Lịch Sử Giao Dịch:** Xem lại lịch sử theo ngày, tháng thông qua giao diện Lịch (Calendar) trực quan.
* **Thống Kê:** Biểu đồ tròn (Pie Chart) hiển thị tỷ lệ phần trăm thu/chi giúp dễ dàng kiểm soát tài chính.
* **Mục Tiêu Tiết Kiệm:** Tạo và theo dõi tiến độ các quỹ tiết kiệm (Mua xe, Du lịch...) tách biệt với ví chi tiêu hàng ngày.
* **Offline First:** Dữ liệu được lưu trữ nội bộ trên thiết bị bằng SQLite, không cần kết nối internet.

## 🛠 Công Nghệ Sử Dụng

* **Framework:** Flutter (Dart)
* **State Management:** Provider
* **Local Database:** Sqflite
* **UI Components:** * `fl_chart` (Biểu đồ thống kê)
    * `table_calendar` (Giao diện lịch)
    * `intl` (Định dạng tiền tệ và thời gian)
    * `shared_preferences` (Lưu trạng thái lần đầu mở app)

## 🚀 Hướng Dẫn Cài Đặt & Chạy Dự Án

Để chạy được dự án này trên máy của bạn, vui lòng làm theo các bước sau:

### 1. Yêu Cầu Tiên Quyết
* Đã cài đặt [Flutter SDK](https://docs.flutter.dev/get-started/install).
* Một thiết bị Android/iOS (máy thật hoặc máy ảo).
* VS Code hoặc Android Studio.

### 2. Tải Mã Nguồn
Mở terminal và chạy lệnh:
```bash
git clone <LINK_GITHUB_CUA_BAN>
cd <TEN_THU_MUC_DU_AN>

Chạy thêm:
flutter pub get



