# ToolHub — bản phát hành

Kho này **chỉ chứa gói cài đặt và gói cập nhật** của phần mềm nội bộ ToolHub.
Không có mã nguồn.

## Cài lần đầu (nhân viên mới nhận máy)

Tải file **`_BANGIAO_ToolHub_v*.zip`** ở [bản phát hành mới nhất](../../releases/latest)
→ giải nén ra ổ đĩa → mở thư mục `thanhthao\` → chạy `thanhthao.exe`.

- Mật khẩu đăng nhập: `123456` (đổi trong tab Cài đặt)
- **Đừng để trong `C:\Program Files`** — Windows chặn ghi, app sẽ không lưu được
  dữ liệu và không tự cập nhật được. Nên để `D:\ToolHub` hoặc Desktop.
- Đọc file `DOC-TRUOC-KHI-DUNG.txt` kèm trong gói.

Chỉ phải làm **một lần duy nhất**. Từ đó về sau app tự cập nhật.

## Cập nhật (tự động)

App tự kiểm tra bản mới mỗi lần mở, thấy có thì hiện nút **"Có bản mới"** ở góc trên
— bấm là app tự tải, tự thay, tự khởi động lại. Gói cập nhật chỉ vài MB chứ không
phải tải lại cả bộ, và **không đụng vào dữ liệu** (luôn sao lưu trước khi thay).

Nếu app chưa tự kiểm tra, vào **Cài đặt → Phiên bản & cập nhật** dán địa chỉ này:

```
https://github.com/nguyenbichwork-hue/toolhub-releases/releases/latest/download/manifest.json
```

## Mỗi bản phát hành gồm

| Tệp | Dùng khi | Dung lượng |
|---|---|---|
| `_BANGIAO_ToolHub_v*.zip` | cài lần đầu trên máy mới | ~540 MB |
| `ToolHub_CapNhat_v*.zip` | app tự tải để cập nhật | 1,5 – 31 MB |
| `manifest.json` | app đọc để biết có bản mới không | vài KB |

Gói cập nhật **không bao giờ chứa dữ liệu** của máy nào — dữ liệu nằm trong
`thanhthao\data\` và `thanhthao\DuLieu\`, bộ cập nhật không đụng tới.
