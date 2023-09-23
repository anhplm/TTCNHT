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

# Khai báo và phân quyền người dùng mới

Tài liệu mô tả các bước thao tác tạo mới người sử dụng và phân quyền truy cập cơ bản để sử dụng chương trình. Chức năng chỉ được sử dụng cho tài khoản quản trị (ADMIN) hoặc tài khoản có quyền quản lý.

## Hướng dẫn thao tác

### Khai báo người sử dụng

**Bước 1:** Vào Đường dẫn: _**Hệ thống/ Quản lý tài khoản/ Người sử dụng.**_

**Bước 2:** Trên thanh công cụ, nhấn **Thêm** để tạo mới.

<figure><img src="../.gitbook/assets/Sysuserinfo_1 (1).png" alt=""><figcaption><p>Khai báo người sử dụng</p></figcaption></figure>

**Bước 3:** Khai báo thông tin người sử dụng mới.

<figure><img src="../.gitbook/assets/image (39).png" alt=""><figcaption><p>Khai báo người sử dụng</p></figcaption></figure>

Các thông tin cần lưu ý khi khai báo tài khoản:

* Tên: Tài khoản đăng nhập.
* Mật khẩu: Mật khẩu truy cập lần đầu cho người dùng. Lưu ý mật khẩu phải tối thiểu 8 ký tự và không được đặt các mật khẩu thông dụng, nếu không chương trình sẽ báo mật khẩu không hợp lệ.
* Thư: Địa chỉ email của người sử dụng, dùng trong các trường hợp gửi mail duyệt theo quy trình hoặc quên mật khẩu.
* Đổi mật khẩu khi đăng nhập: Khi người sử dụng đăng nhập lần đầu tiên bằng tài khoản được cấp thì phải đổi mật khẩu mới.

### Phân quyền chức năng người dùng

**Bước 1:** Vào đường dẫn: _**Hệ thống/ Quản lý tài khoản/ Người sử dụng.**_

_**Bước 2:**_ Chọn dòng tài khoản được phân quyền, nhấn nút **Phân quyền** trên thanh công cụ.

<figure><img src="../.gitbook/assets/Group 1000008702.png" alt=""><figcaption></figcaption></figure>

**Bước 3:** Tick chọn các quyền mà tài khoản được phép thao tác và nhấn Đồng ý.

### Khai báo và phân quyền nhóm người sử dụng

Chức năng dùng để khai báo nhóm người sử dụng có cùng chức năng truy cập sử dụng và có thể phân quyền cho nhóm thay vì phải phân quyền từng user.

Cách phân quyền nhóm user tương tự phân quyền từng user, khi phân quyền theo nhóm, thì tất cả user trong nhóm có chức năng như nhau, quyền truy cập như nhau.

**Bước 1:** Vào đường dẫn: _**Hệ thống/ Quản lý tài khoản/ Nhóm người sử dụng.**_

**Bước 2:** Chọn vào **Thêm** để tạo mới.

<figure><img src="../.gitbook/assets/image (40).png" alt=""><figcaption><p>Thêm mới nhóm người sử dụng.</p></figcaption></figure>

**Bước 3:** Khai báo Nhóm, Tên nhóm và Danh sách user của nhóm sau đó nhân **Lưu**.

<figure><img src="../.gitbook/assets/Nhóm user (1).png" alt=""><figcaption><p>Khai báo nhóm người sử dụng.</p></figcaption></figure>

**Lưu ý:** Để phân quyền nhân vào nút Phân quyền trên thanh công cụ thao tác tương tự phân quyền cho từng user.

### Phân quyền truy cập theo đơn vị cơ sở

Bước này thực hiện khi công ty có nhiều đơn vị cơ sở, cần phân quyền để nhận biết người dùng được quyền tác động dữ liệu tại đơn vị nào.

Nếu chỉ có 1 đơn vị cơ sở thì quyền là mặc định, không cần phân quyền bước này.

**Bước 1:** Vào đường dẫn: _**Hệ thống/ Phân quyền và giới hạn truy cập/ Phân quyền truy cập theo đơn vị.**_

**Bước 2:** Nhấn **Thêm** để khai báo nhóm user phân quyền.

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

**Bước 3:** Chọn Tên/Nhóm, danh sách chi nhánh và tick chọn chức năng sau đó nhấn **Lưu.**

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>
