# Bida 3 Bi 3D – bản PWA (chơi offline, miễn phí)

## Trong thư mục
- `index.html` – toàn bộ game (một file)
- `manifest.webmanifest` – tên app, biểu tượng, toàn màn hình, xoay ngang
- `sw.js` – lưu game vào máy để chơi không cần mạng
- `icons/` – biểu tượng app

## Đưa lên GitHub Pages (miễn phí)
1. Vào github.com → **New repository** → đặt tên, ví dụ `bida3bi` → chọn **Public** → **Create**.
2. Bấm **uploading an existing file** → kéo thả **tất cả** file và thư mục `icons` trong thư mục này → **Commit changes**.
3. Vào **Settings → Pages** → mục *Branch* chọn **main** và **/(root)** → **Save**.
4. Chờ 1–2 phút, link game sẽ là:
   `https://trom-dev-22.github.io/bida3bi/`

## Cài lên điện thoại
- **iPhone:** mở link bằng **Safari** → nút **Chia sẻ** → **Thêm vào MH chính**.
- **Android:** mở link bằng **Chrome** → menu **⋮** → **Cài đặt ứng dụng** / **Thêm vào màn hình chính**.
- Mở game 1 lần khi có mạng (để máy lưu lại). Sau đó tắt mạng vẫn chơi được.

## Cập nhật game
1. Thay `index.html` bằng bản mới.
2. Mở `sw.js`, đổi `VERSION = 'bida-v1'` thành `'bida-v2'` (mỗi lần cập nhật tăng 1 số).
3. Tải 2 file đó lên GitHub (ghi đè). Người chơi mở game khi có mạng là tự nhận bản mới (có thể phải mở lại app 1 lần).
