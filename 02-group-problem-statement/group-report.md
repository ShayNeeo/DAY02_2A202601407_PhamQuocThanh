# 02 — Group Problem Statement

> Nhóm: Rubric Audit | Cohort: 3 | Ngày: 27/07/2026

---

## Thành viên nhóm

| STT | MSSV | Họ và tên | Vai trò trong nhóm |
|-----|-----------|-------------|--------------------|
| 1 | 2A202601407 | Phạm Quốc Thanh | A — Product & Experiment Lead (team lead: persona/problem, interviews, validation, BMC, business metric) |
| 2 | 2A202601163 | Nguyễn Trần Hội Thắng | D — Full-stack UX & GTM Lead (review UX, deployment, instrumentation, funnel) |
| 3 | 2A202601017 | Nguyễn Thành An | B — AI & Evaluation Lead (AI necessity, prompt/model, gold protocol, ablation, error analysis) |
| 4 | 2A202602038 | Vũ Quang Nhật | C — Data Quality & Backend Lead (profiler, RuleSpec, compiler, API, safe execution) |

> Team size: 4 người. Thanh làm team lead kiêm Product & Experiment Lead. Các vai trò B/C/D được phân công ngẫu nhiên cho Thắng, An, Nhật.

---

## Phase 3 — Group Convergence: từ candidates về 1

### Bước 3.1 — Trình bày top 3

Mỗi người trình bày 3 candidates, mỗi candidate 1-2 phút.

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh |
|---|---|---|---|---|---|
| 1 | Thanh | Kiểm tra Rubric bài nộp | Sinh viên nộp bài tập lớn | Cuộn đối chiếu thủ công Rubric và bài làm | Workflow rõ, metric thời gian đo được |
| 2 | Thanh | Đọc paper dài trước deadline | Sinh viên làm research | Đọc 10-15 trang và tóm tắt ý chính | Pain thật, nhưng quality metric khó |
| 3 | Thanh | Tổng hợp weekly report | Junior PM | Viết narrative từ raw data | Pattern kinh điển, nhưng nhiều tool có sẵn |
| 4 | Thắng | Lục Discord nhớ deadline | Sinh viên nhiều môn | Mở từng kênh Discord tìm deadline | Lặp lại thường xuyên, nhưng data access phức tạp |
| 5 | Thắng | Theo dõi tiến độ nhiều môn | Sinh viên | Gom progress từ nhiều nguồn | Impact rộng, nhưng khó isolate AI injection point |
| 6 | Thắng | Phân công task nhóm | Nhóm trưởng | Chia việc và follow-up thủ công | Có thể giải bằng rule/template tốt |
| 7 | An | Tóm tắt audio bài giảng | Sinh viên học online | Nghe lại 2-3 tiếng bài giảng | Pain thật, nhưng transcription tool có sẵn |
| 8 | An | Chuẩn bị slide thuyết trình | Nhóm làm presentation | Viết bullet point từ tài liệu dài | Lặp lại, nhưng AI có thể hỗ trợ tốt |
| 9 | An | Định dạng bài báo cáo | Sinh viên nộp báo cáo | Canh lề, font, mục lục thủ công | Rule-based; AI overkill |
| 10 | Nhật | Trả lời câu hỏi nộp bài trùng lặp | Trợ giảng, mentor | Copy-paste cùng câu trả lời | Có thể giải bằng FAQ/rule |

### Bước 3.2 — Gom trùng / cluster

Nhóm 3-4 người, mỗi người share top 3. Tổng cộng khoảng 9-12 candidates.

| Cluster | Candidate examples | Pattern chung |
|---|---|---|
| Kiểm tra & Chấm điểm | Kiểm tra Rubric bài nộp, định dạng bài báo cáo | Rà soát sản phẩm bài viết/bài nộp theo bộ tiêu chí cho trước |
| Đọc & Tổng hợp tài liệu | Đọc paper dài, tóm tắt audio bài giảng | Xử lý lượng thông tin văn bản/âm thanh lớn trước deadline |
| Quản lý công việc & Deadline | Lục Discord nhớ deadline, theo dõi tiến độ nhiều môn, phân công task nhóm | Quản lý thời gian và phân công công việc rải rác |
| Hỗ trợ nhóm & Thuyết trình | Chuẩn bị slide thuyết trình, trả lời câu hỏi nộp bài trùng lặp | Hỗ trợ truyền thông và tổng hợp tài liệu trình bày cho nhóm |

