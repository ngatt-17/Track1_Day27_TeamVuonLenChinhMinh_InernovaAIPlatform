# Track 1 - Day 27 — AI Team Lab: Internova AI Platform
**Đơn vị:** Track 1 - Day 27 AI Team Lab  
**Tên nhóm:** Team Vươn Lên Chính Mình  
**Danh sách 3 thành viên:**
1. **Vũ Huy Hoàng** — Trưởng nhóm (Leader) / Fullstack & Backend Developer
2. **Tạ Thị Nga** (`ngatt-17`) — AI Engineer (Mô hình, RAG Pipeline, Guardrails & AI Safety)
3. **Trần Hoài Nam** — AI Product & Domain Lead (Nghiệp vụ thực tập & Quản lý Knowledge Base)  
**Tên dự án:** Internova AI Platform (Hệ thống AI Quản lý & Tư vấn Thực tập Thông minh)  
**File bài nộp:** `Day27_AI-Team-Lab_TeamVuonLenChinhMinh.pdf` (Tối đa 4 trang chuẩn A4)

---

# TRANG 1 — STAKEHOLDER MAP & STRATEGY

## 1. Bối cảnh & Mục tiêu dự án (Gate 0)
* **Dự án:** Internova AI Platform — Nền tảng hỗ trợ và quản lý quá trình thực tập cho sinh viên, giảng viên và nhà trường bằng AI & RAG.
* **Mục tiêu 1–3 tháng tới:** Hoàn thiện phiên bản MVP với pipeline RAG trích dẫn chính xác quy chế (Groundedness ≥ 90%), triển khai thử nghiệm Pilot thành công cho 100 sinh viên và 3 giảng viên Khoa CNTT tại trường đại học đối tác.
* **Đội ngũ thực hiện (3 thành viên):**
  * **Vũ Huy Hoàng:** Trưởng nhóm (Leader) / Fullstack & Backend Lead (chịu trách nhiệm tổng hợp bài nộp và phát triển hệ thống nền tảng).
  * **Tạ Thị Nga:** AI Engineer / RAG Specialist (làm chủ kiến trúc RAG, Guardrails và đánh giá chất lượng AI).
  * **Trần Hoài Nam:** AI Product & Domain Lead (chịu trách nhiệm nghiệp vụ thực tập và tương tác với các bên liên quan).

---

## 2. Ma trận Stakeholder Map (Influence × Interest & Stance)

| Phân vùng ma trận | Stakeholder cụ thể & Vai trò | Mức độ ảnh hưởng (Influence) | Mức độ quan tâm (Interest) | Thái độ thực tế (Stance) | Lý do & Phân tích tâm lý |
|---|---|:---:|:---:|:---:|---|
| **Blocker** *(Ưu tiên thuyết phục)* | **TS. Nguyễn Minh Tuấn**<br>*(Trưởng phòng Đào tạo & QL Thực tập)* | **Cao** | **Trung bình / Thấp** | **Chưa ủng hộ / E ngại** | Lo ngại AI bị hallucination trả lời sai quy chế gây rủi ro pháp lý; e ngại việc lộ dữ liệu sinh viên. Có quyền cấp phép hoặc chặn triển khai pilot. |
| **Champion** *(Ủng hộ chủ chốt)* | **ThS. Hoàng Thu Hà**<br>*(Giảng viên điều phối thực tập Khoa CNTT)* | **Cao** | **Cao** | **Ủng hộ mạnh mẽ** | Bị quá tải bởi hàng trăm email hỏi trùng lặp về thủ tục, biểu mẫu. Cần công cụ theo dõi tiến độ sinh viên nộp báo cáo và giảm tải việc hành chính. |
| **Supporter** *(Người ủng hộ)* | **Bạn Trần Đức Anh**<br>*(Đại diện Sinh viên năm 3 sắp thực tập)* | **Thấp** | **Cao** | **Ủng hộ nhiệt tình** | Rất cần công cụ tự động tra cứu deadline, form mẫu, hỗ trợ rà soát CV khớp với Job Description. Là đối tượng trực tiếp hưởng lợi và lan tỏa. |
| **Bystander** *(Theo dõi định kỳ)* | **Chị Vũ Mai Lan**<br>*(HR Lead Doanh nghiệp đối tác tiếp nhận)* | **Thấp** | **Thấp** | **Trung lập** | Bận rộn với tuyển dụng chung, chỉ quan tâm nhận được hồ sơ sinh viên chất lượng, đúng hạn; chưa có thời gian tìm hiểu sâu về nền tảng nội bộ trường. |
| **Champion** *(Ủng hộ chuyên môn)* | **TS. Cố vấn Chuyên môn AI**<br>*(Mentor hướng dẫn kỹ thuật)* | **Cao** | **Cao** | **Ủng hộ mạnh mẽ** | Muốn thấy kiến trúc RAG & Guardrails được ứng dụng thực tế và kiểm soát chất lượng bằng benchmark khoa học; sẵn sàng hỗ trợ phản biện giải pháp. |
| **Blocker** *(Cần làm rõ kỹ thuật)* | **Thầy Đặng Quốc Việt**<br>*(Đại diện Trung tâm CNTT Nhà trường)* | **Cao** | **Thấp** | **Trung lập / Thận trọng** | Quan tâm tới an toàn thông tin mạng, tải hạ tầng máy chủ và rủi ro tấn công injection; cần xem kiến trúc an toàn trước khi kết nối. |

