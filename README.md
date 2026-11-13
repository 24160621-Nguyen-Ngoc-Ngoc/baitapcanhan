# Tuổi Trẻ Đáng Giá Bao Nhiêu? — Website cảm nhận sách

Website tĩnh được xây dựng bằng HTML và CSS, có thể triển khai miễn phí bằng GitHub Pages.

## Cấu trúc

- `index.html`: Trang chủ và toàn bộ giao diện website.
- `README.md`: Hướng dẫn triển khai.
- `.nojekyll`: Giúp GitHub Pages phục vụ các tệp tĩnh mà không chạy Jekyll.

## Chạy trên máy tính

Mở trực tiếp `index.html` bằng trình duyệt (Chrome, Edge, Firefox).

## Đưa website lên GitHub Pages

1. Đăng nhập GitHub và tạo repository mới, ví dụ: `tuoi-tre-dang-gia-bao-nhieu`.
2. Chọn repository ở chế độ Public (hoặc dùng gói GitHub hỗ trợ Pages cho repository riêng tư).
3. Chọn **Add file → Upload files**.
4. Tải lên toàn bộ nội dung trong thư mục này, bảo đảm `index.html` nằm ở thư mục gốc repository.
5. Chọn **Commit changes**.
6. Vào **Settings → Pages**.
7. Trong **Build and deployment**, chọn **Deploy from a branch**.
8. Chọn branch `main`, thư mục `/(root)`, sau đó nhấn **Save**.
9. Đợi GitHub triển khai và mở đường dẫn được hiển thị trong mục Pages. Thường có dạng:
   `https://TEN-TAI-KHOAN.github.io/tuoi-tre-dang-gia-bao-nhieu/`

## Ghi chú

- Website không cần cài đặt Node.js, framework hoặc chạy lệnh build.
- Phông chữ Google Fonts cần kết nối Internet; nếu ngoại tuyến, trình duyệt sẽ dùng phông chữ dự phòng.
- Khi cập nhật nội dung, sửa `index.html` rồi commit lại lên GitHub.
