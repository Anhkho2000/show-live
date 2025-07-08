# Bài Thực Hành Buổi 3: `this`, call, apply, bind trong JavaScript

## Bài 1: Method và `this`
Tạo một object `car` có thuộc tính `brand` là "Toyota" và một method `showBrand` in ra `"Xe của tôi là Toyota"` sử dụng `this`.

## Bài 2: Gọi hàm với `call()`
Tạo một hàm `introduce` in ra `"Tôi là <name>"`. Dùng `call()` để gọi hàm với object `{ name: "Minh" }`.

## Bài 3: Gọi hàm với `apply()`
Tạo một hàm `greet` nhận 2 tham số `greeting` và `punctuation`, in ra ví dụ `"Hello, Hoa!"`. Dùng `apply()` để gọi với object `{ name: "Hoa" }` và mảng `["Hello", "!"]`.

## Bài 4: Sử dụng `bind()` để trì hoãn gọi hàm
Viết hàm `sayHello` in ra `"Xin chào, tôi là <name>"` dùng `this`. Tạo object `{ name: "Linh" }`. Dùng `bind()` để tạo hàm mới rồi gọi hàm đó sau 1 giây bằng `setTimeout`.

## Bài 5: Sửa lỗi `this` trong `setTimeout`
Cho object `counter = { count: 0, increase: function() { ... } }`. Trong `increase`, dùng `setTimeout` để tăng `count` lên 1 sau 1 giây và in ra giá trị mới. Dùng arrow function hoặc bind để sửa lỗi `this`.

> Mỗi bài em hãy tạo file JS riêng để chạy thử và in ra kết quả trong console.