---
type: world-lore-audit
status: dang-phat-trien
tags:
  - the-gioi
  - audit
  - unresolved-lore
  - author-review
---

# Báo Cáo Audit Lore

> Snapshot đối chiếu nhánh main tại commit 10c7937b041a7889da866605a0ced11495f15194, trước khi thêm bộ mục lục lore. Ngày audit: 2026-09-26. Đây là báo cáo continuity, không phải quyết định retcon.

## Kết quả nhanh

| Hạng mục | Số lượng / trạng thái |
|---|---|
| Hồ sơ nguồn thế giới | 33 tệp trong 02-THẾ GIỚI |
| Hồ sơ tu luyện | 24 tệp trong 03-HỆ THỐNG TU LUYỆN |
| Hồ sơ timeline | 4 tệp trong 05-TIMELINE |
| Tư liệu/bí mật/địa điểm | 16 tệp trong 07-TƯ LIỆU & BÍ MẬT |
| Chương được rà chéo từ khóa | 52 |
| Tầng địa lý được xác lập ở nền | 5 tầng lồng nhau: Cửu Thiên → Đại Vực → Tiểu Vực → Vân Châu → Lăng Vân Thành |
| Cảnh giới hiện được ghi nhận | 12; cơ chế ba cảnh giới đầu có tài liệu chuyên biệt |
| Hệ thống cảnh giới | 1 thang chung đã xác nhận; đạo lộ/công pháp là nhánh, chưa có bảng quy đổi |
| Chủng tộc | Chưa có danh mục hoàn chỉnh; Ngoại Sinh Linh được canon nền xác nhận, Mạc Nhân/Di Kỷ Tộc theo trạng thái riêng |
| Hồ sơ thế lực | 18 trong 02B; không đồng nghĩa 18 phe đã xuất hiện |
| Thời đại lịch sử | Chưa có niên biểu/thời đại hoàn chỉnh; Lịch Sử Thế Giới ghi TBD |
| Nhóm tài nguyên | Có hồ sơ đan dược, pháp bảo, thiên tài địa bảo, địa mạch; chưa có kinh tế/chuỗi cung ứng tổng thể |
| Bí cảnh/di tích/hiện tượng | 02C và 07C; một số khái niệm soft-canon/TBD |
| Hồ sơ vật phẩm | 6 trong 07A; không đồng nghĩa cùng cấp/phẩm chất |
| Hồ sơ bí ẩn/sự kiện | 8 trong 07B; nhiều quan hệ khả dĩ chưa xác nhận |
| Mâu thuẫn rõ cần tác giả xem | 1: tình trạng sinh tử của Lâm Chinh trong timeline |
| File canon nền được sửa | 0 |

## Phát hiện

### 🔴 Critical — không thấy bằng chứng đủ để báo lỗi canon nền

Không phát hiện mâu thuẫn nào buộc phải thay đổi ba file nền được bảo vệ. Điều này không có nghĩa mọi hồ sơ đã đầy đủ; các phần UNKNOWN bên dưới được giữ mở.

### 🟠 Major — AUTHOR REVIEW REQUIRED

**AR-001 — Tình trạng Lâm Chinh**

- **Timeline:** [[Timeline Tổng]] ghi “10 năm trước … Lâm Chinh … chết; mẹ Lâm Uyên mất”, gán nguồn Chương 1.
- **Chương 1:** ghi Lâm Chinh rời trấn và mất liên lạc; ba tháng trước gia đình nhận quan tài cùng lời báo thi thể đã được liệm.
- **Chương 1 về sau:** ngôi mộ có Hắc Quan và lời xác nhận cha Lâm Uyên chưa từng nằm trong mộ.
- **Hồ sơ nhân vật:** [[Lâm Chinh]] giữ trạng thái sinh tử unknown, phân biệt lời báo tử với sự thật chưa rõ.
- **Mốc bổ sung:** Chương 12 nhắc ngôi mộ rỗng; Chương 32 cho Lâm Uyên ghi nhớ cha nhưng không xác nhận sinh tử.
- **Xung đột:** timeline biến lời báo tử thành sự thật khách quan “chết”; nguồn truyện/hồ sơ không xác nhận cái chết.
- **Ảnh hưởng:** continuity nhân vật, bí ẩn Hắc Quan và động cơ Lâm Uyên.
- **Xử lý:** không sửa timeline, không khẳng định Lâm Chinh sống hoặc chết. Giữ xung đột cho tới quyết định tác giả.
- **Phương án cần duyệt nếu muốn đồng bộ timeline:** “được báo đã chết / gia đình nhận tin và làm tang”. Đây chỉ là đề xuất sửa câu, không được áp dụng trong lần audit.

