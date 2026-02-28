# Website CLB Cầu Lông THPT Hùng Vương 🏸

Đây là mã nguồn HTML/CSS tĩnh cho trang web giới thiệu Câu lạc bộ Cầu lông trường THPT Hùng Vương. Trang web được thiết kế hiện đại, bao gồm các tính năng hiển thị trực quan và hoàn toàn đáp ứng (responsive) trên các thiết bị di động.

## 🌟 Các Tính Năng Nổi Bật

- **Giao diện Modern UI:** Thiết kế Glassmorphism với màu sắc tươi sáng, chuyển động mượt mà (Scroll Reveal animations).
- **Responsive Design:** Tương thích hoàn hảo với màn hình điện thoại, máy tính bảng và máy tính để bàn.
- **Đồng hồ Sự kiện (Đếm ngược):** Tính năng đếm ngược đến các giải đấu hoặc sự kiện sắp tới.
- **Trang Liên Kết Tổng Hợp:** File `links.html` hoạt động như một "Linktree" giúp gom nhóm mọi tài nguyên mạng xã hội, hội nhóm của CLB vào một chỗ.
- **Form Đăng Ký (Modal):** Biểu mẫu đăng ký thành viên dạng Popup không cần tải lại trang.

## 📁 Cấu Trúc File

Dự án bao gồm 2 file chính:

1. `index.html`: Giao diện chính giới thiệu, quảng bá thông tin, hình ảnh và sự kiện của câu lạc bộ.
2. `links.html`: Trang tổng hợp các liên kết mạng xã hội (Facebook, TikTok, Zalo, Web chính).

## 🚀 Hướng Dẫn Sử Dụng và Triển Khai Lên Web (Sử Dụng GitHub Pages)

Nếu trình duyệt của bạn đang mở trang GitHub này, tức là bạn đã đưa code lên mạng thành công! Để trang web của bạn có thể truy cập bằng một đường dẫn (link) công khai, bạn thực hiện các bước sau:

**Kích Hoạt GitHub Pages:**

1. Trên thanh công cụ của Repository này, nhấp vào thẻ **Settings** (biểu tượng bánh răng).
2. Kéo xuống phần menu bên trái, tìm và nhấp vào mục **Pages**.
3. Tại phần `Build and deployment`, mục **Source**, chọn chức năng là **Deploy from a branch**.
4. Chỗ mục **Branch**, nhấp vào nút chữ `None`, chọn nhánh **`main`** (hoặc `master`), các thiết lập bên cạnh giữ nguyên chữ `/ (root)` và sau đó bấm **Save**.
5. Đợi khoảng 1-2 phút cho đến khi GitHub xử lý xong dữ liệu. Một đường link trang web sẽ hiển thị màu xanh lá ở trên cùng.

**Ví dụ, đường link của bạn sẽ trông giống thế này:**
- Trang chủ: `https://[tên-tài-khoản-github].github.io/[tên-kho-lưu-trữ]/`
- Trang liên kết: `https://[tên-tài-khoản-github].github.io/[tên-kho-lưu-trữ]/links.html`

## 🎨 Tùy Chỉnh

Mã nguồn được viết rất dễ để bạn có thể tự chỉnh sửa.
* Để thay đổi thời gian đếm ngược, mở thẻ `<script>` ở cuối file `index.html` và tìm biến `targetDate`, đổi ngày tháng bạn cần.
* Để đổi ảnh, thay đổi nội dung các nguồn URL (`src=...`) trong mục `activities` bằng đường link ảnh của bạn.

---
© Đã được xuất bản cho dự án CLB Cầu Lông THPT Hùng Vương.
