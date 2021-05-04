Em chào thầy cô ạ. Em tên là Lê Huy Hải Anh học lớp k65J ạ.

Nói qua một chút về game thì nó sẽ là một game rắn săn mồi với logic bình thường như bao game rắn khác. Vì em chưa quen hoàn toàn với việc sử dụng SDL nên
nghĩ ra game mới sẽ tương đối khó khăn và phức tạp nên em quyết định sẽ làm một game có sẵn và tùy biến

Game sẽ có những tính năng sau:
- Giao diện đồ họa
- Game logic: sẽ giống như game rắn bình thường, rắn chạy trong 1 khung vuông kích cỡ 577x577 có tường bao quanh. Rắn tìm kiếm và ăn thức ăn để tăng độ
dài lên, trò chơi sẽ kết thúc nếu rắn đâm vào tường hoặc tự cắn vào thân mình
-Có màn hình hiển thị khi game kết thúc hoặc khi đạt điểm chiến thắng
-Thuật toán cơ bản, dùng vector để lưu giữ tọa độ của thân rắn.

Hướng làm:
- Tạo ra các đối tượng: bề mặt(render background,score board,wall,..: những đối tượng không di chuyển), rắn, thức ăn.
- Tọa độ hóa các đối tượng là rắn và thức ăn sao cho chúng có tọa độ hay đổi,
- Mỗi khí tọa độ của đầu rắn trùng với tọa độ thức ăn thì độ dài mảng sẽ tăng

-Về điểm thì em tự nhận được 6 đến 6.5 ạ.

-Em có tham khảo video trên youtube https://www.youtube.com/watch?v=AaGK-fj-BAM và lazyfoo và thư viện chữ 
