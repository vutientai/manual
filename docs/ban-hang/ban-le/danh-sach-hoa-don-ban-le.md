# Danh sách hóa đơn bán lẻ

Danh sách hóa đơn bán lẻ để quản lý toàn bộ hóa đơn bán lẻ tại cửa hàng.
Bạn có thể tìm kiếm hóa đơn bán lẻ theo nhiều tiêu chí: Cửa hàng, ngày tạo, thu ngân lập phiếu...

Để xem danh sách hóa đơn bán lẻ, bạn vào menu Bán hàng, hoặc truy cập [tại đây.](https://new.nhanh.vn/pos/bill/index)

Giao diện làm việc của module Danh sách hóa đơn bán lẻ như sau:

# 1.Bộ lọc

## Bộ lọc cơ bản:

Doanh nghiệp: Chọn doanh nghiệp muốn lọc danh sách hóa đơn bán lẻ.

ID: Lọc theo ID của hóa đơn bán lẻ. Mỗi hóa đơn bán lẻ được hệ thống gắn cho 1 ID riêng.

Sản phẩm: Lọc theo tên sản phẩm

Từ ngày - Đến ngày: Lọc theo khoảng thời gian lập hóa đơn bán lẻ

Người tạo: Lọc theo tên lập hóa đơn bán lẻ.

## Bộ lọc nâng cao:

Kho: Chọn cửa hàng/kho hàng muốn lọc.

IMEI: Lọc theo số IMEI (áp dụng cho sản phẩm có IMEI).

ID đơn hàng: Lọc theo ID đơn đặt hàng từ module [Đơn hàng.](https://new.nhanh.vn/order/manage/index)

Đặc điểm: Lọc theo đặc điểm của hóa đơn bán lẻ: Có/Không có chiết khấu, Có quẹt thẻ, Có thanh toán công nợ...

Số lần in hóa đơn: Cho phép lọc những hóa đơn bán lẻ có số lượng in bao nhiêu (lớn hơn, nhỏ hơn, hoặc bằng một giá trị nào đó).

Hạn thanh toán: Lọc theo khoảng thời gian hẹn thanh toán của hóa đơn bán lẻ.

Khách: Lọc theo tên khách mua hàng.

Ghi chú: Lọc theo những mô tả, ghi chú thêm về hóa đơn bán lẻ.

Nhân viên bán hàng: Lọc theo tên nhân viên phụ trách bán hàng,tư vẫn về sản phẩm trong hóa đơn bán lẻ.

## Nút ![]()

Cho phép người dùng xuất Excel danh sách hóa đơn bán lẻ (trang hiện tại hoặc toàn bộ các danh sách, dạng đơn giản hoặc dạng đầy đủ thông tin) và Tạo phiếu trả hàng.

## Danh sách bảng hoá đơn bán lẻ:
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/ban-hang/img/danh-sach-hoa-don-ban-le.png)

Hiển thị thông tin các hóa đơn bán lẻ của doanh nghiệp. Bảng này gồm các cột:

Ngày: Hiển thị ngày lập hóa đơn bán lẻ và tên người lập hóa đơn (cũng chính là tên Nhân viên thu ngân)

ID: Hiển thị ID của hóa đơn bán lẻ. Khi click vào ID, hệ thống chuyển sang trang chi tiết hóa đơn bán lẻ đó.

Kiểu: Hiển thị kiểu xuất bán (Xuất [L]), và tên cửa hàng lập hóa đơn bán lẻ.

Khách hàng: Hiển thị tên và số điện thoại của khách hàng trên hóa đơn bán lẻ.

Sản phẩm: Hiển thị tên và mã sản phẩm trong hóa đơn bán lẻ.

Giá: Hiển thị giá bán của từng đơn vị sản phẩm trong hóa đơn bán lẻ (chưa gồm VAT), và số tiền chiết khấu của hóa đơn (số màu đỏ).

SL: Hiển thị số lượng sản phẩm bán trong hóa đơn bán lẻ.

VAT: Hiển thị giá VAT phải trả của từng đơn vị sản phẩm trong hóa đơn bán lẻ. Giá sau VAT được tính = Giá đơn vị sản phẩm * % VAT * số lượng đơn vị sản phẩm trong hóa đơn bán lẻ.

Chiết khấu: Hiển thị số tiền và số % chiết khấu cho hóa đơn bán lẻ (số % màu đỏ).

Tổng tiền: Tổng tiền khách hàng phải thanh toán (sau khi đã trừ chiết khấu, tiền tích điểm,..).

Thanh toán: Hiển thi số tiền khách thanh toán và hình thức thanh toán (tiền mặt, chuyển khoản, quẹt thẻ, trả góp...).

Mô tả: Hiển thị thông tin khuyến mãi, tặng điểm tích lũy, Vpoint; mô tả thêm của nhân viên bán hàng/ nhân viên thu ngân.

In: Cho phép người dùng click vào biểu tượng ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/ban-hang/img/may-in.png)  để in hóa đơn bán lẻ.

Ở hàng cuối cùng của bảng là hàng tính tổng số lượng sản phẩm, tổng VAT, tổng tiền chiết khấu, tổng tiền phải thu, tổng tiền thanh toán và tổng số tiền còn nợ của tất cả các hóa đơn bán lẻ của doanh nghiệp.

## * Trang chi tiết hoá đơn bán lẻ:
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/ban-hang/img/chi-tiet-hoa-don-ban-le.png)

Thông tin chi tiết của hóa đơn bán lẻ gồm các phần : Thông tin hóa đơn, Lịch sử sửa đổi, Hóa đơn trả hàng. Click vào từng tab để xem thêm.

Thông tin hóa đơn: Hiển thị các thông tin chi tiết về hóa đơn trả hàng đó, tại tab này, bạn có thể thực hiện một số thao tác sau:

In hóa đơn:![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/ban-hang/img/in-hd.png?token=AQBB63O7L2DKRBTX5LBZYNK66GDWC)

Sửa hoá đơn: ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/ban-hang/img/sua-hd.png?token=AQBB63O544RYTA2UHP7PTDC66GD2A)

Thao tác:

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/ban-hang/img/sua-hoa-don-ban-lee.png?token=AQBB63PGZINTKOWCMEZTQV266GFJW) cho phép bạn tạo hóa đơn trả hàng cho hóa đơn bán lẻ đó, xóa phiếu Xuất nhập kho tương ứng với hóa đơn bán lẻ, và Hạch toán lại kế toán cho hóa đơn bán lẻ này.
Lịch sử sửa đơn: Tab này hiển thị thông tin về những lần sửa hóa đơn bán lẻ.
Hóa đơn trả hàng: Tab này hiển thị các hóa đơn trả hàng tương ứng với hóa đơn bán lẻ này.


Mọi thắc mắc trong quá trình sử dụng, xin quý khách vui lòng:

- Click vào  Hướng dẫn sử dụng để xem bài hướng dẫn trên màn hình mà doanh nghiệp đang thao tác

- Click vào  Hỗ trợ trực tuyến để chat trực tiếp với bộ phận hỗ trợ online của Nhanh.vn

- Tham khảo các video hướng dẫn sử dụng phần mềm Nhanh.vn [Tại đây.](https://www.youtube.com/playlist?list=PLzIvXH9OQtJPsxnm78xzUmhmMhgJEFl5q)
