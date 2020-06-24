# Sản phẩm combo
## 1. Khái niệm.
- Với khía cạnh là một người mua hàng Combo là hình thức mua sắm kết hợp nhiều mặt hàng trong cùng một combo sản phẩm. Hình thức này ngày càng phổ biến khi mà bất cứ mặt hàng nào cũng có thể sử dụng combo, từ thời trang, mỹ phẩm, gia dung … cho đến các thiết bị điện tử.
- VD: Sản phẩm "Mặt nạ dưỡng da" có thể bán lẻ theo số lượng 1 chiếc hoặc có thể đóng combo "3 mặt nạ dưỡng da"
- VD: Sản phẩm "Combo bàn phím giả cơ và chuột cho game thủ" được gộp lại từ 2 sản phẩm độc lập 1 bàn phím và 1 chuột.
## 2. Mục đích và ý nghĩa.
- Tăng doanh thu trên một hóa đơn.
- Tăng số lượng các sản phẩm bán ra cho một lượt khách.
- Các nhà bán hàng có thể khéo léo lồng ghép những sản phẩm ít được khách biết đến vào trong các combo để kích cầu nhu cầu mua sắm. Bên cạnh đó, các combo cũng giúp nhà bán hàng làm nên lợi thế cạnh tranh so với đối thủ không áp dụng hình thức phục vụ này.
## 3. Quy trình tạo sản phẩm combo.
Ví dụ: Tạo combo sản phẩm CBQuần12 bao gồm:
1 Sản phẩm Quần01 giá nhập 50.000đ,  giá bán 100.000đ ( số tồn của Quần01 hiện có 10 sản phẩm )
1 Sản phẩm Quần02 giá nhập 100.000đ, giá bán 200.000đ ( số tồn của Quần02 hiện có 10 sản phẩm )
=> Giá nhập của sản phẩm CBQuần12 150.000; giá bán 300.000đ
### 3.1. Thêm mới từng sản phẩm.
Bước 1: Tương tự tạo sản phẩm thường (tham khảo tại thêm mới [từng sản phẩm]())
Bước 2: Chon loại sản phẩm combo và gắn các sản phẩm trong combo.
Chọn tab thuộc tính / Chọn loại sản phẩm là sản phẩm Combo / Điền tên sản phẩm con trong combo/ để thêm sản phẩm khác ấn nút “ + “ / Lưu

Ảnh![]()

*:warning: Lưu ý :*
- Không nhập tồn đầu cho sản phẩm combo.
- Ô "SL" bên cạnh tên sản phẩm là số lượng của sản phẩm đó có trong combo.
### 3.2. Import sản phẩm Combo từ file excel
Bước 1: Bạn có thể tạo combo sản phẩm tại menu Sản phẩm / Thêm mới/ [Import sản phẩm Combo]()
Bước 2: Tải file mẫu và điền các thông tin

:warning: **Lưu ý** : Nếu sản phẩm combo có nhiều sản phẩm con, bạn cần điền mỗi sản phẩm con trên 1 dòng (không điền lại Tên combo, Giá bán).

Ảnh![]()

Bước 3 : Tải file import lên phần mềm/Import
## 4. Tồn kho sản phẩm combo
Hệ thống lấy số tồn của sản phẩm combo dựa vào tồn kho của các sản phẩm độc lập ; tồn sản phẩm combo bằng tồn sản phẩm con nhỏ nhất / số lượng quy đổi khi thêm vào combo

Ảnh ![]()

## 5. Bán sản phẩm combo.
- Sau khi bán sản phẩm combo bạn cần làm thao tác tính lại giá vốn để  ghi nhận đúng doanh thu, lợi nhuận ( thao tác 1 lần duy nhất cho 1 combo )
- Tính lại giá vốn sản phẩm:
+ Bạn vào menu Sản phẩm, kích vào ID xem chi tiết sản phẩm cần tính lại giá vốn
+ Tại đây chọn Thao tác/Tính lại giá vốn

Ảnh ![]()

- Nếu muốn chạy lại giá vốn cho cả doanh nghiệp sau khi ấn thao tác chạy lại giá vốn của 1 sản phẩm tại ô điền đường link của trình duyệt sẽ hiển thị https://nhanh.vn/auto/product/calcavgcost?storeId=.....&ids=........&forceRun=1

Bạn cần xóa các số sau “ ids= ” đến “ &forceRun=1” . Sau đó ấn Enter phần mềm sẽ chạy lại giá vốn tất cả các sản phẩm.


Ảnh ![]()


**:warning: Lưu ý :**
- Đối với sản phẩm Combo: Sản phẩm con có trong combo phải là sản phẩm độc lập, sản phẩm con và cần nhập từ 1 sản phẩm trở lên.
Giá nhập và giá vốn của sản phẩm combo sẽ bằng giá sản phẩm con
- Khi thêm mới sản phẩm, bạn cần chọn loại là sản phẩm Combo và nhập các sản phẩm con cho Combo.
- Với loại sản phẩm combo này, hệ thống sẽ không lưu tồn kho của combo, mà dựa vào tồn kho của các sản phẩm độc lập để tính ra tồn của sản phẩm combo.
- Giá vốn của combo được tính bẳng tổng số lượng nhân với giá vốn của các sản phẩm con trong combo.
- Giá bán của combo do bạn tự quy định.
- Với tính năng Combo này, trên website có thể hỗ trợ thêm tính năng mua các sản phẩm trong cùng 1 combo
