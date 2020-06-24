# Xác nhận đơn hàng

Sau khi tạo đơn hàng, nhân viên telesale sẽ gọi điện cho khách để xác nhận lại một số thông tin về đơn hàng như: tên sản phẩm, số lượng sản phẩm, thông tin khách hàng, hình thức thanh toán, thông tin phí vận chuyển,...
## QUY TRÌNH XÁC NHẬN ĐƠN HÀNG
**Bước 1**: Kiểm tra lại các đơn hàng trùng để tránh tình trạng đóng gói và gửi hàng nhiều lần cho cùng một khách hàng vào phần đơn trùng hoặc truy cập [tại đây.](link)
- Trang này liệt kê toàn bộ các số điện thoại có nhiều đơn hàng trong khoảng thời gian lọc để kiểm tra lại xem có bị trùng đơn, tránh tình trạng đóng gói và gửi hàng nhiều lần.

- Mặc định hệ thống sẽ lọc đơn trong 2 ngày gần nhất. Bạn có thể chọn lại khoảng ngày này.

Liệt kê tất cả các đơn hàng cần xác nhận: Tại [Danh sách đơn hàng](link). Click vào tab ![xac nhan don hang](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/xac-nhan-don-hang-1.png). Hệ thống sẽ hiển thị ra tất cả những đơn hàng cần xác nhận.

Nhân viên click vào những đơn hàng Mới (chưa có ai xác nhận) và những đơn hàng Chờ khách xác nhận (chưa gọi được cho khách) để xác nhận các đơn hàng đó.

Lưu ý: Khi 1 nhân viên click vào đơn hàng để xác nhận, hệ thống sẽ chặn không cho nhân viên khác xác nhận đơn hàng đó ==> loại bỏ tình huống nhân viên xác nhận trùng khách.

**Bước 2:** Giao diện làm việc của module Xác nhận đơn hàng như sau. Ở khâu thao tác này, nhân viên chăm sóc khách hàng (CSKH) của doanh nghiệp cần xác nhận với khách hàng tất cả thông tin về đơn hàng và thay đổi trạng thái đơn hàng.

![Giao diện module Xác nhận đơn hàng](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/xac-nhan-%20don-hang-2.png)

Tình trạng:

**Chờ xác nhận:** Áp dụng với đơn hàng đang chờ người bán xác nhận.

**Đã xác nhận:** Áp dụng với đơn hàng khách đồng ý nhận hàng.

**Đang xác nhận:** Áp dụng với đơn hàng chưa liên hệ được với khách hoặc lý do khác khiến khách chưa muốn nhận hàng.

**Khách hủy:** Áp dụng với đơn hàng khách không đồng ý nhận hàng.

**Hệ thống hủy:** Áp dụng với đơn hàng không liên hệ được với khách, hoặc hết hàng, hoặc lý do khác.

Trong khi xác nhận đơn hàng, nhân viên CSKH cần kiểm tra về số lượng sản phẩm tồn trong kho của mỗi đơn hàng. 

![](https://raw.githubusercontent.com/nhanhapi/manual/master/docs/don-hang/img/xac-nhan-don-hang-3.png)
- Nếu sản phẩm tại kho đặt hàng đang tạm hết hàng, các kho khác vẫn còn hàng, cần chuyển kho đặt hàng hoặc điều chuyển sản phẩm từ kho đó về kho đăng ký đặt hàng.
- Nếu sản phẩm hết hàng toàn bộ, nhân viên CSKH cần xác nhận với khách hàng hoặc gửi SMS thông báo cho khách hàng biết để khách chuyển sang sản phẩm khác.

**Bước 3:** Sau khi hoàn tất các khâu xác nhận ở trên, nhân viên CSKH click nút **Lưu** hoặc **Lưu và in** để hoàn tất quy trình xác nhận đơn hàng:
- Lưu: Đơn hàng sẽ chuyển sang trạng thái Đã xác nhận
- Lưu và in: Phiếu gửi hàng sẽ được in ra, đồng thời đơn hàng chuyển sang trạng thái Đang đóng gói sản phẩm.

Sau khi xác nhận đơn hàng, doanh nghiệp chuyển sang bước [In và đóng gói đơn hàng](https://manual.nhanh.vn/don-hang/quy-trinh-xu-ly-don-hang/in-va-dong-goi-don-hang)

**LƯU Ý:**
- Khi tài khoản có quyền xác nhận đơn hàng thì khi kích vào trạng thái **Mới** ngoài danh sách đơn hàng hoặc kích Tab Xác nhận ở trong chi tiết đơn hàng thì trạng thái đơn sẽ chuyển thành trạng thái **"Đang xác nhận"** và lưu người chăm sóc là tài khoản đã tích xác nhận này

- Để CSKH không lấy đơn hàng của nhau để chăm sóc thì vào Cài đặt -> bật On cài đặt **"Không cho phép xử lý đơn hàng**: Khi một nhân viên CSKH đang xác nhận 1 đơn hàng, không cho phép CSKH khác được xác nhận lại đơn hàng đó (trừ quyền Trưởng nhóm CSKH sẽ vẫn được thao tác tiếp)."

- Trường hợp thay ca của tài khoản chăm sóc thì muốn tài khoản của ca sau chăm sóc và gắn làm người chăm sóc thì tài khoản Giám đốc hoặc tài khoản có quyền đổi trạng thái đơn hàng sẽ đổi trạng thái đơn về **Mới** -> Đơn hàng cho phép tài khoản ca sau chăm sóc và ghi nhận lại người chăm sóc

Bạn có thể tham khảo video hướng dẫn xác nhận đóng gói đơn hàng tại đây:
