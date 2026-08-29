
# Internova AI Platform

> **AI-powered Internship Support Platform for Students, Lecturers, and Universities**

## 1. Tổng quan dự án

**Internova AI Platform** là hệ thống hỗ trợ quản lý và tư vấn quá trình thực tập cho sinh viên bằng trí tuệ nhân tạo.

Nền tảng được xây dựng nhằm giải quyết tình trạng thông tin thực tập bị phân tán giữa nhiều tài liệu, email, biểu mẫu và hệ thống khác nhau. Internova tập trung các quy trình này vào một nền tảng duy nhất, đồng thời sử dụng **AI và Retrieval-Augmented Generation (RAG)** để giúp người dùng tìm kiếm và sử dụng thông tin chính xác hơn.

Hệ thống hướng tới ba nhóm người dùng chính:

* **Sinh viên**
* **Giảng viên**
* **Nhà trường / Quản trị viên**

Trong tương lai, nền tảng có thể mở rộng thêm khả năng kết nối với **doanh nghiệp và supervisor thực tập**.

---

# 2. Vấn đề cần giải quyết

Trong quá trình thực tập, sinh viên thường gặp các vấn đề như:

* Không biết chính xác bước tiếp theo cần thực hiện.
* Khó tìm quy định hoặc biểu mẫu phù hợp.
* Thông tin nằm rải rác trong nhiều tài liệu.
* Không biết deadline hoặc yêu cầu cụ thể.
* Khó xác định doanh nghiệp/vị trí phù hợp với CV.
* Phải hỏi lại giảng viên hoặc bộ phận quản lý nhiều lần.

Ở phía nhà trường và giảng viên:

* Khó theo dõi tiến độ của nhiều sinh viên cùng lúc.
* Việc quản lý báo cáo và trạng thái thực tập còn phân tán.
* Cập nhật quy định/tài liệu mới khó đồng bộ tới hệ thống AI.
* Việc phát hiện sinh viên chậm tiến độ chưa được tự động hóa đầy đủ.

Internova được xây dựng để giải quyết các vấn đề này.

---

# 3. Mục tiêu sản phẩm

Mục tiêu của Internova không đơn thuần là xây dựng một chatbot.

Mục tiêu chính là:

> **Giúp sinh viên biết đúng việc cần làm tiếp theo trong quá trình thực tập dựa trên nguồn thông tin đáng tin cậy, đồng thời giúp giảng viên và nhà trường quản lý quá trình thực tập hiệu quả hơn.**

Internova hướng tới một hệ thống có thể:

* Hỗ trợ sinh viên trong toàn bộ internship lifecycle.
* Cung cấp câu trả lời dựa trên tài liệu chính thức.
* Hạn chế hallucination của AI.
* Quản lý và cập nhật Knowledge Base.
* Hỗ trợ CV và cơ hội nghề nghiệp.
* Theo dõi tiến độ thực tập.
* Hỗ trợ giảng viên quản lý sinh viên.
* Cung cấp monitoring cho hệ thống AI.

---

# 4. Người dùng chính

## 4.1 Sinh viên

Sinh viên là nhóm người dùng chính của nền tảng.

Internova giúp sinh viên:

* Tra cứu quy định thực tập.
* Tìm biểu mẫu cần thiết.
* Hỏi các bước cần thực hiện.
* Theo dõi tiến độ thực tập.
* Kiểm tra deadline.
* Chuẩn bị báo cáo.
* Phân tích CV.
* So khớp CV với Job Description.
* Chuẩn bị phỏng vấn.
* Nhận gợi ý liên quan đến internship và career preparation.

---

## 4.2 Giảng viên

Giảng viên sử dụng Internova để:

* Theo dõi sinh viên phụ trách.
* Xem tiến độ thực tập.
* Theo dõi báo cáo.
* Phát hiện sinh viên có nguy cơ chậm tiến độ.
* Giảm thời gian trả lời các câu hỏi lặp lại.
* Quản lý quy trình liên quan đến sinh viên.

