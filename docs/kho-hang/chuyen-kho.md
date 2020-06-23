# Chuyển kho

Khi quản lý nhiều cửa hàng và muốn chuyển hàng từ cửa hàng này sang cửa hàng khác, bạn dùng tính năng Chuyển kho.

Ví dụ: Bạn có 2 kho, muốn chuyển bớt 3 chiếc 'Quần HM 001 - Đen ZZZ ' từ kho A sang kho B, quy trình như sau:
## Bước 1: Cửa hàng 1 tạo phiếu chuyển kho [tại đây](https://new.nhanh.vn/inventory/transfer/add)
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/tao-phieu-ck.png)

## Hệ thống sẽ sinh ra:
- 1 phiếu Xuất [chuyển kho] từ kho A --> kho B. Số tồn ở kho A giảm 3, tuy nhiên số tồn ở kho B chưa tăng. 3 sản phẩm này ở trạng thái Đang chuyển kho
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/phieu-yeu-cau-ck.png)

- 1 phiếu yêu cầu Xuất [chuyển kho].
## Bước 2: Sau khi nhận được hàng, Kho B cần xác nhận phiếu này (Tại [Sắp chuyển đến](https://new.nhanh.vn/inventory/transfer/draft?tab=waitingConfirm))

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/phieu-xac-nhan-ck1.png)
## Bước 3: Sau khi xác nhận phiếu, hệ thống sẽ chuyển sang giao diện xác nhận chuyển kho. Điền số lượng hàng xác nhận chuyển kho và ấn nút Lưu hoặc Lưu và In
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/giao-dien-xac-nhan-phieu-ck%201.png)

## Bước 4: hệ thống tự tạo 1 phiếu Nhập [chuyển kho] để tăng số tồn ở của kho B thêm 3.
![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/kho-hang/img/phieu-chuyen-kho-tu-kho-A-sang-B.png)
Bạn có thể tham khảo video hướng dẫn sử dụng tại đây:
