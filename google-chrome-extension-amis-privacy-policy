# Chính sách quyền riêng tư cho các tiện ích AMIS

Cập nhật lần cuối: 04/11/2026
Nhà phát triển/đơn vị chịu trách nhiệm: Lê Ngọc
Email liên hệ: ngocle492@gmail.com

## 1. Phạm vi

Chính sách này áp dụng cho các tiện ích sau:

- OneAI Usage Monitor — https://chromewebstore.google.com/detail/oneai-usage-monitor/djigdmnbclhcjfihkckmgggoeicioenh?authuser=0&hl=vi
- AMIS ShortLink — https://chromewebstore.google.com/detail/amis-shortlink/cfmcdknldedmmdlgnfgbmgiajkbjippj?authuser=0&hl=vi
- AMIS Contact — https://chromewebstore.google.com/detail/amis-contact/lmgglbmomkfoemjdlnpidfgpmeaoopbf?authuser=0&hl=vi
- AMIS Calendar — https://chromewebstore.google.com/detail/amis-room-booking/cokiggpjklfkfoaeglpneiklnneeeihm?authuser=0&hl=vi

Mỗi tiện ích chỉ xử lý dữ liệu cần cho chức năng được mô tả trong mục tương ứng. Các tiện ích OneAI Usage Monitor, AMIS ShortLink và AMIS Contact dùng dữ liệu từ AMIS. Riêng AMIS Calendar còn kết nối với Google Calendar và dùng backend để xử lý xác thực và nhật ký đồng bộ.

## 2. Nguyên tắc chung

Chúng tôi chỉ dùng dữ liệu để cung cấp chức năng của tiện ích, vận hành và bảo vệ dịch vụ. Chúng tôi không bán dữ liệu người dùng, không dùng dữ liệu nhận từ Google APIs cho quảng cáo cá nhân hóa và không dùng dữ liệu đó để đánh giá khả năng tín dụng.

Các tiện ích không thu thập lịch sử duyệt web chung. Cookie AMIS chỉ được dùng để xác thực yêu cầu đến các API AMIS cần thiết cho chức năng của tiện ích.

## 3. Dữ liệu được xử lý theo từng tiện ích

### OneAI Usage Monitor

Tiện ích truy vấn AMIS OneAI để hiển thị thống kê sử dụng tính năng OneAI của nhân viên đang đăng nhập. Dữ liệu có thể gồm:

- Thống kê sử dụng tính năng do AMIS OneAI trả về, chẳng hạn loại tính năng, số lượt sử dụng và thông tin thời gian nếu có.
- Thông tin nhận diện nhân viên gắn với thống kê, nếu AMIS trả về thông tin đó.
- Cookie phiên AMIS cần để xác thực yêu cầu.

Dữ liệu được dùng để hiển thị thống kê cho người dùng. Tiện ích không gửi dữ liệu thống kê đến backend của nhà phát triển hoặc dịch vụ bên thứ ba khác.

### AMIS ShortLink

Tiện ích truy vấn danh sách liên kết rút gọn do nhân viên đang đăng nhập tạo trên AMIS Mily. Dữ liệu có thể gồm:

- Địa chỉ liên kết rút gọn và địa chỉ đích.
- Tiêu đề, trạng thái, ngày tạo hoặc thông tin liên quan khác nếu AMIS Mily trả về.
- Thông tin nhận diện người tạo nếu AMIS Mily trả về.
- Cookie phiên AMIS cần để xác thực yêu cầu.

Dữ liệu được dùng để hiển thị và tra cứu các liên kết của người dùng. Tiện ích không gửi danh sách liên kết đến backend của nhà phát triển hoặc dịch vụ bên thứ ba khác.

### AMIS Contact

Tiện ích truy vấn AMIS Danh bạ để tìm và hiển thị thông tin liên hệ mà tài khoản đang đăng nhập được phép xem. Dữ liệu có thể gồm các trường do AMIS trả về, chẳng hạn:

- Tên, chức danh, phòng ban hoặc đơn vị.
- Email công việc và số điện thoại công việc, nếu có.
- Các thông tin liên hệ khác được AMIS Danh bạ cung cấp.
- Cookie phiên AMIS cần để xác thực yêu cầu.

