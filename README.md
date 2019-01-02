**Tóm lược**
- Những nhóm kiến thức/kĩ năng mong muốn các bạn đạt được sau khóa thực tập này nhằm mục đích hướng các bạn trở thành một Kĩ sư CNTT ở mảng lập trình Hệ thống và Cơ sở dữ liệu (System & Database) sử dụng công nghệ nòng cốt PHP và MySQL.
- Các nhóm kiến thức được liệt kê bao gồm cả phần cơ bản và phần nâng cao. Nếu cố gắng có thể nắm trọn và áp dụng tốt trong vòng 6 tháng tới 1 năm đối với các bạn đã có kiến thức nền tảng.
- Các Milestone là các mốc các bạn cần đạt được và báo cáo kết quả với người hướng dẫn.
- Việc sử dụng các công cụ làm việc là hoàn toàn tự do theo lựa chọn cá nhân. Tuyệt đối **không** sử dụng các phần mềm được bẻ khóa.

#### 1. Các mốc báo cáo Kĩ năng/Kiến thức đã tiếp thu
#####Milestone 1. Sau ngày bắt đầu thực tập 1 tuần
- Tìm hiểu và thành thạo các công cụ làm việc (Phần 3. và 4. trong tài liệu này)
- Quyết định chọn dự án để thực hiện và trình bày kế hoạch thực hiện
- Thực hiện các tìm hiểu ban đầu về yêu cầu và công nghệ sử dụng trong dự án. Cài đặt thử một vài case đơn giản nếu cần.

#####Milestone 2. Sau ngày bắt đầu thực tập 2 tuần
- Trình bày lược đồ dữ liệu về mặt vật lý và cài đặt dữ liệu
- Trình bày các tìm hiểu chi tiết về công nghệ sử dụng trong dự án.

#####Milestone 3. Sau ngày bắt đầu thực tập 3 tuần
- Báo cáo tiến độ thực hiện cài đặt dự án thực tế
- Các khó khăn gặp phải chưa có hướng giải quyết

#####Milestone 4. Sau ngày bắt đầu thực tập 5 tuần
- Demo ứng dụng MVP
- Các khó khăn gặp phải chưa có hướng giải quyết

#####Milestone 5. Trước khi kết thúc khóa thực tập 3 ngày.
- Báo cáo hoàn thành dự án: Cài đặt, kiểm thử, triển khai.
- Những tính năng không thể thực hiện được
- Những tính năng sẽ mở rộng/xây mới trong tương lai để đưa sản phẩm ra thương mại hóa.


#####1.1. Kiến thức về ngôn ngữ lập trình PHP
**Nhóm kiến thức cơ bản về ngôn ngữ**
- xyz...

**Nhóm kiến thức về làm việc Client - Server**
- REQUEST, POST, GET
- FILES
- SESSION, COOKIE
- SERVER

**Nhóm kiến thức về OOP**
- Các kiến thức cơ bản
- Namespace - Use - Autoload

**Nhóm kiến thức về dữ liệu**
- Làm việc với MySQL
- Làm việc với Redis

**Open source và việc sử dụng các repo open source**
- Công cụ composer

#####1.2. Kiến thức về kĩ thuật lập trình và kiến trúc hệ thống
**Cơ bản về MVC**
**PHP Framework tốt**
- [Laravel](https://laravel.com)
- [Lumen](https://lumen.laravel.com)

**Microservice và Sessionless**
- Cơ bản về RESTful và Web Services
- Triệu gọi từ xa (RPC)
- Token và [JWT](https://jwt.io)

**Message Broker và Queue**
- [RabbitMQ](https://www.rabbitmq.com)

**Realtime**
- Websocket
- [Nodejs](https://nodejs.org)
- [Sailjs](https://sailsjs.com)

#####1.3. Kiến thức về hệ quản trị CSDL MySQL
**Nhóm kiến thức cơ bản**
- abc...

**Các ràng buộc**
- Ràng buộc trên field
- Ràng buộc giữa các table
- Ràng buộc khác

**Kiến thức nâng cao khác**
- Trigger
- Stored Proceduce
- View
- ...

**Thao tác với hệ quản trị CSDL**
- Người dùng và phân quyền
- Backup và Restore

#####1.4. Các kiến thức bổ trợ khác
- xyz...

####2. Dự án
- Chọn một trong số các dự án sau để thực hiện

**Dự án 1**: Ứng dụng chat ChatNao
- Độ khó: cao 
- Công nghệ sử dụng: PHP - MySQL cho phân hệ backend, Websocket cho phân hệ chat, WebRTC cho phân hệ cuộc gọi video (Video Call)
- Mô tả: Ứng dụng cho phép chat trực tiếp hoặc thực hiện cuộc gọi Video Call giống Zalo, Viber

**Dự án 2**: Ứng dụng PhotoTag
- Độ khó: cao
- Công nghệ sử dụng: PHP - MySQL co phân hệ backend, RabbitMQ cho xử lý hàng đợi, TensorFlow cho xử lý đọc hình ảnh
- Mô tả: Ứng dụng tiếp nhận đầu vào là hàng loạt các ảnh chụp (số lượng có thể lên tới hàng trăm hình ảnh mỗi giây). Sử dụng thuật toán máy học có sẵn (cài đặt dùng TensorFlow) để trích xuất thông tin từ các hình ảnh này và lưu vào CSDL.

**Dự án 3**: Ứng dụng MedicalID
- Độ khó: trung bình
- Công nghệ sử dụng: PHP - MySQL cho cả 2 phân hệ Front-end và Back-end
- Mô tả: Ứng dụng như một cuốn sổ lưu toàn bộ các thông tin Y Khoa của một người. Cho phép người dùng dễ dàng nhập liệu, chỉnh sửa và quản lý các thông tin Y Khoa của mình.

#####2.1. Requirements

#####2.2. Product & Delivery

####3. Quá trình thực hiện

#####3.1. Lập kế hoạch

#####3.2. Thiết kế dữ liệu

#####3.3. Thiết lập môi trường làm việc
- Tạo board trên Trello và add các thành viên liên quan
- Tạo repository trên Gitlab
- Tạo group trên Telegram và add các thành viên liên quan
- Thiết lập webhook để đẩy notification từ Giblab vào Telegram

#####3.4. Cài đặt
- ...

#####3.5. Kiểm thử
- Viết Unit Test
- Tìm hiểu về Automation Testing

#####3.6. Triển khai
- **Level1**. Triển khai lên server bằng cách thủ công
- **Level2**. Thiết lập Auto Deploy trên server

#####3.7. Tìm hiểu về DevOpt
- Cài đặt và vận hành DevOpt cho project sử dụng các công cụ của Gitlab

####4. Tài liệu và tài nguyên liên quan
#####4.1. Các công cụ làm việc
#####Công cụ viết mã
- [Eclipse](https://www.eclipse.org) 
- [Vscode](https://code.visualstudio.com/)

#####Công cụ làm việc với CSDL MySQL
- [MySQL Workbench](https://www.mysql.com/products/workbench)

#####Công cụ làm việc với source-control
- [Gitlab](https://gitlab.com) 
- [Github](https://github.com)
- [Plugin egit của Eclipse](https://www.eclipse.org/egit)
- [SourceTree](https://www.sourcetreeapp.com)

#####Công cụ truy vấn, gỡ lỗi
- [Postman](https://www.getpostman.com)
- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools)

#####Công cụ phối hợp làm việc, giao tiếp nhóm
- [Telegram](https://telegram.org)
- [Trello](https://trello.com)

#####4.2. Các tài liệu tham khảo
- ...
