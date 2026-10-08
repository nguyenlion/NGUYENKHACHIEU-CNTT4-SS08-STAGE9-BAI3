# Hướng Dẫn Cài Đặt VS Code

Sử dụng biến `python_path` và chạy lệnh `python --version` trong Terminal để kiểm tra môi trường.

```python
import sys

def check_env():
    print(f"Python version: {sys.version}")

if __name__ == "__main__":
    check_env()
```

### So Sánh Công Cụ

| Tiêu chí | StackEdit | VS Code |
| :--- | :--- | :--- |
| **Mục đích** | Soạn thảo Markdown online | Trình soạn thảo mã nguồn / IDE |
| **Ưu điểm** | Dễ dùng, không cần cài đặt | Extension phong phú, Terminal & Debug mạnh |

### Hiển Thị Ký Tự Đặc Biệt

- Ký tự sao: \*Không in nghiêng\*
- Ký tự thăng: \# Không phải tiêu đề

### Danh Sách Tiến Độ

- [x] Tải và cài đặt VS Code
- [x] Cài đặt Extension Python
- [ ] Chạy câu lệnh `python --version` kiểm tra