---

## 3. Bốn Stakeholder ưu tiên & Kế hoạch hành động cụ thể (1–2 tuần tới)

### Nhóm 1: Tận dụng sự ủng hộ mạnh mẽ (Champions & Strong Supporters)
1. **ThS. Hoàng Thu Hà (Giảng viên điều phối thực tập Khoa CNTT)**
   * *Họ quan tâm điều gì:* Giảm thiểu thời gian trả lời câu hỏi lặp lại; nắm bắt danh sách sinh viên có nguy cơ nộp muộn báo cáo thực tập.
   * *Họ có thể giúp thế nào:* Cung cấp toàn bộ tài liệu quy chế, sổ tay thực tập chuẩn và 50 câu hỏi sinh viên thường gặp nhất; làm cầu nối đưa 100 sinh viên tham gia pilot.
   * *Hành động cụ thể (7 ngày tới):* Trần Hoài Nam (Product) phối hợp cùng giảng viên chuẩn hóa bộ tài liệu Handbook thực tập để nạp vào Knowledge Base; Vũ Huy Hoàng bàn giao tài khoản Lecturer Portal thử nghiệm trước 17h00 thứ Sáu (04/09).
2. **TS. Cố vấn Chuyên môn AI (Mentor kỹ thuật)**
   * *Họ quan tâm điều gì:* Kiến trúc RAG vững chắc, kiểm soát hallucination, giải pháp Semantic Routing và hệ thống AI Observability đo độ trễ.
   * *Họ có thể giúp thế nào:* Đánh giá phương pháp luận, giới thiệu các kỹ thuật RAG tiên tiến (Hybrid Search, Re-ranking) và review bộ benchmark.
   * *Hành động cụ thể (10 ngày tới):* Tạ Thị Nga (AI Engineer) gửi báo cáo kết quả kiểm thử latency (P95 < 2s) và citation accuracy kèm bộ 30 golden test cases trước buổi review kỹ thuật ngày 06/09.

### Nhóm 2: Ưu tiên thuyết phục & Xử lý rủi ro (Blockers / Cần thuyết phục)
3. **TS. Nguyễn Minh Tuấn (Trưởng phòng Đào tạo & QL Thực tập)**
   * *Họ quan tâm điều gì:* Tuân thủ quy định đào tạo, độ chính xác tuyệt đối của thông tin cung cấp cho sinh viên, trách nhiệm pháp lý nếu AI phát ngôn sai.
   * *Họ có thể cản trở thế nào:* Phủ quyết hoặc đình chỉ chương trình thử nghiệm nếu thấy có rủi ro về mặt thông tin và pháp lý.
   * *Hành động cụ thể (7 ngày tới):* Vũ Huy Hoàng (Leader) và Trần Hoài Nam (Product) chuẩn bị tài liệu "Cam kết an toàn AI & Cơ chế Guardrails trích dẫn", trực tiếp gửi demo 20 câu hỏi quy chế có số điều/khoản trích dẫn đối chiếu; xin lịch họp báo cáo trực tiếp 20 phút vào sáng thứ Ba tuần tới (08/09).
