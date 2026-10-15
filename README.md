# FixFlow - Điều phối yêu cầu bảo trì thiết bị

## 📄 Thông tin trang
* **Tên trang:** Trang 21 - Bảng phân công
* **Đề tài:** FixFlow - Hệ thống điều phối yêu cầu bảo trì thiết bị

---

## 🎯 Mục đích của trang
Trang **Bảng phân công** cung cấp một giao diện trực quan theo mô hình Kanban Board, giúp người điều phối (Dispatcher/Manager) dễ dàng quản lý, sắp xếp và phân công các ticket (yêu cầu bảo trì thiết bị) cho các kỹ thuật viên hoặc đội ngũ kỹ thuật một cách nhanh chóng và hiệu quả. Giao diện này cũng giúp theo dõi tiến độ xử lý của từng ticket cũng như tải công việc hiện tại của các kỹ thuật viên.

---

## ⚙️ Các chức năng chính

1. **Quản lý trạng thái Ticket (Kanban Board):**
   * **Chờ phân công:** Hiển thị danh sách các yêu cầu mới cần được phân công kỹ thuật viên (có gắn mức độ ưu tiên như *Khẩn*, *Cao* và thời gian SLA còn lại).
   * **Đã phân công – Đang chờ:** Các ticket đã được phân công nhưng kỹ thuật viên chưa bắt đầu thực hiện (có hiển thị mức độ ưu tiên như *Trung bình*, *Cao*).
   * **Đang xử lý:** Các ticket đang trong quá trình được kỹ thuật viên khắc phục, sửa chữa (có mức độ ưu tiên *Thấp* hoặc thông tin thời gian).

2. **Điều phối kéo thả (Drag & Drop):**
   * Cho phép người điều phối kéo và thả các ticket qua lại giữa các trạng thái hoặc gán trực tiếp cho đội ngũ kỹ thuật một cách mượt mà.

3. **Quản lý danh sách Đội kỹ thuật (Technicians Workload):**
   * Hiển thị danh sách các thành viên trong đội kỹ thuật (Ví dụ: *Trần Thị B*, *Le Quốc C*, *Hoàng Nam*).
   * Theo dõi trực quan thanh **Tải công việc (Workload)** tính theo phần trăm (%) của từng kỹ thuật viên để tránh quá tải công việc.

4. **Tìm kiếm và Lọc:**
   * Thanh tìm kiếm nhanh phía trên cho phép tra cứu ticket, thiết bị hoặc người dùng.
   * Nút **Làm mới (Refresh)** dữ liệu để cập nhật thông tin mới nhất từ hệ thống.

---

## 💻 Công nghệ đã sử dụng

* **Frontend:** 
  * HTML, CSS, JavaScript
  * Tailwind CSS (hoặc bộ CSS tương đương giúp xây dựng giao diện UI hiện đại, responsive)
* **Design & Prototyping:** 
  * Figma (dùng để thiết kế giao diện UI/UX)
* **Tools & Environment:**
  * Live Server (VS Code Extension) cho môi trường phát triển cục bộ

---

## Figma
https://www.figma.com/design/ZSMpHOH5EC4JlVNlwfqSmN/Untitled?node-id=0-1&t=Pq7d3kEyhOtyk8oB-1

---

## Youtube
https://youtu.be/G2XH-0OsCoo

---

## Github
https://github.com/haison19/baigiuaki

---
