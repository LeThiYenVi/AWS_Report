---
title: "Event 2"
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---

# BÁO CÁO THU HOẠCH SỰ KIỆN
**Sự kiện:** AWS Cloud Mastery Series #1: Generative AI, RAG & AWS Agentic AI

---

## 1. MỤC TIÊU THAM DỰ
Việc tham dự sự kiện tập trung vào 5 mục tiêu cốt lõi nhằm nâng cao năng lực kỹ thuật và tư duy chiến lược:
* **Prompt Engineering:** Thành thạo kỹ thuật Prompt Engineering để tối ưu hóa khả năng điều khiển các mô hình ngôn ngữ.
* **AWS AI Services:** Tìm hiểu hệ sinh thái các dịch vụ AI được huấn luyện sẵn (Pretrained AI Services) của AWS.
* **RAG Architecture:** Đi sâu vào quy trình xây dựng ứng dụng thông minh sử dụng kỹ thuật RAG (Retrieval-Augmented Generation).
* **Agentic AI:** Cập nhật xu hướng Agentic AI và phương pháp chuyển đổi AI Agent từ giai đoạn thử nghiệm (POC) sang vận hành thực tế (Production) thông qua Amazon Bedrock AgentCore.
* **Voice AI Framework:** Tiếp cận Pipecat – Framework hỗ trợ xây dựng trợ lý ảo tương tác bằng giọng nói trong thời gian thực.

---

## 2. DANH SÁCH DIỄN GIẢ
Sự kiện quy tụ các chuyên gia hàng đầu về AI và Cloud:
* **Lâm Tuấn Kiệt** – Sr DevOps Engineer (FPT Software)
* **Danh Hoàng Hiếu Nghị** – AI Engineer (Renova Cloud)
* **Đinh Lê Hoàng Anh** – Cloud Engineer Trainee (First Cloud AI Journey)

---

## 3. NỘI DUNG CHUYÊN MÔN NỔI BẬT

### 3.1. Prompt Engineering & Foundation Models (Nền Tảng Cốt Lõi)
Trước khi tiếp cận các dịch vụ nâng cao, sự kiện nhấn mạnh tầm quan trọng của việc giao tiếp hiệu quả với các Mô hình nền tảng (Foundation Models) trên Amazon Bedrock:
* **Zero-shot / Few-shot Prompting:** Kỹ thuật ra lệnh trực tiếp hoặc cung cấp một vài ví dụ mẫu để định hướng đầu ra mong muốn.
* **Chain of Thought (CoT):** Yêu cầu mô hình "suy luận từng bước", giúp nâng cao độ chính xác khi giải quyết các bài toán logic phức tạp.

### 3.2. Các Dịch Vụ AI Được Huấn Luyện Trước (AWS AI Services)
Giới thiệu bộ API tiện lợi, cho phép tích hợp trí tuệ nhân tạo mà không cần tốn công huấn luyện mô hình:
* **Hình ảnh/Video:** Amazon Rekognition.
* **Ngôn ngữ:** Amazon Translate, Comprehend, Textract (OCR).
* **Âm thanh:** Amazon Polly (Chuyển văn bản thành giọng nói), Transcribe (Chuyển giọng nói thành văn bản).

### 3.3. RAG - Retrieval Augmented Generation
Giải pháp giúp AI phản hồi dựa trên dữ liệu nội bộ của doanh nghiệp, giảm thiểu rủi ro cung cấp thông tin sai lệch:
* **Embeddings:** Ứng dụng Amazon Titan Text Embeddings V2 để vector hóa dữ liệu, phục vụ cho việc tìm kiếm theo ngữ nghĩa.
* **Knowledge Bases for Amazon Bedrock:** Quản lý toàn trình từ khâu phân mảnh dữ liệu (Chunking) $\rightarrow$ Lưu trữ Vector $\rightarrow$ Truy xuất (Retrieval) $\rightarrow$ Sinh câu trả lời (Generation).

