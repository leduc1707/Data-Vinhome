---
trang_thai: can-xac-minh
cap_nhat: 2026-09-29
---

# Rà soát dữ liệu Masterise

> Cập nhật xử lý 30/09/2026: đã mở rộng hồ sơ đủ sáu tòa theo yêu cầu mới, thay tám file M1/H1 bằng dữ liệu có nguồn và danh mục chờ thu thập. Xem [danh mục hiện hành](masteri-waterfront/DANH-MUC-TOA.md). Bản cũ M1/H1 được lưu trong [ZIP đối chiếu](luu-tru/M1-H1-truoc-ra-soat-2026-09-30.zip). Các nhận xét dưới đây mô tả phiên bản ngày 29/09/2026; giới hạn hai tòa mẫu và số lượng 16 file không còn là phạm vi hiện hành. Các vấn đề trong file nghiệp vụ chung chưa được xác minh toàn bộ.

Đã đọc 16 file dữ liệu trong `02-masterise`, đối chiếu `AGENTS.md` và `README.md`. Đây là báo cáo kiểm tra, không phải nội quy hay hướng dẫn vận hành đã được BQL xác nhận. Chưa sửa nội dung 16 file gốc đang có thay đổi chưa commit.

## Kết luận

Dữ liệu chưa đủ điều kiện dùng làm câu trả lời vận hành đã xác thực. Cả 16 file đều không có URL đầy đủ để truy ngược nguồn. Việc ghi tên website, tên hồ sơ hoặc “tháng 09/2026” không chứng minh nội dung đã được kiểm tra hay đang có hiệu lực. Không có căn cứ để kết luận tất cả dữ liệu sai; cần phân biệt mâu thuẫn nội bộ, thông tin chưa chứng minh và thông tin còn thiếu.

README yêu cầu fact có tên văn bản, đường dẫn và ngày; để trống khi thiếu văn bản BQL/bảng niêm yết, không dùng phí từ bài rao. Kho hiện chưa đáp ứng yêu cầu này.

## Các điểm cần xử lý

| Ưu tiên | File / nội dung | Phát hiện | Cách xử lý |
|---|---|---|---|
| 1 | `masteri-waterfront/quy-trinh-van-hanh.md`, `huong-dan-xu-ly-tinh-huong.md` | P1–P4 được gọi là quy ước của kho nhưng lại đưa ra mốc 3–5 phút, 15 phút, 1–2 giờ, 24–48 giờ như cam kết vận hành. File tình huống còn khẳng định kỹ thuật sẽ đến cứu hộ trong 3–5 phút. | Không dùng làm SLA của MPM. Cần quy trình hoặc xác nhận BQL có ngày hiệu lực. |
| 1 | Hai file `miami/M1/so-dien-thoai-truc-toa.md`, `hawaii/H1/so-dien-thoai-truc-toa.md` và các file chung | Hai số 0818 910 909 / 0888 366 159 được lặp lại nhưng không có bản thông báo gốc, số máy lẻ hoặc ngày xác nhận còn hoạt động. | Xin bảng số trực từng tòa, phân biệt BQL, lễ tân, an ninh và điều phối buggy. Chưa kết luận hai số sai. |
| 1 | Hai file PCCC M1/H1 | Thừa nhận chưa có sơ đồ nhưng khẳng định số thang, tăng áp, đường tiếp cận và tuyến thoát xuống tầng 1. | Cần sơ đồ niêm yết đúng tòa/tầng và phương án được xác nhận; mô tả bán hàng không thay được sơ đồ thoát nạn. |
| 1 | `huong-dan-an-toan.md` | Ghi “do Masterise Property Management ban hành”, dẫn “Hồ sơ thiết kế và nghiệm thu PCCC” nhưng không có mã hồ sơ, bản gốc, trang trích hoặc đường dẫn. | Bỏ việc quy thuộc văn bản cho MPM nếu chưa có chứng cứ. Xác minh riêng thông số cửa chịu lửa, lan can, thiết bị và điểm tập kết. |
| 1 | `huong-dan-xu-ly-tinh-huong.md` | Có khẳng định tuyệt đối “không lo ngạt thở”; mô tả quay thang bằng tay; hướng dẫn thoát nạn không phân biệt tình trạng lối thoát. | Cần chuyên môn và tài liệu gốc để duyệt trước khi dùng; không xem là quy trình cứu hộ của dự án. Báo cáo này không cung cấp hướng dẫn cứu hộ thay thế. |
| 2 | `miami/M1/THONG-TIN-TOA.md` và `miami/M1/phong-chay-chua-chay-va-thoat-hiem.md` | Một file đặt đường Hải Đăng phía Tây Nam, file kia đặt phía Tây Bắc. | Mâu thuẫn nội bộ xác định được; chưa đủ bằng chứng chọn hướng đúng. Cần mặt bằng có hướng Bắc. |
| 2 | `cau-hoi-thuong-gap.md`, hai file hầm | Phí dịch vụ, phí xe, ưu đãi 36 tháng thiếu biểu phí/HĐMB cụ thể. Tổng sau VAT đang ngầm dùng 10%, không ghi kỳ áp dụng. | Xin biểu phí có hiệu lực, cơ sở diện tích, tình trạng VAT, điều kiện ưu đãi và đối tượng áp dụng; không tự cập nhật mức thuế hay giá. |
| 2 | `quy-dinh.md` | Giờ thi công và giờ yên tĩnh ghi “thông dụng”; quy định thú cưng, pin xe điện, camera, chuyển đồ không dẫn điều khoản. | Không biến thông lệ thành nội quy Masteri Waterfront; cần văn bản BQL tương ứng. |
| 2 | Các file dịch vụ, FAQ và quy trình | Lễ tân 24/7, văn phòng 8h30–17h30 T2–T7, app và các chức năng, xác thực CCCD, Face ID chưa có tài liệu hướng dẫn cụ thể. | Tách từng fact, ghi tài liệu chứng minh và ngày xác nhận; an ninh 24/7 không tự chứng minh lễ tân 24/7. |
| 2 | `huong-dan-dich-vu.md`, FAQ | FAQ nói không phục vụ khách vãng lai; file dịch vụ nói khách đi cùng cư dân được đăng ký. | Chưa phải mâu thuẫn chắc chắn vì hai nhóm khách có thể khác nhau. Cần quy định khách, điều kiện và phí cụ thể. |
| 2 | Các file thông số tòa / tổng quan | M1 ghi 517–541 căn; tầng bể bơi, số thang, diện tích, mã căn H1 và vị trí gym thiếu bản vẽ gốc. | Giữ trạng thái chưa xác minh; không chọn số bằng suy đoán hoặc số đông website. |
| 2 | `quy-trinh-chung-masterise-property-management.md` | Gộp “Lumiere Bayfront / Orient Pearl”, khẳng định các dự án chưa bàn giao. | Cần xác minh định danh từng dự án và mốc bàn giao riêng; không coi dấu gạch chéo là chứng cứ hai tên đồng nghĩa. |

