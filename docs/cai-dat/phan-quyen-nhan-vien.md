# Phân quyền nhân viên
Cài đặt Phân quyền nhân viên cho phép bạn thêm mới, sửa, xóa tài khoản của nhân viên, phân các quyền cho nhân viên sao cho phù hợp với công việc của từng người, từng bộ phận.

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/cai-dat/img/phan-quye-nhan-vien-1.PNG)

---

## Thêm mới / sửa / xóa tài khoản nhân viên
Thêm mới tài khoản nhân viên [tại đây](https://new.nhanh.vn/store/user/index)

Video hướng dẫn thêm tài khoản nhân viên:

{% youtube src="https://www.youtube.com/watch?v=FY8pd0SQGXc" %}{% endyoutube %}

Khi thêm mới tài khoản nhân viên, bạn cần chọn đúng nhóm quyền phù hợp với nhân viên đó. Phần mềm bán hàng Nhanh.vn có các nhóm quyền sau:
Nhóm quyền |Ý nghĩa
------------ | -------------
Giám đốc | Là nhóm quyền cao nhất, phụ trách tất cả các vấn đề của hệ thống, thường sẽ không bị giới hạn quyền gì của doanh nghiệp (trừ khi tài khoản đó được phân quyền riêng)
Nhân viên kế toán | Nhóm quyền gần với giám đốc nhất, gần như quản lý hết mọi vấn đề, phụ trách chính về các vấn đề liên quan tới kế toán
Nhân viên cửa hàng trưởng | Nhóm quyền quản lý các nội dung có trong cửa hàng: danh sách bán lẻ, danh sách bán buôn, danh sách đơn hàng, danh sách phiếu XNK. Khi phân quyền này cần phải gắn kho/cửa hàng
Nhân viên thu ngân | Nhóm quyền chủ yếu phụ trách thêm/trả phiếu bán lẻ, bán buôn, đơn hàng của doanh nghiệp
Nhân viên bán hàng | Nhân viên phụ trách chăm sóc, tư vấn cho khách hàng để khuyến khích họ mua sản phẩm mà doanh nghiệp bán ra
Chăm sóc khách hàng | Phụ trách xác nhận và xử lý đơn hàng online, xử lý các nghiệp vụ có thể liên quan tới việc tặng tiền, tặng điểm khách hàng, tặng quà nhân ngày sinh nhật
Trưởng nhóm chăm sóc khách hàng | Là cấp quản lý của nhân viên Chăm sóc khách hàng, để điều phối các hoạt động của CSKH, và xác nhận lại các đơn hàng mà Chăm sóc khách hàng chưa xử lý xong
Nhân viên kho | Nhân viên phụ trách việc nhập, chuyển kho
Nhân viên vận chuyển | Nhân viên phụ trách về chuyển đơn hàng online cho khách đặt mua (thường dùng cho doanh nghiệp có đội vận chuyển riêng, không dùng dịch vụ của các hãng vận chuyển)
Nhân viên nhập liệu| Nhân viên phụ trách việc nhập các thông tin sản phẩm, danh mục, tin tức lên website
Nhân viên thu mua |Là nhân viên phụ trách một số sản phẩm nhất định, làm việc với nhà cung cấp để nhập/trả các sản phẩm mình phụ trách
Nhà cung cấp | Quyền gắn cho các tài khoản nhà cung cấp, cho phép họ xem được các thông tin liên quan tới sản phẩm của họ bán cho doanh nghiệp
Nhân viên kiểm soát viên/nhân viên đối soát viên | Quyền dùng để kiểm soát các vấn đề nội bộ trong quá trình kinh doanh của doanh nghiệp
## Phân quyền nhóm nhân viên
Nhanh.vn có các nhóm quyền phù hợp với từng bộ phận của doanh nghiệp. Tuy nhiên doanh nghiệp cũng có thể thêm/bớt các quyền trong nhóm quyền đó, bằng cách tích vào các quyền trong tab Phân quyền nhóm nhân viên.

Lưu ý, bạn có thể tìm kiếm tính năng thông qua thanh tìm kiếm, click vào biểu tượng ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/cai-dat/img/phan-quyen-nhan-vien-2.PNG) để hiển thị thanh công cụ tìm kiếm và click vào ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/cai-dat/img/phan-quyen-nhan-vien-3.PNG) để thu gọn thanh công cụ tìm kiếm 

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/cai-dat/img/phan-quyen-nhan-vien-4.PNG)
## Phân quyền nhân viên
Dùng trong trường hợp bạn muốn phân quyền riêng cho nhân viên, quy trình thao tác như sau: nhập Tên/user của nhân viên => So sánh với nhóm quyền/nhân viên khác (không bắt buộc) ==> click Lọc ==> Tích chọn các quyền muốn phân cho nhân viên ==> click Lưu.

Lưu ý:

- Bạn click vào nút ![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/cai-dat/img/phan-quyen-nhan-vien-5.PNG) để hệ thống load lại các quyền mặc định của nhân viên trước khi tích thêm/bớt quyền cho nhân viên đó
- Để chuyển về phân quyền mặc định, doanh nghiệp click vào nút Chuyển về phân quyền mặc định.
## Phân quyền xem dữ liệu
Cho phép doanh nghiệp giới hạn nhân viên chỉ xem được một số dữ liệu do chính nhân viên đó tạo, mà không xem được của nhân viên khác.

Tình huống sử dụng thực tế:

- Doanh nghiệp có 2 nhân viên thu ngân, nên chỉ muốn nhân viên A nhìn thấy hóa đơn mình tạo, không cho phép thấy hóa đơn do nhân viên B tạo, hoặc chỉ nhìn thấy hóa đơn do mình tạo trong vòng 1 tuần trở lại đây.
- Không cho phép nhân viên này nhìn thấy khách hàng của nhân viên khác

Một số lưu ý tại cài đặt này:
1. Giới hạn quyền xem Danh sách hóa đơn bán lẻ:
- Tích chọn cài đặt này: Tất cả nhân viên chỉ được nhìn thấy các hóa đơn do nhân viên đó tạo.
- Cài đặt nâng cao: Giới hạn theo từng nhóm quyền và số ngày xem (nếu có). Lưu ý khi sử dụng cài đặt nâng cao, bạn cần bỏ tích chọn ở cài đặt chung.

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/cai-dat/img/phan-quyen-nhan-vien-6.PNG)

2. Giới hạn quyền xem Danh sách đơn hàng
- Tích chọn cài đặt này: Giới hạn tất cả nhân viên chỉ được nhìn thấy các đơn hàng do nhân viên đó tạo.
- Cài đặt nâng cao: Giới hạn theo từng nhóm quyền và số ngày xem (nếu có). Lưu ý khi sử dụng cài đặt nâng cao, bạn cần bỏ tích chọn ở cài đặt chung.
- Chi tiết đơn hàng: Cho phép nhân viên xem được chi tiết đơn hàng do nhân viên khác tạo khi có cài đặt giới hạn xem danh sách đơn hàng theo nhân viên tạo.

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/cai-dat/img/phan-quyen-nhan-vien-7.PNG)

3. Giới hạn quyền xem Chi tiết sản phẩm
- Tích chọn cài đặt này: Giới hạn nhân viên chỉ xem được tồn kho trong kho mình quản lý ở trang chi tiết sản phẩm.
- Cài đặt nâng cao: Giới hạn theo từng nhóm quyền và số ngày xem (nếu có). Lưu ý khi sử dụng cài đặt nâng cao, bạn cần bỏ tích chọn ở cài đặt chung.
