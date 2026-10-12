# Hoa Phenikaa: nhận diện hoa real-time

Web-app nhận diện **15 loài hoa** trong khuôn viên Đại học Phenikaa bằng camera điện thoại.
Mô hình **YOLO11n-cls** (1,5M tham số) chạy ngay trên trình duyệt bằng ONNX Runtime Web, khung hình không được gửi đi đâu.

**Dùng thử:** https://quanhhquanhhh.github.io/hoa-phenikaa/ → bấm *Mở camera* → đưa bông hoa vào giữa khung vuông.

Các loài: Bạch đồng nữ, Chiều tím, Dâm bụt cam, Dâm bụt đỏ, Dâm bụt hồng, Dâm bụt vàng, Hoa hồng, Huỳnh anh, Lài trâu, Mai chỉ thiên, Mía dò đỏ, Mỏ két, Thanh tú, Trang đỏ, Trang trắng.

Khi khung hình không có loài nào trong danh sách, app hiện **"Chưa nhận ra hoa"** thay vì đoán bừa.
