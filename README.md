# Nhom2_Quanlyanphamthuvien
# 📚 Phần mềm Quản lý Ấn phẩm Thư viện

## 🧾 Giới Thiệu

Dự án **"Phần mềm quản lý ấn phẩm thư viện"** là một ứng dụng Java sử dụng JavaFX giúp quản lý các ấn phẩm thư viện, đăng nhập người dùng, giao diện thân thiện, và hỗ trợ thao tác với dữ liệu XML.  
Ứng dụng hỗ trợ quản lý sản phẩm (ấn phẩm), giao diện trực quan, và hoạt động trên môi trường desktop hiệu quả.

---

## 👥 Thành Viên

- Nguyễn Tuấn Anh — MSV: 23010799
- Phạm Tiến Chiêu - 23010526
- Lê Anh Duy - 23010710
-  Đoàn Hoàng Vũ - 23010534

## 🔐 Tài khoản đăng nhập (admin)

- **Username:** `admin`  
- **Password:** `1`

---

## 💻 Môi trường phát triển

- **IDE:** NetBeans 23  
- **JDK:** Java 17 trở lên  
- **Dependencies:** JavaFX, Maven, XML parser (builtin)

---

## 🗃 Cơ sở dữ liệu

- Dữ liệu lưu trữ dưới dạng file `.xml`.
- Bao gồm:
  - `data.xml`: lưu dữ liệu người dùng
  - `table_data.xml`: lưu thông tin ấn phẩm thư viện

---

## 🎨 Giao diện & Thành phần

- Giao diện thiết kế bằng `FXML`
- Ảnh nền và CSS làm đẹp bố cục chương trình
- **Thực thể ấn phẩm thư viện (Product):**
  ```java
  String id;
  String ten;
  String loai;
  String tacgia;
  String nxb;
  int nam;
  int soluong;
  ```

---

## 🖥 View (Giao diện chức năng)

- `LoginView` — Giao diện đăng nhập
- `SignUpView` — Giao diện đăng ký tài khoản
- `MainView` — Giao diện chính sau đăng nhập
- `FXML` và `Controller` được tách riêng trong thư mục `src/main/java` và `resources`

---

## ⚙️ Chức năng

- Đăng nhập / đăng ký người dùng
- Xem danh sách ấn phẩm thư viện
- Thêm / sửa / xóa ấn phẩm
- Giao diện đẹp và dễ sử dụng
- Tìm kiếm và xử lý dữ liệu XML

---

## 📌 Hướng dẫn sử dụng

### 1. Cài đặt

> **Khuyến nghị:** chạy bằng IDE (NetBeans, IntelliJ) do file `.jar` có thể không hỗ trợ giao diện đầy đủ

- Bước 1: Cài đặt JDK  
  Tải từ [Oracle JDK Download](https://www.oracle.com/java/technologies/javase-downloads.html)

- Bước 2: Clone hoặc mở source code  
  ```bash
  git clone <repository-url>
  ```

- Bước 3: Mở bằng IDE  
  Dùng NetBeans/IntelliJ mở thư mục `prj/` chứa `pom.xml`

- Bước 4: Chạy `App.java` để khởi động ứng dụng

---

### 2. Đăng nhập

- Khi mở ứng dụng → màn hình đăng nhập
- Nhập tài khoản:
  - **Tên đăng nhập:** `1`
  - **Mật khẩu:** `1`
- Sau đó vào giao diện chính

---

### 3. Các chức năng chính

- **Quản lý ấn phẩm:**
  - Nhập thông tin và nhấn **Thêm** để thêm ấn phẩm
  - Chọn ấn phẩm và nhấn **Xóa** để xoá
  - Chỉnh sửa thông tin rồi nhấn **Cập nhật** để cập nhật
  - Tìm kiếm nhanh ấn phẩm theo tên hoặc mã

- **Tài khoản người dùng:**
  - Đăng ký tài khoản mới tại giao diện SignUp
  - Hệ thống lưu dữ liệu người dùng vào `data.xml`



