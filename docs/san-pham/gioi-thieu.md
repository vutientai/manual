# Giới thiệu về sản phẩm

* Là module để quản lý thông tin sản phẩm, danh mục sản phẩm, thương hiệu của sản phẩm.
* hỗ trợ quản lý thông tin các các sản phẩm bán tại cửa hàng, bán trên website, bán trên các sàn thương mại điện tử.
* Bạn có thể dùng Nhanh.vn để quản lý sản phẩm và tồn kho tập trung tại 1 nơi, sau đó cài đặt đồng bộ số tồn đi 
nhiều kênh bán khác nhau, giúp bạn tiết kiệm thời gian không phải sử dụng nhiều hệ thống.

----

Dưới đây là các khái niệm cơ bản về sản phẩm:

## Loại sản phẩm

* sản phẩm được chia thành nhiều loại, phục vụ các mục đích quản lý khác nhau

Tên loại| Mô tả
--------|------
Sản phẩm thường|Nhanh.vn quản lý sản phẩm theo ID (do hệ thống tự sinh), tên, mã sản phẩm, mã vạch sản phẩm. Các bộ lọc sẽ dựa theo một trong các thông tin này, hệ thống cũng hỗ trợ đọc mã vạch bằng máy tít. Trong đó mã vạch sản phẩm do hệ thống tự động sinh hoặc tự doanh nghiệp điền.
Sản phẩm IMEI|Loại sản phẩm có mã IMEI, chủ yếu là các sản phẩm công nghệ: điện thoại, máy tính bảng ...
Sản phẩm dịch vụ|Loại sản phẩm này dùng để ghi nhận một dịch vụ mà doanh nghiệp cung cấp, sản phẩm này sẽ không hiện số tồn ở danh sách sản phẩm, được phép xuất âm; sản phẩm dịch vụ sẽ không kiểm kho được.
Sản phẩm cân đo|Loại sản phẩm bán tính theo cân nặng, thường dùng với các sản phẩm hoa quả, rau xanh ...
Sản phẩm combo|Loại sản phẩm kết hợp nhiều mặt hàng trong một combo sản phẩm. Ví dụ: combo "Bàn phím giả cơ và chuột cho game thủ" . Để tìm hiểu về sản phẩm Combo, bạn có thể truy cập Sản phẩm combo.
Gói sản phẩm|Loại sản phẩm bao gồm nhiều sản phẩm. Ví dụ: sản phẩm "gói quà tặng" bao gồm các sản phẩm: 1 dầu gội, 1 sữa tắm, 1 dầu xả. Để tạo được sản phẩm loại gói sản phẩm ta vào Tạo gói sản phẩm; để tách sản phẩm ra gỏi gói vào trang Bung gói sản phẩm.
Danh mục sản phẩm|Giúp doanh nghiệp nhóm các sản phẩm lại để quản lý dễ dàng hơn, đồng thời Danh mục cũng để hiển thị trên website (nếu doanh nghiệp dùng website do Nhanh.vn cung cấp). Đây là tính năng tùy chọn, doanh nghiệp có thể tạo hoặc không tạo danh mục nếu có ít sản phẩm.
Danh mục nội bộ|Một loại danh mục khác, dùng cho doanh nghiệp quản lý theo một danh mục riêng, khác với danh mục sản phẩm.
Thông tin kích thước|Chiều dài (cm), Chiều rộng (cm), Chiều cao (cm), Khối lượng cả vỏ hộp (gram) - các doanh nghiệp sử dụng đơn hàng vận chuyển có gửi sang hãng vận chuyển thì nên điền các thông tin này.
Sản phẩm cha con|Thường áp dụng với các sản phẩm thời trạng, có phân size, màu. Ví dụ: sản phẩm cha sẽ tên là Áo thun -> các sản phẩm con sẽ là Áo thun Đen - L, Áo thun Đen - M, Áo thun Trắng - L, Áo thun Trắng - XL.
Nhân viên, Người tạo|Người tạo sản phẩm này trên hệ thống.

