# Thực hành: Xây dựng bố cục trang web với CSS Grid

## Nội dung
- `index.html`: cấu trúc trang gồm Header, Sidebar, Main Content và Footer.
- `style.css`: bố cục CSS Grid dùng `grid-template-columns`, `grid-template-rows` và `grid-template-areas`.
- `screenshots/`: ảnh kết quả desktop, tablet và mobile.

## Chạy bài
1. Tải các tệp về cùng một thư mục.
2. Mở `index.html` bằng trình duyệt.
3. Thu nhỏ cửa sổ hoặc dùng DevTools để kiểm tra ở màn hình mobile.

## Kỹ thuật sử dụng
- Desktop: 2 cột theo tỷ lệ `1fr 3fr`, Sidebar nằm cạnh Main Content.
- Mobile (màn hình rộng tối đa 768px): chuyển thành một cột theo thứ tự Header, Sidebar, Main Content, Footer.
- Sử dụng Media Queries để điều chỉnh khoảng cách, thẻ nội dung và điều hướng trên màn hình nhỏ.

## Nộp bài lên GitHub
Tạo repository mới, tải lên `index.html`, `style.css`, thư mục `screenshots` và `README.md`, sau đó commit changes và nộp đường dẫn repository.
