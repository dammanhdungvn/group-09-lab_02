# 03 — Individual Reflection

## Đóng góp của học viên trong nhóm

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

## Bảng sử dụng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm các lăng kính từ trải nghiệm sinh viên. | Mở rộng ra các vấn đề về citation, dịch thuật chuyên ngành. | Một số gợi ý quá chung chung (ví dụ: "quản lý thời gian học tập"). | Bỏ qua các ý chung chung, chỉ giữ lại các vấn đề có dấu hiệu rõ như định dạng APA. |
| Problem Card | Hỗ trợ cấu trúc chi tiết của card số 1. | Sắp xếp thông tin mạch lạc, rõ ràng. | AI đề xuất success metric chung chung như "làm nhanh hơn". | Sửa thành metric định lượng cụ thể: "giảm từ 15 tiếng xuống dưới 4 tiếng". |
| Workflow | Sinh mã ASCII cho sơ đồ Before/After. | Tiết kiệm thời gian căn chỉnh sơ đồ chữ. | AI gộp bước viết nội dung và slide thành một bước AI duy nhất. | Tách ra làm hai bước riêng vì sinh viên cần review báo cáo trước rồi mới làm slide. |
| Research | Tìm kiếm các thư viện hỗ trợ sinh slide tự động từ Markdown. | Gợi ý thư viện Marp và python-pptx rất hữu ích. | Đưa ra thông tin tính năng của một số tool trả phí không rõ nguồn gốc. | Chỉ giữ lại Marp vì đây là công cụ mã nguồn mở dễ tích hợp vào workflow. |
| Problem Statement | Phản biện tính chặt chẽ của các trường thông tin. | Chỉ ra rằng phần "Boundary" ban đầu còn quá lỏng lẻo. | Đề xuất boundary mang tính kỹ thuật sâu không cần thiết. | Sửa lại boundary tập trung vào khía cạnh sản phẩm: "AI không tự ý nộp bài, không tự bịa số liệu nghiên cứu". |
| Rule / Workflow / Agent | Đối chiếu ưu nhược điểm của 3 giải pháp. | Đưa ra các rủi ro cụ thể của từng phương án. | Gợi ý chọn Agent để hệ thống nghe có vẻ "hiện đại" hơn. | Quyết định chọn Workflow vì tính khả thi cao và dễ kiểm soát lỗi đối với sinh viên. |
| Decision | Lập các điều kiện để quyết định Go/No-Go. | Gợi ý bộ khung câu hỏi tự kiểm tra rất logic. | Các điều kiện rollback còn mơ hồ, thiếu định lượng. | Bổ sung điều kiện rollback định lượng: "nếu phải sửa lại >70% nội dung draft trong 2 tuần". |

## Phản tư cá nhân

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

**Bài học rút ra:**  
Buổi lab hôm nay giúp tôi hiểu rõ rằng AI không phải là "chìa khóa vạn năng". Việc xác định đúng vấn đề, hiểu rõ workflow hiện tại và điểm nghẽn thực sự quan trọng hơn nhiều so với việc cố gắng áp dụng các công nghệ phức tạp như Agent. Khi làm việc nhóm, việc lắng nghe challenge từ các bạn khác giúp tôi nhìn nhận vấn đề khách quan hơn, không bị thiên lệch bởi trải nghiệm cá nhân của mình. Đối với bài toán viết báo cáo và làm slide, việc chọn mức độ Workflow (AI hỗ trợ draft, con người kiểm soát chất lượng) là một quyết định cân bằng giữa tính khả thi kỹ thuật và trải nghiệm người dùng.
