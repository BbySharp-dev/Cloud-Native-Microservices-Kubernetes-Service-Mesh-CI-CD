# ☁️ Cloud Native Application Architecture

## 1. Giới thiệu

Cloud Native Application Architecture là phương pháp thiết kế, xây dựng và vận hành ứng dụng sao cho **tận dụng tối đa lợi ích của môi trường điện toán đám mây**.

### 🎯 Mục tiêu:
- Scalable (mở rộng dễ dàng)
- Highly Available (sẵn sàng cao)
- Resilient (chống chịu lỗi)
- Flexible (linh hoạt)
- Tăng tốc đổi mới và phản ứng nhanh với biến động thị trường

---

## 2. 🔑 Các đặc điểm chính (Key Characteristics)

### 2.1. Microservices
- Ứng dụng được chia thành nhiều **dịch vụ nhỏ, độc lập, loosely-coupled**.
- Mỗi microservice chịu trách nhiệm cho một chức năng riêng.
- Cho phép **phát triển, triển khai, mở rộng độc lập**.
- Tăng hiệu quả tài nguyên và tốc độ phát triển so với monolith.

### 2.2. Containers
- Mỗi microservice được đóng gói dưới dạng container.
- **Nhẹ, di động, môi trường chạy đồng nhất**.
- Dễ dàng build, test và deploy qua nhiều môi trường khác nhau.
- Công cụ phổ biến: `Docker`, `Containerd`.

### 2.3. Orchestration
- Dùng để quản lý lifecycle của container.
- Công cụ chính: **Kubernetes**.
- Tính năng:
  - Triển khai tự động
  - Tự động scale
  - Rolling update
  - Quản lý tài nguyên hiệu quả

### 2.4. DevOps Practices
- Áp dụng:
  - **CI/CD** (Continuous Integration / Continuous Deployment)
  - **Infrastructure as Code**
- Giúp phát triển – kiểm thử – triển khai nhanh chóng và lặp lại được.

### 2.5. Automation
- Tự động hóa quy trình:
  - Triển khai
  - Scale
  - Phục hồi (recovery)
- Giảm lỗi do con người và tăng tính ổn định.

### 2.6. Scalability
- Thiết kế **mở rộng ngang** (scale-out).
- Thêm/bớt instances tùy vào tải hệ thống.
- Đảm bảo hiệu năng cao khi có tải lớn.

### 2.7. Resilience
- **Tự phục hồi khi có lỗi**, chịu lỗi tốt.
- Áp dụng các kỹ thuật:
  - Circuit Breaker
  - Retry
  - Timeout
- Đảm bảo độ sẵn sàng và giảm downtime.

### 2.8. Observability
- Bao gồm:
  - **Monitoring**
  - **Logging**
  - **Tracing**
- Giúp theo dõi, tối ưu hiệu suất và phát hiện sự cố.
- Công cụ phổ biến: `Prometheus`, `Fluentd`, `Jaeger`.

---

## 3. 🌟 Lợi ích tổng thể khi áp dụng Cloud-Native Architecture

- Triển khai nhanh hơn, phản hồi linh hoạt với thị trường
- Khả năng mở rộng cao
- Độ tin cậy và ổn định cao
- Giảm chi phí quản trị hệ thống
- Tăng **agility** và **competitiveness** cho tổ chức

---

## 4. 📚 Trong khóa học

Chúng ta sẽ học toàn bộ những nội dung trên dưới dạng các **Cloud Native Pillars** — từng phần sẽ có lý thuyết, thực hành và kiến trúc áp dụng thực tế.
