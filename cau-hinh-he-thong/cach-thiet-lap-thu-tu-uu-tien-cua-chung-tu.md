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

# Cách thiết lập thứ tự ưu tiên của chứng từ

Chức năng này cho phép người dùng thiết lập thứ tự sắp xếp của chứng từ trên một số báo cáo (sổ cái, thẻ kho, bảng kê nhập xuất kho, ...) và thứ tự ưu tiên khi tính giá nhập trước xuất trước, giá trung bình di động khi có nhiều chứng từ cùng phát sinh cùng ngày.&#x20;

## Các bước thao tác

**Bước 1.** **Truy cập vào màn hình danh mục chứng từ**

Đường dẫn: _**Hệ thống/ Thông tin chứng từ**_

<figure><img src="../.gitbook/assets/danh mục ct.png" alt=""><figcaption><p>Truy cập vào danh mục chứng từ</p></figcaption></figure>

**Bước 2. Chọn chứng từ, bấm Sửa và khai báo số thứ tự**

<figure><img src="../.gitbook/assets/thứ tự ưu tiên ct.png" alt=""><figcaption><p>Nhập số thứ tự cho chứng từ</p></figcaption></figure>

## **Ví dụ minh hoạ**

Cần thiết lập để thứ tự các phiếu nhập sắp xếp trước các phiếu xuất trên khi tính giá trị của hàng tồn kho.

**Bước 1. Thiết lập thứ tự ưu tiên trong danh mục chứng từ**

Ở bước này, các phiếu nhập kho cần được đánh số thứ tự nhỏ hơn (ưu tiên hơn) các phiếu xuất kho.

Trường hợp này cần đánh số thứ tự của phiếu nhập trước, gồm Hoá đơn mua hàng trong nước, Hoá đơn mua nhập khẩu, Phiếu nhập mua hàng, Phiếu nhập kho, Phiếu nhập hàng bán trả lại, Phiếu nhập chi phí mua hàng, Phiếu nhập điều chuyển theo thứ tự 1, 2, 3, 4, 5, 6, 7.

Đánh số thứ tự của phiếu xuất, gồm Hoá đơn bán hàng, Phiếu xuất bán hàng, Phiếu xuất trả nhà cung cấp, Phiếu xuất điều chuyển theo thứ tự 8, 9, 10, 11.

Sau đây là thiết lập mẫu trên hoá đơn mua hàng trong nước (phiếu nhập) và hoá đơn bán hàng (phiếu xuất).

<figure><img src="../.gitbook/assets/ưu tiên phiếu nhập.png" alt=""><figcaption><p>Thiết lập thứ tự ưu tiên của phiếu nhập</p></figcaption></figure>

<figure><img src="../.gitbook/assets/ưu tiên phiếu xuất.png" alt=""><figcaption><p>Thiết lập thứ tự ưu tiên của phiếu xuất</p></figcaption></figure>

**Bước 2. Xem báo cáo**

Đường dẫn: _**Tồn kho/ Báo cáo/ Thẻ kho, sổ chi tiết vật tư**_

<figure><img src="../.gitbook/assets/thứ tự ưu tiên ct 2.png" alt=""><figcaption><p>Xem báo cáo thẻ kho</p></figcaption></figure>

Trên các báo cáo thẻ kho (hoặc bảng kê nhập/ xuất kho), trường hợp có nhiều phiếu nhập, xuất phát sinh cùng ngày thì thứ tự sắp xếp các phiếu nhập xuất sẽ được quy định bởi thứ tự ưu tiên đã khai báo trong danh mục chứng từ.

Trong trường hợp này, hoá đơn mua hàng trong nước có thứ tự ưu tiên nhỏ hơn nên được xếp trước, hoá đơn bán hàng xếp sau. Từ đó, giá trị hàng tồn kho được tính luỹ kế theo nguyên tắc cộng giá trị của phiếu nhập trước, sau đó mới trừ đi giá trị của phiếu xuất.
