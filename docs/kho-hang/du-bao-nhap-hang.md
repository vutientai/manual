# Dự báo nhập hàng

Đến đợt nhập hàng mới, bạn muốn tính toán xem nên nhập sản phẩm với số lượng bao nhiêu cho hợp lý, để kịp thời dự trữ số lượng hàng tồn, tránh tình trạng hết hàng.
Nếu tính toán bằng tay hay Excel sẽ mất rất nhiều thời gian, trong khi sử dụng tính năng Dự báo nhập hàng thì chỉ cần vài click chuột là đã có một bảng dự báo chính xác.

Tính năng này dựa trên tổng số lượng bán gần nhất, phù hợp với các sản phẩm bán liên tục trong một khoảng thời gian dài.

Để dự báo số lượng sản phẩm cần nhập, bạn truy cập lần lượt vào Kho hàng / Dự báo số lượng sản phẩm cần nhập, hoặc truy cập [tại đây](https://new.nhanh.vn/inventory/forecasting/movingaverage).

Quy trình tính toán số lượng sản phẩm cần nhập thêm:

## Bước 1: Bạn nhập thông tin vào các trường cần thiết, bao gồm:
- Doanh Nghiệp: Chọn tên Doanh Nghiệp
- Cửa hàng cần dự báo: chọn kho/cửa hàng cần tính toán số lượng sản phẩm nhập thêm
- Danh mục: bạn lựa chọn danh mục sản phẩm cần dự báo số lượng nhập thêm
- Số ngày để tính lượng bán TB/ngày: doanh nghiệp lựa chọn số ngày (trở về trước) để tính lượng bán trung bình/ngày, hoặc chọn một khoảng thời gian cụ thể (từ ngày X đến ngày Y).
- Nhập hàng bán trong mấy ngày: bạn nhập số ngày bán hàng dự tính sắp tới (thường là khoảng cách số ngày giữa 2 lần nhập hàng)
- Tồn tối thiểu của mỗi sản phẩm: nhập số tồn tối thiểu của sản phẩm mà bạn mong muốn.
- Tên sản phẩm: nếu không muốn dự báo theo danh mục sản phẩm, bạn có thể nhập tên chính xác của 1 sản phẩm cụ thể hoặc một vài chữ cái trong tên sản phẩm.

## Bước 2: Click vào Tính số lượng cần nhập. Công thức tính như sau
Số lượng bán trung bình ngày = Tổng bán trong khoảng ngày / Số ngày trong khoảng
Số lượng bán dự tính sắp tới = Số lượng bán trung bình ngày * Số ngày sắp tới
Số lượng hàng cần nhập = Số lượng bán dự tính sắp tới - Số tồn có thể bán hiện tại + Số tồn tối thiểu.

Sau khi hệ thống tính được số lượng sản phẩm doanh nghiệp cần nhập thêm, bạn có thể click nút Hành động để xuất Excel danh sách này để đề xuất nhập bổ sung, tránh tình trạng hết hàng.

Video hướng dẫn thao tác:
