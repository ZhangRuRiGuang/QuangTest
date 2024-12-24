Dưới đây là phiên bản `.md` với định dạng tối ưu và đẹp mắt hơn, sử dụng các chi tiết nổi bật để làm rõ ràng nội dung:

```markdown
# QuangTest

🚀 **A personal CLI project intended to replace Postman in a production environment.**

---

## 🌟 Features

- **HTTP Methods**: Support for GET, POST, PUT, DELETE, and more.
- **Payload Support**: JSON and form-data for requests.
- **Authentication**: Easily configure Bearer Tokens, Basic Auth, etc.
- **Reusable Requests**: Save and execute requests via configuration files.
- **Formatted Responses**: View response headers and body in a clean, structured format.
- **Lightweight**: Minimal resource usage, ideal for production environments.

---

## 🔥 Why Choose QuangTest?

QuangTest simplifies your workflow by providing a lightweight alternative to GUI tools like Postman.  
It’s designed for efficiency and scalability in production environments, ensuring quick and reliable API interactions directly from your terminal.

---

## 📥 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/QuangTest.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd QuangTest
   ```
3. **Build the binary**:
   ```bash
   go build -o quangtest main.go
   ```
4. **Add the binary to your PATH**:
   ```bash
   mv quangtest /usr/local/bin/
   ```

---

## 💡 Usage

### 🟢 Send a GET Request:
```bash
quangtest get https://api.example.com/v1/resource
```

### 🔵 Send a POST Request:
```bash
quangtest post https://api.example.com/v1/resource -d '{"key": "value"}'
```

### 🛡️ Add Authentication:
```bash
quangtest get https://api.example.com/v1/resource -H "Authorization: Bearer YOUR_TOKEN"
```

### 📂 Save and Reuse Requests:
Save a request:
```bash
quangtest save --name getUser --method GET --url https://api.example.com/v1/users/{id}
```

Execute a saved request:
```bash
quangtest run getUser --params id=123
```

---

## 🛠️ Roadmap

- [ ] Add support for multipart file uploads.
- [ ] Enhance CLI help documentation.
- [ ] Implement response filtering options.
- [ ] Integration with logging tools for better debugging.

---

## 🤝 Contributing

Contributions are welcome!  
Please fork the repository, make your changes, and submit a pull request.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

🎯 **Start building smarter workflows with QuangTest today!**
```

### Tối ưu hóa:
1. **Biểu tượng cảm xúc**: Thêm điểm nhấn và làm tài liệu dễ nhìn hơn.
2. **Phân cách**: Sử dụng các đường kẻ `---` để chia các phần rõ ràng.
3. **Các tiêu đề phụ có biểu tượng**: Gợi cảm giác hiện đại và chuyên nghiệp.
4. **Cấu trúc gọn gàng**: Nội dung từng phần được làm nổi bật, dễ dàng tìm kiếm và sử dụng.
