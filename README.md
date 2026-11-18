# Hồ sơ đất đai – soạn đơn, tờ khai, niêm yết, trình cấp GCN

Công cụ chạy ngay trên trình duyệt (một file `index.html`, không cần cài đặt, không cần máy chủ). Nhập thông tin một lần, xuất ra các biểu mẫu Word (.docx):

- Mẫu 22, 22a, 22b – Đơn đăng ký đất đai, cấp GCN
- Mẫu 25 – Đơn đăng ký biến động
- 01/TK-SDDPNN, 01/LPTB, 03/BĐS-TNCN, 01/TSDĐ – Tờ khai thuế, lệ phí
- Bộ niêm yết: Thông báo, Danh sách công khai (Mẫu 17), Biên bản và Thông báo kết thúc niêm yết, Tờ trình cấp GCN, Phiếu trình

## Cách dùng chung (GitHub Pages)

1. Tạo repo mới trên GitHub (ví dụ `ho-so-dat-dai`), tải toàn bộ file trong thư mục này lên nhánh `main`.
2. Vào **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.
3. Sau 1–2 phút, mọi người mở link: `https://<tên-tài-khoản>.github.io/<tên-repo>/`

Cũng có thể tải `index.html` về và mở trực tiếp bằng Chrome/Edge, kể cả khi không có mạng.

## Lưu ý về dữ liệu cá nhân

- Toàn bộ xử lý diễn ra **trong trình duyệt của người dùng**; không có dữ liệu nào được gửi lên GitHub hay máy chủ nào khác.
- Hồ sơ và bản nháp được lưu trong `localStorage` của từng trình duyệt/máy, nên mỗi người chỉ thấy hồ sơ của mình. Muốn chuyển sang máy khác thì dùng nút **Xuất file / Nhập file** trong công cụ.
- **Không** commit file hồ sơ thật (có họ tên, CCCD, địa chỉ...) lên repo công khai. Repo chỉ nên chứa công cụ, không chứa dữ liệu.

## Cập nhật

Sửa trực tiếp `index.html` (mẫu Word được nhúng dạng base64 trong các hằng `TPL`, `TA`) rồi commit; GitHub Pages tự cập nhật.
