# M-DataPlus

<p align="center">
  <img src="https://github.com/anhnvt4620/M-DataPlus/blob/master/favicon.svg" width="128" alt="M-DataPlus Logo" />
</p>

<p align="center">
  <strong>Professional Database IDE for SQL Server & PostgreSQL — Fast, Smart, and Intuitive.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-blue?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/Database-SQL%20Server%20%7C%20PostgreSQL-orange?style=flat-square" alt="Databases">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License">
</p>

---

## 🚀 Tải về (Download)

| Phiên bản | Liên kết tải xuống | Yêu cầu hệ thống |
| :--- | :--- | :--- |
| **v1.1.1 (Latest)** | [**M-DataPlus Setup 1.1.0.exe**](https://github.com/anhnvt4620/M-DataPlus/releases/download/v1.1.1/M-DataPlus.Setup.1.1.1.exe) | Windows 10/11 (Không cần cài thêm .NET) |

---
**KEY TRIAL : LIC-DF82D629F140CBD53282EBCAA3F197BC02FE8214**
## ✨ Tính năng nổi bật

### 📝 SQL Editor thông minh
* **IntelliSense thế hệ mới:** Tự động gợi ý chính xác keyword, bảng, view, procedure và column.
* **Frequency Ranking:** Thuật toán thông minh tự động ưu tiên các gợi ý bạn thường xuyên sử dụng nhất.
* **FK JOIN Suggestion:** Tự động sinh điều kiện `ON` dựa trên Foreign Key khi viết câu lệnh `JOIN`.
* **Dot-completion:** Gõ `dbo.` hoặc schema name để liệt kê ngay các object thuộc schema đó.
* **Smart ALTER:** Gõ `ALTER VIEW name` để tự động load định nghĩa hiện tại của view.
* **Snippets tiện lợi:** Hỗ trợ phím tắt và placeholder `${1:Table}` giúp gõ code nhanh chóng.

### 🌳 Object Explorer trực quan
* Quản lý cây thư mục cấu trúc rõ ràng: Tables, Views, Synonyms, Procedures, Functions.
* **Pin Database:** Ghim các database thường xuyên làm việc lên trên cùng.
* **Smart Filter:** Bộ lọc tìm kiếm object nhanh, tự động mở rộng (expand) cây thư mục đến kết quả.
* **Phím tắt điều hướng nhanh:** 
  * `F12`: Định vị nhanh object trong cây thư mục từ vị trí con trỏ code.
  * `Shift+F12`: Tìm kiếm tất cả các reference liên quan.
* **Quick Scripting:** Chuột phải để sinh nhanh các mẫu câu lệnh `CREATE`, `SELECT`, `INSERT`, `UPDATE`, `DELETE`.

### 📊 Data Grid & Biên tập dữ liệu
* **Inline Editing:** Chỉnh sửa dữ liệu trực tiếp trên lưới (INSERT/UPDATE/DELETE) kèm cơ chế `Commit` / `Discard` an toàn.
* **Form Inspector:** Chế độ xem chi tiết từng dòng dữ liệu theo dạng form dọc.
* **Tối ưu hiển thị:** Hỗ trợ ẩn/hiện cột (Column picker) và phân trang mượt mà ở phía client (Client-side paging).
* **Xuất dữ liệu linh hoạt:** Export nhanh ra các định dạng CSV, JSON hoặc sao chép dưới dạng câu lệnh `SQL INSERT`.

### 🎨 SQL Formatting chuyên nghiệp
* Tích hợp bộ engine format SQL mạnh mẽ với **11 tùy chọn chuyên sâu** (theo phong cách RedGate SQL Prompt).
* Cấu hình linh hoạt: Chỉnh sửa chuẩn hóa keyword case, identifier case, indent style, expression width...
* Phím tắt tiện lợi: `Ctrl+Shift+F` (Format toàn bộ) hoặc `Ctrl+K, Ctrl+F` (Format vùng chọn).

### 📈 Execution Plan (Kế hoạch thực thi)
* Trực quan hóa kế hoạch thực thi dưới dạng cây sơ đồ với các biểu tượng và màu sắc trực quan cho từng toán tử (operator).
* **Cost Bar:** Hiển thị thanh tiến trình trực quan hóa "độ nặng" (chi phí tài nguyên) của từng operator.
* Hỗ trợ đóng/mở (expand/collapse) các nhánh và bảng chú giải (Legend) chi tiết.

### 🔗 Quản lý đa kết nối (Multi-Connection)
* Kết nối và làm việc với nhiều server cùng lúc, chuyển đổi mượt mà qua Sidebar.
* **Test Connection:** Kiểm tra trạng thái kết nối nhanh mà không cần khởi tạo session làm việc thực tế.
* **Tab Coloring:** Đổi màu tab theo môi trường (Ví dụ: DEV màu xanh, PROD màu đỏ) giúp nhận diện trực quan.

### 🛡️ Tính năng an toàn (Safety)
* **Cảnh báo nguy hiểm:** Tự động đưa ra cảnh báo khi phát hiện lệnh `DELETE` hoặc `UPDATE` thiếu mệnh đề `WHERE`.
* **Error Boundary:** Cơ chế cô lập lỗi thông minh, đảm bảo ứng dụng không bị crash trắng màn hình khi gặp sự cố đột ngột.

### 🎨 Giao diện (Themes)
Hỗ trợ 7 theme màu phong phú, phù hợp với mọi không gian làm việc: `Light`, `Dark+`, `Monokai`, `Solarized`, `High Contrast`, `Midnight`, `Ocean`.

---

## ⌨️ Hệ thống phím tắt

| Phím tắt | Chức năng |
| :--- | :--- |
| **Thực thi & Điều hướng** | |
| `F5` / `Ctrl+Enter` | Thực thi câu lệnh SQL (Execute query) |
| `Ctrl+R` | Ẩn/Hiện bảng kết quả (Toggle Results) |
| `Ctrl+L` | Xem kế hoạch thực thi (Execution Plan) |
| `F12` | Đi đến định nghĩa (Go to Definition) |
| `Shift+F12` | Tìm các liên kết/tham chiếu (Find References) |
| **Biên tập Code** | |
| `Ctrl+Shift+F` | Định dạng toàn bộ tài liệu (Format document) |
| `Ctrl+K, Ctrl+F` | Định dạng vùng chọn (Format selection) |
| `Ctrl+K, Ctrl+C` / `Ctrl+K, Ctrl+U` | Comment / Uncomment dòng code |
| `Ctrl+Shift+U` / `Ctrl+Shift+L` | Chuyển chữ Hoa (Uppercase) / Chữ thường (Lowercase) |
| **Hệ thống** | |
| `Ctrl+N` | Mở tab truy vấn mới (New Query) |
| `Ctrl+P` | Mở thanh lệnh hệ thống (Command Palette) |
| `Ctrl+B` | Ẩn/Hiện thanh Sidebar |

---

## 🗄️ Cơ sở dữ liệu hỗ trợ

* **Microsoft SQL Server:** Hỗ trợ cả hai chế độ xác thực Windows Authentication và SQL Server Authentication.
* **PostgreSQL:** Hỗ trợ đầy đủ kết nối bảo mật SSL.

---

## 📄 Giấy phép (License)

Dự án này được phát hành dưới bản quyền **MIT License**. Chi tiết xem tại tệp [LICENSE](LICENSE).

Copyright © 2026 M-DataPlus
