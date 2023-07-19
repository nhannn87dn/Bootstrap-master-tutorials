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
<form id="myForm">
  <input placeholder="username" type="text" name="username"  />
  <input  placeholder="password" type="password" name="password" />
  <button type="submit">Submit</button>
</form>
```

Yêu cầu: 

* Bước 1: Lấy giá trị từ 2 ô username, password
* Bước 2: Kiểm tra 
- Nếu username chưa điền thì báo lỗi
- Nếu username ít hơn 4 kí tự thì báo lỗi
- Nếu password chưa điền thì báo lỗi
- Nếu password ít hơn 8 kí tự thì báo lỗi

* Bước 3: Nếu vượt qua được kiểm tra thì lấy username, password đem so sánh

- Nếu username = 'aptech' và password = '38yenbai' thì thông báo đăng nhập thành công
- Ngược lại: thông báo Sai username hoặc password

