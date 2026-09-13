# 1. STAKEHOLDERS

Dựa trên yêu cầu của khách hàng, các stakeholder chính của **CAB System** được xác định như sau:

### 1.1. Ban giám đốc Công ty ABC

* Là bên đưa ra định hướng và kỳ vọng đối với hệ thống CAB mới.
* Mong muốn xây dựng một nền tảng đặt xe có khả năng phục vụ số lượng lớn khách hàng và tài xế.
* Quan tâm đến khả năng mở rộng hệ thống và phát triển thêm các tính năng trong tương lai.
* Có nhu cầu theo dõi các báo cáo về:

  * Số lượng chuyến.
  * Doanh thu.
  * Tỷ lệ chuyến hoàn thành.
  * Tỷ lệ hủy chuyến.
  * Hiệu quả hoạt động của tài xế.

### 1.2. Khách hàng

* Là người sử dụng CAB System để yêu cầu và sử dụng dịch vụ đặt xe.
* Có nhu cầu:

  * Đăng ký tài khoản và đăng nhập.
  * Cập nhật thông tin cá nhân.
  * Nhập điểm đón và điểm đến.
  * Lựa chọn loại xe.
  * Gửi yêu cầu đặt xe.
  * Theo dõi trạng thái chuyến đi.
  * Biết tài xế đã nhận chuyến và thời gian dự kiến tài xế đến.
  * Xem lịch sử chuyến đi.
  * Xem số tiền phải trả.
  * Thanh toán chuyến đi.
  * Đánh giá tài xế sau khi hoàn thành chuyến.
  * Nhận các thông báo liên quan đến quá trình đặt xe, thực hiện chuyến và thanh toán.

### 1.3. Tài xế

* Là người tiếp nhận và thực hiện các chuyến đi được hệ thống phân công.
* Có nhu cầu:

  * Đăng ký tài khoản hoặc được nhân viên vận hành tạo tài khoản.
  * Cập nhật hồ sơ cá nhân.
  * Cập nhật thông tin phương tiện.
  * Cập nhật trạng thái hoạt động.
  * Chuyển sang trạng thái sẵn sàng nhận chuyến.
  * Nhận thông báo về chuyến mới.
  * Chấp nhận hoặc từ chối chuyến.
  * Cập nhật trạng thái trong quá trình thực hiện chuyến.
  * Cung cấp thông tin vị trí để hỗ trợ hệ thống tìm tài xế phù hợp và dự kiến thời gian đến.

### 1.4. Nhân viên vận hành

* Là người sử dụng giao diện quản trị để theo dõi và hỗ trợ hoạt động của CAB System.
* Có nhu cầu:

  * Quản lý khách hàng.
  * Quản lý tài xế.
  * Quản lý phương tiện.
  * Quản lý chuyến đi.
  * Xem các chuyến đang diễn ra.
  * Kiểm tra trạng thái tài xế.
  * Hỗ trợ xử lý các trường hợp chuyến bị lỗi.
  * Tra cứu lịch sử giao dịch.
* Một số chức năng quản trị cần được phân quyền để hạn chế nhân viên thông thường thực hiện các thao tác nhạy cảm.

### 1.5. Nhà cung cấp dịch vụ thanh toán bên ngoài

* Là hệ thống/bên thứ ba được CAB System tích hợp để hỗ trợ thanh toán điện tử.
* CAB System sử dụng dịch vụ của nhà cung cấp thanh toán nhưng không lưu trực tiếp các thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán.
* Kết quả giao dịch thanh toán cần được CAB System tiếp nhận để thông báo cho khách hàng và xử lý trường hợp giao dịch thất bại.

### 1.6. Business Analyst

* Có trách nhiệm phân tích và làm rõ yêu cầu của CAB System với các bên liên quan.
* Cần xác định và làm rõ:

  * Phạm vi hệ thống.
  * Tác nhân.
  * Quy trình nghiệp vụ.
  * Yêu cầu chức năng.
  * Yêu cầu phi chức năng.
  * Quy tắc nghiệp vụ.
  * Các trường hợp ngoại lệ.
  * Các vấn đề chưa được khách hàng xác nhận.
* Đặc biệt cần tiếp tục làm rõ các vấn đề như cách tính cước, tiêu chí ưu tiên tài xế, thời gian phản hồi của tài xế, chính sách hủy chuyến, xử lý khi mất kết nối mạng và thời gian lưu trữ dữ liệu.

### 1.7. Nhóm phát triển

* Là bên xây dựng giải pháp CAB System dựa trên các yêu cầu đã được phân tích và làm rõ.
* Việc phát triển cần dựa trên các yêu cầu đã được xác nhận, đặc biệt đối với những vấn đề nghiệp vụ hiện vẫn chưa được khách hàng chốt.
