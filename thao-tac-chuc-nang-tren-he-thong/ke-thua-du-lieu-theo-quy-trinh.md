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

# Kế thừa dữ liệu theo quy trình

Dùng để kế thừa dữ liệu từ các chứng từ với nhau trong quy trình. Chứng từ sau sẽ kế thừa dữ liệu của chứng từ trước

Lưu vết dữ liệu đã được lấy và có thể truy về chứng từ được lấy dữ liệu để theo dõi/ kiểm tra

## Các bước thực hiện

Hiện tại trên phần mềm đều có nhiều chứng từ lấy dữ liệu từ chứng từ khác để thể hiện các chứng từ có liên kết với nhau

Ví dụ: Hóa đơn mua hàng trong nước => Lấy dữ liệu từ Đơn hàng mua trong nước

**Bước 1.** Thêm mới Đơn hàng mua trong nước

Đường dẫn: _**Mua hàng/ Đơn hàng/ Đơn hàng mua trong nước**_

<figure><img src="../.gitbook/assets/kế thừa.png" alt=""><figcaption><p>Đơn hàng mua trong nước</p></figcaption></figure>

**Bước 2.** Thêm mới hóa đơn mua hàng trong nước

Đường dẫn: _**Mua hàng/ Hóa đơn/ Hóa đơn mua hàng trong nước**_

<figure><img src="../.gitbook/assets/kế thừa1.png" alt=""><figcaption></figcaption></figure>

**Bước 3.** Kế thừa dữ liệu từ Đơn hàng mua trong nước ở bước 1

Kế thừa dữ liệu từ Đơn hàng được tạo mới ở bước 1 và Lưu

<figure><img src="../.gitbook/assets/kế thừa2.png" alt=""><figcaption></figcaption></figure>

**Bước 4.** Kiểm tra liên kết chứng từ

Kiểm tra nếu số đơn hàng và dòng của sản phẩm tương ứng với B1 khi thiết lập Đơn hàng mới và kiểm tra trạng thái trên Đơn hàng, nếu ở trạng thái: Đang thực hiện/ Hoàn thành thì hoàn thành việc liên kết chứng từ

<figure><img src="../.gitbook/assets/kế thừa3.png" alt=""><figcaption></figcaption></figure>
