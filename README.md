Web đặt vé xem phim# Đề tài: Hệ thống Quản lý Đặt vé Xem phim

## 1. Giới thiệu hệ thống
Hệ thống Quản lý Đặt vé Xem phim được xây dựng nhằm hỗ trợ người dùng dễ dàng đặt vé trực tuyến, tra cứu lịch chiếu và quản lý vé đã đặt.  
Đối với quản trị viên, hệ thống cung cấp chức năng quản lý phim, suất chiếu, phòng chiếu và theo dõi doanh thu.  

**Các chức năng chính:**
- Người dùng:
  - Đăng ký / đăng nhập
  - Xem danh sách phim, lịch chiếu
  - Đặt vé xem phim, xem lại vé đã đặt
- Quản trị viên:
  - Quản lý phim
  - Quản lý lịch chiếu, phòng chiếu
  - Quản lý vé và doanh thu

---

## 2. Mô tả công nghệ sản phẩm
Hệ thống được phát triển bằng các công nghệ:
- **Ngôn ngữ lập trình:** PHP (thuần, không framework)  
- **Cơ sở dữ liệu:** MySQL  
- **Máy chủ chạy thử:** XAMPP (Apache + MySQL)  
- **Giao diện:** HTML, CSS, JavaScript (kết hợp Bootstrap để responsive)  

Cấu trúc thư mục dự án:



---

## 3. Hình ảnh các chức năng
*(Bạn tự thêm ảnh minh họa vào phần này – ví dụ: giao diện đăng nhập, giao diện đặt vé, quản lý phim...)*

---

## 4. Các bước cài đặt
1. **Cài đặt XAMPP**  
   - Tải và cài XAMPP: [https://www.apachefriends.org](https://www.apachefriends.org)  
   - Khởi động Apache và MySQL trong XAMPP Control Panel.  

2. **Tạo cơ sở dữ liệu**  
   - Mở [http://localhost/phpmyadmin](http://localhost/phpmyadmin)  
   - Tạo database mới, ví dụ: `movie_booking`  
   - Import file `db_movie.sql` trong thư mục dự án vào database vừa tạo.  

3. **Copy source code vào thư mục htdocs**  
   - Giải nén project vào:  
     ```
     C:\xampp\htdocs\project_movie_booking
     ```  

4. **Cấu hình kết nối database**  
   - Mở file `includes/db_connect.php` (hoặc file cấu hình kết nối)  
   - Chỉnh sửa thông tin nếu cần:
     ```php
     $servername = "localhost";
     $username   = "root";
     $password   = "";
     $dbname     = "movie_booking";
     ```

5. **Chạy hệ thống**  
   - Mở trình duyệt và truy cập:  
     ```
     http://localhost/project_movie_booking
     ```  

6. **Tài khoản mẫu** (nếu có)  
   - Admin: `admin / 123456`  
   - User: `user / 123456`  

---

📌 *Lưu ý: Có thể tùy chỉnh tên database, tài khoản admin, giao diện theo nhu cầu.*  
