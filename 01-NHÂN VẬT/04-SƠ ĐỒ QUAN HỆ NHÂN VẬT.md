---
type: nhan-vat
status: hoan-thien
tags:
  - nhan-vat
  - relationship-map
---

# Sơ Đồ Quan Hệ Nhân Vật

> Bảng nền có căn cứ đến Chương 52; cập nhật Chương 54–64 ở cuối. Đường liền là quan hệ được xác nhận; nét chấm là quan hệ xã hội/đang hình thành. Không suy chức quyền hay huyết thống từ cùng họ.

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
| CHAR-005 | Lâm Uyên | Con | CHAR-007 | Lâm Chinh | Cha Lâm Uyên là Lâm Chinh; số phận thật vẫn mở. |
| CHAR-005 | Lâm Uyên | Con | CHAR-009 | Mẹ Lâm Uyên | Mẹ đã mất; tên riêng chưa rõ. |
| CHAR-005 | Lâm Uyên | Cháu | CHAR-010 | Ông nội Lâm Uyên | Được ông nuôi; không đồng nhất với Lão Đầu. |
| CHAR-005 | Lâm Uyên | Đồng hành, phối hợp nhưng có bất đồng | CHAR-006 | Tô Thanh Ly | Không mặc định tình cảm lãng mạn hay đồng thuận tuyệt đối. |
| CHAR-005 | Lâm Uyên | Người học việc/người hướng dẫn | CHAR-037 | Mạnh Thanh Tễ | Đang học căn bản dược lý trong công việc. |
| CHAR-013 | Tô Lạc | Đồng đội; Tô Lạc cứu Tô Tín | CHAR-019 | Tô Tín | Tô Lạc chết; thi thể chưa được đưa về tại Ch52. |
| CHAR-019 | Tô Tín | Cùng ở viện sau biến cố | CHAR-044 | Trần Dực | Quan hệ trước Hắc Phong Sơn chưa xác định. |
| CHAR-006 | Tô Thanh Ly | Làm hồ sơ/điều tra | CHAR-046 | Tạ Nghiên Chi | Liên hệ công vụ; không có căn cứ về quan hệ riêng. |
| CHAR-044 | Trần Dực | Người được nhắc trong lời kể | CHAR-057 | Tả Tiên Sinh | Lời kể chưa xác minh danh tính hay phe phái. |

## Quan hệ chưa chốt

- Tô Thanh Dương gọi Tô Thanh Ly bằng tên; mức độ thân thuộc/huyết thống chưa được phân định.
- Gia phả Tô Gia chưa xác nhận phần lớn quan hệ cha-con/anh-em; sơ đồ chức vụ không phải phả hệ.
- Không nối các vụ người áo đen, Tả Tiên Sinh, mạng thuốc và người lấy trang giấy nếu chưa có chứng cứ độc lập.

## Quy tắc cập nhật

Mỗi quan hệ cần chiều, loại, mức chắc chắn, sự kiện hình thành và nguồn. Giữ lịch sử khi quan hệ thay đổi, không xóa mốc cũ.

Liên kết: [[MỐI QUAN HỆ]], [[02-SỔ CÁI NHÂN VẬT]], [[05-MA TRẬN TRI THỨC]].


## Liên hệ phát sinh ở Chương 54

| ID A | Nhân vật A | Quan hệ | ID B | Nhân vật B | Căn cứ và giới hạn |
| --- | --- | --- | --- | --- | --- |
| CHAR-006 | Tô Thanh Ly | Người hỏi/dự chứng, để thợ hoàn tất cứu trang | CHAR-058 | Đỗ Hoài Chương | Nhà hong và cổng phụ; chưa xác lập bạn bè hoặc tình cảm riêng. |
| CHAR-005 | Lâm Uyên | Chứng kiến nghề, hỏi bản kê | CHAR-058 | Đỗ Hoài Chương | Không có truyền nghề/thầy trò. |
| CHAR-046 | Tạ Nghiên Chi | Ghi lời khai/đối chiếu | CHAR-058 | Đỗ Hoài Chương | Liên hệ công vụ, giữ trách nhiệm riêng; không kết án. |
| CHAR-037 | Mạnh Thanh Tễ | Tiếp tục hướng dẫn nhận lá và giới hạn sức tay | CHAR-005 | Lâm Uyên | Chưa hướng dẫn tự cân/phối thuốc. |

Kỷ Hành Chu mới được nhắc qua chứng từ, chưa có quan hệ trực tiếp với nhóm trong một cảnh gặp. Sửa ID ở bảng nền theo sổ cái: Lâm Uyên là CHAR-005.

Nguồn: [[Chương 54]], [[Đỗ Hoài Chương]], [[Trạng Thái Truyện Sau Chương 54]].

## Liên hệ được xác lập/nhận diện ở Chương 55

