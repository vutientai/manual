# Quản lý Đơn hàng
**Đơn hàng** là nơi quản lý tất cả các đơn hàng online, đơn đặt hàng trước, đơn cần vận chuyển (đơn gửi hãng vận chuyển, cần thu hộ tiền COD).

**Đơn hàng có thể được tạo từ các nguồn sau:** 

- Nhân viên tự tạo từng đơn hàng 
- Đơn hàng đồng bộ từ phần mềm quản lý fanpage https://vpage.nhanh.vn
- Đơn hàng do người mua đặt hàng từ website bán hàng của doanh nghiệp do Nhanh.vn cung cấp
- Đơn hàng nhận từ API đồng bộ giữa Nhanh.vn với các website của khách hàng hoặc các sàn TMĐT (Lazada.vn, Shopee.vn, Tiki.vn, Sendo.vn, Vatgia.com, Adayroi.com)

**Đơn hàng khác so với Bán hàng ở chỗ:**

- Khách hàng (người mua hàng) không trực tiếp đến cửa hàng mua mà cần có một bên thứ 3 giao hàng.
- Khách hàng có thể không mua hàng và hoàn trả, do đó cần quản lý thêm "trạng thái đơn hàng"
- Khi đơn hàng mới được tạo thì hệ thống Nhanh.vn không trừ tồn kho và cũng chưa ghi nhận doanh thu. Khi nào đơn hàng thành công hệ thống thì mới trừ kho và tính doanh thu.

## **I. Các khái niệm trong Đơn hàng**
### **1. Trạng thái đơn hàng**
**Trạng thái** | **Ý nghĩa**
------------ | -------------
Mới | Trạng thái đơn hàng mới tạo
Đang xác nhận / Đã xác nhận | Trạng thái lúc gọi điện cho khách để xác nhận lại đơn hàng
Đang đóng gói sản phẩm | Trạng thái đơn hàng mới tạo
Chờ đi nhận / Đang đi nhận / Đã nhận hàng | Chờ đi nhận khi doanh nghiệp gửi sang hãng vận chuyển; Đang đi nhận, Đã nhận hàng hãng vận chuyển sẽ cập nhật trạng thái này khi đi và nhận hàng gửi từ doanh nghiệp
Đang chuyển | Hãng vận chuyển sẽ đổi sang trạng thái này hoặc doanh nghiệp tự đổi với đơn tự vận chuyển
Thất bại | Nếu hãng vận chuyển gửi hàng đến khách hàng nhưng vì một lý do nào đó khách không nhận hoặc không gửi được cho khách, hãng sẽ cập nhật về trạng thái này -> doanh nghiệp cần liên hệ lại với khách hàng để xem chuyển hàng về hay gửi lại cho khách
Đang chuyển hoàn | Khi khác hàng không nhận và doanh nghiệp xác nhận việc khách không nhận hàng, hãng sẽ cập nhật về trạng thái này và mang hàng về cho doanh nghiệp
Đã chuyển hoàn | Doanh nghiệp nhận lại hàng Đang chuyển hoàn và tự đổi sang trạng thái Đã chuyển hoàn
Thành công | Khi đơn hàng đã gửi cho khách thì hãng/doanh nghiệp cần đổi sang trạng thái thành công.

**Bạn có thể tham khảo video hướng dẫn trạng thái sản phẩm và đơn hàng [Tại đây](http://github.com)**
### **2. Biên bản bàn giao**
