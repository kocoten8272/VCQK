---
type: world-source-ledger
status: dang-phat-trien
tags:
  - the-gioi
  - canon
  - information-layers
---

# Sổ Nguồn Và Lớp Tri Thức

> Quy tắc để phân biệt điều tác giả xác nhận, điều đã viết ra, điều một nhân vật tin và điều vẫn là bí ẩn. Không thay thế các file canon nền.

## Thứ tự áp dụng tại repository

Kho truyện đã có thứ tự bảo vệ trong [[00_CANON_PROTECTION]]: ba file nền [[01_CORE_CANON]], [[02_WORLD_LOR|02_WORLD_LORE]] và [[03_PLOT_STRUCTURE]] được bảo vệ; chương không tự động là canon nền. Hệ thống này giữ nguyên quy tắc đó và không sửa ba file nền.

Đặc tả World Lore mới yêu cầu một thang ưu tiên khác, trong đó chương đã xuất bản đứng trên outline. Hai quy tắc này không hoàn toàn đồng nhất. Trong lần triển khai này:

- Không sửa bất kỳ file nền nào.
- Dùng chương làm bằng chứng rằng một sự kiện/chi tiết đã được viết, không tự động nâng thành sự thật khách quan của thế giới.
- Nếu chương và hồ sơ xung đột, giữ cả hai nguồn, ghi CANON CONFLICT / AUTHOR REVIEW REQUIRED trừ khi có chỉ thị tác giả trực tiếp giải quyết.
- Không dùng outline/ghi chú cũ để phủ định canon bảo vệ hoặc chỉ thị trực tiếp mới hơn.

## Phân loại mệnh đề

| Nhãn | Dùng khi | Cách ghi |
|---|---|---|
| **CANON** | Nêu rõ trong nền tảng được bảo vệ hoặc được tác giả xác nhận trực tiếp | Nêu nguồn cụ thể và giới hạn nội dung được xác nhận |
| **DRAFT TEXT** | Nội dung có trong bản thảo nhưng chưa được tác giả chốt thành canon | Ghi số chương và trạng thái bản thảo; không coi là sự thật canon hoặc độc giả đã đọc |
| **INFERRED — NOT CANON** | Suy luận có căn cứ nhưng chưa được xác nhận | Tách riêng, nêu tiền đề; không đưa thành dữ kiện |
| **UNKNOWN** | Không có dữ liệu hoặc cố ý chưa quyết định | Giữ nguyên; không bù chỗ trống |
| **POSSIBLE** | Có dấu vết gợi ý nhưng chưa đủ chứng cứ | Không gộp với canon; ghi giả thuyết và nguồn |
| **CANON CONFLICT** | Hai nguồn đưa ra khẳng định không thể đồng thời đúng | Trích cả hai nguồn, không tự chọn |
| **PLANNED CANON** | Đề xuất/outline được duyệt để phát triển, nhưng chưa diễn ra trong truyện | Gắn nhãn kế hoạch, không đưa vào sự kiện đã xảy ra |
| **SOFT CANON** | Tài liệu tự ghi soft-canon hoặc tác giả cho phép dùng có điều kiện | Chỉ dùng trong phạm vi đã ghi; không mở rộng |
| **CHARACTER BELIEF / RUMOR / RECORD** | Lời nhân vật, lời đồn, cổ tịch hoặc sử liệu chưa được xác nhận khách quan | Gắn nguồn tri thức cụ thể; có thể sai |

## Lớp tri thức

Mỗi mệnh đề có ảnh hưởng tới cốt truyện nên ghi riêng các lớp liên quan. Không mặc định mọi lớp đều biết cùng một điều.

1. **Author Truth** — sự thật tác giả đã xác nhận; không nhất thiết đã lộ cho độc giả.
2. **Restricted / Elite Knowledge** — người hoặc thế lực cụ thể biết; nêu ai và nguồn.
3. **Cultivator Knowledge** — điều tu sĩ thường biết; cần căn cứ trong truyện.
4. **Public Knowledge** — điều thường dân/công chúng biết; không tự suy ra.
5. **Character Belief / Rumor / Historical Record** — một cá nhân/tài liệu tin hoặc kể; có thể sai.
6. **Reader-Facing Reveal** — điều đã công bố/xác nhận cho độc giả; chương còn là nháp chỉ ghi là DRAFT TEXT.
7. **Unknown / Not assigned** — chưa có người biết nào được xác định.

