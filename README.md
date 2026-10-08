# Hành Trình Tìm Bố Mẹ – Game Toán lớp 5

Game pixel: cô bé chạy qua 10 chặng toán, nhận món ăn/đồ dùng Việt Nam để đánh zombie và tìm bố mẹ.

## Đưa lên GitHub Pages (không cần cài gì, làm trên trình duyệt)

1. Đăng nhập github.com, bấm dấu **+** ở góc phải trên, chọn **New repository**.
2. Đặt tên repository, ví dụ `tim-bo-me`. Chọn **Public**. Bấm **Create repository**.
3. Ở trang repository mới, bấm **uploading an existing file**.
4. Giải nén file zip, mở thư mục, chọn **tất cả file và thư mục bên trong** (`index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll`, thư mục `icons`) rồi kéo thả vào trang GitHub. Thư mục `icons` phải được tải lên cùng các file bên trong.
   Nếu máy không hiện file `.nojekyll` (file ẩn), có thể bỏ qua, game vẫn chạy.
5. Kéo xuống, bấm **Commit changes**.
6. Vào **Settings** → **Pages**. Ở mục **Build and deployment**, chọn **Source: Deploy from a branch**, **Branch: main**, thư mục **/ (root)**, rồi bấm **Save**.
7. Đợi 1–2 phút. Tải lại trang Pages, GitHub sẽ hiện link dạng
   `https://TEN-CUA-BAN.github.io/tim-bo-me/`

## Cài thành app trên điện thoại Android

1. Mở link trên bằng **Chrome** và đợi trang tải xong (lần đầu cần có mạng).
2. Bấm menu **⋮** → **Thêm vào màn hình chính** (hoặc **Cài đặt ứng dụng**) → **Cài đặt**.
3. Biểu tượng cô bé xuất hiện trên màn hình chính. Mở lên là chơi toàn màn hình, chiều ngang, và chơi được cả khi không có mạng.

## Cập nhật game về sau

Tải lại các file mới lên repository (bấm **Add file** → **Upload files**, ghi đè file cũ). Nếu điện thoại vẫn hiện bản cũ, đổi `tim-bo-me-v1` trong `sw.js` thành `tim-bo-me-v2` rồi tải lên.
