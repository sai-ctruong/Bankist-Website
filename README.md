# 🏦 Project: "Bankist" Website (Landing Page)

Project này là một màn trình diễn thực tế về sức mạnh của JavaScript DOM nâng cao. Từ một trang HTML/CSS tĩnh, project này "thổi hồn" vào giao diện, triển khai các kỹ năng UI hiện đại nhất:

Tối ưu hiệu năng với Lazy Loading Images.

Hiệu ứng "Reveal-on-Scroll" mượt mà.

Sticky Navigation (Menu dính) và Smooth Scrolling (Cuộn mượt).

## Tất cả được xây dựng bằng IntersectionObserver API và JavaScript thuần.

## 🚀 Live Demo

Bạn có thể trải nghiệm trang web trực tiếp tại đây:
**👉 [Xem Demo Trực Tiếp!](https://sai-ctruong.github.io/Bankist-Website/)**

---

## 🛠️ Kỹ Năng & Tính Năng Nổi Bật

Toàn bộ code trong `script.js` được sử dụng để triển khai các tính năng sau từ một trang HTML/CSS tĩnh:

- **🖱️ Cuộn Mượt (Smooth Scrolling):**

  - Triển khai cho nút "Learn More" (dùng `scrollIntoView`) và các link trên menu (dùng kỹ thuật **Event Delegation** để tối ưu hiệu năng).

- **✨ Menu Cố Định (Sticky Navigation):**

  - Sử dụng **`IntersectionObserver API`** (API Quan sát Giao lộ) để menu tự động dính (sticky) vào top màn hình khi cuộn qua header, một cách hiệu quả nhất.

- **💨 Hiệu Ứng Menu Mờ Dần (Fade Animation):**

  - Tạo hiệu ứng mờ (fade) cho các link "anh em" và logo khi người dùng di chuột (hover) vào một link, sử dụng kỹ thuật `bind(this)` để truyền giá trị `opacity`.

- **🧩 Component Tab (Tabbed Component):**

  - Xây dựng một component tab (ở mục "Operations") hoàn toàn bằng JavaScript, cho phép chuyển đổi nội dung tương ứng khi bấm vào tab.

- **⬆️ Hiệu Ứng Hiện Ra Khi Cuộn (Reveal Sections):**

  - Dùng **`IntersectionObserver API`** để các `section` (khu vực) của trang web mờ dần và trượt lên một cách mượt mà khi người dùng cuộn trang đến gần chúng.

- **🖼️ Tải Ảnh Lười (Lazy Loading Images):**

  - Tối ưu hiệu năng tải trang. Các ảnh chất lượng cao chỉ được tải khi người dùng cuộn đến gần. Ảnh mờ (placeholder) được hiển thị trước, sau đó được thay thế mượt mà (dùng `data-src` và class `lazy-img`).

- **🎠 Thanh Trượt (Slider/Carousel Component):**

  - Xây dựng một component slider/carousel (ở mục "Testimonials") hoàn chỉnh từ đầu, bao gồm các chức năng:
    - Nút qua trái/phải.
    - Các nút chấm (dots) điều hướng.
    - Hỗ trợ sự kiện bấm phím (mũi tên trái/phải).

- **팝 Cửa Sổ Modal (Modal Window):**
  - Xây dựng cửa sổ pop-up (modal) để đăng ký tài khoản, có thể đóng bằng nút "X", bấm ra ngoài (overlay), hoặc bấm phím `Esc`.

---

## 💻 Cách Chạy Project

Đây là một dự án tĩnh (HTML, CSS, JS). Bạn chỉ cần tải về và mở file `index.html` bằng trình duyệt (hoặc dùng extension **Live Server** của VS Code).

---

## 🧑‍💻 Tác giả

* **Phạm Công Trường** - [SaiCTruong](https://github.com/sai-ctruong)

---

## 🏁 Giấy phép

Dự án được sử dụng **phi thương mại** cho **mục đích học tập và nghiên cứu**.  

