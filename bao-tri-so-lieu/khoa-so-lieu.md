---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: false
---

# Khóa số liệu

Khóa số liệu nhằm mục đích không cho người dùng thao tác các màn hình dữ liệu, chứng từ trước ngày này không thể sửa (chỉ xem)

Thao tác khóa số liệu được thực hiện sau khi chốt dữ liệu kỳ (tháng/ quý/ năm) được thực hiện bởi kế toán tổng hợp/ kế toán trưởng để không cho người dùng nào được phép thêm mới, sửa, xóa chứng từ làm ảnh hưởng đến báo cáo đã chốt.

## Hướng dẫn thao tác

Đường dẫn: _**Hệ thống/ Các tham số tùy chọn và khóa số liệu/ Khóa số liệu**_

### Khóa số liệu cho toàn hệ thống

<figure><img src="../.gitbook/assets/khóa số liệu 01.png" alt=""><figcaption><p>Khóa số liệu toàn hệ thống</p></figcaption></figure>

### Khóa số liệu đơn vị chi nhánh

Tính năng này sử dụng cho công ty có nhiều đơn vị cơ sở (chi nhánh), mà mỗi đơn vị có bộ phận kế toán độc lập và có thời gian chốt báo cáo kỳ khác nhau.&#x20;

Đường dẫn: _**Hệ thống/ Các tham số tùy chọn và khóa số liệu/ Khóa số liệu theo đơn vị (Chi nhánh)**_

<figure><img src="../.gitbook/assets/Khóa số liệu 02.png" alt=""><figcaption><p>Khóa số liệu theo Đơn vị cơ sở</p></figcaption></figure>

### Khóa số liệu chi tiết theo chứng từ và đơn vị

Tính năng này sử dụng khi công ty có quy định thời gian chốt dữ liệu kỳ khác nhau cho từng bộ phận. VD kế toán tiền phải chốt sổ vào ngày 3, kế toán kho là ngày 5, kế toán tổng hợp là ngày 10 hàng tháng.

Đường dẫn: _**Hệ thống/ Các tham số tùy chọn và khóa số liệu/ Khóa số liệu chi tiết theo chứng từ và đơn vị**_

<figure><img src="../.gitbook/assets/khóa số liệu 03.png" alt=""><figcaption><p>Khóa số liệu theo chứng từ</p></figcaption></figure>

Khi muốn áp lại ngày khóa sổ cho cùng đơn vị, người sử dụng, chứng từ đã khóa số liệu trước đó, thì chỉ cần chọn sửa phiếu, nhập ngày khóa sổ mới và nhấn nút Áp dụng cho tất cả chi tiết và Lưu.

### Cách mở khóa số liệu

Để mở khóa số liệu thì thực hiện thao tác dời ngày khóa số liệu lên trước ngày muốn mở khóa sổ.

Ví dụ: Công ty đang khóa số liệu tại ngày 31/12/2022, vì một lý do nào đó mà có nhu cầu sửa phiếu ngày 01/12/20022. Thì thực hiện thao tác khóa số liệu ngày 30/11/2022.&#x20;

Lưu ý:

* Khi vừa khóa số liệu hệ thống và vừa khóa số liệu đơn vị (hoặc chứng từ) thì chương trình sẽ xét theo cả hai điều kiện khóa và khóa theo điều kiện có ngày khóa lớn hơn.

Ví dụ: ngày khóa số liệu hệ thống là ngày 31/12/2022 và ngày khóa số liệu chứng từ hóa đơn bán là ngày 31/01/2023 thì ngày khóa số liệu của tất cả chứng từ là ngày 31/12/2022, riêng ngày khóa số của chứng từ bán là ngày 31/01/2023.

* Khi mở khóa số liệu chứng từ thì phải xem ngày cần mở có nằm trong vùng ngày khóa số liệu hệ thống hay không. Nếu có thì phải mở khóa số liệu hệ thống.
