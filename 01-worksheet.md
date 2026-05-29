# Day 02 Lab — Worksheet

> File này là hướng dẫn chính cho toàn bộ lab 4 tiếng. Bộ gợi ý, hướng dẫn công cụ, prompt mẫu và checklist tự kiểm đã được đặt trực tiếp vào từng phase để bạn không phải nhảy qua nhiều file.

## Nguyên tắc

1. **Problem first, not AI first.** Đừng bắt đầu bằng chatbot/agent. Bắt đầu bằng actor, workflow, bottleneck, metric.
2. **Cá nhân scan rộng, nhóm hội tụ.** Mỗi người chuẩn bị nhiều candidate problems; nhóm chọn một candidate đáng đào sâu.
3. **Vẽ workflow trước khi chọn AI.** Nếu chưa thấy bước nào nghẽn, chưa được chọn Rule / Workflow / Agent.
4. **Không cần AI vẫn là kết luận tốt.** Điểm nằm ở chất lượng lập luận, không nằm ở độ "ngầu" của solution.
5. **AI hỗ trợ, không thay quyết định.** Dùng AI để hỏi ngược, phản biện, vẽ lại, research. Người học tự kiểm và tự chốt.
6. **Tự làm trước, AI sau.** Những phần thể hiện suy nghĩ cá nhân như pitch, challenge và reflection không được để AI viết thay.

## Repo nộp bài

Mỗi học viên nộp một repo cá nhân:

```text
Day02-MãHọcViên-HọVàTên/
├── README.md
├── 01-individual-problem-scan/
├── 02-group-problem-statement/
└── 03-individual-reflection/
```

File phụ như ảnh workflow, Mermaid, survey screenshot, research notes đặt cùng prefix:

```text
01-individual-problem-scan-workflow-card-1.png
02-group-problem-statement-workflow.pdf
02-group-problem-statement-research-notes.md
```

Lưu ý: `02-group-problem-statement/` là **bản nộp nhóm**. Nhóm 3-4 người làm chung một bản cuối, sau đó mỗi học viên copy bản này vào repo cá nhân của mình.

## Output cuối cùng

| Phần | Ai làm | Cần có gì |
|---|---|---|
| `01-individual-problem-scan/` | Cá nhân | 5+ problems, top 3 Problem Cards, draft workflow trước/sau cho top 3 |
| `02-group-problem-statement/` | Nhóm | Nhật ký hội tụ, kiểm chứng nhanh, research giải pháp, workflow trước/sau, Problem Statement v0/v1, Rule / Workflow / Agent, quyết định cuối |
| `03-individual-reflection/` | Cá nhân | Vai trò trong nhóm, cách dùng AI, học được gì, nếu làm lại sẽ đổi gì |

## Tiêu chí đánh giá nhanh

Chi tiết rubric nằm trong `README.md`. Bảng dưới đây giúp bạn biết phần nào đang ảnh hưởng tới điểm khi làm worksheet.

| Nhóm / cá nhân | Thành phần | Điểm |
|---|---|---:|
| Nhóm | Workflow trước/sau | 15 |
| Nhóm | Problem Statement + metric + boundary | 20 |
| Nhóm | Độ phù hợp với AI + phương án thay thế | 15 |
| Nhóm | Chất lượng quyết định Go / Not Yet / No-Go | 10 |
| Cá nhân | Scan problem + top 3 Problem Cards | 12 |
| Cá nhân | Tham gia pitch + challenge | 12 |
| Cá nhân | Reflection cá nhân | 10 |
| Cá nhân | Kiểm tra hiểu bài cá nhân | 6 |

Bonus tối đa +10 điểm:

- +3 nếu scan rộng hơn yêu cầu và vẫn cụ thể.
- +3 nếu tương tác tích cực trên Discord hoặc trong nhóm.
- +4 nếu kiểm chứng/research vượt yêu cầu và giúp nhóm sửa lại problem, metric hoặc quyết định cuối.

## Quy ước dùng AI trong lab

| Phần | Có thể dùng AI không? | Cách dùng đúng |
|---|---|---|
| Scan cá nhân | Có, sau khi tự scan trước | Hỏi thêm góc nhìn, rồi tự chọn ý nào là pain thật. |
| Problem Card | Có | Dùng AI để phản biện, không để AI tự bịa problem thay mình. |
| Pitch + challenge | Không dùng để nói/thay mình | Trình bày và phản biện bằng hiểu biết của bản thân. |
| Research | Có | Dùng AI/search để tìm nguồn, nhưng phải kiểm link và ghi rõ giả định chưa chắc. |
| Workflow | Có | Có thể dùng AI/Mermaid để vẽ lại flow, nhưng phải tự kiểm từng bước. |
| Reflection | Không dùng để viết thay | Có thể dùng AI để gợi ý câu hỏi tự soi, nhưng câu trả lời phải là trải nghiệm thật của mình. |

## Gợi ý công cụ nhanh

| Phase | Tool có thể dùng | Dùng để làm gì | Lưu ý |
|---|---|---|---|
| Phase 1 | ChatGPT / Claude / Gemini, Google, review app/forum | Gợi ý thêm problem nếu bí | Tự scan trước; bỏ ý không có trải nghiệm thật. |
| Phase 2 | ChatGPT / Claude | Phản biện Problem Card | Prompt rõ: "chỉ ra điểm yếu, đừng khen". |
| Phase 4 | Google, Perplexity, tài liệu chính thức, survey/interview nhanh | Kiểm chứng pain, tìm giải pháp đã có | Không dùng số liệu nếu không kiểm được nguồn. |
| Phase 5 | Giấy/bảng, Mermaid, Excalidraw, FigJam | Vẽ workflow trước/sau | Vẽ tay cho rõ tư duy trước, số hóa sau nếu cần nộp đẹp hơn. |
| Phase 6 | ChatGPT / Claude | Hỏi phản biện Rule / Workflow / Agent | Không để AI chốt thay. Nhóm phải tự quyết định. |
| Phase 7 | Không bắt buộc | Chỉ dùng để gợi ý câu hỏi tự soi | Không copy reflection do AI viết. |

---

# Phase 0 — Worked Example (15')

Mở `02-deliverable-example.md` để xem một bài hoàn chỉnh. Khi đọc, chú ý:

