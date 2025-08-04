# 🤖 ChatGPT Markdown to HTML Converter

Tool chuyển đổi file Markdown sang HTML với giao diện giống ChatGPT, hoạt động hoàn toàn trên trình duyệt.

## 🚀 Cách sử dụng

### 1. Mở file converter.html
Mở file `converter.html` trong trình duyệt web bất kỳ.

### 2. Chọn file Markdown
- Click vào vùng "Kéo thả file hoặc click để chọn"
- Hoặc kéo thả file .md vào vùng đó
- Hỗ trợ các định dạng: .md, .markdown, .txt

### 3. Tùy chỉnh thông tin
- **Tên file output**: Tên file HTML sẽ được tạo
- **Tên người dùng**: Tên hiển thị trong avatar
- **Email**: Email người dùng
- **Tiêu đề cuộc hội thoại**: Tiêu đề chính của trang

### 4. Convert
Click nút "🔄 Convert sang HTML" để xử lý.

### 5. Xem kết quả
- **Xem trước**: Xem kết quả ngay trong iframe
- **Tải xuống**: Tải file HTML về máy
- **Mở tab mới**: Mở kết quả trong tab mới

## ✨ Tính năng

### 🎨 Giao diện ChatGPT
- Màu sắc và font chữ giống hệt ChatGPT
- Avatar cho người dùng và ChatGPT
- Layout responsive cho mọi thiết bị

### 📝 Xử lý Markdown
- Parse tự động các section "## Prompt:" và "## Response:"
- Hỗ trợ đầy đủ các element markdown:
  - Headers (# ## ###)
  - Bold (**text**) và italic (*text*)
  - Code blocks (```) và inline code (`code`)
  - Lists (* - 1. 2. 3.)
  - Links [text](url)
  - Blockquotes (> text)
  - Horizontal rules (***)

### ⚡ Xử lý nhanh
- Hoạt động hoàn toàn trên client-side
- Không cần server hay cài đặt gì thêm
- Convert ngay lập tức

### 🔧 Tùy chỉnh dễ dàng
- Thay đổi tên người dùng, email
- Tùy chỉnh tiêu đề cuộc hội thoại
- Đặt tên file output theo ý muốn

## 📁 Cấu trúc file

```
ChatGPT-Converter/
├── converter.html          # Giao diện web chính
├── ChatGPT.md             # File markdown mẫu
└── README.md              # Hướng dẫn sử dụng
```

## 🎯 Ví dụ sử dụng

1. **File Markdown mẫu** (ChatGPT.md):
```markdown
# Đánh số lô 39

## Prompt:
Phốt make link discoverable của bọn mày vừa rồi là như nào

## Response:
Phốt về tính năng "Make link discoverable" của ChatGPT vừa qua...
```

2. **Kết quả HTML** sẽ có:
- Header với thông tin người dùng
- Các đoạn hội thoại với avatar
- Styling giống ChatGPT
- Responsive design

## 🔧 Tùy chỉnh nâng cao

### Thay đổi màu sắc
Trong file `converter.html`, tìm và sửa các biến CSS:
```css
--primary-color: #10a37f;
--user-avatar-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
--gpt-avatar-gradient: linear-gradient(135deg, #10a37f 0%, #1a7f64 100%);
```

### Thay đổi template
Sửa hàm `convertMarkdownToChatGPTHTML()` trong JavaScript để thay đổi cấu trúc HTML.

## 🐛 Troubleshooting

### File không load được
- Đảm bảo file có định dạng .md, .markdown hoặc .txt
- Kiểm tra encoding UTF-8
- Thử file khác

### Kết quả không đúng
- Kiểm tra format markdown có đúng không
- Đảm bảo có các section "## Prompt:" và "## Response:"
- Thử với file mẫu ChatGPT.md

### Không tải xuống được
- Kiểm tra quyền ghi file trong thư mục Downloads
- Thử đổi tên file output
- Kiểm tra antivirus có chặn không

## 📝 Ghi chú

- Tool hoạt động hoàn toàn offline
- Không gửi dữ liệu lên server
- Hỗ trợ file lớn (tùy theo RAM trình duyệt)
- Tương thích với mọi trình duyệt hiện đại

## 🤝 Đóng góp

Để cải thiện tool:
1. Fork repository
2. Tạo feature branch
3. Commit changes
4. Push và tạo Pull Request

## 📄 License

MIT License - Sử dụng tự do cho mục đích cá nhân và thương mại. 