### 🟡 Minor — đã chuẩn hóa ở menu trong commit này

Menu trước đây dùng một số nhãn vượt quá mức xác nhận: gọi Cửu Thiên là “thượng giới”, Ngoài Cửu Thiên là “ngoại vực”, Ngoại Sinh Linh là “linh thể dị chủng”, và biến hồ sơ thế lực dự kiến thành thế lực như đã triển khai. Menu đã được đổi thành mô tả trung tính, phân biệt hồ sơ dự kiến/chưa xác nhận đã xuất hiện; ba file nền không đổi.

### 🔵 Uncertain — dữ liệu phải để UNKNOWN

1. **Vũ trụ:** bản chất Ngoài Cửu Thiên; đó có phải vị diện riêng; quan hệ thật với Quy Khư/Ngoại Sinh Linh.
2. **Bản đồ:** tọa độ, phương hướng liên vùng, cự ly, tốc độ đi lại, đường biên, truyền tống/phá giới. MAP DATA INCOMPLETE; DISTANCE SYSTEM UNDEFINED; TRAVEL-TIME SYSTEM UNDEFINED.
3. **Vọng Sơn Trấn:** quê nhà Lâm Uyên đã rõ; vị trí hành chính và khoảng cách tới Lăng Vân Thành chưa rõ.
4. **Lịch sử:** các thời đại, niên đại/đơn vị lịch, nguồn hình thành tầng thế giới, thứ tự sự kiện cổ xưa.
5. **Tu luyện:** thọ nguyên/tiểu cảnh giới cho mọi cấp; thiên kiếp, quy tắc sinh tử/phục sinh; quy đổi hệ phái và chiến lực.
6. **Sinh linh:** danh mục chủng tộc đầy đủ; phân biệt canon giữa Mạc Nhân, Di Kỷ Tộc, Ngoại Sinh Linh và các nhóm khác.
7. **Xã hội:** quốc gia, chính trị, luật pháp, kinh tế, tiền tệ, giá tài nguyên, quyền sở hữu địa mạch/cơ chế cai trị.
8. **Nghề nghiệp/vật phẩm:** nghề chuyên môn, cấp bậc, nguồn cung và định giá.
9. **Tri thức xã hội:** ai biết từng bí mật; phân tầng công chúng, tu sĩ, thế lực và độc giả.
10. **Quy Khư / Mạc Pháp / Địa Mạch / Khoảng Trống / Địa Ký:** giữ nguyên độ chắc chắn trong hồ sơ riêng; không gộp khái niệm.

## Các kiểm tra liên tục đã làm

- Thứ bậc Cửu Thiên → Đại Vực → Tiểu Vực → Vân Châu → Lăng Vân Thành thống nhất giữa file nền và hồ sơ địa lý chính.
- Tài liệu nền xác nhận 12 cảnh giới, nhưng không cho phép thêm cảnh giới sau Đạo Chủ.
- Quy Khư là bí mật/hiện tượng quan trọng; giả thuyết về bản chất và quan hệ rộng hơn vẫn là giả thuyết.
- Ngoại Sinh Linh được phân biệt với di cốt: một bên không thuộc thiên địa; bên kia là tàn tích của tồn tại từng thuộc trật tự thiên địa.
- Quét từ khóa chương: Vân Châu xuất hiện ở Ch27/28/30/32; Ngoại Sinh Linh ở Ch31; Mạc Nhân ở Ch28; Vĩnh Sinh Môn ở Ch1/2/4/5/33/44/51. Đây là dấu mốc tìm kiếm, không chứng nhận toàn bộ diễn giải trong hồ sơ.
- Chương 52 là trạng thái truyện hiện tại theo menu; kế hoạch tương lai không tính là sự kiện đã xảy ra.

## Tác giả cần quyết định

### AR-001 — Lâm Chinh

Chọn cách ghi timeline khi tiện rà soát:

- **A.** Giữ “đã chết” như sự thật khách quan và xác nhận hồ sơ unknown cần sửa.
- **B.** Ghi “được báo đã chết/gia đình làm tang”, giữ sinh tử chưa rõ.
- **C.** Cách khác do tác giả chốt.

Không cần giải quyết những UNKNOWN khác để dùng bộ index; chúng được giữ mở.

## Thứ tự xử lý

1. Dùng [[00-DANH MỤC LORE]] làm điểm tra cứu duy nhất.
2. Sau chương mới, cập nhật node và nguồn; không chép lore sang file tổng hợp.
3. Khi có quyết định tác giả cho AR-001, sửa nguồn thích hợp có kiểm soát rồi đóng mục.
4. Khi bản đồ/luật thế giới được chốt, cập nhật hồ sơ gốc trước; index và audit chỉ trỏ tới nguồn.