### Bước 3.3 — Shortlist

Hỏi:

- Có ai trong nhóm hiểu workflow thật đủ sâu không?
- Actor có cụ thể không?
- Bottleneck có phải một bước cụ thể không?
- Impact có thể đo không?
- Có thể vẽ before/after workflow không?
- Có thể so sánh Rule / Workflow / Agent không?
- Có quá rộng cho lab hôm nay không?

| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| Kiểm tra Rubric bài nộp | Workflow rõ, ai cũng trải qua, metric thời gian đo được | Cần xác định đúng loại bài tập có Rubric chi tiết |
| Đọc paper dài | Pain thật với sinh viên làm research | Quality metric "tóm tắt đúng" khó thống nhất |
| Lục Discord nhớ deadline | Nhiều người gặp, lặp lại thường xuyên | Data access API Discord phức tạp, scope quá rộng |

### Bước 3.4 — Score để đồng thuận

Chấm 1-5. Điểm không cần tuyệt đối; mục tiêu là ép nhóm nói rõ lý do.

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Kiểm tra Rubric bài nộp | 5 | 5 | 5 | 5 | 5 | 5 | 4 | 34 |
| Đọc paper dài | 4 | 4 | 4 | 4 | 3 | 4 | 4 | 27 |
| Lục Discord nhớ deadline | 4 | 5 | 3 | 3 | 5 | 4 | 4 | 28 |

Nhóm chọn: **Kiểm tra Rubric bài nộp**.

Vì sao chọn:

- Có workflow rõ nhất.
- Có baseline thời gian.
- Có thể validate nhanh với các sinh viên khác.
- Có thể research các tool/pattern có sẵn.
- Có thể vẽ before/after rất rõ.

Vì sao không chọn các bài khác:

- Đọc paper dài: impact rộng nhưng quality metric tóm tắt bài báo khó thống nhất trong thời gian lab.
- Lục Discord nhớ deadline: data access API tin nhắn cá nhân/nhóm phức tạp, dễ trượt sang hệ thống bot quá lớn.

Nếu có disagreement, nhóm xử lý thế nào: Score matrix cho kết quả rõ ràng (34 vs 27-28). Nhóm thống nhất nhanh vì candidate Kiểm tra Rubric vượt trội trên mọi tiêu chí.

---

## Phase 4 — Quick Validation + Research giải pháp

### Bước 4.1 — Quick validation

Nhóm hỏi nhanh 3 sinh viên quen biết.

| Nguồn | Số người | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Quick interview | 3 | 2/3 người từng bị trừ điểm vì quên 1 tiêu chí nhỏ trong Rubric; đều mất thời gian rà soát | 1 người nói họ chỉ nộp bài nhỏ không có Rubric chi tiết | Thu hẹp problem: không phải "bài tập nhỏ", mà là "bài tập lớn/báo cáo có Rubric chi tiết" |
| Mini poll trong lớp | 6 | 4/6 từng phải cuộn đọc lại bài làm để xem đã đủ ý theo Rubric chưa | Một số bài tập code có Autograder riêng | Thêm non-AI alternative: checklist thủ công + template |

Insight sau validation:

```text
Pain thật không nằm ở việc "đọc Rubric" đơn thuần. Pain nằm ở đoạn đối chiếu ngữ cảnh giữa từng tiêu chí trong Rubric với toàn bộ nội dung file bài làm xem đã viết đủ hay chưa.
```

### Bước 4.2 — Research giải pháp đã có

Nhóm tìm các hướng đã có sẵn, không giả định phải tự build từ đầu.