4. **Thầy Đặng Quốc Việt (Đại diện Trung tâm CNTT Nhà trường)**
   * *Họ quan tâm điều gì:* An toàn hệ thống, bảo vệ dữ liệu cá nhân sinh viên, phân quyền truy cập và ranh giới mạng độc lập.
   * *Họ có thể cản trở thế nào:* Chậm trễ hoặc từ chối hỗ trợ kết nối tài nguyên thông tin trường.
   * *Hành động cụ thể (10 ngày tới):* Vũ Huy Hoàng (Fullstack Lead) gửi sơ đồ kiến trúc hệ thống chứng minh AI vận hành độc lập trên Cloud bảo mật, tuân thủ nguyên tắc "Privacy by Design" (không thu thập dữ liệu nhạy cảm của trường và không dùng dữ liệu nội bộ để huấn luyện mô hình công cộng).

---
\pagebreak

# TRANG 2 — PITCH "KẾT LUẬN TRƯỚC" & RACI MATRIX

## 1. Pitch gửi Ban Lãnh đạo Trường & Phòng Đào tạo (Conclusion First)

### [KẾT LUẬN / ĐỀ XUẤT]
> **Đề xuất Ban Đào tạo phê duyệt triển khai thử nghiệm (Pilot) nền tảng Internova AI Platform trong 4 tuần cho 100 sinh viên và 3 giảng viên Khoa CNTT trong kỳ thực tập học kỳ tới, bắt đầu từ ngày 15/09/2026.**

### [LÝ DO CHÍNH]
1. **Giải phóng 70% khối lượng tác vụ hành chính lặp lại:** Tự động giải đáp 24/7 toàn bộ câu hỏi về thủ tục, biểu mẫu, quy trình nộp hồ sơ bằng AI Assistant chuyên biệt, giúp giảng viên và chuyên viên đào tạo tập trung vào chuyên môn.
2. **Xóa bỏ tình trạng sinh viên trễ hạn & thiếu sót hồ sơ:** Hệ thống tự động theo dõi tiến độ từng sinh viên, thông báo hạn nộp báo cáo và cảnh báo sớm các trường hợp có nguy cơ chậm tiến độ cho giảng viên phụ trách.
3. **Đảm bảo 100% căn cứ quy định chính thức & an toàn dữ liệu:** AI được kiểm soát bằng cơ chế RAG có trích dẫn văn bản chính xác (citation), tuyệt đối không phỏng đoán hay đưa ra thông tin nằm ngoài quy chế nhà trường ban hành.

### [BẰNG CHỨNG & DỮ LIỆU THỰC NGHIỆM]
* Đã hoàn thiện phiên bản MVP và thực hiện kiểm thử nội bộ trên bộ **50 câu hỏi quy chế thực tập thực tế**: Đạt tỷ lệ trả lời đúng có trích dẫn điều khoản (Citation Accuracy) là **94%**, không phát hiện trường hợp hallucination ngoài phạm vi tài liệu.
* 100% giảng viên thử nghiệm đánh giá giao diện quản lý tiến độ trực quan, tiết kiệm trung bình **3.5 giờ/tuần** trong việc rà soát tình trạng thực tập của sinh viên.
* Hệ thống tích hợp sẵn cơ chế Semantic Router & Guardrails từ chối 100% các câu hỏi nằm ngoài nghiệp vụ thực tập.

### [SMALL ASK — ĐỀ NGHỊ HÀNH ĐỘNG NHỎ TIẾP THEO]
* **Kính đề nghị Thầy/Cô dành 30 phút vào thứ Năm tuần này (10/09 lúc 09h00) để nhóm demo trực tiếp sản phẩm trên 5 tình huống thực tế của trường và thống nhất danh sách 100 sinh viên tham gia đợt pilot thử nghiệm.**

