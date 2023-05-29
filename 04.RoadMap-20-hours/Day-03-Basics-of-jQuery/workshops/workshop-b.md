# Thực hành tại Lab - Session 4

Nguồn data: <https://jsonplaceholder.typicode.com/posts>


## Step 1:

- Tạo một bảng có header gồm các cột: ID, title, Author, Actions
- Sử dụng AJAX để lấy Data đổ vào phần thân của Tabel đó.
  - Nếu lấy thành công thì thêm thông tin vào
  - Thất bại thì chèn dòng với thông báo: Không tìm thấy dữ liệu
- Cột Author: Nếu giá trị userId = 1 thì hiển thị là Admin
- Cột Actions có 2 action: Xem và Xóa
  - Click vào Xóa sẽ xuất hiện một Modal xác nhận. Bạn có chắc chắn muốn xóa không ?
  - Nếu ok thì console đã xóa ID số bao nhiêu đó.


## Step 2:

- Phía trên bảng đó tạo thêm một nút: Thêm mới
- CLick vào sẽ mở một Modal là một form
    - Trường title kiểu text
    - Trường body kiểu texteare
    - Trường userID kiểu hidden

Submit Form xong thì ẩn Modal
- Nếu thành công thì xuất hiện **Toasts** thông báo thêm mới thành công
- Nếu thất bại thì xuất hiện **Toasts** thông báo thêm mới thất bại