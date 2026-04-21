# [Tên Dự Án: Hệ Thống Quản Lý Bán Hàng & Kho Mini]

## 📝 Giới Thiệu
Dự án được thực hiện bởi sinh viên chuyên ngành **Hệ thống thông tin - Trường Đại học Khoa học Tự nhiên (HCMUS)**. Mục tiêu của hệ thống là giúp các cửa hàng nhỏ quản lý danh mục hàng hóa, thực hiện giao dịch bán hàng và theo dõi lượng tồn kho một cách chính xác.

## ✨ Tính Năng Chính
* **Quản lý danh mục:** Thêm, xóa, sửa và tìm kiếm thông tin sản phẩm.
* **Quản lý bán hàng:** Tạo hóa đơn, tính tổng tiền và tự động cập nhật số lượng tồn kho sau mỗi giao dịch.
* **Cảnh báo tồn kho:** Hệ thống tự động liệt kê các mặt hàng có số lượng thấp (dưới ngưỡng an toàn) để chủ cửa hàng kịp thời nhập hàng.
* **Báo cáo:** Thống kê doanh thu và các mặt hàng bán chạy.

## 🛠️ Công Nghệ Sử Dụng

| Thành phần | Công nghệ |
| :--- | :--- |
| **Ngôn ngữ** | [Ví dụ: Python / C#] |
| **Database** | [Ví dụ: SQL Server / MySQL / SQLite] |
| **Giao diện** | [Ví dụ: Tkinter (Python) / WinForms (C#)] |
| **Công cụ thiết kế** | Draw.io (Thiết kế DB), Visual Studio Code / Visual Studio |

## 🗄️ Thiết Kế Cơ Sở Dữ Liệu (Database Design)
Đây là phần quan trọng nhất của chuyên ngành HTTT. Hệ thống bao gồm các bảng chính:

* `SanPham`: Lưu trữ thông tin chi tiết về hàng hóa.
* `LoaiHang`: Phân loại sản phẩm.
* `HoaDon`: Lưu thông tin chung của mỗi lần bán.
* `ChiTietHoaDon`: Lưu chi tiết các món hàng trong một hóa đơn (Mối quan hệ n-n).

*Hình ảnh sơ đồ ERD: [Chèn link ảnh sơ đồ của bạn vào đây]*

## 🚀 Hướng Dẫn Cài Đặt

1. **Clone project:**
   ```bash
   git clone [https://github.com/](https://github.com/)[username]/[ten-du-an].git

2. **Cài đặt môi trường:**
* [Ví dụ: Cài đặt Python 3.x]
* [Ví dụ: Cài đặt thư viện: pip install -r requirements.txt]

3. **Cấu hình Database:**
* Chạy file script SQL đính kèm trong thư mục /database để tạo bảng và dữ liệu mẫu.
4. **Chạy ứng dụng:**
* [Ví dụ: python main.py]

## 📸 Hình Ảnh Demo

## 👤 Thông Tin Tác Giả
* **Họ và tên:** Phạm Văn Hữu Tài
* **MSSV:** 24120435
* **Lớp:** 24CTT3 - Khoa CNTT, HCMUS.