---

## 2. Phản biện lớn nhất & Cách xử lý dựa trên bằng chứng

* **Ý kiến phản biện có khả năng xảy ra nhất:**  
  *"Nếu AI bị ảo giác (hallucination) đưa ra thông tin quy định sai lệch khiến sinh viên lỡ hạn tốt nghiệp, hoặc hệ thống làm lộ dữ liệu cá nhân của sinh viên thì nhà trường phải chịu rủi ro rất lớn."*
* **Câu trả lời & Phương án xử lý có căn cứ:**  
  1. **Kiến trúc Domain-Restricted RAG + Strict Citation:** Internova không phải là chatbot mở. AI chỉ sinh câu trả lời khi tìm thấy bằng chứng cụ thể trong Knowledge Base chính thống của trường và bắt buộc gắn kèm trích dẫn (Tên văn bản, Điều, Khoản). Nếu độ tương đồng dưới ngưỡng an toàn (Similarity Score < 0.80), AI tự động kích hoạt cơ chế Fallback: *"Quy định này chưa có trong văn bản chính thức, vui lòng liên hệ ThS. Hoàng Thu Hà để được hướng dẫn chính xác."*
  2. **Nguyên tắc "Privacy by Design":** Tách biệt rạch ròi giữa truy vấn kiến thức chung (không đính kèm thông tin người dùng) và dữ liệu cá nhân. Toàn bộ thông tin sinh viên được mã hóa trong PostgreSQL nội bộ, cam kết không sử dụng dữ liệu sinh viên để huấn luyện bất kỳ mô hình công cộng nào của OpenAI.

---

## 3. RACI Matrix (6 công việc trọng tâm trong 1–2 tháng tới)

*Quy tắc chuẩn: Mỗi công việc chỉ có DUY NHẤT một người chịu trách nhiệm cuối cùng (Accountable - A).*

| STT | Công việc trọng tâm | Leader / Fullstack<br>*(Vũ Huy Hoàng)* | AI Engineer<br>*(Tạ Thị Nga)* | Product Lead<br>*(Trần Hoài Nam)* | Giảng viên / Đào tạo<br>*(ThS. Hoàng Thu Hà)* |
|:---:|---|:---:|:---:|:---:|:---:|
| **1** | **Xác định Use Case, ranh giới an toàn (Guardrails) & kịch bản hội thoại** | I | C | **A** *(Chịu trách nhiệm)* | C *(Tư vấn)* |
| **2** | **Thu thập, số hóa & chuẩn hóa Knowledge Base quy chế thực tập** | I | C | **A** *(Chịu trách nhiệm)* | C *(Cung cấp)* |
| **3** | **Xây dựng & tối ưu RAG Pipeline (Embedding, Hybrid Search, Citation)** | C | **A** *(Chịu trách nhiệm)* | C | I |
| **4** | **Phát triển Web Portal (Student, Lecturer, Admin) & tích hợp API** | **A** *(Chịu trách nhiệm)* | C | C | I |
| **5** | **Thiết lập bộ Benchmark đánh giá chất lượng AI (AI Evals & Golden Cases)** | I | **A** *(Chịu trách nhiệm)* | C | C *(Phê duyệt đáp án)* |
| **6** | **Tổ chức vận hành chương trình Pilot thực tế & thu thập phản hồi** | **A** *(Chịu trách nhiệm)* | I | C | C *(Phối hợp)* |

*Ghi chú: A = Accountable (Chịu trách nhiệm cuối), R = Responsible (Người trực tiếp thực hiện), C = Consulted (Hỏi ý kiến), I = Informed (Thông báo kết quả).*

---
\pagebreak

# TRANG 3 — AI TEAM DESIGN

