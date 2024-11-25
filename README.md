# Tool Lấy Refresh Token và Đọc Mail Outlook

## Giới Thiệu

Tool này giúp bạn lấy **Refresh Token** từ tài khoản Microsoft và sử dụng nó để truy cập vào các email trong hộp thư Outlook của bạn. Công cụ hỗ trợ tự động hoá quy trình đăng nhập qua OAuth2 và cung cấp các tính năng tiện ích để xem và tương tác với email của bạn.

## Tính Năng

- **Hỗ trợ nhập danh sách email**: Cho phép bạn nhập danh sách email cần đọc.
- **Nút chuyển giữa các email**: Tính năng cho phép chuyển đổi giữa các email để chọn email cần đọc.
- **Hiển thị 20 email mới nhất**: Hiển thị 20 email mới nhất từ hộp thư đến và thư rác.
- **Đọc email bằng Refresh Token**: Sử dụng Refresh Token qua OAuth2 để truy xuất các email từ Outlook.
- **Tương tác với nội dung email**: Bạn có thể sao chép nội dung văn bản của email hoặc truy cập các liên kết trong email theo ý muốn.

## Yêu Cầu

- **.NET 8.0 Desktop Runtime**: Trước khi chạy ứng dụng, bạn cần cài đặt .NET 8.0 Desktop Runtime. Bạn có thể tải về tại [đây](https://dotnet.microsoft.com/download/dotnet/8.0).
- **Windows OS**: Công cụ này được thiết kế để chạy trên hệ điều hành Windows.

## Cách Cài Đặt

### Bước 1: Tải Công Cụ

1. Tải toàn bộ repository về máy

### Bước 2: Cài Đặt .NET 8.0 Desktop Runtime

Trước khi chạy ứng dụng, bạn cần cài đặt .NET 8.0 Desktop Runtime:

1. Truy cập [trang tải .NET 8.0 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0).
2. Chọn phiên bản tương ứng với hệ điều hành của bạn và làm theo hướng dẫn để cài đặt.

### Bước 3: Chạy Ứng Dụng

Sau khi cài đặt .NET 8.0 Desktop Runtime, bạn có thể chạy ứng dụng `ReadEmail`:

1. Mở thư mục chứa file `ReadEmail.exe`.
2. Chạy `ReadEmail.exe` trực tiếp bằng cách nhấp đôi chuột vào file.

### Bước 4: Tương Tác với Nội Dung Email

Sau khi ứng dụng tải danh sách các email:

- Bạn có thể chọn email cần đọc từ danh sách đã nhập.
- Ứng dụng sẽ hiển thị các thông tin chi tiết của email, cho phép bạn sao chép nội dung văn bản hoặc truy cập các liên kết có trong email.

### Cài Đặt .NET SDK

1. Tải và cài đặt .NET SDK 8.0 tại [đây](https://dotnet.microsoft.com/download/dotnet/8.0).
2. Kiểm tra cài đặt .NET SDK bằng cách chạy lệnh sau trong Command Prompt hoặc Terminal:
   ```bash
   dotnet --version
