# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Đặng Quốc Cường
- Mã học viên: 2A202602466
- Nhóm: Nhóm 5 thành viên
- Candidate problem nhóm chọn: VinWonders — dự báo thời gian chờ và điều phối luồng khách bằng vé ảo tại các trò chơi đông khách.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Đưa ra 3 candidate về an toàn: phát hiện người thiếu mũ bảo hộ, báo tin nguy hiểm thiếu vị trí/thời điểm và báo cáo an toàn cuối tuần. | Nhóm có thêm góc nhìn về camera/cảnh báo; ba ý này được đưa vào cụm A và cụm C khi gom 15 candidate. |
| Pitch Problem Card | Trình bày actor, workflow và điểm còn thiếu dữ liệu của 3 candidate an toàn. | Nhóm thấy rõ các bài an toàn có impact lớn nhưng chưa có baseline hay quyền truy cập dữ liệu để thử trong lab. |
| Challenge bài của bạn khác | Nêu rủi ro khi dùng AI cho các cảnh báo an toàn: nếu bỏ sót một ca thật thì hậu quả cao, nên không thể chỉ nhìn vào việc giảm báo giả. | Nhóm không chọn cụm cảnh báo an toàn làm bài chính vì chưa đủ dữ liệu để lập luận nghiêm túc về đánh đổi giữa báo giả và bỏ sót. |
| Gom trùng / cluster | Cùng nhóm gom 15 candidate thành 4 cụm; xác định ba candidate của mình liên quan đến cụm cảnh báo/camera và cụm gom thông tin. | Giúp nhóm thấy nhiều bài trong cụm C có thể được giải một phần bằng form, rule hoặc template trước khi cần AI. |
| Chọn candidate problem | Tham gia chấm shortlist và đồng ý chọn VinWonders với điều kiện không được kết luận Go khi chưa có bằng chứng. | Nhóm chọn bài có impact và giá trị học tập cao, nhưng giữ quyết định cuối là Not Yet thay vì hứa triển khai quá sớm. |
| Validation / research | Tham gia phần research về pattern hiển thị thời gian chờ và vé ảo; dùng các nguồn như Disney Virtual Queue, Lightning Lane và Queue-Times để so sánh giải pháp. | Nhóm nhận ra bảng giờ chờ nhập tay là phương án non-AI cần thử trước; Queue-Times là nguồn dữ liệu công khai để kiểm giả thuyết dự báo. |
| Workflow nhóm | Góp phần làm rõ workflow hiện tại của khách: không biết thời gian chờ → đi tới trò chơi → mới thấy hàng → phải chờ; và workflow tương lai có bước nhân viên xác nhận. | Workflow thể hiện rõ AI chỉ dự báo thời gian chờ; nhân viên vẫn có quyền ghi đè và vận hành trò chơi. |
| Problem Statement | Cùng nhóm tách metric AI chịu trách nhiệm (sai số dự báo) khỏi kết quả vận hành (thời gian chờ), đồng thời thêm boundary không nhận diện khuôn mặt hay quyết định dừng/chạy trò chơi. | Problem Statement v1 bớt hứa quá mức và nêu rõ phần AI không thể tự tạo thêm công suất cho trò chơi. |
| Rule / Workflow / Agent | Lập luận rằng Agent tự điều phối toàn công viên là quá rủi ro; Rule nhập thời gian chờ bằng tay là lớp nền cần có; Workflow phù hợp hơn khi có đủ dữ liệu. | Nhóm chọn Workflow trên nền Rule, không chọn Agent. |
| Decision | Ủng hộ quyết định Not Yet vì baseline 30-45 phút mới là ước lượng, chưa có data vận hành và chưa có người owner thật. | Nhóm có kế hoạch validate cụ thể thay vì kết luận Go chỉ vì ý tưởng nghe hấp dẫn. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là đưa cụm bài toán an toàn vào phần hội tụ và cùng nhóm giữ lập luận về boundary: AI không được tự quyết định trong các tình huống có rủi ro cao. Ở bài VinWonders, tôi đóng góp vào cách nhìn rằng phải thử lớp Rule và đo baseline trước, rồi mới bàn đến phần AI dự báo.