## Các khái niệm về giá sản phẩm
Tên gọi | Mô tả
---------|------
Giá nhập, giá bán, giá bán buôn|Các loại giá của sản phẩm, khi nhập NCC hệ thống sẽ chủ động lấy theo giá nhập, bán lẻ sẽ lấy giá bán, bán buôn sẽ lấy giá buôn, không có giá bán buôn thì sẽ lấy theo giá bán lẻ.
Giá vốn|Hệ thống hỗ trợ 2 kiểu tính giá vốn: Giá vốn trung bình: Tính theo công thức ((tồn hiện tại * giá vốn hiện tại) + (số lượng nhập * giá nhập)) / (tồn hiện tại + số lượng nhập); / Giá vốn đích danh: Trường hợp sản phẩm IMEI đích danh thì sẽ lấy theo giá vốn bằng giá nhập nhà cung cấp của IMEI đó. 
Xem thêm cách tính giá vốn trên Nhanh.vn tại đây.
Giá chi nhánh|Giá sản phẩm nhảy theo chi nhánh, doanh nghiệp nếu như quản lý theo các chi nhánh và mỗi chi nhánh có 1 giá khác nhau sẽ dùng tính năng này.
VAT|VAT theo từng sản phẩm, khi điền giá bán của sản phẩm sẽ cộng thêm giá trị VAT này.

## Các khái niệm liên quan đến sản phẩm khi hiển thị trên website
Tên gọi | Mô tả
---------|------
MetaKeywords, MetaDescription, MetaTitle, Tag|Các thông tin SEO của sản phẩm trên website.
Trang chủ, Sản phẩm mới, Sản phẩm hot|Trang ưu tiên sẽ hiển thị sản phẩm trên website (tùy vào từng template).
Thứ tự trên site|Thứ tự hiển thị sản phẩm trên các trang trong website - tùy theo yêu cầu làm của từng doanh nghiệp thì mới chạy được.
Giá trị khuyến mãi, Mô tả khuyến mãi|Hiển thị thông tin khuyến mãi của sản phẩm, cái này chỉ hiển thị trên website và tùy vào từng template.
Thông tin bảo hành|Hiển thị thông tin bảo hành của sản phẩm, cái này chỉ hiển thị trên website và tùy vào từng template.
Bài viết, Mô tả|Các thông tin mô tả ngắn, giới thiệu về sản phẩm.

## Các khái niệm về tồn kho của sản phẩm
Tên gọi | Mô tả
---------|------
Tồn|Số tồn của sản phẩm trên hệ thống. Khi lọc theo cửa hàng thì sẽ có 2 trường là Tồn: số tồn của sản phẩm tại kho; Tổng tồn: số tồn của cả doanh nghiệp. Khi tồn sản phẩm <= 0 thì sản phẩm có thể hiện thị hoặc đặt hàng được trên website tùy theo người dùng cài đặt và thiết kế website.
Lỗi![](https://github.com/nhanhapi/manual/blob/master/docs/san-pham/img/sp_icon_loi.png)|Trạng thái biểu diễn số sản phẩm đang lỗi khi doanh nghiệp sử dụng tính năng nhập hàng lỗi.
Đang giao hàng|Hiển thị số lượng của sản phẩm đang có trong các đơn hàng ở trạng thái: chờ thu gom, đang chuyển, thất bại, đang chuyển hoàn.
Tồn tại cửa hàng![]()|Bằng Tồn - Số lượng sản phẩm đang giao hàng
Đang chuyển kho![]()|Hiển thị số lượng của sản phẩm đang trong quá trình chuyển kho/cửa hàng, mới chỉ duyệt nhưng chưa được xác nhận.
Tạm giữ![]()|Hiển thị số các sản phẩm đang có trong các đơn hàng ở trạng thái: mới, đang xác nhận, đã xác nhận, đang đóng gói sản phẩm.
Có thể bán![]()|Là giá trị doanh nghiệp có thể bán sản phẩm, số Có thể bán = Tồn - Lỗi - đang giao hàng - tạm giữ.
Chờ nhập hàng![]()|Chỉ có trong tab Tồn kho trang chi tiết sản phẩm, ghi nhận số lượng của sản phẩm trong phiếu yêu cầu XNK nhập Nhà cung cấp.

----
Xem thêm video giới thiệu Trạng thái tồn kho của sản phẩm:(Youtube updating)
----
## Các khái niệm về trạng thái bán của sản phẩm
Tên gọi | Mô tả
---------|------
Mới|Sản phẩm bán được trên các giao diện Bán lẻ, Bán buôn, Đơn hàng, nhưng sẽ không hiện trên website.
Đang bán|Sản phẩm bán được trên các giao diện Bán lẻ, Bán buôn, Đơn hàng, và có hiển thị trên website.
Ngừng bán|Sản phẩm không thêm được ở các giao diện Bán lẻ, Bán buôn, Đơn hàng, cũng không hiển thị được sản phẩm trên website.
Hết hàng|Sản phẩm vẫn có thể hiển thị trên website, nhưng sẽ không cho phép đặt mua nữa mà sẽ hiển thị tiêu đề là Hết hàng hoặc Ngừng kinh doanh.

