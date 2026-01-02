# Tool-Dop-Video

Tool đớp video từ youtube - Tool nhận thông báo tức thời từ kênh youtube - Tool nhận thông báo và tải video từ youtube

📥 **Tải về:** [Tool đớp video v1.1](https://github.com/Alex020997/Tool-Dop-Video/releases/download/v1.1/tool_tiktok_v1.1.zip) 
hoặc [Xem tất cả Releases](https://github.com/Alex020997/Tool-Dop-Video/releases)

Vui lòng liên hệ telegram [![Telegram](https://img.shields.io/badge/Telegram-@tdanghocode-blue?style=for-the-badge&logo=telegram)](https://t.me/tdanghocode)

<img width="748" height="779" alt="image" src="https://github.com/user-attachments/assets/9132280a-a36e-487d-afa1-c3ef95c82a02" />


---

## 1️⃣ LẤY NGROK TOKEN

**Bước 1: Đăng ký tài khoản Ngrok (miễn phí)**

→ Truy cập: https://dashboard.ngrok.com/get-started/setup/windows  
→ Copy token sau chữ `ngrok config add-authtoken` ví dụ: `2abc123def456ghi789jkl012mno345pq_6R7S8T9U0V1W2X3Y4Z5A6B7C8D`

**Bước 2: Nhập Token vào Tool**

→ Mở Tool → Nhập token vào ô "Ngrok Token"  
→ Click "Save Token Ngrok"

---

## 2️⃣ LẤY TELEGRAM BOT TOKEN VÀ TELEGRAM ID

**BỎ QUA BƯỚC NÀY NẾU KO MUỐN NHẬN THÔNG BÁO TRÊN TELEGRAM**

### 📱 TẠO TELEGRAM BOT (Lấy Bot Token):

**Bước 1: Tìm BotFather trên Telegram**

→ Mở Telegram → Tìm kiếm: @BotFather  
→ Click vào kết quả đầu tiên

**Bước 2: Tạo bot mới**

→ Gửi lệnh: `/newbot`  
→ Đặt tên cho bot (ví dụ: "My Video Notifier")  
→ Đặt username cho bot (phải kết thúc bằng "bot", ví dụ: "my_video_notifier_bot")  
→ Đảm bảo đã gửi lệnh `/start` cho bot của bạn

**Bước 3: Lấy Bot Token**

→ BotFather sẽ trả về token (dạng: `1234567890:ABCdefGHIjklMNOpqrsTUVwxyz`)  
→ Copy token này → Đây là Telegram Bot Token

### 🆔 LẤY TELEGRAM ID CỦA BẠN:

**Bước 1: Dùng Bot @userinfobot**

→ Mở Telegram → Tìm kiếm: @userinfobot  
→ Click "Start" hoặc gửi lệnh `/start`  
→ Bot sẽ trả về ID của bạn (số dài, ví dụ: `123456789`)

**Bước 2: Nhập vào Tool**

→ Mở Tool → Nhập "Telegram Token" (Bot Token từ BotFather)  
→ Nhập "Telegram ID" (ID của bạn từ các bot trên)  
→ Click "Save token telegram"

---

## 3️⃣ CÁCH SỬ DỤNG TOOL

**Bước 1: Cấu hình**

✓ Nhập Ngrok Token (bắt buộc)  
✓ Nhập Telegram Token và ID (tùy chọn)

**Bước 2: Thêm kênh YouTube cần theo dõi**

→ Nhập Channel ID vào ô "Channel ID/URL"  
→ Ví dụ Channel ID: `UCiz19rgacvujLo0-FH8u5xA`  
→ Click "Đăng ký"  
→ Nếu nhiều channel thì cách nhau bởi dấu `,`

**📱 CÁCH LẤY CHANNEL ID CỦA KÊNH YOUTUBE:**

→ Truy cập: https://timeskip.io/tools/youtube-channel-id-finder  
→ Dán URL kênh → Click "FIND Channel ID"  
→ Click COPY ID dán vào tool

**Bước 3: Bắt đầu theo dõi**

→ Click nút "Bắt Đầu Theo Dõi" (màu xanh)  
→ Tool sẽ đăng ký webhook và bắt đầu theo dõi các kênh  
→ Khi có video mới, bạn sẽ nhận thông báo ở chương trình và telegram

**Bước 4: Tùy chọn - Tải video tự động**

→ Tick vào "Tải video" nếu muốn tự động tải video mới  
→ Chọn độ phân giải: 1080p, 720p, 480p, hoặc 360p  
→ Video sẽ được tải vào thư mục "downloads" trong thư mục chứa tool

**Bước 5: Dừng theo dõi**

→ Click nút "Dừng" (màu đỏ) để dừng theo dõi  
→ Hoặc chọn kênh cần hủy, sau đó click "Hủy Đăng Ký Kênh Nhận Thông Báo" để xóa kênh khỏi danh sách

---

## 💡 MẸO VÀ LƯU Ý:

✓ Ngrok Token chỉ cần nhập 1 lần, tool sẽ lưu vào config.txt  
✓ Telegram Token và ID chỉ cần nhập 1 lần, tool sẽ lưu vào config.txt  
✓ Danh sách kênh sẽ được lưu tự động, không cần thêm lại mỗi lần mở tool  
✓ Mã máy (Hardware ID) hiển thị màu vàng - click để copy khi cần active license  
✓ Tool sẽ tự động cập nhật yt-dlp.exe khi click "Cập nhật yt-dlp"  
✓ Đảm bảo máy tính có kết nối Internet để tool hoạt động  
✓ Tool cần chạy liên tục để nhận thông báo video mới

---

## 📞 HỖ TRỢ:

Nếu gặp vấn đề:

→ Log trong cửa sổ tool để xem chi tiết lỗi  
→ Đảm bảo đã cấu hình đúng các token và ID  
→ Kiểm tra kết nối Internet và firewall  
→ Vui lòng liên hệ telegram @tdanghocode

