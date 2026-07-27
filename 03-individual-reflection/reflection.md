# 03 — Individual Reflection

> Học viên: Phạm Quốc Thanh | Mã: 2A202601407 | Cohort: 3

---

## Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Scan 10 problems từ 4 lăng kính (lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác); dựa trên trải nghiệm sinh viên và quick interview | Nhóm có 10 candidates đa dạng; nổi bật là Rubric Audit, Đọc paper, Discord deadline |
| Pitch Problem Card | Pitch Card #1 Rubric Audit với full Problem Card + workflow trước/sau + metric thời gian | Bài vào shortlist và được nhóm chọn với điểm cao nhất (34/35) |
| Challenge bài của bạn khác | Hỏi về data access feasibility của Discord deadline; chất vấn quality metric của Đọc paper dài | Nhóm loại bớt scope quá rộng (Discord API) và metric khó đo (paper summary quality) |
| Gom trùng / cluster | Đề xuất 4 cluster: Kiểm tra & Chấm điểm, Đọc & Tổng hợp, Quản lý công việc, Hỗ trợ nhóm | Giúp nhóm thấy pattern chung; chọn đúng cluster để đào sâu |
| Chọn candidate problem | Phân tích score matrix; lập luận so sánh Rubric Audit vs Đọc paper vs Discord | Nhóm thống nhất chọn Rubric Audit (34 điểm) |
| Validation / research | Thực hiện quick interview 3 sinh viên + mini poll 6 người; research 4 nguồn (Turnitin, Canvas, Gradescope, ChatGPT prompt) | Xác nhận pain thật: 2/3 từng bị trừ điểm; 4/6 từng cuộn đối chiếu thủ công; thấy solution pattern: AI audit + human review |
| Workflow nhóm | Vẽ current/future workflow 5 bước → 5 bước; xác định bottleneck ở bước cuộn đối chiếu thủ công | Nhóm dùng làm workflow bản cuối |
| Problem Statement | Viết PS v0 → phản biện → PS v1 với thêm AI intervention point, risk, boundary | PS chặt hơn; metric có baseline thời gian và success rate |
| Rule / Workflow / Agent | Lập luận chọn Workflow (không Rule-only vì cần semantic matching; không Agent vì vi phạm liêm chính học thuật) | Nhóm thống nhất: Workflow |
| Decision | Viết decision matrix 6 câu hỏi; kết luận GO với scope nhỏ và fallback rõ | Quyết định cuối cùng: GO |

---

## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Hỏi ChatGPT gợi ý thêm problem theo lăng kính "lặp lại" và "AI có thể tốt hơn" trong môi trường học tập | Gợi ý thêm Rubric Audit và Đọc paper — đúng pain tôi từng gặp | Gợi ý vài ý quá chung chung như "AI tutor toàn năng" | Bỏ ý chung chung; giữ ý có workflow và actor cụ thể (sinh viên + Rubric) |
| Problem Card | Nhờ Claude phản biện Card #1 Rubric Audit theo prompt skeptical PM | Chỉ ra: metric "100% không bị trừ điểm" quá tuyệt đối; cần fallback khi AI sai; cần phân biệt precision vs recall của audit | AI gợi ý thêm tính năng "tự động chấm điểm" — vượt scope và vi phạm boundary | Giữ boundary: AI chỉ audit, không chấm điểm; sinh viên tự review |
| Workflow | Nhờ AI render Mermaid diagram từ mô tả text | Nhanh hơn vẽ tay; giúp hình dung before/after rõ ràng | AI gộp bước review và nộp thành một | Tách lại vì review là human boundary, nộp là action cuối |
| Research | Dùng internet search tìm Turnitin, Canvas, Gradescope, ChatGPT Rubric prompt patterns | Tìm được pattern: các tool hiện có đều thiết kế cho GIẢNG VIÊN, không cho SINH VIÊN tự audit | Một số tool claim "AI chấm điểm tự động" nhưng không rõ accuracy | Chỉ dùng thông tin từ trang chính thức; ghi rõ tool nào cho ai |
| Problem Statement | Nhờ Claude phản biện PS v0; chỉ ra field nào mơ hồ | Chỉ ra: "impact" chỉ nói thời gian, thiếu consequence về điểm số; "boundary" cần rõ hơn về academic integrity | Đề xuất chọn Agent vì "nghe thông minh hơn" | Giữ Workflow vì Agent tự viết bài là vi phạm liêm chính học thuật |
| Rule / Workflow / Agent | Hỏi Claude: "so sánh Rule vs Workflow vs Agent cho bài Rubric Audit" | Phân tích tốt: Rule đủ cho format check, Workflow cho semantic matching, Agent quá mức | Có xu hướng suggest Workflow + Agent hybrid | Tự phân tích: Workflow là đủ vì các bước tuyến tính, không cần Agent tự quyết định |
| Decision | Hỏi phản biện: "có cách non-AI nào giải quyết 80% không?" | Gợi ý: checklist Excel + peer review có thể giải ~30-40% | Đánh giá thấp giá trị của AI semantic matching | Giữ AI cho semantic matching (không thể thay bằng keyword), checklist cho format |

---

## Reflection câu hỏi mở

**Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Bài toán "quản lý deadline", "tóm tắt tài liệu", "phân công task nhóm" xuất hiện rất nhiều — đó là pattern phổ biến trong môi trường học tập. Nhưng tôi học được rằng không phải problem nào cũng phù hợp để chọn AI. Rubric Audit được chọn vì nó có workflow tuyến tính rõ ràng, metric đo được, và boundary rất rõ (AI không được viết bài thay sinh viên). Ngược lại, Discord deadline bị loại vì data access API phức tạp và scope quá rộng.

**Nhóm có lúc nào bị solution-first không?**

