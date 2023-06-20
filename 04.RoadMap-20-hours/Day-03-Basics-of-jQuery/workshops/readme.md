# jQuery Basic

## Task 1

- Tạo một chương trình tính toán đơn giản với 2 số.
- Sử dụng các phép tính: cộng, trừ, nhân, chia
- Bằng cách tạo giao diện html với:
  - input có name: a
  - input có name: b
  - select có name: op (với các options add = cộng, subtract = trừ, multiply = nhân, divide = chia, modulus = chia lấy dư)
  - In  kết quả của phép tính ra một thẻ div#result

## Task 2 

- Tạo ra một button với icon 3 dấu gạch ngang
- CLick vào button này thì hiển thị ra một navigation
- Thực hiện show ra với 3 cách: toogleClass, show (với speed), fadeIn (với speed), slideDown (với speed)


## Task 3

Cho một đoạn code html như sau:

```html
<ul id="list">
    <li class="child_one">Child 1</li>
    <li class="child_two">
        <img src="images/photo.png" alt="photo" />
    </li>
    <li class="child_three"><a href="link3">Child 3</a></li>
</ul>
```

Yêu cầu:

* 1. Thêm cho thẻ ul một class mới tên `list`
* 2. Lấy nội dung: Child 1 từ thẻ li đầu tiên, hiển thị nội dung lấy được ra console
* 3. Lấy nội dung: thuộc tính `src` và `alt` từ thẻ img, hiển thị ra console
* 4. Thay đổi: thuộc tính `src` và `alt` từ thẻ img bằng một giá trị mới
* 5. Lấy tên class của thẻ li thứ 3, hiển thị ra console


## Task 4

Cho một đoạn code html như sau:

```html
<input placeholder="username" type="text" name="username" value="" />
<input  placeholder="password" type="text" name="password" value="" />
```

Yêu cầu: 

* Bước 1: Add cho 2 input nói trên 2 giá trị tương ứng vào thuộc tính value
* Bước 2: Add cho 2 input nói trên 2 thuộc tính `id`
* Bước 3: Lấy 2 giá trị vừa add ở bước 1 dựa vào `id` đã thêm ở bước 2, rồi show kết quả ra console

Gợi ý: thực hiện tuần từ từng bước là được