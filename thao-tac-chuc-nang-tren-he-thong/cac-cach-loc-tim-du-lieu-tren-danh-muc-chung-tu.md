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

# Các cách lọc tìm dữ liệu trên danh mục, chứng từ

Bài viết hướng dẫn cách lọc, tìm dữ liệu trên các màn hình danh mục, chứng từ.

## Các bước thực hiện

Để tìm, lọc dữ liệu trên các màn hình danh mục, chứng từ, người dùng có thể lựa chọn một trong hai cách sau đây:

### Cách 1. Sử dụng chức năng lọc trên từng cột dữ liệu có trên màn hình hiển thị

**Bước 1.** Truy cập vào màn hình danh mục, chứng từ. Click chuột vào Thanh tiêu đề của cột cần lọc dữ liệu.

<figure><img src="../.gitbook/assets/lọc dữ liệu 1.png" alt=""><figcaption><p>Click chuột để chương trình hiển thị chức năng lọc</p></figcaption></figure>

Người dùng cũng có thể click chuột vào ô tìm kiếm (dưới thanh tiêu đề) để thực tiện thao tác lọc.

<figure><img src="../.gitbook/assets/lọc dữ liệu 5.png" alt=""><figcaption><p>Thao tác lọc ở các ô tìm kiếm</p></figcaption></figure>

**Bước 2.** Nhập ký tự lọc ở ô Tìm kiếm

<figure><img src="../.gitbook/assets/lọc dữ liệu 2.png" alt=""><figcaption><p>Thao tác lọc dữ liệu</p></figcaption></figure>

**Lưu ý**

Lọc ký tự ABC ở các trường dạng chuỗi (tên khách hàng, địa chỉ, ...) --> chương trình trả kết quả là danh sách các dòng mà cột đang lọc có chứa ký tự ABC.

* _Khi lọc ký tự ABC ở cột tên khách hàng --> Kết quả lọc là danh sách các dòng mà trong tên                               khách hàng có chứa ký tự ABC._

Khi các ký tự lọc bắt đầu bằng **\*; % -->** Sử dụng để tìm các ký tự giữa của chuỗi, chương trình trả kết quả là danh sách các dòng mà cột đang lọc có chứa ký tự lọc (áp dụng đối với các trường dạng mã và chuỗi như mã khách hàng, mã số thuế, tên khách hàng, ...)

* _VD: Nhập ký tự lọc ở cột mã khách hàng là \*ABC hoặc %ABC --> Kết quả trả về là các danh sách các dòng mà trong mã khách hàng có chứa ký tự ABC._

Khi các ký tự lọc bắt đầu bằng **=; >=; >; <; <= -->** Tìm theo phép so sánh, chương trình trả kết quả là danh sách các dòng mà cột đang lọc có giá trị =; >=; >; <; <=

* _VD:_&#x20;

&#x20;     _Lọc ký tự >10 ở trường tên khách hàng (dạng chuỗi) --> Kết quả trả về là danh sách các dòng_

&#x20;    _có tên khách hàng '>10'._

&#x20;    _Lọc ký tự >10 ở trường số lượng (dạng số) --> Kết quả trả về là danh sách các dòng có số lượng_&#x20;

&#x20;   _> 10._

&#x20;   _Lọc ký tự >20/09/2019 ở trường dạng ngày sinh (dạng số)--> Kết quả trả về là danh sách các_&#x20;

&#x20;   _dòng có ngày sinh lớn hơn 20/09/2019._

Khi các ký tự lọc bắt đầu bằng **i%; i\* (không giống); <>; != (khác)** --> Tìm theo phép loại trừ, chương trình trả kết quả là danh sách các dòng mà cột đang lọc không chứa ký tự lọc.

* _VD: Lọc ký tự <> ở trường mã số thuế --> Kết quả trả về là danh sách các dòng có mã số thuế khác trắng._

Để lọc các dòng dữ liệu trắng, nhập ký tự lọc là dấu bằng (=).

_VD: Lọc ký tự = ở trường mã số thuế --> Kết quả trả về là danh sách các dòng có mã số thuế trắng._

Lọc ký tự **; (chấm phẩy), | (gạch đứng)** --> Tìm theo phép toán hoặc OR.

* VD

&#x20;     _Khi lọc theo cú pháp KH;ARITO ở trường Tên khách hàng (dạng chuỗi)--> Kết quả trả về danh sách các dòng_

&#x20;    _có tên khách hàng có giá trị bắt đầu là KH hoặc có chứa chuỗi ARITO._

&#x20;    _Khi lọc theo cú pháp >10&<1000 ở trường Số lượng (dạng số)--> Kết quả trả về danh sách các_&#x20;

&#x20;    _dòng có số lượng lớn hơn 10 và nhỏ hơn 1000._

Ngoài ra, khi lọc các cột dữ liệu có kiểu dữ liệu ngày thì cần nhập theo định dạng dd/MM/yyyy. Nếu nhập định dạng dd hoặc dd/MM thì hệ thống tự điền phần còn lại dựa trên tháng, năm hiện tại.

* _VD: Nhập cú pháp lọc là 02/05 --> Hệ thống lọc theo các dòng có ngày bằng 02/05/20xx (20xx là năm hiện tại)._

**Cách 2. Sử dụng nút chức năng Tìm kiếm**

Nút chức năng Tìm kiếm thường có trên các màn hình chứng từ.

**Bước 1.** Truy cập vào màn hình danh mục, chứng từ. Bấm Tìm kiếm ![](<../.gitbook/assets/image (30).png>)

<figure><img src="../.gitbook/assets/tìm kiếm 1.png" alt=""><figcaption><p>Biểu tượng Tìm kiếm trên chứng từ</p></figcaption></figure>

**Bước 2.** Nhập các thông tin cần lọc

<figure><img src="../.gitbook/assets/tìm kiếm 2.png" alt=""><figcaption><p>Mô tả chức năng Tìm kiếm</p></figcaption></figure>

**Lưu ý**

Khi lọc theo người sử dụng thì hệ thống cho phép lọc theo người tạo chứng từ. Có thể lựa chọn chỉ theo người tạo là user đang thao tác (Lọc theo người tạo) hoặc tất cả người tạo (Tất cả).
