# Link-in-bio (Linktree clone)

Trang link tổng hợp, host miễn phí trên GitHub Pages tại:
**https://kienbuidevops.github.io**

## Sửa nội dung
Mở `index.html`, tìm các chỗ ghi `CHANGE_ME` và thay bằng link thật:
- YouTube, Spotify, TikTok, SoundCloud, Buy Music
- Tên + bio: sửa trong `<h1>` và `<p class="bio">`
- Tiêu đề tab / preview share: phần `<title>` và các thẻ `og:` trong `<head>`

## Đổi ảnh đại diện
Bỏ 1 ảnh tên đúng `avatar.jpg` vào thư mục này (vuông, ~400×400 là đẹp).
Chưa có file thì trang tự hiện vòng tròn chữ "KB".

## Đăng lại sau khi sửa
```bash
git add .
git commit -m "update links"
git push
```
Trang tự cập nhật sau ~1 phút.

## Gắn domain riêng (sau này, nếu muốn)
Mua domain → tạo file `CNAME` chứa domain → trỏ DNS về GitHub Pages → bật "Enforce HTTPS" trong Settings > Pages.
