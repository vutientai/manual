# Kiểm kho

Trong quá trình kinh doanh tất yếu xảy ra thất thoát, dẫn đến chênh lệch giữa số tồn kho thực tế bên ngoài và số tồn bên trong phần mềm bán hàng. Kiểm kho hàng hóa giúp bạn kiểm kê lại số lượng hàng hóa tồn kho thực tế so với số lượng tồn kho trên phần mềm, và cập nhật số lượng tồn kho thực thế lên phần mềm (bù trừ kiểm kho)

## Các loại kiểm kho
- Kiểm kho theo sản phẩm: Áp dụng khi doanh nghiệp cần kiểm đếm một (một số) mặt hàng nhất định, đã lên danh sách từ trước khi kiểm.
- Kiểm kho theo danh mục: Áp dụng khi doanh nghiệp cần kiểm đếm một hoặc một số mặt hàng trong cùng một danh mục sản phẩm. Khi bạn chọn loại kiểm kho này, hệ thống sẽ chỉ ghi nhận những sản phẩm trong danh mục đã chọn (nếu gõ tên sản phẩm hoặc dùng đầu đọc mã vạch sản phẩm ngoài danh mục thì hệ thống sẽ không ghi nhận)
- Kiểm kho toàn bộ: Áp dụng khi doanh nghiệp cần kiểm toàn bộ kho hàng/ cửa hàng. Trường hợp này, các sản phẩm không nằm trong danh sách kiểm sẽ được mặc định là không tồn (không còn) trong kho, số lượng kiểm kho bằng 0.

## Quy trình kiểm kho gồm 3 bước như sau

1. Thêm phiếu kiểm kho

2. Thêm sản phẩm cần kiểm kho vào phiếu

3. Tìm sản phẩm thiếu ( Với loại kiểm kho theo danh mục/ toàn bộ)

4. Bù trừ kiểm kho.

## I. Thêm phiếu kiểm kho

Bạn truy cập lần lượt vào Kho hàng / Kiểm kho / Thêm phiếu kiểm kho hoặc truy cập tại đây.

Điền đầy đủ thông tin kiểm kho vào giao diện như sau:

Click nút Tiếp tục để chuyển sang màn hình Thêm sản phẩm vào phiếu kiểm kho.

## II. Thêm sản phẩm kiểm kho

Bạn nhập sản phẩm cần kiểm kho vào trường Sản phẩm. Để nhập sản phẩm kiểm kho, có 02 cách như sau:

## 1.1. Nhập thủ công trực tiếp bằng tay vào hệ thống:

- Hệ thống cho phép nhập bằng Mã vạch sản phẩm/Mã sản phẩm/Tên sản phẩm.
- Sau khi hệ thống load tự động sản phẩm vào Danh sách sản phẩm kiểm kho, bạn cần cập nhật số lượng hàng tồn kho thực tế vào cột Số kiểm kho.
- Nếu doanh nghiệp dùng quét bằng mã vạch sản phẩm: Dùng đầu đọc mã vạch để quét mã vạch trên mỗi sản phẩm. Mỗi sản phẩm được tít qua, số lượng tồn kho thực tế sẽ được cập nhật luôn tại cột Số kiểm kho.
- Đối với loại kiểm kho theo danh mục, khi bạn nhập một sản phẩm không nằm trong danh mục đã chọn thì hệ thống sẽ báo Sản phẩm không thuộc danh mục đang kiểm kho để bạn chọn sản phẩm khác.
(*) Khuyến cáo: Bạn nên sử dụng phương án Quét bằng mã vạch sản phẩm để tránh nhầm lẫn, sai sót báo cáo về sau.

Giao diện làm việc khi nhập sản phẩm kiểm kho như hình bên dưới:

## 1.2. Import bằng file Excel: Click vào tab Import Excel để thực hiện thao tác Import kiểm kho bằng file Excel. Quy trình như sau

- Tải file mẫu import về
- Nhập tên sản phẩm/mã vạch/mã sản phẩm và số lượng sản phẩm tồn thực tế vào file import, sau đó save lại
- Import file Excel kiểm kho lên hệ thống.