Không dùng nhãn “True Lore” cho suy luận AI. Nếu sự thật tác giả chưa chốt, ghi UNKNOWN.

## Theo dõi nguồn

Mẫu tối thiểu cho node lore quan trọng:

    claim: "Mệnh đề đủ hẹp để kiểm chứng"
    status: CANON | INFERRED — NOT CANON | UNKNOWN | POSSIBLE | CANON CONFLICT | PLANNED CANON
    source:
      - file: "đường dẫn tệp"
        location: "mục / chương / đoạn"
    knowledge_layer: "Author / character / reader / public / unknown"
    confidence: "được xác nhận / gợi ý / chưa rõ"
    last_checked: "YYYY-MM-DD"

Một hồ sơ có thể chứa nhiều mệnh đề ở các trạng thái khác nhau; không gắn một nhãn canon duy nhất cho toàn bộ hồ sơ nếu nội dung gồm sự thật, giả thuyết và hướng phát triển.

## Nguồn đã đối chiếu tại snapshot này

- Nền tảng canon và thứ tự bảo vệ: 00_CANON_PROTECTION.md, 01_CORE_CANON.md, 02_WORLD_LOR.md, 03_PLOT_STRUCTURE.md.
- Hồ sơ thế giới/cơ chế: toàn bộ **33** tệp trong 02-THẾ GIỚI và **24** tệp trong 03-HỆ THỐNG TU LUYỆN.
- Timeline/tư liệu bí mật: **4** tệp trong 05-TIMELINE, **16** tệp trong 07-TƯ LIỆU & BÍ MẬT.
- Bản thảo: **52 chương** được quét chéo theo từ khóa. Kết quả tìm kiếm chỉ hỗ trợ định vị; chương nháp được ghi là DRAFT TEXT, một từ khóa xuất hiện không chứng minh diễn giải trong hồ sơ là canon.

## Ví dụ áp dụng

- **Lâm Uyên là con Lâm Chinh** — chỉ thị tác giả đã xác nhận; không đổi thành Lâm Sơn.
- **Lâm Chinh sinh tử thế nào** — UNKNOWN/CANON CONFLICT giữa cách ghi timeline và hồ sơ/chương; không suy ra ông còn sống.
- **Cửu Thiên không phải toàn bộ thế giới** — canon nền.
- **Ngoài Cửu Thiên là Ma giới/Thần giới** — UNKNOWN; chưa có xác nhận.
- **Mạc Pháp/Địa Mạch** — giữ nhãn soft-canon của tài liệu; không mô tả thành nguyên nhân chắc chắn.
- **Mạc Nhân là Ngoại Sinh Linh** — chưa được xác nhận; phải giữ hai node riêng.
- **Chương/outline nêu một khái niệm** — ghi rõ đó là lần xuất hiện, hồ sơ biên tập hay đề xuất; không suy ra cấp độ nhận thức xã hội.

## Liên kết

- [[00_CANON_PROTECTION]]
- [[01_CORE_CANON]]
- [[02_WORLD_LOR|02_WORLD_LORE]]
- [[03_PLOT_STRUCTURE]]
- [[00-DANH MỤC LORE]]
- [[04-Báo Cáo Audit Lore]]

## Đối chiếu có phạm vi sau Chương 57 — 2026-10-09

| Node/mệnh đề | Lớp nguồn | Giới hạn |
| --- | --- | --- |
| FAC-019 [[Dược Phường Hòa Sinh]] phối lô ba hiệu | DRAFT TEXT Ch49–50; node mới tổng hợp nguồn cũ và Ch57 | Không tự xác định nguyên nhân vón, người mua hoặc gian lận |
| Đinh nhận mình chép mặt sau và nơi nhận chỉ dẫn | Lời tự nhận trong DRAFT TEXT Ch57 | Chưa có người chứng kiến viết/đối người đọc; không xem như chứng cứ hoàn chỉnh |
| Dấu/bàn nhận giấy/lượt công Hòa Sinh | Văn bản xác nhận được báo cuối Ch57 | Không tự nâng người giữ bàn thành người mua hoặc toàn cơ sở thành chủ mưu |
| [[Thẩm Từ Nghi]] được giới thiệu gia chủ/đối nguyên liệu | DRAFT TEXT Ch57, gia chủ/gia phả là thiết kế tác giả đã duyệt trước | Tuổi/tu vi/người nhà khác không tự lộ; giao dịch không thuộc lô Xích Tủy Tán |
| Gỗ trạm được trả, thử nền ngoài cọc được cho tiếp | DRAFT TEXT Ch57 | Không kết luận đã vào hầm/thu hồi Tô Lạc hoặc viện phí trẻ đã chốt |

