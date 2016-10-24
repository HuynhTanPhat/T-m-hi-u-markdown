>## ***TÌM HIỂU VỀ MARKDOWN***
>
>**Huỳnh Tấn Phát**

### Mục lục

[1.MARKDOWN LÀ GÌ?](#MARKDOWN)
 
[2.Tạo tiêu đề](#Tạo tiêu đề)

[3.Định dạng chữ](#Định dạng chữ)
  
[4.Xuống dòng](#Xuống dòng)

[5.Tạo danh sách](#Tạo danh sách)

[6.Tạo liên kết](#Tạo liên kết)

[7.Tạo hình ảnh](#Tạo hình ảnh)

[8.Bảng](#Bảng)

[9.Trích dẫn, bo chữ](#9.Trích dẫn, bo chữ)


<a name="MARKDOWN">  
**1.MARKDOWN**  
  <li> Markdown là ngôn ngữ đánh dấu văn bản thô được tạo ra bởi John Gruber.
  <li> Markdown sử dụng cú pháp khá đơn giản và dễ hiểu để đánh dấu văn bản, văn bản được viết bằng Markdown sẽ có thể được chuyển đổi sang HTML và ngược lại.
  <li> Markdown thường được dùng để:  
         + Viết các tập tin README, viết wiki cho các dự án nguồn mở đặt trên Github  
         + Dùng để viết sách, phần lớn sách, truyện đều có kết cấu (về mặt format) đơn giản  
         + Dùng để viết blog, tin tức  
         + Sáng tạo ngôn ngữ markdown thành Hekyll( kết hợp Markdown và impress.js),....  
         
  <a name="Tạo tiêu đề">    
 **2.Tạo tiêu đề**  
   
   ># Tiêu đề 1 (h1)  
   ## Tiêu đề 2 (h2)  
   ### Tiêu đề 3 (h3)  
    ...  
   ###### Tiêu đề 6 (h6)  
   
 <a name="Định dạng chữ">  
 **3. Định dạng chữ**  
 <li> *In nghiêng*: `*kí tự cần in nghiêng*`  
 <li> **In đậm**: `*kí tự cần in đậm*`  
 <li> ~~gạch ngang~~: `*kí tự cần gạch ngang*`  
 
 <a name="Xuống dòng">  
 **4.Xuống dòng**  
 Sử dụng 2 khoảng trắng: `<space><space>` để xuống dòng.  
 
 <a name="Tạo danh sách">  
 **5.Tạo danh sách**  
   >1. danh sách 1  
    2. danh sách 2  
    3. danh sách 3  
    
  <a name="Tạo liên kết">  
  **6.Tạo liên kết**  
  - Có thể chèn Link trực tiếp:  
  https://github.com/  
  Hoặc thu ngắn đường dẫn của link:  `[tên](tên đường link)`
    ví dụ:`[Github](https://github.com)`  
    kết quả là: [Github](https://github.com)

<a name="Tạo hình ảnh">  
**7.Tạo hình ảnh**  
Cú pháp: `![mô tả](link)`  
![](http://tophinhanhdep.net/wp-content/uploads/2016/07/hinh-anh-trai-tim-1.gif)

<a name="Bảng"> 
**8.Bảng**  
Bạn có thể sử dụng cú pháp sau để tạo bảng:  
~~~
| Cột 1 Hàng 1 | Cột 2 | Cột 3| Cột 4 |
|--------------|-------|------|-------|
| Hàng 2 | 2 x 1 | 2 x 2 | 2 x 3 | 2 x 4 |
| Hàng 3 | 3 x 1 | 3 x 2 | 3 x 3 | 3 x 4 |
| Hàng 4 | 4 x 1 | 4 x 2 | 4 x 3 | 4 x 4 |
~~~

| Cột 1 Hàng 1 | Cột 2 | Cột 3| Cột 4 |
|--------------|-------|------|-------|
| Hàng 2 | 2 x 1 | 2 x 2 | 2 x 3 | 2 x 4 |
| Hàng 3 | 3 x 1 | 3 x 2 | 3 x 3 | 3 x 4 |
| Hàng 4 | 4 x 1 | 4 x 2 | 4 x 3 | 4 x 4 |

<a name="Trích dẫn, bo chữ">  
**9.Trích dẫn, bo chữ**  
+Để bo cậu bạn cần sử dụng cú pháp nhập câu cần bo vào giữa 2 dấu ``  
ví dụ: `câu cần bo`  
+Để làm nổi bật một đoạn cần sử dụng cú pháp:  
```sh
Mây lang thang,
  mây mang nhiều tâm sự...
Gió rì rào,
  gió cứ đến rồi đi
```