## Thiếu gì so với nhiệm vụ thu thập

| Nhóm | Tài liệu / trường cần bổ sung |
|---|---|
| Liên hệ từng tòa | Số lễ tân, an ninh, kỹ thuật, máy lẻ; giờ trực; mã tòa thực tế trên app; ảnh bảng niêm yết và ngày chụp. |
| PCCC từng tòa | Sơ đồ từng loại tầng, lối thoát, tầng lánh nạn nếu có, điểm tập kết chính thức; phiên bản/ngày của sơ đồ. |
| Hầm từng tòa | Bản đồ, cửa vào/ra, chiều lưu thông, vị trí đỗ/sạc và quy định sạc thực tế. Hai file mang tên sơ đồ hiện chưa chứa sơ đồ. |
| Nội quy | Văn bản ban hành; điều khoản tiếng ồn, thú cưng, thi công, chuyển nhà; thủ tục, biểu mẫu và khoản ký quỹ nếu áp dụng. |
| Dịch vụ | Giờ mở cửa/bảo trì hồ bơi, gym; đặt chỗ; khách đi cùng; phí; lịch buggy và điểm đón hiện hành. |
| Phí / thẻ | Biểu phí có hiệu lực, phí cấp lại thẻ, điều kiện đăng ký, thời gian xử lý, kênh thanh toán được xác nhận. |
| Vận hành | Kênh tiếp nhận, giờ phục vụ, người/bộ phận phụ trách, cách chuyển cấp và SLA chỉ khi có tài liệu. |
| Nguồn | URL cụ thể hoặc file chứng cứ, tên đơn vị ban hành, ngày ban hành/hiệu lực, trang/điều khoản, ngày kiểm tra. |

Không tính M2/M3/H2/H3 là folder bị thiếu: README chủ đích chọn M1/H1 làm hai tòa mẫu. Không tự thêm Lumiere Bayfront hay Masteri Lakeside chỉ để đủ danh sách; cần kiểm tra điều kiện phạm vi theo README trước.

## Đối chiếu nguồn công khai có giới hạn

- Kết quả tìm kiếm dẫn đến [bản tin trên tên miền Masterise Homes](https://masterisehomes.com/storage/media/HWGRqfa2ENXffPs2SeGdveKqR4ONccXJjk98d7rd.pdf), có nội dung cư dân Miami nhận dịch vụ MPM và ra mắt Hawaii tháng 8/2023. Đây là đầu mối để kiểm tra tiếp, không xác nhận hotline, phí hoặc SLA hiện tại. Chưa kiểm tra toàn bộ PDF.
- Tìm kiếm hai số hotline kèm tên dự án chưa cung cấp được thông báo BQL gốc trong lượt rà soát này. Không tìm thấy không có nghĩa số đó sai.
- Chưa xác minh được toàn bộ thông số kiến trúc, tình trạng bàn giao các dự án khác và chính sách hiện hành. Ngày rà soát không thay thế ngày hiệu lực tài liệu.

## Thứ tự hoàn thiện

1. Thu chứng cứ số trực, sơ đồ PCCC và hầm cho M1/H1; ưu tiên nội dung ảnh hưởng trực tiếp đến việc liên hệ và tìm đường.
2. Lấy nội quy, biểu phí và hướng dẫn cư dân hiện hành từ BQL/MPM, kèm phụ lục và ngày hiệu lực.
3. Sửa từng fact dựa trên chứng cứ; chuyển phần chưa xác minh sang danh sách cần thu thập, loại các SLA tự quy ước khỏi dữ liệu thực tế.
4. Giữ fact chung tại file phân khu và dẫn chiếu từ file tòa, tránh lặp hotline/phí/giờ buggy ở nhiều nơi.
5. Kiểm tra lại mâu thuẫn và khả năng truy nguồn trước khi chuyển trạng thái dữ liệu.
