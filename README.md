Công cụ Quick-Check-Proxy là một công cụ Windows tiện ích cho việc kiểm tra, xác minh và xử lý proxy một cách nhanh chóng và hiệu quả. Công cụ được xây dựng với giao diện đồ họa thân thiện, cung cấp nhiều chức năng như:

Kiểm tra Proxy Live: Cho phép kiểm tra nhanh các proxy có thể kết nối và các proxy không thể kết nối.
Thông Tin Proxy Chi Tiết: Hiển thị thông tin chi tiết về địa chỉ IP, quốc gia, múi giờ, thành phố, nhà cung cấp dịch vụ và thời gian phản hồi.
Bỏ Pass Proxy: Chuyển đổi danh sách proxy có định dạng IP:PORT:USER:PASS thành danh sách chỉ chứa địa chỉ IP và port, giúp dễ dàng xử lý khi cần loại bỏ thông tin xác thực.

Hỗ trợ nhiều định dạng proxy: Công cụ hỗ trợ nhiều định dạng khác nhau, bao gồm:

IP:PORT:USER:PASS
IP:PORT
http://user:pass@ip:port
http://ip:port@user:pass
user:pass@ip:port
ip:port@user:pass
user:pass:ip:port

Ngoài ra, tool còn có các tính năng bổ trợ như xuất kết quả ra file Excel hoặc file text (.txt) và cài đặt chứng chỉ Root CA (cho việc cấu hình proxy thông qua MITM).

🔧 Cách Sử Dụng
1. Download & Cài Đặt
Tải file thực thi (.exe)
File .exe của công cụ đã được biên dịch sẵn và bạn có thể tải về từ phần Releases của GitHub.

Chạy ứng dụng:
Nhấn đúp vào file .exe để khởi động ứng dụng. (Chỉ hỗ trợ trên Windows)

2. Các Tính Năng Chính
Kiểm tra Proxy trực tiếp:

Nhập danh sách proxy theo định dạng đã chọn (ví dụ: IP:PORT:USER:PASS).

Nhấn nút "Kiểm Tra" để bắt đầu quá trình kiểm tra.

Proxy được xác minh sẽ được hiển thị trong danh sách "Proxy Live" (màu xanh) và các proxy không hợp lệ trong danh sách "Proxy Die" (màu đỏ).

Thông Tin Proxy Chi Tiết:

Sử dụng tab "Thông Tin Proxy" để xem các thông tin chi tiết về các proxy đã kiểm tra.

Bạn có thể sắp xếp, tìm kiếm và xuất danh sách proxy ra file Excel.

Bỏ Pass Proxy:

Nhập danh sách proxy có định dạng đầy đủ, sau đó công cụ sẽ chuyển đổi và hiển thị danh sách proxy không có thông tin xác thực.

Tính năng này rất hữu ích khi bạn cần chia sẻ danh sách proxy mà không tiết lộ thông tin nhạy cảm.

Cài Đặt Root CA (nếu cần):

Nếu bạn sử dụng proxy với chứng chỉ (MITM) để kiểm tra HTTPS, hãy đảm bảo cài đặt chứng chỉ Root CA đã được cung cấp.

Nhấn nút "Cài Đặt Root CA" để thêm chứng chỉ vào cửa hàng chứng chỉ của Windows.

Lưu ý: Windows sẽ hiển thị cảnh báo bảo mật; hãy xác nhận để tiếp tục.

3. Xuất Kết Quả
Bạn có thể xuất danh sách proxy live hoặc proxy die ra file .txt bằng cách sử dụng các nút “Xuất Proxy Live” và “Xuất Proxy Die”.

Ngoài ra, ở tab "Thông Tin Proxy", bạn có thể xuất toàn bộ danh sách proxy ra file Excel (.xlsx).
