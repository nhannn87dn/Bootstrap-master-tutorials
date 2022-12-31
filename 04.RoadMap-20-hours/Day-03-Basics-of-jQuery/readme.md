# Basics-of-jQuery

Xem Slide Session 3

Tham khảo 2 nguồn học jQuery:

- Chính chủ: <https://learn.jquery.com/>

- w3School: <https://www.w3schools.com/jquery/jquery_intro.asp>


## ⭐ 1. jQuery Functions


1. Basic Declaration: 

```js
function basicFunction(name){
    console.log(`Hello ${name} !`);
}
```

2. Declaration as a variable name: 

```js

let multiply = function(a,b){
    return a*b;
}

```


3. Self-invoking function Declaration:

Hay còn gọi là anonymous function: hàm nặc danh, hàm không tên.

```js
(function(){
    console.log('Anonymous function');
})();

```

4. User-defined function Declaration:

```js

$(document).ready(function(){

    // Defined function
    $.fn.myFunction = function() {
      console.log('hello world');
    };

    //Call function
    $("#call").click(function(){
        $.fn.myFunction();
    });

});

```

##  ⭐ 2. jQuery Selector

Tham khảo: <https://www.w3schools.com/jquery/jquery_selectors.asp>


##  ⭐ 3. JSON

### 3.1 JSON là gì ?

- JSON là viết tắt của **J**ava**S**cript **O**bject **N**otation.
- JSON Là một định dạng trao đổi dữ liệu nhẹ nhàng.
- JSON là một văn bản thuần túy được viết như Object của Javascript.
- JSON được sử dụng để gửi dữ liệu giữa các máy tính, dịch vụ I/O.
- JSON là một ngôn ngữ độc lập.

> Lưu ý: Cú pháp JSON bắt nguồn từ ký hiệu Object của JavaScript, nhưng định dạng JSON chỉ là văn bản.



Xem đẩy đủ: <https://www.w3schools.com/js/js_json_intro.asp>

- Tạo một JSON
- Truy cập các phần tử một JSON


### 3.2 Cú pháp JSON

```js
//JSON
{"name":"John"}
/* 
- key phải là chuổi, và đặt trong dấu nháy kép
- value: kiểu string được đặt trong dấu nháy kép

*/

//Khác so với Javascript
{name:"John"}

```

Giá trị của JSON - JSON Values;

- string

```js
{"name":"John"}
```
- number

```js
{"age":30}
```

- object (json object)

```js
{
"employee":{"name":"John", "age":30, "city":"New York"}
}
```
- array

```js
{
"employees":["John", "Anna", "Peter"]
}
```

- boolean

```js
{"is_admin":true}
```

- null

```js
{"middlename":null}
```

Nó khác Javascript ở chổ là **không bao gồm**: function, date, undefined



### 3.3 Sử dụng JSON

```js
person = {
"employees":["John", "Anna", "Peter"]
};

//use
let employees = person.employees;

console.log(employees);

```

### 3.3 Convert một chuổi sang JSON

Ví dụ 1:

```js
// String as JSON:
const str = '{"name":"John", "age":30, "city":"New York"}';
//Convert to JSON
const obj = JSON.parse(str);
```

Ví dụ 2:

```js
//Array as JSON
const text = '["Ford", "BMW", "Audi", "Fiat"]';
const myArr = JSON.parse(text);
```

Ví dụ 3:

```js
const text = '{"name":"John", "birth":"1986-12-14", "city":"New York"}';
const obj = JSON.parse(text);
//Convert a string into a date
obj.birth = new Date(obj.birth);
```

Ví dụ 4:

Hàm ko được hỗ trợ trong JSON tuy nhiên bạn có thể sử dụng theo cách sau:

```js
const text = '{"name":"John", "age":"function () {return 30;}", "city":"New York"}';
const obj = JSON.parse(text);

//Convert a string into a function
obj.age = eval("(" + obj.age + ")");
```


### 3.4 Convert JSON Object sang JSON string

```js
const myObj = { "name": "John", "age": 31, "city": "New York" };
const myJSON = JSON.stringify(myObj);

//return 
'{"name":"John", "age":31, "city":"New York"}'

```