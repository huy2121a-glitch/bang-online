# BANG! Online — website tiếng Việt

Dự án web nhiều người chơi chạy bằng Node.js, Express và Socket.IO. Thiết kế dựa trên các ý tưởng kiến trúc trong tutorial của repository `honzaHlavnicka/Bang`: tách định nghĩa trò chơi, luật, lá bài, nhân vật và vai trò; tuy nhiên đây là ứng dụng web độc lập, không phải plugin Java cho engine của repository đó.

## Chạy trên máy

- Cài Node.js 20 trở lên.
- Mở terminal trong thư mục dự án.
- Chạy `npm install`
- Chạy `npm start`
- Mở `http://localhost:3000`

## Deploy miễn phí

1. Tải toàn bộ nội dung thư mục này lên repository GitHub.
2. Tạo Web Service trên Render và kết nối repository.
3. Build command: `npm install`
4. Start command: `npm start`
5. Chọn gói Free và deploy.

Có endpoint kiểm tra sức khỏe `/health`.

## Có trong bản này

- Phòng trực tuyến và mã phòng 6 ký tự.
- 4–7 người chơi, thêm bot.
- Vai trò bí mật và 16 nhân vật cơ bản.
- Bộ bài, vũ khí/trang bị, khoảng cách, lượt chơi, sát thương, phản ứng né đòn và cẩm nang tiếng Việt.
- Giao diện responsive.

## Trạng thái

Đây là bản thử nghiệm có thể triển khai, chưa được chứng nhận tương thích hoàn toàn với mọi luật chính thức của BANG!. Một số tương tác cần tiếp tục hoàn thiện, đặc biệt lựa chọn lá bỏ thủ công, lựa chọn bài tại CHỢ CHUNG, phục hồi kết nối và kiểm thử đầy đủ mọi tổ hợp kỹ năng/bài. Phòng hiện lưu trong RAM; khởi động lại máy chủ sẽ làm mất phòng.

## Ghi chú về tài liệu tham khảo

Tutorial gốc hướng dẫn viết plugin Java cho một engine riêng (Maven, `HerniPlugin`, `HerniPravidla`, các lớp lá bài). Website này áp dụng cách tổ chức ý tưởng tương tự nhưng dùng Node.js/Socket.IO để chạy trực tiếp trên trình duyệt; không dùng SDK Java của engine đó.
