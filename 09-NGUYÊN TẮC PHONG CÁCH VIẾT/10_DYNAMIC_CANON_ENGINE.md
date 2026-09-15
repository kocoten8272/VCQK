# VẠN CỔ QUY KHƯ

# 10_DYNAMIC_CANON_ENGINE.md

> FILE QUẢN LÝ CANON ĐỘNG — DYNAMIC CANON / WORLD STATE ENGINE
>
> Mục đích:
> Cho phép AI Agent tự động nhận diện, suy luận, cập nhật và duy trì trạng thái nhất quán của toàn bộ thế giới truyện sau mỗi lần viết mới hoặc chỉnh sửa chương.
>
> Đây không phải file lore.
>
> Đây là **BỘ QUY TẮC VẬN HÀNH** để AI quản lý sự thay đổi của lore, nhân vật, công pháp, sinh linh, vật phẩm, thế lực, địa điểm, quan hệ, bí mật, nhân quả và diễn biến cốt truyện.

---

# I. NGUYÊN TẮC TỐI CAO

Mỗi chương mới hoặc mỗi lần chỉnh sửa chương phải được xem là:

> **MỘT LẦN THAY ĐỔI TRẠNG THÁI CỦA TOÀN BỘ THẾ GIỚI.**

AI không được coi chương mới là một văn bản độc lập.

Sau khi chương được viết hoặc chỉnh sửa, AI phải tự hỏi:

> "Sau chương này, thế giới đã thay đổi những gì?"

Không chỉ kiểm tra:

> "Chương này viết có hay không?"

Mà phải kiểm tra:

> "Sau chương này, Canon đã thay đổi ở đâu?"

---

# II. PHÂN BIỆT HAI LOẠI THÔNG TIN

Mọi thông tin xuất hiện trong chương phải được AI phân loại thành:

### 1. INFORMATION

Thông tin mới nhưng chưa chắc làm thay đổi trạng thái lâu dài.

Ví dụ:

* một quán trọ mới;
* một người qua đường;
* một địa danh chỉ được nhắc thoáng qua;
* một món ăn;
* một vật dụng bình thường.

Không nhất thiết phải tạo node.

### 2. STATE CHANGE

Thông tin làm thay đổi trạng thái của thế giới hoặc câu chuyện.

Ví dụ:

* nhân vật mới;
* công pháp mới;
* cảnh giới mới được xác nhận;
* sinh linh mới;
* chủng tộc mới;
* thế lực mới;
* địa điểm quan trọng;
* pháp bảo;
* di vật;
* bí cảnh;
* bí mật mới;
* quan hệ mới;
* nhân quả mới;
* thương thế;
* cái chết;
* phản bội;
* lời thề;
* truyền thừa;
* năng lực mới;
* nhược điểm mới;
* quy tắc thế giới mới;
* thông tin mới về đời thứ chín;
* dấu hiệu liên quan đến Quy Khư;
* dấu hiệu liên quan đến Ngoại Sinh Linh;
* thông tin làm thay đổi nhận thức của Lâm Uyên.

Mọi STATE CHANGE phải được ghi nhận.

---

# III. AUTO NODE DETECTION

Sau mỗi chương, AI phải tự động quét toàn bộ nội dung và tìm:

```text
[NEW CHARACTER]
[UPDATED CHARACTER]
[NEW CREATURE]
[NEW SPECIES]
[NEW TECHNIQUE]
[NEW CULTIVATION]
[NEW DAO]
[NEW TREASURE]
[NEW ITEM]
[NEW LOCATION]
[NEW FACTION]
[NEW SECRET]
[NEW RULE]
[NEW RELATIONSHIP]
[NEW CONFLICT]
[NEW CAUSALITY]
[NEW INJURY]
[NEW DEATH]
[NEW INHERITANCE]
[NEW MYSTERY]
[NEW FORESHADOWING]
[NEW PAYOFF]
[NEW WORLD INFORMATION]
[STATE CHANGE]
```

