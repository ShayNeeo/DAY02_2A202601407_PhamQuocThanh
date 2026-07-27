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

## Bonus: Tương tác tích cực (Discord + nhóm) — +3đ

### Nhật ký tương tác trên Discord và trong nhóm

| Thời điểm | Kênh / ngữ cảnh | Tôi đã làm gì? | Ảnh hưởng đến nhóm |
|---|---|---|---|
| Đầu Phase 1 | Discord #day02-labs Cohort 3 | Gửi bản scan 10 problems sớm nhất nhóm (trước deadline 15 phút) | Các bạn khác tham khảo format scan của tôi để làm bài |
| Giữa Phase 2 | Discord group chat | Đặt câu hỏi "Làm sao phân biệt AI đúng vs AI bịa tiêu chí?" | Nhóm thêm boundary rõ ràng vào Problem Statement |
| Phase 3 convergence | Discord voice call 15 phút | Đề xuất dùng score matrix để chọn candidate thay vì vote cảm tính | Nhóm áp dụng score matrix, chọn Rubric Audit với 34/35 |
| Phase 4 validation | Discord #day02-labs | Đăng mini poll "Bạn có từng cuộn bài làm đối chiếu Rubric thủ công không?" → 6 responses | Kết quả poll (4/6 YES) được dùng làm evidence trong group report |
| Phase 5 workflow | Discord group chat | Gửi draft Mermaid diagram cho before/after workflow | Nhóm dùng làm base để refine workflow cuối |
| Phase 6 decision | Discord group chat | Gửi bảng so sánh Rule/Workflow/Agent kèm rationale | Nhóm thống nhất chọn Workflow thay vì tranh luận dài |
| Sau Phase 7 | Discord #day02-labs | Chia sẻ bài học "Boundary quan trọng hơn tính năng" + link tới research về LMS | 2 bạn khác trong cohort comment "hữu ích" và hỏi thêm về cách research |
| Sau nộp bài | Discord group chat | Gửi bản final đầy đủ 3 files để cả nhóm copy vào repo cá nhân | Cả 4 thành viên nộp đúng hạn và đồng bộ nội dung |

> **Impact:** Chủ động gửi bài sớm, đặt câu hỏi challenge đúng trọng tâm, đề xuất công cụ (score matrix, Mermaid, poll), và chia sẻ bài học ra cộng đồng. Các bạn khác confirm rằng format scan và score matrix của tôi giúp nhóm làm nhanh hơn.

---

## Bonus: Kiểm chứng/research vượt yêu cầu — +4đ

### Research của tôi đã trực tiếp thay đổi kết quả nhóm

| Phát hiện từ research | Trước research | Sau research | Thay đổi artifact nào? |
|---|---|---|---|
| 6/6 LMS (Turnitin, Canvas, Gradescope, Blackboard, Teams, ChatGPT) đều có Rubric nhưng **không LMS nào cho sinh viên tự audit** | Nhóm còn do dự: "Có tool nào làm rồi không? Có đáng làm không?" | Nhóm tự tin GO vì đây là **gap thị trường thật**, không phải build lại cái đã có | Problem Statement v1: thêm dòng "KHÔNG CÓ tool nào cho SINH VIÊN tự audit trước khi nộp" vào rationale |
| ChatGPT có thể hallucinate tiêu chí không có trong Rubric nếu prompt không chuẩn | Nhóm định chọn Agent để "AI tự làm hết" | Nhóm chuyển sang **Workflow + human review mandatory** | Decision matrix: từ "Agent" → "Workflow"; thêm fallback checklist thủ công |
| Tất cả LMS dùng pattern "hiển thị checklist Rubric + minh chứng citations" | Chưa có idea UX | Thiết kế Audit Report dạng bảng: Đạt / Chưa đạt / Gợi ý vị trí (có citation từ bài làm) | Future workflow bước 3: "AI xuất Rubric Audit Report" được spec rõ format output |
| Mini poll 6 người: 4/6 từng cuộn đối chiếu thủ công | Baseline thời gian chỉ là estimate cá nhân | Có **data thật** để set baseline 45 phút và target 22 phút | Success metric: từ "ước lượng" thành "baseline 45 phút từ poll 6 người, target <22 phút" |

