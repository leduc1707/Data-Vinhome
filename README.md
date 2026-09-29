# Kho tri thức Vinhomes Ocean Park 1

Tài liệu này hướng dẫn team thu thập và điền dữ liệu vận hành. Trạng thái ngày 30/09/2026: Sapphire, Pavilion, bốn khu thấp tầng và `00-do-thi/` đã điền một phần. Zenpark, Masteri Waterfront và file chung Masterise còn để trống (`trang_thai: chua-thu-thap`). Chỉ điền fact có nguồn và ngày. Không suy từ phân khu khác sang.

Mốc lọc phân khu: 28/09/2026. Chỉ giữ khu đã bàn giao.

## Phạm vi

Trong repo:

- Sapphire 1 và Sapphire 2, bàn giao khoảng 2020. Tòa mẫu S1.01, S1.02, S2.01, S2.05.
- Zenpark, bàn giao khoảng 2021. Tòa mẫu R1.02, R1.03.
- Pavilion, mốc bàn giao tháng 1/2024. Tòa mẫu P1, P2. Đối chiếu biển tòa trước khi chốt mã.
- Masteri Waterfront, bàn giao từ quý 2/2023. Tòa mẫu M1 (cụm Miami), H1 (cụm Hawaii).
- Thấp tầng: Ngọc Trai, San Hô, Sao Biển, Hải Âu, bàn giao khoảng 2020.

Chưa đưa vào vì chưa xác nhận bàn giao: Zurich, Beverly, London, Paris, Masteri Lakeside, Lumiere Bayfront, The Senique Hanoi. Khi bàn giao, tạo folder cùng cấu trúc. Không gộp vào Sapphire.

## Cấu trúc thư mục

```
kb-ocean-park/
├── README.md
├── AGENTS.md
├── NGUON.md                                   # khu đã bỏ vì chưa bàn giao
├── 00-do-thi/
│   ├── tien-ich-ho-bien-vincom.md
│   └── noi-quy-giao-thong.md                  # còn chờ văn bản ban quản lý
├── 01-vinhomes/
│   ├── sapphire/
│   │   ├── quy-dinh-chung-dong-sapphire.md    # tổng quan dòng Sapphire
│   │   ├── quy-dinh.md
│   │   ├── cau-hoi-thuong-gap.md
│   │   ├── quy-trinh-van-hanh.md
│   │   ├── huong-dan-dich-vu.md
│   │   ├── huong-dan-xu-ly-tinh-huong.md
│   │   ├── huong-dan-an-toan.md
│   │   ├── sapphire-1/
│   │   │   ├── S1.01/                         # 5 file tòa
│   │   │   └── S1.02/                         # 5 file tòa
│   │   └── sapphire-2/
│   │       ├── quy-dinh-chung-phan-khu.md     # ghi chú riêng Sapphire 2
│   │       ├── S2.01/                         # 5 file tòa
│   │       └── S2.05/                         # 5 file tòa
│   ├── zenpark/                               # quy-dinh-chung-phan-khu.md + 6 file, rồi R1.02/, R1.03/ (3 file tòa)
│   └── pavilion/                              # quy-dinh-chung-phan-khu.md + 6 file, rồi P1/, P2/ (5 file tòa)
├── 02-masterise/
│   ├── quy-trinh-chung-masterise-property-management.md
│   └── masteri-waterfront/                    # quy-dinh-chung-phan-khu.md + 6 file, rồi M1/, H1/ (3 file tòa)
└── 04-thap-tang/
    ├── ngoc-trai/                             # quy-dinh-chung-phan-khu.md + 6 file
    │   ├── biet-thu-dai-dien/quy-dinh-cu-dan.md
    │   └── shophouse-dai-dien/quy-dinh-kinh-doanh.md
    ├── san-ho/                                # như ngoc-trai
    ├── sao-bien/                              # như ngoc-trai
    └── hai-au/                                # như ngoc-trai
```

"6 file" là sáu file nghiệp vụ ở mục dưới. "3 file tòa" là ba file bắt buộc, "5 file tòa" là ba file đó cộng hai file bổ sung — xem mục Folder tòa. Số `03-` đang bỏ trống. Không đánh lại số các folder hiện có.

## Đơn vị vận hành

Vinhomes vận hành Sapphire, Zenpark, Pavilion và bốn khu thấp tầng. Masterise Property Management vận hành Masteri Waterfront. Hai bộ tài liệu không dùng chung. Phí, ứng dụng, số trực và quy trình xử lý phải lấy đúng đơn vị.