Nếu phát hiện một thực thể hoặc thông tin đã tồn tại:

> **KHÔNG tạo node mới.**

Phải tìm node cũ và cập nhật nó.

---

# IV. NGUYÊN TẮC "FILL NODE"

Khi phát hiện một thực thể mới, AI phải tự động suy luận những trường thông tin có thể xác định được từ chương.

Ví dụ:

## Nhân vật mới

AI phải cố gắng xác định:

* Tên;
* giới tính;
* chủng tộc;
* tuổi ước tính;
* thân phận;
* địa vị;
* cảnh giới;
* Đại Đạo;
* công pháp;
* thần thông;
* pháp bảo;
* thế lực;
* quan hệ;
* tính cách thể hiện qua hành động;
* mục tiêu;
* động cơ;
* thái độ với Lâm Uyên;
* thông tin mà nhân vật biết;
* thông tin nhân vật không biết;
* bí mật;
* lần xuất hiện đầu tiên;
* trạng thái hiện tại;
* khả năng tái xuất hiện;
* liên hệ với tuyến plot;
* liên hệ với mystery.

Nếu chưa biết:

> ghi `UNKNOWN` hoặc `TBD`.

**Không được tự ý biến suy đoán thành canon.**

---

# V. SUY LUẬN NHƯNG KHÔNG TỰ Ý CANON HÓA

AI được phép suy luận.

Nhưng phải phân biệt:

```text
CANON
INFERENCE
HYPOTHESIS
UNKNOWN
```

### CANON

Thông tin đã được tác phẩm xác nhận.

### INFERENCE

Điều có thể suy ra tương đối chắc chắn từ những gì đã xuất hiện.

### HYPOTHESIS

Giả thuyết có khả năng đúng nhưng chưa được xác nhận.

### UNKNOWN

Chưa đủ dữ liệu để kết luận.

Ví dụ:

Trong chương xuất hiện một sinh linh có thể sống ngoài nhân quả.

AI được phép suy luận:

> "Sinh linh này có khả năng liên quan đến Ngoại Sinh Linh."

Nhưng không được tự động ghi:

> "Sinh linh này chắc chắn là Ngoại Sinh Linh."

Trừ khi tác phẩm đã xác nhận.

---

# VI. KHÔNG ĐƯỢC TỰ Ý VIẾT LẠI CANON

Thứ tự ưu tiên:

```text
01_CORE_CANON
>
02_WORLD_LORE
>
03_PLOT_STRUCTURE
>
04_WRITING_BIBLE
>
các file quản lý phụ trợ
>
nội dung chương mới
>
suy luận của AI
```

Nếu chương mới mâu thuẫn với Canon:

> **KHÔNG âm thầm sửa Canon.**

Phải đánh dấu:

```text
[CANON CONFLICT]
```

và xác định:

* Canon cũ là gì?
* Chương mới nói gì?
* Mâu thuẫn nằm ở đâu?
* Đây có thể là lời nói sai của nhân vật không?
* Đây có thể là nhận thức sai của nhân vật không?
* Đây có thể là thông tin chưa đầy đủ không?
* Đây có thể là bí mật chưa được biết không?
* Hay thực sự cần retcon?

Chỉ thay đổi Canon khi có quyết định rõ ràng.

---

# VII. NHẬN DIỆN "NHÂN QUẢ MỚI"

Sau mỗi chương, AI phải tìm những quan hệ:

> **CAUSE → EVENT → CONSEQUENCE**

Ví dụ:

```text
Lâm Uyên cứu một người
↓
người đó sống sót
↓
người đó ghi nhớ ân tình
↓
sau này trở thành nhân tố trong một thế lực
↓
ảnh hưởng đến một biến cố khác
```

AI phải ghi nhận chuỗi nhân quả này.

Không được chỉ lưu:

> "Lâm Uyên cứu người."

Mà phải lưu:

> "Hành động cứu người đã tạo ra một khoản nhân quả chưa hoàn tất."

Nếu chưa biết hậu quả:

```text
PAYOFF STATUS: OPEN
```

---

# VIII. THE "RIPPLE EFFECT" ENGINE

Mỗi STATE CHANGE phải được kiểm tra khả năng tạo ra ảnh hưởng dây chuyền.

AI phải hỏi:

### 1. Nó ảnh hưởng đến ai?

### 2. Nó ảnh hưởng đến đâu?

### 3. Nó thay đổi quan hệ nào?

### 4. Nó tạo ra vấn đề mới nào?

### 5. Nó giải quyết vấn đề cũ nào?

### 6. Nó tạo ra mystery nào?

### 7. Nó tạo ra foreshadowing nào?

### 8. Nó có thể tạo payoff trong tương lai không?

### 9. Nó có thay đổi lựa chọn tương lai của nhân vật không?

### 10. Nó có thay đổi trạng thái thế giới không?

---

# IX. CÔNG PHÁP MỚI

Khi chương xuất hiện công pháp mới, AI phải tự động tạo hoặc cập nhật node Công Pháp.

Cố gắng xác định:

```text
Tên:
Nguồn gốc:
Người sáng tạo:
Người sử dụng:
Phẩm cấp:
Thuộc tính:
Con đường tu luyện:
Đại Đạo liên quan:
Khả năng:
Điều kiện tu luyện:
Ưu điểm:
Nhược điểm:
Cái giá:
Tương khắc:
Giới hạn:
Nguồn gốc bí ẩn:
Lần xuất hiện:
Trạng thái:
```

Nếu công pháp có liên hệ với:

* Quy Khư;
* đời thứ chín;
* Hắc Quan;
* Ngoại Sinh Linh;
* hệ thống cảnh giới;

phải đánh dấu liên kết.

Không được tự ý xác định nguồn gốc nếu tác phẩm chưa xác nhận.

---

# X. SINH LINH / CHỦNG TỘC MỚI

Khi xuất hiện sinh linh mới:

AI phải xác định:

```text
Tên:
Loại:
Chủng tộc:
Nguồn gốc:
Khu vực sinh sống:
Đặc điểm:
Năng lực:
Nhược điểm:
Cấp độ:
Quan hệ với thiên địa:
Có thuộc luân hồi không?
Có chịu nhân quả không?
Có thuộc hệ thống cảnh giới không?
Có liên quan Ngoại Sinh Linh không?
```

Đặc biệt:

> Không được mặc định mọi sinh linh đều thuộc hệ thống cảnh giới.

Điều này phải phù hợp với Canon rằng Ngoại Sinh Linh không nhất thiết có thể được đánh giá bằng hệ thống cảnh giới thông thường.

---

# XI. NHÂN VẬT MỚI

Nhân vật mới không chỉ là một node tên tuổi.

AI phải theo dõi:

```text
FIRST APPEARANCE
CURRENT STATUS
CURRENT LOCATION
CURRENT GOAL
CURRENT RELATIONSHIPS
KNOWN INFORMATION
UNKNOWN INFORMATION
SECRETS
PROMISES
DEBTS
CONFLICTS
INJURIES
ITEMS
TECHNIQUES
FACTIONS
FUTURE OPEN THREADS
```

Mỗi khi nhân vật xuất hiện lại:

> cập nhật trạng thái hiện tại.

Không tạo bản sao node.

---

# XII. NHÂN VẬT CŨ PHẢI ĐƯỢC CẬP NHẬT

Không chỉ node mới.

Sau mỗi chương, AI phải kiểm tra các nhân vật đã tồn tại:

* cảnh giới có thay đổi không;
* thương thế có thay đổi không;
* tâm lý có thay đổi không;
* mục tiêu có thay đổi không;
* quan hệ có thay đổi không;
* biết thêm điều gì;
* mất điều gì;
* có nợ mới không;
* có lời hứa mới không;
* có bí mật mới không;
* thái độ đối với Lâm Uyên có thay đổi không.

Ví dụ:

```text
Tô Thanh Ly
↓
trước chương: tin tưởng Lâm Uyên 60%
↓
sự kiện mới
↓
tin tưởng 80%
↓
quan hệ mới được ghi nhận
```

Không cần dùng số nếu không phù hợp.

Có thể mô tả bằng trạng thái:

```text
xa lạ
↓
quan sát
↓
tin tưởng
↓
đồng hành
↓
ràng buộc
```

---

# XIII. THƯƠNG THẾ / TÀI NGUYÊN / TRẠNG THÁI

AI phải theo dõi trạng thái vật lý và tài nguyên quan trọng.

Ví dụ:

```text
Lâm Uyên:
- thương thế: gãy một xương sườn
- linh lực: suy giảm
- pháp bảo: Hắc Quan
- vật phẩm: ngọc giản
- công pháp: Quy Khư Quyết
```

Nếu chương sau sử dụng lại:

> phải căn cứ vào trạng thái mới nhất.

Không được tự động hồi phục nhân vật chỉ vì chương mới bắt đầu.

---

# XIV. DEATH / LOSS / PERMANENT CHANGE

Nếu một nhân vật chết:

AI phải cập nhật:

```text
STATUS = DEAD
```

Nhưng đồng thời phải kiểm tra:

* ai biết người đó chết;
* ai không biết;
* vật phẩm còn lại;
* di sản;
* lời hứa chưa hoàn thành;
* nhân quả chưa giải quyết;
* ảnh hưởng đến người sống;
* ảnh hưởng đến plot;
* ảnh hưởng đến mystery.

Một cái chết quan trọng không được chỉ ghi:

> "Nhân vật X đã chết."

Mà phải theo dõi:

> **Death → Emotional Consequence → Decision Change → Future Consequence**

---

# XV. MYSTERY AUTO-TRACKING

Mỗi khi chương xuất hiện thông tin chưa giải thích hoàn toàn:

AI phải kiểm tra xem nó có phải:

```text
MYSTERY
FORESHADOWING
OPEN QUESTION
POSSIBLE PAYOFF
```

hay không.

Ví dụ:

> Hắc Quan phản ứng khi Lâm Uyên chạm vào.

AI phải ghi:

```text
MYSTERY:
Tại sao Hắc Quan phản ứng với Lâm Uyên?

STATUS:
OPEN

KNOWN:
Hắc Quan phản ứng.

UNKNOWN:
Nguyên nhân.

POSSIBLE CONNECTION:
Lâm Uyên / đời thứ chín / Quy Khư.

PAYOFF:
TBD
```

Không tự ý giải thích.

---

# XVI. FORESHADOWING AUTO-TRACKING

Nếu một chi tiết có khả năng trở thành manh mối về sau:

AI phải ghi:

```text
FORESHADOWING ID:
F-XXXX

CHAPTER:
Chương X

DETAIL:
...

SURFACE INTERPRETATION:
...

POSSIBLE FUTURE INTERPRETATION:
...

LINKED MYSTERY:
...

PAYOFF:
OPEN
```

Foreshadowing phải có khả năng được hiểu hợp lý ở thời điểm xuất hiện.

---

# XVII. PAYOFF AUTO-TRACKING

Khi một bí mật, lời hứa, nhân quả hoặc foreshadowing được giải quyết:

AI phải cập nhật:

```text
STATUS:
OPEN
→ PARTIALLY PAID
→ PAID
```

Sau khi payoff:

AI phải kiểm tra:

> "Payoff này có tạo ra câu hỏi mới không?"

Nếu có:

> tạo OPEN THREAD mới.

Nguyên tắc:

