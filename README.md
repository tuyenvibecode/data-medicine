# Kho Dữ Liệu & Hình Ảnh Thuốc (Vietnam Medicine Catalog)

Kho lưu trữ độc lập chứa **2039 loại thuốc** thông dụng kèm hình ảnh hộp/viên thuốc, phục vụ cho **App Nhắc Nhở Uống Thuốc Gia Đình** và **Web Quản Lý Thuốc**.

## 📌 Đường dẫn API (Raw JSON & CDN)

- **Danh sách thuốc (GitHub Raw JSON)**:
  `https://raw.githubusercontent.com/tuyenvibecode/data-medicine/main/medicines.json`
- **Danh sách thuốc (chi_thuoc.json)**:
  `https://raw.githubusercontent.com/tuyenvibecode/data-medicine/main/chi_thuoc.json`
- **Thư mục hình ảnh thuốc**:
  `https://raw.githubusercontent.com/tuyenvibecode/data-medicine/main/images/<ten-file-anh>.jpg`

## 📦 Cấu trúc dữ liệu mỗi loại thuốc

```json
{
  "name": "Kem Oxy 10 hỗ trợ điều trị mụn bọc, mụn sưng đỏ tuýp 10g",
  "brand": "Rohto-Mentholatum",
  "dosage_form": "Kem",
  "strength": "",
  "image": "https://raw.githubusercontent.com/tuyenvibecode/data-medicine/main/images/0001-oxy-10-thumb-1-600x600.jpg",
  "short_usage": "Dùng tại chỗ để điều trị mụn trứng cá nhẹ và vừa...",
  "classification": "Thuốc không kê đơn",
  "registration_number": "VD-20653-14",
  "manufacturer": "Công ty TNHH Rohto-Mentholatum (Việt Nam)"
}
```
