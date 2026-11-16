# Thắp sáng Mùa Vọng – Gameshow Lời Chúa (Mùa Vọng năm B)

30 câu hỏi (lấy từ bộ "Vui Học Thánh Kinh – Mùa Vọng B"), 10 giây mỗi câu.
Người chơi quét mã QR, nhập tên, không cần tài khoản.

## Chạy thử trên máy tính (cùng Wi-Fi)
1. Cài Node.js 18+ (https://nodejs.org).
2. Trong thư mục này gõ: `node server.js`
3. Quản trò mở http://<IP-máy-tính>:3000/host (mật khẩu mặc định: giaoly). Dùng địa chỉ IP thay vì localhost để mã QR đúng.

## Đưa lên Render (miễn phí)
Giống bản trước: tải thư mục lên GitHub, tạo Web Service trên Render, Start Command = `node server.js`,
thêm biến môi trường HOST_PASSWORD. Quản trò vào địa chỉ-của-bạn/host.

## Gợi ý khi chơi
- Quản trò bấm một nút bất kỳ (ví dụ "BẮT ĐẦU") để trình duyệt cho phép phát âm thanh. Nối máy với loa lớn.
- Nút 🔊 góc phải để tắt/bật tiếng. Điện thoại người chơi chỉ phát tiếng ngắn khi bấm và khi có kết quả.
- Sau mỗi câu hiện top 5; cuối trò chỉ vinh danh top 3.
- Điểm: đúng được 500–1000 (càng nhanh càng cao), thêm +100/+200/+300 khi đúng liên tiếp 2/3/4 câu.
- Trả lời SAI: mất hết điểm và xuống cuối bảng xếp hạng. Không trả lời (hết giờ) thì chỉ không được điểm, không bị trừ.
- Ván đầu theo thứ tự gốc. Mỗi lần bấm "Làm lại từ đầu" hoặc "Xoá người chơi" thì thứ tự 30 câu được đảo ngẫu nhiên.
- Thứ tự đáp án A–D được xáo ngẫu nhiên mỗi lần mở máy chủ.
- Sửa câu hỏi, thời gian: đầu file server.js (biến TIME_MS hoặc TIME).
