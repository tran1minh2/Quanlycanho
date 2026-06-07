# 📁 CẤU TRÚC THƯ MỤC DỰ ÁN (QUẢN LÝ CĂN HỘ)

```text
Quanlycanho/
├── database/
│   └── apartment_db.sql               <-- File script tạo cơ sở dữ liệu MSSQL
│
├── diagrams/
│   ├── activity_diagram.png           <-- Biểu đồ hoạt động hệ thống
│   ├── anh.docx                       <-- Tài liệu hình ảnh đi kèm
│   ├── lab3ve.eap                     <-- File thiết kế Enterprise Architect
│   └── nhanvienbosung.EAP             <-- Bản vẽ sơ đồ nhân viên bổ sung
│
├── docs/
│   └── NHOM2_QUANLYCANHO_SD2011_GD2.docx <-- Báo cáo / Tài liệu dự án Giai đoạn 2
│
└── src/
    ├── backend/                       <-- Mã nguồn xử lý Logic / API
    │   ├── config/
    │   │   └── db.js                  <-- Kết nối cơ sở dữ liệu
    │   ├── routes/
    │   │   ├── auth.js                <-- Xử lý Đăng nhập / Đăng ký
    │   │   ├── properties.js          <-- Quản lý căn hộ
    │   │   ├── bookings.js            <-- Quản lý đặt phòng
    │   │   └── users.js               <-- Quản lý người dùng
    │   ├── server.js                  <-- File chạy chính của Backend
    │   └── package.json
    │
    └── frontend/                      <-- Giao diện người dùng (UI)
        ├── public/
        │   └── index.html
        └── src/
            ├── components/            <-- Các thành phần giao diện dùng chung
            │   ├── Header.jsx
            │   ├── Footer.jsx
            │   ├── SearchBox.jsx
            │   └── PropertyCard.jsx
            ├── pages/                 <-- Các trang giao diện lớn
            │   ├── HomePage.jsx
            │   ├── SearchPage.jsx
            │   └── LoginPage.jsx
            ├── App.js
            └── index.js
