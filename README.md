# Nhóm 5 thành viên

Trang web tĩnh đơn giản giới thiệu 5 thành viên nhóm. Mỗi thành viên có thông tin riêng và link đến portfolio cá nhân.

Cách mở nhanh (trong thư mục dự án):

- Dùng Python 3:

```bash
python3 -m http.server 8000
```

- Hoặc chỉ cần nhấp đúp `index.html` để mở bằng trình duyệt.

Tính năng:
- Mỗi thành viên có link riêng đến portfolio/trang cá nhân
- Hover effects và keyboard navigation
- Responsive design
- Fallback từ ảnh JPG sang SVG nếu ảnh không có

Các file chính:

- `index.html` - trang chính
- `assets/styles.css` - file CSS
- `assets/members/*.svg` - avatar SVG cho từng thành viên
- `notes.txt` - thông tin chi tiết các thành viên

Ảnh thành viên cần thiết trong `assets/members/`:
- `khoa.jpg` - Đoàn Đăng Khoa
- `tung.jpg` - Nguyễn Ngọc Tùng  
- `dat.jpg` - Lâm Tiến Đạt
- `thang.jpg` - Nguyễn Quốc Thắng
- `phuc.jpg` - Nguyễn Đình Phúc

Nếu ảnh không tồn tại, trang sẽ sử dụng các SVG avatar có sẵn làm dự phòng.

Muốn mình thêm ảnh thực cho từng thành viên (khác nhau), liên kết tới mạng xã hội, hay form liên hệ không?