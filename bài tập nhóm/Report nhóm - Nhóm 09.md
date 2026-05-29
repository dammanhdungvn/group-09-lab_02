# BÀI TẬP NHÓM - NHÓM 09

## AI hỗ trợ sinh viên xây dựng báo cáo dự án

**Repo nộp bài:** `git@github.com:dammanhdungvn/group-09-lab_02.git`  
**Nhóm:** 09  
**Đề tài:** AI Report Assistant - giúp sinh viên biến những gì đã làm trong dự án thành một báo cáo hoàn chỉnh dạng Markdown/LaTeX, có liên kết với bằng chứng thật.

| Họ và tên | Mã sinh viên | Vai trò trong bài nhóm |
|---|---|---|
| Đàm Mạnh Dũng | 2A202600741 | Tổng hợp problem statement, workflow, metric, decision |
| Nguyễn Hoàng Thanh Tùng | 2A202600846 | Góp ý workflow hiện tại, challenge rủi ro AI bịa nội dung |
| Đàm Mạnh A | 2A202600xxx | Đóng góp góc nhìn sinh viên viết đồ án/báo cáo |
| Nguyễn Hoàng Thanh B | 2A202600xxx | Đóng góp góc nhìn format, bằng chứng, demo, kiểm thử |

---

# 1. Hội tụ nhóm

## 1.1. Các candidate problems ban đầu

Nhóm không chốt ngay "xây AI". Mỗi thành viên đưa ra các vấn đề quan sát được trong học tập, làm bài tập lớn và làm dự án.

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh |
|---:|---|---|---|---|---|
| 1 | Đàm Mạnh Dũng | Sinh viên làm xong sản phẩm nhưng mất rất lâu để viết báo cáo dự án | Sinh viên năm cuối/làm bài tập lớn | Tổng hợp source code, demo, test, README thành báo cáo | Rất phù hợp |
| 2 | Đàm Mạnh Dũng | Không biết cấu trúc báo cáo nên bắt đầu từ đâu | Sinh viên mới làm đồ án | Blank page, thiếu outline | Phù hợp |
| 3 | Đàm Mạnh Dũng | Báo cáo thiếu bằng chứng: ảnh demo, kết quả test, giải thích tính năng | Sinh viên nộp bài | Không có evidence matrix | Rất phù hợp |
| 4 | Thanh Tùng | README và source code không khớp với báo cáo | Sinh viên dev | Update code nhưng quên update tài liệu | Phù hợp |
| 5 | Thanh Tùng | Viết giải thích kỹ thuật khó hiểu với người chấm | Sinh viên IT | Chuyển code thành ngôn ngữ học thuật | Phù hợp |
| 6 | Đàm Mạnh A | Cần format báo cáo LaTeX/Word theo mẫu trường | Sinh viên | Mất nhiều thời gian sửa format | Phù hợp một phần |
| 7 | Đàm Mạnh A | Không biết chèn hình/chứng cứ vào phần nào | Sinh viên làm demo | Evidence nằm rải rác | Phù hợp |
| 8 | Đàm Mạnh A | Cuối deadline mới phát hiện thiếu chương kiểm thử | Sinh viên | Checklist nộp bài không rõ | Phù hợp |
| 9 | Nguyễn Hoàng Thanh B | Báo cáo nhiều người viết bị lệch giọng văn | Nhóm sinh viên | Không thống nhất style | Phù hợp |
| 10 | Nguyễn Hoàng Thanh B | Tìm tài liệu tham khảo và trích dẫn mất thời gian | Sinh viên | Reference management | Phù hợp nhưng scope lớn |
| 11 | Nguyễn Hoàng Thanh B | Chuyển nội dung từ Markdown sang LaTeX lỗi format | Sinh viên | Lỗi bảng, hình, citation | Phù hợp một phần |
| 12 | Nguyễn Hoàng Thanh B | Gộp feedback của giảng viên vào bản sửa khó theo dõi | Sinh viên | Không có version/checklist sửa lỗi | Scope lớn hơn |

## 1.2. Gom trùng / cluster

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A. Tổng hợp báo cáo từ dự án thật | 1, 2, 3, 4, 5, 7, 8 | Biến nhiều nguồn dữ liệu dự án thành báo cáo có cấu trúc | Cluster mạnh nhất |
| B. Format và xuất tài liệu | 6, 11 | Chuyển nội dung sang LaTeX/Word theo mẫu | Nên là một phần trong workflow, không phải problem chính |
| C. Quản lý tham khảo | 10 | Tìm và trích dẫn tài liệu | Cần giải pháp riêng, dễ vượt scope lab |
| D. Làm việc nhóm và version | 9, 12 | Nhiều người viết, nhiều feedback, khó đồng bộ | Có liên quan nhưng scope rộng |

