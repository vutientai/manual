# Hạch toán kế toán bảo hành

Khi trả bảo hành thì hệ thống sẽ tạo ra các phiếu:

Phiếu bán hàng hạch toán theo Nợ *131*, Có *5111* - số tiền = phí sửa chữa + giá linh kiện (nếu có)

Phiếu thu hạch toán theo Nợ *1111* (mã tk tiền mặt), Có *131* - số tiền mặt khách đưa cho dn

Phiếu Báo có (thu tiền) hạch toán theo Nợ (mã tk ngân hàng), Có *131* - số tiền chuyển khoản khách chuyển cho dn

Phiếu xuất hạch toán theo Nợ *1561*, Có *632* - hạch toán giá vốn của linh kiện.

Các phiếu này được gắn chứng từ theo ID phiếu trả bảo hành

## Lưu ý:

Nếu như ko điền tiền mặt, tiền chuyển khoản thì hạch toán kê toán phiếu XNK trả bảo hành sẽ chỉ sinh phiếu bán hàng, hiển thị khách hàng đang nợ doanh nghiệp

Nếu điền số tiền khách trả < số tiền phải trả thì hạch toán phiếu XNK trả Bảo hành sẽ sinh ra phiếu bán hàng, phiếu thu/ phiếu chuyển khoản với số tiền tương ứng, hiển thị khách hàng đang nợ doanh nghiệp.
