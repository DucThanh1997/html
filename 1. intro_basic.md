# Introduction
## Html là gì?
- HTML là viết tắt của Hyper Text Markup Language
- HTML mô tả cấu trúc của các trang web bằng cách sử dụng markup
- Các tag sẽ được dùng để đại diện các phần tử của Html
- Web không hiện các tag đó nhưng dùng các tag để biểu diễn nội dung trang web

Ví dụ
```
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```
 Kết quả
 ![image](https://user-images.githubusercontent.com/45547213/51667070-c1c4f280-1ff1-11e9-9130-09a46a09166e.png)
 
 ### Giải thích
 - `<!DOCTYPE html>`: Khai báo tài liệu này là html5
 - `<html>`: Là 1 phần tử gốc của page html
 - `<head>`: Là phần tử chứa các thông tin meta của tài liệu
 - `<title>`: Là phần tử đặt tên của page 
 - `<body>`: Là phần tử chứa nội dung trang hiển thị
 - `<h1>`: định nghĩa tiêu đề lớn
 - `<p>`: định nghĩa 1 dòng
 
 ## Html tags
 - Là các phần tử có tên bao quanh bởi dấu ngoặc nhọn

 ```
 <tagname>content goes here...</tagname>
 Ví dụ
 <p> lolololo </p>
 ```
 
 ## Cấu trúc của 1 page html
 ![image](https://user-images.githubusercontent.com/45547213/51669648-7e6d8280-1ff7-11e9-8568-c351a0cb0a32.png)

# Các thẻ cơ bản của html
 1. Html heading
 
 Được xác định từ h1 đến h6
 ```
 <!DOCTYPE html>
<html>
<body>

<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>

</body>
</html>
```

Kết quả 
![image](https://user-images.githubusercontent.com/45547213/51670487-4b2bf300-1ff9-11e9-808b-21ef46dcf1d1.png)

2. Html paragraph

HTML paragraphs được định nghĩa bằng thẻ  <p>:
```
<!DOCTYPE html>
<html>
<body>

<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

</body>
</html>
```
Kết quả
![image](https://user-images.githubusercontent.com/45547213/51670760-e91fbd80-1ff9-11e9-926a-109a395f5d96.png)

3. Html Link

cái thẻ này ấn vào đấy nó sẽ ra cái đường link

`<a href="https://www.w3schools.com">This is a link</a>`

4. Html image

cái thẻ này hiển thị hình ảnh

`<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">`

5. Html list

Hiển thị list ul thì không order còn ol thì có
```
ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```

Kết quả 
![image](https://user-images.githubusercontent.com/45547213/51671500-a6f77b80-1ffb-11e9-9a76-2ec93af9c0f2.png)
