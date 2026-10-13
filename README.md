# Hoa Phenikaa: nhận diện hoa real-time

Web-app **phát hiện (object detection) 10 loài hoa** trong khuôn viên Đại học Phenikaa bằng camera điện thoại: vẽ khung + tên loài cho từng bông hoa.
Mô hình **YOLO11n-detect** (2,6M tham số) chạy ngay trên trình duyệt bằng ONNX Runtime Web, khung hình không được gửi đi đâu.

**Dùng thử:** https://quanhhquanhhh.github.io/hoa-phenikaa/ → bấm *Mở camera* → hướng camera vào bụi hoa.

Các loài: Chiều tím, Dâm bụt đỏ, Dâm bụt vàng, Hoa hồng, Huỳnh anh, Lài trâu (Ngọc bút), Mía dò đỏ, Mỏ két, Trang đỏ, Trang vàng.

Test (563 ảnh): mAP50 = 0,838, mAP50-95 = 0,656.