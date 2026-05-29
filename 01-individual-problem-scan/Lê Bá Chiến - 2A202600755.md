  
Bài làm được thiết lập trong bối cảnh một đội ngũ phát triển kỹ thuật/sản phẩm (Product & Engineering Team), lấy ý tưởng **GraphRAG Onboarding** làm trục bài toán chủ đạo (Candidate \#1).

# **BẢN NỘP BÀI CÁ NHÂN: PHASE 1 & PHASE 2**

**Thành phần thư mục:** 01-individual-problem-scan/  
**Học viên:** Lê Bá Chiến-2A202600755 

## **PHASE 1 — INDIVIDUAL SCAN: NGÂN HÀNG VẤN ĐỀ CÁ NHÂN**

*Mục tiêu: Quét rộng tối thiểu 5 vấn đề thực tế từ lăng kính quan sát hằng ngày, có số liệu minh chứng (Baseline) rõ ràng, không nhảy cóc sang giải pháp AI.*

### **Bảng Quét Vấn Đề (Scan 5+ Problems)**

| \# | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật (Evidence / Baseline) |
| :---- | :---- | :---- | :---- | :---- |
| **1** | **Tốn thời gian** | Lập trình viên mới vào dự án mất nhiều ngày đọc tài liệu phân mảnh để hiểu luồng sản phẩm. | Nhân sự mới (Newbie Dev, Manual QA) | Mất trung bình **10-15 tiếng/tuần đầu** chỉ để tự tra cứu thông tin tĩnh từ nhiều nguồn. |
| **2** | **Lặp lại** | Nhân sự cũ phải liên tục dừng việc để giải thích cấu trúc tính năng và sự phụ thuộc cho người mới. | Core Dev / Senior Dev / Tech Lead | Bị ping hỏi lặp đi lặp lại **3-4 lần/tuần** trên Slack (gây đứt gãy mạch code, giảm 20% năng suất tập trung). |
| **3** | **AI tốt hơn** | Tìm kiếm từ khóa thông thường (Keyword Search) chỉ ra file đích, không kết nối được mối quan hệ chéo. | Toàn bộ đội ngũ kỹ thuật | Mỗi lần search tài liệu vẫn phải mở tiếp **3-4 tab** (Notion, Jira, Confluence) để tự đối chiếu logic. |
| **4** | **Tốn thời gian** | Đọc, đối chiếu chéo và phát hiện các điểm xung đột logic trong tài liệu đặc tả yêu cầu (PRD) quá dài. | Business Analyst (BA), Tech Lead | Mất từ **45-60 phút** cho mỗi lần rà soát thủ công một tài liệu PRD dài 10-15 trang; Dev vẫn hiểu sai luồng. |
| **5** | **Pain từ người khác** | Thành viên dự án bỏ sót hoặc quên thực hiện các đầu việc (Action Items) quan trọng sau cuộc họp. | Project Manager (PM), Thành viên nhóm | Trung bình **20% các task phụ** bị quên hoặc trễ deadline do biên bản họp (Meeting Notes) không được cập nhật kịp thời. |

## **PHASE 2 — TOP 3 PROBLEM CARDS & DRAFT WORKFLOW**

*Mục tiêu: Chọn lọc ra 3 vấn đề có cấu trúc tốt nhất, lập Problem Card chi tiết và phác thảo luồng công việc trước/sau khi có công nghệ can thiệp.*

### **Bảng Chọn Lọc Top 3 Candidates**

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
| :---- | :---- | :---- | :---- |
| **1** | **Tra cứu kiến thức dự án chéo hệ thống bằng GraphRAG** | Workflow tra cứu rõ ràng, baseline thời gian đo lường được bằng con số, painpoint có tác động kinh tế lớn (giải phóng Senior Dev). | Cách tối ưu hóa việc trích xuất thực thể đồ thị (Knowledge Graph) từ các đoạn chat Slack tự nhiên không theo cấu trúc. |
| **2** | **Tự động phản biện và soát lỗi tài liệu Đặc tả (PRD Reviewer)** | Logic quy trình tuyến tính, ranh giới dữ liệu (Boundary) gói gọn trong file văn bản, dễ làm thử nghiệm quy mô nhỏ. | Khó thống nhất một metric chung để đánh giá "chất lượng lập luận" của tài liệu sau khi được AI rà soát. |
| **3** | **Tự động trích xuất Action Items từ cuộc họp Cross-team** | Đầu vào và đầu ra rõ ràng (File ghi âm/Transcript \-\> Bản tóm tắt dạng danh sách hành động có gán tên). | Cách AI phân biệt và gán đúng task khi cuộc họp có nhiều người cùng tranh luận chéo một vấn đề. |

### **CHI TIẾT CÁC PROBLEM CARDS & WORKFLOWS**

#### **PROBLEM CARD \#1 (PITCH CHỦ ĐẠO): GraphRAG Onboarding & Tra cứu kiến thức dự án**

* **Problem 1 câu:** Nhân viên mới mất quá nhiều thời gian (10-15 tiếng/tuần đầu) để tự kết nối thông tin bị phân mảnh giữa PRD, Slack và Jira nhằm hiểu sự phụ thuộc giữa các tính năng, dẫn đến onboarding chậm và làm phiền nhân sự cũ.  
* **Actor:** Newbie Developer hoặc QA mới gia nhập đội ngũ dự án.  
* **Thời điểm / Bối cảnh:** 2 tuần đầu tiên nhận bàn giao dự án hoặc khi được phân công sửa đổi, bảo trì một phân hệ (module) cũ mà người làm trước đã nghỉ việc.  
* **Current Workflow Bottleneck:** Bước **"Tự liên hệ và xâu chuỗi thông tin phi cấu trúc"**. Sau khi đọc tài liệu thô, Newbie phải tự vẽ lại luồng hoặc đi hỏi để biết Module A sửa thì ảnh hưởng đến API hay Database nào. Bước này tốn khoảng **45 phút cho mỗi task** và rất dễ đoán sai logic.  
* **Impact:** Kéo dài thời gian Onboarding; giảm 20% block thời gian tập trung của Senior Dev do phải trả lời câu hỏi lặp lại; tăng tỷ lệ phát sinh lỗi hệ thống (bug) nghiêm trọng khi deploy code mới.  
* **Success Metric:**  
  * Giảm thời gian tự tra cứu thông tin kết nối hệ thống xuống **\< 15 phút/task**.  
  * Giảm **70%** số câu hỏi cơ bản liên quan đến "luồng hệ thống" hướng về phía Senior Dev.  
* **Non-AI alternative:** Tạo một file Master Document (Wiki) hoặc sơ đồ kiến trúc hệ thống cập nhật thủ công.  
  * *Hạn chế:* Tài liệu này sẽ nhanh chóng bị lỗi thời (outdated) ngay khi code hoặc yêu cầu thay đổi sau mỗi Sprint.  
* **AI hypothesis:** Sử dụng công nghệ **GraphRAG** để trích xuất thực thể (Tính năng, API, Database, Người phụ trách) và các mối quan hệ của chúng thành một Đồ thị kiến thức (Knowledge Graph). Khi Newbie hỏi, AI truy vấn đồ thị này để trả ra câu trả lời tổng hợp kèm sơ đồ phụ thuộc trực quan.  
* **Quick gut:** Workflow kết hợp Rule-based Processing.

##### **Draft Current Workflow (Luồng hiện tại \- Chưa có AI)**

**Plaintext**  
\[Nhận Task\]   
    │  
    ▼  
\[Đọc PRD trên Notion\] (Mất 20 phút)  
    │  
    ▼  
\[Tra cứu API Docs trên Confluence\] (Mất 20 phút)  
    │  
    ▼  
\[Đọc các thread thảo luận cũ trên Slack\] (Mất 15 phút)  
    │  
    ▼  
\[BẮT ĐẦU NGHẼN: Tự ngồi xâu chuỗi, đoán sự phụ thuộc chéo hệ thống\] ───► (Tốn 45 phút, rủi ro đoán sai cao)  
    │  
    ▼  
\[Ping hỏi trực tiếp Senior Dev/Tech Lead để xác nhận lại\] ───────► (Làm phiền người cũ, mất 15-20 phút chờ đợi)  
    │  
    ▼  
\[Thực thi viết Code\]

##### **Draft Future Workflow (Luồng tương lai \- Có AI hỗ trợ)**

##### **Plaintext**

\[Nhận Task\]  
    │  
    ▼  
\[Truy vấn Hệ thống GraphRAG Onboarding\]  
    │  
    ├─► (Hệ thống chạy Script tự động quét data từ Notion, Confluence, Slack Decision đã cấu trúc)  
    └─► (AI Engine truy vấn Đồ thị kiến thức & Draft ra câu trả lời tổng hợp)  
    │  
    ▼  
\[AI hiển thị câu trả lời: Luồng logic \+ Các Module ảnh hưởng \+ Đính kèm link trích dẫn (Citations)\]  
    │  
    ▼  
\[HUMAN BOUNDARY: Newbie click kiểm tra link trích dẫn gốc để xác thực thông tin\] (Chỉ mất \< 10 phút)  
    │  
    ▼  
\[Thực thi viết Code\] (Bỏ qua hoàn toàn bước làm phiền Senior Dev trừ trường hợp đặc biệt)

#### **PROBLEM CARD \#2: Hệ thống tự động phản biện tài liệu Đặc tả (PRD Reviewer)**

* **Problem 1 câu:** Business Analyst (BA) mất nhiều thời gian rà soát thủ công các tài liệu đặc tả dài (10-15 trang), dẫn đến việc bỏ sót các điểm xung đột logic nội bộ khiến đội Dev/Design hiểu mập mờ và phải họp giải thích lại nhiều lần.  
* **Actor:** Business Analyst (BA) hoặc Tech Lead đọc duyệt tài liệu.  
* **Thời điểm / Bối cảnh:** Giai đoạn chuẩn bị đóng gói tài liệu Specs (PRD v1.0) trước khi tổ chức buổi họp chuyển giao (Handoff) sang cho đội Dev và Design.  
* **Current Workflow Bottleneck:** Bước **"Đọc đối chiếu chéo giữa các chương mục đan xen"**. Người kiểm duyệt phải căng mắt đọc từ phần mô tả User Flow ở chương 1 để so sánh với danh sách thuộc tính API ở chương 3 xem có khớp số bước xử lý hay không.  
* **Impact:** Mất **45-60 phút** cho mỗi lần rà soát thủ công; đội Dev/Design hiểu sai luồng dẫn đến code lỗi, gây hiện tượng làm lại (Rework) tốn hàng tuần trời.  
* **Success Metric:** Giảm thời gian phát hiện điểm xung đột logic trong tài liệu xuống **\< 10 phút**; giảm **80%** số lần Dev phải dừng lại để làm rõ spec trong quá trình chạy Sprint.  
* **Non-AI alternative:** Thiết lập các Template mẫu viết PRD cực kỳ nghiêm ngặt kèm Checklist rà soát thủ công.  
  * *Hạn chế:* Người viết vẫn có thể quên hoặc bỏ sót lỗi do mệt mỏi khi xử lý khối lượng chữ quá lớn.  
* **AI hypothesis:** Sử dụng một Long-context LLM có năng lực lập luận (Reasoning). Hệ thống đóng vai trò "Phản biện viên độc lập", đọc toàn bộ file PRD, phân tích sự nhất quán logic giữa các phân đoạn và "cắm cờ" cảnh báo tại những vị trí có dấu hiệu mâu thuẫn.  
* **Quick gut:** Workflow hỗ trợ (AI tìm lỗi và cắm cờ, con người chỉnh sửa).

##### **Draft Current/Future Workflow (\#2)**

**Plaintext**  
Current Flow: \[Đọc chương 1\] ──► \[Đọc tiếp đến chương 4\] ──► \[Tự lật ngược lại so sánh bằng trí nhớ\] ──► \[Dễ sót lỗi mâu thuẫn ẩn\]  
Future Flow:  \[Tải PRD lên hệ thống\] ──► \[AI phân tích toàn cục\] ──► \[AI xuất báo cáo cắm cờ: "Mục 1.2 viết Luồng A có 3 bước, nhưng mục 4.1 viết API xử lý 4 bước"\]

#### **PROBLEM CARD \#3: Tự động trích xuất Action Items từ cuộc họp Cross-team**

* **Problem 1 câu:** Nhân sự quản lý mất 30-45 phút sau mỗi cuộc họp cross-team để nghe lại ghi âm và tổng hợp Meeting Notes thủ công, dẫn đến việc ban hành hành động (Action Items) bị chậm và dễ bỏ sót thông tin quan trọng.  
* **Actor:** Thư ký cuộc họp, Project Owner (PO), hoặc Team Lead.  
* **Thời điểm / Bối cảnh:** Ngay sau khi cuộc họp kết thúc, trước khi thông tin bị nguội và đội ngũ bắt đầu bắt tay vào làm việc.  
* **Current Workflow Bottleneck:** Bước **"Nghe lại ghi âm và bóc tách nội dung"**. Con người phải xử lý thông tin phi cấu trúc từ giọng nói, lọc bỏ các đoạn hội thoại thừa để tìm ra kết luận cuối cùng.  
* **Impact:** Tốn khoảng **90-135 phút/tuần** cho một nhân sự; chậm trễ trong việc triển khai task; các thành viên dễ quên các task phụ được giao miệng.  
* **Success Metric:** Giảm thời gian từ lúc họp xong đến lúc ban hành bản tóm tắt xuống **\< 10 phút**; tỷ lệ trích xuất đúng và đủ Action Items đạt **\> 90%**.  
* **Non-AI alternative:** Sử dụng file template sẵn trên Notion/Docs và phân công một người gõ trực tiếp tốc ký trong lúc họp.  
  * *Hạn chế:* Người viết bị phân tâm, không thể tập trung thảo luận sâu hoặc dễ bỏ sót ý khi mọi người tranh luận quá nhanh.  
* **AI hypothesis:** Sử dụng mô hình Speech-to-Text để chuyển âm thanh thành văn bản, kết hợp LLM để phân loại nội dung theo cấu trúc: Chủ đề \-\> Thảo luận \-\> Quyết định \-\> Action Items (kèm người phụ trách và deadline).  
* **Quick gut:** Workflow hỗ trợ (AI xử lý thô và dàn trang, con người biên tập lại).

##### **Draft Current/Future Workflow (\#3)**

**Plaintext**  
Current Flow: \[Họp xong\] ──► \[Mở file ghi âm\] ──► \[Tua đi tua lại để gõ tóm tắt (30-45 phút)\] ──► \[Tag tên thủ công lên Notion\]  
Future Flow:  \[Họp xong\] ──► \[AI Speech-to-Text & Phân tích cấu trúc\] ──► \[AI draft biên bản trong 2 phút\] ──► \[Human review & Click Duyệt\]

### **CHỌN CARD MUỐN PITCH NHẤT VỚI NHÓM**

* **Card tôi muốn pitch nhất:** Card \#1 (Hệ thống hỗ trợ Onboarding & Tra cứu kiến thức dự án bằng GraphRAG).  
* **Vì sao:** Đây là vấn đề có cấu trúc "Nỗi đau lớn \- Impact đo được \- Dữ liệu đầu vào rõ ràng". Nó giải quyết trực tiếp bài toán kinh tế cho đội ngũ kỹ thuật thông qua việc giải phóng thời gian cho các Senior Dev. Hơn nữa, nó thể hiện tư duy chọn giải pháp rất kỹ: Dùng GraphRAG để giải quyết triệt để điểm yếu của RAG thông thường (vốn hay bị lạc lối khi gặp tài liệu phi tuyến tính, phân mảnh).  
* **Câu hỏi tôi muốn nhóm challenge:** *"Làm sao để chúng ta giới hạn phạm vi dữ liệu (Boundary) một cách khôn ngoan trong 4 tiếng của buổi Lab để hệ thống GraphRAG không bị quá tải hoặc sinh chi phí (Cost) quá cao khi index dữ liệu?"*