# 01 — Individual Problem Scan

> Học viên: Phạm Quốc Thanh | Mã: 2A202601407 | Cohort: 3

---

## Phase 1 — Individual Scan: 10 problems

### Bảng scan

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại + Tốn thời gian | Mỗi lần nộp bài tập lớn, sinh viên phải cuộn qua lại giữa Rubric và bài làm để kiểm tra xem đã viết đủ tiêu chí chưa | Sinh viên nộp bài tập lớn / báo cáo môn học | Mất ~45 phút/bài; 4/6 sinh viên poll cho biết từng làm việc này |
| 2 | Lặp lại + Tốn thời gian | Đọc paper nghiên cứu 10-15 trang và tóm tắt ý chính trước deadline | Sinh viên làm research, học viên AI in Action | Mất 45-60 phút/paper; dễ bỏ sót ý quan trọng |
| 3 | Tốn thời gian | Tổng hợp weekly report từ nhiều nguồn (Jira, Slack, Sheets, Docs) mỗi thứ Hai | PM, EM, CEO | Mất ~90 phút/tuần; report hay trễ deadline |
| 4 | AI có thể tốt hơn | Đối chiếu ngữ cảnh giữa Rubric và bài làm — checklist tĩnh không hiểu semantic meaning | Sinh viên | Tiêu chí "Phân tích được ưu nhược điểm" cần hiểu ngữ cảnh, không phải keyword matching |
| 5 | AI có thể tốt hơn | Chuẩn bị slide thuyết trình từ tài liệu dài — cần chọn lọc ý và viết bullet point | Nhóm làm presentation | Mất 60-90 phút/bộ slide; AI có thể hỗ trợ tổng hợp ý |
| 6 | Pain từ người khác | Sinh viên bị trừ 0.5-1.5 điểm vì quên tiêu chí nhỏ trong Rubric dù nội dung chính đã có | Sinh viên | 2/3 người interview xác nhận từng bị trừ điểm vì thiếu mục phụ |
| 7 | Lặp lại | Lục Discord nhiều kênh để tìm deadline các môn học khác nhau | Sinh viên nhiều môn | 5-10 phút/ngày; deadline nằm rải rác không tập trung |
| 8 | Tốn thời gian | Tìm lại quyết định cũ trong Slack/Discord khi cần context | Cả team | 10-15 phút/lần tìm; search keyword không hiệu quả |
| 9 | Lặp lại + Tốn thời gian | Review PRD hoặc tài liệu kỹ thuật 10-15 trang trước khi comment | PM reviewer, Tech Lead | 45 phút/bản; cần hiểu context tổng thể |
| 10 | Pain từ người khác | Trợ giảng/mentor phải trả lời cùng một câu hỏi về cách nộp bài hoặc tiêu chí Rubric nhiều lần | Trợ giảng, mentor | Câu hỏi lặp lại 5-10 lần/kỳ; mất thời gian copy-paste |

### Ghi chú scan

- Problem #1, #4, #6 liên quan trực tiếp đến Rubric Audit — sản phẩm giúp sinh viên đối chiếu bài làm với Rubric trước khi nộp. Đây là candidate được nhóm chọn (xem `02-group-problem-statement/group-report.md`, Phase 3.4).
- Problem #2 (đọc paper) và #5 (chuẩn bị slide) là pain thật trong môi trường học tập.
- Problem #7 (Discord deadline) có data access phức tạp nhưng lặp lại thường xuyên.
- Data source: quick interview 3 sinh viên + mini poll 6 người trong lớp + trải nghiệm cá nhân.

### Phân tích độ đa dạng của scan (Bonus: scan rộng)

Bảng dưới chứng minh 10 problems trải đều qua **4 bối cảnh quan sát** và **4 lăng kính phân tích**:

| Bối cảnh | Số problem | Problem # | Độ cụ thể |
|---|---|---|---|
| Học tập (bài nộp, Rubric, paper, audio) | 6 | #1, #2, #4, #5, #6, #10 | Có actor cụ thể (sinh viên, trợ giảng), có dấu hiệu thật (số phút, số người poll) |
| Công việc / thực tập (report, review PRD) | 2 | #3, #9 | Có actor (PM, Tech Lead), có metric thời gian cụ thể |
| Nhóm / CLB / dự án (slide, phân công) | 1 | #5 (liên nhóm) | Overlap với học tập nhưng context khác (làm nhóm vs cá nhân) |
| Sản phẩm đang dùng (Discord, Slack, LMS) | 3 | #7, #8, #10 | Pain từ chính nền tảng sinh viên dùng hằng ngày |

