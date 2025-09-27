# Simple Auth

Một project mẫu nhỏ chứa hai ví dụ xác thực bằng Node.js:

- `basic_auth.js` - ví dụ xác thực HTTP Basic.
- `cookie_auth.js` - ví dụ xác thực dựa trên cookie.

## Yêu cầu

- Node.js v14+ (khuyến nghị v16+)
- npm (đi kèm Node.js)

## Cài đặt

Mở terminal tại thư mục project và chạy:

```powershell
npm install
```

> Nếu repository không có `package.json` hoặc phụ thuộc, hãy thêm các package cần thiết theo nhu cầu.

## Chạy ví dụ

Chạy `basic_auth.js`:

```powershell
node basic_auth.js
```

Chạy `cookie_auth.js`:

```powershell
node cookie_auth.js
```

## Nội dung tệp

- `basic_auth.js`:
  - Triển khai HTTP server đơn giản (ví dụ dùng `http` hoặc `express`) với xác thực Basic.
  - Kiểm tra header `Authorization` và so sánh với username/password.

- `cookie_auth.js`:
  - Triển khai session/cookie-based authentication.
  - Thiết lập cookie sau khi đăng nhập và kiểm tra cookie cho các route cần bảo vệ.

