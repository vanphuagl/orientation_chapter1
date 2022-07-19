# **orientation_chapter1**

### Cơ chế hoạt động của internet
- Khi mình truy cập vào một trang web trên các thiết bị, thì thiết bị đó sẽ gửi yêu cầu thông qua đường dẫn như cáp quang, wifi đến máy chủ. Từ đó máy chủ sẽ truy xuất và trả kết quả chính xác cho thiết bị đó.

### Giải thích về protocol của HTTP/HTTPS
- HTTP là giao thức chuẩn cho internet, cho phép web client và web server có thể liên lạc và hiểu nhau.
- HTTPS là phiên bản bảo mật của HTTP, nó tích hợp thêm chứng chỉ bảo mật SSL giúp tạo kết nối được mã hóa an toàn giữa client và server.

### Cơ chế hoạt động của browser và sự khác nhau giữa các browser
- Khi người dùng nhập đường dẫn trang web vào thanh địa chỉ của browser -> browser sẽ tải xuống các tài liệu từ địa chỉ đó và hiển thị chúng trên thiết bị. Format của web chủ yếu được định dạnh HTML hay pdf
- Hiện nay có 5 trình duyệt web phổ biến gồm: Google Chorme, Firefox, Edge, Opera, Safari. Mỗi trình duyệt đều có ưu và nhược

|Trình duyệt      | Ưu điểm                 |           Nhược điểm     |
|:---------------:|:-----------------------:| :-----------------------:|
|**Google Chorme**| Đồng bộ trên mọi thiết bị, tốc độ duyệt web nhanh, có cảnh báo người dùng và ngăn chặn các trang web có nội dung không rõ ràng hoặc độc hại | Ngốn nhiều ram khi mở nhiều tab, đóng tab không có cảnh báo nên dễ mất các dữ liệu quan trọng |
|**FireFox**| Khi đóng tab sẽ có thông báo để tránh tình trạng mất dữ liệu quan trọng, ngăn chặn các trang web không rõ nguồn gốc | Cũng giống Google Chrome khi mở nhiều tab cùng lúc khiến dung lượng ram bị ngốn nghiêm trọng |
|**Edge**| Giao diện thiết kế đẹp, có tính năng Read Aloud giúp đọc mọi thứ trên trang web | Xuất hiện nhiều tin tức trong và ngoài nước gây khó chịu, công cụ tìm kiếm mặc định là Bing |
|**Opera**| Tốc độ duyệt web và tải về nhanh, cho phép đồng bộ hóa dữ liệu bằng tài khoản Opera, có chế độ tiết kiệm pin cho Laptop, Tích hợp công cụ chặn quảng cáo | Không có dịch vụ hỗ trợ khách hàng |
|**Safari**| Truy cập trang web nhanh, có thể đồng bộ và lưu trữ dữ liệu trên các thiết bị Apple, cải thiện tuổi thọ pin trên các thiết bị Apple | Chỉ tương thích với các thiết bị Apple |

### Cơ chế hoạt động của DNS và Domain
- Khi nhập tên miền vào trình duyệt trên thiết bị -> trình duyệt sẽ gửi yêu cầu tới máy chủ DNS -> DNS sẽ tìm địa chỉ IP tương ứng với tên miền đã nhập -> sau khi có địa chỉ IP, trình duyệt sẽ gửi yêu cầu tới máy chủ IP tương ứng đó nhận được yêu cầu truy cập vào 1 trang web nào đó -> dữ liệu sẽ được truyền đi thông qua cáp quang hoặc wifi đến thiết bị

### Giải thích về hosting server
- Hosting server là một máy chủ giúp lưu trữ các file và dữ liệu cần thiết để web chạy được cũng như có thể xuất bản web hoặc là ứng dụng web lên internet. Và sẽ luôn được chạy ko gián đoạn để web luôn hoạt động và có thể truy cập mọi lúc.
