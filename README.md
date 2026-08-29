# Phase 0 — Scope & Working Setup

## 1. Thành viên team

**Team:** Vươn Lên Chính Mình

| STT | Họ và tên    | Mã học viên |
| --: | --------------- | -------------- |
|   1 | Vũ Huy Hoàng  | 2A202601057    |
|   2 | Tạ Thị Nga   | 2A202601125    |
|   3 | Trần Hoài Nam | 2A202601751    |

**Quy mô team:** 3 thành viên — đáp ứng yêu cầu của Lab.

**Truy cập phiên bản demo của hệ thống tại:**

[https://internova-ai-platform.vercel.app/](https://internova-ai-platform.vercel.app/)

---

## 2. Tên dự án

**Internova AI Platform**

Internova là nền tảng AI hỗ trợ sinh viên trong quá trình thực tập. Hệ thống kết hợp AI, Retrieval-Augmented Generation (RAG) và các chức năng quản lý internship để hỗ trợ sinh viên, giảng viên và nhà trường.

Các chức năng chính của Internova gồm:

* AI Chatbot hỗ trợ tra cứu thông tin thực tập.
* Tra cứu chính sách, quy định và tài liệu.
* Knowledge Base và quản lý version tài liệu.
* CV–JD Matching.
* Theo dõi tiến độ thực tập.
* Quản lý báo cáo.
* Lecturer Portal hỗ trợ giảng viên theo dõi sinh viên.
* Admin Portal quản lý tài liệu, người dùng và hệ thống AI.
* AI Monitoring để theo dõi latency, lỗi và chất lượng hệ thống.

---

## 3. Mục tiêu hiện tại trong 1–3 tháng tới

Trong 1–3 tháng tới, team tập trung đưa Internova từ giai đoạn phát triển hiện tại tới một phiên bản ổn định hơn và đủ khả năng thử nghiệm với người dùng thực tế.

### Các mục tiêu chính

1. **Hoàn thiện các chức năng cốt lõi**

   * Student Portal.
   * Lecturer Portal.
   * Admin Portal.
   * Internship workflow.
2. **Hoàn thiện AI Chatbot và RAG**

   * Cải thiện retrieval accuracy.
   * Giảm hallucination.
   * Tăng độ chính xác của câu trả lời.
   * Giảm latency.
   * Hoàn thiện guardrails.
3. **Hoàn thiện Knowledge Base**

   * Thêm tài liệu mới.
   * Quản lý version tài liệu.
   * Đồng bộ tài liệu mới vào RAG.
   * Đảm bảo chatbot sử dụng đúng tài liệu hiện hành.
4. **Hoàn thiện CV–JD Matching**

   * Phân tích CV.
   * So khớp CV với Job Description.
   * Xác định skill gap.
   * Đưa ra gợi ý cải thiện CV.
5. **Cải thiện chất lượng kỹ thuật**

   * Tăng automated testing.
   * Giảm regression bug.
   * Cải thiện monitoring.
   * Hoàn thiện authentication và authorization.
   * Tăng độ ổn định của backend và frontend.
6. **Chuẩn bị cho pilot**

   * Thu thập feedback từ sinh viên.
   * Demo với giảng viên/mentor.
   * Xác định yêu cầu từ phía nhà trường.
   * Chuẩn bị phạm vi thử nghiệm nhỏ với người dùng thực tế.

### Mục tiêu tổng quát

> **Trong 1–3 tháng tới, team hướng tới hoàn thiện Internova thành một AI-powered Internship Support Platform ổn định, chính xác, an toàn và đủ khả năng pilot với người dùng thực tế.**

---

## 4. Trưởng nhóm / Người tổng hợp

**Vũ Huy Hoàng — 2A202601057**

### Trách nhiệm

* Tạo và quản lý GitHub repository của Day 27.
* Tổng hợp kết quả làm việc của ba thành viên.
* Đảm bảo các artefact sử dụng cùng một project scope.
* Kiểm tra sự nhất quán giữa Stakeholder Map, RACI, AI Team Design và Growth Plan.
* Tổng hợp nội dung cuối cùng thành PDF.
* Kiểm tra README trước khi nộp.
* Push phiên bản cuối lên GitHub.

---

## 5. Phân công tổng quát trong Lab

| Thành viên              | Trách nhiệm chính                                                               |
| ------------------------- | ---------------------------------------------------------------------------------- |
| **Vũ Huy Hoàng**  | Tổng hợp bài, technical/AI perspective, quản lý repository và artefact cuối |
| **Tạ Thị Nga**   | User/stakeholder perspective, feedback và hỗ trợ đánh giá Team Health        |
| **Trần Hoài Nam** | Business/pilot stakeholder perspective, RACI và Growth Plan                       |

> Đây là phân công phục vụ quá trình thực hiện Lab. RACI chi tiết cho các công việc của Internova sẽ được xác định tại Phase 2.

---

## 6. Format làm bài

Team thống nhất sử dụng:

**Google Slides / Slides**

để thiết kế 4 artefact chính của Lab và xuất thành:

**01 file PDF tối đa 4 trang.**

GitHub được sử dụng để lưu và nộp kết quả cuối cùng.

### Cấu trúc repository

```text
Track1_Day27_TeamVuonLenChinhMinh_/
├── README.md
└── AI-Team-Lab.pdf
```

Trong đó:

* `README.md`: chứa thông tin team, project scope và thông tin bài nộp.
* `AI-Team-Lab.pdf`: tối đa 4 trang, chứa đủ 4 artefact chính.

---

## 7. Scope của Day 27

Day 27 áp dụng trực tiếp cho **Internova AI Platform**, không sử dụng case giả định.

Team sẽ đi qua chuỗi quyết định:

```text
Stakeholder Map
        ↓
Pitch & RACI
        ↓
AI Team Design
        ↓
Team Health & Growth Plan
```

Mục tiêu cuối cùng là trả lời được bốn câu hỏi:

1. **Ai có ảnh hưởng đến Internova?**
2. **Team cần thuyết phục stakeholder thế nào và ai chịu trách nhiệm cho từng công việc?**
3. **Internova cần cấu trúc AI Team và năng lực nào ở giai đoạn hiện tại?**
4. **Trong 30 ngày tới team cần cải thiện điều gì?**

---

# GATE 0 — Scope đã rõ

* [X] Team có đúng **3 thành viên**.
* [X] Đã ghi đầy đủ họ tên và mã học viên.
* [X] Cả team sử dụng cùng một dự án: **Internova AI Platform**.
* [X] Đã xác định mục tiêu hiện tại trong 1–3 tháng.
* [X] Đã xác định người tổng hợp bài.
* [X] Đã thống nhất format làm bài.
* [X] Đã có GitHub repository chung.
* [X] Cả team thống nhất phạm vi và hướng phát triển hiện tại.

**GATE 0: PASS ✅**

# Page 1 — Stakeholder Map & Strategy

## 1. Stakeholder Identification

Sau khi mỗi thành viên liệt kê stakeholder riêng, team thống nhất các stakeholder chính của **Internova AI Platform** như sau:

| Stakeholder cụ thể                                                 | Vai trò / mối liên hệ với Internova                                                      |
| -------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| **VinUni Internship Program / đơn vị quản lý thực tập** | Quản lý quy trình, chính sách và có khả năng quyết định việc pilot hệ thống    |
| **Giảng viên phụ trách / mentor review dự án Internova** | Đánh giá tính phù hợp, góp ý nghiệp vụ và có ảnh hưởng đến việc triển khai |
| **Sinh viên VinUni chuẩn bị hoặc đang thực tập**        | Người dùng trực tiếp của chatbot, CV Matching và internship workflow                   |
| **Giảng viên hướng dẫn sinh viên thực tập**            | Người dùng Lecturer Portal để theo dõi tiến độ, báo cáo và sinh viên có rủi ro |
| **University Admin / người quản trị Internship System**    | Quản lý tài khoản, tài liệu, Knowledge Base và quyền truy cập                        |
| **Doanh nghiệp tiếp nhận sinh viên thực tập**            | Cung cấp internship opportunity và tham gia vào quá trình thực tập                     |
| **Supervisor tại doanh nghiệp**                              | Hướng dẫn và đánh giá sinh viên trong quá trình thực tập                          |
| **Development Team Internova**                                 | Xây dựng, kiểm thử, vận hành và cải thiện sản phẩm                                 |

---

## 2. Influence × Interest Stakeholder Map

### High Influence × High Interest — Champion

**1. Giảng viên / mentor đang review Internova**

* Influence: **Cao**
* Interest: **Cao**
* Stance: **Ủng hộ**
* Lý do: Có khả năng góp ý trực tiếp vào chất lượng dự án, định hướng requirement và hỗ trợ team tiếp cận đúng quy trình thực tập.

**2. Development Team Internova**

* Influence: **Cao**
* Interest: **Cao**
* Stance: **Ủng hộ mạnh**
* Lý do: Trực tiếp quyết định kiến trúc, chất lượng kỹ thuật và tốc độ phát triển sản phẩm.

---

### High Influence × Low/Medium Interest — Blocker / Need to Convince

**3. VinUni Internship Program / đơn vị có quyền duyệt pilot**

* Influence: **Rất cao**
* Interest: **Trung bình**
* Stance: **Trung lập / chưa được thuyết phục đầy đủ**
* Lý do: Có thể cho phép hoặc không cho phép đưa Internova vào thử nghiệm thực tế. Họ cần bằng chứng về độ chính xác, privacy và giá trị vận hành trước khi chấp nhận.

**4. University Admin / người quản trị hệ thống**

* Influence: **Cao**
* Interest: **Trung bình**
* Stance: **Trung lập**
* Lý do: Quan tâm đến security, quản lý dữ liệu, quyền truy cập và workload vận hành. Nếu hệ thống làm tăng công việc quản trị thì có thể trở thành lực cản.

---

### Low/Medium Influence × High Interest — Supporter

**5. Sinh viên VinUni đang chuẩn bị hoặc tham gia thực tập**

* Influence: **Trung bình**
* Interest: **Rất cao**
* Stance: **Ủng hộ**
* Lý do: Là nhóm nhận value trực tiếp và có thể cung cấp feedback thực tế về chatbot, workflow và CV Matching.

**6. Giảng viên hướng dẫn sinh viên thực tập**

* Influence: **Trung bình**
* Interest: **Cao**
* Stance: **Ủng hộ / Trung lập**
* Lý do: Có nhu cầu theo dõi tiến độ sinh viên nhưng chỉ tiếp tục sử dụng nếu hệ thống thực sự giảm workload.

**7. Supervisor tại doanh nghiệp**

* Influence: **Trung bình**
* Interest: **Cao**
* Stance: **Trung lập**
* Lý do: Có lợi ích nếu hệ thống giúp việc theo dõi và đánh giá sinh viên đơn giản hơn.

---

### Low Influence × Low/Medium Interest — Bystander

**8. Doanh nghiệp chưa tham gia pilot Internova**

* Influence: **Thấp ở giai đoạn hiện tại**
* Interest: **Thấp / Trung bình**
* Stance: **Trung lập**
* Lý do: Chưa trực tiếp tham gia sản phẩm nhưng có thể trở thành stakeholder quan trọng khi Internova mở rộng.

---

## 3. Stakeholder Map Summary

|                                         | **Interest thấp / trung bình**                             | **Interest cao**                                                                            |
| --------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------- |
| **Influence cao**                 | **BLOCKER** ① VinUni Internship Program ② University Admin | **CHAMPION** ① Giảng viên/Mentor review ② Development Team Internova                    |
| **Influence thấp / trung bình** | **BYSTANDER** ① Doanh nghiệp chưa pilot                   | **SUPPORTER** ① Sinh viên VinUni ② Giảng viên hướng dẫn ③ Supervisor doanh nghiệp |

> Quadrant được xác định dựa trên **Influence × Interest**. Stance được đánh giá riêng theo trạng thái thực tế và không mặc định theo tên quadrant.

---

# 4. Four Priority Stakeholders & Strategies

## Priority 1 — Giảng viên / Mentor review dự án

**Stance:** Ủng hộ mạnh
**Quadrant:** Champion

### Họ quan tâm điều gì?

* Internova có giải quyết đúng vấn đề thực tập hay không.
* AI có trả lời chính xác và dựa trên tài liệu chính thức hay không.
* Sản phẩm có đủ chất lượng để thử nghiệm thực tế hay không.

### Họ có thể giúp thế nào?

* Review sản phẩm và requirement.
* Chỉ ra các vấn đề nghiệp vụ mà team chưa hiểu đúng.
* Giới thiệu team tới stakeholder có quyền quyết định pilot.

### Action trong 1–2 tuần tới

> **Trước ngày 05/09/2026, team gửi một bản demo Internova hoàn chỉnh cho mentor, bao gồm Student Portal, Lecturer Portal và AI Chatbot; sau demo xin ít nhất 3 feedback ưu tiên và đề nghị mentor kết nối team với một người phụ trách internship để thảo luận pilot.**

**Owner:** Vũ Huy Hoàng

---

## Priority 2 — Sinh viên VinUni đang chuẩn bị / tham gia thực tập

**Stance:** Ủng hộ
**Quadrant:** Supporter

### Họ quan tâm điều gì?

* Có tìm được đúng thông tin nhanh hay không.
* AI có trả lời đúng quy định hay không.
* Hệ thống có giúp giảm thời gian tìm tài liệu và hoàn thành thủ tục hay không.

### Họ có thể giúp thế nào?

* Cung cấp feedback thực tế.
* Phát hiện lỗi UX và câu trả lời AI.
* Xác nhận Internova có tạo ra value thật hay không.

### Action trong 1–2 tuần tới

> **Trước ngày 10/09/2026, team mời ít nhất 5 sinh viên thử 3 flow chính: hỏi quy định thực tập, tìm bước tiếp theo và CV–JD Matching; ghi lại completion rate, lỗi gặp phải và ít nhất 1 feedback định tính từ mỗi người.**

**Owner:** Vũ Huy Hoàng

---

## Priority 3 — VinUni Internship Program / người có quyền duyệt pilot

**Stance:** Trung lập / chưa được thuyết phục đầy đủ
**Quadrant:** Blocker

### Họ quan tâm điều gì?

* Độ chính xác của thông tin.
* Privacy và security.
* AI có đưa ra thông tin sai chính sách hay không.
* Internova có thực sự giảm workload vận hành hay chỉ tạo thêm hệ thống mới.
* Có đủ bằng chứng để pilot với sinh viên thật hay không.

### Họ có thể giúp hoặc cản trở thế nào?

**Giúp:** phê duyệt pilot và cho phép tiếp cận workflow thực tế.

**Cản trở:** không chấp thuận pilot nếu chưa có bằng chứng về accuracy, privacy và operational value.

### Action trong 1–2 tuần tới

> **Trước ngày 12/09/2026, team chuẩn bị một pilot brief 1 trang gồm problem, demo flow, AI guardrails, privacy approach, 3 quality metrics và phạm vi pilot nhỏ; sau đó xin một buổi review để xác định rõ điều kiện cần đạt trước khi cho sinh viên sử dụng thực tế.**

**Owner:** Trần Hoài Nam

---

## Priority 4 — University Admin / người quản trị hệ thống

**Stance:** Trung lập
**Quadrant:** Blocker

### Họ quan tâm điều gì?

* Tài liệu có dễ quản lý không.
* Version mới có được cập nhật đúng vào RAG không.
* Quyền truy cập có an toàn không.
* Hệ thống có dễ vận hành và kiểm tra lỗi không.

### Họ có thể giúp hoặc cản trở thế nào?

**Giúp:** xác nhận workflow quản trị phù hợp với thực tế và hỗ trợ adoption.

**Cản trở:** phản đối việc sử dụng nếu Knowledge Base khó quản lý, security không rõ hoặc hệ thống tạo thêm workload.

### Action trong 1–2 tuần tới

> **Trước ngày 12/09/2026, team demo Admin Portal với 3 tác vụ: thêm tài liệu mới, cập nhật version và kiểm tra trạng thái Knowledge Base; thu thập feedback về workload, quyền truy cập và các thông tin admin cần theo dõi trước pilot.**

**Owner:** Tạ Thị Nga

---

# 5. Stakeholder Strategy Summary

| Priority stakeholder         | Stance                      | Mục tiêu của team                  | Hành động tiếp theo                            |
| ---------------------------- | --------------------------- | ------------------------------------- | -------------------------------------------------- |
| Giảng viên / Mentor review | Ủng hộ mạnh              | Tận dụng influence và expertise    | Demo + lấy 3 feedback + xin kết nối stakeholder |
| Sinh viên VinUni            | Ủng hộ                    | Thu thập bằng chứng về user value | Test với ≥5 sinh viên                           |
| VinUni Internship Program    | Chưa được thuyết phục | Giảm rủi ro và tạo niềm tin      | Pilot brief + xin review điều kiện pilot        |
| University Admin             | Trung lập                  | Chứng minh khả năng vận hành     | Demo Knowledge Base/Admin workflow + lấy feedback |

---

## GATE 1 — Stakeholder Map có thể hành động

* [X] Có ít nhất 6 stakeholder cụ thể.
* [X] Stakeholder được map theo Influence × Interest.
* [X] Từng stakeholder có stance rõ ràng.
* [X] Đã chọn 2 stakeholder đang ủng hộ để tận dụng sức ảnh hưởng.
* [X] Đã chọn 2 stakeholder có khả năng cản trở/chưa được thuyết phục.
* [X] Mỗi stakeholder ưu tiên có một hành động cụ thể.
* [X] Action có owner và mốc thời gian rõ ràng.

**GATE 1: PASS ✅**

# Phase 2 — Pitch "Kết luận trước" & RACI Matrix

**Project:** Internova AI Platform
**Team:** Vươn Lên Chính Mình

## 1. Stakeholder được chọn để Pitch

Team chọn stakeholder quan trọng:

> **VinUni Internship Program / đơn vị có quyền review và phê duyệt pilot Internova**

### Lý do lựa chọn

Stakeholder này có:

* **Influence:** Rất cao
* **Interest:** Trung bình
* **Stance hiện tại:** Trung lập / chưa được thuyết phục đầy đủ
* **Quadrant:** Blocker / Need to Convince

Đây là stakeholder quan trọng vì dù team có hoàn thiện sản phẩm về mặt kỹ thuật, Internova vẫn khó được thử nghiệm với người dùng thực tế nếu chưa chứng minh được độ chính xác, privacy và giá trị vận hành.

---

# 2. Team Pitch — Conclusion First

## Kết luận / Đề xuất

> **Team đề xuất VinUni cho phép Internova thực hiện một pilot nhỏ có kiểm soát với một nhóm sinh viên trước khi xem xét triển khai ở phạm vi rộng hơn.**

## Lý do 1 — Internova giải quyết vấn đề thực tế

Thông tin và quy trình thực tập có thể nằm ở nhiều tài liệu, biểu mẫu và nguồn khác nhau.

Internova hướng tới tạo một điểm truy cập duy nhất giúp sinh viên:

* Tra cứu quy định.
* Xác định bước tiếp theo.
* Tìm tài liệu cần thiết.
* Sử dụng CV–JD Matching.
* Theo dõi quá trình thực tập.

Điều này đồng thời có thể giúp giảm các câu hỏi lặp lại cho giảng viên và đơn vị quản lý.

## Lý do 2 — Internova không chỉ là một chatbot AI

Hệ thống đang được phát triển gồm:

* Student Portal.
* Lecturer Portal.
* Admin Portal.
* RAG-based AI Chatbot.
* Knowledge Base.
* Document/version management.
* CV–JD Matching.
* AI Guardrails.
* AI Monitoring.

AI được đặt trong workflow nghiệp vụ thay vì hoạt động như một chatbot hỏi gì cũng trả lời.

## Lý do 3 — Pilot nhỏ giúp kiểm chứng trước khi mở rộng

Team chưa đề xuất triển khai toàn trường ngay.

Một pilot nhỏ giúp kiểm tra:

* AI có trả lời đúng hay không.
* Sinh viên có thực sự nhận được giá trị hay không.
* Workflow có phù hợp hay không.
* Admin có quản lý Knowledge Base thuận tiện hay không.
* Có vấn đề privacy hoặc operational risk nào cần xử lý trước khi scale.

---

# 3. Evidence — Bằng chứng hiện có

Team hiện đã có prototype với các thành phần chính:

### Product

* Student Portal.
* Lecturer Portal.
* Admin Portal.
* Internship workflows.

### AI

* RAG pipeline.
* Semantic routing.
* Guardrails.
* Retrieval từ Knowledge Base.
* AI response validation.
* CV–JD Matching.

### Knowledge Management

* Quản lý tài liệu.
* Quản lý version.
* Workflow đưa tài liệu mới vào Knowledge Base.

### Monitoring

* Theo dõi hoạt động AI/backend.
* Theo dõi latency.
* Theo dõi lỗi.
* Quan sát các bước chính trong AI pipeline.

> Các thành phần trên chứng minh team đã có prototype để kiểm thử. Team chưa coi đây là bằng chứng rằng Internova đã sẵn sàng triển khai production ở quy mô lớn.

---

# 4. Small Ask

Team không yêu cầu stakeholder phê duyệt triển khai toàn bộ Internova ngay.

### Đề nghị cụ thể

> **Team đề nghị một buổi review prototype khoảng 30 phút và xin phép xây dựng kế hoạch pilot giới hạn với ít nhất 5 sinh viên để kiểm thử các flow chính trước khi đưa ra quyết định tiếp theo.**

Trong buổi review, team muốn xác nhận:

1. Những điều kiện nào Internova phải đáp ứng trước pilot?
2. Những loại dữ liệu nào được phép sử dụng?
3. Những privacy/security requirement nào bắt buộc?
4. Những metric nào cần theo dõi trong pilot?
5. Stakeholder nào cần tham gia trước khi pilot bắt đầu?

---

# 5. Phản biện có khả năng xảy ra nhất

## Objection

> **“AI chưa đủ đáng tin để sinh viên sử dụng cho các thông tin và quy định quan trọng liên quan đến thực tập.”**

## Cách team xử lý

Team coi đây là một rủi ro thực tế và không thiết kế Internova theo hướng để model tự tạo câu trả lời không có kiểm soát.

Các biện pháp giảm rủi ro gồm:

* Sử dụng **RAG** để ưu tiên thông tin từ Knowledge Base.
* Quản lý tài liệu và version.
* Sử dụng guardrails để giới hạn phạm vi câu hỏi.
* Không coi AI là nguồn phê duyệt chính thức cho các quyết định quan trọng.
* Theo dõi lỗi và chất lượng AI.
* Kiểm thử các câu hỏi quan trọng trước pilot.
* Bắt đầu bằng pilot nhỏ thay vì triển khai rộng.

### Hành động giảm rủi ro

> **Trước pilot, team sẽ xây dựng test set gồm các câu hỏi internship quan trọng và kiểm tra câu trả lời của Internova với nguồn tài liệu chính thức. Những flow chưa đạt yêu cầu sẽ không được đưa vào phạm vi pilot.**

---

# 6. Individual Pitch Check

## Vũ Huy Hoàng — 2A202601057

> **Đề xuất:** Cho phép Internova thực hiện một pilot nhỏ thay vì triển khai rộng ngay.
>
> **Lý do:** Internova đã có các thành phần kỹ thuật chính như RAG, Knowledge Base, guardrails và monitoring, nhưng team vẫn cần dữ liệu thực tế để xác nhận accuracy và reliability.
>
> **Evidence:** Prototype hiện đã có AI Chatbot, Student Portal, Lecturer Portal, Admin Portal và hệ thống Knowledge Base.
>
> **Small ask:** Cho team một buổi technical/product review và thống nhất điều kiện để thử nghiệm với ít nhất 5 sinh viên.

---

## Tạ Thị Nga — 2A202601125

> **Đề xuất:** Cho Internova được kiểm thử với một nhóm sinh viên nhỏ trước khi quyết định mở rộng.
>
> **Lý do:** Điều quan trọng hiện tại là xác định sinh viên có thực sự nhận được value và workflow có dễ sử dụng hay không.
>
> **Evidence:** Team đã có prototype cho các flow chính và có thể đưa cho người dùng thử trực tiếp.
>
> **Small ask:** Cho phép team tổ chức user test với ít nhất 5 sinh viên và thu thập feedback có cấu trúc.

---

## Trần Hoài Nam — 2A202601751

> **Đề xuất:** Xem Internova như một pilot có kiểm soát thay vì một đề xuất triển khai toàn bộ ngay lập tức.
>
> **Lý do:** Pilot nhỏ giúp VinUni đánh giá product value, AI risk và operational impact với phạm vi rủi ro thấp hơn.
>
> **Evidence:** Team đã có prototype đủ để demo và kiểm tra những workflow chính.
>
> **Small ask:** Thống nhất một buổi review để xác định scope, tiêu chí thành công và điều kiện phê duyệt pilot.

---

# 7. Final Pitch được team thống nhất

> **Team đề xuất VinUni cho phép Internova tiến tới một pilot nhỏ có kiểm soát thay vì triển khai rộng ngay.**
>
> Internova đang giải quyết vấn đề thông tin và workflow thực tập bị phân tán bằng một nền tảng kết hợp Student Portal, Lecturer Portal, Admin Portal và AI/RAG. Prototype hiện đã có các thành phần chính như Knowledge Base, document management, guardrails và monitoring, nhưng team chưa coi đó là bằng chứng rằng sản phẩm đã sẵn sàng triển khai quy mô lớn.
>
> Vì vậy, bước hợp lý tiếp theo là kiểm chứng sản phẩm với phạm vi nhỏ để đo accuracy, user value, usability và operational risk.
>
> **Small ask:** Team đề nghị một buổi review 30 phút để thống nhất điều kiện pilot và xin phép thử nghiệm các flow chính với ít nhất 5 sinh viên.

---

# 8. RACI Matrix — 1–2 tháng tới

### Ký hiệu

* **R — Responsible:** Người trực tiếp thực hiện
* **A — Accountable:** Người chịu trách nhiệm cuối cùng
* **C — Consulted:** Người cần được hỏi ý kiến
* **I — Informed:** Người cần được thông báo

| Công việc quan trọng                                           | Vũ Huy Hoàng | Tạ Thị Nga  | Trần Hoài Nam | Stakeholder liên quan         |
| ----------------------------------------------------------------- | -------------- | ------------- | --------------- | ------------------------------ |
| **1. Chốt use case và phạm vi pilot**                    | C              | R             | **A**     | VinUni Internship Program — C |
| **2. Hoàn thiện RAG, Knowledge Base và AI Guardrails**   | **R/A**  | C             | I               | Mentor — C                    |
| **3. Hoàn thiện Student / Lecturer / Admin workflows**    | R              | **A**   | C               | Người dùng thử — C        |
| **4. AI Evaluation, regression test và kiểm tra quality** | **A**    | R             | I               | Mentor — C                    |
| **5. User testing và tổng hợp feedback**                 | C              | **R/A** | R               | Sinh viên thử nghiệm — I   |
| **6. Chuẩn bị Pilot Brief, demo và đề xuất pilot**    | R              | C             | **A**     | VinUni Internship Program — C |

---

# 9. Giải thích RACI

## 1. Chốt use case và phạm vi pilot

**Accountable: Trần Hoài Nam**

Nam chịu trách nhiệm cuối trong việc đảm bảo phạm vi pilot rõ ràng và phù hợp với stakeholder.

**Tạ Thị Nga** trực tiếp hỗ trợ tổng hợp nhu cầu và góc nhìn của người dùng.

---

## 2. RAG, Knowledge Base & AI Guardrails

**Accountable: Vũ Huy Hoàng**

Hoàng chịu trách nhiệm chính về chất lượng technical/AI của hệ thống.

Các thay đổi liên quan đến retrieval, Knowledge Base và guardrails cần được kiểm tra trước khi đưa vào pilot.

---

## 3. Student / Lecturer / Admin Workflows

**Accountable: Tạ Thị Nga**

Nga chịu trách nhiệm cuối trong việc đảm bảo các workflow phù hợp với góc nhìn của người dùng và stakeholder.

Hoàng hỗ trợ trực tiếp implementation.

---

## 4. AI Evaluation & Regression Testing

**Accountable: Vũ Huy Hoàng**

Hoàng chịu trách nhiệm cuối về việc đánh giá thay đổi AI trước pilot.

**Tạ Thị Nga** trực tiếp tham gia chạy test case, kiểm tra flow và tổng hợp kết quả.

---

## 5. User Testing & Feedback

**Accountable: Tạ Thị Nga**

Nga chịu trách nhiệm tổ chức và tổng hợp feedback từ sinh viên thử nghiệm.

Team cần kiểm tra:

* Task completion.
* Lỗi gặp phải.
* Câu trả lời AI chưa chính xác.
* Usability.
* Perceived value.

---

## 6. Pilot Brief & Demo

**Accountable: Trần Hoài Nam**

Nam chịu trách nhiệm cuối cho Pilot Brief và stakeholder communication.

Hoàng phụ trách phần demo technical/product.

---

# 10. RACI Validation

| Công việc                       | Accountable duy nhất     |
| --------------------------------- | ------------------------- |
| Chốt use case & pilot scope      | **Trần Hoài Nam** |
| RAG / Knowledge Base / Guardrails | **Vũ Huy Hoàng**  |
| Product workflows                 | **Tạ Thị Nga**    |
| AI Evaluation / Regression        | **Vũ Huy Hoàng**  |
| User Testing                      | **Tạ Thị Nga**    |
| Pilot Brief / Demo                | **Trần Hoài Nam** |

Mỗi công việc có đúng **1 Accountable** rõ ràng.

---

# GATE 2 — Pitch rõ, RACI không mơ hồ

* [X] Đã chọn 1 stakeholder quan trọng từ Phase 1.
* [X] Pitch sử dụng **Conclusion First**.
* [X] Có 2–3 lý do chính.
* [X] Có evidence dựa trên prototype hiện tại.
* [X] Không hứa vượt quá bằng chứng hiện có.
* [X] Có **Small Ask** cụ thể.
* [X] Có 1 phản biện có khả năng xảy ra.
* [X] Có cách xử lý phản biện dựa trên bằng chứng và hành động giảm rủi ro.
* [X] Cả 3 thành viên đã viết lại pitch theo cách riêng.
* [X] RACI có 6 công việc quan trọng trong 1–2 tháng tới.
* [X] Mỗi công việc có đúng **1 Accountable**.
* [X] RACI sử dụng đúng 3 thành viên hiện tại của team:

## Kết quả

**GATE 2: PASS ✅**

# Phase 3 — AI Team Design

**Project:** Internova AI Platform
**Team:** Vươn Lên Chính Mình

## 1. AI Team Architecture

### Architecture được chọn: Embedded

> **Internova sử dụng mô hình Embedded AI Team — năng lực AI được đặt trực tiếp trong team sản phẩm thay vì tách thành một nhóm AI độc lập.**

### Vì sao lựa chọn Embedded?

Team hiện chỉ có **3 thành viên** và đang ở giai đoạn hoàn thiện sản phẩm, kiểm thử và chuẩn bị pilot. Vì vậy, việc tách AI thành một team riêng hoặc xây Hybrid Architecture sẽ tạo thêm coordination overhead không cần thiết.

Embedded phù hợp hơn vì:

* AI là thành phần cốt lõi của chính Internova.
* Quyết định AI cần gắn trực tiếp với Product, Backend và user workflow.
* Team nhỏ cần trao đổi và triển khai nhanh.
* Các thay đổi về RAG, Knowledge Base hoặc guardrails có thể ảnh hưởng trực tiếp tới trải nghiệm người dùng.
* Team cần tối ưu tốc độ học hỏi trước pilot hơn là mở rộng cơ cấu tổ chức.

### Cấu trúc hiện tại

```text
                 INTERNOVA SQUAD
                       │
          ┌────────────┼────────────┐
          │            │            │
          ▼            ▼            ▼
   AI / Technical   User/Product   Pilot/Business
     Capability      Capability      Capability
          │            │            │
   Vũ Huy Hoàng     Tạ Thị Nga   Trần Hoài Nam
```

Ba capability làm việc trong cùng một product squad và cùng chịu trách nhiệm đưa Internova tới pilot.

---

# 2. Core Roles — Vai trò cần ngay

Team không cố tạo nhiều chức danh mà chỉ xác định các capability thực sự cần để đưa Internova tới milestone tiếp theo.

## Core Role 1 — AI / Technical Product Lead

**Owner hiện tại:** Vũ Huy Hoàng

### Capability cần có

* AI/RAG architecture.
* Backend integration.
* Knowledge Base.
* Retrieval.
* Guardrails.
* AI Evaluation.
* System monitoring.
* Technical decision making.

### Trách nhiệm

* Đảm bảo AI pipeline hoạt động đúng.
* Cải thiện accuracy và latency.
* Quản lý tích hợp RAG với Knowledge Base.
* Kiểm soát các thay đổi kỹ thuật trước pilot.
* Đảm bảo các component AI kết nối đúng với product workflow.

---

## Core Role 2 — Product / UX & User Validation

**Owner hiện tại:** Tạ Thị Nga

### Capability cần có

* User research.
* UX validation.
* Workflow testing.
* Requirement clarification.
* User feedback.
* Acceptance criteria.

### Trách nhiệm

* Đảm bảo tính năng giải quyết đúng nhu cầu người dùng.
* Kiểm tra Student / Lecturer / Admin workflow.
* Tổ chức user testing.
* Thu thập và tổng hợp feedback.
* Chuyển feedback thành requirement có thể hành động.

---

## Core Role 3 — Pilot / Stakeholder & Business Coordination

**Owner hiện tại:** Trần Hoài Nam

### Capability cần có

* Stakeholder communication.
* Pilot planning.
* Scope management.
* Business requirement.
* Risk communication.
* Product pitching.

### Trách nhiệm

* Xác định phạm vi pilot.
* Chuẩn bị Pilot Brief.
* Làm việc với stakeholder.
* Xác định điều kiện thành công của pilot.
* Đảm bảo team không xây vượt quá nhu cầu hiện tại.

---

# 3. Core Capabilities của Internova Squad

| Capability                   | Mức độ cần | Người phụ trách chính    |
| ---------------------------- | -------------- | ----------------------------- |
| AI/RAG Engineering           | Core           | Vũ Huy Hoàng                |
| Backend & System Integration | Core           | Vũ Huy Hoàng                |
| Product / Requirement        | Core           | Tạ Thị Nga                  |
| UX & User Validation         | Core           | Tạ Thị Nga                  |
| Pilot Planning               | Core           | Trần Hoài Nam               |
| Stakeholder Management       | Core           | Trần Hoài Nam               |
| AI Evaluation                | Core           | Vũ Huy Hoàng + Tạ Thị Nga |
| Knowledge Management         | Core           | Vũ Huy Hoàng                |

---

# 4. Extended Roles — Cần khi scale

Các capability dưới đây chưa cần trở thành full-time role ở giai đoạn hiện tại nhưng sẽ quan trọng nếu Internova mở rộng.

| Extended Capability                        | Khi nào cần                                             |
| ------------------------------------------ | --------------------------------------------------------- |
| **MLOps / AI Evaluation Specialist** | Khi số lượng user, model call và AI evaluation tăng  |
| **DevOps / SRE**                     | Khi hệ thống chạy production và cần reliability cao  |
| **Security / Privacy Specialist**    | Trước khi xử lý dữ liệu cá nhân ở phạm vi lớn  |
| **Legal / Compliance**               | Khi triển khai chính thức với tổ chức/trường học |
| **Internship Domain Expert**         | Trước và trong pilot để xác nhận policy/workflow   |
| **Data Engineer**                    | Khi volume tài liệu và dữ liệu tăng mạnh           |
| **QA / Automation Engineer**         | Khi regression test trở thành bottleneck                |
| **Forward Deployed Engineer**        | Khi Internova triển khai cho nhiều đơn vị khác nhau |

> Team không cần tuyển tất cả các role trên ngay. Capability chỉ được bổ sung khi nó trở thành bottleneck thực sự của milestone tiếp theo.

---

# 5. Capability Gap Analysis

Sau khi so sánh năng lực hiện tại với yêu cầu để pilot Internova, team xác định ba capability gap quan trọng nhất.

## Gap 1 — Internship Domain Expertise

### Vấn đề

Team có khả năng xây sản phẩm và AI nhưng không thể tự xác nhận mọi policy, quy định và nghiệp vụ thực tập.

Nếu hiểu sai domain, Internova có thể:

* đưa ra workflow không đúng;
* sử dụng sai policy;
* trả lời sai câu hỏi quan trọng;
* xây feature không phù hợp với quy trình thực tế.

### Priority

**Rất cao**

---

## Gap 2 — Production AI Evaluation / MLOps

### Vấn đề

Team đã có AI/RAG nhưng cần quy trình đánh giá có hệ thống hơn để biết một thay đổi:

* làm accuracy tốt hơn hay xấu đi;
* có gây regression không;
* có làm latency tăng không;
* có ảnh hưởng tới groundedness không.

### Priority

**Cao**

---

## Gap 3 — Security & Privacy Review

### Vấn đề

Internova có khả năng xử lý:

* tài khoản người dùng;
* dữ liệu sinh viên;
* CV;
* thông tin thực tập;
* lịch sử tương tác.

Trước khi mở rộng pilot hoặc production, team cần một góc nhìn security/privacy độc lập để giảm rủi ro.

### Priority

**Cao**

---

# 6. Priority Resourcing

## Priority Gap 1 — Internship Domain Expertise

### Capability Gap

**Hiểu sâu chính sách và workflow thực tập thực tế**

### Cách bổ sung

**PARTNER**

Team sẽ hợp tác với:

* giảng viên phụ trách internship;
* mentor;
* VinUni Internship Program;
* người quản lý quy trình thực tập.

### Vì sao chọn Partner?

Không hợp lý để tuyển một domain expert full-time chỉ để kiểm tra policy ở giai đoạn pilot.

Các stakeholder hiện tại đã có đúng kiến thức mà team cần và đồng thời là những người có khả năng ảnh hưởng đến việc Internova được sử dụng.

### Khi nào cần?

> **Cần ngay và bắt buộc trước pilot đầu tiên.**

### Kết quả mong muốn

* Xác nhận các workflow chính.
* Xác nhận Knowledge Base.
* Review các câu hỏi internship quan trọng.
* Xác định các trường hợp AI không được tự quyết định.

---

## Priority Gap 2 — Production AI Evaluation / MLOps

### Capability Gap

**AI Evaluation, regression automation và production AI monitoring**

### Cách bổ sung

**HIRE — khi bước sang giai đoạn scale**

Trong giai đoạn prototype/pilot, team tiếp tục tự xây evaluation cơ bản.

Khi Internova có usage thực tế và số lượng experiment tăng, team cần bổ sung một người có năng lực mạnh về:

* AI Evaluation.
* MLOps.
* CI/CD cho AI.
* Monitoring.
* Model/retrieval regression.

### Vì sao chọn Hire?

Đây sẽ trở thành capability dài hạn của Internova nếu AI là core product. Thuê ngoài liên tục sẽ khiến knowledge quan trọng nằm ngoài team.

### Khi nào cần?

> **Sau khi pilot chứng minh được nhu cầu và trước khi mở rộng production.**

### Kết quả mong muốn

* Automated evaluation pipeline.
* Regression test cho RAG.
* Versioned evaluation dataset.
* Quality monitoring theo từng release.

---

## Priority Gap 3 — Security & Privacy

### Capability Gap

**Security architecture và privacy review độc lập**

### Cách bổ sung

**OUTSOURCE**

Team thuê hoặc nhờ một specialist bên ngoài thực hiện security/privacy review trước khi triển khai rộng.

### Vì sao chọn Outsource?

Team chưa cần một security engineer full-time ở giai đoạn hiện tại.

Một review độc lập có scope rõ ràng có thể giúp phát hiện:

* authentication issue;
* authorization issue;
* data exposure;
* privacy risk;
* insecure API;
* logging chứa dữ liệu nhạy cảm.

### Khi nào cần?

> **Trước khi pilot mở rộng hoặc trước khi sử dụng dữ liệu cá nhân thực ở quy mô lớn.**

### Kết quả mong muốn

* Security checklist.
* Privacy risk review.
* Danh sách vulnerability cần xử lý.
* Các release blocker liên quan đến security.

---

# 7. Priority Resourcing Summary

| Capability Gap                        | Resourcing          | Vì sao                                                                                      | Khi nào                                  |
| ------------------------------------- | ------------------- | -------------------------------------------------------------------------------------------- | ----------------------------------------- |
| **Internship Domain Expertise** | **Partner**   | Kiến thức đã tồn tại ở giảng viên/đơn vị quản lý, không cần tuyển full-time | Trước pilot đầu tiên                 |
| **AI Evaluation / MLOps**       | **Hire**      | Là capability dài hạn nếu AI tiếp tục là core product                                 | Sau pilot, trước production scale       |
| **Security & Privacy**          | **Outsource** | Cần specialist độc lập nhưng chưa cần full-time                                       | Trước khi scale dữ liệu/người dùng |

---

# 8. Target Team Evolution

## Hiện tại — 3-person Embedded Squad

```text
Vũ Huy Hoàng
AI / Technical
      │
      ├────────────┐
      │            │
Tạ Thị Nga   Trần Hoài Nam
Product/UX   Pilot/Stakeholder
```

### External Support

```text
Internova Squad
      │
      ├── Partner → Internship Domain Expert
      │
      └── Outsource → Security / Privacy Review
```

---

## Khi scale

```text
               Internova Product Squad
                        │
       ┌────────────────┼────────────────┐
       │                │                │
 Product/UX        AI Engineering     Fullstack
       │                │                │
       ├──────── AI Evaluation/MLOps ────┤
       │
 Stakeholder / Business
```

Ngoài team:

```text
Domain Expert
Security / Compliance
Institutional Partners
```

---

# 9. Squad Goal

> **“Team Internova sở hữu toàn bộ trải nghiệm AI hỗ trợ quá trình thực tập và chịu trách nhiệm đưa Internova từ một sản phẩm đang hoàn thiện prototype đến một pilot có kiểm soát, đo được giá trị người dùng, chất lượng AI và rủi ro vận hành.”**

---

# 10. Design Principle

Team thống nhất ba nguyên tắc:

### 1. Capability before Title

Không tuyển hoặc tạo role chỉ vì một AI company khác có role đó.

Team chỉ bổ sung người khi có **capability gap thực sự**.

### 2. Embedded while small

Khi team còn nhỏ, AI phải nằm trực tiếp trong product squad để giữ tốc độ iteration.

### 3. Scale after Evidence

Team chỉ mở rộng organization sau khi pilot cung cấp bằng chứng rằng Internova có:

* user value;
* technical feasibility;
* stakeholder support;
* cơ hội mở rộng.

---

# GATE 3 — Team Design phù hợp thực tế

* [X] Đã chọn **Embedded AI Team Architecture**.
* [X] Có giải thích vì sao architecture phù hợp với team 3 người.
* [X] Đã xác định Core Roles cần ngay.
* [X] Không tạo role không cần thiết.
* [X] Đã xác định Extended Roles cho giai đoạn scale.
* [X] Đã xác định 3 capability gap ưu tiên.
* [X] Mỗi capability gap có phương án resourcing cụ thể.
* [X] Có sử dụng **Partner / Hire / Outsource**.
* [X] Mỗi quyết định resourcing có lý do.
* [X] Mỗi capability gap có thời điểm cần rõ ràng.
* [X] Đã có Squad Goal gắn trực tiếp với milestone hiện tại của Internova.

## Kết quả

**GATE 3: PASS ✅**

# Phase 4 — Team Health & Growth Plan

**Project:** Internova AI Platform
**Team:** Vươn Lên Chính Mình

---

## 1. Individual Team Health Assessment

Team tự đánh giá theo thang điểm:

* **1 — Rất yếu**
* **2 — Cần cải thiện nhiều**
* **3 — Đạt mức cơ bản**
* **4 — Tốt**
* **5 — Rất tốt**

### Kết quả đánh giá

| Khía cạnh                       | Vũ Huy Hoàng | Tạ Thị Nga | Trần Hoài Nam |      Trung bình |
| --------------------------------- | -------------: | -----------: | --------------: | ---------------: |
| **Chất lượng AI**        |    **5** |            4 |               4 | **4.33/5** |
| **Tiến độ**              |    **5** |            4 |               5 | **4.67/5** |
| **Tinh thần team**         |    **5** |            5 |               4 | **4.67/5** |
| **Tốc độ ra sản phẩm** |    **4** |            5 |               4 | **4.33/5** |

### Điểm trung bình theo thành viên

| Thành viên              | Điểm trung bình |
| ------------------------- | -----------------: |
| **Vũ Huy Hoàng**  |   **4.75/5** |
| **Tạ Thị Nga**    |   **4.50/5** |
| **Trần Hoài Nam** |   **4.25/5** |

### Điểm Team Health chung

> **4.50 / 5 — VERY HEALTHY**

Team đang vận hành ở mức tốt. Các thành viên phối hợp hiệu quả, tiến độ phát triển nhanh và các capability chính của Internova đã tương đối đầy đủ.

Tuy nhiên, team vẫn còn một số điểm cần chuẩn hóa trước khi đưa sản phẩm vào pilot thực tế.

---

# 2. Team Health Analysis

## 2.1 Chất lượng AI — 4.33/5

Internova hiện đã có các thành phần AI quan trọng:

* RAG Pipeline.
* Knowledge Base.
* Semantic Routing.
* Retrieval.
* Guardrails.
* Response Validation.
* AI Monitoring.
* Document Version Management.
* CV–JD Matching.

Team đánh giá AI Quality ở mức **4.33/5**, tức là tốt nhưng chưa hoàn toàn đạt mức tối đa.

### Điểm mạnh

* AI không hoạt động như chatbot general-purpose.
* Có Knowledge Base riêng.
* Có RAG để grounding câu trả lời.
* Có guardrails.
* Có monitoring.
* Có kiểm soát document/version.

### Điểm cần cải thiện

Team cần chuẩn hóa:

* Golden Test Cases.
* Retrieval Evaluation.
* Groundedness Evaluation.
* Answer Correctness.
* Regression Testing.
* AI Quality Gate trước release.

> **Kết luận:** AI hiện đã tốt ở mức prototype/pilot preparation nhưng cần thêm bằng chứng định lượng trước khi production.

---

# 2.2 Tiến độ — 4.67/5

Đây là một trong những điểm mạnh của team.

Internova đã phát triển được nhiều module:

* Student Portal.
* Lecturer Portal.
* Admin Portal.
* AI Chatbot.
* RAG.
* Knowledge Base.
* Document Management.
* CV–JD Matching.
* Internship Progress Management.
* Authentication & Authorization.
* AI Monitoring.

### Điểm mạnh

* Team triển khai feature nhanh.
* Có khả năng xử lý bug và thay đổi requirement.
* Các thành viên chủ động xử lý công việc.
* Product scope ngày càng rõ.

### Điểm cần nâng

Cần cải thiện:

* Acceptance Criteria.
* Release Planning.
* Automated Testing.

để giảm rework sau implementation.

---

# 2.3 Tinh thần team — 4.67/5

Team có khả năng phối hợp tốt và trao đổi trực tiếp khi xuất hiện vấn đề.

### Vai trò/góc nhìn hiện tại

**Vũ Huy Hoàng**
→ AI / Technical / Engineering

**Tạ Thị Nga**
→ Product / UX / User Validation

**Trần Hoài Nam**
→ Pilot / Stakeholder / Business

### Điểm mạnh

* Thành viên chủ động trao đổi.
* Có tinh thần hỗ trợ.
* Có khả năng thống nhất quyết định nhanh.
* Technical và Product đều được đưa vào thảo luận.

### Điểm cần cải thiện

Một số task nằm giữa technical, product và stakeholder cần có owner rõ hơn để tránh overlap trách nhiệm.

> **Đánh giá:** Team spirit tốt và là một lợi thế của nhóm.

---

# 2.4 Tốc độ ra sản phẩm — 4.33/5

Team có tốc độ implementation tốt nhưng để biến một thay đổi thành một version đủ tin cậy cho user test vẫn cần nhiều bước.

Workflow hiện tại:

```text
Requirement
    ↓
Implementation
    ↓
Integration
    ↓
Manual Testing
    ↓
Bug Fix
    ↓
Demo
```

### Điểm mạnh

* Team nhỏ nên coordination nhanh.
* AI capability nằm trực tiếp trong product team.
* Technical decision được đưa ra nhanh.
* Feature có thể iteration liên tục.

### Điểm cần cải thiện

Cần bổ sung:

```text
Automated Testing
        +
AI Evaluation
        +
Release Gate
```

để tăng release velocity mà vẫn giữ quality.

---

# 3. Khía cạnh thấp nhất

Hai khía cạnh thấp nhất đều đạt:

> **4.33/5**

bao gồm:

1. **Chất lượng AI**
2. **Tốc độ ra sản phẩm**

Đây không phải các khía cạnh yếu, nhưng là hai khu vực có nhiều cơ hội cải thiện nhất trước pilot.

Hai vấn đề này cũng liên quan trực tiếp với nhau.

Nếu AI Evaluation chưa được tự động hóa thì:

* mỗi thay đổi RAG phải test lại thủ công;
* khó phát hiện regression;
* mất thời gian xác nhận release;
* tốc độ đưa feature tới người dùng bị giảm.

---

# 4. Điểm chênh lệch giữa các thành viên

Khác biệt rõ nhất xuất hiện ở hai khía cạnh.

## Chất lượng AI

| Thành viên             |      Điểm |
| ------------------------ | ----------: |
| **Vũ Huy Hoàng** | **5** |
| Tạ Thị Nga             |           4 |
| Trần Hoài Nam          |           4 |

### Giải thích

Hoàng trực tiếp làm việc sâu hơn với:

* RAG.
* Retrieval.
* Backend.
* Knowledge Base.
* Guardrails.
* Monitoring.

Do hiểu rõ các lớp kiểm soát kỹ thuật hiện tại, Hoàng đánh giá AI Quality ở mức cao hơn.

Nga và Nam nhìn từ góc độ user/pilot nên vẫn muốn có thêm user testing và evaluation evidence trước khi đánh giá tối đa.

---

## Tốc độ ra sản phẩm

| Thành viên           |      Điểm |
| ---------------------- | ----------: |
| Vũ Huy Hoàng         |           4 |
| **Tạ Thị Nga** | **5** |
| Trần Hoài Nam        |           4 |

### Giải thích

Nga đánh giá từ góc độ product/user và thấy team có khả năng đưa feature từ requirement tới demo khá nhanh.

Hoàng nhìn từ technical perspective nên tính thêm:

* integration;
* regression;
* AI testing;
* fixing;
* release verification.

Nam nhìn từ pilot perspective nên tính cả thời gian cần để một version đủ an toàn cho user thật.

> Sự chênh lệch giúp team nhìn sản phẩm từ nhiều góc độ thay vì chỉ dựa trên một đánh giá duy nhất.

---

# 5. Priority Problem

## Vấn đề ưu tiên trước milestone tiếp theo

> **Internova đã có AI capability tốt nhưng chưa có một AI Evaluation & Regression Process đủ chuẩn hóa để chứng minh chất lượng giữa các release.**

Milestone tiếp theo của team là:

> **Controlled Pilot với người dùng thực tế.**

Nếu không giải quyết vấn đề này:

* team khó chứng minh AI Quality với stakeholder;
* regression có thể không được phát hiện;
* update Knowledge Base có thể ảnh hưởng câu trả lời;
* testing thủ công làm giảm release velocity.

Vì vậy vấn đề team cần giải quyết không phải:

> “AI chưa tốt.”

Mà là:

> **“Team cần có bằng chứng và quy trình để chứng minh AI tốt một cách nhất quán.”**

---

# 6. Competency cần nâng cấp

## Role

**AI / Technical Product Lead**

**Owner:** Vũ Huy Hoàng

## Current Level

> **L2 — AI Practitioner, đang tiến gần L3 — AI Builder**

### Năng lực hiện tại

* Xây AI application thực tế.
* Xây RAG pipeline.
* Retrieval.
* Knowledge Base.
* Semantic routing.
* Guardrails.
* Backend integration.
* AI monitoring.
* AI system debugging.

## Competency cần nâng tiếp theo

> **AI Evaluation & Quality Engineering**

Bao gồm:

* Golden Cases.
* Retrieval Evaluation.
* Answer Correctness.
* Groundedness.
* Regression Detection.
* Quality Metrics.
* Release Quality Gate.

---

# 7. Competency Action — 30 ngày

> **Trong 30 ngày, xây dựng ít nhất 40 Golden Cases cho Internova và đưa AI Evaluation vào quy trình kiểm tra trước các release có thay đổi AI/RAG.**

Golden Cases bao gồm:

### Internship Knowledge

* Policy.
* Quy trình.
* Biểu mẫu.
* Deadline.
* Internship requirement.

### Career

* CV Analysis.
* CV–JD Matching.
* Interview Preparation.

### AI Safety

* Out-of-scope.
* Prompt Injection.
* Personal Data Request.
* Ambiguous Questions.

### RAG

* Correct Retrieval.
* Wrong Document Detection.
* Document Version Cases.

Mỗi case có:

```text
Question
Expected Intent
Expected Evidence
Expected Behavior
Pass Criteria
Result
```

---

# 8. Growth Plan 30 ngày

## Action 1 — AI Evaluation & Golden Test Set

### Vấn đề

AI hiện hoạt động tốt nhưng team cần evidence chuẩn hóa để xác nhận quality giữa các release.

### Hành động

> Xây dựng ít nhất **40 Golden Cases** và evaluation checklist cho các thay đổi AI/RAG.

### Owner

**Vũ Huy Hoàng**

### Deadline

**15/09/2026**

### Dấu hiệu hoàn thành

* Có ≥40 Golden Cases.
* Mỗi case có expected behavior.
* Có Pass/Fail Criteria.
* Có baseline evaluation.
* Đã chạy evaluation trên ít nhất 1 version.
* Có thể phát hiện regression trước release.

---

## Action 2 — Weekly Product & Team Health Review

### Vấn đề

Team phối hợp tốt nhưng cần duy trì alignment khi số lượng task và stakeholder tăng.

### Hành động

> Thực hiện **20 phút Product & Team Health Review mỗi tuần**.

### Owner

**Tạ Thị Nga**

### Deadline

**Bắt đầu 04/09/2026 và duy trì hàng tuần trong ít nhất 30 ngày.**

### Nội dung

```text
1. Tuần vừa rồi hoàn thành gì?
2. Blocker hiện tại?
3. Feedback mới?
4. AI Quality có thay đổi?
5. Milestone tiếp theo?
6. Priority tuần tới?
7. Owner của từng action?
```

### Dấu hiệu hoàn thành

* Có ≥4 weekly reviews.
* Mỗi review có action item.
* Action có owner.
* Blocker được ghi nhận.
* Không có critical task bị thiếu owner.

---

## Action 3 — Pilot Release Checklist

### Vấn đề

Team development nhanh nhưng cần tiêu chuẩn chung để xác định một version có đủ điều kiện cho user test hay không.

### Hành động

> Xây dựng và áp dụng **Pilot Release Checklist** trước mỗi release candidate.

### Owner

**Trần Hoài Nam**

### Phối hợp

* Vũ Huy Hoàng — AI & Technical.
* Tạ Thị Nga — Product & User Experience.

### Deadline

**22/09/2026**

### Checklist tối thiểu

* Critical flows PASS.
* Không có blocker bug.
* Authentication PASS.
* Authorization PASS.
* Knowledge Base sử dụng đúng version.
* AI Evaluation đạt ngưỡng.
* Privacy check PASS.
* Demo flow PASS.
* Monitoring hoạt động.
* Có issue owner khi lỗi xảy ra.

### Dấu hiệu hoàn thành

* Có checklist chính thức.
* Có Pass/Fail cho từng tiêu chí.
* Checklist được áp dụng cho ≥1 release candidate.
* Release blocker được xác định trước user testing.

---

# 9. Growth Plan Summary

| Vấn đề                            | Hành động 30 ngày                  | Owner                     | Deadline                         | Dấu hiệu hoàn thành           |
| ------------------------------------ | -------------------------------------- | ------------------------- | -------------------------------- | --------------------------------- |
| AI Quality cần evidence chuẩn hóa | Xây ≥40 Golden Cases + AI Evaluation | **Vũ Huy Hoàng**  | **15/09/2026**             | ≥40 cases + baseline + Pass/Fail |
| Cần duy trì team alignment         | Weekly Product & Team Health Review    | **Tạ Thị Nga**    | **04/09/2026 → 30 ngày** | ≥4 review + actions + owners     |
| Cần tiêu chuẩn pilot-ready        | Xây Pilot Release Checklist           | **Trần Hoài Nam** | **22/09/2026**             | Checklist dùng trên ≥1 release |

---

# 10. Team Health Summary

| Khía cạnh                       |        Trung bình |
| --------------------------------- | -----------------: |
| **Chất lượng AI**        | ⭐**4.33/5** |
| **Tiến độ**              | ⭐**4.67/5** |
| **Tinh thần team**         | ⭐**4.67/5** |
| **Tốc độ ra sản phẩm** | ⭐**4.33/5** |

### Overall Team Health

> **4.50 / 5 — VERY HEALTHY**

---

# 11. Mục tiêu sau 30 ngày

| Khía cạnh             | Hiện tại |          Target |
| ----------------------- | ---------: | --------------: |
| Chất lượng AI        |       4.33 | **≥4.6** |
| Tiến độ              |       4.67 | **≥4.8** |
| Tinh thần team         |       4.67 | **≥4.8** |
| Tốc độ ra sản phẩm |       4.33 | **≥4.6** |

Improvement phải được chứng minh bằng:

* AI Evaluation.
* Golden Cases.
* Weekly Review.
* Release Checklist.
* Pilot Feedback.

---

# 12. Growth Principle

> **Team Internova hiện đang vận hành tốt. Trong 30 ngày tới, mục tiêu không phải xây thêm thật nhiều feature mà là chuẩn hóa AI Quality, tăng độ tin cậy của release và chuẩn bị một phiên bản đủ tốt cho controlled pilot.**

---

# GATE 4 — Growth Plan có thể thực thi

* [X] Cả 3 thành viên đã chấm đủ 4 khía cạnh Team Health.
* [X] Điểm có cả mức **4 và 5**, phản ánh sự khác biệt thực tế.
* [X] Điểm trung bình của cả 4 khía cạnh đều ≥ **4.33/5**.
* [X] Điểm Team Health chung đạt **4.50/5**.
* [X] Vũ Huy Hoàng có điểm trung bình cá nhân cao nhất: **4.75/5**.
* [X] Đã xác định hai khía cạnh có điểm thấp nhất.
* [X] Đã phân tích sự chênh lệch giữa các thành viên.
* [X] Đã chọn vấn đề ưu tiên ảnh hưởng trực tiếp tới pilot.
* [X] Đã chọn role: **AI / Technical Product Lead**.
* [X] Current level: **L2 — AI Practitioner, tiến gần L3 — AI Builder**.
* [X] Competency cần nâng: **AI Evaluation & Quality Engineering**.
* [X] Có action thực hành trong 30 ngày.
* [X] Growth Plan có đúng 3 action.
* [X] Mỗi action có Owner.
* [X] Mỗi action có Deadline.
* [X] Mỗi action có dấu hiệu hoàn thành đo được.

### Kết quả

**GATE 4: PASS ✅**

# Phase 5 — Final Self-check & Submission

**Project:** Internova AI Platform
**Team:** Vươn Lên Chính Mình

---

## 1. Stakeholder Self-check

* [X] Có ít nhất 6 stakeholder cụ thể.
* [X] Team đã xác định 8 stakeholder liên quan đến Internova.
* [X] Stakeholder được phân loại theo **Influence × Interest**.
* [X] Đã sử dụng đúng 4 quadrant:

  * Champion
  * Blocker
  * Supporter
  * Bystander
* [X] Mỗi stakeholder có **stance** riêng:

  * Ủng hộ
  * Trung lập
  * Chưa được thuyết phục
* [X] Không mặc định stance chỉ dựa trên quadrant.
* [X] Đã chọn 4 stakeholder ưu tiên.
* [X] Có 2 stakeholder đang ủng hộ để tận dụng ảnh hưởng.
* [X] Có 2 stakeholder cần ưu tiên thuyết phục.
* [X] Cả 4 stakeholder ưu tiên đều có hành động cụ thể trong 1–2 tuần.

### 4 stakeholder ưu tiên

| Stakeholder               | Stance                                 | Action chính                                               |
| ------------------------- | -------------------------------------- | ----------------------------------------------------------- |
| Giảng viên / Mentor     | Ủng hộ mạnh                         | Demo sản phẩm + lấy feedback + xin kết nối stakeholder |
| Sinh viên VinUni         | Ủng hộ                               | User test với ít nhất 5 sinh viên                       |
| VinUni Internship Program | Chưa được thuyết phục đầy đủ | Pilot Brief + buổi review                                  |
| University Admin          | Trung lập                             | Demo Admin/Knowledge Base workflow                          |

**Stakeholder Check: PASS ✅**

---

# 2. Pitch & RACI Self-check

## Pitch

* [X] Pitch sử dụng **Conclusion First**.
* [X] Đề xuất được nói ngay từ đầu.
* [X] Có 3 lý do chính.
* [X] Có evidence từ prototype Internova hiện tại.
* [X] Không khẳng định sản phẩm đã production-ready khi chưa có bằng chứng.
* [X] Có một **Small Ask** cụ thể.
* [X] Có một phản biện có khả năng xảy ra.
* [X] Có cách xử lý phản biện dựa trên giảm rủi ro và evidence.

### Conclusion

> Team đề xuất VinUni cho phép Internova tiến tới một **controlled pilot nhỏ** thay vì triển khai rộng ngay.

### Evidence

Internova hiện đã có:

* Student Portal.
* Lecturer Portal.
* Admin Portal.
* AI/RAG Chatbot.
* Knowledge Base.
* Document/version management.
* Guardrails.
* AI Monitoring.
* CV–JD Matching.

### Small Ask

> Một buổi review khoảng 30 phút để thống nhất điều kiện pilot và xin phép kiểm thử các flow chính với ít nhất 5 sinh viên.

### Main Objection

> “AI chưa đủ đáng tin để sử dụng cho các thông tin quan trọng liên quan đến thực tập.”

### Response

Team giảm rủi ro bằng:

* RAG.
* Controlled Knowledge Base.
* Document versioning.
* Guardrails.
* AI Evaluation.
* Pilot phạm vi nhỏ trước khi scale.

---

## RACI

Team đã chọn 6 công việc quan trọng trong 1–2 tháng tới.

| Công việc                          | Accountable               |
| ------------------------------------ | ------------------------- |
| Chốt use case và phạm vi pilot    | **Trần Hoài Nam** |
| RAG / Knowledge Base / Guardrails    | **Vũ Huy Hoàng**  |
| Student / Lecturer / Admin workflows | **Tạ Thị Nga**    |
| AI Evaluation / Regression Testing   | **Vũ Huy Hoàng**  |
| User Testing & Feedback              | **Tạ Thị Nga**    |
| Pilot Brief & Demo                   | **Trần Hoài Nam** |

* [X] Có 6 công việc quan trọng.
* [X] Mỗi công việc có đúng **1 Accountable**.
* [X] Responsibility phù hợp với capability của từng thành viên.
* [X] Stakeholder ở Phase 1 xuất hiện hợp lý trong Pitch và RACI.

**Pitch & RACI Check: PASS ✅**

---

# 3. AI Team Design Self-check

## Architecture

Team chọn:

> **Embedded AI Team**

### Lý do

Team hiện chỉ có 3 thành viên và AI là capability cốt lõi của chính Internova.

Việc đặt AI trực tiếp trong product squad giúp:

* giảm coordination overhead;
* iteration nhanh hơn;
* kết nối AI trực tiếp với product workflow;
* xử lý nhanh feedback trước pilot.

* [X] Architecture được chọn rõ ràng.
* [X] Có lý do phù hợp với quy mô team.
* [X] Không sao chép cấu trúc của công ty lớn.

---

## Core Roles

| Thành viên              | Core Capability                |
| ------------------------- | ------------------------------ |
| **Vũ Huy Hoàng**  | AI / Technical / Engineering   |
| **Tạ Thị Nga**    | Product / UX / User Validation |
| **Trần Hoài Nam** | Pilot / Stakeholder / Business |

* [X] Role phù hợp với nhu cầu hiện tại.
* [X] Không tạo role không cần thiết.

---

## Capability Gaps

Team xác định 3 capability gap ưu tiên:

### 1. Internship Domain Expertise

**Resourcing:** Partner

→ Hợp tác với giảng viên, mentor và VinUni Internship Program.

### 2. AI Evaluation / MLOps

**Resourcing:** Hire khi scale.

→ Capability này trở thành năng lực dài hạn khi Internova chuyển từ pilot sang production.

### 3. Security & Privacy

**Resourcing:** Outsource.

→ Cần specialist độc lập trước khi mở rộng user và dữ liệu thực.

* [X] Có capability gap rõ ràng.
* [X] Có Priority Resourcing.
* [X] Có sử dụng Hire / Partner / Outsource.
* [X] Mỗi lựa chọn đều có lý do.
* [X] Có thời điểm cần capability rõ ràng.

**AI Team Design Check: PASS ✅**

---

# 4. Team Health & Growth Plan Self-check

Team đã đánh giá đủ 4 khía cạnh:

| Khía cạnh             | Điểm trung bình |
| ----------------------- | -----------------: |
| Chất lượng AI        |   **4.33/5** |
| Tiến độ              |   **4.67/5** |
| Tinh thần team         |   **4.67/5** |
| Tốc độ ra sản phẩm |   **4.33/5** |

### Overall Team Health

> **4.50 / 5 — Very Healthy**

---

## Priority Problem

Team xác định vấn đề ưu tiên:

> **Internova đã có AI capability tốt nhưng cần một AI Evaluation & Regression Process chuẩn hóa để chứng minh chất lượng ổn định giữa các release trước pilot.**

---

## Competency cần nâng

**Role:** AI / Technical Product Lead
**Owner:** Vũ Huy Hoàng

**Current level:**

> L2 — AI Practitioner, đang tiến gần L3 — AI Builder.

**Competency cần nâng:**

> AI Evaluation & Quality Engineering.

---

## Growth Plan 30 ngày

| Vấn đề                            | Hành động                           | Owner                     | Deadline                                | Dấu hiệu hoàn thành                     |
| ------------------------------------ | -------------------------------------- | ------------------------- | --------------------------------------- | ------------------------------------------- |
| AI Quality cần evidence chuẩn hóa | Xây ≥40 Golden Cases + AI Evaluation | **Vũ Huy Hoàng**  | **15/09/2026**                    | ≥40 cases + baseline + Pass/Fail           |
| Cần duy trì team alignment         | Weekly Product & Team Health Review    | **Tạ Thị Nga**    | **Từ 04/09/2026 trong 30 ngày** | ≥4 reviews + action + owner                |
| Cần tiêu chuẩn pilot-ready        | Pilot Release Checklist                | **Trần Hoài Nam** | **22/09/2026**                    | Checklist dùng trên ≥1 release candidate |

* [X] Đã đánh giá đủ 4 Team Health dimensions.
* [X] Có vấn đề ưu tiên.
* [X] Có competency cần nâng.
* [X] Growth Plan có tối đa 3 action.
* [X] Mỗi action có owner.
* [X] Mỗi action có deadline.
* [X] Mỗi action có dấu hiệu hoàn thành đo được.

**Team Health Check: PASS ✅**

---

# 5. Consistency Check giữa 4 Artefact

## Check 1 — Stakeholder → Pitch

Stakeholder quan trọng tại Phase 1:

> **VinUni Internship Program**

được chọn làm stakeholder chính trong Pitch tại Phase 2.

**Consistency: PASS ✅**

---

## Check 2 — Stakeholder → RACI

Phase 1 xác định:

* VinUni Internship Program có ảnh hưởng rất cao.
* University Admin cần được thuyết phục.
* Sinh viên cần được sử dụng để kiểm chứng user value.

Phase 2 đưa các stakeholder này vào:

* Pilot scope.
* User testing.
* Demo.
* Product review.

**Consistency: PASS ✅**

---

## Check 3 — Capability Gap → Team Health

Phase 3 xác định:

> **AI Evaluation / MLOps là một capability gap quan trọng.**

Phase 4 xác định:

> **AI Quality và Release Speed là hai khía cạnh còn nhiều cơ hội cải thiện nhất.**

Growth Plan sau đó chọn:

> **Xây Golden Cases + AI Evaluation Process.**

Như vậy capability gap và Team Health problem liên kết trực tiếp với nhau.

**Consistency: PASS ✅**

---

## Check 4 — Growth Plan → RACI

### Vũ Huy Hoàng

RACI:

> Accountable cho AI/RAG và AI Evaluation.

Growth Plan:

> Owner của Golden Cases & AI Evaluation.

**Khớp ✅**

### Tạ Thị Nga

RACI:

> Accountable cho Product Workflow và User Testing.

Growth Plan:

> Owner của Product & Team Health Review.

**Khớp ✅**

### Trần Hoài Nam

RACI:

> Accountable cho Pilot Scope và Pilot Brief.

Growth Plan:

> Owner của Pilot Release Checklist.

**Khớp ✅**

---

# 6. Final Artefact Structure

PDF cuối cùng gồm đúng **4 trang**:

### Trang 1 — Stakeholder Map & Strategy

Bao gồm:

* Influence × Interest Matrix.
* Stance.
* 4 stakeholder ưu tiên.
* 4 concrete actions.

### Trang 2 — Pitch & RACI

Bao gồm:

* Conclusion First Pitch.
* Evidence.
* Small Ask.
* Objection & Response.
* RACI Matrix.

### Trang 3 — AI Team Design

Bao gồm:

* Embedded Architecture.
* Core Roles.
* Capability Gaps.
* Priority Resourcing.
* Squad Goal.

### Trang 4 — Team Health & Growth Plan

Bao gồm:

* Team Health Score.
* Priority Problem.
* Competency L2 → L3.
* 30-Day Growth Plan.

---

# 7. Final Repository Structure

Repository của team:

```text
Track1_Day27_TeamVuonLenChinhMinh_/
│
├── README.md
└── Day27_AI-Team-Lab_TeamVuonLenChinhMinh.pdf
```

---

# 8. README Final Check

`README.md` cần có:

* [X] Tên team: **Vươn Lên Chính Mình**
* [X] Tên dự án: **Internova AI Platform**
* [X] Danh sách 3 thành viên.
* [X] Phase 0 Scope.
* [X] Mục tiêu 1–3 tháng.
* [X] Người tổng hợp / trưởng nhóm.
* [X] Thông tin về artefact.
* [X] Link demo
* [X] File PDF được đặt trong repository.

### Thành viên

| Họ và tên              | Mã học viên |
| ------------------------- | -------------- |
| **Vũ Huy Hoàng**  | 2A202601057    |
| **Tạ Thị Nga**    | 2A202601125    |
| **Trần Hoài Nam** | 2A202601751    |

---

# 9. PDF Final Check

File:

`Day27_AI-Team-Lab_TeamVuonLenChinhMinh.pdf`

Phải đảm bảo:

* [X] Có đủ 4 artefact.
* [X] Tối đa 4 trang.
* [X] Không chứa nội dung ngoài phạm vi project.
* [X] Tên thành viên nhất quán.
* [X] Tên stakeholder nhất quán.
* [X] Owner nhất quán với RACI.
* [X] Growth Plan nhất quán với Team Health.
* [X] Nội dung dễ đọc.
* [X] Không có placeholder chưa điền.

---

# 10. Final GitHub Check

Trước khi nộp, trưởng nhóm kiểm tra:

* [X] Repository đúng của team.
* [X] Repository có `README.md`.
* [X] Repository có `Day27_AI-Team-Lab_TeamVuonLenChinhMinh.pdf` sau khi export.
* [X] PDF không quá 4 trang.
* [X] GitHub repository truy cập được.
* [X] Link PDF mở được từ GitHub.
* [X] Các thay đổi cuối đã được commit và push.

---

### Kết quả

**GATE 5: PASS ✅**
