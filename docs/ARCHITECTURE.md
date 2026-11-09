# Kiến trúc

Tài liệu tham khảo: https://github.com/honzaHlavnicka/Bang/blob/master/docs/tutorial/VlastniHra.md

Tutorial mô tả cách engine gốc chia trách nhiệm giữa plugin trò chơi, lớp luật, lá bài, nhân vật và vai trò. Bản web độc lập này tương ứng ở mức khái niệm:

- `server.js`: trạng thái phòng, xác thực hành động, lượt chơi, hiệu ứng và đồng bộ Socket.IO.
- `public/index.html`: giao diện, thao tác người chơi và hiển thị luật/cẩm nang.
- `package.json`: phụ thuộc và lệnh chạy.
- `render.yaml`: cấu hình triển khai Render.

Đây không phải bản chuyển đổi trực tiếp từ plugin Java. Những quy tắc chưa được cài đặt hoặc chưa được kiểm thử sẽ không được coi là tương thích chính thức.