> **Mở một nút → tháo một nút → xuất hiện một nút sâu hơn.**

Không được để toàn bộ mystery biến mất sau một lần giải thích.

---

# XVIII. PLOT AUTO-UPDATE

Sau mỗi chương, AI phải cập nhật:

```text
CURRENT ARC
CURRENT OBJECTIVE
CURRENT CONFLICT
CURRENT STAKES
CURRENT CHARACTER STATE
CURRENT WORLD STATE
OPEN THREADS
CLOSED THREADS
NEW THREADS
UNRESOLVED CONSEQUENCES
NEXT PRESSURE
```

AI phải biết:

> "Chúng ta đang đứng ở đâu trong câu chuyện?"

và:

> "Nếu viết tiếp chương sau, những thứ nào đang tồn tại và có khả năng tác động?"

---

# XIX. WORLD STATE SNAPSHOT

Sau mỗi chương hoàn thành, AI phải tạo một trạng thái logic:

```text
WORLD STATE BEFORE
↓
EVENTS
↓
CHARACTER CHANGES
↓
WORLD CHANGES
↓
NEW INFORMATION
↓
NEW MYSTERIES
↓
NEW CAUSALITY
↓
WORLD STATE AFTER
```

Điều này đặc biệt quan trọng với truyện dài.

---

# XX. KHÔNG ĐƯỢC "RESET" TRẠNG THÁI

Chương mới không bắt đầu từ trạng thái mặc định.

AI phải luôn đọc trạng thái mới nhất trước khi viết.

Ví dụ:

Nếu chương 20:

> Lâm Uyên bị thương.

Thì chương 21 phải nhớ thương thế.

Nếu chương 21:

> Lâm Uyên dùng thuốc.

Thì chương 22 phải biết thương thế đã thay đổi.

Không được để nhân vật:

> "reset HP" sau mỗi chương.

---

# XXI. CHƯƠNG ĐƯỢC CHỈNH SỬA CŨNG PHẢI TRIGGER UPDATE

Đây là nguyên tắc bắt buộc.

Nếu chương cũ được chỉnh sửa:

> AI phải coi đó là một STATE CHANGE mới.

Không được chỉ sửa văn bản.

Phải thực hiện:

```text
OLD CHAPTER STATE
↓
COMPARE
↓
DETECT DIFFERENCES
↓
IDENTIFY STATE CHANGES
↓
UPDATE NODES
↓
UPDATE RELATIONSHIPS
↓
UPDATE MYSTERIES
↓
UPDATE FORESHADOWING
↓
UPDATE PAYOFF
↓
UPDATE TIMELINE
↓
CHECK CANON CONFLICT
```

---

# XXII. DIFFERENTIAL UPDATE

AI không được mỗi lần sửa chương lại viết lại toàn bộ database.

Chỉ cập nhật phần thay đổi.

Ví dụ:

```text
Chương 18 cũ:
Lâm Uyên gặp A.

Chương 18 mới:
Lâm Uyên gặp A và nhận được ngọc giản.
```

AI phải:

```text
GIỮ NGUYÊN:
- cuộc gặp A

THÊM:
- ngọc giản

CẬP NHẬT:
- inventory của Lâm Uyên
- mystery nếu ngọc giản có bí mật
```

---

# XXIII. TEMPORAL CONSISTENCY

AI phải kiểm tra tính nhất quán theo thời gian.

Không được để:

```text
Chương 30:
Nhân vật A đã chết.

Chương 45:
Nhân vật A xuất hiện bình thường.
```

Trừ khi có giải thích hợp lý như:

* phân thân;
* hồi sinh;
* giả chết;
* luân hồi;
* ký ức;
* tồn tại khác;
* hoặc cơ chế đặc biệt đã được Canon cho phép.

Nếu chưa có giải thích:

```text
[TEMPORAL CONFLICT]
```

---

# XXIV. KNOWLEDGE STATE

