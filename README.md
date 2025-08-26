**Phần mềm quản lý bệnh viện
**Hướng dẫn sử dụng Ứng dụng Quản lý Bệnh viện
Đây là một ứng dụng quản lý bệnh viện đơn giản được viết bằng ngôn ngữ Java. Ứng dụng này cho phép quản lý thông tin bệnh nhân, bác sĩ và lịch khám bệnh.

**Cài đặt và chạy ứng dụng

Đảm bảo rằng bạn đã cài đặt Java Development Kit (JDK) trên máy tính của bạn.
Sao chép mã nguồn từ repository này hoặc tải xuống dưới dạng file ZIP và giải nén.
Mở Terminal hoặc Command Prompt và di chuyển đến thư mục chứa mã nguồn.
Biên dịch mã nguồn bằng cách chạy lệnh sau: javac Main.java
Chạy ứng dụng bằng lệnh: java Main

**Đăng nhập
Khi ứng dụng chạy, bạn sẽ được yêu cầu đăng nhập. Hãy sử dụng tài khoản sau để đăng nhập:

Tên đăng nhập: admin  ,  1
Mật khẩu: admin       ,  1
Vui lòng đảm bảo rằng bạn nhập đúng tên đăng nhập và mật khẩu để truy cập vào ứng dụng.

**Nhập dữ liệu vào các form
Ứng dụng cho phép bạn nhập dữ liệu vào các form để thêm, chỉnh sửa hoặc xóa thông tin bệnh nhân, bác sĩ và lịch khám bệnh. Dưới đây là hướng dẫn cho việc nhập dữ liệu cho mỗi loại form:

Bệnh nhân (Patient Form)
ID: Nhập mã bệnh nhân.
Họ và tên: Nhập họ và tên của bệnh nhân.
Ngày sinh: Nhập ngày sinh của bệnh nhân theo định dạng ngày/tháng/năm.
Giới tính: Chọn giới tính của bệnh nhân từ danh sách thả xuống.
Địa chỉ: Nhập địa chỉ của bệnh nhân.
Số điện thoại: Nhập số điện thoại liên lạc của bệnh nhân.
Tiền sử bệnh: Nhập thông tin về tiền sử bệnh của bệnh nhân.
Bác sĩ (Doctor Form)
ID: Nhập mã bác sĩ.
Họ và tên: Nhập họ và tên của bác sĩ.
Ngày sinh: Nhập ngày sinh của bác sĩ theo định dạng ngày/tháng/năm.
Giới tính: Chọn giới tính của bác sĩ từ danh sách thả xuống.
Chuyên khoa: Nhập chuyên khoa của bác sĩ.
Số điện thoại: Nhập số điện thoại liên lạc của bác sĩ.
Email: Nhập địa chỉ email của bác sĩ.
Lịch khám bệnh (Schedule Form)
ID: Nhập mã lịch khám bệnh.
Mã bệnh nhân: Nhập mã bệnh nhân.
Mã bác sĩ: Nhập mã bác sĩ.
Ngày khám: Nhập ngày khám bệnh theo định dạng ngày/tháng/năm.
Giờ khám: Nhập giờ khám bệnh theo định dạng giờ
út.
Nội dung khám: Nhập nội dung khám bệnh.
Tổng tiền: Nhập tổng chi phí khám bệnh.
Sử dụng các chức năng trong ứng dụng
Sau khi đăng nhập và nhập dữ liệu vào các form, bạn có thể sử dụng các chức năng trong ứng dụng bằng cách nhấp vào các nút tương ứng. Dưới đây là các chức năng mà bạn có thể sử dụng:

Manage Patient: Mở giao diện quản lý bệnh nhân.
Add Patient: Thêm bệnh nhân mới vào danh sách.
Delete Patient: Xóa bệnh nhân khỏi danh sách.
Edit Patient: Chỉnh sửa thông tin của bệnh nhân.
Manage Doctor: Mở giao diện quản lý bác sĩ.
Add Doctor: Thêm bác sĩ mới vào danh sách.
Delete Doctor: Xóa bác sĩ khỏi danh sách.
Edit Doctor: Chỉnh sửa thông tin của bác sĩ.
Manage Schedule: Mở giao diện quản lý lịch khám bệnh.
Add Schedule: Thêm lịch khám bệnh mới vào danh sách.
Delete Schedule: Xóa lịch khám bệnh khỏi danh sách.
Edit Schedule: Chỉnh sửa thông tin của lịch khám bệnh.