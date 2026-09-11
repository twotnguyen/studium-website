# Studium — Thư viện & đối thoại triết học

Website giới thiệu, nghiên cứu và bàn luận sâu về triết học Đông — Tây:
Khắc kỷ · Hiện sinh · Lão Trang · Phật học · Khổng học.

🌐 **Xem trực tiếp:** https://twotnguyen.github.io/studium-website/

## Các trang

| Trang | Nội dung |
|---|---|
| `index.html` | Mục lục dự án — 8 cửa vào |
| `trang-chu.html` | Trang chủ: hero, hoạt động cộng đồng, 5 trường phái |
| `thu-vien.html` | Thư viện luận giải, lọc theo trường phái |
| `doi-thoai.html` | Phòng đối thoại, quy tắc tranh luận |
| `chuyen-de.html` | Chuyên đề dài kỳ: *Philia* là gì? (Aristotle) |
| `chuyen-de-ergon.html` | Chuyên đề: Ergon — con người để làm gì? |
| `chuyen-de-arete.html` | Chuyên đề: Aretē — nghệ thuật thói quen |
| `su-kien.html` | Lịch đọc chung, đối thoại, trà đàm + form đăng ký |
| `bien-ban-suy-tuong.html` | Biên bản nhóm đọc chung *Suy tưởng* (Marcus Aurelius) |

## Chạy local

Mở bằng server tĩnh (không dùng `file://` trực tiếp vì trình duyệt nhúng
có thể chặn chuyển trang):

```bash
cd studium-website
python -m http.server 8123
# mở http://localhost:8123/index.html
```

## Kỹ thuật

- HTML + CSS thuần túy, không build step, không dependency.
- Font: Inter Tight / Playfair Display / JetBrains Mono (Google Fonts).
- 1 file CSS dùng chung `atelier.css` + `<style>` riêng mỗi trang.
- Responsive: breakpoint 880px / 560px, menu hamburger + chế độ tối/sáng.