### 3.4. Sự Tiến Hóa Lên Agentic AI (Kỷ Nguyên AI Tác Vụ)
Bức tranh tiến hóa của GenAI:
* **GenAI Assistants:** Hỗ trợ tự động hóa các tác vụ lặp lại theo quy tắc.
* **GenAI Agents:** Hướng tới mục tiêu cụ thể (Goal-oriented), xử lý chuỗi công việc rộng hơn.
* **Agentic AI Systems:** Hệ thống đa tác nhân (Multi-agent) hoạt động hoàn toàn tự chủ với sự can thiệp tối thiểu của con người.
* **Thách thức "Hố sâu ngăn cách" (The Prototype to Production Chasm):** Việc đưa Agent ra thị trường gặp rào cản lớn về Hiệu năng (Performance), Bảo mật & Quản trị (Security & Governance), và Sự phức tạp (Complexity) trong quản lý ngữ cảnh/kiểm toán.

### 3.5. Amazon Bedrock AgentCore: Giải Pháp Đưa Agent Ra Thị Trường
AWS giới thiệu AgentCore để giải quyết bài toán vận hành Agent:
* **Các thành phần cốt lõi:** Runtime & Memory (Môi trường chạy & Ghi nhớ), Identity & Gateway (Định danh & Kết nối), Code Interpreter (Tự viết và chạy code), Observability (Giám sát hoạt động).
* **Lợi ích:** Giúp lập trình viên tập trung vào logic nghiệp vụ thay vì loay hoay với hạ tầng bảo mật hay lưu trữ ngữ cảnh.

### 3.6. Pipecat: Framework Cho AI Voice Thời Gian Thực
Giới thiệu framework mã nguồn mở tối ưu cho các trợ lý ảo đa phương thức (Multimodal):
* **Đặc điểm:** Tối ưu cho độ trễ thấp (Real-time) và xử lý luồng (Streaming).
* **Cơ chế hoạt động:** WebRTC Input (Nhận âm thanh) $\rightarrow$ STT (Chuyển thành chữ) $\rightarrow$ LLM Processing (Xử lý) $\rightarrow$ TTS (Chuyển thành giọng nói) $\rightarrow$ Output (Phát lại).

---

## 4. TRẢI NGHIỆM CHI TIẾT TRONG EVENT

Buổi workshop đã giúp tôi mở rộng tầm nhìn từ những kiến thức nền tảng đến các công nghệ tiên phong đang định hình tương lai AI.

### 4.1. Sự chuyển dịch từ "Hỏi - Đáp" sang "Hành động" (Agentic AI)
Điều khiến tôi ấn tượng nhất là khái niệm Agentic AI. Nó thay đổi tư duy của tôi về AI từ việc chỉ biết chat/tóm tắt sang hình ảnh những "nhân viên ảo" có khả năng tự lập kế hoạch, sử dụng công cụ (duyệt web, viết code) để giải quyết vấn đề mà không cần cầm tay chỉ việc.

### 4.2. Giải quyết bài toán "Production"
Tôi đánh giá cao phần chia sẻ về "Hố sâu ngăn cách" giữa POC và Production. Các công cụ như Amazon Bedrock AgentCore thực sự là lời giải cho bài toán niềm tin của doanh nghiệp, nhờ vào các cơ chế bảo mật (Identity) và giám sát (Observability) chặt chẽ mà AWS cung cấp.

### 4.3. Tiềm năng của Voice AI với Pipecat
Phần demo Pipecat thực sự thú vị. Sự kết hợp giữa WebRTC và AI để tạo ra các cuộc hội thoại mượt mà, độ trễ cực thấp mở ra tiềm năng ứng dụng to lớn: từ Tổng đài ảo, Trợ lý phỏng vấn cho đến Giáo viên ngôn ngữ AI.

---

## 5. KẾT LUẬN

Buổi workshop "Generative AI & Agentic AI on AWS" đã vẽ nên một bức tranh toàn cảnh giá trị:

* **Hiện tại:** Chúng ta tối ưu hóa dữ liệu với RAG và Prompt Engineering.
* **Tương lai:** Kỷ nguyên Agentic AI đang đến gần, nơi các hệ thống tự chủ (Autonomous Agents) sẽ thay đổi cách vận hành doanh nghiệp.
* **Công cụ:** Với hệ sinh thái AWS (Bedrock, AgentCore) và các Framework (Pipecat, LangChain), rào cản kỹ thuật đang dần được xóa bỏ, tạo đà cho các kỹ sư hiện thực hóa những ý tưởng đột phá.

---

