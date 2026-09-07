# 💻 Chapter 20 — System Console

> *"Để lại quá khứ phía sau, sống vui vẻ ở hiện tại và thức giấc vào ngày mai."*

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge&logo=githubpages)](https://aominhtam.github.io/Chapter_20_for_me/)
[![Release](https://img.shields.io/badge/Release-v20.0-blue?style=for-the-badge&logo=git)](https://github.com/AOMINHTAM/Chapter_20_for_me)
[![Status](https://img.shields.io/badge/Status-200_OK-success?style=for-the-badge)]()

A lightweight, interactive Web-based Terminal Console built to commemorate the **Chapter 20 (v20.0)** milestone. Instead of a traditional greeting post, this project turns birthday wishes and photo reveals into a CLI-inspired experience.

---

## ⚡ Live Preview

Truy cập trực tiếp tại: **[https://aominhtam.github.io/Chapter_20_for_me/](https://aominhtam.github.io/Chapter_20_for_me/)**

---

## 🚀 Key Features

* **Terminal UI & Boot Sequence:** Giả lập terminal bash với hiệu ứng khởi động hệ thống (`kernel modules`, `dependencies check`, v.v.).
* **Interactive CLI Commands:**
  * `help`: Liệt kê tất cả các lệnh khả dụng trong hệ thống.
  * `story`: Đọc thông điệp và nhật ký đánh dấu cột mốc Chapter 20.
  * `photo`: Tự động tải và hiển thị bộ ảnh cosplay Sunday dưới dạng lưới gallery (`grid layout`).
  * `wish`: Luồng hội thoại tương tác cho phép người xem nhập tên/biệt danh và gửi lời chúc trực tiếp.
  * `sunday`: Easter Egg đặc biệt dành riêng cho concept.
  * `clear`: Dọn sạch màn hình console.
* **Serverless Backend (Google Sheets Webhook):** Tích hợp Google Apps Script Webhook để lưu trữ thời gian thực (`Timestamp`, `Sender`, `Message`) vào Google Sheets qua `FormData`.

---

## 🛠 Tech Stack

* **Frontend:** HTML5, CSS3 (Modern Flexbox & Grid), Vanilla JavaScript.
* **Hosting / Deployment:** GitHub Pages.
* **Data Storage / Pipeline:** Google Apps Script (`doPost`), Google Sheets API (Serverless Webhook).

---

## 📂 Project Structure

```text
Chapter_20_for_me/
├── index.html          # UI Terminal, logic tương tác CLI & Webhook
├── DS302048.jpg        # Asset ảnh cosplay
├── DS302149.jpg        # Asset ảnh cosplay
├── DS302176.jpg        # Asset ảnh cosplay
└── README.md           # Tài liệu dự án
