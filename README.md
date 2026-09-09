# 🌲 LVT4U — Official Global Distribution & Update Repository

Repository phân phối chính thức và cập nhật tự động toàn cầu cho plugin QGIS **LVT4U**.

## 🌐 Hướng dẫn cài đặt kho cập nhật tự động trong QGIS (Dành cho Lào, Thái Lan & Quốc Tế)

Để nhận các bản cập nhật mới nhất từ mạng lưới CDN toàn cầu Fastly/Microsoft (tốc độ cao, không bao giờ bị chặn mạng):

1. Mở **QGIS** $\rightarrow$ Vào menu **Plugins** $\rightarrow$ **Manage and Install Plugins...** (Quản lý và cài đặt phần bổ trợ).
2. Chọn mục **Settings** (Cài đặt) ở thanh menu bên trái.
3. Trong phần **Plugin Repositories** (Kho phần bổ trợ) $\rightarrow$ Nhấn nút **Add...** (Thêm...).
4. Điền thông tin:
   - **Name**: `LVT4U Official (Global CDN)`
   - **URL**: 
     ```
     https://raw.githubusercontent.com/locvutrunglvt/LVT4U-Update/main/plugins.xml
     ```
5. Nhấn **OK** $\rightarrow$ Chuyển sang tab **All** hoặc **Upgrade** $\rightarrow$ Tìm `LVT4U` và nhấn **Install Plugin** / **Upgrade Plugin**.

---

## ⚡ Các Kênh Phân Phối / Distribution Mirrors

| Kênh tải | Địa chỉ kho XML | Đối tượng khuyến nghị |
| :--- | :--- | :--- |
| **1. GitHub Global CDN (Chính)** | `https://raw.githubusercontent.com/locvutrunglvt/LVT4U-Update/main/plugins.xml` | Người dùng Lào, Thái Lan và Quốc tế (Toàn cầu) |
| **2. Máy chủ VPS (Dự phòng)** | `https://lvtfield.lvtcenter.it.com/plugins/plugins.xml` | Người dùng tại Việt Nam |

---

## 🔒 Bảo vệ bản quyền & Tác quyền
- **Tác giả**: Lộc Vũ Trung
- **Email**: locvutrung@gmail.com
- Bản quyền thuộc về Lộc Vũ Trung. Mã nguồn được đóng gói bảo vệ phục vụ nghiên cứu và ứng dụng quản lý tài nguyên rừng.