> **Impact định lượng:** Research 6 nguồn (yêu cầu tối thiểu 2-3) + mini poll 6 người. Kết quả research trực tiếp thay đổi 3 quyết định lớn: (1) từ do dự → GO, (2) từ Agent → Workflow, (3) từ UX mơ hồ → spec rõ format output. (Bonus +4đ)

- [x] [12đ cá nhân] Cá nhân có 10 problems và top 3 Problem Cards (Rubric Audit, Đọc paper, Weekly Report).
- [x] [12đ cá nhân] Tôi đã pitch rõ Card #1 Rubric Audit và challenge nhóm về data access Discord và quality metric paper summary.
- [x] Nhóm có nhật ký hội tụ từ 10 candidates về 1 bài (4 cluster, score matrix 34/27/28).
- [x] [15đ nhóm] Nhóm có workflow trước/sau (5 bước → 5 bước, cùng số bước nhưng effort shift).
- [x] [20đ nhóm] Nhóm có Problem Statement v0/v1 với metric (thời gian, điểm số) và boundary rõ.
- [x] [15đ nhóm] Nhóm có so sánh No AI / Rule / Workflow / Agent với rationale cho từng mức.
- [x] [10đ nhóm] Nhóm có Go / Not Yet / No-Go decision với 6 câu hỏi decision matrix.
- [x] [10đ cá nhân] Reflection cá nhân có nói rõ vai trò trong nhóm, cách dùng AI (bảng chi tiết 7 phase), điều học được và nếu làm lại sẽ đổi gì.
- [x] [6đ cá nhân] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp với AI.

### Bonus eligibility

- [x] **Scan rộng hơn yêu cầu (+3đ):** 10 problems cụ thể, đủ 4 lăng kính × 4 bối cảnh, mỗi problem có actor và dấu hiệu thật định lượng (xem phân tích chi tiết trong `01-individual-problem-scan/`).
- [x] **Tương tác tích cực (+3đ):** Gửi bài sớm nhất nhóm trên Discord #day02-labs; đăng mini poll thu thập 6 responses; đề xuất score matrix giúp nhóm chọn đúng candidate; chia sẻ bài học và research ra cộng đồng Discord (xem nhật ký Discord bên trên).
- [x] **Kiểm chứng/research vượt yêu cầu (+4đ):** Research 6 nguồn LMS + mini poll 6 người thay đổi 3 quyết định lớn của nhóm (GO, Agent→Workflow, UX format) — xem bảng research impact bên trên. Tổng: **+10đ bonus**.

---

## Bài học cá nhân

1. **Problem first, not AI first.** Tôi suýt chọn Weekly Report vì có worked example sẵn. Nhưng quan trọng hơn là nhóm có hiểu domain không, có thể validate được không. Rubric Audit thắng vì mọi người đều là sinh viên — ai cũng hiểu pain.

2. **Boundary quan trọng hơn tính năng.** Với Rubric Audit, boundary "AI không được viết bài thay sinh viên" quan trọng hơn bất kỳ tính năng nào. Nếu không có boundary này, sản phẩm trở thành công cụ gian lận. Boundary không phải là "giới hạn" — nó là "điều kiện để sản phẩm tồn tại hợp pháp và có đạo đức".

3. **Tool research giúp tránh build lại cái đã có.** Khi research Turnitin, Canvas, Gradescope, tôi nhận ra tất cả đều thiết kế cho GIẢNG VIÊN chấm bài. KHÔNG CÓ tool nào cho SINH VIÊN tự audit trước khi nộp. Đây chính là gap mà Rubric Audit lấp vào — không cạnh tranh với tool có sẵn, mà phục vụ một persona bị bỏ quên.

4. **Workflow không "thấp" hơn Agent.** Có lúc tôi bị áp lực phải chọn Agent vì "nghe AI hơn". Nhưng Workflow là lựa chọn đúng cho Rubric Audit: các bước tuyến tính, AI chỉ hỗ trợ một bước (semantic matching), human review là mandatory. Không phải bài toán nào cũng cần Agent.

5. **Validation dù nhỏ cũng quý.** Chỉ 3 interview + 6 poll, nhưng đủ để nhóm biết: (a) pain có thật, (b) cần thu hẹp vào bài tập lớn có Rubric chi tiết, (c) sinh viên sợ bị trừ điểm oan. Không cần sample lớn — cần đúng persona.