| Nguồn / tool / case | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Turnitin Rubric Feedback | https://www.turnitin.com/products/feedback-studio | Chấm điểm & feedback theo Rubric | Tốt cho giảng viên chấm bài | Thiết kế cho người chấm (Grader), không phục vụ sinh viên tự rà soát trước khi nộp | Pattern tốt: hiển thị bảng Rubric checklist kèm minh chứng |
| Canvas SpeedGrader AI | https://www.instructure.com/canvas | Hỗ trợ đối chiếu tiêu chí Rubric | Tích hợp sẵn trong LMS | Sinh viên không truy cập được tính năng tự audit trước khi bấm nộp | Có thể học cách map tiêu chí Rubric vào dòng văn bản |
| Gradescope Rubric Audit | https://www.gradescope.com | Phân loại câu trả lời theo Rubric | Tốt cho bài thi tự luận | Chủ yếu dành cho giáo viên tạo Rubric | Cần giao diện đơn giản cho sinh viên upload bài làm |
| ChatGPT Rubric Prompt | https://chatgpt.com | Nhận diện tiêu chí thiếu sót trong bài | Linh hoạt, đọc được nhiều định dạng file | AI có thể bịa ra tiêu chí không có trong Rubric nếu prompt không chuẩn | Workflow hợp lý hơn Agent: gom Rubric + Bài làm → AI Audit → User Review |

Research takeaway:

```text
Không nên build một agent tự động sửa bài và nộp ngay. Hướng hợp lý hơn là Workflow: tự động phân tích Rubric và bài làm, dùng AI để xuất Rubric Audit Report, sinh viên review và tự bổ sung nội dung trước khi nộp.
```

---

## Phase 5 — Workflow + Problem Statement

### Bước 5.1 — Current workflow bản nhóm

Vẽ workflow hiện tại kỹ hơn bản cá nhân. Mỗi bước nên có: actor, input, output, thời gian/tần suất, handoff, bottleneck.

```text
CURRENT STATE — 5 bước, 45 phút

[1 Mở Rubric & Bài làm: 5']
→ [2 Đọc tiêu chí Rubric: 10']
→ [3 Cuộn bài làm đối chiếu thủ công: 15']  <-- bottleneck
→ [4 Chỉnh sửa & bổ sung mục thiếu: 10']
→ [5 Kiểm tra định dạng & Nộp LMS: 5']
```

| Bước | Actor | Input | Output | Thời gian/tần suất | Ghi chú |
|---|---|---|---|---|---|
| 1 | Sinh viên | File Rubric + file bài làm | Hai file đã mở | 5' | Mỗi lần nộp bài |
| 2 | Sinh viên | Rubric | Hiểu danh sách tiêu chí | 10' | Đọc lần lượt từng mục |
| 3 | Sinh viên | Rubric + bài làm | Danh sách tiêu chí đã đối chiếu | 15' | BOTTLENECK — cuộn qua lại giữa 2 file |
| 4 | Sinh viên | Danh sách mục thiếu | Bài làm đã hoàn thiện | 10' | Bổ sung nội dung còn thiếu |
| 5 | Sinh viên | Bài làm hoàn thiện | Đã nộp LMS | 5' | Kiểm tra định dạng lần cuối |

Bottleneck chính:

```text
Bước 3 — Cuộn đối chiếu thủ công giữa Rubric và bài làm. Sinh viên phải tự nhớ từng tiêu chí rồi cuộn tìm trong bài làm xem đã viết đủ chưa. Dễ bỏ sót tiêu chí nhỏ (0.5-1.0 điểm). Đặc biệt tệ với bài dài 5-15 trang.
```

### Bước 5.2 — Future workflow bản nhóm

Vẽ workflow sau tối ưu. Cần thể hiện: bước nào Rule xử lý, bước nào AI/Workflow hỗ trợ, bước nào con người vẫn làm, boundary ở đâu, phương án quay về nếu AI sai.