| ID A | Nhân vật A | Quan hệ | ID B | Nhân vật B | Căn cứ và giới hạn |
| --- | --- | --- | --- | --- | --- |
| CHAR-005 | Lâm Uyên | Người dự đối chiếu theo lệnh | CHAR-034 | Kỷ Hành Chu | Thấy quyết toán/hoàn cước, chưa bạn bè hoặc biết toàn bộ đời sống. |
| CHAR-006 | Tô Thanh Ly | Người hỏi và dự chứng | CHAR-034 | Kỷ Hành Chu | Hỏi phần đã làm, không nhận quyền miễn lỗi. |
| CHAR-046 | Tạ Nghiên Chi | Sao/ghi lời có nguồn | CHAR-034 | Kỷ Hành Chu | Liên hệ công vụ, giữ sổ gốc tại quầy. |
| CHAR-006 | Tô Thanh Ly | Đối mặt kiểm hàng Ch47, tên nhận diện Ch55 | CHAR-059 | Phan Kính | Vai đã có ở bến; Ch55 không có cảnh gặp mới. |
| CHAR-034 | Kỷ Hành Chu | Chữ ký ở khâu trước trên chuỗi giấy nhận | CHAR-059 | Phan Kính | Không chứng minh quen nhau hoặc cùng tổ chức. |

Không xác lập Kỷ Hành Chu/Phan Kính là thành viên Hạ Gia từ việc quầy thuê chỗ. Nguồn: [[Chương 47]], [[Chương 55]], [[Trạng Thái Truyện Sau Chương 55]].

## Liên hệ được đối chiếu ở Chương 56

| ID A | Nhân vật A | Quan hệ | ID B | Nhân vật B | Căn cứ và giới hạn |
| --- | --- | --- | --- | --- | --- |
| CHAR-005 | Lâm Uyên | Lần đầu trực tiếp hỏi tại bến | CHAR-059 | Phan Kính | Hỏi nguồn tờ đổi và lựa chọn giữ hàng; không phải lần gặp được hồi tố về Ch47, chưa thành thân hữu. |
| CHAR-006 | Tô Thanh Ly | Đối chứng biên nhận/lựa chọn kéo dây | CHAR-059 | Phan Kính | Có cuộc gặp cũ Ch47; giữ cả chữ ký bồi hoàn của mình và trách nhiệm riêng của Phan Kính. |
| CHAR-046 | Tạ Nghiên Chi | Ghi lời, sao đủ hai mặt tờ đổi | CHAR-059 | Phan Kính | Liên hệ công vụ; không xóa phần kéo dây hoặc bảo đảm chủ thuê sẽ trả công. |
| CHAR-059 | Phan Kính | R: tự khai nhận việc/tờ đổi và lời điều kiện từ | CHAR-060 | Đinh Bá Nghiêm | Phan Kính nói từng đối công ở quầy, có thể nhận người; chưa có đối mặt kiểm lời. Sổ quầy xác nhận tên nhận phiếu, không tự chứng minh mọi phần khai. |
| CHAR-034 | Kỷ Hành Chu | Cùng chuỗi chứng từ, chưa xác nhận quen biết | CHAR-059 | Phan Kính | Có mặt cùng quầy Ch56 nhưng không nhận Phan Kính từng lấy hàng từ mình; không nâng thành quan hệ đồng nghiệp thân quen. |
| CHAR-034 | Kỷ Hành Chu | Chưa nhận người yêu cầu đổi là | CHAR-060 | Đinh Bá Nghiêm | Việc tên Đinh Bá Nghiêm có trong phần lưu không lấp được nhận diện còn thiếu của Kỷ Hành Chu. |
| CHAR-037 | Mạnh Thanh Tễ | Hướng dẫn cách ghi điều trực tiếp thấy | CHAR-005 | Lâm Uyên | Sửa “chưa khô” thành quan sát mặt lá còn ẩm, nghe buổi lấy lời sau chuyến; không dự đối chứng hoặc biết đáp án mặt sau. |

Người phu xe được nhắc trước đây nay dùng hồ sơ chính [[Đinh Bá Nghiêm]] (CHAR-060), không lập thêm người trung gian trùng vai. Không suy quan hệ huyết thống, tổ chức hoặc chủ mua từ cùng quầy/dấu phiếu.

Nguồn: [[Chương 56]], [[Trạng Thái Truyện Sau Chương 56]], [[Phan Kính]], [[Đinh Bá Nghiêm]].

## Liên hệ tiến triển ở Chương 57