`00-do-thi/` chỉ chứa thông tin chung cả đô thị: tiện ích (hồ Ngọc Trai, biển hồ nước mặn, Vincom, VinUni) và nội quy giao thông nội khu. Không ghi nội quy tòa vào đây.

## Mỗi phân khu có một file tổng quan và sáu file nghiệp vụ

Các file này dùng cho toàn phân khu. Không chép lại vào từng tòa.

File tổng quan:

| File | Nội dung cần thu |
|---|---|
| `quy-dinh-chung-phan-khu.md` | Số tòa, mã tòa, tòa đại diện, đặc điểm riêng của phân khu |

Sapphire dùng `quy-dinh-chung-dong-sapphire.md` thay cho file này, ghi chung cho cả dòng Sapphire. Sapphire 2 có thêm `sapphire-2/quy-dinh-chung-phan-khu.md` cho thông tin riêng (số tòa, mã tòa, tòa mẫu).

Sáu file nghiệp vụ:

| File | Nội dung cần thu |
|---|---|
| `quy-dinh.md` | Nội quy: giờ ồn, thú nuôi, cải tạo, hành lang, ban công |
| `cau-hoi-thuong-gap.md` | Phí dịch vụ, thẻ, gửi xe, ứng dụng cư dân |
| `quy-trinh-van-hanh.md` | Cách ban quản lý tiếp nhận sự cố, mức ưu tiên, đầu mối |
| `huong-dan-dich-vu.md` | Lễ tân, hồ bơi, gym, dịch vụ có phí, giờ mở cửa |
| `huong-dan-xu-ly-tinh-huong.md` | Thang kẹt, rò nước, mất điện, quên chìa, gây rối |
| `huong-dan-an-toan.md` | Quy tắc an toàn chung của phân khu |

## Folder tòa

Mỗi phân khu chỉ để một hoặc hai tòa mẫu. Tòa còn lại dùng sáu file chung. Chỉ thêm folder tòa khi sơ đồ thoát nạn hoặc số trực khác.

Folder tòa không chứa nội quy. Ba file bắt buộc:

| File | Nội dung cần thu |
|---|---|
| `phong-chay-chua-chay-va-thoat-hiem.md` | Sơ đồ thoát nạn, tầng lánh nạn, điểm tập kết của tòa đó |
| `so-dien-thoai-truc-toa.md` | Cách gọi an ninh, đầu mối và mã tòa trên ứng dụng |
| `so-do-ham-gui-xe.md` | Hầm, lối xe, chỗ sạc của tòa đó |

Hai file bổ sung. Tòa Sapphire và Pavilion đã có; Zenpark và Masteri Waterfront chưa có:

| File | Nội dung cần thu |
|---|---|
| `thong-tin-toa.md` | Thông số tòa: số tầng, số căn, layout, thang, loại căn, tiếp giáp, ngày bàn giao |
| `danh-sach-tai-lieu-can-thu-thap.md` | Tài liệu team còn phải chụp hoặc tải tại tòa, và file đích để đưa vào |

S2.05 trước đây được ghi là căn hộ dịch vụ. Dữ liệu ngày 30/09/2026 cho thấy tại Ocean Park đây là căn hộ ở thông thường (xem `S2.05/thong-tin-toa.md`). Chỉ thêm quy định lưu trú ngắn ngày khi ban quản lý có văn bản riêng, và để trong folder S2.05.

## Thấp tầng

Không có tòa chung cư. Mỗi khu có file tổng quan và sáu file chung, thêm hai slot:

- `biet-thu-dai-dien/quy-dinh-cu-dan.md` cho căn ở
- `shophouse-dai-dien/quy-dinh-kinh-doanh.md` cho biển hiệu, nhận hàng, phòng cháy mặt tiền

Ngọc Trai là khu đóng trên đảo hồ, có kiểm soát cổng. San Hô mở, sát VinUni. Sao Biển nhiều shophouse, sát biển mặn và Vincom. Hải Âu cho phép kinh doanh trên toàn bộ liền kề.

## Cách điền

Giữ phần đầu file. Một fact một dòng, kèm tên văn bản, đường dẫn và ngày. Để trống nếu chưa có văn bản ban quản lý hoặc bảng niêm yết. Không điền số phí lấy từ bài rao.
