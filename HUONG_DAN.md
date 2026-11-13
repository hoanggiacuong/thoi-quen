# Lịch thói quen — hướng dẫn

## Đưa lên GitHub Pages
1. Vào github.com → **New repository** → đặt tên (vd `thoi-quen`) → **Public** → Create.
2. Trong repo vừa tạo: **Add file → Upload files** → kéo 6 file vào:
   `index.html`, `manifest.json`, `sw.js`, `icon-180.png`, `icon-192.png`, `icon-512.png`
   → **Commit changes**.
3. **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
4. Đợi 1–2 phút, link sẽ là `https://<tên-github>.github.io/thoi-quen/`

## Cài lên iPhone
1. Mở link bằng **Safari** (không phải Chrome).
2. Bấm nút **Chia sẻ** (ô vuông mũi tên lên) → **Thêm vào MH chính** → Thêm.
3. Mở app từ icon trên màn hình chính — mỗi ngày mở là ô hôm nay tự sáng.

## Lưu ý
- Dữ liệu lưu ngay trên máy (trong app). Xoá app khỏi màn hình chính là mất dữ liệu.
- Nếu iPhone không mở app hơn ~7 ngày, iOS có thể xoá dữ liệu của web app. Mở đều mỗi ngày thì không sao.
- Thêm/bớt thói quen, đổi màu: sửa mảng `HABITS` đầu thẻ `<script>` trong `index.html`.
- Sau khi sửa file, đổi `habit-v1` → `habit-v2` trong `sw.js` để iPhone nhận bản mới.
