---
title: "Event 3"
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

# BÁO CÁO THU HOẠCH SỰ KIỆN
**Sự kiện:** AWS Cloud Mastery Series #2: Từ DevOps, IaC đến Container & Observability

---

## 1. MỤC TIÊU THAM DỰ
Việc tham dự sự kiện tập trung vào 4 mục tiêu cốt lõi nhằm nâng cao năng lực kỹ thuật và tư duy chiến lược:
* **Định hình tư duy (Mindset):** Nắm bắt bản chất Vòng đời giá trị (Value Cycle) và sứ mệnh của DevOps trong việc đảm bảo dòng chảy phần mềm liên tục và đáng tin cậy.
* **Tự động hóa hạ tầng (IaC):** Chấm dứt kỷ nguyên thao tác thủ công (ClickOps), chuyển sang quản trị hạ tầng bằng mã nguồn với bộ ba công cụ: CloudFormation, Terraform và CDK.
* **Chiến lược Container hóa:** Hiểu sâu kiến trúc và tiêu chí lựa chọn nền tảng vận hành Container tối ưu: App Runner cho đơn giản, ECS cho hiệu quả hoặc EKS cho sự linh hoạt.
* **Giám sát chủ động (Observability):** Thiết lập hệ thống "tai mắt" toàn diện để phát hiện sự cố và tối ưu hiệu năng thông qua CloudWatch và X-Ray.

---

## 2. DANH SÁCH DIỄN GIẢ
Sự kiện quy tụ các chuyên gia hàng đầu từ AWS và Cloud Engineering:
* **Đội ngũ chuyên gia AWS & Cloud Engineers** – Các kỹ sư và kiến trúc sư giải pháp chia sẻ về mô hình Platform Engineering và demo kỹ thuật thực chiến.

---

## 3. NỘI DUNG CHUYÊN MÔN NỔI BẬT

### 3.1. DevOps Mindset & CI/CD Pipeline (Nền Tảng Tư Duy)
Sự kiện tái định nghĩa DevOps không chỉ là công cụ, mà là văn hóa tối ưu hóa dòng chảy giá trị:
* **The Value Cycle (Vòng Đời Giá Trị):** Chu trình 5 giai đoạn khép kín từ Phân tích (Insights) $\rightarrow$ Danh mục (Portfolio) $\rightarrow$ Tích hợp (CI) $\rightarrow$ Kiểm thử (Testing) $\rightarrow$ Chuyển giao (CD). Mục tiêu là cân bằng giữa Tốc độ phát hành (Speed) và Sự ổn định (Stability).
* **Phân biệt rõ các cấp độ tự động hóa:**
    * *Continuous Integration (CI):* Merge code hàng ngày, tự động Build và Test để phát hiện lỗi sớm (Fail fast).
    * *Continuous Delivery:* Tự động deploy đến Staging, nhưng cần con người duyệt (Manual Trigger) để ra Production.
    * *Continuous Deployment:* Tự động hóa 100% dòng chảy từ Commit đến Production.
* **Chiến lược Pipeline tối ưu:**
    * *Centralized CI:* Xây dựng CI tập trung để quản lý nhưng trao quyền tự phục vụ (Self-service) cho Developer.
    * *Artifact Management:* Tuân thủ nguyên tắc **"Build Once, Deploy Anywhere"**. Chỉ đóng gói mã nguồn một lần duy nhất (Artifact) và dùng nó cho mọi môi trường để đảm bảo tính nhất quán.
    * *Điều kiện Fail:* Pipeline phải dừng ngay nếu gặp lỗi biên dịch, vi phạm chuẩn code, lỗ hổng bảo mật hoặc test quá chậm.
    * *Metrics:* Dùng Heatmap và các chỉ số DORA (Tần suất deploy, Tỷ lệ lỗi, MTTR) để đo lường sức khỏe quy trình.

### 3.2. Infrastructure as Code (IaC) - Từ ClickOps Đến Code
Hành trình loại bỏ rủi ro từ thao tác tay (ClickOps) để hướng tới sự Chính xác, Mở rộng và Cộng tác:
* **AWS CloudFormation (Native):** Sử dụng YAML/JSON để định nghĩa tài nguyên. Quản lý vòng đời qua khái niệm Stack (xóa Stack là dọn sạch tài nguyên).
* **Terraform (Multi-Cloud):** Sức mạnh mã nguồn mở với ngôn ngữ HCL. Quy trình chuẩn: Write $\rightarrow$ Plan (Xem trước thay đổi) $\rightarrow$ Apply. Điểm mạnh là khả năng quản lý đa nền tảng (AWS, Azure, GCP) và quản lý trạng thái qua State File.
* **AWS CDK (Code-based):** Định nghĩa hạ tầng bằng ngôn ngữ lập trình (Python, TypeScript...).
    * *Constructs:* Từ L1 (Cấu hình chi tiết) đến L3 (Patterns kiến trúc dựng sẵn).
    * *Drift Detection:* Tính năng sống còn để phát hiện sự sai lệch cấu hình do sửa thủ công, giúp duy trì kỷ luật hệ thống.

