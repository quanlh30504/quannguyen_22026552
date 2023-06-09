# KING DARKNESS AND PIGS


## Giới thiệu
- Chào mọi người mình là **Nguyễn Văn Quân (22026552)** sinh viên K67 trường **Đại học Công Nghệ**, đây là dự án đầu tiên của mình nên vẫn còn nhiều thiếu sót mong mọi người góp ý và ủng hộ để các bản update sau được hoàn chỉnh hơn.

## Cốt truyện
- King Darkness and Pigs là 1 tựa game lấy ý tưởng từ trò chơi ***Celeste***, một trò chơi có thể loại platformer (trò chơi đánh nhau và di chuyển trên nền tảng) được phát triển và xuất bản bởi Maddy Makes Games vào năm 2018.

- Cốt chuyện của King Darkness and Pigs xoay quanh nhanh vật chính là chúa tể bóng tối **Maloch** sau 1 lần đi chơi với công chúa **Peony** đã không may để bọn lợn xanh chiếm mất lâu đài, game là 1 hành trình của vua maloch đấu tranh đánh bại kẻ thù để dành lại ngôi vị của mình


![image](./data/textures/Background/Game.png)


## Cài đặt
Các bạn có thể cài đặt game theo video hướng dẫn của mình:
>**Cách 1**:
>- Các bạn có thể tải source của mình và chạy trên trình biên dịch codeblock ( chú ý cài thư viện SDL2 cho codeblock)
>- Dưới đây là video hướng dẫn:

[![Video name](./data/textures/Background/Youtube.png)](https://www.youtube.com/watch?v=TEEGek_0P74&t=200s)
>Mình đã để sẵn mục SDL trong source nên các bản khi cài SDL cho codeblock có thể dẫn tới luôn thư mục chứa các thư viện SDL2 đó

>**Cách 2**:
>- *Bước 1*: Tải game và giải nén ([Link game](https://drive.google.com/file/d/1f7w7b9X7QBBkWBmQXBOpC2ALQ450ZOOr/view?usp=share_link))
>- *Bước 2*: Mở file .exe và trải nghiệm game

![ảnh minh họa](./data/textures/Background/setupgame.png) 


## Hướng dẫn chơi
![Cách chơi](./data/textures/Background/Tutorial.png)

>**Một số tính năng game** 
>- Esc: để dừng trò chơi
>- Enter: để return về menu game
>- Game có sử dụng 1 thuật toán để chuyển đổi số xu nhận được sang % thứ hạng:
```cpp
string conver(int num){
     num = num * 100;
     int cc = num / 83;
     std::string res = std::to_string(cc);
     cc = num % 83; cc *= 10; cc = cc/ 83;
     res += "." + std::to_string(cc) + "%";
     return res;
}
```
![anh](data/textures/Background/wingame.png)

## Các kĩ thuật lập trình được sử dụng
- Mảng
- Con trỏ/ Giải phóng bộ nhớ
- Class
- Đồ họa
- Bắt sự kiện bàn phím, chuột
- Bắt va chạm per-pixel theo từng hoạt ảnh, chuyển động
- Stringstream
- Xử lí nhảy/ rơi theo vật lí
- Cắm cờ
- Chia file theo đối tượng
- Đọc, ghi file
## Update sắp tới
- Menu thêm phần tùy trỉnh âm thanh
- Thêm các kĩ năng mới cho nhân vật
- Làm thanh máu cho nhân vật
- Update thêm 1 số quái và các vật phẩm sau khi tiêu diệt quái
- Update thêm các map mới có độ khó cao hơn

## Đóng góp

- Nếu bạn muốn đóng góp cho game, vui lòng truy cập trang GitHub của mình và tạo một pull request. Mình rất hoan nghênh mọi đóng góp từ cộng đồng.

## Liên hệ 

- Nếu bạn có bất kỳ câu hỏi hoặc góp ý nào, vui lòng liên hệ với mình qua email ***quanlh3052004@gmail.com*** . Mình rất vui lòng được trò chuyện với bạn.

## Tham khảo
- Page LazyFoo: [Lazyfoo](https://lazyfoo.net/tutorials/SDL/)
- Youtuber: [Madsycode](https://www.youtube.com/@Madsycode/playlists)
- Youtuber: [Phát Triển Phần Mềm 123A-Z](https://www.youtube.com/@PhatTrienPhanMem123AZ)
- [Geeksforgeeks.org](https://www.geeksforgeeks.org/)
- [Stackoverflow.com](https://stackoverflow.com/)
- [itch.io](https://itch.io/)

## Lời kết
- Tuy chưa có nhiều kinh nghiệm trong việc thiết kế game, song mình vẫn đầu tư tâm huyết và trí lực của mình vào việc hoàn thiện thiết kế để mọi người có được trải nghiệm tuyệt vời nhất, cảm ơn mọi người đã dành thời gian quý báu dụng sản phẩm! 