**Phân bổ theo lăng kính:**

| Lăng kính | Số problem | Problem # |
|---|---|---|
| Lặp lại | 6 | #1, #2, #3, #7, #9, #10 |
| Tốn thời gian | 7 | #1, #2, #3, #5, #8, #9, #10 |
| AI có thể tốt hơn | 4 | #1, #4, #5, #7 |
| Pain từ người khác | 4 | #1, #6, #8, #10 |

> **Nhận xét:** 4/10 problems thuộc ≥2 lăng kính (ví dụ #1 vừa lặp lại vừa tốn thời gian) — đây là dấu hiệu problem có impact cao. 6/10 problems có dấu hiệu thật định lượng (số phút, số người, tần suất/tuần). Không có problem nào chỉ là "ý tưởng chung chung".

---

## Phase 2 — Top 3 Problem Cards

### Chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Kiểm tra Rubric bài nộp: đối chiếu bài làm với bộ tiêu chí trước khi nộp | Workflow rõ nhất; ai cũng trải qua; metric thời gian đo được; impact trực tiếp vào điểm số | AI có thể bịa tiêu chí không có trong Rubric nếu prompt không chuẩn |
| 2 | Đọc paper dài: tóm tắt ý chính từ bài báo nghiên cứu | Pain thật với sinh viên làm research; AI đọc hiểu văn bản là strength | Quality metric "tóm tắt đúng" khó thống nhất; cần expert đánh giá |
| 3 | Tổng hợp weekly report: PM viết báo cáo từ nhiều nguồn | Pattern kinh điển; workflow lặp lại; có thể áp dụng template worked example | Narrative "đủ tốt" khó đo bằng metric định lượng thuần túy |

---

## Problem Card #1 — Rubric Audit (Kiểm tra Rubric bài nộp)

```
┌──────────────────────────────────────────────┐
│ PROBLEM CARD #1                              │
│                                              │
│ Problem 1 câu: Sinh viên mất nhiều thời gian  │
│ cuộn qua lại giữa Rubric và bài làm để kiểm   │
│ tra xem đã viết đủ tiêu chí chưa, dễ bỏ sót   │
│ mục nhỏ và bị trừ điểm.                       │
│                                              │
│ Ai chịu ảnh hưởng? Sinh viên nộp bài tập      │
│ lớn / báo cáo môn học có Rubric chi tiết.     │
│                                              │
│ Workflow hiện tại:                           │
│ 1. Mở Rubric → 2. Đọc tiêu chí → 3. Cuộn bài │
│ làm đối chiếu → 4. Sửa mục thiếu → 5. Nộp    │
│                                              │
│ Bước nghẽn nhất: 3 — cuộn đối chiếu thủ công  │
│ (15 phút/bài, dễ bỏ sót tiêu chí phụ)        │
│                                              │
│ Đo thành công bằng gì? Giảm 45' → dưới 22';  │
│ 100% không bị trừ điểm do thiếu tiêu chí      │
│                                              │
│ Quick gut: □ No AI □ Rule ■ Workflow         │
│            □ Agent □ Chưa biết               │
└──────────────────────────────────────────────┘
```

**Problem 1 câu:**
Sinh viên mất nhiều thời gian cuộn qua lại giữa file Rubric và file bài làm để kiểm tra xem đã viết đủ từng tiêu chí chưa, dễ bỏ sót mục nhỏ và bị trừ điểm oan.

**Actor:**
Sinh viên nộp bài tập lớn hoặc báo cáo môn học có Rubric chi tiết (5-15 tiêu chí). Ví dụ: báo cáo AI in Action, bài tập lớn cuối kỳ, đồ án môn học.

**Thời điểm / bối cảnh:**
Trước deadline nộp bài 1-2 ngày. Áp lực thời gian cao, dễ bỏ sót tiêu chí nhỏ khi chỉ tập trung vào nội dung chính.

**Current workflow 5 bước:**
1. Mở Rubric và bài làm (5')
2. Đọc từng tiêu chí trong Rubric (10')
3. Cuộn bài làm đối chiếu thủ công với từng tiêu chí (15') ← **BOTTLENECK**
4. Chỉnh sửa và bổ sung mục còn thiếu (10')
5. Kiểm tra định dạng và nộp LMS (5')

**Bottleneck:**
Bước 3 — cuộn đối chiếu thủ công. Sinh viên phải tự ghi nhớ từng tiêu chí rồi cuộn tìm trong bài làm dài 5-15 trang xem đã đề cập đủ chưa. Checklist tĩnh không hiểu ngữ cảnh — tiêu chí "Phân tích được ưu nhược điểm" không thể kiểm tra bằng keyword matching đơn giản.

**Impact:**
- Thời gian: ~45 phút/bài tập lớn cho 1 sinh viên
- Tần suất: 2-4 bài tập lớn/học kỳ
- Hậu quả: bị trừ 0.5-1.5 điểm do thiếu tiêu chí phụ dù nội dung chính đã có; cảm giác "mất điểm oan"

**Success metric:**
- Tổng thời gian từ 45 phút xuống dưới 22 phút
- 100% không bị trừ điểm do thiếu tiêu chí Rubric sau khi dùng tool
- Audit Report phát hiện ≥90% tiêu chí thiếu thật (precision)

**Non-AI alternative:**
Checklist Excel/Docs template tĩnh: tự tick từng mục. GIẢI QUYẾT ĐƯỢC: kiểm tra format, số trang, font chữ. KHÔNG GIẢI QUYẾT ĐƯỢC: đối chiếu ngữ cảnh nội dung — "đã phân tích đủ sâu chưa?", "đã có ví dụ chưa?"

**AI hypothesis:**
AI (LLM) đọc Rubric và bài làm → phân tích ngữ cảnh từng tiêu chí → xuất Rubric Audit Report dạng bảng: Đạt / Chưa đạt / Gợi ý vị trí cần bổ sung. Sinh viên review report và tự tay bổ sung nội dung.

**Quick gut:**
[ ] No AI / process fix — checklist tĩnh không đủ
[ ] Rule — một phần: kiểm tra định dạng file
[x] **Workflow** — upload → AI audit → sinh viên review → nộp. Tuyến tính, rõ ràng
[ ] Agent — không cần tự lập kế hoạch hay gọi nhiều tool; không nên AI tự viết bài

### Draft current workflow (Card #1)

```text
CURRENT STATE — 5 bước, 45 phút

[1 Mở Rubric & Bài làm: 5']
→ [2 Đọc tiêu chí Rubric: 10']
→ [3 Cuộn bài làm đối chiếu thủ công: 15']  ← BOTTLENECK
→ [4 Chỉnh sửa & bổ sung mục thiếu: 10']
→ [5 Kiểm tra định dạng & Nộp LMS: 5']
```

### Draft future workflow (Card #1)

```text
FUTURE STATE — 5 bước, 22 phút

[1 Upload Rubric & Bài làm: 2']               — Rule/script
→ [2 AI phân tích & đối chiếu ngữ cảnh: 2']     — Workflow step
→ [3 AI xuất Rubric Audit Report: 1']           — Workflow step
→ [4 Sinh viên review & bổ sung ý thiếu: 15']  — Human boundary
→ [5 Sinh viên nộp LMS: 2']

Fallback: AI audit sai → sinh viên bỏ report và tự rà soát lại bằng checklist thủ công.
```

---

## Problem Card #2 — Đọc paper dài

```
┌──────────────────────────────────────────────┐
│ PROBLEM CARD #2                              │
│                                              │
│ Problem 1 câu: Sinh viên mất 45-60 phút để   │
│ đọc hiểu và tóm tắt ý chính từ một paper      │
│ nghiên cứu 10-15 trang trước deadline.        │
│                                              │
│ Ai chịu ảnh hưởng? Sinh viên làm research,   │
│ học viên cần đọc tài liệu kỹ thuật.          │
│                                              │
│ Workflow hiện tại:                           │
│ 1. Mở paper → 2. Đọc abstract → 3. Scan      │
│ toàn bài → 4. Đọc kỹ method/results → 5.     │
│ Ghi chú thủ công → 6. Viết tóm tắt           │
│                                              │
│ Bước nghẽn nhất: 4+5 — đọc kỹ và ghi chú     │
│ (25-30')                                     │
│                                              │
│ Đo thành công bằng gì? Giảm 60' → dưới 20';  │
│ tóm tắt không bỏ sót ý chính (expert review) │
│                                              │
│ Quick gut: □ No AI □ Rule ■ Workflow         │
│            □ Agent □ Chưa biết               │
└──────────────────────────────────────────────┘
```

**Problem 1 câu:**
Sinh viên mất 45-60 phút để đọc hiểu và tóm tắt ý chính từ một paper nghiên cứu 10-15 trang, đặc biệt khi deadline gần và cần đọc nhiều paper.

**Actor:**
Sinh viên làm research, học viên AI in Action cần đọc tài liệu kỹ thuật, hoặc bất kỳ ai cần literature review.

**Thời điểm / bối cảnh:**
Trước deadline assignment hoặc presentation; cần đọc 3-5 paper trong 1-2 ngày.

**Current workflow 6 bước:**
1. Mở paper (1')
2. Đọc abstract và conclusion (5')
3. Scan toàn bài để nắm cấu trúc (5')
4. Đọc kỹ method/results/discussion (25-30') ← **BOTTLENECK**
5. Ghi chú thủ công ý chính (10')
6. Viết tóm tắt hoặc slide (10')

**Bottleneck:**
Bước 4 — đọc kỹ phần method và results. Paper academic viết dày đặc, cần hiểu domain context. Dễ bỏ sót limitation hoặc key finding.

**Impact:**
45-60 phút/paper; đọc 5 paper = 4-5 giờ. Dễ bỏ sót ý quan trọng khi đọc nhanh.

**Success metric:**
Giảm 60 phút xuống dưới 20 phút/paper; tóm tắt không bỏ sót >2 key findings; expert review xác nhận.

**Non-AI alternative:**
Đọc abstract + conclusion + scan figures. GIẢI QUYẾT ĐƯỢC: nắm ý chính. KHÔNG GIẢI QUYẾT ĐƯỢC: hiểu sâu method và limitation.

**AI hypothesis:**
AI đọc toàn văn paper → tóm tắt theo cấu trúc: problem, method, key results, limitations. User đọc tóm tắt và có thể hỏi follow-up.

**Quick gut:**
[ ] No AI / process fix
[ ] Rule
[x] **Workflow** — AI tóm tắt → user đọc và verify
[ ] Agent

### Draft current workflow (Card #2)

```text
CURRENT STATE — 60 phút

[1 Mở paper: 1']
→ [2 Đọc abstract + conclusion: 5']
→ [3 Scan toàn bài: 5']
→ [4 Đọc kỹ method/results: 30']  ← BOTTLENECK
→ [5 Ghi chú thủ công: 10']
→ [6 Viết tóm tắt: 10']
```

### Draft future workflow (Card #2)

```text
FUTURE STATE — 18 phút

[1 Upload paper: 1']
→ [2 AI đọc & tóm tắt cấu trúc: 2']
→ [3 User đọc tóm tắt: 10']
→ [4 User hỏi follow-up nếu cần: 5']

Fallback: AI tóm tắt sai/bỏ sót → user tự đọc phần cần thiết.
```

---

## Problem Card #3 — Tổng hợp weekly report

```
┌──────────────────────────────────────────────┐
│ PROBLEM CARD #3                              │
│                                              │
│ Problem 1 câu: Mỗi thứ Hai PM mất ~90 phút   │
│ tổng hợp Weekly Report từ Jira, Sheets,      │
│ Slack; bước viết narrative tốn nhất.         │
│                                              │
│ Ai chịu ảnh hưởng? Junior PM chịu trách      │
│ nhiệm gửi report cho EM và CEO.              │
│                                              │
│ Workflow hiện tại:                           │
│ 1. Export Jira → 2. Lấy metrics Sheets → 3.  │
│ Đọc Slack recap → 4. Tổng hợp vào Docs → 5.  │
│ Viết narrative → 6. Review & format → 7. Gửi │
│                                              │
│ Bước nghẽn nhất: 5 — viết narrative (25')    │
│                                              │
│ Đo thành công bằng gì? Giảm 90' → dưới 30';  │
│ không tăng số câu hỏi sửa/hỏi lại từ CEO/EM  │
│                                              │
│ Quick gut: □ No AI □ Rule ■ Workflow         │
│            □ Agent □ Chưa biết               │
└──────────────────────────────────────────────┘
```

**Problem 1 câu:**
Mỗi thứ Hai PM mất ~90 phút tổng hợp Weekly Report từ Jira, Sheets, Slack; bước viết narrative từ raw data tốn nhất và dễ trễ deadline.

**Actor:**
Junior PM chịu trách nhiệm gửi weekly report cho Engineering Manager và CEO.

**Thời điểm / bối cảnh:**
Thứ Hai hằng tuần, trước buổi leadership sync.

**Current workflow 7 bước:**
1. Export Jira sprint data (10')
2. Lấy metrics từ Google Sheets (10')
3. Đọc Slack recap tuần (15')
4. Tổng hợp vào Google Docs (15')
5. Viết narrative: insight, highlight, risk, next action (25') ← **BOTTLENECK**
6. Self-review + format (10')
7. Gửi email (5')

**Bottleneck:**
Bước 5 — viết narrative. PM phải biến raw data thành insight, highlight, risk, next action.

**Impact:**
90 phút/tuần; report trễ → leadership thiếu context trước sync.

**Success metric:**
Giảm 90 phút xuống dưới 30 phút; không tăng số câu hỏi sửa/hỏi lại từ CEO/EM.

**Non-AI alternative:**
Template report + Jira dashboard + checklist. GIẢI QUYẾT ĐƯỢC: format và lấy số. KHÔNG GIẢI QUYẾT ĐƯỢC: narrative.

**AI hypothesis:**
AI cấu trúc dữ liệu + draft narrative. PM review/edit trước khi gửi.

**Quick gut:**
[ ] No AI / process fix
[ ] Rule — một phần: auto-pull data
[x] **Workflow**
[ ] Agent

### Draft current workflow (Card #3)

```text
CURRENT STATE — 90 phút

[1 Export Jira: 10']
→ [2 Lấy metrics từ Sheets: 10']
→ [3 Đọc Slack recap: 15']
→ [4 Tổng hợp vào Docs: 15']
→ [5 Viết narrative: 25']  ← BOTTLENECK
→ [6 Review + format: 10']
→ [7 Gửi email: 5']
```

### Draft future workflow (Card #3)

```text
FUTURE STATE — 21 phút

[1 Auto-pull Jira/Sheets: 2']
→ [2 AI cấu trúc input: 1']
→ [3 AI draft narrative: 1']
→ [4 PM review + edit: 15']  ← Human boundary
→ [5 PM gửi: 2']

Fallback: AI draft tệ → PM tự viết lại.
```

---

## Card tôi muốn pitch nhất

```text
Card #1: Rubric Audit (Kiểm tra Rubric bài nộp)
```

**Vì sao:**
- Workflow rõ nhất trong 3 cards — đơn giản, 5 bước, tuyến tính.
- Có baseline thời gian từ trải nghiệm cá nhân và quick validation (mini poll 6 người).
- Có thể validate nhanh với sinh viên khác trong lớp.
- Metric đo được (thời gian, số điểm bị trừ do thiếu tiêu chí).
- Có thể so sánh Rule/Workflow/Agent rõ ràng.
- Không quá rộng cho lab Day 02.
- Tất cả thành viên trong nhóm đều hiểu domain vì đều là sinh viên.

**Câu hỏi tôi muốn nhóm challenge:**
- Làm sao phân biệt giữa "AI phát hiện đúng tiêu chí thiếu" và "AI bịa tiêu chí không có trong Rubric"?
- Có nên giới hạn loại Rubric (chỉ Rubric dạng bảng, hoặc chỉ một số môn học) để tăng precision?
- Nếu sinh viên quá tin vào AI audit và bỏ qua việc tự review thì làm sao?