Dữ liệu được dùng để tìm kiếm và hiển thị danh bạ trong tiện ích. Tiện ích không gửi thông tin danh bạ đến backend của nhà phát triển hoặc dịch vụ bên thứ ba khác.

### AMIS Calendar

Khi người dùng kết nối tài khoản và sử dụng chức năng đồng bộ, tiện ích xử lý:

- Cookie phiên AMIS: Được đọc từ trình duyệt và gửi trực tiếp trong yêu cầu đến AMIS Calendar API để lấy lịch và sự kiện của tài khoản đang đăng nhập.
- Thông tin tài khoản Google: Mã định danh tài khoản, email và thông tin hồ sơ cơ bản nhận từ Google để xác thực và hiển thị trạng thái đăng nhập.
- Danh sách lịch Google: Tên và mã các lịch mà tài khoản có quyền ghi để người dùng chọn lịch đích.
- Thông tin sự kiện: Tiêu đề, mô tả, địa điểm hoặc phòng họp, thời gian bắt đầu và kết thúc, mã sự kiện AMIS và dữ liệu cần thiết để đối chiếu sự kiện. Tiện ích đọc các sự kiện liên quan trong lịch Google đã chọn và có thể tạo, cập nhật hoặc xóa sự kiện được liên kết với AMIS.
- Thông tin chẩn đoán: Thời gian, phiên bản và mã tiện ích, bước đồng bộ, mã lần chạy, số lượng sự kiện đã tạo/cập nhật/xóa, thông báo hoặc mã lỗi, email Google, mã người dùng AMIS và mã tenant.
- Dấu vết phiên AMIS: Mã người dùng và tenant, cùng dấu vân tay băm của mã phiên, được lưu cục bộ để nhận biết thay đổi tài khoản và hỗ trợ chẩn đoán.

Tiêu đề và nội dung sự kiện được gửi đến Google Calendar để phục vụ việc đồng bộ. Theo mã nguồn hiện tại, backend nhận thông tin xác thực và một số nhật ký chẩn đoán, không nhận nội dung tiêu đề hay mô tả sự kiện như một phần của chức năng đồng bộ.

## 4. Cách lưu trữ và thời hạn lưu

### Ba tiện ích chỉ kết nối AMIS

OneAI Usage Monitor, AMIS ShortLink và AMIS Contact xử lý dữ liệu trả về từ AMIS để hiển thị chức năng tương ứng. Theo thiết kế được mô tả, các tiện ích này không gửi dữ liệu đó đến máy chủ của nhà phát triển hoặc dịch vụ bên thứ ba khác. AMIS tiếp tục lưu dữ liệu gốc trong hệ thống AMIS theo chính sách của AMIS.

Nếu một tiện ích lưu cài đặt hoặc dữ liệu tạm trong bộ nhớ cục bộ của Chrome, dữ liệu đó ở trên thiết bị người dùng và có thể được xóa bằng cách xóa dữ liệu tiện ích hoặc gỡ cài đặt tiện ích.

### AMIS Calendar

- Phiên đăng nhập và mã lịch được chọn được lưu trong bộ nhớ cục bộ của Chrome. Token truy cập Google được giữ trong bộ nhớ của service worker khi cần sử dụng.
- Refresh token Google được mã hóa và lưu trong Firebase để duy trì kết nối.
- Backend Vercel xử lý luồng xác thực, làm mới token và tiếp nhận nhật ký đồng bộ.
- Nhật ký trên backend được giữ tối đa 30 ngày rồi được dọn dẹp.
- Nhật ký cục bộ bị giới hạn tối đa 1.000 bản ghi hoặc 1 MB. Theo mã nguồn hiện tại, bản ghi đã tải lên được dọn theo thời hạn 7 ngày khi có thao tác ghi nhật ký tiếp theo. Bản ghi chưa tải lên có thể còn lại đến khi được tải lên, bị loại do giới hạn dung lượng hoặc dữ liệu tiện ích bị xóa.
- Phiếu xác thực tạm thời trong quá trình đăng nhập hết hạn sau khoảng 10 phút.

