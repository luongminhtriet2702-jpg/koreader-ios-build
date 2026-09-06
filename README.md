# 📖 KOReader iOS Automated Build (Unofficial)

[![GitHub Release](https://shields.io)](https://github.com)
[![Platform](https://shields.io)](#)
[![Status](https://shields.io)](#)
[![License: GPL v3](https://shields.io)](https://gnu.org)

> ⚠️ **Lưu ý:** Đây là phiên bản **Không chính thức (Unofficial)**. Dự án này được tối ưu hóa và cấu hình build tự động với sự hỗ trợ từ **ChatGPT AI**.

Bản build tự động (Automated Build) dành riêng cho ứng dụng **KOReader trên iOS / iPadOS**. Dự án này được fork từ nhánh gốc [hezi/koreader-ios](https://github.com), giúp người dùng dễ dàng tiếp cận và cài đặt tệp `.ipa` mà không cần tự cấu hình môi trường compile phức tạp.

---

## ✨ Tính năng nổi bật (Features)

* **Full KOReader Engine:** Giữ nguyên vẹn sức mạnh render file PDF, EPUB, DJVU... cực đỉnh từ KOReader gốc.
* **Pre-compiled IPA:** Tải và cài đặt trực tiếp, bỏ qua bước build source code rườm rà qua Xcode.
* **Tối ưu hóa cho iOS:** Tương thích tốt với các công cụ sideload phổ biến hiện nay.

---

## 📲 Hướng dẫn cài đặt (Installation)

Để cài đặt tệp `.ipa` của KOReader lên iPhone hoặc iPad, bạn có thể lựa chọn một trong các phương thức Sideload phổ biến dưới đây:

### 🌟 Cách 1: Sử dụng TrollStore (Khuyên dùng - Vĩnh viễn)
*Nếu thiết bị của bạn nằm trong phiên bản iOS được TrollStore hỗ trợ:*
1. Vào mục **Releases** của repo này và tải về file `.ipa` mới nhất.
2. Mở file bằng ứng dụng **TrollStore** trên thiết bị của bạn.
3. Nhấn **Install** để cài đặt. Ứng dụng sẽ hoạt động vĩnh viễn không bị giới hạn thời gian.

### 🔄 Cách 2: Sử dụng AltStore / SideStore / Sideloadly (Hạn 7 ngày)
*Dành cho mọi thiết bị iOS chạy phiên bản chưa có TrollStore:*
1. Tải file `.ipa` từ mục **Releases** về máy tính hoặc điện thoại.
2. Sử dụng **AltStore**, **SideStore** hoặc phần mềm **Sideloadly** trên PC/Mac để ký (sign) ứng dụng bằng Apple ID của bạn.
3. **Lưu ý:** Nếu dùng tài khoản Apple ID miễn phí, bạn cần làm mới (refresh) ứng dụng sau mỗi **7 ngày** để tránh bị hết hạn chứng chỉ.

---

## 🛠️ Quy trình Build (Build Workflow)

Mã nguồn được biên dịch tự động thông qua **GitHub Actions** đảm bảo tính minh bạch, sạch sẽ và an toàn tuyệt đối. 

Nếu bạn muốn tự chạy quy trình build riêng:
1. Fork repository này về tài khoản của bạn.
2. Đi tới tab **Actions** và kích hoạt Workflow.
3. Chạy workflow để tự tạo file `.ipa` mới nhất theo mong muốn.

---

## 🤝 Đóng góp & Bản quyền (Credits)

* Dự án được xây dựng dựa trên mã nguồn mở của nhóm phát triển chính **[KOReader](https://github.com)**.
* Chân thành cảm ơn **[hezi](https://github.com)** vì bản port iOS gốc.
* Được duy trì, tối ưu hóa và đóng gói bởi **[luongminhtriet2702-jpg](https://github.com)** với sự đồng hành và hỗ trợ kỹ thuật từ **ChatGPT**.

---

## ⚖️ License

Dự án này tuân thủ theo giấy phép mã nguồn mở **GNU General Public License v3.0**.
