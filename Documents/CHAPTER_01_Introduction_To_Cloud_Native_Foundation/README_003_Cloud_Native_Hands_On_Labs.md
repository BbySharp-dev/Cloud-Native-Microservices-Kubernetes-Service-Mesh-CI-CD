# 🧪 Cloud Native Hands-on Labs: Thực hành theo từng Pillar

Trong khóa học này, bạn sẽ thực hiện chuỗi **Hands-on Labs** cho từng **Cloud Native Pillar** nhằm củng cố kiến thức lý thuyết và nâng cao kỹ năng thực tiễn. Mỗi lab sẽ ứng dụng các công cụ mã nguồn mở phổ biến như Docker, Kubernetes, Helm, Istio, Redis, Kafka, Prometheus, Terraform,...

---

## ⚙️ 1. Microservices & Containerization

### 🔧 Lab 1: Develop RESTful Microservices (CRUD APIs)
- Tạo microservice từ đầu với các endpoint CRUD.
- Thiết kế và triển khai RESTful API.

### 🐳 Lab 2: Containerize Microservices with Docker
- Viết Dockerfile cho từng microservice.
- Build image, run container và kiểm tra cục bộ.

---

## ☸️ 2. Kubernetes Deployment & Service Mesh

### 🚀 Lab 3: Deploy Microservices to Kubernetes
- Viết YAML manifest cho Deployment, Service, ConfigMap.
- Thực hành rolling update, rollback, auto healing.

### 📦 Lab 4: Deploy using Helm Charts
- Viết Helm Chart để deploy microservice.
- Sử dụng Helm CLI để quản lý release.

### 🌐 Lab 5: Deploy with Istio Service Mesh
- Cài Istio vào Kubernetes cluster.
- Cấu hình routing, load balancing giữa services.

---

## 🗄️ 3. Backing Services (Database, Cache, Messaging)

### 🐓 Lab 6: Deploy CockroachDB on Kubernetes (Minikube)
- Dùng SQL client truy cập DB, mô phỏng lỗi node.

### 💾 Lab 7: Deploy Redis as Cache
- Dùng Bitnami Helm chart để deploy Redis.
- Kiểm tra scale, node failure, Redis CLI.

### 📬 Lab 8: Deploy Kafka for Messaging
- Deploy Kafka với Bitnami Helm chart.
- Publish & consume topic, xử lý lỗi & scale Kafka.

---

## 📈 4. Scalability & Auto-Scaling

### 🔄 Lab 9: Implement Kubernetes Auto Scaling
- Cấu hình Horizontal Pod Autoscaler (HPA).
- Thử tải hệ thống và quan sát scale.

### ⚡ Lab 10: Use KEDA - Event-Driven AutoScaler
- Cài KEDA và trigger scale từ sự kiện.

---

## ☁️ 5. Cloud Provider Integration

### 🌥️ Lab 11: Deploy to Amazon EKS with Fargate
- Provision EKS Cluster bằng AWS CLI.
- Deploy microservice sử dụng Fargate (serverless container).

---

## 🔧 6. DevOps, IaC, CI/CD

### 🛠️ Lab 12: Provision Infrastructure with Terraform
- Cài Terraform, viết script để tạo EC2 instance.
- Thực hành `plan`, `apply`, `destroy`.

### 🔄 Lab 13: Setup CI/CD with GitHub Actions
- Tạo workflow build & push Docker image lên DockerHub.
- Tự động test & deploy microservice.

---

## 📊 7. Monitoring & Observability

### 📡 Lab 14: Monitor with Prometheus, Grafana, ELK Stack
- Thiết lập Prometheus + Grafana để monitor ứng dụng.
- Cài Elastic Stack để log và trace ứng dụng.
- Tạo dashboard giám sát hiệu năng.

---

## 🔄 8. Serverless Architecture Labs

### ⚙️ Lab 15: AWS App Runner with Serverless Containers
- Deploy RESTful microservice container lên App Runner.

### ⚡ Lab 16: Fully Serverless on AWS
- Kết hợp: `AWS Lambda`, `API Gateway`, `DynamoDB`, `SNS`, ...
- Xây dựng hệ thống microservice serverless hoàn chỉnh.

---

## ✅ Kết luận

Chuỗi **Hands-on Labs** này sẽ giúp bạn:
- Áp dụng kiến thức lý thuyết vào thực tế.
- Làm chủ các công cụ mã nguồn mở & cloud-native.
- Sẵn sàng thiết kế, triển khai và vận hành ứng dụng trên môi trường Kubernetes cloud-native.