---

## 4.3 Nhà trường / Administrator

Administrator chịu trách nhiệm quản lý hệ thống.

Các chức năng chính bao gồm:

* Quản lý người dùng.
* Quản lý tài liệu.
* Quản lý Knowledge Base.
* Quản lý version tài liệu.
* Theo dõi tình trạng indexing.
* Theo dõi hệ thống AI.
* Theo dõi latency và lỗi.
* Quản lý quyền truy cập.
* Quản lý các cấu hình liên quan đến hệ thống.

---

# 5. Các chức năng chính

## 5.1 AI Internship Assistant

Internova cung cấp chatbot AI chuyên biệt cho các vấn đề liên quan đến:

* Internship.
* Quy trình thực tập.
* Chính sách.
* Biểu mẫu.
* CV.
* Job Description.
* CV–JD Matching.
* Interview preparation.
* Career preparation liên quan tới internship.

Chatbot được thiết kế theo hướng **domain-restricted AI**, không phải chatbot hỏi gì cũng trả lời.

---

## 5.2 Retrieval-Augmented Generation — RAG

Internova sử dụng kiến trúc **RAG** để đưa thông tin từ Knowledge Base vào quá trình tạo câu trả lời.

Luồng xử lý cơ bản:

```text
User Question
      ↓
Guardrails
      ↓
Intent / Semantic Routing
      ↓
Query Processing
      ↓
Retrieval
      ↓
Relevant Documents
      ↓
Evidence / Context
      ↓
LLM Generation
      ↓
Groundedness / Validation
      ↓
Final Answer
```

Mục tiêu là để AI không chỉ dựa vào kiến thức có sẵn của model mà ưu tiên sử dụng tài liệu chính thức của hệ thống.

---

# 6. Knowledge Base

Knowledge Base là thành phần quan trọng của Internova.

Administrator có thể quản lý:

* Tài liệu.
* Loại tài liệu.
* Version.
* Trạng thái tài liệu.
* Năm áp dụng.
* Nội dung được sử dụng bởi RAG.

Khi một tài liệu mới được thêm hoặc version mới được cập nhật, mục tiêu của hệ thống là đồng bộ tài liệu đó vào pipeline RAG để chatbot có thể sử dụng mà không cần xây dựng lại toàn bộ hệ thống.

Luồng dự kiến:

```text
Admin Upload Document
        ↓
Validation
        ↓
Document Storage
        ↓
Parsing
        ↓
Chunking
        ↓
Embedding / Indexing
        ↓
Knowledge Base
        ↓
RAG Retriever
        ↓
Available to Chatbot
```

---

# 7. CV–JD Matching

Internova hỗ trợ phân tích mức độ phù hợp giữa:

```text
Student CV
    +
Job Description
    ↓
AI Analysis
    ↓
Matching Result
```

Hệ thống có thể hỗ trợ đánh giá:

* Kỹ năng phù hợp.
* Kỹ năng còn thiếu.
* Keyword quan trọng.
* Kinh nghiệm.
* Education.
* Mức độ match tổng thể.
* Gợi ý cải thiện CV.

Mục tiêu là hỗ trợ sinh viên lựa chọn internship phù hợp hơn thay vì chỉ tìm kiếm vị trí một cách thủ công.

---

# 8. Internship Progress Management

Internova không chỉ cung cấp chatbot mà còn hướng tới quản lý toàn bộ quá trình internship.

Ví dụ workflow:

```text
Internship Preparation
        ↓
Registration
        ↓
Company / Position
        ↓
Approval
        ↓
Internship Progress
        ↓
Reports
        ↓
Lecturer Review
        ↓
Completion
```

Sinh viên có thể theo dõi trạng thái của mình trong khi giảng viên có thể quan sát tiến độ của các sinh viên được phân công.

---

