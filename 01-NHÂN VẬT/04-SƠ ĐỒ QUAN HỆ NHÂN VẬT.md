---
type: nhan-vat
status: hoan-thien
tags:
  - nhan-vat
  - relationship-map
---

# Sơ Đồ Quan Hệ Nhân Vật

> Quan hệ có căn cứ đến Chương 52. Đường liền là quan hệ được xác nhận; nét chấm là quan hệ xã hội/đang hình thành. Không suy chức quyền hay huyết thống từ cùng họ.

## Gia đình Lâm Uyên

~~~mermaid
graph TD
 LCh[Lâm Chinh] -->|cha| LU[Lâm Uyên]
 ML[Mẹ Lâm Uyên, tên chưa rõ] -->|mẹ| LU
 ON[Ông nội Lâm Uyên, tên chưa rõ] -->|ông nội| LU
 LD[Lão Đầu] -.->|người quản sổ mộ, không phải ông nội| LU
~~~

## Mối quan hệ đã có căn cứ

| ID A | Nhân vật A | Quan hệ | ID B | Nhân vật B | Căn cứ và giới hạn |
| --- | --- | --- | --- | --- | --- |
| CHAR-001 | Lâm Uyên | Con | CHAR-007 | Lâm Chinh | Cha Lâm Uyên là Lâm Chinh; số phận thật vẫn mở. |
| CHAR-001 | Lâm Uyên | Con | CHAR-009 | Mẹ Lâm Uyên | Mẹ đã mất; tên riêng chưa rõ. |
| CHAR-001 | Lâm Uyên | Cháu | CHAR-010 | Ông nội Lâm Uyên | Được ông nuôi; không đồng nhất với Lão Đầu. |
| CHAR-001 | Lâm Uyên | Đồng hành, phối hợp nhưng có bất đồng | CHAR-006 | Tô Thanh Ly | Không mặc định tình cảm lãng mạn hay đồng thuận tuyệt đối. |
| CHAR-001 | Lâm Uyên | Người học việc/người hướng dẫn | CHAR-037 | Mạnh Thanh Tễ | Đang học căn bản dược lý trong công việc. |
| CHAR-013 | Tô Lạc | Đồng đội; Tô Lạc cứu Tín | CHAR-019 | Tô Tín | Tô Lạc chết; thi thể chưa được đưa về tại Ch52. |
| CHAR-019 | Tô Tín | Cùng ở viện sau biến cố | CHAR-044 | Trần Dực | Quan hệ trước Hắc Phong Sơn chưa xác định. |
| CHAR-006 | Tô Thanh Ly | Làm hồ sơ/điều tra | CHAR-046 | Tạ Nghiên Chi | Liên hệ công vụ; không có căn cứ về quan hệ riêng. |
| CHAR-044 | Trần Dực | Người được nhắc trong lời kể | CHAR-057 | Tả Tiên Sinh | Lời kể chưa xác minh danh tính hay phe phái. |

## Quan hệ chưa chốt

- Tô Thanh Dương gọi Thanh Ly bằng tên; mức độ thân thuộc/huyết thống chưa được phân định.
- Gia phả Tô Gia chưa xác nhận phần lớn quan hệ cha-con/anh-em; sơ đồ chức vụ không phải phả hệ.
- Không nối các vụ người áo đen, Tả Tiên Sinh, mạng thuốc và người lấy trang giấy nếu chưa có chứng cứ độc lập.

## Quy tắc cập nhật

Mỗi quan hệ cần chiều, loại, mức chắc chắn, sự kiện hình thành và nguồn. Giữ lịch sử khi quan hệ thay đổi, không xóa mốc cũ.

Liên kết: [[MỐI QUAN HỆ]], [[02-SỔ CÁI NHÂN VẬT]], [[05-MA TRẬN TRI THỨC]].