```text
FUTURE STATE — 5 bước, 22 phút

[1 Upload Rubric & Bài làm: 2']               -- Rule/script
→ [2 AI phân tích & đối chiếu ngữ cảnh: 2']     -- Workflow step
→ [3 AI xuất Rubric Audit Report: 1']           -- Workflow step
→ [4 Sinh viên review & bổ sung ý thiếu: 15']  -- Human boundary
→ [5 Sinh viên nộp LMS: 2']

Fallback:
AI draft sai hoặc không rõ → sinh viên bỏ audit report và tự rà soát lại theo checklist thủ công.

Bottleneck mới:
Sinh viên review & bổ sung ý thiếu. Đây là bottleneck chấp nhận được vì đó là điểm kiểm soát chất lượng nội dung.
```

Before/after impact:

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---:|---:|---|
| Tổng thời gian | 45 phút | Dưới 22 phút | Target chính |
| Số bước | 5 | 5 | Không chỉ giảm bước, mà giảm effort ở bước cuộn đối chiếu |
| Bước thủ công | 5/5 | 2/5 | Sinh viên vẫn review và viết bổ sung nội dung |
| Bottleneck chính | Cuộn bài làm đối chiếu thủ công | Review & bổ sung ý thiếu | Human boundary |
| Risk mới | Không có AI hallucination | Có hallucination risk | Cần review kĩ báo cáo audit trước khi nộp |

### Bước 5.3 — Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên nộp bài tập lớn / báo cáo môn học có Rubric chi tiết. |
| **Workflow** | Mở Rubric → đọc tiêu chí → cuộn bài làm đối chiếu → sửa mục thiếu → nộp LMS. |
| **Bottleneck** | Bước cuộn đối chiếu thủ công giữa Rubric và bài làm mất khoảng 15 phút và dễ bỏ sót tiêu chí phụ. |
| **Impact** | Tổng workflow mất khoảng 45 phút/bài cho 1 sinh viên; dễ bị trừ 0.5-1.5 điểm do thiếu mục nhỏ. |
| **Success Metric** | Giảm tổng thời gian từ 45 phút xuống dưới 22 phút; 100% không bị trừ điểm do thiếu tiêu chí Rubric. |
| **Boundary** | AI không tự viết lại toàn bộ bài làm; không tự nộp bài lên LMS; không tự thay đổi định dạng gốc của file. |

---

## Phase 6 — Rule / Workflow / Agent + Decision

### Bước 6.0 — Ma trận độ phù hợp với AI

Bài toán nằm ở ô: **Độ mơ hồ cao × Độ phức tạp thấp.**

Vì sao:

- Độ mơ hồ cao: không có đáp án đúng/sai rõ ràng cho việc "bài làm đã cover đủ ý chưa". AI cần hiểu ngữ cảnh văn bản và semantic matching giữa Rubric và nội dung.
- Độ phức tạp thấp: workflow đơn giản (upload → AI audit → review → nộp); ít nguồn dữ liệu; không cần phối hợp nhiều bước động.

### Bước 6.1 — So sánh Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | Checklist Excel/Docs template tĩnh | Đủ nếu bài nộp chỉ cần kiểm tra số trang, font chữ | Không đọc được ngữ cảnh nội dung bài làm đã đủ ý hay chưa | Không chọn làm toàn bộ, nhưng dùng cho khâu kiểm tra định dạng |
| **Workflow** | Upload Rubric & Bài làm → AI đọc ngữ cảnh → AI xuất Rubric Audit Report → Sinh viên review | Hợp vì workflow tuyến tính, AI chỉ hỗ trợ bước đọc đối chiếu ngữ cảnh | Audit sai/bỏ sót tiêu chí, cần sinh viên review | Chọn |
| **Agent** | Agent tự lấy Rubric, tự sửa nội dung bài làm, tự nộp lên LMS | Chỉ cần nếu bài làm được tự động hóa hoàn toàn từ A-Z | Quá rộng, vi phạm quy định liêm chính học thuật nếu AI tự viết bài | Chưa chọn |

Mức chọn:

```text
Workflow.
```

Vì sao chọn:

- Khâu kiểm tra định dạng file có thể dùng rule/script.
- Khâu đối chiếu ngữ cảnh Rubric cần AI hỗ trợ hiểu văn bản.
- Sinh viên vẫn review và tự bổ sung nội dung nên rủi ro được kiểm soát.
- Chưa cần agent vì workflow không cần tự lập kế hoạch động hay tự viết bài thay sinh viên.

