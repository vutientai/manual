# Cài đặt gửi email
## 1. Các tình huống hỗ trợ gửi Email:
Bạn có thể cài đặt để hệ thống gửi email cho khách hàng khi:

- Gửi email thông báo về các chương trình khuyến mại mới của cửa hàng

- Sau khi thu ngân lập hóa đơn bán lẻ: Gửi email cảm ơn khách vừa mua hàng, thông báo tổng tiền tích lũy, điểm tích lũy, tặng Coupon cho lần sau...

- Sau khi khách đặt hàng trên website: Gửi email xác nhận thông tin đơn hàng.

- Khách đăng ký tài khoản: Gửi email cho khách đăng ký tài khoản mới trên website

- Khách đăng ký Newsletter: Gửi email (có thể kèm coupon) cho khách đăng ký nhận thông tin giảm giá, hàng mới về... trên website

- CSKH cập nhật trạng thái đơn hàng: Gửi email thông báo hàng đã chuẩn bị xong, đã gửi vận chuyển, các trạng thái thay đổi trong quá trình xử lý đơn hàng, tạm thời hết hàng...

- CSKH hủy đơn hàng: Gửi email khi CSKH có hành động hủy đơn hàng.

## 2. Lưu ý khi email gửi đi dùng Gmail:
Có 2 cách để sử dụng tài khoản Gmail cho việc gửi email:

- Sử dụng luôn tài khoản Google bình thường của bạn: cách này bạn sẽ cần tắt chế độ "Xác minh 2 bước". Nhanh.vn khuyến cáo bạn không nên dùng cách này.

- Tạo mật khẩu ứng dụng cho tài khoản Google của bạn, dùng mật khẩu này thay thế cho mất khẩu chính, chú ý bạn không nên đặt mật khẩu này giống với mật khẩu chính của tài khoản Google (khuyến cáo bạn nên dùng cách này).

* Bước 1: truy cập vào link sau: https://myaccount.google.com/security

* Bước 2: Tạo mật khẩu ứng dụng

Chú ý: Để sử dụng "Mật khẩu ứng dụng", Bạn cần bật "Xác minh 2 bước" cho tài khoản Google của bạn.

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/cai-dat/img/cai-dat-email-1.PNG)

Chọn ứng dụng và chọn thiết bị bạn muốn tạo mật khẩu ứng dụng

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/cai-dat/img/cai-dat-email-2.PNG)

Copy mật khẩu ứng dụng đã tạo

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/cai-dat/img/cai-dat-email-3.PNG)

* Bước 3: Copy mật khẩu điền vào phần mật khẩu khi cài đặt gửi mail
## 3. Quy trình cài đặt email như sau:
### Bước 1: Cài đặt tài khoản gửi email
- Nếu bạn không cài đặt tài khoản, hệ thống sẽ gửi đi bằng tài khoản mặc định là no-reply@nhanh.vn



![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/cai-dat/img/cai-dat-gui-email-4.PNG)



- Bạn chọn Email host, nhập email và mật khẩu, tên của email gửi đi, email nhận phản hồi, sau đó click Lưu. Chú ý:
Tên của Email gửi đi: chỉ để hiển thị thay thế cho địa chỉ email trong trường hợp có cài đặt, (mặc định không điền thì hệ thống sẽ lấy tên email gửi đi bằng địa chỉ email gửi đi hoặc bằng tên của cửa hàng), khác với tiêu đề email.
Email nhận phản hồi: Khi khách hàng phản hồi lại email thì sẽ gửi về địa chỉ email này thay vì gửi về địa chỉ email gửi đi (Thường dùng trong tình huống: VD gửi đi từ noreply@tinhkhoi.online nhưng khi khách phản hồi thì sẽ về mail cskh@tinhkhoi.online)
- Sau khi lưu, bạn click vào Gửi email kiểm tra cài đặt tài khoản email gửi đi để xem email đã hoạt động chưa.
### Bước 2: Cài đặt hành động gửi email (gửi ngay khi có hành động):
Bạn chọn hành động muốn gửi email, nhập tiêu đề và nội dung email muốn gửi tới cho khách hàng. Lưu ý:

- Email chỉ được gửi sau khi bạn click Lưu cài đặt hành động

- Bạn click vào Danh sách từ khóa để lựa chọn từ khóa cho vào nội dung email. Danh sách các từ khóa:

_ID_HOA_DON_: Id của hóa đơn trên hệ thống

_DIEN_THOAI_: Điện thoại khách đặt hàng

_TEN_KHACH_DAT_HANG_: Tên khách đặt hàng

_DANH_SACH_SAN_PHAM_: Danh sách sản phẩm

_CHI_TIET_HOA_DON_: Chi tiết hóa đơn



![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/cai-dat/img/cai-dat-gui-email-5.PNG)



Sau khi cài đặt email thành công, mỗi lần phát sinh hành động mua hàng tại quầy, đặt hàng online..., khách hàng sẽ nhận được email có dạng như sau:

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/cai-dat/img/cai-dat-email-6.jpg)

Thông tin chi tiết email:

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/cai-dat/img/cai-dat-email-7.jpg)

## 4. Gửi Email định kỳ (Gửi theo lịch hẹn định giờ):
- Gửi email trước ngày sinh nhật khách hàng: Thường dùng để gửi mã giảm giá, hoặc chính sách giảm giá cho khách mua vào ngày sinh nhật.

- Gửi email vào ngày sinh nhật khách hàng: Thường dùng để gửi lời chúc, gửi mã giảm giá chúc mừng sinh nhật khách hàng.

- Gửi email sau khi khách mua hóa đơn, sản phẩm bao nhiêu ngày: Thường dùng để gửi nhắc khách quay lại mua hàng.

VD: Sau khi khách mua 1 bình gas, sau 30 ngày sẽ Gửi Email nhắc khách cần thay gas.




