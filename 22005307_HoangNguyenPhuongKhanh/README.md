# Tiêu đề dự án : Quản lý cửa hàng mỹ phẩm GUIMI

## Mô tả : Thêm xoá sửa sản phẩm, danh mục, loại sản phẩm, đăng ký, đăng nhập bằng PHP và trang mua hàng, chi tiết sản phẩm,thanh toán, xem các sản phẩm liên quan.

### Yêu cầu : tải phần mềm Xampp 7.4.20 trên link "https://www.apachefriends.org/download.html" để có thể chạy được CSDL MYPHPADMIN
tải Fontawesome bản 6.1.1, tải ckeditor và ckfinder. Đặc biệt yêu cầu phải có wifi để có thể thấy được hết toàn bộ nội dung.

#### Cách sử dụng dự án
_ Về phần CSDL:
+Mở xampp lên chỗ Apache và Mysql chọn Start để mở lên nếu không hiện màu xanh lá thì đã bị chiếm cổng vào Config để đổi cổng lại (nếu vẫn chưa biết cách sử dụng có thể lên Youtube hoặc Google tìm hiểu cách chạy).

+Sau đó mở trình duyệt Chrome lên và gõ "localhost:81/phpmyadmin" chỗ 80 đó là phụ thuộc vào số mà bạn đặt lại trong Config ở Apache. Khi truy cập vào, sẽ xuất hiện ra phần "Login" thì nhập vào Username : " root" và Password để trống đẻ có thể vào bên trong.Sau khi vào phpMyAdmin bạn chọn mới gõ vào tên cơ sở dữ liệu là "website_guimidemo" và chọn kiểu chữ là "utf8_unicode_ci" bấm "Tạo".
+Sau đó trong trang server MySQL ấn vào chữ "Import" kế bên "Export", nó hiện ra trang "Import" bạn chỉ cần click vào chữ "Choose file" rồi chọn file có tên là "website_guimidemo.sql" trong thư mục "admin" kéo xuống ở cuối trang bấm chọn và kéo xuống ấn "GO" là bạn có thể xem CSDL ấy có gì.

- Về phần WEb: 

+ Việc đầu tiên hãy đưa folder có tên "mypham" vào folder "htdocs" của folder"xampp" (chỉ có XAMPP mới có folder "htdocs") để có thể chạy chương trình

+ Quay lại trang PHPMYADMIN hồi nãy với đường dẫn là "localhost:81/phpmyadmin" chọn "Import" và "Choose file" trong thư mục mỹ phẩm chọn file có tên là "db_user.sql" ấn "GO" rồi mở một tab mới và nhập "localhost:81/mypham" và enter để truy cập vào trang web tại đây gồm trang chủ, các sản phẩm, các danh mục, trang mua hàng, thanh toán, đăng nhập,đăng ký,các sản phẩm liên quan. Lưu ý là phần này phải có wifi để xem các hiệu ứng đẹp.

+ Sau khi khám phá hết các tính năng trên trang web thì nhập tiếp vào "localhost:81/mypham/admin" sẽ hiện lên form Login. Nhập vào Username : "admin@gmail.com" và password : "123" để vào trang dành cho admin. Ngoài ra, nếu muốn tạo tài khoản khác thì bấm vào chữ Signup ở phía dưới để tạo tài khoản mới

+ Khi vào trong trang admin có thể thêm xoá sửa sản phẩm, danh mục, loại sản phẩm, xem các sản phẩm 

##### Link github : "https://github.com/phuongkhanh789/mypham"