- cá nhân scan rộng như thế nào,
- top 3 Problem Cards cụ thể ra sao,
- nhóm hội tụ từ nhiều candidates về một bài như thế nào,
- research giải pháp giúp nhóm tránh nghĩ trong chân không ra sao,
- workflow trước/sau thể hiện bottleneck, boundary và phương án quay về nếu AI sai như thế nào,
- Problem Statement v0/v1 khác nhau ở đâu.

Self-check:

- [ ] Tôi hiểu nhóm chỉ chọn **candidate problem**, không chọn ngay Problem Statement.
- [ ] Tôi hiểu deep-dive gồm validation, research, workflow, metric, PS và AI decision.

---

# Phase 1 — Individual Scan: tìm 5+ problems (25')

## Mục tiêu

Mỗi người scan rộng ít nhất 5 problems từ trải nghiệm thật. Đây là phần phân kỳ cá nhân.

Bonus:

- 8+ problems: bonus nếu vẫn cụ thể.
- 10+ problems: bonus tốt nếu đa dạng lăng kính và có dấu hiệu thật.
- Không bonus cho list dài nhưng toàn ý chung chung.

## 4 lăng kính để scan

Một problem có thể rơi vào nhiều lăng kính. Không cần phân loại hoàn hảo ở bước này. Dùng lăng kính để mở rộng quan sát, rồi bước sau mới filter.

| Lăng kính | Câu hỏi gợi mở | Ví dụ |
|---|---|---|
| **Lặp lại** | Việc gì cứ xuất hiện đều đặn mỗi ngày/tuần/tháng?<br>Nếu phải làm thêm 10 lần nữa, phần nào tôi muốn chuẩn hóa hoặc tự động hóa?<br>Người mới vào có phải hỏi lại cùng một quy trình không? | Báo cáo tuần, nhập liệu, tổng hợp câu hỏi |
| **Tốn thời gian** | Việc gì mỗi lần làm đều nặng, dù không nhất thiết xảy ra thường xuyên?<br>Thời gian mất ở đâu: tìm thông tin, đọc hiểu, tổng hợp, chờ người khác, format, hay sửa lại?<br>Nếu giảm 50% thời gian thì có đáng kể không? | Đọc tài liệu dài, tìm quyết định cũ, review PRD |
| **AI có thể tốt hơn** | Việc gì cần hiểu ngữ cảnh, đọc/viết ngôn ngữ, phân loại, so sánh, tổng hợp hoặc gợi ý đúng lúc?<br>Nếu AI chỉ hỗ trợ một bước trong workflow, bước nào đáng hỗ trợ nhất?<br>Nếu AI sai ở bước đó thì hậu quả là gì? | Search tài liệu, gợi ý next step, tóm tắt nhiều nguồn |
| **Pain từ người khác** | Ai ngoài tôi đang bị kẹt hoặc phàn nàn lặp lại?<br>Họ thường nói câu gì, hỏi lại điều gì, hoặc bỏ sót bước nào?<br>Có dấu hiệu thật không: ticket, Slack/Discord, comment, survey, phản hồi trực tiếp? | Hỏi lại deadline, không hiểu task, support ticket lặp lại |

Cách phân biệt nhanh:

- `Lặp lại` bắt đầu từ câu hỏi: việc này xảy ra bao nhiêu lần?
- `Tốn thời gian` bắt đầu từ câu hỏi: mỗi lần làm tốn bao nhiêu công?
- Một problem vừa lặp lại vừa tốn thời gian thì càng đáng đưa vào danh sách scan.

Nếu bí, tự hỏi:

- Tuần trước tôi mất nhiều thời gian nhất vào việc gì?
- Việc gì tôi hay trì hoãn vì nhàm chán hoặc rối?
- Người khác hay hỏi tôi câu gì lặp lại?
- Có workflow nào ở trường/công ty ai cũng biết là chậm?
- Có app nào tôi dùng và thường nghĩ "giá như nó hiểu mình hơn"?

Một số điểm bắt đầu dễ quan sát:

| Bối cảnh | Có thể nhìn vào đâu? | Câu hỏi gợi mở |
|---|---|---|
| Học tập | Bài tập, tài liệu, deadline, câu hỏi lặp lại trong lớp | Phần nào làm tôi mất thời gian vì phải đọc, tổng hợp, hỏi lại hoặc đoán ý? |
| Công việc / thực tập | Báo cáo, họp, handoff, ticket, review, nhập liệu | Việc nào lặp lại đủ nhiều nhưng vẫn cần hiểu ngữ cảnh trước khi xử lý? |
| Nhóm / CLB / dự án | Phân công, theo dõi tiến độ, feedback, tổng hợp quyết định | Chỗ nào mọi người hay hiểu khác nhau hoặc bỏ sót việc cần làm? |
| Sản phẩm đang dùng | Search, onboarding, support, form, notification | Điểm nào user phải tự nối nhiều thông tin rời rạc để hoàn thành việc? |

## Ngân hàng gợi ý problem

Nếu vẫn bí ý tưởng, đọc nhanh các gợi ý dưới đây rồi quay lại trải nghiệm thật của bạn. Không copy nguyên văn; hãy viết lại theo người dùng, workflow và dấu hiệu thật mà bạn quan sát được.

| Bối cảnh | Gợi ý problem để suy nghĩ |
|---|---|
| Học tập | Tìm lại quyết định/câu trả lời cũ trong Discord; đọc tài liệu dài trước deadline; không biết bài nộp thiếu field nào; ôn tập từ nhiều nguồn rời rạc. |
| Đời sống cá nhân | Theo dõi chi tiêu rải rác nhiều app; lên kế hoạch đi lại/ăn uống cho nhóm; tổng hợp giấy tờ cá nhân; nhắc việc định kỳ nhưng hay quên context. |
| Thực tập / công việc mới | Hỏi lại quy trình onboarding; tìm người phụ trách đúng việc; viết update hằng tuần; hiểu task từ nhiều Slack/thread/tài liệu. |
| Người đi làm | Tổng hợp báo cáo tuần; chuẩn bị meeting recap; review tài liệu dài; phân loại ticket/support; tìm quyết định cũ trước khi làm tiếp. |
| Cải thiện sản phẩm đang dùng | Search kém; onboarding khó hiểu; notification không đúng lúc; form dài và dễ nhập sai; support phải hỏi lại cùng một thông tin nhiều lần. |

## Bảng scan

| # | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Tốn thời gian | Reproduce kết quả paper không có code sẵn | Researcher | Vài tuần - 1 tháng/paper; tốn nhiều công sức phân tích toán học và thuật toán. |
| 2 | Tốn thời gian | Literature review tìm hướng phát triển mới (gap) | Researcher | 2-3 tuần/topic; phải đọc và đối chiếu chéo hàng chục paper. |
| 3 | Tốn thời gian + Lặp lại | Viết báo cáo và làm slide cho một project môn học | Sinh viên | 1 tuần/project; lặp lại mỗi cuối kỳ cho tất cả các môn học. |
| 4 | Lặp lại | Định dạng danh mục tài liệu tham khảo (citations) đúng chuẩn (APA, IEEE, Harvard) | Sinh viên, Researcher | 2-3 tiếng/báo cáo; kiểm tra từng dấu chấm, dấu phẩy thủ công. |
| 5 | Tốn thời gian | Đọc hiểu và tóm tắt các tài liệu kỹ thuật dài (documentation, API, papers mới) để áp dụng vào bài làm | Sinh viên CNTT / Kỹ thuật | 3-4 tiếng/tài liệu; tài liệu quá dài và khó tìm đúng đoạn thông tin cần thiết. |
| 6 | Pain từ người khác | Nhắc nhở thành viên nhóm nộp bài đúng hạn và tổng hợp nội dung đóng góp | Trưởng nhóm (Sinh viên) | Phải nhắn tin giục 3-4 lần/tuần trên Messenger, mất thời gian copy-paste từ nhiều file. |
| 7 | AI có thể tốt hơn | Tóm tắt các quyết định và phân công công việc sau buổi họp nhóm môn học | Nhóm sinh viên | 20-30 phút/buổi họp; họp xong trôi tin nhắn trên Zalo dẫn đến việc quên task. |
| 8 | Lặp lại | Viết email học thuật gửi giáo sư để hỏi bài hoặc xin phản hồi nghiên cứu | Sinh viên, Researcher | 1-2 tiếng/email; mất nhiều thời gian trau chuốt từ ngữ trang trọng, lịch sự. |
| 9 | Tốn thời gian | Dịch thuật ngữ chuyên ngành trong tài liệu khoa học nước ngoài | Sinh viên, Researcher | Dịch tự động (Google) bị sai ngữ cảnh kỹ thuật, phải tra lại thủ công mất 1-2 tiếng. |
| 10 | AI có thể tốt hơn | Lên đề cương chi tiết (outline) cho bài báo cáo dựa trên rubric đánh giá của giảng viên | Sinh viên | 3-4 tiếng/đề cương; khó cấu trúc nội dung đúng hướng để đạt điểm tối đa theo rubric. |

Gợi ý cho `Dấu hiệu thật`: mất bao lâu, xảy ra mấy lần/tuần, bao nhiêu người gặp, có log/ticket/review/comment không, nếu không sửa thì hậu quả là gì.

## Nếu dùng AI ở phase này

Tự scan trước rồi mới hỏi AI.

Prompt gợi ý:

```text
Tôi là [vai trò] trong [bối cảnh].
Công việc hằng tuần gồm: [...]

Tôi đã nghĩ ra các vấn đề sau:
1. [...]
2. [...]
3. [...]

Hãy gợi ý thêm problem theo 4 lăng kính: lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác.
Với mỗi gợi ý, ghi actor, workflow sơ bộ và cách đo.
Đừng đưa ý tưởng quá rộng kiểu "xây trợ lý AI toàn năng".
```

Ghi vào reflection: AI gợi ý gì dùng được, ý nào bị bỏ vì không phải pain thật.

---

# Phase 2 — Top 3 Problem Cards + draft workflow (35')

## Mục tiêu

Từ 5+ problems, mỗi người chọn top 3 để chuẩn bị share với nhóm. Mỗi top problem cần có:

- Problem Card.
- Draft current workflow.
- Draft future workflow.
- Lý do vì sao bài này có impact.

## Chọn top 3

Tiêu chí chọn:

- Actor rõ.
- Workflow hiện tại có thể vẽ được.
- Bottleneck cụ thể.
- Impact có thể đo hoặc ước lượng.
- Có thể so sánh No AI / Rule / Workflow / Agent.
- Không quá rộng cho một buổi lab.

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Viết báo cáo và làm slide cho một project môn học | Tần suất lặp lại cao (cuối kỳ môn nào cũng có), workflow rõ ràng từ đề cương -> nội dung -> slide, tốn nhiều thời gian của sinh viên. | Làm sao để slide thiết kế chuyên nghiệp và nội dung báo cáo chính xác, không bị AI "hallucinate" kiến thức chuyên môn. |
| 2 | Literature review tìm hướng phát triển mới (gap) | Impact rất lớn đối với researcher, giúp tiết kiệm hàng tuần đọc tài liệu. | Độ tin cậy của AI khi đọc hiểu các nghiên cứu sâu, rủi ro bỏ sót paper quan trọng hoặc hiểu sai kết quả. |
| 3 | Reproduce kết quả paper không có code sẵn | Pain point cực kỳ lớn trong giới nghiên cứu AI/Khoa học máy tính. | Tính khả thi rất thấp vì đòi hỏi suy luận toán học/thuật toán cực kỳ phức tạp để tự viết lại code từ mô tả của bài báo. |

## Problem Card template

Lặp lại template này cho top 3.

Nếu cần một bản nhìn nhanh để pitch với nhóm, dùng dạng card này:

```text
┌──────────────────────────────────────────────┐
│ PROBLEM CARD #___                            │
│                                              │
│ Problem 1 câu: ___________________________   │
│                                              │
│ Ai đang đau? _____________________________   │
│                                              │
│ Workflow hiện tại:                           │
│ 1. ______ → 2. ______ → 3. ______ → 4. ___   │
│                                              │
│ Bước nghẽn nhất: ________  (___ phút/lần)    │
│                                              │
│ Đo thành công bằng gì? ___________________   │
│ Ví dụ: giảm 90 phút → dưới 30 phút           │
│                                              │
│ Quick gut: □ No AI □ Rule □ Workflow         │
│            □ Agent □ Chưa biết               │
└──────────────────────────────────────────────┘
```

Phần nộp chi tiết của Top 3 Problem Cards:

### PROBLEM CARD #1 — Viết báo cáo và làm slide cho project môn học

