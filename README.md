# M-DataPlus

**Professional Database IDE** for SQL Server & PostgreSQL — fast, smart, and intuitive.

<p align="center">
  <img src="https://github.com/anhnvt4620/M-DataPlus/raw/master/build/icon.png" width="128" alt="M-DataPlus" />
</p>

---

## Download

[**M-DataPlus Setup 1.0.0.exe** (Windows)](https://github.com/anhnvt4620/M-DataPlus/releases/download/v1.0.0/M-DataPlus.Setup.1.0.0.exe)

Yêu cầu: Windows 10/11, .NET không cần cài thêm.

---

## Tính năng

### SQL Editor
- **IntelliSense** tự động gợi ý: keyword, bảng, view, procedure, column
- **Frequency ranking** — càng dùng nhiều, gợi ý càng chính xác
- **FK JOIN suggestion** — tự động gợi ý điều kiện `ON` khi JOIN
- **Dot-completion** — gõ `dbo.` hiện danh sách object trong schema
- **Smart ALTER** — gõ `ALTER VIEW name` → tự load định nghĩa
- **Snippets** với placeholder `${1:Table}`

### Object Explorer
- Cây thư mục: Tables, Views, Synonyms, Procedures, Functions
- **Pin database** thường dùng lên đầu
- **Filter** theo tên object, tự expand đến kết quả
- **F12** → trỏ đến bảng/view trong Explorer
- **Shift+F12** → tìm tất cả reference
- Chuột phải → Script (CREATE / SELECT / INSERT / UPDATE / DELETE)

### Data Grid
- **Edit trực tiếp** (INSERT / UPDATE / DELETE) + Commit / Discard
- **Form Inspector** xem chi tiết từng dòng
- **Column picker** — ẩn/hiện cột
- **Export** CSV / JSON
- **Copy as SQL INSERT**
- **Phân trang** client-side

### Formatting
- `Ctrl+Shift+F` format SQL với 11 tùy chọn (theo style RedGate SQL Prompt)
- `Ctrl+K, Ctrl+F` format vùng chọn
- Cấu hình: keyword case, identifier case, indent style, expression width...

### Execution Plan
- **Cây trực quan** với icon + màu code cho từng operator
- Cost bar hiển thị độ nặng của mỗi operator
- Expand/collapse từng nhánh
- Legend chú thích

### Multi-Connection
- Kết nối nhiều server cùng lúc
- Chuyển đổi nhanh qua Sidebar
- **Test Connection** — test không connect thật
- **Tab coloring** — mỗi connection 1 màu (DEV xanh, PROD đỏ...)

### Safety
- Cảnh báo khi DELETE/UPDATE thiếu WHERE
- Tab màu theo môi trường — tránh nhầm DEV/PROD
- Error Boundary — crash không trắng màn hình

### Themes
7 themes: Light, Dark+, Monokai, Solarized, High Contrast, Midnight, Ocean

---

## Phím tắt

| Phím | Chức năng |
|---|---|
| `F5` | Execute query |
| `Ctrl+Enter` | Execute (Alt) |
| `Ctrl+Shift+F` | Format document |
| `Ctrl+K, Ctrl+F` | Format selection |
| `Ctrl+K, Ctrl+C` | Comment |
| `Ctrl+K, Ctrl+U` | Uncomment |
| `Ctrl+Shift+U` | Uppercase |
| `Ctrl+Shift+L` | Lowercase |
| `F12` | Go to Definition |
| `Shift+F12` | Find References |
| `Ctrl+N` | New Query |
| `Ctrl+P` | Command Palette |
| `Ctrl+B` | Toggle Sidebar |
| `Ctrl+R` | Toggle Results |
| `Ctrl+L` | Execution Plan |

---

## Hỗ trợ

- **SQL Server** (Windows Auth / SQL Auth)
- **PostgreSQL** (SSL support)

---

## License

MIT © 2026 M-DataPlus
