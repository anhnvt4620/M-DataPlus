# M-DataPlus

**Professional Database IDE** — SQL Server & PostgreSQL management tool with IntelliSense, formatting, and execution plans.

![M-DataPlus](build/icon.png)

## Tính năng nổi bật

### SQL Editor với IntelliSense thông minh
- Auto-complete **từ khóa SQL**, **bảng**, **view**, **procedure**, **function**, **column**
- **Frequency-based ranking** — học thói quen sử dụng, gợi ý thông minh hơn theo thời gian
- **Foreign key JOIN suggestions** — tự động gợi ý `ON` condition khi JOIN
- **Dot-completion** — gõ `dbo.` → hiện danh sách bảng trong schema
- **Smart ALTER** — gõ `ALTER VIEW dbo.X` → tự động load định nghĩa
- **Snippets** tùy chỉnh với placeholder `${1:Table}`

### Object Explorer
- **Cây thư mục** hiển thị Tables, Views, Synonyms, Procedures, Functions
- **Pin database** — ghim database hay dùng lên đầu
- **Filter** theo tên object với auto-expand
- **Context menu** — Script as CREATE/SELECT/INSERT/UPDATE/DELETE
- **F12 Go to Definition** — nhảy đến bảng/view trong Explorer
- **Shift+F12 Find References** — tìm tất cả tab chứa identifier

### Data Grid
- **Inline editing** với INSERT/UPDATE/DELETE + commit/discard
- **CSV/JSON Export**
- **Copy as SQL INSERT** từ context menu
- **Row Inspector** — xem chi tiết từng dòng dạng form
- **Pagination** client-side
- **Column picker** — ẩn/hiện cột tùy chọn

### Query Editor
- **Monaco Editor** (VS Code engine) với syntax highlighting
- **Format SQL** (`Ctrl+Shift+F`) với 11 tùy chọn format (RedGate SQL Prompt style)
- **Execution Plan** trực quan với cây operator, cost bars, màu code
- **Multi-result-set** — hiển thị nhiều kết quả trong 1 lần chạy
- **Messages tab** — log query execution

### Safety
- **DELETE/UPDATE warning** khi thiếu WHERE clause
- **Tab coloring per connection** — phân biệt DEV/TEST/PROD
- **Error Boundary** — crash không làm trắng màn hình

### Multi-Connection
- Kết nối **nhiều server cùng lúc**
- Chuyển đổi connection qua Sidebar
- **Test Connection** — test không connect thật

## Themes

| Light | Dark+ | Monokai | Solarized | High Contrast | Midnight | Ocean |
|---|---|---|---|---|---|---|
| `light` | `dark` | `monokai` | `solarized` | `highContrast` | `midnight` | `ocean` |

## Phím tắt

| Phím | Chức năng |
|---|---|
| `F5` | Execute Query |
| `Ctrl+Enter` | Execute Query (Alt) |
| `Ctrl+Shift+F` | Format Document |
| `Ctrl+K, Ctrl+F` | Format Selection |
| `Ctrl+K, Ctrl+C` | Comment |
| `Ctrl+K, Ctrl+U` | Uncomment |
| `Ctrl+Shift+U` | Transform Uppercase |
| `Ctrl+Shift+L` | Transform Lowercase |
| `F12` | Go to Definition |
| `Shift+F12` | Find All References |
| `Ctrl+N` | New Query |
| `Ctrl+P` | Command Palette |
| `Ctrl+B` | Toggle Sidebar |
| `Ctrl+R` | Toggle Results Pane |
| `Ctrl+Shift+H` | Query History |
| `Ctrl+L` | Show Execution Plan |

## Công nghệ

- **Frontend**: React 19 + TypeScript + Vite + Tailwind CSS
- **Editor**: Monaco Editor (`@monaco-editor/react`)
- **Desktop**: Electron 41
- **Database**: `mssql` (tedious) + `pg` (PostgreSQL)
- **Format**: `sql-formatter`
- **Icons**: Lucide React

## Cài đặt

### Windows

Tải installer từ [Releases](https://github.com/anhnvt4620/M-DataPlus/releases):

```
M-DataPlus Setup 1.0.0.exe
```

### Development

```bash
# Clone
git clone https://github.com/anhnvt4620/M-DataPlus.git
cd M-DataPlus

# Install
npm install

# Dev mode
npm run dev

# Build Windows installer
npm run build:exe
```

## Build

```bash
npm run build:exe
# Output: release/M-DataPlus Setup 1.0.0.exe
```

## License

MIT © 2026 M-DataPlus