**Problem 1 câu:**
Sinh viên mất trung bình 10-15 tiếng vào tuần cuối kỳ để tổng hợp kết quả dự án, soạn thảo báo cáo chi tiết và thiết kế slide thuyết trình, dẫn đến quá tải và chất lượng slide không đẹp mắt.

**Actor:**
Sinh viên đại học/cao đẳng (đặc biệt là sinh viên các ngành kỹ thuật hoặc kinh tế thường xuyên có dự án nhóm).

**Thời điểm / bối cảnh:**
Tuần cuối kỳ học, chuẩn bị nộp bài và thuyết trình trước giảng viên.

**Current workflow 3-7 bước:**
1. Thu thập kết quả thực hiện dự án (code, số liệu, biểu đồ, khảo sát) từ các thành viên nhóm.
2. Viết nội dung báo cáo chi tiết (Word/Docs) theo cấu trúc yêu cầu của giảng viên.
3. Rút gọn nội dung báo cáo thành các gạch đầu dòng (bullet points) chính cho slide.
4. Thiết kế slide (PowerPoint/Canva) - lựa chọn template, sắp xếp bố cục, chèn hình ảnh.
5. Viết kịch bản thuyết trình (script) tương ứng với từng slide.
6. Review, căn chỉnh format báo cáo và slide lần cuối.

**Bottleneck:**
Bước 2 (Viết báo cáo từ số liệu thô - mất ~300 phút) và Bước 4 (Thiết kế slide & sắp xếp bố cục - mất ~180 phút).

**Impact:**
Mỗi học kỳ sinh viên học 4-5 môn, hầu hết đều có project nhóm. Mất khoảng 40-50 tiếng/kỳ chỉ cho việc làm báo cáo/slide. Quá tải cuối kỳ làm giảm chất lượng nội dung chuyên môn của dự án.

**Success metric:**
Giảm tổng thời gian từ 15 tiếng xuống dưới 4 tiếng mỗi dự án. Slide được thiết kế đúng chuẩn trực quan, nội dung báo cáo bám sát kết quả dự án và rubric của giảng viên.

**Non-AI alternative:**
Sử dụng template Word/Canva sẵn có. Giúp giảm thời gian format nhưng sinh viên vẫn phải tự tóm tắt, viết báo cáo từ đầu và tự điền nội dung vào slide thủ công.

**AI hypothesis:**
AI hỗ trợ chuyển đổi từ kết quả dự án thô (raw notes, code, số liệu) thành draft báo cáo có cấu trúc, đồng thời tự động tóm tắt thành bullet points và sinh code slide (Markdown/Marp) để import trực tiếp thành slide hoàn chỉnh.

**Quick gut:**
[x] Workflow

---

### PROBLEM CARD #2 — Literature review tìm hướng phát triển mới (gap)

**Problem 1 câu:**
Researcher mất 2-3 tuần đọc hàng chục paper chuyên ngành dài để tìm ra các điểm trống (gap) nghiên cứu mới, dễ bị quá tải thông tin và bỏ sót các tài liệu quan trọng.

**Actor:**
Researcher, nghiên cứu sinh, học viên cao học.

**Thời điểm / bối cảnh:**
Giai đoạn đầu của một đề tài nghiên cứu mới hoặc khi viết chương Literature Review.

**Current workflow 3-7 bước:**
1. Search các paper liên quan theo từ khóa trên Google Scholar/Scopus.
2. Đọc lướt abstract và kết luận để lọc ra các paper chất lượng nhất.
3. Đọc chi tiết phương pháp, kết quả và hạn chế (limitations/future work) của từng paper.
4. Ghi chú và phân loại các hướng nghiên cứu hiện tại vào bảng tổng hợp.
5. Đối chiếu các kết quả và tìm ra điểm trống chưa được giải quyết (gap).
6. Viết bản tóm tắt Literature Review.

**Bottleneck:**
Bước 3 (Đọc chi tiết và hiểu sâu nội dung chuyên ngành - mất 4-5 tiếng/paper) và Bước 5 (Đối chiếu chéo nhiều paper để tìm gap).

**Impact:**
Mất hàng tuần cho một chủ đề nghiên cứu, làm chậm tiến độ khởi động dự án. Có thể chọn sai hướng nghiên cứu nếu bỏ sót các công trình đã công bố.

**Success metric:**
Giảm thời gian làm literature review từ 2-3 tuần xuống còn dưới 5 ngày, phát hiện được ít nhất 2-3 gaps khả thi có dẫn chứng đầy đủ.

**Non-AI alternative:**
Sử dụng các công cụ quản lý thư viện (Zotero, Mendeley) để sắp xếp và đọc tài liệu. Giúp quản lý file tốt hơn nhưng không hỗ trợ đọc hiểu nhanh hay phân tích tìm gap.

**AI hypothesis:**
Sử dụng AI Agent có thể truy cập cơ sở dữ liệu học thuật, tự động đọc và lập bảng đối chiếu phương pháp/kết quả của các paper, sau đó gợi ý các điểm trống nghiên cứu dựa trên so sánh logic.

**Quick gut:**
[x] Agent

---

### PROBLEM CARD #3 — Reproduce kết quả paper không có code sẵn

**Problem 1 câu:**
Researcher mất vài tuần đến hàng tháng để tự lập trình lại thuật toán từ mô tả toán học/phương pháp trong paper do tác giả không cung cấp mã nguồn, gây lãng phí thời gian nghiên cứu.

**Actor:**
Researcher, kỹ sư AI/ML.

**Thời điểm / bối cảnh:**
Khi cần so sánh (benchmark) thuật toán của mình với các thuật toán state-of-the-art trước đó.

**Current workflow 3-7 bước:**
1. Đọc kỹ phần Phương pháp (Methodology) và các công thức toán học trong paper.
2. Phân tích kiến trúc hệ thống và luồng dữ liệu được mô tả.
3. Thiết kế cấu trúc code và lập trình các lớp/hàm chính bằng Python/C++.
4. Cài đặt các tham số tối ưu và chuẩn bị tập dữ liệu thử nghiệm.
5. Chạy thử nghiệm và so sánh kết quả với kết quả công bố trong paper.
6. Debug và tinh chỉnh mã nguồn nếu kết quả không khớp.

**Bottleneck:**
Bước 3 (Chuyển đổi công thức toán học thành code - mất nhiều ngày) và Bước 6 (Debug tìm nguyên nhân lệch kết quả mà không có mã nguồn gốc để đối chiếu).

