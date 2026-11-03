# Cùng nhau làm thiện — Ngôi Chùa An Lạc

Trải nghiệm đi chùa trên trình duyệt với không gian 2D và 2.5D. Bạn có thể chọn pháp danh, trang phục, dạo quanh sân chùa và tham gia các hoạt động như thiền định, thắp hương, lạy Phật và phóng sinh.

![Ảnh chụp trải nghiệm Ngôi Chùa An Lạc](img/Screenshot%202026-11-03%20211740.png)

## Bắt đầu

Mở file [main.html](main.html) bằng trình duyệt hiện đại. Không cần cài đặt thư viện hay chạy bước build.

Cần kết nối Internet để tải Tailwind CSS, biểu tượng Font Awesome và Google Fonts từ CDN.

## Cách trải nghiệm

1. Nhập tên hoặc pháp danh, chọn trang phục rồi nhấn **Bước Vào Điện Phật**.
2. Di chuyển bằng **WASD**, **phím mũi tên**, hoặc **chạm / nhấp chuột** vào vị trí muốn đến.
3. Chọn góc nhìn **Chính Diện**, **2.5D** hoặc **Top-down** ở góc trên màn hình.
4. Dùng các nút phía dưới để **Thiền Định**, **Thắp Hương**, **Lạy Phật**, **Gõ Mõ**, **Thỉnh Chuông**, tương tác với **Thùng Công Đức** và **Phóng Sinh**.
5. Nhập lời khấn nguyện rồi nhấn **Enter** hoặc **Gửi** để hiển thị lời nói của nhân vật.

Nút hình nốt nhạc dùng để bật hoặc tắt nhạc thiền.

## Tính năng

- Nhân vật có tên và ba lựa chọn trang phục.
- Không gian chùa được vẽ bằng Canvas, hỗ trợ ba góc nhìn.
- Các hoạt động tương tác cùng điểm công đức trong trò chơi.
- Phóng sinh cá và hiệu ứng trong sân chùa.
- Âm thanh mõ, chuông và nhạc thiền được tạo bằng Web Audio API.
- Các nhân vật viếng chùa mô phỏng.

Trải nghiệm chạy phía trình duyệt, chưa có máy chủ, chế độ nhiều người chơi hay lưu tiến trình. Tải lại trang sẽ bắt đầu lại; điểm công đức chỉ thuộc trải nghiệm mô phỏng.

## Cấu trúc

```text
.
├── main.html   # Giao diện, CSS và JavaScript của trải nghiệm
└── README.md   # Giới thiệu và hướng dẫn sử dụng
```

Để chỉnh sửa, mở `main.html` trong trình soạn thảo, lưu thay đổi rồi tải lại trang trên trình duyệt.