Sự kiện đã đồng bộ nằm trong tài khoản Google Calendar của người dùng và tuân theo chính sách lưu trữ của Google.

## 5. Các bên nhận dữ liệu

Tùy tiện ích đang sử dụng, dữ liệu được gửi đến các bên sau:

- AMIS/MISA: Nhận cookie phiên và yêu cầu API cần thiết để cung cấp dữ liệu OneAI, ShortLink, Danh bạ hoặc Calendar mà tài khoản người dùng được quyền truy cập.
- Google: Với AMIS Calendar, Google xử lý đăng nhập và nhận yêu cầu đọc, tạo, cập nhật hoặc xóa sự kiện trong Google Calendar do người dùng chọn.
- Vercel: Chạy backend AMIS Calendar, xử lý luồng xác thực và nhận nhật ký đồng bộ.
- Firebase Realtime Database: Lưu refresh token Google đã mã hóa, thông tin tài khoản cần cho phiên xác thực và nhật ký đồng bộ của AMIS Calendar.
- Google Fonts: Popup AMIS Calendar hiện có tham chiếu đến Google Fonts. Khi trình duyệt tải phông chữ, Google có thể nhận dữ liệu kỹ thuật của yêu cầu kết nối.

OneAI Usage Monitor, AMIS ShortLink và AMIS Contact không kết nối với Google, Vercel, Firebase hoặc dịch vụ bên thứ ba khác theo thiết kế được mô tả ở trên.

## 6. Bảo mật và quyền truy cập

Các yêu cầu giữa tiện ích và dịch vụ trực tuyến sử dụng HTTPS. Refresh token Google được mã hóa trước khi lưu trong Firebase. Chúng tôi giới hạn quyền truy cập backend và cơ sở dữ liệu cho hoạt động vận hành cần thiết.

Chúng tôi không cho phép nhân sự đọc dữ liệu người dùng tùy ý. Việc truy cập dữ liệu cá nhân trong nhật ký chỉ được thực hiện khi có sự đồng ý cụ thể của người dùng, khi cần thiết cho mục đích bảo mật hoặc khi pháp luật yêu cầu.

## 7. Lựa chọn và yêu cầu của người dùng

Với AMIS Calendar, người dùng có thể:

- Đăng xuất trong tiện ích để xóa thông tin xác thực Google đã lưu trên backend và gửi yêu cầu thu hồi token đến Google.
- Thu hồi quyền truy cập của tiện ích từ phần cài đặt bảo mật của Tài khoản Google.
- Yêu cầu truy cập hoặc xóa dữ liệu bằng cách gửi email đến ngocle492@gmail.com.

Đăng xuất không xóa các sự kiện đã đồng bộ vào Google Calendar. Nhật ký chẩn đoán còn lại được xử lý theo thời hạn lưu ở mục 4.

Với ba tiện ích chỉ kết nối AMIS, người dùng có thể đăng xuất khỏi AMIS để kết thúc phiên. Dữ liệu gốc trong AMIS được quản lý theo công cụ và chính sách của AMIS.

## 8. Google API và Limited Use

Thông tin nhận được từ Google APIs chỉ được dùng để cung cấp chức năng của AMIS Calendar đã mô tả trong chính sách này. Thông tin đó không được bán, dùng cho quảng cáo cá nhân hóa hoặc chuyển cho bên thứ ba không cần thiết để cung cấp chức năng này.

The use of information received from Google APIs will adhere to the Chrome Web Store User Data Policy, including the Limited Use requirements.

Chính sách Limited Use của Chrome Web Store (https://developer.chrome.com/docs/webstore/program-policies/limited-use)

## 9. Thay đổi chính sách

Nếu cách một tiện ích xử lý dữ liệu thay đổi, chúng tôi sẽ cập nhật chính sách này và ghi ngày cập nhật mới ở đầu trang.

## 10. Liên hệ

Nhà phát triển/đơn vị chịu trách nhiệm: Lê Ngọc
Email: ngocle492@gmail.com