**Impact:**
Tốn hàng tháng trời cho một paper, thậm chí phải bỏ cuộc giữa chừng nếu bài toán quá phức tạp hoặc paper thiếu thông tin siêu tham số.

**Success metric:**
Giảm thời gian tái hiện kết quả từ 4 tuần xuống dưới 1 tuần, kết quả chạy lại sai lệch không quá 5% so với paper gốc.

**Non-AI alternative:**
Liên hệ trực tiếp với tác giả xin code, hoặc tìm kiếm các bản reproduce không chính thức của cộng đồng trên GitHub. Tuy nhiên tỷ lệ nhận được phản hồi thấp và code cộng đồng có thể sai sót.

**AI hypothesis:**
AI có khả năng phân tích công thức toán học (LaTeX) và mô tả thuật toán bằng ngôn ngữ tự nhiên để sinh cấu trúc code khung, đồng thời gợi ý các kịch bản test và debug khi kết quả chạy thử bị lệch.

**Quick gut:**
[x] Agent

---

## Draft workflow cho mỗi top problem

### Workflow cho Problem Card #1 (Viết báo cáo và làm slide)

```text
CURRENT STATE — 15 tiếng (900 phút)

[1 Gom kết quả thô: 120']
→ [2 Viết báo cáo chi tiết: 300']   <-- bottleneck 1
→ [3 Rút gọn ý chính làm slide: 120']
→ [4 Thiết kế slide & bố cục: 180'] <-- bottleneck 2
→ [5 Viết script thuyết trình: 90']
→ [6 Căn chỉnh format & review: 90']

FUTURE STATE — 3 tiếng 45 phút (225 phút)

[1 Gom kết quả thô & rubric: 30']
→ [2 AI cấu trúc báo cáo & draft nội dung: 20']  -- AI Workflow
→ [3 Sinh viên review + chỉnh sửa báo cáo: 90']  <-- Human boundary (kiểm soát nội dung)
→ [4 AI tóm tắt ý chính & sinh code slide (Marp/PPTX): 15'] -- AI Workflow
→ [5 Sinh viên import slide & tinh chỉnh visual/review: 60'] <-- Human boundary (thẩm mỹ + trình bày)
→ [6 AI draft script thuyết trình từ slide cuối: 10']

Fallback:
- Nếu AI draft nội dung báo cáo bị sai lệch chuyên môn -> Sinh viên dùng cấu trúc đề xuất nhưng tự viết lại các phần nội dung chuyên sâu.
- Nếu slide sinh ra xấu -> Sinh viên dùng template Canva có sẵn và copy-paste nội dung đã được AI tóm tắt ở bước 4.
```

### Workflow cho Problem Card #2 (Literature Review)

```text
CURRENT STATE — 2-3 tuần

[1 Search keyword trên Scholar: 2 ngày]
→ [2 Lọc paper qua abstract: 1 ngày]
→ [3 Đọc chi tiết từng paper: 5 ngày] <-- bottleneck 1
→ [4 Ghi chú & lập bảng so sánh: 3 ngày]
→ [5 Tìm gap & hướng phát triển: 3 ngày] <-- bottleneck 2
→ [6 Viết tóm tắt Lit Review: 2 ngày]

FUTURE STATE — 4 ngày

[1 AI Agent tự động search + tải các paper liên quan: 2 tiếng]
→ [2 AI phân tích, trích xuất dữ liệu chính & lập bảng so sánh: 4 tiếng]
→ [3 Researcher duyệt bảng, chọn các paper cần đọc sâu: 1 ngày] <-- Human boundary
→ [4 AI gợi ý các gap nghiên cứu dựa trên so sánh logic: 2 tiếng]
→ [5 Researcher đánh giá tính khả thi và chốt hướng nghiên cứu: 1.5 ngày] <-- Human boundary
→ [6 AI draft nháp chương Literature Review từ bảng dữ liệu: 4 tiếng]
→ [7 Researcher review & sửa bài: 1 ngày]

Fallback:
- Nếu AI Agent trích xuất sai thông tin paper -> Researcher phải tự kiểm tra lại các nguồn trích dẫn trực tiếp.
- Nếu AI gợi ý các gap nghiên cứu không khả thi hoặc ngớ ngẩn -> Researcher quay lại cách truyền thống, tự suy luận từ bảng so sánh đã có.
```

### Workflow cho Problem Card #3 (Reproduce Paper)

```text
CURRENT STATE — 4 tuần

[1 Đọc hiểu methodology & toán: 3 ngày]
→ [2 Thiết kế cấu trúc code: 2 ngày]
→ [3 Lập trình các hàm toán & model: 7 ngày] <-- bottleneck 1
→ [4 Chuẩn bị data & config: 3 ngày]
→ [5 Chạy thử nghiệm & so số liệu: 5 ngày]
→ [6 Debug lỗi lệch kết quả: 8 ngày] <-- bottleneck 2

FUTURE STATE — 6 ngày

[1 AI phân tích phần methodology & trích xuất công thức toán sang code khung: 1 ngày]
→ [2 Developer review, sửa đổi cấu trúc code khung cho đúng ý: 1 ngày] <-- Human boundary
→ [3 AI hỗ trợ code chi tiết các module & sinh unit tests: 1 ngày]
→ [4 Developer setup môi trường & chạy thử nghiệm: 1 ngày]
→ [5 AI phân tích log lỗi, so sánh biểu đồ kết quả & gợi ý hướng debug: 4 tiếng]
→ [6 Developer sửa lỗi & hoàn thành reproduce: 1.5 ngày] <-- Human boundary

Fallback:
- Nếu code do AI sinh ra bị lỗi syntax hoặc logic nghiêm trọng -> Developer quay lại tự lập trình thủ công dựa trên cấu trúc khung đã kiểm chứng.
```

## Chọn card muốn pitch nhất

Card tôi muốn pitch nhất:

```text
PROBLEM CARD #1 — Viết báo cáo và làm slide cho project môn học
```

Vì sao:

```text
Bài toán này cực kỳ thực tế với sinh viên, tần suất lặp lại rất cao (mỗi kỳ học 4-5 lần). Workflow rõ ràng, dễ đo lường bằng thời gian thực hiện, và rủi ro kiểm soát được vì sinh viên luôn là người duyệt nội dung cuối cùng trước khi nộp.
```

Câu hỏi tôi muốn nhóm challenge:

