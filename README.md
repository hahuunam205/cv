# CV Cá Nhân — Hà Hữu Nam

Trang CV cá nhân viết bằng HTML/CSS/JavaScript thuần, không cần cài đặt hay build.

## Tính năng

- **Song ngữ Việt / Anh**: nút `Switch to English` ở góc trên bên phải chuyển đổi toàn bộ nội dung.
- **Bố cục 2 cột**: cột trái (ảnh, mục tiêu nghề nghiệp, điểm mạnh, liên hệ) và cột phải (kinh nghiệm làm việc, kỹ năng, sở thích).
- **Vòng tròn kỹ năng** vẽ bằng `conic-gradient` (ReactJS 90%, NodeJS 75%, Docker 60%).
- **Responsive cơ bản** theo chiều rộng màn hình.

## Công nghệ sử dụng

| Thành phần | Mô tả |
| --- | --- |
| HTML5 | Cấu trúc trang, thuộc tính `data-vi` / `data-en` cho nội dung song ngữ |
| CSS3 | Flexbox, `conic-gradient`, Google Fonts (Roboto) |
| JavaScript | Hàm `toggleLanguage()` / `applyLanguage()` đổi ngôn ngữ |

## Cách chạy

Mở trực tiếp file `CV giữa kì.html` bằng trình duyệt:

```bash
# Windows
start "" "CV giữa kì.html"
```

Hoặc chạy một local server:

```bash
python -m http.server 8000
# sau đó mở http://localhost:8000
```

## Cấu trúc thư mục

```
cv/
├── CV giữa kì.html   # Toàn bộ trang CV (HTML + CSS + JS)
├── DDF9E085-27C2-4FA8-8201-9E0CD7513B5A.png  # Ảnh đại diện
└── README.md
```

## Tùy chỉnh

- **Ảnh đại diện**: thay file PNG và cập nhật thuộc tính `src` của thẻ `<img class="profile-pic">`.
- **Nội dung**: sửa đồng thời cả hai thuộc tính `data-vi` và `data-en` để bản dịch luôn khớp.
- **Màu sắc**: các màu chính là `#2c3e50` (xanh đậm), `#e74c3c` (đỏ), `#f39c12` (cam).

## Liên hệ

- Email: hahuunam2020@gmail.com
- GitHub: [github.com/hahuunam205](https://github.com/hahuunam205)
