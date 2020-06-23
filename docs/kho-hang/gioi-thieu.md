Bạn có thể thực hiện nghiệp vụ xuất nhập kho (Viết tắt là XNK), chuyển kho, tạo Phiếu XNK nháp, kiểm kho và một số tính năng đặc biệt hỗ trợ cho việc quản lý và ra quyết định nhập xuất hàng.
# 1.Quy trình thao tác cơ bản trong Kho hàng:
## 1.1. Nhập hàng nhà cung cấp: bạn nhập một số lượng sản phẩm từ nhà cung cấp về để bán hàng:
Bước 1: Thêm nhà cung cấp

Bước 2: Thêm phiếu nhập hàng từ Nhà cung cấp
## 1.2. Trả hàng cho nhà cung cấp
## 1.3. Chuyển hàng giữa các cửa hàng: Trong quá trình kinh doanh, một kho/cửa hàng bị hết hàng trong khi kho khác vẫn còn thì có thể làm thao tác chuyển kho.
Bước 1: Thêm phiếu yêu cầu chuyển kho hoặc Thêm phiếu chuyển kho
Bước 2. Duyệt và Xác nhận phiếu yêu cầu chuyển kho
## 1.4. Kiểm kho: Kiểm tra lại số lượng sản phẩm, hàng hóa trong kho và bù trừ cho khớp giữa số lượng tồn thực tế và số lượng tồn trên hệ thống
Bước 1: Thêm phiếu kiểm kho
Bước 2: Bù trừ kiểm kho
## 1.5. Quản lý vị trí sản phẩm trong kho
# 2. Các khái niệm được sử dụng trong Kho hàng
Các loại ID, bao gồm:
| Các loại ID | Ý nghĩa |
|-------------|---------|
| ID phiếu XNK | Mỗi phiếu XNK sẽ được hệ thống cấp cho 1 ID riêng|
| ID sản phẩm XNK | Trong mỗi phiếu XNK sẽ có 1 hoặc nhiều sản phẩm XNK, mỗi sản phẩm XNK đó được hệ thống cấp cho 1 ID riêng|
| ID phiếu yêu cầu XNK | Khi tạo 1 phiếu yêu cầu XNK, hệ thống sẽ gắn 1 ID riêng cho phiếu đó, không phải là ID của phiếu XNK|
| ID sản phẩm yêu cầu XNK | Trong mỗi phiếu yêu cầu XNK sẽ có 1 hoặc nhiều sản phẩm yêu cầu XNK, hệ thống sẽ gắn cho mỗi sản phẩm đó 1 ID riêng, không phải là ID sản phẩm XNK |
| ID phiếu kiểm kho | Khi bạn tạo 1 phiếu kiểm kho thì hệ thống sẽ cấp một ID riêng cho phiếu đó|
| ID sản phẩm kiểm kho | Trong mỗi phiếu kiểm kho có thể có 1 hoặc nhiều sản phẩm được kiểm kho, mối sản phẩm trong phiếu kiểm kho được hệ thống gắn cho 1 ID riêng|
| ID phiếu bảo hành | Khi khách hàng mang sản phẩm đến bạn để bảo hành hoặc sửa chữa, hệ thống sẽ sinh phiếu bảo hành và gắn ID riêng cho phiếu bảo hành đó|
| ID phiếu XNK bị xóa | Khi xóa 1 phiếu XNK trong danh sách phiếu XNK thì ID của phiếu XNK đó cũng chính là ID trong danh sách phiếu XNK bị xóa|

Loại XNK: bao gồm Xuất kho và Nhập kho

Kiểu XNK: bao gồm:

| Kiểu Xuất nhập kho | Ý nghĩa |
|--------------------|---------|
| [N] Nhà cung cấp | Nhập hàng từ nhà cung cấp, xuất trả lại hàng cho nhà cung cấp|
| [C] Chuyển kho | Chuyển hàng giữa các kho trong doanh nghiệp của bạn|
| [G] Giao hàng | Xuất bán online, nhập lại đơn hàng bị chuyển hoàn|
| [L] Bán lẻ | Xuất bán lẻ, Nhập lại trong trường hợp khách trả lại hàng|
| [B] Bán buôn | Xuất bán buôn, Nhập lại trong trường hợp khách trả lại hàng|
| [T] Hàng tặng kèm | Xuất hàng tặng kèm khi mua sản phẩm, Nhập lại trong trường hợp khách trả lại sản phẩm và hàng tặng kèm|
| [K] Bù trừ kiểm kho | Hệ thống tự động tạo các phiếu Xuất hoặc Nhập kho để bù trừ lại số lượng chênh lệch giữa tồn trên hệ thống và tồn thực tế khi kiểm kho|
| [#] Kiểu khác | Xuất nhập kho này không ghi nhận vào doanh thu|
| [BH] Bảo hành, [SC] Sửa chữa | Nhập hàng để bảo hành, sửa chữa, Xuất trả hàng cho khách|
| [TTBH] Trung tâm bảo hành | Bạn xuất hàng sang Trung tâm bảo hành để bảo hành, sửa chữa máy, và Nhập hàng từ Trung tâm bảo hành về kho của bạn khi quá trình bảo hành sửa chữa hoàn tất|
| [LKBH] Linh kiện bảo hành | Dùng để Xuất, nhập linh kiện phụ vụ cho việc bảo hành, sửa chữa|