## 1. Lựa chọn AI Team Architecture: Embedded Cross-functional Squad
* **Mô hình lựa chọn:** **Embedded Squad** (Nhóm đa chức năng tích hợp trực tiếp).
* **Giải thích lý do lựa chọn:**  
  Ở giai đoạn hiện tại, dự án Internova đang tập trung toàn lực đưa 01 sản phẩm cốt lõi từ MVP đến Pilot. Quy mô nhóm 3 thành viên (Vũ Huy Hoàng, Tạ Thị Nga, Trần Hoài Nam) đòi hỏi tốc độ lặp (iteration) cao và sự gắn kết chặt chẽ giữa logic nghiệp vụ thực tập, giao diện người dùng và thuật toán AI. Mô hình Embedded giúp Trưởng nhóm/Fullstack, Kỹ sư AI và Phụ trách sản phẩm cùng trao đổi hàng ngày, loại bỏ độ trễ giao tiếp và sự quan liêu của mô hình Centralized.

---

## 2. Phân loại vai trò: Core Roles & Extended Roles

```text
┌──────────────────────────────────────────────────────────────────────────────────┐
│              INTERNOVA AI TEAM — EMBEDDED CROSS-FUNCTIONAL SQUAD                 │
├──────────────────────────────────────┬───────────────────────────────────────────┤
│    CORE ROLES (3 Thành viên hiện tại)│     EXTENDED ROLES (Giai đoạn mở rộng)    │
├──────────────────────────────────────┼───────────────────────────────────────────┤
│ • Leader / Fullstack: Vũ Huy Hoàng   │ • MLOps & Continuous Evaluation Engineer  │
│ • AI Engineer / RAG: Tạ Thị Nga      │ • Data Privacy & Compliance Specialist    │
│ • AI Product & Domain: Trần Hoài Nam │ • University & Industry Partnership Lead  │
└──────────────────────────────────────┴───────────────────────────────────────────┘
```

* **Core Roles (3 Thành viên hiện tại):**
  1. **Vũ Huy Hoàng — Trưởng nhóm (Leader) / Fullstack & Backend Engineer:** Điều phối chung dự án, xây dựng kiến trúc hệ thống backend FastAPI, cơ sở dữ liệu PostgreSQL, Next.js frontend, phân quyền và tích hợp API bảo mật.
  2. **Tạ Thị Nga — AI Engineer / RAG Specialist:** Làm chủ RAG architecture, semantic routing, vector index, prompt engineering, guardrails an toàn và hệ thống AI observability.
  3. **Trần Hoài Nam — AI Product & Domain Lead:** Hiểu sâu quy trình thực tập đại học, kiểm định chất lượng nội dung Knowledge Base, thiết kế trải nghiệm người dùng và tiếp nhận phản hồi từ nhà trường.
* **Extended Roles (Bổ sung khi scale sang 5–10 trường đại học):**
  1. **MLOps & Continuous Evaluation Engineer:** Tự động hóa pipeline đánh giá chất lượng mô hình, quản lý latency, caching và chi phí token khi lượng truy vấn tăng cao.
  2. **Data Privacy & Compliance Specialist:** Rà soát tuân thủ Nghị định 13/2023/NĐ-CP về bảo vệ dữ liệu cá nhân trong môi trường giáo dục.
  3. **Industry Partnership Lead:** Làm việc với các doanh nghiệp để mở rộng kho Job Description chuẩn và cơ hội thực tập cho sinh viên.

---

## 3. Năng lực còn thiếu (Capability Gaps) & Chiến lược bổ sung (Priority Resourcing)

