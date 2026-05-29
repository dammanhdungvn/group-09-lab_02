Dưới đây là nội dung hoàn chỉnh cho file Reflection cá nhân (03-individual-reflection/), được thiết kế dựa trên trải nghiệm thực tế tại buổi Lab.  
Nội dung phản ánh đúng tình huống: **Ý tưởng GraphRAG của bạn không được nhóm chọn đi tiếp**, nhưng bạn đã đóng góp tích cực vào việc xây dựng giải pháp mới của nhóm, tham gia phản biện chéo (QA) và chấm điểm cho các đội khác theo đúng tinh thần tài liệu Day02-AI-Product-Labs/01-worksheet.md at main · VinUni-AI20k/Day02-AI-Product-Labs · GitHub.

# **BẢN NỘP BÀI CÁ NHÂN: PHASE 7 — INDIVIDUAL REFLECTION**

**Thành phần thư mục:** 03-individual-reflection/  
**Học viên:** Lê Bá Chiến \-2A202600755 

## **1\. TÔI ĐÃ THAM GIA VÀO PHẦN NÀO?**

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
| :---- | :---- | :---- |
| **Scan cá nhân** | Quét rộng 5 vấn đề thực tế, chuẩn hóa số liệu Baseline bài toán GraphRAG Onboarding. | Đóng góp một bài toán có cấu trúc rõ ràng làm nguyên liệu chất lượng cho vòng thảo luận nhóm. |
| **Pitch Problem Card** | Thuyết trình bảo vệ ý tưởng GraphRAG trong 2 phút, nhấn mạnh điểm nghẽn tốn 10-15 tiếng/tuần đầu của Newbie. | Giúp nhóm hiểu sâu về cơ chế bóc tách thông tin phi tuyến tính và ranh giới dữ liệu (Data Boundary). |
| **Chọn candidate problem** | Cùng nhóm tranh luận và chấm điểm đồng thuận. Phương án GraphRAG của tôi **không được chọn** do độ phức tạp dữ liệu quá cao, không khả thi để làm sạch và chạy thử trong 4 tiếng của buổi Lab. | Nhóm thống nhất chuyển sang bài toán tối ưu khác có tính khả thi cao hơn trong phòng Lab, tối ưu hóa nguồn lực của đội. |
| **Validation / Research & Workflow nhóm** | Sau khi ý tưởng cá nhân bị loại, tôi lập tức pivot sang hỗ trợ nhóm vẽ Workflow (Trước/Sau) và làm tài liệu nghiên cứu giải pháp cho bài toán chung được chọn. | Đảm bảo luồng quy trình của nhóm bám sát nguyên tắc "Problem first", chỉ rõ chính xác bước nghẽn cần AI can thiệp. |
| **Tương tác chéo & Trả lời câu hỏi nhóm khác** | Đại diện nhóm đứng lên trả lời, phản biện các câu hỏi hóc búa từ các nhóm khác trong phiên QA chéo về Problem Statement của nhóm mình. | Bảo vệ thành công tính hợp lý trong việc chọn ranh giới (Boundary) và mức độ can thiệp AI (Workflow chứ không lạm dụng Agent) của nhóm. |
| **Chấm điểm nhóm khác** | Sử dụng Biểu mẫu chấm điểm nhanh (Score để đồng thuận) để đánh giá các đội khác dựa trên 3 tiêu chí: *Impact đo được*, *Làm được trong lab*, và *So sánh R/W/A*. | Giúp đưa ra những góc nhìn khách quan, công tâm cho bài làm của các đội bạn, đồng thời kéo về những bài học hay cho chính mình. |

## **2\. BẢNG DÙNG AI TRONG REFLECTION**

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
| :---- | :---- | :---- | :---- | :---- |
| **Scan & Problem Card** | Gợi ý cấu trúc Problem Card và tìm thêm các góc khuất của lăng kính "Pain từ người khác". | Giúp diễn đạt gãy gọn các trường thông tin phức tạp như AI Hypothesis. | AI có xu hướng bốc thuốc, tự bịa ra các con số thống kê chung chung không có căn cứ thực tế. | Tôi xóa bỏ toàn bộ số liệu do AI tự sinh, thay bằng trải nghiệm và con số Baseline thật từ dự án tôi từng tham gia. |
| **Workflow** | Chuyển đổi các mô tả quy trình dạng text thô của nhóm sang định dạng sơ đồ Mermaid. | Tiết kiệm thời gian gõ cú pháp và dàn trang sơ đồ. | AI tự động gộp bước "AI xử lý" và "Con người kiểm tra" làm một, vi phạm quy tắc Human-in-the-loop. | Tôi tách đôi bước này ra, vẽ lại ranh giới kiểm soát (Human Boundary) để con người giữ quyền quyết định cuối cùng. |
| **Decision (Rule/Workflow/Agent)** | Tham khảo ma trận độ mơ hồ và độ phức tạp để phân loại bài toán. | Hệ thống hóa nhanh các định nghĩa thế nào là độ mơ hồ cao/thấp. | AI liên tục khuyên nhóm nên nâng cấp lên hệ thống "Autonomous Agent" cho ngầu dù không cần thiết. | Tôi phản biện lại AI, hạ mức giải pháp xuống Workflow phối hợp Rule-based để kiểm soát rủi ro ảo tưởng (Hallucination). |