Vì sao không chọn mức đơn giản hơn:
- Rule-only: checklist tĩnh chỉ kiểm tra được format, không hiểu ngữ cảnh nội dung.
- Agent: tự viết bài thay sinh viên là vi phạm liêm chính học thuật và vượt scope.

### Bước 6.2 — Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên nộp bài tập lớn / báo cáo môn học có Rubric chi tiết. |
| **Workflow** | Upload Rubric & Bài làm → AI phân tích đối chiếu → AI xuất Audit Report → Sinh viên review & bổ sung → Nộp LMS. |
| **Bottleneck** | Đối chiếu ngữ cảnh từng tiêu chí Rubric với bài làm mất 15 phút và dễ bỏ sót mục nhỏ. |
| **Impact** | Khoảng 45 phút/bài; dễ bị trừ 0.5-1.5 điểm do thiếu mục phụ. |
| **Success Metric** | Giảm tổng thời gian xuống dưới 22 phút; 100% không bị trừ điểm do thiếu tiêu chí trong Rubric. |
| **Boundary** | AI không tự viết bài thay sinh viên, không tự nộp lên LMS, không sửa nội dung gốc nếu chưa có sinh viên duyệt. |
| **AI intervention point** | Sau khi Rubric và bài làm được upload lên, trước bước sinh viên sửa/bổ sung nội dung cuối. |
| **Mức chọn** | Workflow: rule/script nhận file, AI xuất Rubric Audit Report, sinh viên review & tự sửa. |
| **Rủi ro & người thật kiểm tra** | Risk: hallucination, báo nhầm tiêu chí đã đạt/chưa đạt. Người thật review: Sinh viên phải đọc lại báo cáo audit và tự tay bổ sung bài viết. |

### Bước 6.3 — Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor và workflow đã rõ chưa? | **Yes** | Actor: sinh viên nộp bài tập lớn có Rubric. Workflow 5 bước rõ ràng. |
| Baseline và success metric đã đo được chưa? | **Yes** | Baseline 45 phút từ trải nghiệm thật và mini poll. Target dưới 22 phút. |
| Có data/input đủ dùng chưa? | **Yes** | Rubric và bài làm mẫu từ 2 bài tập lớn gần nhất. |
| Nếu AI sai, hậu quả có chấp nhận được không? | **Yes** | AI không tự nộp bài; sinh viên review trước. Fallback về checklist thủ công. |
| Có người review/owner vận hành không? | **Yes** | Sinh viên là reviewer cuối cùng; tự tay bổ sung nội dung. |
| Có cách non-AI đơn giản hơn không? | **Yes, nhưng không đủ** | Checklist tĩnh kiểm tra được format nhưng không đọc được ngữ cảnh nội dung. |

Decision:

```text
Go với scope nhỏ.
```

Lý do:

- Problem rõ, workflow rõ, metric rõ.
- Có non-AI components (rule/script kiểm tra format).
- AI nằm ở một bước cụ thể, không ôm toàn bộ workflow.
- Human review rõ.

Pilot nhỏ nhất:

- Dùng file Rubric và bài làm mẫu của 2 bài tập lớn gần nhất.
- Chạy workflow bán thủ công: Sinh viên paste Rubric và bài làm vào prompt chuẩn.
- AI xuất Rubric Audit Report (dạng bảng Checklist: Đạt / Chưa đạt / Gợi ý vị trí thiếu).
- Sinh viên đo thời gian rà soát và đánh giá số mục AI phát hiện đúng.

Exit / rollback:

- Nếu sinh viên vẫn phải đối chiếu thủ công lại hơn 70% số tiêu chí trong 2 bài nộp liên tiếp, hạ xuống checklist Excel thông thường.
- Nếu AI báo nhầm tiêu chí hoặc bịa tiêu chí không có trong Rubric, không cho dùng trực tiếp để rà soát điểm.

Decision rationale:

- Problem rõ, workflow rõ, metric rõ.
- Có non-AI components.
- AI nằm ở một bước cụ thể, không ôm toàn bộ workflow.
- Human review rõ.