```text
Làm thế nào để AI có thể sinh slide trực quan, bố cục đẹp mắt mà không đòi hỏi tích hợp kỹ thuật quá phức tạp? Liệu có nên dùng các định dạng trung gian như Marp (Markdown-to-Slides) hay Python-pptx để sinh slide không?
```

## Nếu dùng AI ở phase này

Prompt phản biện:

```text
Đây là Problem Card của tôi:
[dán card]

Hãy đóng vai skeptical product manager và phản biện:
1. Actor có đủ cụ thể không?
2. Workflow có thật không?
3. Bottleneck có rõ chưa?
4. Metric có đo được không?
5. Rule/process fix đã đủ chưa?
6. Tôi có đang nhảy sang Agent quá sớm không?

Trả lời ngắn, tập trung vào điểm yếu.
```

---

# Break (10')

---

# Phase 3 — Group Convergence: từ 9-12 candidates về 1 (30')

## Mục tiêu

Nhóm 3-4 người sẽ có khoảng 9-12 candidate problems. Không vote ngay. Đi qua 4 bước hội tụ:

```text
Trình bày top 3
→ gom trùng / cluster
→ shortlist
→ chấm nhanh + đồng thuận chọn 1 candidate problem
```

Nhóm lúc này **chỉ chọn candidate problem**, chưa viết Problem Statement hoàn chỉnh.

Đây là phase **tự pitch và tự challenge**. Không dùng AI để viết lời pitch, đặt câu hỏi thay mình, hoặc quyết định thay nhóm. Nếu muốn dùng AI để tóm tắt notes, chỉ làm sau khi nhóm đã thảo luận xong phần chính.

## Bước 3.1 — Trình bày top 3

Mỗi người trình bày 3 candidates, mỗi candidate 1-2 phút:

- problem là gì,
- người gặp vấn đề là ai,
- workflow hiện tại nghẽn ở đâu,
- draft workflow tương lai thay đổi gì,
- vì sao bài này có tác động đáng kể.

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh |
|---|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |
| 8 | | | | | |
| 9 | | | | | |
| 10 | | | | | |
| 11 | | | | | |
| 12 | | | | | |

## Bước 3.2 — Gom trùng / cluster

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A | | | |
| B | | | |
| C | | | |
| D | | | |

## Bước 3.3 — Shortlist

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
| | | |
| | | |
| | | |

## Bước 3.4 — Score để đồng thuận

Chấm 1-5. Điểm không cần tuyệt đối; mục tiêu là ép nhóm nói rõ lý do.

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

Candidate nhóm chọn:

```text

```

Vì sao chọn:

```text

```

Vì sao không chọn các candidate còn lại:

```text

```

Nếu có disagreement, nhóm xử lý thế nào:

```text

```

---

# Phase 4 — Quick Validation + Research giải pháp (30')

## Mục tiêu

Sau khi chọn candidate problem, nhóm cần kiểm tra nhanh:

- pain có thật không,
- người khác có gặp không,
- đã có giải pháp nào tương tự chưa,
- bài toán có nên giải bằng AI không.

## Bước 4.1 — Quick validation

Chọn ít nhất một cách.

### Option A — Quick interviews

Hỏi 2-3 người:

- Lần gần nhất bạn gặp vấn đề này là khi nào?
- Bạn đang xử lý bằng workflow nào?
- Bước nào mất thời gian hoặc khó chịu nhất?
- Bạn mất khoảng bao lâu?
- Nếu tốt hơn, bạn muốn điều gì thay đổi?

### Option B — Micro survey / Discord poll

Hỏi 5-10 người:

- Bạn có gặp vấn đề này không?
- Tần suất?
- Bước nào đau nhất?
- Hiện bạn workaround thế nào?
- Mức độ đáng giải quyết: 1-5?

Kết quả:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | | | | |
| Survey / poll | | | | |
| Log / review / ticket | | | | |

## Bước 4.2 — Research giải pháp đã có

Tìm ít nhất:

- 2-3 existing solutions/tools/patterns.
- 1-2 nguồn tham khảo có hyperlink.
- Nhận xét: họ xử lý bước nào trong workflow, chưa xử lý bước nào.
- Bài học kéo về bài toán nhóm mình.

| Nguồn / tool / case | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

Nếu dùng AI research, dùng prompt:

```text
Nhóm tôi đang phân tích bài toán:
[mô tả ngắn]

Hãy tìm:
1. 2-3 tool/case/pattern đã giải bài toán tương tự
2. Họ giải quyết bước nào trong workflow
3. Rủi ro hoặc khoảng trống còn lại

Yêu cầu: ghi link nguồn cho claim quan trọng. Nếu không chắc, nói rõ không chắc.
```

Không dùng số liệu AI đưa ra nếu không verify được.

---

# Phase 5 — Workflow + Problem Statement (45')

## Bước 5.1 — Current workflow bản nhóm

Vẽ workflow hiện tại kỹ hơn bản cá nhân. Mỗi bước nên có:

- actor,
- input,
- output,
- thời gian/tần suất,
- handoff,
- bottleneck.

Dán workflow hoặc link file:

```text

```

| Bước | Actor | Input | Output | Thời gian/tần suất | Ghi chú |
|---|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

Bottleneck chính:

```text

```

## Bước 5.2 — Future workflow bản nhóm

Vẽ workflow sau tối ưu. Cần thể hiện:

- bước nào Rule xử lý,
- bước nào AI/Workflow hỗ trợ,
- bước nào con người vẫn làm,
- boundary ở đâu,
- phương án quay về nếu AI sai.

Dán workflow hoặc link file:

```text

```

Before/after impact:

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Risk mới | | | |

## Bước 5.3 — Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | |
| **Workflow** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** | |
| **Boundary** | |

Prompt phản biện PS:

```text
Đây là Problem Statement v0 của nhóm tôi:
[dán 6 field]

Hãy chỉ ra field nào còn mơ hồ, metric đã đo được chưa, boundary đã rõ chưa.
Đừng viết lại thay tôi. Chỉ đặt câu hỏi và chỉ ra lỗ hổng.
```

---

# Break (10')

---

# Phase 6 — Rule / Workflow / Agent + Decision (25')

## Bước 6.0 — Ma trận độ phù hợp với AI để suy nghĩ nhanh

Ma trận này chỉ là công cụ phụ để suy nghĩ. Quyết định cuối vẫn phải dựa trên workflow, metric, boundary và rủi ro thật.

