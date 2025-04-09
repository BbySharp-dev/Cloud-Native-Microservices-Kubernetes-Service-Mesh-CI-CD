# 🧱 Cloud Native Architecture: Design Principles & Key Characteristics

## 1. 🎯 Mục tiêu khi thiết kế Cloud Native Architecture

Cloud Native Architecture yêu cầu hệ thống có khả năng:
- **Thay đổi linh hoạt**
- **Tự động mở rộng (scale out)**
- **Tự xử lý lỗi**
- **Dễ bảo trì và thích nghi với sự thay đổi nhanh**

> Dưới đây là những **nguyên tắc thiết kế (design principles)** cốt lõi giúp bạn xây dựng kiến trúc Cloud Native hiệu quả và bền vững.

---

## 2. 🧩 Các nguyên tắc thiết kế kiến trúc Cloud Native

### 2.1. Loosely Coupled Microservices
- Chia ứng dụng thành các **dịch vụ nhỏ, độc lập**.
- Giao tiếp qua **protocol nhẹ** (REST, gRPC, messaging).
- Tăng khả năng scale và phát triển song song.

### 2.2. Polyglot & Optimum Language / Framework
- Mỗi microservice có thể sử dụng **ngôn ngữ phù hợp nhất**.
  - Ví dụ: `Python` cho ML, `Go` cho performance, `C#` cho enterprise app.
- Tối ưu hiệu năng và tận dụng thế mạnh từng ngôn ngữ.

### 2.3. API-Centric Communication
- Tương tác giữa các dịch vụ qua **APIs nhẹ** (REST/gRPC).
- Giao tiếp hiệu quả, giảm độ phụ thuộc, dễ quản lý.

### 2.4. Stateless & Scalable
- Thiết kế **stateless** – không lưu trạng thái trong service.
- Trạng thái lưu tại hệ thống bên ngoài như **Redis, DB, message queue**.
- Dễ dàng **scale ngang** nhiều instance.

### 2.5. Elasticity & Dynamic Scaling
- Tự động **scale up/down** theo nhu cầu sử dụng và tài nguyên.
- Ví dụ: tăng số lượng pods khi CPU > 80%, giảm khi idle.

### 2.6. Resiliency & Fault Tolerance
- Thiết kế để **chịu lỗi và tự phục hồi** (self-healing).
- Áp dụng:
  - Redundancy (dự phòng)
  - Multi-AZ / Multi-region
  - Circuit Breaker, Retry, Timeout

### 2.7. Polyglot Architecture
- Không ràng buộc một công nghệ/ngôn ngữ.
- Chọn **công nghệ phù hợp nhất cho từng thành phần**, tùy theo mục tiêu và năng lực đội ngũ.

### 2.8. Lightweight Container & Orchestration
- Đóng gói app dưới dạng **container nhẹ** (Docker).
- Dùng **Kubernetes** hoặc hệ thống orchestrator khác để:
  - Triển khai
  - Scale
  - Quản lý vòng đời container

### 2.9. Immutable Infrastructure
- Hạ tầng không thay đổi sau khi triển khai.
- Nếu cần thay đổi, **tạo mới instance** thay vì cập nhật thủ công.
- Tăng tính **ổn định, nhất quán và dễ tái tạo** cho môi trường vận hành.

---

## ✅ Tổng kết

> Kiến trúc Cloud Native không chỉ là dùng công nghệ hiện đại, mà là **tư duy thiết kế ứng dụng có khả năng tiến hóa, phục hồi và thích nghi cao**.

Hãy đảm bảo rằng mỗi nguyên tắc trên đều được xem xét và áp dụng phù hợp trong quá trình thiết kế hệ thống Cloud Native của bạn.
