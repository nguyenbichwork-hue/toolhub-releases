# ToolHub — bản phát hành

Kho này **chỉ chứa gói cập nhật** của phần mềm nội bộ ToolHub. Không có mã nguồn.

App tự đọc `manifest.json` của bản phát hành mới nhất rồi tự tải và cập nhật —
nhân viên không cần vào đây tải tay.

Địa chỉ cập nhật điền trong app (Cài đặt → Phiên bản & cập nhật):

```
https://github.com/nguyenbichwork-hue/toolhub-releases/releases/latest/download/manifest.json
```

Mỗi bản phát hành gồm:

| Tệp | Nội dung |
|---|---|
| `manifest.json` | số phiên bản, ghi chú, dung lượng, mã kiểm tra SHA-256 |
| `ToolHub_CapNhat_v*.zip` | phần thay đổi của app (giao diện, và exe nếu có sửa mã) |

Gói cập nhật **không bao giờ chứa dữ liệu** của máy nào — dữ liệu nằm trong thư mục
`data\` cạnh app và không bị bộ cập nhật đụng tới.
