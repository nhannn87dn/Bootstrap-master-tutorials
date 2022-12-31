# Session 6 - Sử dụng Bootstrap 5

Từ phiên bản 5, Bootstrap đưa chúng ta tiếp cận theo **8 phần chính**

<https://getbootstrap.com/docs/5.3/getting-started/introduction/>

- **Customize**: tùy biến Bootstrap 5 theo ý muốn.
- **Layout**: Dựng bố cục Layout ==> DONE
- **Content**: Trình bày nội dung
- **Forms**: Dựng giao diện về Form ==> DONE
- **Components**: Các thành phần dựng sẵn bởi Bootstrap ==> DONE
- **Helpers**: Class soạn sẵn để sử dụng
- **Utilities**: Class soạn sẵn để sử dụng
- **Extend**: Thành phần Mở rộng cho Bootstrap như icon Font

Hoặc bạn muốn tiếp cận Bootstrap 5 theo hướng cũ thì có thể tham khảo tài liệu w3School

<https://www.w3schools.com/bootstrap5/index.php>

==========================================


## ⭐ Content

Chuyên về trình bày đội dung

Tiếp tục phần trước

### 🍄 Tables

Bootstrap cung cấp các `class` để định dạng `table` một cách nhanh chóng và chuyên nghiệp.

Chi tiết xem: <https://getbootstrap.com/docs/5.2/content/tables/>

==========================================


## ⭐ Customize

Bootstrap 5 thiết kế để cho chúng ta có thể tùy biến linh hoạt: thêm mới các class theo ý muốn.
Tuy nhiên nó sử dụng với Sass thì mới phát huy hết công năng.

Phiên bản Bootstrap 5 cho chúng ta sử dụng các biến `css-variables` khai báo sẵn ở `:root` để customize css, giữ được tính nhất quán các giá trị thông số.

Danh sách các biến: <https://getbootstrap.com/docs/5.2/customize/css-variables/>

Sử dụng các biến để customize:

```css

div {
    background-color: var(--bs-gray-300);
    color: var(--bs-black);
    border: 1px solid var(--bs-border-color);
    border-radius: var(--bs-border-radius);
}

```

==========================================


## ⭐ Helpers

## ⭐ Utilities

**Helpers** và **Utilities** chung quy thì nó cũng chỉ là các `class` được Bootstrap tạo sẵn, có cái gì đó có hơi hướng của **Tailwind CSS**

Giúp chúng ta định dạng Css nhanh mà ko cần phải đi code vất vả nữa.

Bạn chỉ việc mở ra xem nó là gì và nhớ để dùng thôi.

==========================================

## ⭐ Extend

Phần này chúng ta chỉ cần quan tâm tới mục thôi đó là **icon**.

Bootstrap 5 đã không đưa **Glyphicons** vào gói phát triển nữa.

Và xem icon như là một thành phần mở rộng - **Bootstrap Icons**

Có thể sử dụng bên thứ 3 khác như: Font Awesome, Google Material icons...

==========================================
## KẾT LẠI


- Linh hồn của Bootstrap 5 là **flexbox grid system** với 12 columns.
- Responsive với 6 điểm Breakpoints với quy tắc Mobile First.
- Components là các Block IU được Bootstrap dựng sẵn, chỉ việc dùng.
- Còn lại là các `class` được Bootstrap định nghĩa sẵn để định dạng các elements một cách nhanh chóng mà ko cần tạo thêm file `.css`