### 3.3. Containerization - Chiến Lược Chạy Ứng Dụng
Phân tích các lựa chọn điều phối (Orchestration) và tính toán (Compute):
* **So sánh ECS vs. EKS:**
    * *Amazon ECS:* Đơn giản, tích hợp chặt chẽ với hệ sinh thái AWS, phù hợp team muốn deploy nhanh, giảm vận hành.
    * *Amazon EKS:* Chuẩn Kubernetes, mạnh mẽ và linh hoạt, dành cho hệ thống Enterprise phức tạp hoặc Hybrid-cloud.
* **Mô hình tính toán:**
    * *EC2 Launch Type:* Kiểm soát tối đa nhưng tốn công quản lý server.
    * *AWS Fargate:* Serverless cho container, chỉ cần quan tâm CPU/RAM, AWS lo hạ tầng bên dưới.
    * *AWS App Runner:* Giải pháp "Zero-ops", đưa code/image thành Web App có HTTPS chỉ trong vài bước, không cần cấu hình mạng/server.

### 3.4. Observability - Giám Sát & Tối Ưu Hóa
Đảm bảo khả năng quan sát sâu rộng để vận hành ổn định:
* **Amazon CloudWatch:** Thu thập dữ liệu hiệu năng (Metrics), nhật ký tập trung (Logs) và tự động phản ứng (Alarms) khi hệ thống gặp sự cố.
* **AWS X-Ray:** Công cụ truy vết phân tán (Distributed Tracing), giúp vẽ lại hành trình request qua các microservices để tìm điểm nghẽn (Bottlenecks) và nguyên nhân gốc rễ.
* **Best Practices:** Phân biệt rõ vai trò của Logs (sự kiện) và Traces (hành trình); sử dụng các Patterns chuẩn của AWS để thiết lập giám sát.

---

## 4. TRẢI NGHIỆM CHI TIẾT TRONG EVENT

Chuyên đề này đã thay đổi hoàn toàn góc nhìn của tôi về vận hành hệ thống:

### 4.1. Sự chuyển dịch từ "Ops" sang "Platform Engineering"
Tôi nhận ra DevOps hiện đại không phải là người chạy theo Developer để deploy giúp họ. DevOps là người xây dựng "Đường cao tốc" (Pipeline & Platform). Một nền tảng tốt là nơi Developer có thể tự phục vụ (Self-service) nhu cầu hạ tầng trong khuôn khổ an toàn (Governance) mà đội ngũ DevOps đã thiết lập sẵn.

### 4.2. Kỷ luật trong vận hành (Operational Discipline)
Nguyên tắc **Artifact Management** và **Drift Detection** là bài học đắt giá. Trong môi trường doanh nghiệp, sự nhất quán (Consistency) là yếu tố sống còn. Tuyệt đối không build lại code ở từng môi trường khác nhau và nghiêm cấm việc sửa đổi cấu hình thủ công (Manual changes) khi đã áp dụng IaC.

### 4.3. Chiến lược lựa chọn công cụ thông minh
Không có công cụ "tốt nhất", chỉ có sự lựa chọn "phù hợp nhất":
* Cần sự ổn định và hỗ trợ native: Chọn **CloudFormation**.
* Doanh nghiệp đa nền tảng (Multi-cloud): **Terraform** là bắt buộc.
* Team mạnh về lập trình, cần tái sử dụng kiến trúc phức tạp: **AWS CDK** là vũ khí tối thượng.
* Web App đơn giản: Dùng **App Runner** thay vì lãng phí nhân lực vận hành Kubernetes.

---

## 5. KẾT LUẬN

Chuyên đề "DevOps & IaC Mastery" đã vẽ ra tấm bản đồ hoàn chỉnh cho hành trình hiện đại hóa trên Cloud:

* **Về Tư duy:** Chuyển dịch triệt để từ thủ công sang tự động hóa và đo lường bằng dữ liệu.
* **Về Hạ tầng:** Làm chủ IaC để đảm bảo khả năng mở rộng, tái tạo và kiểm soát cấu hình.
* **Về Vận hành:** Sự kết hợp giữa Containerization linh hoạt và Observability sâu rộng là chìa khóa cho một hệ thống hiệu năng cao và bền vững.

Đây là nền tảng kiến thức vững chắc để tôi tự tin xây dựng và vận hành các hệ thống phần mềm quy mô lớn trên AWS.

---