| ID A | Nhân vật A | Quan hệ / chuyển biến | ID B | Nhân vật B | Căn cứ và giới hạn |
| --- | --- | --- | --- | --- | --- |
| CHAR-059 | Phan Kính | Trực tiếp nhận người giao giấy, cùng nhận việc bàn giao | CHAR-060 | Đinh Bá Nghiêm | Phan Kính gọi đủ tên, Đinh Bá Nghiêm nhận đã đưa tờ đổi. Hai lời nhận củng cố khâu giao, không chứng minh toàn bộ người thuê/nguồn tiền/việc thuốc bị gì. |
| CHAR-059 | Phan Kính | Từ chối một lượt hợp tác mới | CHAR-060 | Đinh Bá Nghiêm | Không nhận lượt mới chỉ có giấy, thiếu người thuê; nếu gọi được người thuê thì hỏi lại. Chưa cắt mọi hợp tác vĩnh viễn hoặc có lệnh của Tông Sảnh. |
| CHAR-005 | Lâm Uyên | Hỏi trách nhiệm nhận chuyển điều kiện | CHAR-060 | Đinh Bá Nghiêm | Quan hệ trong buổi trình lời; không trả công để lấy lời, chưa thân hữu/thầy trò hoặc biết hết cuộc sống người này. |
| CHAR-046 | Tạ Nghiên Chi | Ghi lời và nhận phần giấy liên quan | CHAR-060 | Đinh Bá Nghiêm | Sao phần sổ cần đối, nhận phiếu công gốc có biên nhận; không giữ toàn sổ hoặc xóa phần trách nhiệm đã nhận. |
| CHAR-042 | Thẩm Từ Nghi | Đối mẫu/điều kiện giao nguyên liệu | CHAR-037 | Mạnh Thanh Tễ | Tiếp xúc nghề nghiệp trực tiếp, giữ thẻ/ngày sơ chế riêng; không xác nhận quan hệ riêng lâu năm. |
| CHAR-042 | Thẩm Từ Nghi | Bán phần đã kiểm, giao giữ hộ phần chờ | CHAR-047 | Viện Chủ Tế Sinh Viện (chưa rõ tên) | Giao dịch mới với viện, điều khoản giữ riêng/báo trước khi gọi xe; không dùng Dược Khế cũ hoặc nhận mua hết. |
| CHAR-005 | Lâm Uyên | Tiếp xúc trong việc giữ thẻ mẫu | CHAR-042 | Thẩm Từ Nghi | Gặp trực tiếp, thấy lựa chọn/người làm được trả công; không tạo quan hệ lãng mạn, nợ riêng hoặc người hướng dẫn mới. |

Theo lời Đinh Bá Nghiêm, người đọc cho chép ở bàn cửa bên [[Dược Phường Hòa Sinh]] là người nhận việc/giữ khoản công chưa chốt; tên thật chưa biết và chưa được đối mặt. Văn bản xác minh dấu/lượt công không tự nối người đó với người mua cuối. Kỷ Hành Chu chưa đối mặt Đinh Bá Nghiêm, lời chưa nhận người Ch56 vẫn giữ riêng.

Nguồn: [[Chương 57]], [[Trạng Thái Truyện Sau Chương 57]], [[Thẩm Từ Nghi]], [[Đinh Bá Nghiêm]].

## Liên hệ được nhận diện/triển khai ở Chương 58

| ID A | Nhân vật A | Quan hệ | ID B | Nhân vật B | Căn cứ và giới hạn |
| --- | --- | --- | --- | --- | --- |
| CHAR-060 | Đinh Bá Nghiêm | Trực tiếp nhận người đã đọc cho chép | CHAR-061 | Tề Duy Cẩn | Tề Duy Cẩn nhận đã đọc/lập phiếu, nhận Đinh Bá Nghiêm chép trước mặt và đọc lại. Hai lời đối cùng phiếu/phần lưu củng cố khâu thuê chép, không chứng minh chủ mua hoặc mọi nguồn tiền. |
| CHAR-005 | Lâm Uyên | Hỏi trách nhiệm giữ thuốc thành hai lượt | CHAR-061 | Tề Duy Cẩn | Liên hệ trong buổi đối công, chưa bạn bè/địch thù thuộc tổ chức hoặc biết toàn bộ đời sống người giữ bàn. |
| CHAR-006 | Tô Thanh Ly | Đối lời và từ chối giao lời Trần Dực thay thuốc | CHAR-061 | Tề Duy Cẩn | Đề nghị trình câu hỏi tới Tông Sảnh; không nói thay Trần Dực hoặc nhận trách nhiệm trả lời cho cả nhóm. |
| CHAR-046 | Tạ Nghiên Chi | Ghi phần tự nhận/sao nguồn liên quan | CHAR-061 | Tề Duy Cẩn | Giữ riêng lý do hắn kể và phần tự thêm; không kết án chủ mua từ tên/thẻ trực. |
| CHAR-062 | Khương Tố Nương | Mẹ | — | Đứa trẻ chưa rõ tên, sáu tuổi theo lời mẹ | Mẹ trực tiếp nhận đứa áo nâu/vạt vá đỏ, trẻ gọi mẹ; giới tính/tên cha chưa nêu, không đồng nhất trẻ xóm lò ngói. |
| CHAR-037 | Mạnh Thanh Tễ | Y sư tiếp nhận/cứu giúp | CHAR-062 | Khương Tố Nương | Xem người trên cáng, hướng dẫn trước chuyển, cho mẹ con cùng tới viện; không xác nhận đã khỏi hoặc thân hữu có từ trước. |
| CHAR-005 | Lâm Uyên | Ghi nhận/đối mẹ con và nơi chuyển | CHAR-062 | Khương Tố Nương | Ghi đủ tên theo lời bà, nhờ người trực dẫn trẻ cho mẹ nhận, ghi cùng lượt; chưa trở thành người chẩn trị hoặc người thân. |
| CHAR-037 | Mạnh Thanh Tễ | Tiếp tục hướng dẫn việc nhẹ trong cứu trợ | CHAR-005 | Lâm Uyên | Giao giữ điểm cáng/danh sách, gọi mới đưa đồ; dừng bước theo tiếng gọi và giữ riêng vải rơi bùn, không dạy quyền tự chữa bệnh. |