## **3\. REFLECTION CÂU HỎI MỞ**

### **Tôi học được gì khi nghe top 3 problems của các bạn khác và khi chấm điểm cho các đội bạn?**

Khi nghe và trực tiếp chấm điểm cho các nhóm khác dựa trên 3 tiêu chí (*Impact*, *Làm trong lab*, *Biết chọn R/W/A*), tôi nhận ra một bài học rất lớn: **Ý tưởng hay nhất không phải là ý tưởng dùng công nghệ tối tân nhất, mà là ý tưởng có lăng kính thực nghiệm rõ ràng nhất.**  
Nhiều đội có ý tưởng rất vĩ mô nhưng khi bị chất vấn đến phần "Làm trong lab" và "Bằng chứng thật (Evidence)" thì hoàn toàn bị vỡ trận vì dữ liệu quá mơ hồ. Việc chấm điểm đội bạn giúp tôi nhìn lại bài toán của nhóm mình, nhận ra lý do vì sao nhóm quyết định loại bỏ ý tưởng GraphRAG ban đầu của tôi là hoàn toàn chính xác. GraphRAG rất tốt và có Impact lớn, nhưng trong phạm vi 4 tiếng của buổi Lab, nó là một "gánh nặng" bất khả thi về mặt chuẩn bị dữ liệu đồ thị.

### **Nhóm có lúc nào bị solution-first (nghĩ về giải pháp trước) không?**

Có. Ngay từ đầu, khi tôi pitch ý tưởng GraphRAG, cả nhóm đã bị cuốn theo sự "băng sương" của công nghệ này. Mọi người lập tức bàn về việc dùng Framework nào (Microsoft GraphRAG hay LlamaIndex), dùng Neo4j hay Vector DB để lưu trữ.  
Tuy nhiên, nhờ nguyên tắc nghiêm ngặt của Lab: *"Nếu chưa vẽ được workflow và chỉ ra bước nghẽn, chưa được chọn công nghệ"*, nhóm đã phải phanh gấp. Khi đặt bút vẽ luồng công việc hiện tại, chúng tôi nhận ra điểm nghẽn lớn nhất của nhân sự đôi khi chỉ cần một bộ template tốt kết hợp với Rule-based Automation là giải quyết được 70% vấn đề, chưa cần dùng đến GraphRAG phức tạp. Điều này giúp nhóm tỉnh ngộ và quay về đúng mạch tư duy "Problem-first".

### **Tôi có thay đổi ý kiến sau khi bị challenge không?**

Tôi hoàn toàn thay đổi. Ban đầu, tôi khá nuối tiếc khi giải pháp GraphRAG của mình không được chọn đi tiếp. Nhưng sau khi bị cả nhóm và các đội bạn challenge về mặt "Data Access Permission" (Làm sao quét được hội thoại Slack nội bộ mà không vi phạm bảo mật công ty?) và "Time-boxing" (Làm sao dựng được Knowledge Graph hoàn chỉnh trong vài tiếng?), tôi nhận ra mình đã bị rơi vào cái bẫy "AI-first" — cố tìm một bài toán để nhét công nghệ mình thích vào.  
Tôi học được cách chấp nhận từ bỏ giải pháp cá nhân để đồng thuận với nhóm, tập trung nguồn lực vào một bài toán có đầu vào sạch, dễ đo lường và mang lại giá trị thực tế ngay lập tức.

### **Điều khó nhất khi viết Problem Statement là gì?**

Điều khó nhất chính là việc đóng khung **Boundary (Ranh giới)** và **Success Metric**. Rất dễ để viết một câu hứa hẹn chung chung như "hệ thống giúp nhân sự làm việc nhanh hơn và thông minh hơn". Nhưng để ép nó vào một khuôn khổ: *AI chỉ được phép làm gì, không được phép làm gì, nếu AI sai thì hệ thống quay về luồng dự phòng (Rollback Plan) như thế nào* là một cực hình về mặt tư duy. Nó đòi hỏi chúng tôi phải thực sự hiểu sâu sắc quy trình vận hành của con người trước khi nghĩ đến việc đưa AI vào.

### **Nếu làm lại, tôi sẽ challenge nhóm hoặc bản thân mạnh hơn ở điểm nào?**

Nếu được làm lại, tôi sẽ challenge bản thân ngay từ Phase 1 ở cột **Dấu hiệu thật (Evidence)**. Tôi sẽ tự đặt câu hỏi khắt khe hơn: *"Nếu không có AI, tôi dùng cơm hoặc dùng code chạy bằng cơm (Rule) thì có giải quyết được triệt để không?"*. Nếu câu trả lời là Có, tôi sẽ tự loại bài toán đó ngay từ vòng gửi xe chứ không đợi đến khi lên nhóm mới bị mọi người challenge. Điều này sẽ giúp tiết kiệm tối đa thời gian phân kỳ và đẩy nhanh tiến độ hội tụ của cả đội.