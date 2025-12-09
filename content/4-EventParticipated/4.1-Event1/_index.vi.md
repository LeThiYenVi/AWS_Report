---
title: "Event 1"
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

# BÁO CÁO THU HOẠCH SỰ KIỆN
**Sự kiện:** Vietnam Cloud Day 2025: Ho Chi Minh City Connect Edition for Builders  
**Chuyên đề (Track 1):** GenAI & Data

---

## 1. MỤC TIÊU THAM DỰ
Việc tham dự sự kiện tập trung vào 4 mục tiêu cốt lõi nhằm nâng cao năng lực kỹ thuật và tư duy chiến lược:
* **Bảo mật GenAI:** Tìm hiểu cơ chế bảo mật trong GenAI và AI Agent để đảm bảo an toàn dữ liệu doanh nghiệp.
* **Quy trình phát triển (AI-DLC):** Khám phá mô hình *AI-Driven Development Lifecycle* và cách tích hợp vào quy trình DevOps hiện tại.
* **Nền tảng dữ liệu:** Phương pháp xây dựng nền tảng dữ liệu hợp nhất (Unified Data Platform) tối ưu cho Analytics và AI.
* **Cập nhật xu hướng:** Nắm bắt chiến lược, tầm nhìn và các công nghệ GenAI mới nhất trên AWS.

---

## 2. DANH SÁCH DIỄN GIẢ (AWS EXPERTS)
Sự kiện quy tụ các chuyên gia hàng đầu từ Amazon Web Services:
* **Jun Kai Loke** – AI/ML Specialist SA
* **Kien Nguyen** – Solutions Architect
* **Tamelly Lim** – Storage Specialist SA
* **Binh Tran** – Senior Solutions Architect
* **Taiki Dang** – Solutions Architect
* **Michael Armentano** – Principal WW GTM Specialist

---

## 3. NỘI DUNG CHUYÊN MÔN NỔI BẬT

### 3.1. Nền tảng dữ liệu thống nhất (Unified Data Platform)
Dữ liệu là nền tảng cốt lõi ("Data is the fuel") để triển khai AI thành công.
* **Kiến trúc End-to-End:** Quy trình khép kín từ Ingestion $\rightarrow$ Lưu trữ $\rightarrow$ Xử lý $\rightarrow$ Truy cập $\rightarrow$ Quản trị.
* **Mục tiêu:** Xóa bỏ "Silo" (sự cô lập) về dữ liệu, con người và quy trình. Hướng tới Self-service và chuẩn hóa Governance.
* **Dịch vụ AWS chủ chốt:** S3, Glue, Redshift, Lake Formation, OpenSearch, Kinesis/MSK.
* **Công nghệ nổi bật:** **Zero-ETL integration** (kết nối S3 $\leftrightarrow$ Redshift, Aurora, DynamoDB...) giúp giảm thiểu độ trễ và phức tạp trong luân chuyển dữ liệu.

### 3.2. Chiến lược & Công cụ GenAI trên AWS
* **Amazon Bedrock:** Dịch vụ chủ đạo cho phép lựa chọn Foundation Models (FM), tích hợp RAG, Guardrails, tối ưu hóa giữa chi phí và độ trễ.
* **Amazon SageMaker Unified Studio:** Nền tảng hợp nhất cho Data, Analytics & AI. Hỗ trợ MLOps toàn diện (Pipelines, Registry, Deployment, Monitoring).
* **AI Agents - Tăng cường năng suất:** Chuyển dịch từ Assistant đơn lẻ sang Multi-agent systems (như AgentCore, Amazon Nova). Hỗ trợ các framework: CrewAI, LangGraph, LlamaIndex.
* **Ứng dụng thực tế:** Chăm sóc khách hàng (CSKH), Business Intelligence (BI) với Amazon Q (trong QuickSight), tự động hóa quy trình nghiệp vụ.

### 3.3. Bảo mật & Độ tin cậy của GenAI (Security & Trust)
* **Mô hình bảo mật đa lớp:** Bảo vệ từ Hạ tầng $\rightarrow$ Mô hình $\rightarrow$ Ứng dụng.
* **5 Trụ cột bảo mật:** Compliance, Privacy, Controls, Risk Management, Resilience.
* **Giảm thiểu ảo giác (Hallucination):** Kết hợp Prompt Engineering, RAG (Retrieval-Augmented Generation), và Fine-tuning.
    * *Quy trình RAG:* Input $\rightarrow$ Embedding $\rightarrow$ Context $\rightarrow$ LLM $\rightarrow$ Output.
* **Công cụ kiểm soát:** Bedrock Guardrails, Human-in-the-loop, Observability (OpenTelemetry) để phòng chống rủi ro theo chuẩn OWASP LLM.