Khương Tố Nương và con là gia đình mới trong cảnh nhà trú, tách khỏi mẹ con xóm lò ngói và người mẹ đưa trẻ tới viện sáng ngày 13. Tề Duy Cẩn là hồ sơ chính của vai người đọc cho chép được Đinh Bá Nghiêm nhận; không lập thêm người giữ bàn vô danh trùng vai.

Nguồn: [[Chương 58]], [[Trạng Thái Truyện Sau Chương 58]], [[Tề Duy Cẩn]], [[Khương Tố Nương]].

## Quan hệ theo bản thảo Chương 59

| Người | Liên hệ/đổi trạng thái | Căn cứ và giới hạn |
| --- | --- | --- |
| Mạnh Thanh Tễ → Lâm Uyên | Giao phần chuyển người cần đi gấp khi chính mình bị giữ | Ông còn gọi, đội cứu ở cạnh. Hắn làm theo nhưng vẫn day dứt/sợ; chưa nghi thức bái sư, lời trăng trối hoặc di sản |
| Lâm Uyên → Hồ Nhuận Chi | Ghi/báo tình trạng theo cáng tới viện | Người có nghề quyết và chữa, không để bà thành nguyên nhân có lỗi vì thầy bị nạn |
| Tô Thanh Ly → Lâm Uyên | Giữ đường cáng thầy, trở lại/ngồi cạnh | Không hứa cứu chắc, không nói một lời đã chữa nỗi sợ; nhắc người trên cáng cần tới viện |
| Tô Tín → Lâm Uyên | Hỏi người còn cạnh thầy, nhờ bát cháo | Nạng/viện, không tự tới hiện trường; chưa bỏ việc Tô Lạc |
| Mạnh Thanh Tễ → Hồ Nhuận Chi | Chăm và nhắc đưa gấp | Nghề/trách nhiệm trong cứu trợ, không kết luận quen lâu hoặc nợ tiền |
| Khương Tố Nương/con → người đã xem chân | Hỏi khi nào về | Biết người chăm mình vắng, chưa tự biết chẩn đoán/tương lai của ông |

Hồ Nhuận Chi khác Khương Tố Nương; cùng nghề/chỗ trú không xác lập họ hàng/bạn thân/chung con. Không nhập quan hệ tình cảm thành cơ chế tu luyện.

Nguồn: [[Chương 59]], [[Trạng Thái Truyện Sau Chương 59]], [[Hồ Nhuận Chi]].

## Quan hệ theo bản thảo Chương 60

| Người | Liên hệ/chuyển biến | Căn cứ và giới hạn |
| --- | --- | --- |
| Mạnh Thanh Tễ → Lâm Uyên | Người hướng dẫn qua đời sau cứu chữa; Lâm Uyên gọi “thầy”, nhớ lỗi quấn băng đã được sửa | Quan hệ có hậu quả mất mát trực tiếp. Không có nghi thức bái sư mới, lời trăng trối, trao công pháp hoặc thừa kế sổ/túi thuốc. |
| Viện Chủ Tế Sinh Viện (chưa rõ tên) → Lâm Uyên | Cho ngồi cạnh, giải thích đã làm phần có thể, giao người tiếp việc của viện | Không để Lâm Uyên thay y sư quyết chữa hoặc nhận đồ của người mất làm riêng. Thân nhân vẫn đang được tìm để báo. |
| Tô Thanh Ly → Lâm Uyên | Ở lại bên ghế, đưa nước/vải, chờ hắn tự nhận; cùng nói đã nghĩ về viện sẽ còn kịp | Đồng hành trong nỗi đau, không hứa chữa được đau buồn hoặc dùng việc nhẹ làm mệnh lệnh quên thầy. |
| Tô Tín → Lâm Uyên | Ngồi cạnh sau tin mất, nhờ thêm ghế, vẫn giữ lời nhờ về Tô Lạc | Quan hệ hỗ trợ ở viện; nạng và việc hồi phục không thay đổi, không tự đi núi/cứu hộ. |
| Mạnh Thanh Tễ → Khương Tố Nương, Hồ Nhuận Chi | Người từng chăm/cứu; hai bệnh nhân được báo tin và vẫn được y sư khác tiếp chăm | Không biến người sống được cứu thành người có lỗi vì ông chết, không khẳng định chữa khỏi hoặc quan hệ riêng lâu năm. |
| Mạnh Thanh Tễ → Lưu Định | Người từng sơ cứu, viết giấy trạm ở Ch49; Lưu Định trở lại với câu hỏi nhận chuyến nặng | Người lao động còn cần khám và muốn tới thăm sau khi được phép; không xác nhận thầy từng miễn toàn bộ phí. |
| Lâm Uyên → Lưu Định | Nhận ra người từng được mình quấn lại băng, trực tiếp báo tin mất | Hắn kể phần biết về nạn cứu nhà trú, không tự nhận đã thấy toàn việc nhấc gỗ hoặc trả lời thay y sư về sức cổ tay. |
| Người giám dược trực chưa rõ tên → Lâm Uyên | Nhận phần thuốc, tự kiểm thẻ, giao việc nhẹ và cho ngồi nghỉ | Tiếp việc chăm bệnh, chưa lập quan hệ sư phụ mới hoặc mặc định cùng người đã giúp đêm trước. |