## 1.3. Shortlist

| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| AI Report Assistant cho báo cáo dự án | Actor rõ, workflow rõ, đau thật, có metric thời gian và chất lượng | Cần tránh AI viết thay/tạo nội dung không có bằng chứng |
| Tool format báo cáo Markdown/LaTeX | Dễ hiểu, dễ làm pilot | Chỉ giải quyết format, không giải quyết tổng hợp nội dung |
| Evidence checklist cho báo cáo | Giảm thiếu sót bằng chứng | Có thể chỉ cần rule/checklist, chưa chắc cần AI |

## 1.4. Score để đồng thuận

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| AI Report Assistant cho báo cáo dự án | 5 | 5 | 4 | 5 | 5 | 5 | 5 | 34 |
| Tool format Markdown/LaTeX | 5 | 4 | 4 | 3 | 5 | 3 | 5 | 29 |
| Evidence checklist cho báo cáo | 5 | 4 | 4 | 4 | 5 | 4 | 5 | 31 |

**Candidate nhóm chọn:** AI Report Assistant cho báo cáo dự án.

**Vì sao chọn:** đây là bài toán có actor rõ, workflow dài và lặp lại, có bottleneck cụ thể ở bước tổng hợp/trình bày, có thể đo thời gian hoàn thiện bản nháp và số mục thiếu bằng chứng. Giải pháp không cần để AI tự viết thay toàn bộ báo cáo, mà đặt AI vào một workflow có người thật kiểm tra.

**Vì sao không chọn các candidate còn lại:** tool format chỉ giải quyết phần cuối; evidence checklist hữu ích nhưng nếu dùng một mình thì chưa giải quyết vấn đề sinh viên không biết nối các bằng chứng thành narrative báo cáo.

---

# 2. Quick validation + research

## 2.1. Quick validation

Ghi chú trung thực: các số liệu dưới đây là ước lượng trong phạm vi lab dựa trên trải nghiệm của nhóm và trao đổi nhanh. Nếu làm sản phẩm thật, nhóm cần đo lại bằng log/report mẫu trong pilot.

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Thảo luận nội bộ nhóm | 4 | Cả 4 thành viên đều từng gặp khó khi tổng hợp code, ảnh demo, test, README vào báo cáo | Mức độ đau khác nhau tùy môn học | Thu hẹp actor vào sinh viên làm bài tập lớn/đồ án có source code và demo |
| Trao đổi nhanh với bạn học | 5 | 4/5 nói viết báo cáo tốn nhiều ngày cuối; 3/5 hay thiếu hình demo/test result | 1 bạn nói chỉ cần mẫu báo cáo rõ là đủ | Thêm non-AI alternative: template + checklist |
| Review nội dung slide đề tài | 10 slide | Slide xác nhận các pain: thông tin rải rác, khó trình bày, dễ thiếu bằng chứng, áp lực deadline | Chưa có số liệu định lượng thật | Đặt metric pilot để đo: thời gian draft, số mục thiếu, số lỗi không khớp |

**Insight sau validation:**

```text
Pain không nằm ở việc "AI viết hộ báo cáo".
Pain nằm ở việc sinh viên phải tổng hợp nhiều bằng chứng rải rác và biến chúng thành một cấu trúc báo cáo nhất quán.
```

## 2.2. Research giải pháp đã có

