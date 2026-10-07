# Bài thực hành: Phối màu đơn tông trên trang web (Monochromatic Color Scheme)

## 📌 Mục tiêu
- Luyện tập sử dụng phối màu đơn tông (Monochromatic) trên trang web.
- Xác định màu chủ đạo (bậc 1) và các cấp độ màu nhạt dần theo màu chủ đạo (bậc 2, bậc 4, bậc 7, bậc 9).
- Ứng dụng màu đen (`#000000`) và trắng (`#ffffff`) để đảm bảo độ tương phản (contrast) và tính thẩm mỹ.

---

## 🎨 Bảng phối màu 1: Tông Xanh Dương (Blue Monochromatic) - Theo yêu cầu đề bài
Màu gốc dựa trên logo: `#00ADEE`

| Cấp bậc màu | Mã màu HEX | Áp dụng cho thành phần | Màu chữ tương phản |
| :--- | :--- | :--- | :--- |
| **Bậc 1 (Màu chính)** | `#00ADEE` | Header, Banner, Menu links, nút ON SALE, nhãn & nút PREVIEW, nút Submit | `#ffffff` (Trắng) |
| **Bậc 2 (Điểm nhấn)** | `#00B2EF` | Hiệu ứng hover / viền / điểm nhấn phụ | `#ffffff` (Trắng) |
| **Bậc 4 (Nền trang)** | `#00BFF2` | Nền toàn bộ trang web (`body`) | `#000000` (Đen) |
| **Bậc 7 (Nền nội dung)** | `#8DD7F7` | Nền các thẻ bài viết / danh sách nghe thử (`#main .preview li a`) | `#000000` (Đen) |
| **Bậc 9 (Nền footer)** | `#C6E9FA` | Nền chân trang (`footer`) và khối thông tin (`#info`) | `#000000` (Đen) |

File áp dụng: [`index.html`](index.html) & [`style.css`](style.css)

---

## 🔥 Bảng phối màu 2: Tông Cam Hoàng Hôn (Warm Amber / Orange) - Mở rộng (Bước 8)
Màu chính ấm áp, năng động: `#E65100`

| Cấp bậc màu | Mã màu HEX | Áp dụng cho thành phần | Màu chữ tương phản |
| :--- | :--- | :--- | :--- |
| **Bậc 1 (Màu chính)** | `#E65100` | Header, Banner, Menu links, nút ON SALE, nhãn & nút PREVIEW, nút Submit | `#ffffff` (Trắng) |
| **Bậc 2 (Điểm nhấn)** | `#F57C00` | Hiệu ứng hover / nút phụ | `#ffffff` (Trắng) |
| **Bậc 4 (Nền trang)** | `#FFB74D` | Nền toàn bộ trang web (`body`) | `#000000` (Đen) |
| **Bậc 7 (Nền nội dung)** | `#FFE0B2` | Nền các thẻ nội dung (`#main .preview li a`) | `#000000` (Đen) |
| **Bậc 9 (Nền footer)** | `#FFF3E0` | Nền chân trang (`footer`) và khối thông tin (`#info`) | `#000000` (Đen) |

File áp dụng: [`index-variant2.html`](index-variant2.html) & [`style-variant2.css`](style-variant2.css)

---

## 🚀 Hướng dẫn xem kết quả
1. Mở file `index.html` bằng trình duyệt (Chrome, Edge, Firefox) để xem giao diện phối màu Tông Xanh.
2. Mở file `index-variant2.html` để xem giao diện phối màu Tông Cam.