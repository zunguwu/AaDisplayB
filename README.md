# 🚀 AADisplay - Android Auto Enhancement Module

[![License](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](LICENSE)
[![Android](https://img.shields.io/badge/Android-12%2B-green.svg)](https://developer.android.com)
[![Xposed Required](https://img.shields.io/badge/LSPosed-Required-orange.svg)](#requirements)
[![Android Auto](https://img.shields.io/badge/Android%20Auto-Supported-4285F4.svg)](https://www.android.com/auto/)

**AADisplay** là một module LSPosed dành cho các thiết bị Android đã root, giúp tùy biến, nâng cao trải nghiệm hiển thị và mở rộng tính năng trên **Android Auto**.

---

## 📋 Requirements (Yêu cầu hệ thống)

- **Android Version:** Android 12 trở lên (SDK 31+). *Lưu ý: Android 10 và 11 không được hỗ trợ.*
- **Xposed Environment:** Cần có quyền Root và đã cài đặt **LSPosed** (hoặc môi trường Xposed tương thích).
- **Android Auto:** Đã cài đặt và hoạt động bình thường (`com.google.android.projection.gearhead`).
- ⚠️ **Lưu ý ROM:** Một số ROM tùy chỉnh (Custom ROM) có thể hoạt động không ổn định hoặc gây crash hệ thống — hãy cân nhắc trước khi sử dụng.

---

## ⚙️ Usage (Hướng dẫn sử dụng)

1. **Kích hoạt Module:** 
   - Mở ứng dụng LSPosed.
   - Bật module **AADisplay** và tích chọn Scope (Phạm vi) gồm:
     - **System Framework**
     - **Android Auto** (`com.google.android.projection.gearhead`)
2. **Cấu hình Launcher:** 
   - Mở ứng dụng AADisplay và thiết lập Package Name cho Launcher mà bạn muốn sử dụng.
3. **Tùy chỉnh nâng cao (Tuỳ chọn):**
   - Điều chỉnh tham số DPI phù hợp với màn hình ô tô của bạn.
   - Inject các thuộc tính/properties của Android Auto.
4. **Quyền Root:** 
   - Quyền Root chỉ được sử dụng khi bạn cần thực thi các lệnh Shell do người dùng cấu hình. Bạn hoàn toàn có thể **từ chối (Deny)** cấp quyền Root nếu không có nhu cầu dùng tính năng này.

---

## ⚠️ Disclaimer (Miễn trừ trách nhiệm)

- Dự án được cung cấp "nguyên trạng" (as-is). Tác giả không chịu trách nhiệm cho bất kỳ rủi ro nào liên quan đến treo máy, mất dữ liệu hoặc mất an toàn khi tham gia giao thông.

---

## 📜 License

Phát hành theo giấy phép [GNU General Public License v3.0](LICENSE).

## 📜 Giấy phép & Đóng góp (License & Contribution)

- Dự án được phân phối dưới giấy phép [GNU General Public License v3.0](LICENSE).
- Mọi đóng góp (Pull Request, Báo lỗi/Issue) từ cộng đồng đều được hoan nghênh!

---
*Created with ❤️ for zunguwu Community.*