AI phải phân biệt:

```text
AUTHOR TRUTH
READER KNOWLEDGE
CHARACTER KNOWLEDGE
FALSE BELIEF
UNKNOWN
```

Ví dụ:

```text
AUTHOR TRUTH:
X thực sự là Ngoại Sinh Linh.

LÂM UYÊN:
chỉ nghi ngờ.

ĐỘC GIẢ:
chưa chắc chắn.

NHÂN VẬT A:
tin rằng X là yêu thú.
```

Không được để AI vô tình cho Lâm Uyên biết điều mà hắn chưa biết.

---

# XXV. INFERENCE ENGINE

Khi xuất hiện dữ kiện mới, AI được phép thực hiện suy luận:

```text
FACT A
+
FACT B
+
FACT C
=
POSSIBLE INFERENCE
```

Nhưng mọi suy luận phải có độ tin cậy:

```text
HIGH
MEDIUM
LOW
```

Ví dụ:

```text
FACT:
Hắc Quan phản ứng với Lâm Uyên.

FACT:
Hắc Quan có liên hệ với đời thứ chín.

INFERENCE:
Lâm Uyên có thể có quan hệ nhân quả với Hắc Quan.

CONFIDENCE:
HIGH

CANON:
CHƯA XÁC NHẬN
```

---

# XXVI. TỰ ĐỘNG PHÁT HIỆN RETCON

Nếu thông tin mới khiến lore cũ trở nên không hợp lý:

AI phải đánh dấu:

```text
[POSSIBLE RETCON]
```

Không tự sửa.

Đưa ra:

```text
OLD STATE
NEW STATE
CONFLICT
POSSIBLE EXPLANATIONS
RECOMMENDED ACTION
```

Sau đó chờ quyết định của tác giả nếu thay đổi Canon là cần thiết.

---

# XXVII. NODE RELATIONSHIP GRAPH

Mỗi node quan trọng phải có liên kết.

Ví dụ:

```text
Lâm Uyên
├── uses → Quy Khư Quyết
├── carries → Nhân quả đời thứ chín
├── connected_to → Hắc Quan
├── follows → Quy Khư Đạo
├── knows → Tô Thanh Ly
├── located_at → Lăng Vân Thành
└── mystery → Hệ thống khống chế thiên địa
```

Một node mới không chỉ tồn tại độc lập.

AI phải tìm:

> "Node này liên quan đến những node nào đã tồn tại?"

---

# XXVIII. NODE IMPORTANCE

Không phải mọi node đều quan trọng như nhau.

AI phân loại:

```text
TIER 0 — CORE CANON
TIER 1 — MAJOR PLOT
TIER 2 — IMPORTANT CHARACTER / WORLD
TIER 3 — SUPPORTING
TIER 4 — TEMPORARY
```

TIER càng cao:

> càng phải được theo dõi lâu dài.

---

# XXIX. AUTO-CONSOLIDATION

Nếu một node xuất hiện nhiều lần dưới các tên khác nhau:

AI phải phát hiện khả năng trùng lặp.

Ví dụ:

```text
Hắc Quan
Hắc sắc quan tài
Quan tài đen
```

Có thể là cùng một node.

AI không được tự tạo ba node độc lập nếu ngữ cảnh cho thấy chúng có thể là một.

Đánh dấu:

```text
[POSSIBLE DUPLICATE]
```

và kiểm tra.

---

# XXX. AFTER-CHAPTER UPDATE PROTOCOL

Sau mỗi lần hoàn thành một chương, AI phải thực hiện theo thứ tự:

```text
STEP 1
Đọc chương vừa hoàn thành.

STEP 2
So sánh với Canon hiện tại.

STEP 3
Extract toàn bộ NEW INFORMATION.

STEP 4
Detect STATE CHANGES.

STEP 5
Detect NEW NODES.

STEP 6
Update EXISTING NODES.

STEP 7
Update CHARACTER STATES.

STEP 8
Update WORLD STATE.

STEP 9
Update RELATIONSHIPS.

STEP 10
Update CAUSALITY.

STEP 11
Update MYSTERY TRACKER.

STEP 12
Update FORESHADOWING.

STEP 13
Update PAYOFF TRACKER.

STEP 14
Update TIMELINE.

STEP 15
Check CANON CONFLICT.

STEP 16
Check TEMPORAL CONSISTENCY.

STEP 17
Run RIPPLE EFFECT analysis.

STEP 18
Create NEW OPEN THREADS if necessary.

STEP 19
Generate CURRENT WORLD STATE.

STEP 20
Only then consider the chapter fully completed.
```

---

# XXXI. AFTER-EDIT UPDATE PROTOCOL

Nếu chỉnh sửa bất kỳ chương nào:

```text
OLD VERSION
↓
NEW VERSION
↓
DIFF ANALYSIS
↓
REMOVED INFORMATION
↓
ADDED INFORMATION
↓
CHANGED INFORMATION
↓
AFFECTED NODES
↓
AFFECTED RELATIONSHIPS
↓
AFFECTED MYSTERIES
↓
AFFECTED FORESHADOWING
↓
AFFECTED PAYOFFS
↓
AFFECTED FUTURE EVENTS
↓
CANON CHECK
```

Đặc biệt:

> **Thông tin bị xóa khỏi chương cũng phải được kiểm tra.**

Ví dụ:

Chương cũ từng giới thiệu:

> "Lâm Uyên nhận được ngọc giản."

Sau khi chỉnh sửa và xóa đoạn đó:

AI phải xóa hoặc đảo trạng thái:

```text
Lâm Uyên INVENTORY:
Ngọc giản
```

nếu ngọc giản không còn tồn tại trong phiên bản mới.

---

# XXXII. FUTURE IMPACT ANALYSIS

Mỗi STATE CHANGE quan trọng phải có:

```text
IMMEDIATE EFFECT
SHORT-TERM EFFECT
LONG-TERM POSSIBILITY
```

Ví dụ:

```text
Nhân vật X chết.

Immediate:
Lâm Uyên mất đồng minh.

Short-term:
Lâm Uyên thay đổi mục tiêu.

Long-term:
Cái chết có thể ảnh hưởng đến một thế lực khác.
```

Nếu chưa biết:

```text
LONG-TERM:
TBD
```

Không được ép tạo payoff.

---

# XXXIII. "CONSERVATIVE INFERENCE" RULE

Khi không đủ dữ liệu:

> **THÀ GHI UNKNOWN CÒN HƠN TỰ BỊA CANON.**

AI phải ưu tiên:

```text
UNKNOWN
>
INFERENCE
>
HYPOTHESIS
```

và chỉ chuyển thành:

```text
CANON
```

khi tác phẩm thực sự xác nhận.

---

# XXXIV. "NEW CHAPTER = NEW STATE" RULE

Mỗi chương phải được coi là:

> **một snapshot mới của thế giới.**

Ví dụ:

```text
CHAPTER 10 STATE
↓
CHAPTER 11 STATE
↓
CHAPTER 12 STATE
↓
CHAPTER 13 STATE
```

AI phải có khả năng trả lời:

> "Tại thời điểm cuối chương 13, Lâm Uyên đang ở đâu, biết gì, có gì, bị thương ra sao, quan hệ với ai, đang theo đuổi điều gì và những vấn đề nào còn mở?"

Nếu không trả lời được:

> State tracking chưa hoàn thành.

---

# XXXV. CHAPTER COMPLETION CONDITION

Một chương chỉ được coi là:

> **COMPLETED**

khi cả hai điều kiện đều đạt:

### WRITING COMPLETE

Văn chương đã hoàn thành.

### STATE UPDATE COMPLETE