Phần mới chỉ đối các nguồn liên quan ở mốc này; các số lượng/snapshot cũ trên đây là lịch sử đợt audit, không nhận đã quét lại toàn repository. Tình trạng thật Lâm Chinh tiếp UNKNOWN theo chỉ thị tác giả, không mở lại một xung đột đã được chốt cách xử lý.

## Đối chiếu có phạm vi sau Chương 58 — 2026-10-09

| Node/mệnh đề | Lớp nguồn | Giới hạn |
| --- | --- | --- |
| CHAR-061 [[Tề Duy Cẩn]], nhận việc giao cửa bên Hòa Sinh | DRAFT TEXT Ch58: thẻ trực, xác nhận người phụ trách, Đinh Bá Nghiêm nhận mặt | Không xác định người mua/nguồn tiền hoặc trách nhiệm toàn cơ sở |
| Tề Duy Cẩn đọc/lập phiếu và đề nghị chia lượt giữ hòm sau | Lời tự nhận được ghi Ch58; lời Đinh Bá Nghiêm đối lần đọc/chép, phiếu công/phần lưu | Không giám định chữ, chưa giải ai mở hòm/niêm hoặc mẫu vón; động cơ người đặt là lời cần kiểm |
| Bao nguyên liệu Thẩm Từ Nghi giữ hộ trả tối ngày10 | DRAFT TEXT Ch58: báo kết quả, người làm nhận lượng/thẻ/ký trả | Không kéo giữ hộ nhiều ngày, không tự nhận viện đã mua tất cả |
| LOC-010 [[Nhà Trú Tạm Ven Nam Phố]] sập giữa buổi ngày13 | DRAFT TEXT Ch58: tin báo và hiện trường một phần mái/vách sập | Chủ nhà, kết cấu/nguyên nhân, người sửa và trách nhiệm UNKNOWN |
| Mưa lặp ngày11–13, đường cáng/nền cao | DRAFT TEXT Ch58 | Mưa hiện diện không là điều tra xác định nguyên nhân; không quy Bùi Gia hoặc mạng thuốc |
| CHAR-062 [[Khương Tố Nương]], con sáu tuổi, nghề vá áo/chỗ ở | Tên/nghề/tuổi trẻ/chỗ ở qua lời mẹ; nhận con trực tiếp trong Ch58 | Tuổi thiết kế35 chưa nêu, giới tính/tên trẻ UNKNOWN; khác mẹ con ở viện buổi sáng/xóm lò ngói |
| Mẹ con cùng lượt rời điểm cứu trợ hướng về viện | DRAFT TEXT Ch58, Mạnh Thanh Tễ quyết chuyển/người trực đi cùng | Chưa có cảnh viện nhận/chữa khỏi; chân bị kẹt chưa là chẩn đoán gãy hoặc thương tật cuối |
| Mạnh Thanh Tễ làm cùng đội cứu gần lỗ vách và còn nói cuối58 | DRAFT TEXT Ch58 | Chỗ làm được xem từng phần, không toàn nhà an toàn; biến cố tiếp58–60 vẫn kế hoạch |
| Thử nền Hắc Phong Sơn chậm vì mưa, Tô Tín còn ở viện | Tin/lời gửi ngày12 trong DRAFT TEXT Ch58 | Chưa kết quả mới, lệnh vào hoặc thu hồi Tô Lạc/miếng đồng |

Chỉ đối nguồn liên quan chương mới; số lượng nguồn của snapshot audit đầu vẫn là lịch sử, không nhận đã quét lại toàn kho. Hắc Nha/Cổ Sử và mạng mua thuốc chưa có chứng cứ đồng nhất. Tu vi chính thức Lâm Uyên chưa xác lập hoặc tăng, Dược Khế giữ7/4tháng; sinh tử thật Lâm Chinh tiếp UNKNOWN theo chỉ thị tác giả.
