# Portfolio - Vũ Mỹ Anh Thư

Digital portfolio cho môn **Nhập môn Công nghệ số và Ứng dụng Trí tuệ nhân tạo**.

- Sinh viên: Vũ Mỹ Anh Thư
- MSV: 25042594
- Ngành: Ngôn ngữ & Văn hóa Hàn Quốc
- Trường: Đại học Ngoại ngữ - ĐHQGHN

## Art direction

Website được redesign theo concept **Mint Hanji Editorial**: cảm hứng từ giấy Hanji, sổ tay học ngoại ngữ, Korean stationery và bố cục editorial journal hiện đại.

## Cấu trúc

```text
index.html          Một chút về mình
projects.html       Trang Dự án, có bộ lọc 6 bài tập
conclusion.html     Trang Tổng kết
contact.html        Trang Liên hệ
detail.html         Trang chi tiết bài tập
styles.css          Design system, layout, responsive
script.js           Menu mobile, reveal, filter dự án
detail.js           Dữ liệu và render trang chi tiết
assets/brand/       Logo ULIS dùng trong header
assets/evidence/    Ảnh minh chứng trích xuất từ PDF
File bài tập/       PDF bài tập và ảnh chân dung
```

## Cách chạy

Mở trực tiếp `index.html` bằng trình duyệt, hoặc chạy một server tĩnh bất kỳ tại thư mục này.

```bash
npx serve .
```

## Deploy GitHub Pages

1. Push toàn bộ thư mục này lên GitHub.
2. Vào **Settings → Pages**.
3. Chọn **Deploy from a branch**.
4. Chọn branch `main` và folder `/root`.
5. Lưu lại, đợi GitHub Pages build xong và mở link được cấp.

Site không cần build, không dùng đường dẫn Windows local và các asset/PDF đều dùng relative path để phù hợp GitHub Pages.