Khương Tố Nương nói rõ với con sáu tuổi Mạnh Thanh Tễ đã mất; trẻ nhìn cửa rồi ngủ cạnh mẹ, chưa được nêu tên/giới tính. Đồ và thi thể Mạnh Thanh Tễ do viện giữ đúng việc đang có, không tạo quan hệ thừa kế. Cái chết không làm mất những nhu cầu chữa bệnh hoặc khép các quan hệ chưa giải.

Nguồn: [[Chương 60]], [[Trạng Thái Truyện Sau Chương 60]], [[Chương 49]], [[Lưu Định]].

## Quan hệ theo bản thảo Chương 61

| Người | Quan hệ có chiều | Người/nhóm | Giới hạn |
| --- | --- | --- | --- |
| Lâm Uyên | Đi cùng viếng, nhận lời muốn giúp tang trong phạm vi | Lưu Định | Lưu Định chưa kéo được xe; không có lời giao chuyến/tang thực tế hoặc thân hữu mới đã chốt |
| Lâm Uyên / Tô Thanh Ly | Làm rõ phần chứng kiến/đối chỗ ở | Khương Tố Nương/con | Mẹ con giữ cùng chỗ, chưa chuyển, viện đối hằng ngày. Không quan hệ nhận nuôi/tài trợ/xóa nợ |
| Bùi Khánh Vân | Giữ bảng công, mang phiếu, nhận về hỏi nguồn | Bùi Gia/người nhận việc | Nghề được bà tự giới thiệu; chưa biết người khảo sát/sửa hoặc tính đúng đủ của cả bảng công |
| Bùi Khánh Vân | Hỏi tin một thợ phụ theo người báo đi cùng | Người làm công vô danh | Quan tâm không xoay quanh nam chính; người thợ chưa xác nhận nơi nhận/sinh tử. Không tự tạo họ hàng |
| Tô Thanh Ly / chấp sự | Hỏi nguồn, giữ phiếu có mảnh nhận | Bùi Khánh Vân/người trông nhà | Liên hệ công việc mới, không xác lập đồng minh/địch thù hoặc tội Bùi Gia |
| Viện chủ | Phối hợp đối mỗi sáng, nhận phần trách nhiệm viện | Người thu xếp chỗ ở nhờ | Phạm vi mấy gian người ấy lo; không quyền phân toàn Nam Phố |

Gia phả Bùi Khánh Vân đã duyệt vẫn thuộc lớp thiết kế, không coi Ch61 đã kể đủ họ hàng.

Nguồn: [[Chương 61]], [[Trạng Thái Truyện Sau Chương 61]].

## Quan hệ theo bản thảo Chương 62

| Người | Liên hệ đã viết | Giới hạn |
| --- | --- | --- |
| Bùi Ninh Viễn → Bùi Khánh Vân/người trông nhà | Người có tên giao việc do cuốn bà giữ, nhận chữ lời hẹn với người trông nhà | Quan hệ nghề đang đối, gia phả chưa kể trong cảnh |
| Lâm Uyên → Bùi Ninh Viễn | Hỏi việc chưa tới trước tai nạn, nghe nhận phần không làm; sau yêu cầu báo cả phần không làm được | Chưa tha thứ/thân hữu/định tội giết thầy, cần người có nghề trong việc hiện tại |
| Bùi Ninh Viễn → người ôm bao/thợ khỏe | Không gọi thợ vào lối chưa xem được; hỏi nhu cầu đồ/sinh kế rồi nhận gọi đội phù hợp | Không quyền chấp pháp hoặc đảm bảo lấy hết, người mất đồ vẫn giận |
| Tô Thanh Ly/Lâm Uyên → người dân chờ đồ | Hỏi phần cần dùng, đối đồ đã ở ngoài; nhận cuộn dây, khung/dao còn trong | Không trả toàn sinh kế, không được cảm tạ hoặc mua lại đồ thay |
| Bùi Ninh Viễn → người phụ trách cứu | Xin phạm vi, giữ lối chưa mở, hỏi lượt làm tiếp và hẹn báo trước tối | Đội cứu quyết chỗ làm, lời hẹn chưa kết quả |
| Bùi Khánh Vân → thợ phụ | Tin qua người cùng đi đã tìm ở trạm khác, bà muốn đối trực tiếp/liên hệ theo bảng công | Không người nhà được nhận diện, không nhân chứng thân thể trực tiếp của bà/Lâm Uyên |

Tô Thanh Ly nghe cùng, giúp lối/chuyến xe/nghỉ; không giải mất mát bằng trấn an. Mạnh Thanh Tễ không có lời đáp/di nguyện mới.

Nguồn: [[Chương 62]], [[Trạng Thái Truyện Sau Chương 62]].

## Quan hệ theo bản thảo Chương 63

