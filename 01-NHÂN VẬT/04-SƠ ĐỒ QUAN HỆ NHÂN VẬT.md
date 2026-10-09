---
type: nhan-vat
status: hoan-thien
tags:
  - nhan-vat
  - relationship-map
---

# Sơ Đồ Quan Hệ Nhân Vật

> Bảng nền có căn cứ đến Chương 52; cập nhật Chương 54–58 ở cuối. Đường liền là quan hệ được xác nhận; nét chấm là quan hệ xã hội/đang hình thành. Không suy chức quyền hay huyết thống từ cùng họ.

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
