# Quỹ "Vì những trái tim bé bỏng" — Website

Website giới thiệu Quỹ "Vì những trái tim bé bỏng" (QN), thành lập theo Quyết định số 315/UBND.

## Cấu trúc
- `index.html` — trang chủ
- `gioi-thieu.html` — trang Giới thiệu
- `chuong-trinh.html` — trang Chương trình
- `hoat-dong.html` — trang Các hoạt động
- `minh-bach.html` — trang Minh bạch
- `lien-he.html` — trang Liên hệ
- `404.html` — trang lỗi 404 tùy chỉnh (GitHub Pages tự dùng khi không tìm thấy trang)
- `robots.txt`, `sitemap.xml` — hỗ trợ Google index trang và Google Ad Grants
- `css/style.css` — toàn bộ style
- `js/main.js` — menu mobile (đóng khi bấm ra ngoài / nhấn Esc) + năm hiện tại ở footer

## Đã bổ sung
- Thẻ `canonical`, Open Graph, Twitter Card cho từng trang (hỗ trợ chia sẻ mạng xã hội và SEO)
- `aria-current="page"` + trạng thái active trên menu để biết đang ở trang nào
- `robots.txt` + `sitemap.xml` liệt kê đủ 6 trang
- Trang 404 tùy chỉnh
- Đóng menu mobile khi bấm ra ngoài hoặc nhấn phím Esc

## Chạy thử cục bộ
Chỉ cần mở `index.html` bằng trình duyệt, hoặc dùng một static server bất kỳ, ví dụ:

```
python3 -m http.server 8080
```

## Triển khai qua GitHub Pages
Vào **Settings → Pages** của repo này, chọn nhánh `main`, thư mục `/ (root)`, rồi Save. Sau vài phút trang sẽ chạy tại:

```
https://hvhwan-debug.github.io/TTBB/
```

## Cần cập nhật thêm
- Số điện thoại liên hệ chính xác (đang dùng: +84 913 498 459)
- Logo và hình ảnh thật của các hoạt động (hiện đang dùng minh họa)