# 9. AI Safety & Guardrails

Internova áp dụng guardrails trước khi câu hỏi được chuyển vào RAG/LLM.

AI được giới hạn chủ yếu trong các domain:

```text
Internship
Career preparation
CV
CV–JD Matching
Internship-related university information
```

Những câu hỏi nằm ngoài phạm vi hệ thống có thể bị từ chối hoặc điều hướng lại.

Mục tiêu của cơ chế này là:

* Giảm prompt injection.
* Giảm sử dụng AI ngoài mục đích.
* Giảm hallucination.
* Bảo vệ dữ liệu người dùng.
* Giữ chatbot đúng domain.

---

# 10. Privacy

Một nguyên tắc quan trọng của Internova là:

> **Thông tin cá nhân chỉ được sử dụng khi thực sự cần thiết cho yêu cầu của chính người dùng.**

Hệ thống cần phân biệt giữa:

```text
General Knowledge Request
```

và:

```text
Personal Data Request
```

Ví dụ:

**General**

> Quy trình đăng ký internship như thế nào?

→ Trả lời từ Knowledge Base.

**Personal**

> Deadline thực tập của tôi là khi nào?

→ Có thể cần sử dụng dữ liệu cá nhân của người dùng đã xác thực.

Thông tin cá nhân không nên được đưa vào các câu trả lời chung không liên quan.

---

# 11. Kiến trúc tổng quan

Internova sử dụng kiến trúc web application kết hợp AI backend.

```text
┌──────────────────────────────┐
│          Frontend            │
│           Next.js            │
│                              │
│ Student │ Lecturer │ Admin   │
└──────────────┬───────────────┘
               │
               │ REST / Streaming API
               ↓
┌──────────────────────────────┐
│           Backend            │
│           FastAPI            │
│                              │
│ Authentication               │
│ Business Services            │
│ Internship Services          │
│ Knowledge Management         │
│ Chat Services                │
└──────────────┬───────────────┘
               │
               ↓
┌──────────────────────────────┐
│          AI Layer            │
│                              │
│ Guardrails                   │
│ Semantic Router              │
│ RAG Pipeline                 │
│ Retriever                    │
│ LLM                          │
│ Evaluation                   │
└──────────────┬───────────────┘
               │
               ↓
┌──────────────────────────────┐
│           Data               │
│                              │
│ PostgreSQL                   │
│ Vector / Retrieval Index     │
│ Knowledge Documents          │
└──────────────────────────────┘
```

---

# 12. Technology Stack

## Frontend

```text
Next.js
React
TypeScript
CSS
```

## Backend

```text
Python
FastAPI
Uvicorn
```

## Database

```text
PostgreSQL
```

## AI

```text
OpenAI
Retrieval-Augmented Generation
Semantic Routing
Hybrid Retrieval
Guardrails
AI Evaluation
```

## Development

```text
Git
GitHub
Feature Branch Workflow
```

---

# 13. AI Observability

Internova có hệ thống monitoring nhằm theo dõi hoạt động của AI.

Các metric quan trọng bao gồm:

* Request count.
* Error rate.
* Latency.
* P95 latency.
* P99 latency.
* Retrieval performance.
* Generation performance.
* AI quality.
* System failures.

Ví dụ:

```text
User Request
      ↓
Trace
      ↓
Guardrail
      ↓
Routing
      ↓
Retrieval
      ↓
Generation
      ↓
Validation
      ↓
Latency + Quality Metrics
```

Điều này giúp team xác định chính xác bottleneck thay vì chỉ biết rằng chatbot đang "chậm".

---

# 14. Vai trò của AI trong Internova

AI không thay thế toàn bộ hệ thống nghiệp vụ.

Internova sử dụng AI như một lớp intelligence nằm trên business system.

```text
Business System
+
University Data
+
Knowledge Base
+
AI
=
Internova
```

AI chịu trách nhiệm cho những bài toán phù hợp như:

