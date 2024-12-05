# Ianit

https://www.linkedin.com/pulse/command-prompt-l%25C3%25A0-g%25C3%25AC-lanit-jsc-txenc/

Command Prompt là gì?

Command Prompt là gì?
Command Prompt viết tắt là CMD, đây là công cụ nhập lệnh để thực hiện các tác vụ trên hệ điều hành Windows. Thay vì thực hiện thủ công nhiều thao tác như thông thường, bạn chỉ việc nhập lệnh và hệ điều hành sẽ thực hiện tác vụ giúp bạn rất nhanh.

Các dòng mã CMD phổ biến hiện nay
Dưới đây là các dòng lệnh hữu ích, phổ biến nhất bạn nên biết để sử dụng:

Tasklist
Hiển thị danh sách tất cả tác vụ đang chạy, bao gồm cả các tác vụ ẩn. Một số lệnh mở rộng:

tasklist /svc: Hiển thị dịch vụ liên quan đến tác vụ.
tasklist /v: Cung cấp thông tin chi tiết.
tasklist /m: Hiển thị đường dẫn các file .dll.

System File Checker (SFC)
Công cụ kiểm tra và sửa chữa tệp hệ thống Windows. Sử dụng:

sfc /scannow: Quét và tự động thay thế tệp bị hỏng hoặc thiếu.

Systeminfo
Hiển thị thông tin hệ điều hành, phần cứng, BIOS, mạng, và cấu hình khác. Thu thập thông tin từ máy khác qua:

systeminfo /s [host_name] /u [domain]\[user_name] /p [password]

Powercfg
Quản lý năng lượng:

powercfg hibernate on/off: Bật/tắt chế độ ngủ đông.
powercfg /a: Xem trạng thái tiết kiệm năng lượng.
powercfg /devicequery s1_supported: Xem các thiết bị hỗ trợ Connected Standby.

PathPing
Kết hợp giữa Ping và Tracert, cung cấp thông tin chi tiết về đường dẫn mạng và thời gian trễ. Sử dụng:

File Compare (FC)
So sánh nội dung hai tệp văn bản. Các tùy chọn:

/b: So sánh nhị phân.
/c: Bỏ qua phân biệt chữ hoa, chữ thường.
/l: So sánh văn bản ASCII.

Driverquery
Liệt kê thông tin về driver đã cài đặt. Lệnh mở rộng:driverquery /v(Hiển thị chi tiết, bao gồm đường dẫn cài đặt)

Cipher
Xóa dữ liệu ghi đè an toàn. Ví dụ:cipher /w:c(Ghi đè dữ liệu đã xóa trên ổ C để bảo vệ thông tin)

Lưu ý khi sử dụng Command Prompt là gì?
Khi sử dụng Command Prompt (CMD), bạn cần cẩn trọng với các lệnh như xóa file (DEL), vì sai cú pháp có thể gây mất dữ liệu. Một số lệnh yêu cầu quyền quản trị, vì vậy hãy kiểm tra kỹ lệnh trước khi thực thi. Nếu lệnh có đường dẫn chứa khoảng trắng, nhớ bao quanh tên bằng dấu ngoặc kép.

Cuối cùng, nếu vì lý do nào đó mà bạn không thể truy cập vào Windows sau khi dùng CMD, đừng lo, bạn có thể thử khởi động lại máy tính ở chế độ Safe Mode để sửa lỗi. Tuy nhiên, nếu bạn không rành về các thủ thuật công nghệ, đừng ngần ngại nhờ sự giúp đỡ từ người có chuyên môn để tránh gặp phải rủi ro không đáng có.
