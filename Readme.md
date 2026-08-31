# Đóng sách — Chuyển DOCX/HTML sang EPUB

Chuyển tài liệu Word (.docx) và HTML thành sách EPUB, không lỗi font tiếng Việt. Tất cả nằm trong một tệp HTML duy nhất, chạy offline ngay trong trình duyệt — tệp của bạn không rời khỏi máy.

## Cách dùng

1. Tải `doc2epub-offline.html` về, mở bằng trình duyệt (Chrome/Edge/Firefox/Safari).
2. Kéo thả tệp `.docx` / `.html` vào — thả nhiều tệp để gộp thành một cuốn.
3. Nhập tên sách, tác giả; tùy chỉnh bìa (tự tạo từ tên sách hoặc dùng ảnh riêng).
4. Bấm **Đóng sách EPUB** và tải về.

## Tính năng

- Tự tách chương theo Heading, tạo mục lục, giữ ảnh và bảng trong Word
- Bìa tùy chỉnh: tự vẽ từ tên sách + tác giả (5 tông màu) hoặc dùng ảnh riêng
- Chống lỗi tiếng Việt: chuẩn hóa Unicode NFC, tự dò encoding, nhúng font `.ttf` tùy chọn
- Chạy trên Windows, macOS, Linux và điện thoại, không cần cài đặt hay mạng

## Lưu ý

- Kindle: gửi epub qua **Send to Kindle** hoặc convert sang AZW3 bằng Calibre.
- Tệp HTML mã cũ TCVN3/VNI cần chuyển sang Unicode bằng Unikey trước.

Dùng [mammoth.js](https://github.com/mwilliamson/mammoth.js) và [JSZip](https://stuk.github.io/jszip/) (đã nhúng sẵn).
