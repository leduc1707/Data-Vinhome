# Data-Vinhome — dữ liệu chăm sóc cư dân Ocean Park 1

> Cập nhật dữ liệu: 2026-10-01. Bản này được làm giàu theo hướng **chăm sóc cư dân / vận hành / tiện ích / xử lý tình huống**, không phải bộ dữ liệu tư vấn giao dịch bất động sản.

## Mục tiêu

Kho dữ liệu này dành cho agent hỗ trợ người **đang sống, làm việc hoặc sử dụng dịch vụ** tại Vinhomes Ocean Park 1 và Masteri Waterfront. Nội dung ưu tiên câu trả lời thực dụng: cư dân cần làm gì, chuẩn bị gì, liên hệ kênh nào, trường hợp nào cần Ban quản lý xác nhận, và cách xử lý tình huống an toàn.

## Cấu trúc

| Thư mục | Phạm vi |
|---|---|
| `00-do-thi/` | Quy định và dịch vụ dùng chung toàn đô thị: ra/vào, khách, tiện ích, gửi xe, cảnh quan, hồ, BBQ, giao nhận, VinBus, sự cố chung |
| `01-vinhomes/` | Dữ liệu đặc thù Vinhomes Ocean Park 1: đại tiện ích, hồ, bể bơi, sân thể thao, trường học, y tế, an ninh, nhà xe, sửa chữa căn hộ |
| `02-masterise/` | Masteri Waterfront: dịch vụ tiền sảnh, thẻ, tạm trú, tiện ích cư dân, kỹ thuật M&E, vệ sinh, an ninh, phản ánh và vận hành |
| `04-thap-tang/` | Kiến thức theo ngữ cảnh tòa/tầng: thang máy, hành lang, riser kỹ thuật, rò nước, mất điện cục bộ, tiếng ồn, mùi, sửa chữa, giao nhận |

Mỗi nhóm chính có các file:

- `du-lieu-tong-quan.md`: dữ kiện nền và phạm vi áp dụng.
- `quy-dinh.md`: quy tắc sử dụng và các điểm cần Ban quản lý xác nhận.
- `cau-hoi-thuong-gap.md`: FAQ cho agent trả lời nhanh.
- `quy-trinh-van-hanh.md`: luồng tiếp nhận, phân loại, xử lý và đóng ticket.
- `huong-dan-dich-vu.md`: cách dùng dịch vụ/tiện ích.
- `huong-dan-xu-ly-tinh-huong.md`: playbook theo tình huống.
- `huong-dan-an-toan.md`: nguyên tắc an toàn và tình huống khẩn cấp.

## Nguyên tắc dữ liệu

1. **Nguồn chính thức ưu tiên cao nhất.** Khi có thông tin từ Vinhomes, Masterise Homes/Masteri Waterfront hoặc tài liệu quản lý vận hành, dùng nguồn đó trước.
2. **Thông tin động không đóng đinh.** Giờ mở cửa, biểu phí dịch vụ, điều kiện đặt chỗ, lịch xe, quy trình đăng ký và số hotline nội bộ có thể đổi; agent phải hướng cư dân kiểm tra app/thông báo/Ban quản lý tại thời điểm hỏi.
3. **Tài liệu Q&A cũ chỉ làm nền.** Bộ Q&A Vinhomes Ocean Park năm 2022 được dùng để bổ sung các câu hỏi cư dân hay gặp, nhưng các chi tiết cũ được đối chiếu và viết lại theo ngữ cảnh vận hành.
4. **Suy luận có kiểm soát.** Các bước vận hành không có văn bản công khai đầy đủ được suy luận từ dịch vụ được công bố và quy trình quản lý chung cư thông thường. Những chỗ đó được ghi rõ `Suy luận vận hành`, không trình bày như cam kết chính thức.
5. **Không chứa dữ liệu phục vụ bán hàng/đầu tư.** Đã loại các nội dung về chính sách bán, vay mua nhà, ưu đãi giao dịch, chiết khấu, hiệu suất đầu tư và các chỉ số kinh doanh bất động sản.

## Cách agent trả lời

- Xác định **khu/tòa/tầng/căn** nếu thông tin này làm thay đổi hướng dẫn.
- Phân biệt **cư dân**, **khách của cư dân**, **nhà thầu/đơn vị giao hàng** vì quyền ra/vào và dùng tiện ích khác nhau.
- Với phí, lịch, quota, giờ mở cửa: trả lời nguyên tắc trước, sau đó nói rõ cần kiểm tra kênh hiện hành.
- Với sự cố kỹ thuật: ưu tiên **an toàn → cô lập nguồn nguy hiểm nếu có thể làm an toàn → báo BQL/kỹ thuật → ghi nhận ảnh/video nếu không gây rủi ro**.
- Không hướng dẫn cư dân tự can thiệp tủ điện, hệ thống PCCC, thang máy, trục kỹ thuật hoặc thiết bị dùng chung.

Xem chi tiết nguồn và mức độ tin cậy tại [`NGUON.md`](NGUON.md).

## Thư mục chi tiết giữ từ bản trước

Ngoài các file cấp nhóm ở trên, repo còn giữ dữ liệu chi tiết theo phân khu, tòa và tiểu khu. Các file này đã được viết lại theo cùng cách trình bày: tiêu đề từng mục và gạch đầu dòng, không còn khối hỏi đáp ở cuối file.

| Vị trí | Nội dung |
|---|---|
| `00-do-thi/` (12 file chuyên đề) | Danh bạ, giao thông, trông giữ xe, sạc xe điện, cấp thẻ, để đồ sảnh, thanh toán phí, biển mặn và hồ Ngọc Trai, tiện ích, xe buýt |
| `01-vinhomes/sapphire/`, `zenpark/`, `pavilion/` | Sáu file nghiệp vụ của từng phân khu |
| Thư mục tòa trong từng phân khu (S1.01, S1.02, S2.01, S2.05, R1.02, R1.03, P1, P2) | Năm file của từng tòa (thoát hiểm, số trực, chỗ đỗ xe, đầu mối, tài liệu) và ảnh mặt bằng tòa |
| `04-thap-tang/ngoc-trai/`, `san-ho/`, `sao-bien/`, `hai-au/` | Bốn tiểu khu thấp tầng: sáu file nghiệp vụ, quy định biệt thự và quy định kinh doanh |
| `02-masterise/` | Giữ nguyên cấu trúc và nội dung của bản trước (sáu tòa Miami và Hawaii, danh mục tòa, báo cáo rà soát), chưa chuyển sang bộ 7 file như ba nhóm còn lại |

Lưu ý: trong `04-thap-tang/`, các file cấp nhóm nói về ngữ cảnh tòa/tầng của chung cư, còn bốn thư mục con là bốn tiểu khu thấp tầng. Hai phần này khác phạm vi.

Các file chi tiết có ghi phí, giờ và số điện thoại tại thời điểm cập nhật. Theo nguyên tắc 2 ở trên, khi số trong file khác với thông báo mới của ban quản lý thì dùng thông báo mới.