Có một chút. Ban đầu có bạn muốn chọn ngay "xây chatbot trả lời câu hỏi nộp bài" vì nghe hay. Nhưng sau khi làm score matrix và so sánh, nhóm nhận ra đó là solution đi tìm problem. Chúng tôi quay lại làm đúng quy trình: cluster → shortlist → score → chọn → validate → research → rồi mới chọn mức AI. Cuối cùng chọn Workflow, không phải Agent.

**Tôi có thay đổi ý kiến sau khi bị challenge không?**

Có. Tôi ban đầu nghĩ Card #3 (Weekly Report) là candidate mạnh vì có worked example. Nhưng sau khi bạn Thắng hỏi "bài này có mấy người trong nhóm từng làm PM?" và "metric narrative quality đo thế nào?", tôi nhận ra nhóm không đủ domain knowledge về PM work và quality metric cho narrative rất khó thống nhất. Từ đó tôi tập trung ủng hộ Rubric Audit vì mọi người đều là sinh viên và đều hiểu pain.

**Tôi đóng góp gì thật sự vào artifact cuối?**

Tôi là người dẫn dắt phần lớn quá trình: từ scan 10 problems, pitch Card #1, đề xuất cluster, research 4 nguồn (Turnitin, Canvas, Gradescope, ChatGPT), vẽ workflow, viết PS v0/v1, phân tích Rule/Workflow/Agent, và đưa ra decision matrix. Các bạn khác đóng góp validation (quick interview), score matrix, và challenge để làm chặt problem hơn.

**Điều khó nhất khi viết Problem Statement là gì?**

Khó nhất là chọn đúng boundary. Với Rubric Audit, ranh giới giữa "AI giúp kiểm tra" và "AI viết bài thay" rất mong manh. Nếu không có boundary rõ, sản phẩm có thể bị coi là công cụ gian lận học thuật. Chúng tôi chốt boundary: AI chỉ xuất báo cáo audit (Đạt/Chưa đạt/Gợi ý), sinh viên tự tay bổ sung nội dung, không AI tự động sửa bài.

**Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?**

Tôi sẽ challenge về validation sớm hơn và mạnh hơn. Chúng tôi chỉ hỏi 3 người (quick interview) và 6 người (mini poll) — sample còn nhỏ. Nếu làm lại, tôi sẽ cố gắng phỏng vấn thêm 2-3 giảng viên hoặc trợ giảng để hiểu góc nhìn từ phía người chấm: họ thường thấy sinh viên thiếu những tiêu chí nào nhất? Điều này sẽ giúp nhóm thiết kế AI audit chính xác hơn.

---

## Tự kiểm cuối bài

- [x] [12đ cá nhân] Cá nhân có 10 problems và top 3 Problem Cards (Rubric Audit, Đọc paper, Weekly Report).
- [x] [12đ cá nhân] Tôi đã pitch rõ Card #1 Rubric Audit và challenge nhóm về data access Discord và quality metric paper summary.
- [x] Nhóm có nhật ký hội tụ từ 10 candidates về 1 bài (4 cluster, score matrix 34/27/28).
- [x] [15đ nhóm] Nhóm có workflow trước/sau (5 bước → 5 bước, cùng số bước nhưng effort shift).
- [x] [20đ nhóm] Nhóm có Problem Statement v0/v1 với metric (thời gian, điểm số) và boundary rõ.
- [x] [15đ nhóm] Nhóm có so sánh No AI / Rule / Workflow / Agent với rationale cho từng mức.
- [x] [10đ nhóm] Nhóm có Go / Not Yet / No-Go decision với 6 câu hỏi decision matrix.
- [x] [10đ cá nhân] Reflection cá nhân có nói rõ vai trò trong nhóm, cách dùng AI (bảng chi tiết 7 phase), điều học được và nếu làm lại sẽ đổi gì.
- [x] [6đ cá nhân] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp với AI.

---

## Bài học cá nhân

1. **Problem first, not AI first.** Tôi suýt chọn Weekly Report vì có worked example sẵn. Nhưng quan trọng hơn là nhóm có hiểu domain không, có thể validate được không. Rubric Audit thắng vì mọi người đều là sinh viên — ai cũng hiểu pain.

2. **Boundary quan trọng hơn tính năng.** Với Rubric Audit, boundary "AI không được viết bài thay sinh viên" quan trọng hơn bất kỳ tính năng nào. Nếu không có boundary này, sản phẩm trở thành công cụ gian lận. Boundary không phải là "giới hạn" — nó là "điều kiện để sản phẩm tồn tại hợp pháp và có đạo đức".

3. **Tool research giúp tránh build lại cái đã có.** Khi research Turnitin, Canvas, Gradescope, tôi nhận ra tất cả đều thiết kế cho GIẢNG VIÊN chấm bài. KHÔNG CÓ tool nào cho SINH VIÊN tự audit trước khi nộp. Đây chính là gap mà Rubric Audit lấp vào — không cạnh tranh với tool có sẵn, mà phục vụ một persona bị bỏ quên.

4. **Workflow không "thấp" hơn Agent.** Có lúc tôi bị áp lực phải chọn Agent vì "nghe AI hơn". Nhưng Workflow là lựa chọn đúng cho Rubric Audit: các bước tuyến tính, AI chỉ hỗ trợ một bước (semantic matching), human review là mandatory. Không phải bài toán nào cũng cần Agent.

5. **Validation dù nhỏ cũng quý.** Chỉ 3 interview + 6 poll, nhưng đủ để nhóm biết: (a) pain có thật, (b) cần thu hẹp vào bài tập lớn có Rubric chi tiết, (c) sinh viên sợ bị trừ điểm oan. Không cần sample lớn — cần đúng persona.
