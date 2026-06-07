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
│   ├── NHOM2_QUANLYCANHO_SD2011_GD2.docx <-- Báo cáo / Tài liệu dự án Giai đoạn 2
│   └── lab8.docx                         <-- Tài liệu hoặc bài tập Lab 8 mới thêm
│
└── src/
    ├── backend/                       <-- Node.js + Express API
    │   ├── config/
    │   │   └── db.js                  <-- Kết nối MSSQL
    │   ├── routes/
    │   │   ├── auth.js                <-- Đăng nhập / Đăng ký / Session
    │   │   ├── properties.js          <-- Tìm kiếm & chi tiết căn hộ
    │   │   ├── bookings.js            <-- Đặt phòng
    │   │   └── users.js               <-- Quản lý users (admin)
    │   ├── server.js                  <-- Entry point Express
    │   └── package.json
    │
    └── frontend/                      <-- React App
        ├── public/
        │   └── index.html
        └── src/
            ├── components/            <-- Các thành phần giao diện dùng chung
            │   ├── Header.jsx         <-- Header + Nav + User dropdown
            │   ├── Header.css
            │   ├── Footer.jsx         <-- Footer 5 cột
            │   ├── Footer.css
            │   ├── SearchBox.jsx      <-- Ô tìm kiếm (city + date + guests)
            │   ├── SearchBox.css
            │   ├── PropertyCard.jsx   <-- Card căn hộ (grid/list)
            │   └── PropertyCard.css
            ├── pages/                 <-- Các trang giao diện lớn
            │   ├── HomePage.jsx       <-- Trang chủ (hero + featured)
            │   ├── HomePage.css
            │   ├── SearchPage.jsx     <-- Trang tìm kiếm + bộ lọc
            │   ├── SearchPage.css
            │   ├── LoginPage.jsx      <-- Đăng nhập + Đăng ký
            │   └── LoginPage.css
            ├── App.js                 <-- Router + AuthContext
            ├── index.js
            ├── index.css              <-- CSS variables (màu Agoda)
            └── package.json