| | Độ mơ hồ thấp | Độ mơ hồ cao |
|---|---|---|
| **Độ phức tạp thấp** | Rule hoặc workflow đơn giản thường đủ | Workflow có AI hỗ trợ một bước có thể đủ |
| **Độ phức tạp cao** | Workflow điều phối nhiều bước rõ ràng, chưa chắc cần Agent | Agent có thể phù hợp, nhưng cần boundary, người thật kiểm tra và phương án quay về rất rõ |

Độ mơ hồ là gì?

- Thấp: có đáp án đúng/sai khá rõ, ví dụ phân loại theo 5 nhóm cố định.
- Cao: có nhiều cách trả lời vẫn chấp nhận được, ví dụ viết narrative tổng hợp từ nhiều nguồn.

Độ phức tạp là gì?

- Thấp: 1-2 bước, input/output rõ, ít nguồn dữ liệu.
- Cao: nhiều bước nối tiếp, nhiều nguồn dữ liệu, bước sau phụ thuộc kết quả bước trước.

Tự kiểm nhanh:

| Câu hỏi | Nếu có | Nếu không |
|---|---|---|
| Output có thể khác nhau mỗi lần mà vẫn chấp nhận được không? | Độ mơ hồ cao | Độ mơ hồ thấp |
| Cần phối hợp 3+ bước hoặc 3+ nguồn dữ liệu không? | Độ phức tạp cao | Độ phức tạp thấp |
| AI có cần tự quyết định bước tiếp theo không? | Có thể cần Agent | Rule/Workflow có thể đủ |

Bài toán của nhóm nằm ở ô nào?

```text

```

Vì sao?

```text

```

## Bước 6.1 — So sánh Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

Hỏi kỹ:

- Rule có giải được 70-80% case không?
- Workflow có đủ vì các bước khá rõ không?
- Có thật sự cần Agent tự lập kế hoạch/gọi công cụ/đổi bước tiếp theo không?
- Nếu AI sai, ai phát hiện và sửa?
- Có thể hạ mức từ Agent về Workflow hoặc từ Workflow về Rule không?

Mức chọn:

```text
[Rule / Workflow / Agent]
```

Vì sao chọn:

```text

```

Vì sao không chọn mức đơn giản hơn:

```text

```

## Bước 6.2 — Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | |
| **Workflow** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | Rule / Workflow / Agent |
| **Rủi ro & người thật kiểm tra** | |

## Bước 6.3 — Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor và workflow đã rõ chưa? | | |
| Baseline và success metric đã đo được chưa? | | |
| Có data/input đủ dùng chưa? | | |
| Nếu AI sai, hậu quả có chấp nhận được không? | | |
| Có người review/owner vận hành không? | | |
| Có cách non-AI đơn giản hơn không? | | |

Decision:

```text
[Go / Not Yet / No-Go]
```

Lý do:

```text

```

Nếu Go, pilot nhỏ nhất là:

```text

```

Nếu Not Yet, cần validate gì trước:

```text

```

Nếu No-Go, nên làm gì thay AI:

```text

```

---

# Phase 7 — Individual Reflection (15')

Reflection không chỉ là "tôi dùng AI thế nào". Bạn cần phản tư về vai trò của mình trong nhóm.

Reflection là phần cá nhân. Không dùng AI để viết thay câu trả lời. Nếu dùng AI, chỉ dùng để gợi ý câu hỏi tự soi hoặc kiểm xem mình còn bỏ sót ý nào.

## Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Liệt kê 10 problems dựa trên trải nghiệm của bản thân về học tập và nghiên cứu. | Nhóm có một bộ scan phong phú, đạt điểm bonus. |
| Pitch Problem Card | Pitch chi tiết về vấn đề Viết báo cáo và làm slide cuối kỳ của sinh viên. | Thuyết phục được nhóm đưa bài toán này vào danh sách shortlist. |
| Challenge bài của bạn khác | Hỏi xem dự án "Reproduce paper" của bạn khác có khả thi trong 1 buổi lab không khi dữ liệu và tài nguyên tính toán hạn chế. | Giúp nhóm nhận ra độ phức tạp của bài toán và hạ xuống vị trí thứ 3 để tập trung bài toán khả thi hơn. |
| Gom trùng / cluster | Phối hợp gom các ý tưởng về báo cáo và dịch thuật vào cùng một nhóm "Tổng hợp & soạn thảo". | Rút gọn danh sách candidate nhanh chóng. |
| Chọn candidate problem | Thảo luận và chấm điểm dựa trên tiêu chí khả thi và mức độ lặp lại của bài toán viết báo cáo/slide. | Nhóm đồng thuận chọn bài toán viết báo cáo và slide làm bài toán nhóm để đào sâu. |
| Validation / research | Thực hiện khảo sát nhanh qua chat với 5 bạn sinh viên khác về thời gian họ làm slide. | Thu được số liệu thực tế: trung bình mất 3-4 tiếng cho slide và 5 tiếng viết báo cáo. |
| Workflow nhóm | Đóng góp ý kiến để vẽ Workflow hiện tại và tương lai của bài toán làm báo cáo/slide nhóm. | Thống nhất được điểm can thiệp của AI (ở bước cấu trúc báo cáo và sinh code slide Marp). |
| Problem Statement | Viết phần boundary và success metric cho Problem Statement. | Đảm bảo tính khả thi và đo lường được của sản phẩm. |
| Rule / Workflow / Agent | Phân tích vì sao không chọn Agent (do quá phức tạp và rủi ro hallucinate cao) mà chọn Workflow. | Giúp nhóm thống nhất giải pháp thực tế, an toàn. |
| Decision | Đề xuất kịch bản rollback cụ thể nếu AI draft nội dung tệ. | Chốt được quyết định Go kèm theo điều kiện thử nghiệm rõ ràng. |

## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm các lăng kính từ trải nghiệm sinh viên. | Mở rộng ra các vấn đề về citation, dịch thuật chuyên ngành. | Một số gợi ý quá chung chung (ví dụ: "quản lý thời gian học tập"). | Bỏ qua các ý chung chung, chỉ giữ lại các vấn đề có dấu hiệu rõ như định dạng APA. |
| Problem Card | Hỗ trợ cấu trúc chi tiết của card số 1. | Sắp xếp thông tin mạch lạc, rõ ràng. | AI đề xuất success metric chung chung như "làm nhanh hơn". | Sửa thành metric định lượng cụ thể: "giảm từ 15 tiếng xuống dưới 4 tiếng". |
| Workflow | Sinh mã ASCII cho sơ đồ Before/After. | Tiết kiệm thời gian căn chỉnh sơ đồ chữ. | AI gộp bước viết nội dung và slide thành một bước AI duy nhất. | Tách ra làm hai bước riêng vì sinh viên cần review báo cáo trước rồi mới làm slide. |
| Research | Tìm kiếm các thư viện hỗ trợ sinh slide tự động từ Markdown. | Gợi ý thư viện Marp và python-pptx rất hữu ích. | Đưa ra thông tin tính năng của một số tool trả phí không rõ nguồn gốc. | Chỉ giữ lại Marp vì đây là công cụ mã nguồn mở dễ tích hợp vào workflow. |
| Problem Statement | Phản biện tính chặt chẽ của các trường thông tin. | Chỉ ra rằng phần "Boundary" ban đầu còn quá lỏng lax. | Đề xuất boundary mang tính kỹ thuật sâu không cần thiết. | Sửa lại boundary tập trung vào khía cạnh sản phẩm: "AI không tự ý nộp bài, không tự bịa số liệu nghiên cứu". |
| Rule / Workflow / Agent | Đối chiếu ưu nhược điểm của 3 giải pháp. | Đưa ra các rủi ro cụ thể của từng phương án. | Gợi ý chọn Agent để hệ thống nghe có vẻ "hiện đại" hơn. | Quyết định chọn Workflow vì tính khả thi cao và dễ kiểm soát lỗi đối với sinh viên. |
| Decision | Lập các điều kiện để quyết định Go/No-Go. | Gợi ý bộ khung câu hỏi tự kiểm tra rất logic. | Các điều kiện rollback còn mơ hồ, thiếu định lượng. | Bổ sung điều kiện rollback định lượng: "nếu phải sửa lại >70% nội dung draft trong 2 tuần". |

## Reflection câu hỏi mở

- **Tôi học được gì khi nghe top 3 problems của các bạn khác?**  
  Tôi nhận ra rằng các bạn khác gặp rất nhiều vấn đề thực tế trong việc nghiên cứu và học tập (như tìm kiếm tài liệu học tập, viết code mẫu). Những vấn đề này đều rất lớn, nhưng khi phân tích kỹ dưới góc độ workflow thì nhận thấy đa số đều chưa có quy trình làm việc chuẩn, khiến việc áp dụng AI gặp khó khăn.
- **Nhóm có lúc nào bị solution-first không?**  
  Có, lúc đầu nhóm rất hào hứng muốn xây dựng một "Agent AI tự động đọc tài liệu và viết code từ A-Z". Tuy nhiên, sau khi vẽ current workflow và thảo luận về rủi ro, nhóm nhận ra việc đó quá phức tạp và dễ thất bại, nên đã quay lại tập trung vào bài toán cốt lõi và chọn giải pháp Workflow đơn giản hơn nhưng thực tế hơn.
- **Tôi có thay đổi ý kiến sau khi bị challenge không?**  
  Có. Ban đầu tôi nghĩ bài toán "Reproduce paper" là cấp bách nhất vì bản thân tôi mất rất nhiều thời gian cho việc đó. Nhưng khi các bạn challenge về tài nguyên tính toán và độ phức tạp cực kỳ cao của việc tự code từ công thức toán học, tôi đồng ý rằng bài toán này quá rộng và khó hoàn thành tốt trong buổi lab, nên đã đồng ý chuyển sang làm bài toán viết báo cáo/slide.
- **Tôi đóng góp gì thật sự vào artifact cuối?**  
  Tôi là người cấu trúc lại toàn bộ bảng so sánh Top 3, viết chi tiết cho Problem Card #1, đề xuất kịch bản workflow tương lai sử dụng Marp (một công cụ sinh slide từ Markdown) để nhóm có một giải pháp khả thi nhất.
- **Điều khó nhất khi viết Problem Statement là gì?**  
  Điều khó nhất là định lượng được success metric và xác định ranh giới (boundary) rõ ràng của AI. Việc viết "giúp sinh viên làm slide nhanh hơn" rất dễ, nhưng để đo lường chính xác và quy định xem AI được phép làm gì, phần nào bắt buộc con người phải duyệt là cực kỳ khó khăn.
- **Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?**  
  Nếu làm lại, tôi sẽ challenge mạnh hơn về các giải pháp thay thế không dùng AI (non-AI alternatives) để xem liệu chúng ta có thực sự cần AI trong bài toán này không, hay chỉ cần một template tốt và một công cụ tự động hóa dạng rule-based là đủ.

Reflection:

```text
Buổi lab hôm nay giúp tôi hiểu rõ rằng AI không phải là "chìa khóa vạn năng". Việc xác định đúng vấn đề, hiểu rõ workflow hiện tại và điểm nghẽn thực sự quan trọng hơn nhiều so với việc cố gắng áp dụng các công nghệ phức tạp như Agent. Khi làm việc nhóm, việc lắng nghe challenge từ các bạn khác giúp tôi nhìn nhận vấn đề khách quan hơn, không bị thiên lệch bởi trải nghiệm cá nhân của mình. Đối với bài toán viết báo cáo và làm slide, việc chọn mức độ Workflow (AI hỗ trợ draft, con người kiểm soát chất lượng) là một quyết định cân bằng giữa tính khả thi kỹ thuật và trải nghiệm người dùng.
```

## Tự kiểm cuối bài

- [ ] [12đ cá nhân] Cá nhân có 5+ problems và top 3 Problem Cards.
- [ ] [12đ cá nhân] Tôi đã pitch rõ và challenge nhóm đúng trọng tâm.
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài.
- [ ] [15đ nhóm] Nhóm có workflow trước/sau.
- [ ] [20đ nhóm] Nhóm có Problem Statement v0/v1 với metric và boundary rõ.
- [ ] [15đ nhóm] Nhóm có so sánh No AI / Rule / Workflow / Agent.
- [ ] [10đ nhóm] Nhóm có Go / Not Yet / No-Go và lý do rõ.
- [ ] [10đ cá nhân] Reflection cá nhân có nói rõ vai trò trong nhóm, cách dùng AI, điều học được và nếu làm lại sẽ đổi gì.
- [ ] [6đ cá nhân] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp với AI.

---

*Day 02 Lab — Worksheet*