Canon động đã được cập nhật.

Do đó:

```text
WRITE CHAPTER
+
UPDATE WORLD
=
CHAPTER COMPLETE
```

Không phải:

```text
WRITE CHAPTER
=
CHAPTER COMPLETE
```

---

# XXXVI. FINAL SELF-CHECK

Sau mỗi chương, AI phải tự kiểm tra:

```text
[ ] Có nhân vật mới không?
[ ] Có nhân vật cũ thay đổi không?
[ ] Có sinh linh mới không?
[ ] Có chủng tộc mới không?
[ ] Có công pháp mới không?
[ ] Có Đại Đạo mới không?
[ ] Có cảnh giới mới không?
[ ] Có vật phẩm mới không?
[ ] Có pháp bảo mới không?
[ ] Có địa điểm mới không?
[ ] Có thế lực mới không?
[ ] Có quy tắc thế giới mới không?
[ ] Có bí mật mới không?
[ ] Có mystery mới không?
[ ] Có foreshadowing mới không?
[ ] Có payoff không?
[ ] Có nhân quả mới không?
[ ] Có quan hệ mới không?
[ ] Có thương thế mới không?
[ ] Có cái chết không?
[ ] Có mất mát không?
[ ] Có trạng thái nhân vật thay đổi không?
[ ] Có trạng thái thế giới thay đổi không?
[ ] Có mâu thuẫn Canon không?
[ ] Có mâu thuẫn timeline không?
[ ] Có thông tin bị xóa do chỉnh sửa không?
[ ] Có node bị trùng không?
[ ] Có ripple effect không?
[ ] Có open thread mới không?
[ ] Có trạng thái nào cần cập nhật cho chương sau không?
```

---

# XXXVII. NGUYÊN TẮC CUỐI CÙNG

AI không chỉ là:

> **người viết chương.**

AI phải hoạt động như:

> **NGƯỜI QUẢN LÝ TRẠNG THÁI CỦA TOÀN BỘ TIỂU THUYẾT.**

Mỗi hành động trong truyện đều có khả năng tạo ra:

```text
THÔNG TIN
↓
QUAN HỆ
↓
NHÂN QUẢ
↓
HẬU QUẢ
↓
THAY ĐỔI NHÂN VẬT
↓
THAY ĐỔI THẾ GIỚI
↓
MYSTERY
↓
FORESHADOWING
↓
PAYOFF
↓
DIỄN BIẾN MỚI
```

Vì vậy:

> **Không có chương nào thực sự "đứng riêng".**

Mọi chương đều phải trở thành một phần của **trạng thái liên tục của Vạn Cổ Quy Khư**.

---

# XXXVIII. MASTER COMMAND

Khi được yêu cầu viết hoặc chỉnh sửa chương, AI phải mặc định thực hiện:

> **WRITE → ANALYZE → UPDATE → VERIFY → COMMIT**

Trong đó:

### WRITE

Viết/chỉnh sửa chương theo Writing Bible.

### ANALYZE

Phân tích tất cả thay đổi về nhân vật, thế giới, lore, công pháp, sinh linh, quan hệ, nhân quả và plot.

### UPDATE

Cập nhật các node và tracker liên quan.

### VERIFY

Kiểm tra Canon, timeline, knowledge state, mystery, foreshadowing và continuity.

### COMMIT

Xác nhận trạng thái mới của truyện là trạng thái chính thức hiện tại.

Không được bỏ qua bước UPDATE và VERIFY chỉ vì chương không xuất hiện "lore lớn".

Ngay cả một cuộc hội thoại nhỏ cũng có thể tạo ra:

> **một thay đổi quan hệ, một khoản nhân quả, một thông tin mới hoặc một lựa chọn sẽ ảnh hưởng đến hàng chục chương sau.**

Đó chính là lý do mọi chương phải được xem như một **state transition** của toàn bộ Vạn Cổ Quy Khư.