* Hiểu intent.
* Semantic search.
* Retrieval.
* Question answering.
* Document understanding.
* CV analysis.
* Matching.
* Recommendation.

Trong khi các nghiệp vụ quan trọng vẫn được kiểm soát bằng backend và database.

---

# 15. Stakeholder

Các stakeholder chính của Internova gồm:

| Stakeholder      | Vai trò                                        |
| ---------------- | ----------------------------------------------- |
| Sinh viên       | Người sử dụng chính                        |
| Giảng viên     | Theo dõi và hỗ trợ sinh viên               |
| Nhà trường    | Quản lý internship program                    |
| Administrator    | Quản trị hệ thống và Knowledge Base        |
| Doanh nghiệp    | Cung cấp cơ hội và môi trường thực tập |
| Supervisor       | Hướng dẫn sinh viên tại doanh nghiệp      |
| Development Team | Xây dựng và vận hành sản phẩm            |

---

# 16. Nguyên tắc phát triển

Internova được phát triển theo một số nguyên tắc chính:

### Accuracy over fluency

Một câu trả lời chính xác và có evidence quan trọng hơn một câu trả lời nghe tự nhiên nhưng không có căn cứ.

### Domain-first AI

AI phải hiểu rõ phạm vi sản phẩm và không cố trả lời mọi câu hỏi.

### Privacy by design

Dữ liệu cá nhân không được sử dụng khi không cần thiết.

### Evidence-based answers

Các câu trả lời liên quan đến chính sách và quy định nên dựa trên Knowledge Base.

### Production-oriented development

Mỗi feature cần được xem xét về:

* Reliability.
* Security.
* Latency.
* Maintainability.
* Monitoring.
* User experience.

---

# 17. Trạng thái phát triển

Internova hiện đang được phát triển theo hướng một **production-ready AI application** thay vì chỉ là AI prototype.

Các nhóm chức năng đang được xây dựng và hoàn thiện bao gồm:

* Student Portal.
* Lecturer Portal.
* Admin Portal.
* AI Chatbot.
* RAG Knowledge Base.
* Document Management.
* Document Version Management.
* CV Matching.
* Internship Progress Management.
* AI Monitoring.
* Authentication & Authorization.
* Privacy Guardrails.
* UI/UX.

---

# 18. Hướng phát triển tiếp theo

Các ưu tiên tiếp theo của Internova bao gồm:

### AI Quality

* Cải thiện retrieval accuracy.
* Xây dựng evaluation dataset.
* Automated AI evaluation.
* Giảm hallucination.
* Tối ưu latency.

### Knowledge Management

* Automatic document ingestion.
* Version synchronization.
* Re-indexing workflow.
* Document validation.

### Internship Management

* Progress tracking.
* Deadline management.
* Lecturer alerts.
* Report workflow.
* Risk detection.

### Engineering

* Automated testing.
* Regression testing.
* Production monitoring.
* CI/CD.
* Error tracking.

### Product

* Pilot với người dùng thực tế.
* Thu thập feedback.
* Đo product metrics.
* Điều chỉnh UX.
* Mở rộng từ VinUni sang các tổ chức khác khi sản phẩm đủ ổn định.

---

# 19. Vision

Internova hướng tới trở thành:

> **Một AI-powered Internship Operating System giúp kết nối sinh viên, giảng viên, nhà trường và doanh nghiệp trong toàn bộ quá trình thực tập.**

Thay vì để sinh viên phải tự tìm kiếm giữa hàng loạt tài liệu, email và biểu mẫu, Internova hướng tới cung cấp một điểm truy cập duy nhất:

```text
Ask
Track
Prepare
Apply
Report
Improve
```

Tất cả trong một nền tảng duy nhất.

---

## Project

**Internova AI Platform**

**Domain:** AI · Education · Internship Management · Career Technology

**Current Focus:** AI-powered internship support and management platform

**Status:** Active Development
