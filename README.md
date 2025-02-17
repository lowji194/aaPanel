[![🇺🇸 English](https://img.shields.io/badge/Language-English-blue?style=for-the-badge&logo=Google%20Translate)](README-EN.md)
---
# Hướng dẫn cài đặt và kích hoạt aaPanel

## Giới thiệu

**aaPanel** là một phần mềm quản lý máy chủ (web hosting control panel) mã nguồn mở, giúp bạn dễ dàng quản lý máy chủ của mình với giao diện người dùng trực quan. Hướng dẫn dưới đây sẽ giúp bạn cài đặt **aaPanel** và kích hoạt phiên bản **Premium** với các tính năng mạnh mẽ.

## Yêu cầu trước khi cài đặt

- **Hệ điều hành**: Ubuntu, CentOS, hoặc Debian.
- **Quyền root**: Bạn cần quyền quản trị viên (root) trên máy chủ của mình.
- **Kết nối internet**: Đảm bảo máy chủ của bạn có kết nối internet ổn định để tải các gói cần thiết.

## Bước 1: Cài đặt aaPanel

1. **Truy cập vào máy chủ**: 
   - Sử dụng SSH để đăng nhập vào máy chủ của bạn:
   
     ```bash
     ssh root@<địa_chỉ_ip_máy_chủ>
     ```

2. **Cài đặt aaPanel**:
   - Chạy lệnh dưới đây để tải và cài đặt **aaPanel** từ GitHub:
   
     ```bash
     bash <(curl -Ls https://raw.githubusercontent.com/lowji194/linh-tinh/refs/heads/main/AAPanel/aapanel_7.sh)
     ```

   - Lệnh trên sẽ tải script từ GitHub và tự động cài đặt **aaPanel** lên máy chủ của bạn. Quá trình này có thể mất vài phút.

3. **Xác nhận cài đặt**:
   - Sau khi cài đặt thành công, bạn sẽ nhận được thông tin đăng nhập và địa chỉ IP của máy chủ để truy cập vào **aaPanel**.

## Bước 2: Truy cập vào aaPanel

1. **Mở trình duyệt web**:
   - Sau khi cài đặt, mở trình duyệt và nhập địa chỉ IP của máy chủ cùng cổng `8888`:
   
     ```
     http://<địa_chỉ_ip_máy_chủ>:8888
     ```

   - Ví dụ: `http://192.168.1.100:8888`

2. **Đăng nhập**:
   - Sử dụng thông tin đăng nhập được cung cấp trong quá trình cài đặt để đăng nhập vào **aaPanel**.

   - Thông tin đăng nhập mẫu:
     - **Tài khoản**: admin
     - **Mật khẩu**: (mật khẩu được cung cấp trong thông báo sau cài đặt)

   - Sau khi đăng nhập thành công, bạn sẽ thấy giao diện quản lý của **aaPanel**.

## Bước 3: Kích hoạt aaPanel Premium

1. **Chạy lệnh kích hoạt Premium**:
   - Để nâng cấp lên phiên bản **Premium** của aaPanel, bạn cần chạy lệnh sau:
   
     ```bash
     bash <(curl -Ls https://raw.githubusercontent.com/lowji194/linh-tinh/refs/heads/main/AAPanel/Active7.sh)
     ```

   - Lệnh này sẽ kích hoạt **aaPanel Premium**, giúp bạn có thêm các tính năng cao cấp như hỗ trợ nhiều tính năng quản lý, bảo mật và tối ưu hóa hệ thống.

2. **Kiểm tra kích hoạt thành công**:
   - Sau khi chạy lệnh kích hoạt, bạn có thể kiểm tra phiên bản Premium trong giao diện **aaPanel**. Phiên bản Premium sẽ cung cấp thêm các tùy chọn và tính năng quản lý máy chủ mạnh mẽ.

## Bước 4: Cấu hình thêm (Tuỳ chọn)

Sau khi cài đặt và kích hoạt **aaPanel**, bạn có thể cấu hình thêm các dịch vụ như:

- **Cài đặt Web Server**: Apache, Nginx hoặc OpenLiteSpeed.
- **Cài đặt PHP và MySQL**: aaPanel hỗ trợ cài đặt và cấu hình các phiên bản PHP và MySQL.
- **Cài đặt SSL**: Cài đặt SSL miễn phí từ Let’s Encrypt để bảo mật trang web của bạn.
- **Cấu hình Firewall và bảo mật**: aaPanel hỗ trợ cấu hình tường lửa và các tính năng bảo mật nâng cao.

## Lưu ý

- **Quyền truy cập**: Đảm bảo rằng bạn đang sử dụng tài khoản root hoặc tài khoản có quyền sudo trên máy chủ của bạn để thực hiện các bước trên.
- **Firewall**: Nếu bạn gặp sự cố khi truy cập vào aaPanel, hãy kiểm tra cấu hình firewall của máy chủ, đảm bảo rằng cổng `8888` mở cho kết nối từ bên ngoài.
- **Đảm bảo kết nối internet ổn định**: Quá trình cài đặt và kích hoạt có thể yêu cầu tải các gói từ internet, vì vậy hãy chắc chắn máy chủ của bạn có kết nối internet tốt.