| Người | Quan hệ/việc mới | Giới hạn |
| --- | --- | --- |
| Bùi Ninh Viễn → người dẫn đội | Gọi được người trực tiếp nhận lượt sáng15, cần gặp phụ trách cứu/xem lại trước làm | Hẹn chưa thực hiện, không toàn quyền/mái đã an toàn |
| Bùi Ninh Viễn → người đóng giỏ | Dao nói là của mình, cho mượn2ngày; người nhận chọn chỉ dùng phần thô/chiều16 trả bàn Bùi Gia | Không bồi thường đủ/thay khung/tha lỗi trách nhiệm nhà |
| Lâm Uyên → chủ đồ | Không nhận hộ, nhờ tự xem/đọc phần cần nhắn, nghe còn thiếu | Không quyết thay nhu cầu hoặc ký nợ thay |
| Tạ Nghiên Chi → Trần Dực/viện | Đọc trả lời Tông, hỏi ý/sức trước chốt chiều15; ghi nhận nghe hỏi chứ không hứa nhớ thêm | Không đưa bản lời cho người đặt, không tự phán quyết |
| Tô Tín → Trần Dực | Chừa ghế/đặt nước, không nhận hộ | Không gán thân hữu trước chuyến đi hoặc năng lực đi núi |
| Lâm Uyên → giám dược trực | Xin học tiếp, nhận chỗ quan sát sau tưởng niệm nếu sức cho | Chưa thầy trò thay thế/giỏi thuốc/quyền tự xem bệnh |
| Lâm Uyên → chấp sự/người trực | Nhờ báo phần đội lấy đồ, nhờ gọi sáng, chịu nghỉ | Hộ tống/Dược Khế còn, không cần có mặt mọi nơi |

Bùi Ninh Viễn chưa được Lâm Uyên tha lỗi/định tội; việc cho mượn có ích không trả lời nguyên nhân cái chết. Viện chủ tổ chức tưởng niệm đồng nghiệp, chưa quyền tang thay thân nhân.

Nguồn: [[Chương 63]], [[Trạng Thái Truyện Sau Chương 63]].

## Quan hệ theo bản thảo Chương 64

| Người | Liên hệ có chiều | Giới hạn |
| --- | --- | --- |
| Hứa Tĩnh Xuyên → Lâm Uyên | Nhận đúng người đã hẹn63, buổi đầu quan sát/hỏi phần nghe được và giải thích riêng | Không truyền thừa/thay Mạnh Thanh Tễ hoặc cấp quyền tự xem bệnh |
| Hứa Tĩnh Xuyên → y sư/người phụ giúp | Phần hỏi thuốc gọi y sư xem, nhờ người tiếp lượt khi chỉ học trò | Nghề/phạm vi riêng, chưa tên toàn bộ ca |
| Lâm Uyên → người nhận bệnh mới | Nghe họ nói, phân điều đang chịu với điều họ đoán | Không chẩn đoán hoặc trực tiếp nhận kê toa cho họ |
| Viện/nhân viên → người bệnh/người mất | Thay lượt trực để thắp hương, một người rời đáp gian bệnh | Tưởng niệm và chăm cùng vận hành; không bài tiểu sử/di nguyện mới |
| Người theo đội → chủ giỏ | Đồ thật khung gãy/dao sứt được trả, chủ nhận dấu ghép/giữ cả mảnh | Không đền đủ/sửa khung hoặc kết luận ai làm hỏng |
| Chủ giỏ → Bùi Ninh Viễn | Giữ hẹn dao mượn chiều16 vì dao cũ cần sửa | Không trả sớm/quên nợ mượn, không bồi thường đổi trách nhiệm |
| Tô Thanh Ly/chấp sự → Lâm Uyên | Nhận phần đối tin đồ để hắn trở lại ghế/nghỉ | Không hết thương/quản thúc hoặc phân việc cho toàn thành |

Trần Dực ngồi gần cửa có y sư cho, Tô Tín không tự khiêng hoặc nhận lời chiều hộ. Gia đình/di sản người mất chưa đổi.

Nguồn: [[Chương 64]], [[Trạng Thái Truyện Sau Chương 64]].

## Quan hệ theo bản thảo Chương 65

| Người | Liên hệ/chuyển biến | Giới hạn |
| --- | --- | --- |
| Trần Dực → Lâm Uyên/Tô Thanh Ly | Cho nghe và sửa đúng phần họ đã thấy, không nói thay chỗ mình không nhớ | Sự đồng ý có phạm vi; bản lời không chuyển cho Hòa Sinh theo điều kiện đổi thuốc |
| Lâm Uyên → Trần Dực | Chủ động để câu hỏi của mình sau khi thấy người bệnh mệt; cuối xác nhận phần không biết được giữ đúng rồi lui | Không lấy nhu cầu tìm người làm quyền ép trả lời; chưa khỏi buồn hoặc hết việc cần hỏi |
| Tạ Nghiên Chi → Trần Dực | Hỏi qua nguồn, đọc lại, sửa sự khác nhau giữa không biết và chắc không có thuốc; dừng theo y sư | Không tự chẩn sức hoặc biến bệnh nhân thành người biết người mua |
| Cố Hoài An → Đinh Bá Nghiêm | Đối phiếu và trả khoản công còn thiếu; chỉ nhận ký phần chép/chuyển lời | Trả tiền không mua sự sửa lời, không xác nhận toàn chuyến đã xong hoặc bồi thường mọi trách nhiệm |
| Cố Hoài An → Tề Duy Cẩn | Theo giấy giao việc, nhận lại thẻ trực cửa bên, giao người khác xử lý phần phiếu/thuê chép tới khi đối xong | Quyền sắp bàn trong vụ này, không quyền chủ phường/sa thải mọi việc hoặc bắt người |
| Tạ Nghiên Chi/chấp sự → Hòa Sinh | Nhận giữ yêu cầu đối mảnh tiếp nhận đầu và người trực, giữ riêng lời bệnh nhân | Chưa được giao nguồn gốc đầy đủ hoặc người đặt cuối; không đồng minh/địch thù mới |
| Tô Thanh Ly → Lâm Uyên | Nhắc Trần Dực đã giữ được lời mình, hỏi sức tay và nhờ giúp đổi chỗ | Hỗ trợ cụ thể, không thay câu hỏi chưa giải bằng lời bảo đã biết hết |