| STT | Năng lực còn thiếu (Capability Gap) | Chiến lược bổ sung | Lý do lựa chọn giải pháp | Thời điểm cần |
|:---:|---|:---:|---|:---:|
| **1** | **Hệ thống đánh giá tự động chất lượng AI (AI Evals & Benchmark RAG)** | **Partner / Consult**<br>*(Hợp tác chuyên gia)* | Team hiện tại mạnh về phát triển ứng dụng nhưng cần chuẩn hóa bộ metric khoa học (Faithfulness, Answer Relevance). Hợp tác với Cố vấn AI giúp Tạ Thị Nga và team chuyển giao tri thức nhanh và tiết kiệm chi phí tuyển dụng. | **Cần ngay**<br>*(Trong 2 tuần tới)* |
| **2** | **Bộ dữ liệu Job Description chuẩn & Tiêu chí sàng lọc CV thực tế của HR** | **Partner**<br>*(Hợp tác doanh nghiệp)* | Nền tảng cần tiêu chí đánh giá CV sát với thực tế tuyển dụng của doanh nghiệp CNTT. Hợp tác với 3–5 đối tác doanh nghiệp tiếp nhận thực tập giúp có dữ liệu chuẩn mà không cần tuyển nhân sự HR full-time. | **Tuần thứ 4**<br>*(Trước khi mở tính năng CV)* |
| **3** | **Thiết kế UI/UX Portal chuyên nghiệp cho Sinh viên & Giảng viên** | **Outsource**<br>*(Thuê ngoài theo task)* | Giao diện hiện tại cơ bản. Cần thuê ngoài một UI/UX Designer hoàn thiện bộ Design System (Figma) trong 10 ngày để tạo độ tin cậy và chuyên nghiệp khi demo với Ban Giám hiệu nhà trường. | **Cần ngay**<br>*(Trong 1 tuần tới)* |

---

## 4. Tuyên ngôn mục tiêu của Squad (Squad Goal)
> *"Team của chúng tôi sở hữu **nền tảng Internova AI Platform** và chịu trách nhiệm đưa **quá trình tra cứu quy định và quản lý thực tập của sinh viên** từ hiện trạng **phân tán, bị động và quá tải thông tin hành chính** đến **trạng thái được tự động hóa 80% bởi trợ lý AI tin cậy, có trích dẫn minh chứng và theo dõi tiến độ thời gian thực trong 90 ngày tới**."*

---
\pagebreak

# TRANG 4 — TEAM HEALTH & GROWTH PLAN (30 NGÀY)

## 1. Đánh giá sức khỏe đội ngũ (Team Health Assessment)

| Khía cạnh đánh giá | Điểm (1–5) | Hiện trạng thực tế & Phân tích nguyên nhân |
|---|:---:|---|
| **Chất lượng AI** *(Output & Stability)* | **3.5 / 5** | AI trả lời rất tốt các câu hỏi đơn văn bản, nhưng độ chính xác giảm khi gặp câu hỏi suy luận chéo giữa nhiều văn bản quy định; chưa có bộ metric đo lường tự động độ tin cậy (Groundedness). |
| **Tiến độ** *(Milestones & Delivery)* | **4.0 / 5** | Các tính năng kỹ thuật cốt lõi hoàn thành đúng hạn; tuy nhiên tiến độ còn bị động do khâu thu thập văn bản quy chế chính thức từ các khoa mất nhiều thời gian hơn dự kiến. |
| **Tinh thần Team** *(Morale & Psychological Safety)* | **4.5 / 5** | Cả 3 thành viên (Hoàng, Nga, Nam) phối hợp cởi mở, thẳng thắn phản biện các lỗi hallucination của AI, chia sẻ công việc linh hoạt, tinh thần cam kết cao với mục tiêu pilot. |
| **Tốc độ ra sản phẩm** *(Release Velocity)* | **3.5 / 5** | Mất nhiều thời gian vào việc kiểm thử thủ công từng câu trả lời của AI trước mỗi lần release; thiếu pipeline CI/CD kiểm định tự động chất lượng AI khi cập nhật tài liệu mới. |

* **Vấn đề ưu tiên số 1 cần giải quyết:**  
  *Thiếu hệ thống đánh giá tự động (Automated Evaluation Benchmark) và bộ dữ liệu test chuẩn (Golden Dataset), dẫn đến quy trình kiểm thử tốn thời gian, làm chậm tốc độ release sản phẩm và tiềm ẩn rủi ro trả lời sai khi nạp thêm quy chế mới.*

---

