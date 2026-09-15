# VẠN CỔ QUY KHƯ

# 00_CANON_PROTECTION.md

> SYSTEM RULE — CANON PROTECTION & IMMUTABLE FOUNDATION
>
> File này có mức ưu tiên tối cao trong toàn bộ Project.
>
> Mục đích:
> Bảo vệ ba file nền tảng:
>
> * `01_CORE_CANON.md`
> * `02_WORLD_LORE.md`
> * `03_PLOT_STRUCTURE.md`
>
> khỏi việc bị AI tự ý sửa đổi, ghi đè, retcon, hợp nhất hoặc thay đổi trong quá trình viết và cập nhật Dynamic Canon.

---

# I. THREE IMMUTABLE FOUNDATION FILES

Ba file sau được xem là:

> **IMMUTABLE FOUNDATION**

```text
01_CORE_CANON.md
02_WORLD_LORE.md
03_PLOT_STRUCTURE.md
```

AI:

* ĐƯỢC ĐỌC.
* ĐƯỢC PHÂN TÍCH.
* ĐƯỢC ĐỐI CHIẾU.
* ĐƯỢC SUY LUẬN TỪ.
* ĐƯỢC DÙNG LÀM CƠ SỞ VIẾT TRUYỆN.

Nhưng:

> **KHÔNG ĐƯỢC TỰ Ý SỬA NỘI DUNG.**

---

# II. ABSOLUTE READ-ONLY RULE

Đối với ba file:

```text
01_CORE_CANON.md
02_WORLD_LORE.md
03_PLOT_STRUCTURE.md
```

AI phải coi chúng như:

```text
READ ONLY
```

AI tuyệt đối không được:

* thêm dòng;
* xóa dòng;
* sửa câu;
* đổi tên;
* đổi cấu trúc;
* đổi thứ tự;
* viết lại;
* hợp nhất;
* tách file;
* thay thế nội dung;
* tự động cập nhật;
* tự động đồng bộ;
* tự động retcon.

Ngay cả khi nội dung chương mới dường như mâu thuẫn với ba file này:

> **KHÔNG ĐƯỢC TỰ SỬA BA FILE.**

---

# III. PRIORITY HIERARCHY

Thứ tự quyền lực:

```text
00_CANON_PROTECTION
        ↓
01_CORE_CANON
        ↓
02_WORLD_LORE
        ↓
03_PLOT_STRUCTURE
        ↓
04_WRITING_BIBLE
        ↓
05+ SUPPORTING FILES
        ↓
DYNAMIC CANON
        ↓
CHAPTERS
        ↓
AI INFERENCE
```

Không có file cấp thấp nào được tự động ghi đè file cấp cao hơn.

Đặc biệt:

```text
CHAPTER
≠
CANON
```

Một thông tin xuất hiện trong chương mới không tự động trở thành Canon nền tảng.

---

# IV. NEW INFORMATION DOES NOT AUTOMATICALLY MODIFY CANON

Khi chương mới xuất hiện:

* nhân vật;
* công pháp;
* sinh linh;
* địa điểm;
* thế lực;
* vật phẩm;
* cảnh giới;
* Đại Đạo;
* bí mật;
* quy tắc;
* sự kiện;
* quan hệ;
* nhân quả;

AI phải cập nhật vào hệ thống Dynamic Canon hoặc node tương ứng.

Không được cập nhật trực tiếp vào:

```text
01_CORE_CANON.md
02_WORLD_LORE.md
03_PLOT_STRUCTURE.md
```

---

# V. DYNAMIC CANON IS A CHILD LAYER

Dynamic Canon có nhiệm vụ:

> **THEO DÕI THẾ GIỚI.**

Không có nhiệm vụ:

> **THAY ĐỔI NỀN TẢNG CỦA THẾ GIỚI.**

Ví dụ:

```text
01_CORE_CANON
        ↓
Quy Khư Đạo là Đại Đạo của Lâm Uyên

CHAPTER 25
        ↓
Lâm Uyên phát hiện một năng lực mới của Quy Khư Đạo

DYNAMIC CANON
        ↓
Tạo / cập nhật node năng lực

01_CORE_CANON
        ↓
KHÔNG ĐỤNG VÀO
```

---

# VI. CANON PROMOTION SYSTEM

Một thông tin mới chỉ được phép trở thành Canon nền tảng thông qua quy trình:

```text
NEW INFORMATION
↓
DYNAMIC NODE
↓
INFERENCE
↓
REPEATED EVIDENCE
↓
CANON CANDIDATE
↓
AUTHOR APPROVAL
↓
CANON PROMOTION
```

Không được:

```text
NEW INFORMATION
↓
AUTO CANON
```

---

# VII. CANON CANDIDATE

Nếu AI nhận thấy một thông tin mới đủ quan trọng để có khả năng trở thành Canon:

Tạo:

```text
CANON CANDIDATE
```

Ví dụ:

```text
CANON CANDIDATE

Thông tin:
Hắc Quan có phản ứng đặc biệt với Lâm Uyên.

Nguồn:
Chương 27.

Hiện trạng:
INFERENCE.

Liên hệ:
Lâm Uyên / đời thứ chín / Quy Khư.

Confidence:
HIGH.

Trạng thái:
PENDING AUTHOR APPROVAL.
```

Không được đưa thông tin này vào `01_CORE_CANON.md` cho đến khi được xác nhận.

---

# VIII. CANON CONFLICT PROTOCOL

Nếu chương mới mâu thuẫn với ba file nền tảng:

AI phải dừng việc cập nhật Canon.

Tạo cảnh báo:

```text
[CANON CONFLICT]
```

Sau đó báo cáo:

```text
FILE:
01 / 02 / 03

CANON CURRENT:
...

NEW INFORMATION:
...

CONFLICT:
...

POSSIBLE EXPLANATION:
...

SEVERITY:
LOW / MEDIUM / HIGH / CRITICAL

RECOMMENDATION:
...
```

---

# IX. KHÔNG ĐƯỢC GIẢI QUYẾT CONFLICT BẰNG CÁCH SỬA CANON

AI tuyệt đối không được làm:

```text
Canon cũ
+
Chapter mới
=
AI tự sửa Canon
```

Thay vào đó:

```text
Canon cũ
+
Chapter mới
=
Conflict Report
```

Chỉ tác giả mới quyết định:

```text
KEEP OLD CANON
hoặc
RETCON
hoặc
EXPLAIN THROUGH STORY
```

---

# X. MISTAKEN INFORMATION IS ALLOWED

Một nhân vật trong truyện có thể nói sai.

Một cổ tịch có thể sai.

Một truyền thuyết có thể sai.

Một nhân vật có thể hiểu sai.

Độc giả có thể hiểu sai.

Vì vậy:

> **Thông tin xuất hiện trong chương không mặc định là sự thật khách quan.**

AI phải phân biệt:

```text
FACT
CHARACTER BELIEF
RUMOR
HISTORICAL RECORD
FALSE INFORMATION
INFERENCE
HYPOTHESIS
AUTHOR CANON
```

Không được sửa Canon chỉ vì một nhân vật nói điều trái với Canon.

---

# XI. AUTHOR TRUTH ALWAYS SURVIVES CHARACTER ERROR

Ví dụ:

Canon:

> Ngoại Sinh Linh không thuộc thiên địa.

Một nhân vật nói:

> "Đó chỉ là một loại yêu thú cổ đại."

AI phải ghi:

```text
CHARACTER BELIEF:
Đó là yêu thú.

AUTHOR CANON:
Ngoại Sinh Linh không thuộc thiên địa.

STATUS:
Character is mistaken.
```

Không được sửa `01_CORE_CANON.md`.

---

# XII. UNKNOWN MUST REMAIN UNKNOWN

Nếu ba file nền tảng nói:

```text
TBD
UNKNOWN
CHƯA XÁC ĐỊNH
???
```

AI phải giữ nguyên trạng thái đó.

Không được tự lấp chỗ trống chỉ vì:

> "AI nghĩ phương án này hợp lý."

Ví dụ:

```text
Đạo Chủ → ??? → ??? → ???
```

AI không được tự quyết định:

```text
Đạo Chủ → Siêu Đạo → Hỗn Độn → Sáng Thế
```

trừ khi tác giả chính thức xác nhận.

---

# XIII. PROTECT LONG-TERM MYSTERIES

Các bí mật dài hạn phải được bảo vệ đặc biệt.

Bao gồm nhưng không giới hạn:

```text
Đời thứ chín
Quy Khư
Quy Khư Đạo
Hắc Quan
Ngoại Sinh Linh
Hệ thống khống chế thiên địa
Giới hạn cảnh giới
Đạo Chủ
Nguồn gốc thế giới
Ngoài Cửu Thiên
```

AI không được tự ý:

* xác nhận bí mật;
* phủ nhận bí mật;
* giải thích nguồn gốc;
* khóa đáp án;
* tạo đáp án cuối cùng.

Nếu xuất hiện bằng chứng mới:

> chỉ cập nhật Mystery / Inference layer.

---

# XIV. PRESERVE AUTHORIAL UNCERTAINTY

Nếu tác giả cố tình để:

```text
TBD
```

thì:

> **TBD LÀ CANON.**

Không được xem TBD là thiếu dữ liệu cần AI bổ sung.

TBD có nghĩa:

> Tác giả chủ động chưa quyết định.

---

# XV. PLOT STRUCTURE PROTECTION

`03_PLOT_STRUCTURE.md` là khung cốt truyện dài hạn.

AI được phép:

* so sánh chương mới với plot;
* xác định chương hiện tại nằm ở đâu;
* phát hiện arc đã tiến triển;
* đề xuất nhánh mới;
* phát hiện plot hole;
* theo dõi open thread.

Nhưng không được tự ý:

* thay đổi ending;
* đổi thứ tự đại arc;
* xóa mystery;
* xác nhận endgame;
* thay đổi tuyến đời thứ chín;
* thay đổi bản chất Quy Khư;
* thay đổi tuyến Ngoại Sinh Linh;
* thay đổi giới hạn cảnh giới.

Nếu cần thay đổi:

```text
[PLOT CHANGE PROPOSAL]
```

---

# XVI. WORLD LORE PROTECTION

`02_WORLD_LORE.md` là nền tảng thế giới.

AI có thể mở rộng:

```text
Vọng Sơn
↓
Lăng Vân Thành
↓
Vân Châu
↓
Tiểu Vực
↓
Đại Vực
↓
Cửu Thiên
```

bằng các node mới.

Nhưng không được tự ý thay đổi cấu trúc nền tảng.

Ví dụ:

Không được tự sửa:

```text
Lăng Vân Thành thuộc Vân Châu.
```

thành:

```text
Lăng Vân Thành thuộc Đại Vực.
```

Nếu chương mới dường như mâu thuẫn:

> tạo `[CANON CONFLICT]`.

---

# XVII. CORE CANON PROTECTION

`01_CORE_CANON.md` là tầng bảo vệ cao nhất.

Các thông tin như:

```text
Lâm Uyên là đời thứ mười.
Đời thứ chín để lại nhân quả.
Nhân quả không phải ký ức.
Quy Khư là khái niệm/trật tự quan trọng.
Quy Khư Đạo là Đại Đạo của Lâm Uyên.
Ngoại Sinh Linh không thuộc thiên địa.
Đạo Chủ chưa được xác định là cảnh giới cuối.
```

phải được xem là:

> **IMMUTABLE FACTS**

cho đến khi tác giả chính thức thay đổi.

---

# XVIII. NO SILENT RETCON

Cấm tuyệt đối:

> **SILENT RETCON**

AI không được âm thầm sửa logic cũ để khiến chương mới trở nên hợp lý.

Nếu cần retcon:

```text
[RETCON PROPOSAL]
```

và phải ghi:

```text
OLD CANON
NEW CANON
REASON
AFFECTED CHAPTERS
AFFECTED NODES
AFFECTED MYSTERIES
AFFECTED FORESHADOWING
AFFECTED PAYOFFS
```

---

# XIX. CASCADE PROTECTION

Một thay đổi Canon có thể ảnh hưởng đến hàng trăm chương.

Vì vậy nếu phát hiện một thay đổi lớn:

AI phải thực hiện:

```text
CANON CHANGE
↓
DEPENDENCY SCAN
↓
AFFECTED CHARACTERS
↓
AFFECTED WORLD LORE
↓
AFFECTED PLOT
↓
AFFECTED MYSTERIES
↓
AFFECTED FORESHADOWING
↓
AFFECTED PAYOFF
↓
AFFECTED TIMELINE
```

Không được chỉ sửa một node rồi bỏ qua hậu quả.

---

# XX. WRITE PROTECTION

Nếu hệ thống Agent có khả năng ghi file tự động:

AI chỉ được phép ghi vào:

```text
DYNAMIC CANON
CHARACTER NODES
WORLD NODES
ITEM NODES
TECHNIQUE NODES
MYSTERY TRACKER
FORESHADOWING TRACKER
PAYOFF TRACKER
TIMELINE
CURRENT WORLD STATE
CHAPTER FILES
```

AI không được tự động ghi vào:

```text
01_CORE_CANON.md
02_WORLD_LORE.md
03_PLOT_STRUCTURE.md
```

---

# XXI. IF WRITE ACCESS CANNOT BE RESTRICTED

Nếu môi trường Obsidian/Agent không hỗ trợ Read-Only thật sự:

AI phải tự áp dụng:

```text
LOGICAL READ-ONLY
```

nghĩa là:

> Không thực hiện thao tác sửa ba file dù hệ thống kỹ thuật cho phép.

Nếu cần thay đổi:

> tạo Proposal thay vì sửa trực tiếp.

---

# XXII. CANON CHANGE REQUEST

Khi tác giả yêu cầu thay đổi Canon, AI phải tạo:

```text
CANON CHANGE REQUEST
```

Format:

```text
# CANON CHANGE REQUEST

Target:
01_CORE_CANON / 02_WORLD_LORE / 03_PLOT_STRUCTURE

Current:
...

Proposed:
...

Reason:
...

Affected Nodes:
...

Affected Chapters:
...

Affected Mysteries:
...

Affected Foreshadowing:
...

Affected Payoffs:
...

Continuity Risk:
LOW / MEDIUM / HIGH / CRITICAL
```

Chỉ sau khi tác giả xác nhận:

> mới được coi thay đổi đó là Canon chính thức.

---

# XXIII. AUTHOR COMMAND HAS HIGHEST EDIT AUTHORITY

Khi tác giả trực tiếp nói:

> "Thay đổi Canon này."

AI phải hiểu đó là:

```text
EXPLICIT CANON CHANGE
```

Nhưng vẫn phải:

1. ghi nhận thay đổi;
2. kiểm tra dependency;
3. xác định các node bị ảnh hưởng;
4. xác định các chương bị ảnh hưởng;
5. cảnh báo continuity nếu có.

Không được chỉ sửa một dòng rồi coi như hoàn tất.

---

# XXIV. DYNAMIC CANON MUST NEVER BECOME CANON BY ACCIDENT

Các trạng thái sau không được tự động trở thành Canon:

```text
INFERENCE
HYPOTHESIS
SPECULATION
POSSIBLE CONNECTION
POSSIBLE ORIGIN
POSSIBLE IDENTITY
POSSIBLE FUTURE
```

Chúng phải giữ nguyên nhãn.

---

# XXV. FINAL PROTECTION CHECK

Trước khi kết thúc mỗi lần:

```text
WRITE
EDIT
UPDATE
DYNAMIC CANON
```

AI phải kiểm tra:

```text
[ ] 01_CORE_CANON không bị sửa ngoài ý muốn.
[ ] 02_WORLD_LORE không bị sửa ngoài ý muốn.
[ ] 03_PLOT_STRUCTURE không bị sửa ngoài ý muốn.
[ ] Không có inference nào bị biến thành Canon.
[ ] Không có hypothesis nào bị biến thành sự thật.
[ ] Không có TBD nào bị AI tự lấp.
[ ] Không có mystery dài hạn nào bị tự ý giải đáp.
[ ] Không có plot structure nào bị tự ý thay đổi.
[ ] Không có silent retcon.
[ ] Không có duplicate Canon.
[ ] Không có timeline conflict chưa được đánh dấu.
[ ] Các thay đổi mới đã được đưa vào Dynamic Canon.
[ ] Các node liên quan đã được cập nhật.
[ ] Các dependency quan trọng đã được kiểm tra.
```

---

# XXVI. MASTER RULE

> **ĐỌC ĐỂ HIỂU.**
>
> **SUY LUẬN ĐỂ HỖ TRỢ.**
>
> **CẬP NHẬT DYNAMIC CANON ĐỂ THEO DÕI.**
>
> **KHÔNG TỰ Ý SỬA CANON NỀN.**

Ba file:

```text
01_CORE_CANON.md
02_WORLD_LORE.md
03_PLOT_STRUCTURE.md
```

được xem như:

> **LUẬT GỐC CỦA VẠN CỔ QUY KHƯ.**

AI có thể phát hiện chúng chưa hoàn hảo.

AI có thể phát hiện mâu thuẫn.

AI có thể nghĩ ra phương án hay hơn.

AI có thể dự đoán tương lai.

Nhưng:

> **AI KHÔNG CÓ QUYỀN TỰ Ý THAY ĐỔI LUẬT GỐC.**

Nếu phát hiện vấn đề:

> **REPORT — DO NOT MODIFY.**

Nếu phát hiện ý tưởng mới:

> **PROPOSE — DO NOT COMMIT.**

If phát hiện mâu thuẫn:

> **FLAG — DO NOT RETCON.**

Nếu phát hiện lore mới:

> **UPDATE DYNAMIC LAYER — DO NOT OVERWRITE FOUNDATION.**

---

# XXVII. SUPREME PRINCIPLE

> **CANON IS THE FOUNDATION.**
>
> **DYNAMIC CANON IS THE MEMORY.**
>
> **WRITING BIBLE IS THE METHOD.**
>
> **CHAPTERS ARE THE EVENTS.**
>
> **AI IS THE MANAGER — NOT THE OWNER OF CANON.**