Nguồn: [[Chương 65]], [[Trạng Thái Truyện Sau Chương 65]].

## Quan hệ theo bản thảo Chương 66

| Người | Liên hệ/chuyển biến | Giới hạn |
| --- | --- | --- |
| Cố Hoài An → Phùng Quý Lương | Sau khi về phường chiều15 cho gọi người ký tới sáng16; đối trách nhiệm phần bàn đã tiếp việc | Đây là lời bà kể được thể hiện66, không cảnh trực tiếp chiều15 hoặc xác nhận bà biết toàn việc mua từ trước |
| Tạ Nghiên Chi/chấp sự → Hòa Sinh | Đối đúng lượt theo lệnh, giữ tờ gốc/phần liên quan và để bản sao có đối cho công việc còn lại | Không lấy mọi sổ/ngừng toàn phường hoặc giao bản lời bệnh nhân |
| Tạ Nghiên Chi/Cố Hoài An → Tề Duy Cẩn | Hỏi tên người gửi đã biết; hắn nhận chiều15 không nói hết vì sợ bị nhận biết cả việc mua | Lời né tránh được ghi riêng, không thành căn cứ hắn biết nguồn hòm núi/ai nhấc sáp |
| Phùng Quý Lương → việc mua thuốc/đổi lời | Nhận cấp tiền ba lượt và chấp thuận cách chia giao để buộc có lời; tự ký thu lại yêu sách | Nhận phần mình không có nghĩa trực tiếp đứng ba quầy hoặc biết hết hành động người chạy việc |
| Lâm Uyên/Tô Thanh Ly → Phùng Quý Lương | Bác yêu cầu đổi chỗ không biết trong hòm thành xác nhận không có thuốc; yêu cầu đối đúng giấy/người | Không ép Trần Dực hỏi lại, không đọc bản riêng để tranh thắng hoặc hứa giúp Phùng Quý Lương khỏi nghĩa vụ |
| Cố Hoài An → bàn phường/Tề Duy Cẩn | Nhận trách nhiệm việc đã tiếp công/chỉ dẫn, giao người thay bàn dừng phần đòi lời còn dở; giữ bản cũ | Không lấy việc Tề Duy Cẩn tự thêm làm phường hết trách nhiệm, không kết tội chung cả phường |
| Lâm Uyên → Hứa Tĩnh Xuyên | Nhờ người trực báo còn câu hỏi về mùi thuốc khi giám dược rảnh | Chưa có buổi học mới hoặc triệu người bỏ việc; không quan hệ truyền thừa mới |

Chỗ mẹ con Khương Tố Nương được báo đã giữ cho ngày16 theo điều kiện cũ; người mẹ vẫn là bệnh nhân. Chủ giỏ vẫn giữ hẹn dao chiều16, chưa có hành động trả tại Bùi Gia.

Nguồn: [[Chương 66]], [[Trạng Thái Truyện Sau Chương 66]].

## Quan hệ theo bản thảo Chương 67

| Người | Liên hệ/chuyển biến | Giới hạn |
| --- | --- | --- |
| Đào Thành Nghiệp → Bùi Ninh Viễn | Đến đúng bàn hẹn, tự giao dao riêng để người cho mượn xem/nhận; Bùi Ninh Viễn nhờ bàn chốt phần nhận đã được báo | Dao đã về túi Bùi Ninh Viễn, không còn khoản mượn chờ trả; không thanh toán trách nhiệm nhà trú hoặc đồng nghĩa tha lỗi |
| Bùi Ninh Viễn → Đào Thành Nghiệp | Hỏi nơi thay cạnh khung, giới thiệu đúng người dẫn đội, chỉ giữ đầu giỏ khi được nhờ/đúng chỗ | Hỗ trợ theo nghề/phạm vi, không tự biết sửa mọi khung hoặc giỏi đan giỏ; chưa bảo đảm việc thuê tiếp |
| Người dẫn đội → Đào Thành Nghiệp | Thuê sửa quai giỏ dụng cụ của chính mình, nhận giá hai đồng/có mây, thử món hoàn thành rồi trả đủ | Giao dịch riêng, không bồi thường của Bùi Gia/ứng công toàn nghề hoặc ký hợp đồng lâu dài |
| Bùi Khánh Vân → thợ phụ/người nhà | Báo đã gặp đúng người tại trạm khác hôm15, người nhà nhận tin theo địa chỉ bảng công; không gọi trở lại chỉ vì tìm được | Tin qua lời bà, chân người thợ còn cần xem; không xác nhận khỏi thương/ra trạm/đã làm lại hoặc họ hàng mới |
| Hứa Tĩnh Xuyên → Lâm Uyên | Đáp câu nhờ66 bằng mẫu quế/thẻ tên, chỉ cách đối đúng phần được người có nghề giao | Buổi học mẫu ngắn, không nhận thầy trò thay Mạnh Thanh Tễ/truyền thừa hoặc quyền tự kê |
| Đào Thành Nghiệp → Lâm Uyên/Tô Thanh Ly | Trở lại viện báo trả dao, sửa quai/nhận công, nói rõ khung còn phải thay/giỏ mới chưa nhận | Nhóm viện chỉ nghe phần được kể; không dùng tin để hứa viện trả khung hoặc có khách ngày mai |
| Đào Thành Nghiệp ↔ Hồ Nhuận Chi | Hỏi đúng phần khung/kim còn thiếu, giữ phần đồ có thể dùng | Chia sẻ việc trước mắt, không người thân/thân hữu lâu năm mới được suy ra hoặc mất mát đã giải |
| Tô Thanh Ly → Đào Thành Nghiệp/người giữ đồ | Chỉ đúng nơi hỏi việc, nhờ giữ chỉ đường; người giữ đồ nhận sáng17 rảnh sẽ cho xem phần cần sửa | Chưa giao việc/định giá hoặc thay viện chấp nhận mọi khoản công |

