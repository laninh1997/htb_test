# after, before, font, background-images

Date: April 19, 2022
Status: CSS

- khi dùng nó có thể tạo tối đa 2 div xung quanh → để làm hiệu ứng, nhìn html đơn giản hơn, tiết kiệm thẻ, bỏ bớt thẻ thừa

- `content:’’ ;` ⇒ nội dung trống.nếu đưa icon thì đưa mã icon vào

![Untitled](after,%20before,%20font,%20background-images%209561cf8b2b954fdd970b4d4678f86b2c/Untitled.png)

- ko nhận width thì thêm `display:block;`
- transition 2 chiều: đặt 1 cái ở nó, 1 cái ở hover. bình thường đặt 1 cái ở nó thì mặc định chỗ hover tương tự.
- 1 web tối đa được dùng 3 font, quá là lỗi
- tìm font ngoài **google font oswald → chọn select this font → chọn cái ô xổ ra màu đen→ customize → chọn → embed → cop link→ dán vào file html**
- `line-height:200px;` ⇒ dãn dòng
- `background-attachment:fixed;` ⇒ dùng kèm với `bachground:url() ;` → ảnh đứng im, chỉ có khung di chuyển
    
    ![**dùng cả hover vả before**](after,%20before,%20font,%20background-images%209561cf8b2b954fdd970b4d4678f86b2c/Untitled%201.png)
    
    **dùng cả hover vả before**
    
- đến v63