```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm problem theo 4 lăng kính. | Giúp mở rộng từ một ý tưởng camera sang các workflow có actor và cách đo. | AI có thể đưa ra nhiều bài nghe hợp lý nhưng không có dữ liệu thật. | Chỉ giữ các ý có actor, workflow và kế hoạch lấy baseline; bỏ ý nhận diện khuôn mặt/tự xử phạt. |
| Problem Card | Không dùng AI để tự chọn bài; tự viết actor, workflow và điểm thiếu bằng chứng cho 3 candidate an toàn. | Giữ Problem Card sát với pain và rủi ro thật hơn. | AI dễ gợi ý solution trước khi làm rõ người dùng và số đo. | Đặt Non-AI alternative và câu hỏi về data access trước khi chọn mức AI. |
| Workflow | Dùng AI để soi xem workflow có thiếu bước kiểm tra của con người không. | Nhắc nhóm nêu rõ nhân viên điều phối có quyền xác nhận, ghi đè hoặc tắt hiển thị. | AI không biết quy trình vận hành thật của VinWonders. | Chỉ dùng AI để phản biện cấu trúc; không coi workflow AI gợi ý là sự thật. |
| Research | Dùng AI gợi ý từ khóa/tên giải pháp, sau đó tự mở và kiểm các link chính thức. | Giúp tìm Disney Virtual Queue, Lightning Lane và Queue-Times nhanh hơn. | AI có thể làm quá vai trò của dự báo hoặc đưa claim không có nguồn. | Chỉ giữ link kiểm được, đồng thời ghi rõ dữ liệu công viên nước ngoài chưa đại diện cho VinWonders. |
| Problem Statement | Dùng AI phản biện v0. | AI chỉ ra baseline 30-45 phút chưa được đo, impact còn cảm tính và cần tách metric AI với metric vận hành. | AI không thể tự xác nhận baseline hay quyền truy cập dữ liệu. | Sửa v1: ghi rõ baseline là ước lượng, thêm boundary và quyết định Not Yet. |
| Rule / Workflow / Agent | Dùng AI để hỏi ngược xem có thật sự cần Agent không. | Làm rõ các bước đi theo thứ tự cố định nên chưa cần Agent. | AI có thể đề xuất Agent quá sớm vì mô tả bài toán nghe phức tạp. | Chọn Workflow trên nền Rule, giữ nhân viên là người quyết định vận hành. |
| Decision | Không dùng AI để chốt thay nhóm. | Nhóm tự đối chiếu evidence, data access, owner và phương án Rule. | AI không thể thay phỏng vấn khách hay xác nhận từ người vận hành. | Chốt Not Yet và lập kế hoạch validate trước khi nói đến pilot. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe 15 candidate của các bạn, tôi nhận ra bài toán nghe “AI” nhất chưa chắc là bài tốt nhất; bài tốt phải có actor, workflow và bằng chứng. Ba candidate an toàn của tôi có impact cao, nhưng lại thiếu baseline và dữ liệu thật, nên nhóm không chọn chúng làm bài chính. Điều này giúp tôi bớt suy nghĩ theo kiểu cứ có camera là phải làm AI phát hiện. Nhóm chọn VinWonders dù điểm số thấp hơn hai candidate khác, và điểm tôi học được là quyết định đó chỉ hợp lý khi đi kèm điều kiện Not Yet rất rõ. Khó nhất khi viết Problem Statement là tách điều AI thực sự chịu trách nhiệm — sai số dự báo thời gian chờ — với điều hệ thống không tự làm được là tăng công suất trò chơi. Tôi cũng hiểu rằng một bảng thời gian chờ do nhân viên nhập tay có thể giải phần lớn pain trước khi cần mô hình dự báo. Khi so sánh Rule, Workflow và Agent, tôi thấy Agent không phải lựa chọn mặc định: các bước ở đây đã biết trước và quyền vận hành cần ở con người. Đóng góp rõ nhất của tôi là tham gia phần workflow và research, giúp làm rõ boundary như không nhận diện khuôn mặt, không tự dừng/chạy trò chơi và phải có người ghi đè. Nếu làm lại, tôi sẽ ưu tiên khảo sát khách và đo thời gian chờ thật sớm hơn, thay vì để cả nhóm tranh luận lâu dựa trên một con số ước lượng. Tôi cũng sẽ challenge mạnh hơn câu hỏi: nếu Rule nhập giờ chờ thủ công đã đủ tốt, AI còn tạo thêm giá trị nào có thể đo được?



```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