## 2. Nâng cấp năng lực cá nhân (Competency Framework L1 → L2 → L3)
* **Vai trò được chọn:** **AI Engineer** *(Tạ Thị Nga)*
* **Cấp độ hiện tại:** **L2 — AI Practitioner** (Đã thành thạo triển khai pipeline RAG, tích hợp Semantic Routing, gọi LLM APIs và thiết lập Guardrails cơ bản).
* **Năng lực cốt lõi cần nâng cấp tiếp theo:** **Automated AI Evals & Observability Engineering** *(Tiệm cận L3 — AI Builder)*.
* **Hành động thực hành nâng cao trong 30 ngày:** Xây dựng bộ công cụ tự động đo lường Groundedness & Retrieval Context Recall bằng framework đánh giá chuyên biệt (sử dụng 30 golden test cases), tự động chạy sau mỗi lần cập nhật Knowledge Base để đảm bảo chất lượng AI đạt chuẩn trước khi deploy.

---

## 3. Kế hoạch hành động 30 ngày (30-Day Growth Plan)

| STT | Vấn đề trọng tâm | Hành động cụ thể trong 30 ngày | Người phụ trách *(Owner)* | Hạn chót *(Deadline)* | Dấu hiệu hoàn thành cụ thể *(Measurable Deliverable)* |
|:---:|---|---|:---:|:---:|---|
| **1** | **Chất lượng AI & Thiếu hệ thống kiểm thử tự động** | Xây dựng bộ "Golden Dataset" gồm 30 ca kiểm thử thực tế (gồm câu hỏi thông thường, câu hỏi suy luận chéo và câu hỏi bẫy); tích hợp script đo lường tự động chỉ số Groundedness ≥ 90% trước mỗi bản release. | **Tạ Thị Nga**<br>*(AI Engineer)* | **15/09/2026** | File `eval_benchmark.py` chạy thành công, tự động xuất báo cáo Groundedness Score ≥ 90% trên 30 test cases và chặn release nếu điểm dưới ngưỡng. |
| **2** | **Tốc độ ra sản phẩm & Trải nghiệm giao diện** | Tích hợp giao diện chuẩn hóa cho Student Portal và Lecturer Portal; bổ sung nút phản hồi "Đúng / Chưa chính xác" ngay dưới từng câu trả lời của AI để lưu vết đánh giá của người dùng vào cơ sở dữ liệu. | **Vũ Huy Hoàng**<br>*(Leader / Fullstack)* | **20/09/2026** | Giao diện Next.js hoàn thiện 100%, thời gian phản hồi API P95 < 1.5 giây, dữ liệu đánh giá của người dùng được lưu thành công vào bảng `ai_feedback` trong PostgreSQL. |
| **3** | **Tiến độ triển khai & Cam kết của Stakeholder** | Tổ chức buổi họp báo cáo demo thực tế với TS. Nguyễn Minh Tuấn (Phòng Đào tạo) và ThS. Hoàng Thu Hà; ký biên bản đồng thuận triển khai pilot cho 100 sinh viên Khoa CNTT. | **Trần Hoài Nam**<br>*(Product Lead)* | **25/09/2026** | Biên bản làm việc có chữ ký xác nhận của đại diện Khoa/Phòng Đào tạo đồng ý cho phép triển khai pilot đợt 1 từ ngày 01/10/2026. |

---

## 4. Kiểm tra tính nhất quán liên thông (Cross-Artefact Consistency Check)
*  **Trang 1 ↔ Trang 2:** Stakeholder trọng tâm cần thuyết phục ở Trang 1 (TS. Nguyễn Minh Tuấn) chính là đối tượng mục tiêu nhận bản Pitch "Conclusion First" ở Trang 2, đồng thời giảng viên ủng hộ (ThS. Hoàng Thu Hà) xuất hiện với vai trò Consulted/Phối hợp trong RACI.
*  **Trang 3 ↔ Trang 4:** Năng lực còn thiếu (Capability Gap 1: AI Evals) ở Trang 3 được giải quyết trực tiếp thông qua hành động nâng cấp năng lực AI Engineer (Tạ Thị Nga) và Action 1 trong Growth Plan 30 ngày ở Trang 4.
*  **RACI ↔ Growth Plan:** Người phụ trách (Owner) trong Growth Plan 30 ngày (Tạ Thị Nga, Vũ Huy Hoàng, Trần Hoài Nam) hoàn toàn trùng khớp với vai trò Accountable (A) cho từng mảng công việc tương ứng trong ma trận RACI.
