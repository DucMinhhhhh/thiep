# 🚀 HƯỚNG DẪN DEPLOY NHANH - ĐỂ QR CODE HOẠT ĐỘNG

## ⚠️ QUAN TRỌNG

QR Code chỉ hoạt động khi file HTML được host trên INTERNET, không thể dùng file local (file://) được!

---

## 🎯 CÁCH NHANH NHẤT - GitHub Pages (MIỄN PHÍ)

### Bước 1: Tạo tài khoản GitHub

1. Truy cập https://github.com
2. Đăng ký tài khoản miễn phí (nếu chưa có)

### Bước 2: Tạo Repository mới

1. Sau khi đăng nhập, click nút **"New"** (góc trên bên trái)
2. Điền thông tin:
   - Repository name: `thiep-20-10-linh` (hoặc tên bất kỳ)
   - Chọn **Public**
   - ✅ Tích vào **"Add a README file"**
3. Click **"Create repository"**

### Bước 3: Upload files

1. Trong repository vừa tạo, click **"Add file"** → **"Upload files"**
2. Kéo thả các file sau vào:
   - `index.html` ⭐ (FILE QUAN TRỌNG NHẤT)
   - `generate-qr.html`
3. Click **"Commit changes"**

### Bước 4: Bật GitHub Pages

1. Vào tab **"Settings"** của repository
2. Kéo xuống phần **"Pages"** (menu bên trái)
3. Tại mục **"Source"**, chọn:
   - Branch: **main**
   - Folder: **/ (root)**
4. Click **"Save"**
5. Đợi 1-2 phút, refresh lại trang

### Bước 5: Lấy URL

Sau khi deploy xong, bạn sẽ thấy thông báo:

```
Your site is live at https://USERNAME.github.io/thiep-20-10-linh/
```

**URL CHÍNH để tạo QR:**

```
https://USERNAME.github.io/thiep-20-10-linh/index.html
```

(Thay `USERNAME` bằng tên GitHub của bạn)

### Bước 6: Tạo QR Code

1. Mở file `generate-qr.html` trong trình duyệt
2. Dán URL vừa lấy được: `https://USERNAME.github.io/thiep-20-10-linh/index.html`
3. Click **"Tạo Mã QR"**
4. Click **"Tải Mã QR"** để tải về
5. **Quét thử bằng điện thoại** → Sẽ hiện thiệp chúc mừng! 🎉

---

## 🌐 CÁCH 2: Netlify Drop (SIÊU NHANH - 30 giây)

### Bước 1: Truy cập Netlify Drop

1. Mở https://app.netlify.com/drop
2. Đăng nhập hoặc đăng ký (miễn phí)

### Bước 2: Kéo thả folder

1. Chọn toàn bộ folder `QR code`
2. Kéo thả vào khung trên website
3. Đợi 10-20 giây

### Bước 3: Lấy URL

Netlify sẽ tạo URL dạng:

```
https://random-name-123456.netlify.app
```

**URL để tạo QR:**

```
https://random-name-123456.netlify.app/index.html
```

### Bước 4: Tạo QR Code

Làm tương tự như hướng dẫn GitHub Pages ở trên.

---

## 🚀 CÁCH 3: Vercel (Dành cho dev)

### Bước 1: Cài Vercel CLI

```bash
npm install -g vercel
```

### Bước 2: Deploy

```bash
cd "/Users/mac/Documents/QR code"
vercel
```

### Bước 3: Làm theo hướng dẫn

- Login vào Vercel
- Chọn các option mặc định
- Lấy URL được cung cấp

---

## 📱 TEST THỬ

Sau khi có URL, test ngay:

1. Mở URL trên điện thoại
2. Nếu thấy thiệp hiện ra → **THÀNH CÔNG!** ✅
3. Nếu không → Kiểm tra lại URL có đúng không

---

## 💡 LƯU Ý

- ✅ URL phải có `https://` ở đầu
- ✅ File `index.html` phải được upload
- ✅ Đợi 1-2 phút sau khi deploy
- ❌ Không dùng URL dạng `file:///...`
- ❌ Không dùng `localhost` hoặc `127.0.0.1`

---

## 🆘 GẶP VẤN ĐỀ?

### Lỗi: "Page not found"

→ Kiểm tra xem file `index.html` đã upload chưa

### QR quét không ra gì

→ URL chưa đúng hoặc chưa deploy thành công

### Trang web không đẹp như mong đợi

→ Thử clear cache hoặc mở bằng trình duyệt ẩn danh

---

## 🎁 KẾT QUẢ CUỐI CÙNG

Sau khi làm xong các bước trên:

1. Bạn có 1 mã QR
2. Khi quét QR bằng điện thoại → Mở trang thiệp chúc mừng 20/10
3. Animation đẹp mắt hiện ra
4. **Tặng cho Linh thôi!** 💐💕

---

**Chúc bạn thành công! 🎊**
