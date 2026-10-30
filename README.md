# 💎 TonPawn

Phần mềm quản lý tiệm cầm đồ chạy trên Windows: hợp đồng cầm cố tài sản, cầm giấy tờ, tính lãi, chuộc, thanh lý, sổ quỹ và báo cáo lời lỗ.

[⬇️ Tải bản mới nhất](https://github.com/manhbui0811/tonpawn/releases/latest/download/TonPawn.exe) · [Tất cả phiên bản](https://github.com/manhbui0811/tonpawn/releases) · [Trang giới thiệu](https://manhbui0811.github.io/TonSoft/#TonPawn)

## Tính năng
- Hợp đồng cầm cố tài sản: lưu nháp, lập hợp đồng, nhân bản, chuộc, thanh lý
- Cầm giấy tờ bằng biên lai riêng, dùng chung cách tính lãi
- Danh mục loại tài sản tự đặt, mỗi loại có các trường thông tin riêng
- Tính lãi tự động (lãi đơn, một tháng 30 ngày, làm tròn lên 1.000đ), sửa được lãi thực thu khi chuộc
- Lời lỗ thanh lý tính theo cả vòng đời hợp đồng
- Hồ sơ khách hàng kèm ảnh căn cước
- Thư viện ảnh, chọn nhiều ảnh và in lên giấy A4
- Sổ quỹ thu chi, báo cáo lãi lỗ có đối chiếu sổ quỹ, màn Tổng quan có hợp đồng đến hạn và quá hạn
- Xuất Excel, xuất sổ doanh thu theo mẫu hộ kinh doanh (Word)
- Tài khoản nhân viên và chủ tiệm, phân quyền

## Yêu cầu
- Windows 10 hoặc 11, 64-bit
- RAM từ 4 GB, trống khoảng 500 MB ổ cứng, thêm dung lượng cho thư mục ảnh
- Microsoft Edge WebView2 Runtime (Windows 11 và hầu hết Windows 10 đã có sẵn; nếu máy báo thiếu, tải tại https://developer.microsoft.com/microsoft-edge/webview2/)

## Cách dùng
TonPawn là một file `.exe` duy nhất, không cần cài .NET.
1. Tải file `TonPawn.exe`.
2. Đặt file vào một thư mục riêng, ví dụ `C:\TonPawn\`.
3. Mở file. Nếu Windows báo chặn, chọn **Thông tin thêm → Vẫn chạy**.
4. Lần đầu mở, khai báo tài khoản quản trị. Bạn có thể chọn nạp dữ liệu mẫu để làm quen, sau đó tự tạo danh mục loại tài sản theo tiệm của mình.

## Dữ liệu của bạn
- Mặc định dữ liệu nằm ngay cạnh file exe, trong thư mục `TonPawn\` gồm file cơ sở dữ liệu `pawn.db` và thư mục ảnh `Images\`. Nếu thư mục chứa exe không ghi được, phần mềm dùng thư mục dữ liệu của Windows.
- Muốn đổi nơi lưu: vào **Cấu hình → Ứng dụng → Thông tin chung** và dùng nút đổi đường dẫn. Dữ liệu và ảnh được chép sang nơi mới, có hiệu lực sau khi mở lại phần mềm.
- Phần mềm **không tự sao lưu**. Hãy sao lưu định kỳ ở **Cấu hình → Ứng dụng → Thông tin chung**. Mất máy hoặc hỏng ổ cứng mà chưa sao lưu là mất dữ liệu.
- Sao lưu và khôi phục chỉ gồm file cơ sở dữ liệu, **không gồm thư mục `Images\`** (ảnh căn cước, tài sản, giấy tờ). Hãy chép thư mục `Images\` riêng, lưu ra ổ khác hoặc ổ đĩa ngoài.
- Nâng cấp phiên bản mới: thoát phần mềm, chép file exe mới đè lên file cũ trong cùng thư mục, giữ nguyên thư mục dữ liệu.
- Phần mềm chỉ chạy trên máy đã cài. Chưa hỗ trợ mở từ điện thoại hay từ máy khác trong mạng.

## Kiểm tra file tải về
Mã SHA256 nằm trong phần mô tả của mỗi bản phát hành. Kiểm tra bằng PowerShell:

```
certutil -hashfile TonPawn.exe SHA256
```

## Báo lỗi và góp ý
Mở tab **Issues** của repo này, mô tả lỗi và đính kèm ảnh chụp màn hình. Không đăng ảnh căn cước hay thông tin cá nhân của khách lên Issues.

## Liên hệ
Zalo / điện thoại: 09740413209 · Email: manhbui0811@gmail.com
