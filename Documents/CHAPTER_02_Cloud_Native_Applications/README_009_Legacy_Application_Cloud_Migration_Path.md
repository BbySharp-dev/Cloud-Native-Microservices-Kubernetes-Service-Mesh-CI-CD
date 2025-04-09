# 🚀 Legacy Application Journey to the Cloud (Modernization Path)

## 1. 📌 Tại sao chuyển ứng dụng lên Cloud?

- **Tăng tốc độ triển khai:** Có thể tạo hàng ngàn máy chủ chỉ trong vài phút.
- **Tối ưu chi phí và linh hoạt hơn** so với on-premises.
- **Hỗ trợ đổi mới nhanh chóng** nhờ tích hợp các dịch vụ hiện đại trên Cloud.

> ⚠️ Không phải ứng dụng nào cũng cần phải viết lại toàn bộ theo mô hình Cloud Native. Tùy theo nhu cầu, có thể chọn cách tiếp cận **từng bước (incremental approach)**.

---

## 2. 🛤️ Ba cấp độ chuyển đổi ứng dụng lên Cloud

### 🌩️ Level 1 – **Infrastructure-Ready / Lift-and-Shift**

- **Mô tả:** Di chuyển ứng dụng hiện có từ on-premises lên cloud **mà không thay đổi mã nguồn**.
- **Cách thực hiện:** Deploy trên máy ảo (VM) sử dụng dịch vụ IaaS.
- **Tên gọi phổ biến:** *Lift and Shift*.

📦 **Ví dụ dịch vụ:**
- AWS: EC2 + Cloud Adoption Framework
- Azure: Virtual Machines

---

### 🛠️ Level 2 – **Cloud-Enhanced Applications**

- **Mô tả:** Tận dụng **container**, **cloud-managed services**, **CI/CD**, nhưng vẫn giữ code logic chính.
- **Cách thực hiện:** Đóng gói app trong Docker, triển khai lên IaaS hoặc PaaS.
- **Lợi ích:** Tăng hiệu quả triển khai, giảm lỗi do môi trường, áp dụng DevOps.

🔧 **Ví dụ dịch vụ:**
- AWS:
  - Database Migration Service
  - Application Migration Service
- Azure:
  - Azure App Services
  - Azure Container Instances

---

### ☁️ Level 3 – **Cloud Native Applications**

- **Mô tả:** Tái kiến trúc hoặc viết lại app hoàn toàn theo mô hình **microservices**, **serverless** và **PaaS**.
- **Lợi ích:** Tối đa hóa tính linh hoạt, khả năng mở rộng và tốc độ đổi mới.
- **Thách thức:** Yêu cầu hiểu sâu cloud, có thể phải viết lại mã nguồn.

🧠 **Ví dụ dịch vụ:**
- AWS:
  - ECS / EKS + Fargate
  - Lambda
  - API Gateway
- Azure:
  - Azure Kubernetes Service (AKS)
  - Azure Functions

---

## 3. 📚 AWS Cloud Adoption Framework (CAF)

> CAF giúp tổ chức xây dựng chiến lược chuyển đổi phù hợp với mục tiêu doanh nghiệp.

### 6 góc nhìn của AWS CAF:
1. **Business**
2. **People**
3. **Governance**
4. **Platform**
5. **Security**
6. **Operations**

---

## 4. ⚖️ Chọn chiến lược phù hợp

| Cấp độ | Đặc điểm | Phù hợp khi... |
|--------|----------|----------------|
| Level 1 | Nhanh, ít thay đổi | Muốn chuyển nhanh, hạn chế ngân sách |
| Level 2 | Tận dụng container, DevOps | App còn dùng được, muốn tăng hiệu quả vận hành |
| Level 3 | Viết lại, kiến trúc hiện đại | App quan trọng, dài hạn, cần mở rộng và linh hoạt cao |

> ✅ **Bạn không cần dùng duy nhất 1 cấp độ. Có thể áp dụng kết hợp:** một phần giữ nguyên (Level 1), một phần container hóa (Level 2), phần còn lại viết lại theo Cloud Native (Level 3).

---

## 🔚 Tổng kết

Hành trình chuyển đổi ứng dụng lên Cloud là một quá trình **linh hoạt và tùy chỉnh**, không có công thức duy nhất cho tất cả.

- Bắt đầu từ nhu cầu kinh doanh
- Đánh giá mức độ phức tạp ứng dụng
- Chọn mô hình chuyển đổi phù hợp
- Tận dụng công cụ từ AWS hoặc Azure để hỗ trợ từng bước

