# Website Vinabook

Website Vinabook là một ứng dụng web được phát triển bằng **React.js** cho front-end, **Node.js** cho back-end, và **MySQL** cho cơ sở dữ liệu.

## Hướng Dẫn Cài Đặt

### 1. Cài Đặt Cơ Sở Dữ Liệu

Để nhập cơ sở dữ liệu `vinabook_db` vào MySQL, bạn cần làm theo các bước sau:

1. Mở **MySQL Workbench** và kết nối với cơ sở dữ liệu của bạn.
2. Chọn `Server` > `Data Import`.
3. Chọn `Import from Self-Contained File` và chọn tệp `vinabook_db.sql` từ máy tính của bạn.
4. Chọn cơ sở dữ liệu đích và nhấp vào nút `Start Import`.

### 2. Đăng Nhập Admin

- **Tài Khoản Admin 1**:
  - Username: `admin@gmail.com`
  - Password: `1`
- **Tài Khoản Admin 2**:

  - Username: `wq`
  - Password: `1`

- URL Trang Admin: [http://localhost:3000/admin/home](http://localhost:3000/admin/home)

## Chức Năng Dự Án

1. **Đăng nhập, Đăng ký**:

   - Xác thực đăng nhập, đăng ký tài khoản mật khẩu người dùng, lưu token.

2. **Quản Lý Sản Phẩm**:

   - Thêm, sửa, xóa các sản phẩm sách.
   - Hiển thị danh sách sách theo danh mục và tìm kiếm sản phẩm.
   - Sắp xếp các loại sách theo đơn giá, giảm giá,...

3. **Quản Lý Người Dùng**:

   - Đăng ký, đăng nhập người dùng.
   - Quản lý thông tin cá nhân và lịch sử đặt hàng.

4. **Đặt Hàng**:

   - Người dùng có thể thêm sách vào giỏ hàng và đặt hàng.
   - Hiển thị chi tiết đơn hàng và quản lý tình trạng đặt hàng.

5. **Trang Quản Trị (Admin Page)**:

   - Quản lý sản phẩm: thêm, sửa, xóa và cập nhật sản phẩm.
   - Quản lý người dùng: theo dõi và quản lý tài khoản người dùng.

6. **API Backend**:
   - Sử dụng RESTful API để xử lý các yêu cầu liên quan đến sản phẩm, người dùng và đặt hàng.
   - Cơ sở dữ liệu MySQL để lưu trữ và quản lý dữ liệu.

## Thông Tin Liên Hệ

Nếu bạn gặp phải bất kỳ vấn đề nào hoặc cần thêm hỗ trợ, vui lòng liên hệ với chúng tôi qua email: `vusam1802@gmail.com` hoặc qua trang [GitHub](https://github.com/samdeptraj?tab=repositories).