### 3.4. AI-Driven Development Lifecycle (AI-DLC)
Một khái niệm mới về vòng đời phát triển phần mềm:
* **Tiến hóa:** AI-Assisted $\rightarrow$ AI-Driven $\rightarrow$ AI-Managed.
* **Các giai đoạn:** Inception (Khởi tạo) $\rightarrow$ Construction (Xây dựng) $\rightarrow$ Operation (Vận hành).
* **Triển khai:** Tích hợp Infrastructure as Code (IaC), kiểm thử tự động, giám sát và quản trị rủi ro ngay trong quy trình.

---

## 4. TỔNG HỢP BÀI HỌC & TƯ DUY MỚI (KEY TAKEAWAYS)

Sau sự kiện, tôi đã đúc kết được những thay đổi quan trọng về tư duy và chiến lược:

1.  **Tư duy thiết kế hệ thống (Design Thinking):**
    * Phải thiết kế hệ thống Dữ liệu & AI theo hướng **End-to-end**, kiên quyết loại bỏ Data Silo.
    * Áp dụng nguyên tắc **Self-service** và **Governance** ngay từ giai đoạn đầu.

2.  **Kiến trúc kỹ thuật (Technical Architecture):**
    * Tận dụng sức mạnh của **Zero-ETL** và **Lakehouse** để hệ thống vận hành bền vững, dễ mở rộng.
    * Kết hợp các mảnh ghép dịch vụ (S3, Glue, Bedrock...) thành một nền tảng thống nhất thay vì các công cụ rời rạc.

3.  **Chiến lược phát triển (Development Strategy):**
    * **Business-first:** Mọi quyết định công nghệ phải xuất phát từ bài toán kinh doanh. Dữ liệu và Bảo mật là nền tảng ("Foundation"), không có nền móng này thì AI không thể phát huy giá trị.
    * **Cân bằng:** Giữa tốc độ đổi mới (Innovation) và chi phí/an toàn (Cost/Security).
    * **AI-DLC:** Chuẩn hóa quy trình phát triển với sự tham gia của AI ở mọi giai đoạn (Code, Review, Test, Doc).

---

## 5. KẾ HOẠCH ỨNG DỤNG VÀO CÔNG VIỆC

Dựa trên những kiến thức đã học, tôi đề xuất kế hoạch ứng dụng cụ thể như sau:

**Trong dự án thực tế:**
* Triển khai thử nghiệm **AI Agent** cho module Đăng ký/Đăng nhập và Hỗ trợ khách hàng (Chatbot).
* Tích hợp **Validation/Guardrails** để đảm bảo an toàn dữ liệu đầu vào/ra của GenAI.

**Trong học tập & Teamwork:**
* Áp dụng mô hình **AI-DLC**: Sử dụng AI để hỗ trợ viết code khung (boilerplate), tạo tài liệu kỹ thuật; con người tập trung vào Review và Approve.
* Phân tích rõ ràng khi nào sử dụng **Serverless (Lambda)** (cho tác vụ ngắn, sự kiện) và khi nào dùng **Container (ECS/Fargate)** (cho ứng dụng dài hạn, phức tạp).

**Trong vai trò cá nhân:**
* Rèn luyện tư duy viết tài liệu và thu thập yêu cầu theo hướng Business-first.
* Tập trung xây dựng Data Foundation vững chắc trước khi triển khai các mô hình AI phức tạp.

---

## 6. TRẢI NGHIỆM SỰ KIỆN & WORKSHOP
*(Phần ghi nhận trải nghiệm thực tế tại sự kiện)*

Điểm nhấn đáng nhớ nhất là Workshop **"GenAI-powered App-DB Modernization"**. Đây là cơ hội quý giá để tôi thực hành hiện đại hóa ứng dụng và cơ sở dữ liệu:
* **Trải nghiệm kỹ thuật:** Tự tay thiết kế pipeline dữ liệu end-to-end và tiếp cận các công cụ mới nhất như Amazon Bedrock, AgentCore.
* **Thực hành RAG:** Hiểu sâu về cách giảm thiểu Hallucination thông qua việc phối hợp Prompt Engineering và RAG workflow.
* **Kết nối chuyên gia:** Trao đổi trực tiếp với các kỹ sư AWS về các Case Study thực tế, giúp củng cố niềm tin vào mô hình Multi-agent và AI-DLC.

> **Kết luận:** GenAI không chỉ là một công cụ xu hướng (trend), mà đòi hỏi một chiến lược tổng thể từ Kiến trúc hạ tầng, Dữ liệu đến Bảo mật để thực sự mang lại giá trị cho doanh nghiệp.

---

