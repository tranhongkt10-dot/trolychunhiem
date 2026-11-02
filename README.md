# Lớp Học Hạnh Phúc – bản GitHub Pages

## Cấu trúc cần giữ nguyên

- `index.html` – mã nguồn ứng dụng.
- `styles.css` – Tailwind CSS đã biên dịch sẵn, không cần CDN Tailwind.
- `assets/audio/applause.mp3` – âm thanh vỗ tay dùng trong ứng dụng.

## Cập nhật repository hiện tại

1. Tải bản sao lưu repository hiện tại trước khi thay thế.
2. Tải `index.html` mới lên thư mục gốc và ghi đè file cũ.
3. Tải `styles.css` mới lên thư mục gốc và ghi đè file cũ.
4. Tải thư mục `assets` lên thư mục gốc. Bảo đảm đường dẫn cuối cùng là `assets/audio/applause.mp3`.
5. Không xóa hoặc thay đổi cấu hình Firebase, tài khoản Firebase, Firestore Rules hay dữ liệu Firestore.
6. Giữ nguyên `wrangler.jsonc` nếu cô còn dùng Cloudflare; GitHub Pages không cần tệp này.
7. Sau khi Commit, chờ GitHub Pages triển khai xong rồi tải lại trang bằng Ctrl+F5.

## Ghi chú

- Ứng dụng tiếp tục dùng Firebase project/config được giữ trong `index.html` này. Không tạo dự án Firebase mới.
- Bản âm thanh `applause.mp3` trong gói là hiệu ứng vỗ tay thay thế. Nếu cần đúng file âm thanh cũ, hãy thay bằng file MP3 gốc nhưng giữ nguyên tên và đường dẫn.
- Đây là gói triển khai tĩnh cho GitHub Pages; không chứa cấu hình Cloudflare Worker.
