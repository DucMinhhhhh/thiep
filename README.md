# 💐 Thiệp Chúc Mừng 20/10 - Mã QR Có Animation

Dự án tạo mã QR code, khi quét sẽ hiển thị thiệp chúc mừng 20/10 dành cho Linh với animation cực đẹp mắt.

## ⚠️ QUAN TRỌNG

**QR Code chỉ hoạt động khi file được host trên INTERNET!**
👉 Đọc file `HUONG-DAN-DEPLOY.md` để biết cách deploy nhanh (3-5 phút)

## 📁 Cấu trúc dự án

```
QR code/
├── index.html              # Trang thiệp chúc mừng 20/10 (sau khi quét QR)
├── generate-qr.html        # Công cụ tạo mã QR
├── HUONG-DAN-DEPLOY.md    # ⭐ Hướng dẫn deploy chi tiết
├── package.json            # Thông tin dự án
├── vercel.json            # Cấu hình Vercel
├── netlify.toml           # Cấu hình Netlify
└── README.md              # File này
```

## 🚀 Cách sử dụng

### ⚡ NHANH NHẤT: Làm theo 3 bước này

1. **📖 Đọc file `HUONG-DAN-DEPLOY.md`** - Hướng dẫn chi tiết từng bước
2. **🌐 Deploy lên GitHub Pages/Netlify** - Chỉ mất 3-5 phút
3. **📱 Tạo QR và quét thử** - Xong!

---

### Bước 1: Tùy chỉnh lời chúc (Nếu muốn)

Mở file `index.html` và chỉnh sửa nội dung trong phần:

```html
<div class="message">
  Gửi đến <span class="highlight">Linh</span> yêu dấu của anh! 🌹<br /><br />
  <!-- Thay đổi nội dung ở đây -->
</div>
```

### Bước 2: Deploy trang web 🌐

**👉 XEM FILE `HUONG-DAN-DEPLOY.md` ĐỂ CÓ HƯỚNG DẪN CHI TIẾT!**

Có 3 cách deploy miễn phí (chọn 1):

#### ⭐ Option 1: GitHub Pages (Khuyến nghị - Chi tiết nhất)

→ Xem `HUONG-DAN-DEPLOY.md` phần "CÁCH NHANH NHẤT"

#### ⚡ Option 2: Netlify Drop (Nhanh nhất - 30 giây)

1. Vào https://app.netlify.com/drop
2. Kéo thả folder `QR code` vào
3. Lấy URL → Tạo QR

#### 🚀 Option 3: Vercel (Cho developer)

```bash
npm install -g vercel
cd "/Users/mac/Documents/QR code"
vercel
```

### Bước 3: Tạo mã QR

1. Mở file `generate-qr.html` trong trình duyệt
2. Dán URL của trang `index.html` đã deploy
3. Nhấn "Tạo Mã QR"
4. Tải mã QR về máy

### Bước 4: Sử dụng

- In mã QR ra giấy
- Hoặc gửi file ảnh QR cho người nhận
- Khi quét bằng điện thoại → Trang lời chúc sẽ hiện ra với animation đẹp mắt!

## 🎨 Tính năng

- 💐 Thiệp chúc mừng 20/10 dành riêng cho Linh
- ✨ Animation chữ trượt xuống mượt mà
- 💖 Hiệu ứng trái tim bay lãng mạn
- ⭐ Particles và sparkles lấp lánh
- 🎭 Hiệu ứng glass morphism sang trọng
- 📱 Responsive, hoạt động tốt trên mọi thiết bị
- 🌸 Gradient màu hồng lãng mạn

## ⚡ Chạy local (không bắt buộc)

```bash
# Cài serve (chỉ cần 1 lần)
npm install -g serve

# Chạy server
cd "QR code"
serve .

# Mở trình duyệt tại http://localhost:3000
```

## 🛠️ Tùy chỉnh nâng cao

### Thay đổi màu sắc gradient

Trong `index.html`, tìm và sửa:

```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Thay đổi font chữ

Thêm Google Font vào `<head>`:

```html
<link
  href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap"
  rel="stylesheet"
/>
```

### Thay đổi tốc độ animation

Sửa giá trị `animation-duration` trong các `@keyframes`

## 📝 Lưu ý

- File `index.html` phải được host online (không thể dùng file:// protocol)
- Mã QR có thể được tùy chỉnh màu sắc trong `generate-qr.html`
- Trang web hoạt động offline sau khi load lần đầu

## 💡 Ý tưởng mở rộng

- Thêm nhạc nền
- Thêm hiệu ứng pháo hoa
- Cho phép người dùng nhập tên
- Tạo nhiều theme khác nhau
- Thêm countdown timer
- Tích hợp gallery ảnh

## 🤝 Hỗ trợ

Nếu gặp vấn đề, hãy kiểm tra:

- URL có đúng và accessible không?
- File đã được upload đầy đủ chưa?
- Browser có hỗ trợ JavaScript không?

---

**Chúc bạn tạo được những mã QR thật đẹp và ý nghĩa! 🎊**
# thiep