Lâm Uyên ở viện cả chiều, nhận người khác có thể tự đi trả món mượn; không cần được kể toàn bộ cuộc trao đổi ở bàn Bùi Gia để có quan hệ hay tri thức mới.

Nguồn: [[Chương 67]], [[Trạng Thái Truyện Sau Chương 67]], [[Chương 63]], [[Chương 66]].

## Quan hệ theo bản thảo Chương 68

| Người | Liên hệ/chuyển biến | Giới hạn |
| --- | --- | --- |
| Viện chủ Tế Sinh Viện → Mạnh Thanh Tễ/thân nhân chưa xác nhận | Viện lo an táng, giữ nơi chôn có tên, đồ riêng và tiếp đầu mối báo tin | Chưa có người nhà nhận; an táng không đồng nghĩa hết thân nhân, tuổi/quê không được điền đoán hoặc trao sổ/túi cho người học |
| Viện chủ Tế Sinh Viện → Lâm Uyên | Báo việc đưa tang, nghe mong muốn chờ/đi cùng và hướng tới đúng lượt xem sức, thu xếp | Không bắt Lâm Uyên quyết mọi việc thay người nhà, không chuyển trách nhiệm tiền tang hoặc quyền nhận di vật |
| Thủ Danh Phường/Vệ Thu Nghi ↔ Tế Sinh Viện | Đối người biết tên/nghề, nguồn liên hệ, chỗ chôn và bên giữ đồ; giao viện bản chỉ nơi chôn, phường giữ phần nguồn để người tới sau hỏi | Quan hệ công việc cụ thể, không quyền xét thân nhân bằng phép thuật hoặc đặt luật chờ cố định |
| Vệ Thu Nghi → Lâm Uyên | Đọc lại đủ tên Mạnh Thanh Tễ, để phần chưa rõ chờ nguồn; cho bản chỉ đường khi hắn xin | Hỗ trợ tìm đúng mộ, không nhận làm người nhà/sư phụ, không cho quyền tự đi ngoài thành hoặc thêm bí mật nguồn gốc |
| Tô Thanh Ly → Lâm Uyên | Giữ khoảng đứng, nhờ người giúp phần nặng, đưa khăn bằng trái và cất bản chỉ đường tới phần giấy của hắn sau khi về | Đồng hành trong mất mát, không lời buộc hắn hết buồn; tay phải nàng chưa lành, không tự mang quan tài |
| Y sư/chấp sự/người hộ tống → Lâm Uyên/Tô Thanh Ly | Xem sức, nhận riêng lượt xe đưa tang, giúp bậc/tựa/chỗ ngồi và xem lại sau chuyến | Quyền đi có mục đích/lượt này, không lấy giấy lượt16 dùng lại hoặc gỡ quản thúc/hộ tống |
| Đào Thành Nghiệp ↔ người giữ đồ | Đã xem giỏ hẹn sáng17, nói rõ đáy hỏng và từ chối nhận sửa với dụng cụ hiện có; giỏ được để riêng | Không có giao việc/giá/công mới; không biến lòng giúp thành lời bảo đảm món dùng được |
| Người xác nhận chỗ ↔ viện/mẹ con Khương Tố Nương | Báo phần giữ ngày17 đã được bên nhận xác nhận và giao phần theo dõi cho sáng sau | Mẹ chưa chuyển khỏi viện; phần sáng sau cần tiếp nhận, không tự đã xác nhận ngày18 |

Sổ nghề/túi thuốc vẫn thuộc phần viện giữ. Bản chỉ đường Lâm Uyên xin là bản riêng có trình tự Vệ Thu Nghi giao → Tô Thanh Ly cất giúp → đặt vào phần giấy của hắn, không là chuyển giao di sản.

Nguồn: [[Chương 68]], [[Trạng Thái Truyện Sau Chương 68]], [[Chương 67]].
