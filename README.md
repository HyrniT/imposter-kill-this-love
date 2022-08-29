# Imposter kill This Love
Construct Game Engine

## I.	Giới thiệu: 
Game dựa trên hình tượng nhận vật game Among Us – game từng thống trị thế giới giữa cuối năm 2020, kết hợp với nội dung trò chơi Imposter Find Real Love và bài hát nổi tiếng Kill This Love của BlackPink. Game Imposter Kill This Love là câu chuyện viết tiếp của tựa game trên. Sau khi “Imposter” tìm được “Real Love” và trải qua thơi gian tìm hiểu thì cảm thấy mình bị lừa dối và là nô lệ của tình yêu. Mang trong mình máu lạnh của một “Imposter” thật thụ, hắn phải “kill this love”. 

Cách chơi: Dùng 4 phím mũi tên để di chuyển nhân vật. Dùng chuột để bắn “dao” tiêu diệt các nhân vật khác. Lưu ý game chỉ có mục đích giải trí và không có ý gì sâu xa hơn…Game 18+

## II.	Quy trình kỹ thuật: 

### 1.	Tổng quát:

*	Game engine: Construct 3.

*	Đồ hoạ: tự thiết kế hoàn toàn(trừ ảnh nền).

*	Âm thanh: Among Us Sound.

### 2.	Chi tiết: 

#### i.	Hình nền (Background):

*	Kích thước: 854 x 480 px (view), 1708 x 960 (layout).

*	Thiết kế: ảnh sử dụng nguồn lấy từ google hình ảnh.

#### ii.	Các đối tượng trong trong trò chơi (Objects):

##### a.	Nhân vật trò chơi (Player):
*	Kích thước: 80 x 100 px.

*	Thiết kế: sử dụng viết (3 px) để vẽ.

*	Hiệu ứng: ảnh động (2 sprites).

*	Trạng thái: di chuyển (8 hướng) và đứng yên.

*	Phương thức di chuyển: sử dụng 4 mũi tên trên bàn phím.

*	Phương thức ngắm bắn: con trỏ chuột.

*	Phương thức bắn: sử dụng chuột trái.

*	Màu sắc: xanh dương (0,0,255).

##### b.	Kẻ địch (Monster):

*	Kích thước: 80 x 100 px.

*	Thiết kế: sử dụng viết (3 px) để vẽ.

*	Hiệu ứng: ảnh động (2 sprites).

*	Trạng thái: di chuyển ngẫu nhiên (8 hướng), khi khoảng cách giữa nhân vật trò chơi và kẻ dịch dưới 200 px thì mỗi 0.1s sẽ quay 1 góc 1 độ.

*	Màu sắc: xanh hồng (225,70,225).

##### c.	Đạn (Bullet):

*	Kích thước: 50 x 24 px.

*	Thiết kế: sử dụng ô vuông pixel (2 px) để vẽ.

*	Trạng thái: di chuyển vector.

*	Phương thức hoạt động: điểm xuất phát là nhân vật trò chơi và bắn về phía con trỏ chuột bằng chuột trái, khi chạm vào kẻ địch sẽ nổ ra máu (explosion).

## III.	Hướng dẫn sử dụng: 

*	Dùng 4 phím mũi tên trên bàn phím để di chuyển nhân vật game.

*	Dùng con trỏ chuột để xác định hướng bắn.

*	Dùng chuột trái để bắn.

*	Di chuyển nhân nhân vật sao cho không chạm vào kẻ địch.

*	Cần 5 viên đạn trúng kẻ địch để có thể tiêu diệt.

*	Tốc độ kẻ địch được (+1) sau khi nhân vật game tiêu diệt 1 kẻ địch.

*	Người chơi sẽ nhận được điểm càng cao khi tiêu diệt được kẻ địch ở cự ly càng gần nhân vật trò chơi.

## IV.	Mở rộng

Các bước thực thi tạo game:

B1:	Chọn chủ đề game, nhân vật.

B2:	Xác định phương thức chơi và giao diện chính.

B3:	Chèn ảnh nền và điều chỉnh kích thước.

B4:	Thiết kế tạo hình các nhân vật và đối tượng xuất hiện trong game.

B5:	Tạo hiệu ứng ảnh động và gắn các hành vi cho đối tượng.

B6:	Trang trí, xắp xếp các đối tượng trên cùng một layout.

B7:	Lập trình các sự kiện diễn ra trong game (tạo câu lệnh điều khiển và điều kiện trong Event sheet).

B8:	Tạo thêm các layout (menu, gameover,…).

B9:	Thêm các button, hệ thống tính điểm, thời gian.

B10:	Chèn nhạc, hiệu ứng âm thanh.

## Copyright by HyrniT
