# Bài Clinic-Cloud

## Phần 1. Phân tích

- chức năng (FR): hệ thống làm gì. ví dụ: đăng ký khám, ghi chẩn đoán, kê đơn
- phi chức năng (NFR): hệ thống làm tốt đến đâu. ví dụ: mã hóa dữ liệu, phân quyền, ghi log

## Phần 2. Triển khai

### SRS

# 1. Giới thiệu
# 2. Yêu cầu chức năng
## 2.1 Khám bệnh
# 3. Yêu cầu phi chức năng
## 3.1 Bảo mật

| Mã | Yêu cầu |
|---|---|
| FR-01 | tạo hồ sơ bệnh nhân |
| FR-02 | ghi chẩn đoán, kê đơn |
| NFR-01 | mã hóa dữ liệu |
| NFR-02 | phân quyền bác sĩ, y tá, lễ tân |
| NFR-03 | ghi log mọi lần xem và sửa hồ sơ |

### Excel 1000 hồ sơ

dòng 1 là tiêu đề, mỗi dòng là 1 bệnh nhân, không merge cell, không hàng trống.

| Mã BN | Họ tên | Ngày sinh | SĐT | Chẩn đoán |
|---|---|---|---|---|
| BN0001 | Nguyễn Văn An | 12/03/1998 | Chưa cập nhật | Cúm |

**Bẫy ô trống:** AutoFilter dừng khi gặp hàng trống. Điền "Chưa cập nhật" vào ô thiếu (Ctrl + G, Special, Blanks, gõ chữ, Ctrl + Enter), rồi chọn cả vùng dữ liệu hoặc Ctrl + T trước khi lọc.

### Donut Chart

Insert, Doughnut. Tối đa 5 phần, ít màu, hiện %. Tiêu đề: "Sốt xuất huyết chiếm 40% số ca".

## Phần 3. Kiểm thử

Đoạn văn bị gán nhầm Heading: bấm vào đoạn đó, Ctrl + Shift + N để về Normal, rồi Update Field mục lục.