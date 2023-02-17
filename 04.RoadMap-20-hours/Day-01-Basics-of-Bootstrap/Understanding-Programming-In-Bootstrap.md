# Session 2 - Sử dụng Bootstrap 5

Từ phiên bản 5, Bootstrap đưa chúng ta tiếp cận theo **8 phần chính**

<https://getbootstrap.com/docs/5.3/getting-started/introduction/>

- **Customize**: tùy biến Bootstrap 5 theo ý muốn.
- **Layout**: Dựng bố cục Layout
- **Content**: Trình bày nội dung
- **Forms**: Dựng giao diện về Form ==> DONE
- **Components**: Các thành phần dựng sẵn bởi Bootstrap ==> DONE
- **Helpers**: Class soạn sẵn để sử dụng
- **Utilities**: Class soạn sẵn để sử dụng
- **Extend**: Thành phần Mở rộng cho Bootstrap như icon Font

Hoặc bạn muốn tiếp cận Bootstrap 5 theo hướng cũ thì có thể tham khảo tài liệu w3School

<https://www.w3schools.com/bootstrap5/index.php>

==========================================

## ⭐ Layout


### 🍄 Breakpoints

**Breakpoint** là những điểm (phạm vi giới hạn) mà tại đó nội dung của website sẽ co dãn một cách linh hoạt phụ thuộc vào chiều rộng của thiết bị nhằm đem đến cho người xem một trải nghiệm tuyệt vời và hoàn hảo nhất



#### Core concepts

- Breakpoints là điểm mấu chốt để thiết kế responsive.

- Media queries sử dụng `min-width` là chủ yếu.

- Mobile first

#### Các breakpoints hợp lệ

--------------------------

Bootstrap bao gổm 6 điểm breakpoints mặc định. Bạn có thể tùy chỉnh breakpoints nếu sử dụng với Sass.

Doc: <https://getbootstrap.com/docs/5.2/layout/breakpoints/#available-breakpoints>

### 🍄 Containers

Containers are a fundamental building block of Bootstrap that contain, pad, and align your content within a given device or viewport.

Doc: <https://getbootstrap.com/docs/5.2/layout/containers/>



### 🍄 Grid

==> QUAN TRỌNG NHẤT

==> LINH HỒN CỦA BOOTSTRAP

- Sử dụng Grid 12 cột, với 6 điểm breakpoints với nguyên tắc mobile-first.

- Các cột mặc định hiển thị dạng flexbox

Doc: <https://getbootstrap.com/docs/5.2/layout/grid/>

- Cách sử dụng Grid: Xem Examples


### 🍄 Columns

- Về mặt cách hoạt động thì Grid và Column giống nhau vì đều dựa trên **flexbox grid system** 

- Columns được hiểu nó dùng thay đổi chiều rộng của cột với các TÙY CHỌN như: alignment, ordering, and offsetting.

- Dùng các đặc tính của Flexbox để sử dụng

Ví dụ: <https://getbootstrap.com/docs/5.2/layout/columns/>

### 🍄 Gutters

Gutters là khoảng trống đệm giữa các cột. Xem hình minh họa

![Glutter](glutter.png)

Khi chưa có Flexbox thì dùng margin-right để tạo khoảng cách giữa các items.

Trong Flexbox, Grid ta có khái niệm là Gutters để tạo khoảng đệm giữa hàng và cột.

Chi tiết xem: <https://getbootstrap.com/docs/5.2/layout/gutters/>


### 🍄 Css Grid

- Sử dụng đặc tính `display: grid;` để tạo lưới hiển thị.
- Cách sử dụng: tương tự như Gird Flexbox, chỉ khác tên class.

Chi tiết: <https://getbootstrap.com/docs/5.2/layout/css-grid/>

==========================================

> **Trong Session 02 đi tìm hiểu 2 Mục: Components và Forms**

## ⭐ Components

**Components là gì?** Nói một cách dễ hiểu là Bootstrap đã tạo sẵn các thành phần thường hay dùng và định dạng chúng sẵn bằng CSS rồi. Bây giờ muốn sử dụng cái nào thì chỉ cần vào mục Components của Bootstrap 5.x xem code rồi đưa vào trang HTML thôi.

Danh sách các Components và cách sử dụng xem ngay trên trang chính thức:

<https://getbootstrap.com/docs/5.2/components/accordion>

**❤️12 Components quan trọng thường sử dụng:**

### 1. Navbar - Thanh điều hướng.

### 2. Pagination - Phân trang

### 3. Badges

### 4. Card

### 5. List group

### 6. Accordion

### 7. Dropdowns

### 8. Buttons

### 9. Modal

### 10. Toasts

### 11. Alers

### 12. Collapse



==========================================


## ⭐ Forms

Bootstrap cung cấp các `class` để định dạng layout của `form` một cách nhanh chóng, hỗ trợ responsive, tương thích trình duyệt.

Chi tiết xem: <https://getbootstrap.com/docs/5.2/forms/overview/>

- Các kiểu hiển thị input trong Bootstrap 5
- Layout Form: Horizontal và Vertical
- Validation Form Bootstrap 5


