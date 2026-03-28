# System-design
The most basic knowlegde how the app work behind the scene

# 📚 Kiến trúc Hệ thống (System Design) cho Developer thời đại AI

## 🧠 Vì sao nên học System Design?

Khi AI ngày càng mạnh trong việc viết code, lợi thế của lập trình viên nằm ở:

- Thiết kế hệ thống có khả năng mở rộng (scalable)
- Đưa ra quyết định kiến trúc
- Hiểu trade-off (hiệu năng vs chi phí vs độ phức tạp)

👉 System Design là kỹ năng mà AI khó thay thế.

---

## 🧩 Các thành phần chính của hệ thống

### 1. Client (Frontend)
- Ứng dụng web / mobile
- Gửi request đến backend

Ví dụ:
- React, Flutter

---

### 2. Backend / API
- Xử lý logic nghiệp vụ
- Nhận request và trả response

Ví dụ:
- Node.js, Java Spring, Golang

---

### 3. Database (Cơ sở dữ liệu)
Lưu trữ dữ liệu lâu dài

- **SQL**: MySQL, PostgreSQL  
- **NoSQL**: MongoDB, Redis  

---

### 4. Cache
- Lưu dữ liệu truy cập thường xuyên
- Giúp tăng tốc hệ thống

Ví dụ:
- Redis

---

### 5. Load Balancer
- Phân phối request đến nhiều server
- Tránh quá tải

---

### 6. Message Queue
- Xử lý bất đồng bộ (async)

Ví dụ:
- Kafka
- RabbitMQ

---

### 7. Microservices
- Chia hệ thống thành nhiều service nhỏ

Ví dụ:
- user-service
- payment-service
- order-service

---

### 8. Authentication & Authorization
- Xác thực người dùng
- Phân quyền

Ví dụ:
- JWT
- OAuth

---

### 9. Storage (Lưu trữ file)
- Lưu ảnh, video, file

Ví dụ:
- AWS S3

---

### 10. Monitoring & Logging
- Theo dõi hệ thống và lỗi

Ví dụ:
- Prometheus
- Grafana

---

## 🧱 Tổng quan hệ thống




##############################################################

# 📚 System Design Fundamentals (For Developers in the AI Era)

## 🧠 Why System Design?

As AI becomes increasingly powerful at writing code, the real advantage of developers lies in:
- Designing scalable systems
- Making architectural decisions
- Understanding trade-offs (performance vs cost vs complexity)

👉 System Design is the skill that AI cannot easily replace.

---

## 🧩 Core Components of a System

### 1. Client (Frontend)
- Web / Mobile applications
- Sends requests to backend
- Example: React, Flutter

---

### 2. Backend / API Layer
- Handles business logic
- Processes requests and returns responses
- Example: Node.js, Java Spring, Golang

---

### 3. Database
Stores persistent data

- **SQL**: MySQL, PostgreSQL  
- **NoSQL**: MongoDB, Redis  

---

### 4. Cache
- Stores frequently accessed data
- Improves performance significantly
- Example: Redis

---

### 5. Load Balancer
- Distributes traffic across servers
- Prevents overload

---

### 6. Message Queue
- Enables asynchronous processing
- Used for background jobs

Examples:
- Kafka
- RabbitMQ

---

### 7. Microservices Architecture
- Break system into smaller services

Examples:
- user-service
- payment-service
- order-service

---

### 8. Authentication & Authorization
- User login & identity verification
- Permission control

Examples:
- JWT
- OAuth

---

### 9. Storage (File System)
- Stores media files (images, videos)

Example:
- AWS S3

---

### 10. Monitoring & Logging
- Tracks system health and errors

Examples:
- Prometheus
- Grafana

---

## 🧱 System Overview