| Nguồn / tool / case | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Overleaf | [overleaf.com/about/features-overview](https://www.overleaf.com/about/features-overview) | Viết, biên dịch và cộng tác trên tài liệu LaTeX | Tốt cho format, collaboration, xuất PDF | Không tự hiểu source code/demo/test của dự án sinh viên | Nên xuất LaTeX/Markdown, nhưng không coi format là toàn bộ solution |
| Gemini in Drive | [support.google.com/drive/answer/15141241](https://support.google.com/drive/answer/15141241) | Tóm tắt và lấy insight từ file/folder | Tốt khi tài liệu nằm trong Drive | Phụ thuộc file được cung cấp; cần kiểm nguồn | AI có thể hỗ trợ đọc/tóm tắt tài liệu, nhưng phải có evidence link |
| GitHub Copilot | [docs.github.com/copilot](https://docs.github.com/en/copilot/overview-of-github-copilot/about-github-copilot) | Hỗ trợ hiểu/viết code và giải thích context code | Tốt cho code-level explanation | Không tự động biến toàn bộ dự án thành báo cáo học thuật | Có thể dùng như input giải thích module, không thay report workflow |
| Grammarly AI Writing Assistant | [grammarly.com/ai-writing-assistant](https://www.grammarly.com/ai-writing-assistant) | Hỗ trợ viết và sửa ngôn ngữ | Tốt cho diễn đạt, tone, grammar | Có thể làm nội dung hay nhưng không đảm bảo đúng với dự án | AI writing chỉ nên là bước polish/draft, không phải nguồn sự thật |

**Research takeaway:**

```text
Nên chọn Workflow: gom tài liệu dự án -> phân loại -> đề xuất outline -> tạo evidence matrix -> draft từng phần -> sinh viên review -> xuất Markdown/LaTeX.
Không nên chọn Agent tự động nộp báo cáo vì rủi ro bịa nội dung, sai bằng chứng và vượt boundary học tập.
```

---

# 3. Workflow trước / sau

## 3.1. Current workflow

```text
CURRENT STATE - 8 bước, ước lượng 24-40 giờ cho một báo cáo dự án

[1 Hoàn thành source code/demo]
-> [2 Tìm lại README, screenshot, test result, ghi chú: 3-6h]
-> [3 Đọc lại yêu cầu giảng viên/mẫu báo cáo: 1-2h]
-> [4 Tự lập outline báo cáo: 2-4h]
-> [5 Viết các chương: mở đầu, phân tích, thiết kế, cài đặt, kiểm thử: 10-18h] <-- bottleneck
-> [6 Chèn hình, bảng, kết quả test, citation: 4-6h]
-> [7 Sửa format Markdown/Word/LaTeX: 2-4h]
-> [8 Review lần cuối và nộp: 2-4h]
```

| Bước | Actor | Input | Output | Thời gian/tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Sinh viên/nhóm | Source code, demo | Sản phẩm có thể chạy | Theo tiến độ dự án | Chưa thành báo cáo |
| 2 | Sinh viên | Code, README, ảnh demo, test | Tập thông tin thô | 3-6 giờ | Thông tin rải rác |
| 3 | Sinh viên | Rubric, mẫu báo cáo | Danh sách yêu cầu | 1-2 giờ | Dễ bỏ sót field |
| 4 | Sinh viên | Yêu cầu + thông tin thô | Outline | 2-4 giờ | Blank page |
| 5 | Sinh viên | Outline + bằng chứng | Bản nháp nội dung | 10-18 giờ | Bottleneck chính |
| 6 | Sinh viên | Ảnh/demo/test/reference | Bằng chứng trong báo cáo | 4-6 giờ | Dễ chèn sai/đổi chỗ |
| 7 | Sinh viên | Bản nháp | File đúng format | 2-4 giờ | Nhiều lỗi nhỏ |
| 8 | Sinh viên/nhóm | File báo cáo | Bản nộp cuối | 2-4 giờ | Review thủ công |

**Bottleneck chính:** bước 5 và 6. Sinh viên biết mình đã làm gì, nhưng khó biến code/demo/test thành văn bản học thuật có cấu trúc và có bằng chứng kèm theo.

## 3.2. Future workflow

```text
FUTURE STATE - 7 bước, ước lượng 9-16 giờ cho bản nháp đầu tiên

[1 Sinh viên upload/gói tài liệu: source, README, screenshot, test, rubric]
-> [2 Rule kiểm tra file bắt buộc và đặt tên]
-> [3 AI phân loại tài liệu + tạo evidence matrix]
-> [4 AI đề xuất outline theo rubric]
-> [5 AI draft từng phần dựa trên bằng chứng đã có] <-- AI intervention point
-> [6 Sinh viên review, sửa, bổ sung, xác nhận sự thật] <-- human boundary
-> [7 Export Markdown/LaTeX/PDF và checklist nộp bài]

Fallback:
Nếu AI không tìm đủ bằng chứng -> đánh dấu "Cần bổ sung", không tự bịa.
Nếu draft sai -> sinh viên loại bỏ đoạn sai và tự sửa dựa trên evidence.
```

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Số bước chính | 8 | 7 | Không giảm nhiều bước, nhưng giảm effort ở bước tổng hợp/viết |
| Thời gian có bản nháp đầu tiên | 24-40 giờ | 9-16 giờ | Metric pilot cần đo bằng time log |
| Số mục bắt buộc bị thiếu | 3-5 mục/báo cáo | <= 1 mục/báo cáo | Đo bằng checklist theo rubric |
| Số claim không có bằng chứng được đưa vào final | Chưa kiểm soát | 0 | Claim không có evidence phải bị flag |
| Bottleneck mới | Review thủ công | Review và xác nhận sự thật | Chấp nhận được vì đó là boundary học tập |
| Risk mới | Không có hallucination AI | AI có thể draft sai | Giảm bằng evidence matrix và human review |

---

# 4. Problem Statement

## 4.1. Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên làm bài tập lớn, đồ án môn học, báo cáo thực tập hoặc đồ án tốt nghiệp. |
| **Workflow** | Sau khi làm xong sản phẩm, sinh viên tìm lại source code, README, ảnh demo, kết quả test, tài liệu tham khảo, rồi viết thành báo cáo dài theo mẫu giảng viên. |
| **Bottleneck** | Tổng hợp và trình bày lại toàn bộ dự án thành báo cáo có cấu trúc, đúng với những gì đã làm, có bằng chứng kèm theo. |
| **Impact** | Mất 24-40 giờ để có bản nháp đầu tiên; dễ thiếu bằng chứng; có nguy cơ viết không khớp với sản phẩm thực tế; áp lực cao sát deadline. |
| **Success Metric** | Giảm thời gian có bản nháp đầu tiên xuống 9-16 giờ; số mục thiếu trong checklist <= 1; claim không có bằng chứng trong final = 0. |
| **Boundary** | Không để AI viết thay và nộp thay; không cho AI bịa tính năng/kết quả; không thay sinh viên kiểm chứng nội dung; chỉ draft dựa trên tài liệu được cung cấp. |

## 4.2. Độ phù hợp với AI

| Câu hỏi | Đánh giá của nhóm |
|---|---|
| Output có nhiều cách viết đúng không? | Có. Báo cáo có tính ngôn ngữ và cấu trúc học thuật. |
| Có cần tổng hợp nhiều nguồn không? | Có. Source code, README, demo, test, rubric, references. |
| Có cần AI tự quyết định hành động tiếp theo không? | Chưa cần trong pilot. Workflow có các bước rõ. |
| Nếu AI sai, hậu quả có chấp nhận được không? | Chấp nhận được nếu AI chỉ draft và sinh viên review trước khi nộp. |

**Ô phù hợp:** độ mơ hồ cao, độ phức tạp cao vừa phải. Chọn **Workflow có AI hỗ trợ**, chưa chọn Agent tự động.

---

# 5. Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI / Process fix** | Mẫu báo cáo + checklist + folder template | Đủ nếu sinh viên chỉ thiếu format | Không giải quyết việc biến dữ liệu rải rác thành narrative | Không chọn làm toàn bộ |
| **Rule** | Kiểm tra file bắt buộc, tên file, số chương, mục nào thiếu bằng chứng | Đủ cho checklist và validation có quy tắc rõ | Không giúp viết/giải thích phần kỹ thuật | Dùng một phần |
| **Workflow** | Rule check input -> AI phân loại -> AI tạo outline/evidence matrix -> AI draft -> sinh viên review -> export | Phù hợp vì các bước rõ, AI chỉ hỗ trợ các bước ngôn ngữ/tổng hợp | Draft sai, thiếu context, cần human review | **Chọn** |
| **Agent** | Agent tự đọc repo, tự hỏi thêm, tự viết, tự sửa format, tự nộp | Chỉ phù hợp khi có môi trường đủ quyền, log tốt, guardrail mạnh | Quá rộng, dễ hallucinate, rủi ro học thuật | Chưa chọn |

**Mức chọn:** Workflow.

**Vì sao chọn:** workflow của bài toán có đường đi tuyến tính và có nhiều bước có thể kiểm soát. Rule phù hợp cho checklist/file validation. AI phù hợp cho phần phân loại, outline, draft narrative và phát hiện missing evidence. Sinh viên vẫn là người xác nhận đúng sai.

**Vì sao không chọn mức đơn giản hơn:** Rule/checklist giảm thiếu sót nhưng không giải quyết bottleneck lớn nhất là diễn đạt và kết nối bằng chứng thành nội dung báo cáo.

**Vì sao không chọn Agent:** pilot chưa cần AI tự lập kế hoạch và tự hành động. Nếu cho Agent tự đọc repo/viết/nộp, rủi ro quyền truy cập, sai nội dung và vi phạm nguyên tắc học tập cao hơn lợi ích.

---

# 6. Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên/nhóm sinh viên đã hoàn thành phần lớn sản phẩm dự án và cần nộp báo cáo theo rubric của giảng viên. |
| **Workflow** | Gom source code, README, screenshot demo, kết quả test, rubric, reference -> lập outline -> viết các chương -> gắn bằng chứng -> format Markdown/LaTeX -> review và nộp. |
| **Bottleneck** | Biến nhiều thông tin rải rác thành bản nháp báo cáo có cấu trúc, khớp với sản phẩm thật và có bằng chứng cho từng claim. |
| **Impact** | Ước lượng 24-40 giờ để có bản nháp đầu tiên; dễ thiếu 3-5 mục/bằng chứng; có nguy cơ viết nội dung không tồn tại trong dự án. |
| **Success Metric** | Trong pilot 1 báo cáo: thời gian có bản nháp đầu tiên giảm xuống 9-16 giờ; checklist thiếu <= 1 mục; 100% claim quan trọng có evidence hoặc bị flag "cần bổ sung". |
| **Boundary** | AI không tự nộp, không tự bịa số liệu/tính năng/test, không thay sinh viên chịu trách nhiệm; nếu không có evidence thì phải đánh dấu thiếu. |
| **AI intervention point** | Sau khi sinh viên cung cấp gói tài liệu dự án, trước bước viết bản nháp báo cáo. AI hỗ trợ phân loại, tạo outline, evidence matrix và draft từng phần. |
| **Mức chọn** | Workflow: rule/checklist + AI draft có evidence + human review. |
| **Rủi ro & người thật kiểm tra** | Rủi ro hallucination, bỏ sót module, diễn đạt quá chung chung. Sinh viên/nhóm phải review từng claim, đối chiếu với repo/demo/test trước khi nộp. |

---

# 7. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor và workflow đã rõ chưa? | Yes | Actor là sinh viên làm báo cáo dự án; workflow đã vẽ được before/after. |
| Baseline và success metric đã đo được chưa? | Not Yet | Đã có ước lượng, cần pilot time log để xác nhận. |
| Có data/input đủ dùng chưa? | Yes cho pilot nhỏ | Cần một repo/project mẫu có README, screenshot, test result, rubric. |
| Nếu AI sai, hậu quả có chấp nhận được không? | Yes nếu có review | AI chỉ draft; sinh viên approve. |
| Có người review/owner vận hành không? | Yes | Sinh viên/nhóm là owner. |
| Có cách non-AI đơn giản hơn không? | Có một phần | Template/checklist nên dùng kèm, nhưng không đủ giải quyết narrative. |

**Decision:** Go với scope nhỏ.

**Lý do:** problem rõ, workflow rõ, có metric pilot, có boundary học thuật và không cần Agent ngay. Rủi ro lớn nhất là AI bịa nội dung đã được giảm bằng nguyên tắc: không có bằng chứng thì không được xem là sự thật.

**Pilot nhỏ nhất:**

1. Chọn 1 dự án sinh viên đã có source code, README, 5-7 screenshot, test result và rubric.
2. Dùng workflow bán thủ công: sinh viên upload/copy input vào template.
3. AI tạo outline, evidence matrix và bản draft từng chương.
4. Sinh viên đo: thời gian có draft, số mục thiếu, số claim sai/không có bằng chứng, mức độ hài lòng.
5. Nếu AI draft sai quá 30% claim quan trọng hoặc sinh viên phải viết lại gần như toàn bộ, hạ scope về template + checklist + evidence matrix.

---

# 8. Checklist tự kiểm

- [x] Nhóm có nhật ký hội tụ từ nhiều candidate về 1 candidate problem.
- [x] Có validation/research và ghi rõ giả định cần kiểm tiếp.
- [x] Có workflow trước/sau, actor, input, output, thời gian và bottleneck.
- [x] Có Problem Statement v0/v1 với metric và boundary.
- [x] Có so sánh No AI / Rule / Workflow / Agent.
- [x] Có decision Go / Not Yet / No-Go và pilot nhỏ nhất.
- [x] Có nguyên tắc human review: AI hỗ trợ, sinh viên chịu trách nhiệm.

