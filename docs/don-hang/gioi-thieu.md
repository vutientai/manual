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

**Bạn có thể tham khảo video hướng dẫn trạng thái sản phẩm và đơn hàng [Tại đây](https://www.youtube.com/watch?v=-CJPWYW2Az0)**
### **2. Biên bản bàn giao**
Khi có nhiều đơn hàng cần gửi cho hãng vận chuyển trong ngày, bạn nên dùng biên bản bàn giao để:
- Cho nhiều đơn hàng vào biên bản và bắn biên bản sang hãng vận chuyển cùng 1 thời điểm, giúp cho việc điều tin nhanh và tập trung hơn.
- In bảng tổng hợp số lượng sản phẩm để nhặt hàng và đóng gói nhanh hơn.
- In biên bản cho bưu tá kí xác nhận đã nhận tổng số đơn và bảng kê chi tiết, mà không cần kí nhận từng phiếu gửi giúp tiết kiệm giấy in, hạn chế thất thoát.

### **3. Tour chuyển hàng**
Dùng cho doanh nghiệp nào tự có đội ngũ vận chuyển riêng, tự quản lý các đơn hàng gửi cho khách.

### **4. Đối soát**
Nhanh.vn sẽ đối soát các đơn hàng gửi qua hãng vận chuyển để gửi tiền cho doanh nghiệp.

## **II. Nghiệp vụ tạo, xử lý đơn hàng**
### **1. Khách hàng đặt đơn hàng**
- Đặt hàng trên website: khách đặt hàng và điền thông tin ở trang thanh toán trên các website mà Nhanh.vn cung cấp, các trang kết nối api với Nhanh.vn, các đơn đặt trên Shopee/Lazada -> đơn hàng sẽ chuyển về [Danh sách đơn hàng](https://nhanh.vn/order/manage/index).
- Khách gọi điện thoại đến doanh nghiệp, đặt hàng trên trang fanpage Facebook của doanh nghiệp...
  - Doanh nghiệp vào tạo đơn hàng trong hệ thống, điền đấy đủ các thông tin khách hàng, báo cho khách về phí vận chuyển (nếu có).
  - Doanh nghiệp import đơn hàng để tạo nhiều đơn hàng cùng lúc lên hệ thống.
- Trường hợp không có doanh nghiệp trên Nhanh.vn, người dùng vẫn có thể đăng nhập để [tạo đơn hàng lẻ](https://nhanh.vn/shipping/shipment/add) miễn phí mà Nhanh.vn cung cấp.

### **2. Chăm sóc, xác nhận lại đơn hàng**
Doanh nghiệp gọi điện lại cho khách để xác nhận lại đơn hàng -> Đơn hàng sẽ chuyển sang các trạng thái: Đang xác nhận, Đã xác nhận.

### **3. In và Đóng gói sản phẩm**

### **4. Tạo biên bản bàn giao**
Tập hợp các đơn hàng cùng 1 hãng vận chuyển -> tạo biên bản bàn giao, thêm các đơn hàng vào biên bản bàn giao -> Click gửi sang hãng vận chuyển -> In biên bản bàn giao giao cho hãng vận chuyển đến lấy hàng.

### **5. Gửi đơn hàng sang hãng vận chuyển**
- Khi kích gửi sang hãng vận chuyển thì trạng thái tự động chuyển sang là Chờ đi nhận -> Hãng khi nào nhận được hàng sẽ chuyển trạng thái sang Đang chuyển để ghi nhận là đang chuyển hàng cho khách.
- Doanh nghiệp tự vận chuyển hàng sang cho khách hàng -> doanh nghiệp đổi trạng thái sang hãng vận chuyển.

### **6. Hãng vận chuyển thay đổi trạng thái -> Cập nhật lịch trình về Nhanh.vn:**

### **7. Nhận lại hàng Đang chuyển hoàn và chuyển trạng thái đơn hàng về Đã chuyển hoàn**

### **8. Chuyển trạng thái Thành công**
- Do hãng vận chuyển đổi khi đơn hàng gửi sang hãng vận chuyển, hàng được chuyển hành công.

- Doanh nghiệp tự đổi trạng thái đơn hàng khi đã chuyển hàng thành công cho khách.

### **9. Đối soát đơn hàng**
Chỉ đối soát các đơn hàng gửi cho hãng vận chuyển, thao tác này thì Nhanh.vn sẽ thực hiện -> sau khi đã đối soát xong sẽ chuyển tiền hàng về cho doanh nghiệp, cá nhân qua các tài khoản đã đăng ký trên Nhanh.vn.

### **10. Tạo phiếu thu ghi nhận tiền thanh toán**
Với doanh nghiệp dùng kế toán thì sẽ tự tạo phiếu thu bằng tay để ghi nhận tiền hàng nhận được do doanh nghiệp thu hoặc do nhanh.vn gửi cho doanh nghiệp. Gắn ID chứng từ theo phiếu XNK [G] được tạo ra khi đơn hàng thành công, để lấy được ID chứng từ này: cách 1 lọc ID đơn hàng ở danh sách phiếu XNK; cách 2 vào trang chi tiết đơn hàng -> kích vào ngày nhận, sẽ trỏ đến phiếu XNK [G] đã tạo.

**Lưu ý:** Quy trình xử lý đơn hàng hiện tại trên nhanh là:
1. Doanh nghiệp tạo đơn.
2. Gửi đơn sang hãng vận chuyển.
3. Khi hãng vận chuyển thay đổi trạng thái -> Cập nhật lịch trình về Nhanh.
4. Khi đơn hàng giao Thành công hoặc Chuyển hoàn về, hãng vận chuyển đối soát với Nhanh.

Nhanh sẽ check các thông tin về khối lượng | tiền cần thu | giá cước (xem có phí vượt cân, có đúng với giá cước theo hợp đồng không) => Khớp các giá trị trên sẽ chốt đối soát với hãng vận chuyển, sau đó Nhanh sẽ chuyển lại tiền này cho doanh nghiệp.

Khi sử dụng vận chuyển trên Nhanh thì các bước 2,3,4 trên là do Nhanh làm, còn với doanh nghiệp Tự vận chuyển thì sẽ tự làm các bước đổi trạng thái, đối soát, chốt tiền.
