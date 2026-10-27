# 🌟 DỰ ÁN WEBSITE "BƯỚC NGOẶT" - NGÂN ĐỖ

**Website:** Hồ sơ cá nhân / Blog chuyên luận & Hệ sinh thái cộng đồng.
**Chủ sở hữu:** Ngân Đỗ (Phát triển kinh doanh & Thấu hiểu con người).
**Phiên bản:** 1.0.0

---

## 📖 Tổng Quan Dự Án
Dự án "Bước Ngoặt" là một Landing Page / Single-Page Application (SPA) được thiết kế đặc biệt nhằm mục đích:
1. Xây dựng thương hiệu cá nhân (Personal Branding) chuẩn phong cách báo chí, chuyên nghiệp và đanh thép.
2. Lan tỏa triết lý "Quản trị bằng sự thấu cảm" và hành trình "Dám khác biệt".
3. Kết nối hệ sinh thái cộng đồng (Group/Fanpage) và thu thập lưu bút, phản hồi của độc giả/đối tác trực tiếp về thiết bị di động.

## 🚀 Công Nghệ Sử Dụng
Dự án được tối ưu hóa ở mức tối đa để dễ dàng bảo trì và triển khai, gói gọn toàn bộ trong **MỘT TỆP DUY NHẤT** (`index.html`):
- **HTML5 & CSS3:** Cấu trúc chuẩn SEO, hiệu ứng cuộn mượt mà.
- **Tailwind CSS (qua CDN):** Framework CSS utility-first giúp thiết kế giao diện hiện đại, Responsive (tương thích mọi thiết bị: Mobile, Tablet, Desktop) mà không cần viết file CSS rời.
- **JavaScript (Vanilla JS):** Xử lý hiệu ứng hiển thị (Fade-up), chia sẻ mạng xã hội và tích hợp API.
- **Google Fonts:** Sử dụng font `Lora` (nội dung) và `Playfair Display` (tiêu đề).
- **FontAwesome:** Hệ thống icon giao diện.
- **Telegram Bot API:** Tích hợp form liên hệ gửi thẳng tin nhắn về Telegram cá nhân.

## ✨ Tính Năng Nổi Bật
- **Thiết kế sang trọng:** Tone màu Vàng đồng (Gold) & Đỏ đô (Crimson), mang lại cảm giác ấm áp, thanh lịch.
- **Chuyên mục "Nhật Ký Bước Ngoặt":** Trình bày văn phong báo chí khách quan, sắc sảo.
- **Hệ Sinh Thái Cộng Đồng (Grid System):** Danh mục các group/fanpage (*Khi Ta Lớn, Quản Trị Bằng Sự Thấu Cảm...*) được bố trí dạng thẻ (card) đẹp mắt, có gắn hiệu ứng Hover.
- **Tường Lưu Bút Tương Tác:** Form liên hệ thu thập Họ tên, SĐT và Lời nhắn. Tích hợp sẵn mã JS để bắn thông báo về Telegram.
- **Nút Kêu Gọi Hành Động (CTA) Cố Định:** Nút gọi điện hotline và Zalo rung lắc thu hút sự chú ý ở góc màn hình.

## 🛠 Hướng Dẫn Cài Đặt & Triển Khai
Vì toàn bộ mã nguồn nằm gọn trong tệp `index.html`, việc triển khai vô cùng đơn giản:

### 1. Xem trên máy tính cá nhân (Offline)
- Chỉ cần nhấp đúp chuột vào tệp `index.html` để mở bằng trình duyệt (Chrome, Safari, Cốc Cốc...) là có thể xem và trải nghiệm ngay.

### 2. Triển khai lên mạng (Hosting / Domain)
- Dự án này là file tĩnh (Static site), có thể host miễn phí trên các nền tảng như:
  - **GitHub Pages**
  - **Vercel**
  - **Netlify**
- Nếu có Hosting/VPS và Tên miền riêng (ví dụ: `ngando.com`), chỉ cần upload file `index.html` lên thư mục `public_html` của server.

### 3. Cấu hình Telegram Bot (Nhận Form Lưu Bút)
Để form liên hệ hoạt động thực tế:
1. Mở file `index.html`, tìm đến phần `<script>` ở cuối file.
2. Tìm biến `BOT_TOKEN` và thay bằng Token từ BotFather trên Telegram.
3. Tìm biến `CHAT_ID` và thay bằng ID tài khoản Telegram của bạn (Lấy qua `@userinfobot`).

## 📞 Liên Hệ & Hỗ Trợ
- **Tác giả nội dung:** Ngân Đỗ
- **Điện thoại / Zalo:** [0902.652.225](https://zalo.me/0902652225)
- **Bản quyền:** © 2026. Mọi quyền được bảo lưu. Dám khác biệt để kiến tạo những giá trị trường tồn.