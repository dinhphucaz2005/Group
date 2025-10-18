# Nhóm 4 thành viên

Trang web tĩnh đơn giản giới thiệu 4 thành viên. Mở `index.html` trong trình duyệt hoặc chạy một server tĩnh để xem.

Cách mở nhanh (trong thư mục dự án):

- Dùng Python 3:

```bash
python3 -m http.server 8000
```

- Hoặc chỉ cần nhấp đúp `index.html` để mở bằng trình duyệt.

Các file chính:

- `index.html` - trang chính
- `assets/styles.css` - file CSS
- `assets/members/*.svg` - avatar SVG cho từng thành viên

Nếu bạn muốn dùng ảnh thật cho các thành viên, đặt file `member.jpg` vào thư mục `assets/members/` (tên chính xác `member.jpg`). Trang sẽ cố tải `member.jpg` cho mỗi thành viên; nếu file không tồn tại thì sẽ dùng các SVG sẵn có làm dự phòng.

Muốn mình thêm ảnh thực cho từng thành viên (khác nhau), liên kết tới mạng xã hội, hay form liên hệ không?