Giao diện làm việc của Import kiểm kho như sau:

(*) Lưu ý: Trong quá trình nhập liệu sản phẩm kiểm kê, để tránh rủi ro cho doanh nghiệp, hệ thống sẽ tự động lưu lại phiếu kiểm kho sau mỗi một thao tác thêm sản phẩm vào phiếu của bạn.

## III. Tìm sản phẩm thiếu ( Với loại kiểm kho theo danh mục/ kiểm kho toàn bộ)

Trong quá trình kiểm kho sẽ có trường hợp, sản phẩm có số tồn trên hệ thống tuy nhiên khi đi kiểm thì không còn sản phẩm nào ( tức là đã bị mất hang) thì trong phiếu kiểm kho bạn sẽ không thấy xuất hiện tên/ mã sản phẩm đó.

Đối với loại kiểm kho theo danh mục/ kiểm toàn bộ cửa hàng, bạn cần vào danh sách phiếu kiểm kho - ấn nút tìm sản phẩm thiếu . Khi click vào biểu tượng này hệ thống sẽ cho toàn bộ các các sản phẩm chưa được kiểm hoặc không có trong phiếu kiểm kho vào phiếu kiểm với số lượng tồn thực tế bằng 0.

Đây là 1 bước rất quan trọng, nếu bạn không ấn nút này => hệ thống sẽ không tính toán được lượng hàng thừa thiếu của các sản phẩm không được kiểm này.

## IV. Bù trừ kiểm kho

Bù trừ kiểm kho là nghiệp vụ chuyển khớp số lượng chênh lệch giữa hệ thống và tồn thực tế sau khi được kiểm kho.

Bản chất là đưa số liệu tồn kho của sản phẩm trên hệ thống về đúng với số lượng tồn kho thực tế

Quy trình bù trừ kiểm kho được thực hiện như sau:

## Bước 1: Truy cập vào Danh sách phiếu kiểm kho, tìm đến phiếu kiểm kho cần tiến hành bù trừ

Tại Danh sách phiếu kiểm kho, bạn sẽ bắt gặp một số khái niệm như:

- Gộp phiếu kiểm kho: Chức năng này dùng để gộp các phiếu kiểm kho lại làm một, tuy nhiên chỉ gộp được khi:

+ Các phiếu phải cùng một cửa hàng và cùng 1 loại phiếu (sản phẩm / danh mục / toàn bộ)
+ Các phiếu chưa được làm phiếu bù trừ kiểm kho.

- Báo cáo: Click vào để xem chi tiết tổng số lượng sản phẩm thừa/thiếu trong mỗi lần kiểm kho
- Bù trừ kiểm kho: Dùng để cân bằng lại số tồn trên hệ thống sao cho giống với số tồn thực thế (bằng cách tạo các phiếu XNK Khác)

## Bước 2: Bù trừ kiểm kho

- Tại Danh sách phiếu kiểm kho, bạn click vào nút Bù trừ kiểm kho.
- Hệ thống sẽ hiển thị màn hình Thêm phiếu xuất nhập kho bù trừ thừa thiếu theo phiếu kiểm kho, bạn tiếp tục click vào Thêm phiếu XNK
- Lúc này, hệ thống sẽ tự động tạo 2 phiếu (Xuất kho và Nhập kho) để cân bằng lại số tồn.

## Bước 3: Kiểm tra lại việc Bù trừ kiểm kho

Sau khi bù trừ kiểm kho, bạn nên quay lại trang Danh sách phiếu kiểm kho để xem hệ thống đã tạo các phiếu Xuất/Nhập bù trừ kiểm kho chưa, và quay lại trang Danh sách sản phẩm để xem số tồn trên hệ thống đã khớp với số tồn thực tế vừa kiểm hay chưa.

Trên đây là toàn bộ quy trình kiểm kho trên Nhanh.vn, ngoài ra bạn cũng có thể tham khảo một số kinh nghiệm kiểm kho tại đây

Bạn có thể xem video hướng dẫn kiểm kho cân tồn tại đây
