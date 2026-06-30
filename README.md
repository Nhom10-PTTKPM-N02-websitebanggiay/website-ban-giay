# KickZone - Website Bán Giày

KickZone là website thương mại điện tử bán giày, cho phép người dùng duyệt sản phẩm, quản lý giỏ hàng và đặt mua trực tuyến. Hệ thống có giao diện dành cho **người dùng** và giao diện riêng cho **quản trị viên (Admin)**.

## Giao diện người dùng (User)

- **Trang chủ**: Hiển thị banner, danh sách sản phẩm nổi bật, sản phẩm mới.
- **Trang danh sách sản phẩm**: Hiển thị toàn bộ sản phẩm giày, hỗ trợ lọc theo danh mục, giá, size; tìm kiếm theo tên.
- **Trang chi tiết sản phẩm**: Hiển thị hình ảnh, mô tả, giá, các size còn hàng; cho phép chọn size và thêm vào giỏ hàng.
- **Trang giỏ hàng**: Xem danh sách sản phẩm đã chọn, cập nhật số lượng, xóa sản phẩm, tính tổng tiền.
- **Trang đặt hàng / thanh toán**: Nhập thông tin giao hàng, xác nhận đơn hàng (thanh toán COD).
- **Trang đăng nhập / đăng ký**: Xác thực tài khoản người dùng.
- **Trang hồ sơ cá nhân**: Xem và cập nhật thông tin cá nhân, địa chỉ, lịch sử đơn hàng.

## Giao diện quản trị (Admin)

- **Dashboard thống kê**: Hiển thị các chỉ số KPI tổng quan (doanh thu, đơn hàng...).
- **Biểu đồ doanh thu**: Biểu đồ cột trực quan (dùng Recharts), cho phép xem theo 7 ngày / 30 ngày gần nhất hoặc chọn theo năm.
- **Quản lý sản phẩm**: Thêm, sửa, xóa sản phẩm; quản lý tồn kho theo size.
- **Quản lý đơn hàng**: Xem danh sách đơn hàng, cập nhật trạng thái xử lý (đang xử lý, đã giao, đã hủy...).
- **Quản lý người dùng**: Xem danh sách tài khoản người dùng đã đăng ký.

## Công nghệ giao diện

- **Frontend**: React.js
- **Biểu đồ**: Recharts
- **Giao tiếp dữ liệu**: Gọi API thông qua API Gateway đến các service backend (Auth, Product, Cart, Order, Profile)
