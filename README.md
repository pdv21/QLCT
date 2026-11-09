# Gọn Chi

Ứng dụng quản lý thu chi cá nhân bằng tiếng Việt, dùng VND và có thể chạy offline trong trình duyệt.

## Dùng offline

Mở `index.html` bằng Chrome, Edge hoặc Firefox. Giao dịch, ngân sách và mục tiêu được lưu trong vùng lưu trữ của trình duyệt đang dùng trên máy đó. Dữ liệu không được mã hóa, không gửi lên GitHub và không đồng bộ giữa thiết bị. Hãy tải bản sao lưu JSON trong phần **Cài đặt** trước khi xóa dữ liệu trình duyệt hoặc chuyển máy.

## Deploy lên GitHub Pages

Workflow tại `.github/workflows/pages.yml` xuất bản `index.html` mỗi khi có thay đổi trên nhánh `main`.

1. Mở repository trên GitHub, vào **Settings → Pages**.
2. Trong **Build and deployment**, chọn **GitHub Actions** làm nguồn deploy.
3. Đẩy commit lên `main`; theo dõi workflow **Deploy Gọn Chi to GitHub Pages** trong tab **Actions**.
4. Trang sẽ có địa chỉ `https://pdv21.github.io/QLCT/` sau khi deployment hoàn tất.

Khi chuyển từ tệp offline sang địa chỉ web, vùng lưu của trình duyệt khác nhau. Xuất JSON từ bản offline rồi nhập vào bản web nếu muốn giữ dữ liệu.
