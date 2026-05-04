# Demo HTML/CSS/JS – Sổ tay ôn tập cho sinh viên năm 2

Đây là repo tổng hợp các bài thực hành HTML/CSS (và một phần JS/media) theo kiểu **học đến đâu làm đến đó**. README này được viết có thể:

- Nắm nhanh repo có gì.
- Mở đúng file để ôn đúng chủ đề.
- Ôn lại lý thuyết cốt lõi trước khi làm bài mới/phỏng vấn/thực hành.

---

## 1) Mục tiêu ôn tập

Sau khi ôn repo này, bạn nên làm được:

1. Dựng một trang tĩnh cơ bản bằng HTML semantic.
2. Style giao diện bằng CSS (box model, selector, pseudo-class).
3. Làm layout bằng `position`, `z-index`, grid/flex, responsive.
4. Tạo navbar, portfolio mini, sticky nav, và trang 404 đơn giản.
5. Biết tách file theo từng chủ đề để dễ bảo trì.

---

## 2) Cấu trúc repo & học gì ở từng thư mục

> Gợi ý: ôn theo đúng thứ tự từ trên xuống dưới.

### `image/`
Thư mục chứa nhiều file thực hành cơ bản đến trung bình:

- `index.html`, `index1.html` ... `index14.html`: các bài luyện HTML/CSS tổng hợp.
- `navbar.html` + `navbar.css`: bài luyện thanh điều hướng.
- `portfolio.html` + `portfolio.css`: bài luyện trang portfolio đơn giản.
- `aboutMeSkill.html` + `aboutMeSkill.css`, `listMySkill.html` + `listmeSkill.css`: bài luyện nội dung giới thiệu và danh sách kỹ năng.
- `practice.html`, `practice1.html`, `reworkpractice.html`: các bài làm lại để củng cố.
- Có cả media (`.png`, `.mp4`, `.mp3`) để thử nhúng ảnh/video/audio.

### `week2/`
Tập trung vào các chủ đề hay gặp ở tuần 2 của môn Web cơ bản:

- `Position.html` + `Position.css`: `static`, `relative`, `absolute`, `fixed`, `sticky`.
- `Z_index.html` + `Z_index.css`: hiểu thứ tự chồng lớp.
- `PseudoClass.html` + `PseudoClass.css`: `:hover`, `:active`, `:focus`, ...
- `3layoutGrid.html` + `3layoutGrid.css`: bố cục với Grid.
- `responsiveLayout.html` + `responsiveLayout.css`, `mobile.html` + `mobile.css`: responsive và media queries.
- `porfolioResponsive.html` + `porfolioResponsive.css`: kết hợp portfolio + responsive.

### `MyPorfolio/`
- `Portfolio.html` + `Portfolio.css`: phiên bản portfolio riêng, nên dùng để ôn bài mini-project.

### `Sticky/`
- `stickyNav.html` + `stickyNav.css`: luyện riêng sticky navigation.

### `rework/`
- `basic.html`, `nav1.html`, `nav1.css`: các bài refactor/làm lại kiến thức nền.

### `animation /`
- `notFound404.html` + `notFound404.css`: thực hành trang lỗi 404 và hiệu ứng cơ bản.

> Lưu ý: thư mục này có tên chứa dấu cách (`animation `), khi thao tác terminal nhớ đặt trong dấu nháy kép.

---


## 3) Checklist kiến thức cần nhớ trước thi/thực hành

- [ ] Phân biệt được block vs inline vs inline-block.
- [ ] Giải thích được box model và `box-sizing: border-box`.
- [ ] Dùng được `position` + `z-index` đúng ngữ cảnh.
- [ ] Biết tạo navbar cơ bản và trạng thái hover.
- [ ] Biết dùng pseudo-class thông dụng.
- [ ] Biết dựng layout bằng Grid/Flex.
- [ ] Biết responsive với media query.
- [ ] Biết tách HTML/CSS theo module nhỏ.

---

## 4) Cách chạy nhanh trong máy local

Vì đây chủ yếu là file tĩnh, bạn có thể chạy theo 1 trong 2 cách:

### Cách 1: Mở trực tiếp file `.html`
- Double click file HTML để mở bằng trình duyệt.

### Cách 2 (khuyến nghị): dùng Live Server (VS Code)
1. Cài extension **Live Server**.
2. Chuột phải vào file HTML (ví dụ `week2/responsiveLayout.html`).
3. Chọn **Open with Live Server**.

---

## 5) Mẹo học hiệu quả cho sinh viên năm 2

1. **Đừng chỉ đọc code** → hãy sửa code rồi reload ngay để thấy khác biệt.
2. Mỗi buổi chỉ tập trung 1 chủ đề lớn (vd: chỉ Position).
3. Sau mỗi bài, tự viết 3 dòng ghi nhớ: "Hôm nay mình hiểu gì?".
4. Khi bí layout, phác thảo khung trên giấy trước khi code.
5. Ưu tiên code sạch, đặt class có nghĩa thay vì class khó hiểu.

---

## 6) Bài tập tự luyện thêm (nên làm)

- Tạo trang CV 1 trang responsive hoàn chỉnh.
- Tạo navbar có menu mobile (hamburger).
- Làm 1 landing page đơn giản với 3 section:
  - Hero
  - Features
  - Contact
- Tạo trang 404 đẹp hơn từ `animation /notFound404.*`.

---

## 7) Định hướng lên năm 3 (nên chuẩn bị từ bây giờ)

Sau khi chắc HTML/CSS, bạn nên học tiếp theo thứ tự:

1. JavaScript DOM + Event.
2. ES6+ (`let/const`, arrow function, map/filter, module).
3. Git/GitHub workflow chuẩn.
4. 1 framework frontend (React là lựa chọn phổ biến).
5. Cơ bản về API/JSON và deploy web tĩnh.

---

