# Session 2- Sử dụng Bootstrap 5

> **Trong Session 02 đi tìm hiểu các Module còn lại**



## ⭐ Content

Chuyên về trình bày đội dung

### 🍄 Reboot

Css Reset các Css mặc định trình duyệt dựa trên Normalize.css


### 🍄 Typography

Chủ đề về cách hiển thị Text

- Headings: h1-h6
- Display headings: display-1 -> display-6
- Lead
- Inline text elements
- Abbreviations
- Blockquotes
- Alignment
- Lists

Ví dụ: <https://getbootstrap.com/docs/5.2/content/typography/>


### 🍄 Images

Boottrap cung cấp các `class` giúp chúng ta thao tác, định dạng hình ảnh một cách đơn giản hơn.

Xem ví dụ: 05.Examples\Session-2\images\index.html

### 🍄 Figures

Dùng để tạo Caption cho một hình ảnh

Xem ví dụ: 05.Examples\Session-2\images\figures.html


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

### Color and background

Set màu chữ bằng tiền tố `.text-*` và `.bg-*`

```html
    <span class="badge text-bg-primary">Primary</span>
    <span class="badge text-bg-info">Info</span>
```

### Position

```html
    <div class="fixed-top">...</div>
    <div class="fixed-bottom">...</div>
```

### Stacks

Vertical spacing

```html

    <div class="vstack gap-3">
        <div class="bg-body-tertiary border">First item</div>
        <div class="bg-body-tertiary border">Second item</div>
        <div class="bg-body-tertiary border">Third item</div>
    </div>
```

Horizontal spacing

```html
    <div class="hstack gap-3">
        <div class="bg-body-tertiary border">First item</div>
        <div class="bg-body-tertiary border">Second item</div>
        <div class="bg-body-tertiary border">Third item</div>
    </div>
```

### Text truncation: rút gọn nội dung

Thường áp dụng cho các bài post có nội dung mô tả ngắn

This text is q...
This text is quite lo...



## ⭐ Utilities

**Helpers** và **Utilities** chung quy thì nó cũng chỉ là các `class` được Bootstrap tạo sẵn, có cái gì đó có hơi hướng của **Tailwind CSS**

Giúp chúng ta định dạng Css nhanh mà ko cần phải đi code css vất vả nữa.


### Background

### Color 

### Border 

### Display - IMPORTANT

### Flex

### Position relative and absolute 

### Object fit dùng cho hình ảnh

### Shadows

### Spacing - BEST

### Text



==========================================

## ⭐ Extend

Phần này chúng ta chỉ cần quan tâm tới mục thôi đó là **icon**.

Bootstrap 5 đã không đưa **Glyphicons** vào gói phát triển nữa.

Và xem icon như là một thành phần mở rộng - **Bootstrap Icons**

Cách sử dụng

```code
https://icons.getbootstrap.com/#install
```

Có thể sử dụng bên thứ 3 khác như: Font Awesome, Google Material icons...

==========================================


## KẾT LẠI


- Linh hồn của Bootstrap 5 là **flexbox grid system** với 12 columns.
- Responsive với 6 điểm Breakpoints với quy tắc Mobile First.
- Components là các Block IU được Bootstrap dựng sẵn, chỉ việc dùng.
- Còn lại là các `class` được Bootstrap định nghĩa sẵn để định dạng các elements một cách nhanh chóng mà ko cần tạo thêm file `.css`

