# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Đặng Quốc Cường
- Mã học viên: 2A202602466
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên ngành AI, tìm hiểu ý tưởng đồ án dùng AI hỗ trợ kiểm tra mũ bảo hộ qua camera.
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - Đọc tài liệu, tìm hướng làm AI phù hợp.
  - Chuẩn bị dữ liệu mẫu, chạy thử model và ghi lại kết quả.
  - Họp nhóm, chia việc và xử lý phần đang vướng.
  - Làm demo, viết báo cáo và chuẩn bị slide.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian | Người phụ trách phải xem camera hoặc đi kiểm tra để tìm người chưa đội mũ bảo hộ. | Người phụ trách an toàn, người làm việc. | Cần bấm giờ [3] ca: thời gian xem camera/đi kiểm tra và số trường hợp phát hiện được. |
| 2 | Lặp lại | Đầu ca và sau giờ nghỉ, người quản lý phải nhắc lại việc đội mũ bảo hộ. | Người quản lý khu vực, người làm việc. | Ghi trong [5] ca: số lần nhắc và số người thiếu mũ. |
| 3 | Pain từ người khác | Người mới hoặc khách không biết khu nào bắt buộc đội mũ nên bị nhắc hoặc phải quay lại lấy mũ. | Người mới, khách, người quản lý. | Hỏi [3–5] người: có từng nhầm khu vực không và biển báo có dễ hiểu không. |
| 4 | AI có thể tốt hơn | Một người không thể xem liên tục nhiều camera nên có thể bỏ qua người thiếu mũ. | Người phụ trách an toàn. | Dùng [200] ảnh/video frame được phép để so sánh thời gian xem thủ công và số lỗi bị bỏ sót. |
| 5 | Tốn thời gian | Ảnh hoặc tin nhắn báo tình huống nguy hiểm qua chat thường thiếu vị trí/thời điểm; người phụ trách phải hỏi lại. | Người phụ trách an toàn, người báo tin. | Xem [10] báo cáo: số báo cáo thiếu thông tin và thời gian hỏi bổ sung. |
| 6 | Lặp lại | Việc nhắc nhở và ghi lại lỗi thiếu mũ làm thủ công nên khó biết lỗi hay xảy ra ở đâu, lúc nào. | Người quản lý khu vực. | Theo dõi [2 tuần]: số lần thiếu mũ theo khu vực và ca làm việc. |
| 7 | Pain từ người khác | Cuối tuần, người phụ trách phải gom ảnh, checklist và ghi chú để làm báo cáo; quản lý khó thấy việc nào cần ưu tiên. | Người phụ trách an toàn, quản lý. | Bấm giờ [2] lần làm báo cáo và đếm số nguồn phải mở. |
| 8 | AI có thể tốt hơn | Khi xem nhiều ảnh về tình huống không an toàn, khó gom các lỗi giống nhau để rút kinh nghiệm. | Người phụ trách an toàn, người đào tạo. | Lấy [50] ảnh được phép; đo thời gian phân loại thủ công theo từng loại lỗi. |
| 9 | Tốn thời gian | Camera mờ, tối hoặc bị che khiến người phụ trách phải xem lại video để xác nhận. | Người phụ trách an toàn. | Ghi [50] frame: số frame không thể kết luận ngay và thời gian xem lại. |
| 10 | Lặp lại | Trước khi vào khu vực có rủi ro, người quản lý kiểm tra mũ nhưng bằng chứng kiểm tra lưu ở nhiều nơi. | Người quản lý khu vực, bộ phận kiểm tra. | Theo dõi [1] buổi kiểm tra: số bước, thời gian và nơi lưu checklist/ảnh. |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Tôi là sinh viên AI tìm hiểu bài toán an toàn lao động. Hãy gợi ý problem có actor, workflow và cách đo; AI chỉ hỗ trợ cảnh báo, không tự phạt hay tự quyết định.
- Ý dùng được: Tách việc phòng ngừa bằng biển báo/checklist với việc AI có thể hỗ trợ là xem ảnh và tóm tắt thông tin.
- Ý bỏ vì không phải pain thật: Nhận diện khuôn mặt, tự mở cổng hoặc tự phạt người làm việc vì vượt phạm vi đồ án và rủi ro cao.

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Kiểm tra người thiếu mũ bảo hộ qua camera | Actor và điểm nghẽn rõ; AI có thể hỗ trợ một bước nhỏ; có thể làm thử với ảnh/video được phép. | Có quyền dùng ảnh/camera không; camera có đủ sáng và đúng góc không. |
| 2 | Nhận báo tin về tình huống nguy hiểm qua chat | Cần xử lý nhanh; có cách không dùng AI để so sánh; dữ liệu đầu vào rõ. | Hiện mọi người báo tin bằng kênh nào và ai quyết định mức độ khẩn. |
| 3 | Làm báo cáo an toàn cuối tuần | Có thể đo thời gian; AI chỉ làm bản nháp và người phụ trách vẫn kiểm. | Có thể form và bảng tổng hợp đã đủ, chưa cần AI. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Cảnh báo người thiếu mũ bảo hộ từ camera

```text
Problem 1 câu:
Người phụ trách an toàn phải tự xem camera hoặc đi kiểm tra để phát hiện người chưa đội mũ bảo hộ; khi có nhiều khu vực, việc quan sát không liên tục có thể phát hiện chậm.

Actor:
Người phụ trách an toàn kiểm tra; người quản lý khu vực xử lý tại chỗ.

Thời điểm / bối cảnh:
Trong ca làm việc, nhất là đầu ca, sau giờ nghỉ và lúc có nhiều người ra vào.

Current workflow 3-7 bước:
1. Mở từng camera hoặc đi kiểm tra trực tiếp.
2. Quan sát xem người trong khu vực có đội mũ không.
3. Nếu chưa rõ, xem lại video hoặc đến tận nơi.
4. Nhắc người quản lý khu vực xử lý.
5. Ghi lại nếu cần.

Bottleneck:
Bước 1-3: phải xem nhiều hình ảnh và xem lại khi ảnh tối, mờ hoặc bị che.

Impact:
Nguy cơ có thể bị phát hiện muộn; người phụ trách tốn thời gian xem camera thay vì kiểm tra trực tiếp chỗ cần thiết.

Success metric:
Giảm ít nhất 50% thời gian xem camera sau khi có baseline; trong 100 cảnh báo thử nghiệm, ít nhất 80 cảnh báo đúng; mọi cảnh báo phải do người phụ trách xác nhận trước khi nhắc nhở ai.

Non-AI alternative:
Biển báo rõ ở lối vào, phát mũ tại cổng, checklist đầu ca và kiểm tra ngẫu nhiên. Đây là việc cần làm dù có AI hay không.

AI hypothesis:
AI đánh dấu ảnh có thể có người chưa đội mũ và gửi ảnh kèm thời gian, khu vực cho người phụ trách. AI không nhận diện khuôn mặt, không kết luận vi phạm và không tự phạt.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — [cần đo, ví dụ 60–120 phút/ngày]

[Mở camera hoặc đi kiểm tra]
→ [Quan sát bằng mắt]
→ [Xem lại video / đến tận nơi]  <-- bottleneck
→ [Nhắc người quản lý]
→ [Ghi lại]

FUTURE STATE — mục tiêu giảm ít nhất 50% thời gian xem camera

[Chọn camera và khu vực được phép]
→ [AI đánh dấu ảnh cần chú ý]
→ [Người phụ trách xem và xác nhận]  <-- human boundary
→ [Người quản lý xử lý + ghi lại]

Fallback: nếu AI sai thì quay lại kiểm tra trực tiếp và dùng checklist; không xử lý ai chỉ dựa vào cảnh báo AI.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Nhận báo tin về tình huống nguy hiểm qua chat

```text
Problem 1 câu:
Người phụ trách nhận ảnh và tin nhắn báo tình huống nguy hiểm qua chat, nhưng thường thiếu vị trí hoặc thời điểm nên phải hỏi lại trước khi nhờ người xử lý.

Actor:
Người phụ trách an toàn nhận tin; người quản lý khu vực xử lý; người làm việc gửi tin.

Thời điểm / bối cảnh:
Khi có tình huống có thể gây tai nạn nhưng chưa gây tai nạn.

Current workflow 3-7 bước:
1. Có người gửi ảnh hoặc tin nhắn.
2. Người phụ trách đọc và tìm thông tin cần thiết.
3. Hỏi lại nếu thiếu vị trí, thời điểm hoặc ảnh rõ.
4. Gọi đúng người quản lý để xử lý.
5. Theo dõi xem việc đã được xử lý chưa.

Bottleneck:
Bước 2-3: báo tin tự do nên thiếu thông tin; việc hỏi lại làm chậm xử lý.

Impact:
Nguy cơ tồn tại lâu hơn; người phụ trách tốn thời gian nhắn tin qua lại; thông tin không đồng đều nên khó rút kinh nghiệm.

Success metric:
Giảm thời gian từ lúc nhận tin đến lúc có người xử lý xuống dưới 15 phút sau khi đo baseline; ít nhất 80% báo tin có đủ vị trí, thời điểm và loại nguy cơ ngay lần đầu.

Non-AI alternative:
Dùng form đơn giản hoặc QR theo khu vực, bắt buộc điền vị trí, thời điểm và ảnh. Đây là cách cần thử trước.

AI hypothesis:
AI tóm tắt thông tin đã có và nhắc phần còn thiếu. Người phụ trách kiểm lại, chọn mức độ khẩn và giao người xử lý.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[x] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — [cần đo, ví dụ 15–30 phút/báo tin]

[Gửi ảnh / tin nhắn]
→ [Đọc thông tin]
→ [Hỏi lại]  <-- bottleneck
→ [Gọi người xử lý]
→ [Theo dõi kết quả]

FUTURE STATE — mục tiêu dưới 15 phút/báo tin

[Dùng form có sẵn]
→ [AI tóm tắt và nhắc chỗ thiếu]
→ [Người phụ trách kiểm và giao xử lý]  <-- human boundary
→ [Cập nhật kết quả]

Fallback: thiếu thông tin hoặc AI tóm tắt sai thì gọi xác minh và điền form thủ công; AI không tự tạo báo tin khẩn hoặc tự đóng việc.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Làm báo cáo an toàn cuối tuần

```text
Problem 1 câu:
Cuối tuần, người phụ trách phải gom checklist, ảnh và ghi chú từ nhiều nơi để làm báo cáo; quản lý khó thấy khu vực hay lỗi nào cần ưu tiên xử lý.

Actor:
Người phụ trách an toàn làm báo cáo; quản lý dùng báo cáo để quyết định việc cần làm tiếp.

Thời điểm / bối cảnh:
Cuối tuần hoặc trước buổi họp định kỳ.

Current workflow 3-7 bước:
1. Mở checklist, ảnh và ghi chú từng khu vực.
2. Bỏ dữ liệu trùng, tìm phần thiếu.
3. Đếm lỗi theo loại, khu vực và thời điểm.
4. Chọn ảnh minh chứng, viết báo cáo.
5. Quản lý hỏi lại và chốt việc ưu tiên.

Bottleneck:
Bước 2-4: gom nhiều nguồn rồi biến thành báo cáo ngắn, có số liệu và ảnh minh chứng.

Impact:
Mất thời gian làm báo cáo; việc cần ưu tiên có thể dựa vào cảm nhận thay vì số liệu rõ ràng.

Success metric:
Giảm thời gian làm báo cáo xuống dưới 30 phút sau khi đo baseline; mọi số trong báo cáo tìm lại được nguồn; báo cáo chỉ ra 1-3 việc ưu tiên có bằng chứng.

Non-AI alternative:
Dùng cùng một form/checklist và một bảng tổng hợp chung. Nếu bảng đã trả lời được câu hỏi thì không cần AI.

AI hypothesis:
Sau khi dữ liệu được điền theo cùng một form, AI làm bản nháp về xu hướng, điểm bất thường và phần dữ liệu thiếu. Người phụ trách kiểm số, sửa nhận xét; quản lý mới chốt việc cần làm.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — [cần đo, ví dụ 60–90 phút/báo cáo]

[Mở checklist / ảnh / ghi chú]
→ [Làm sạch dữ liệu]
→ [Đếm theo loại và khu vực]  <-- bottleneck
→ [Viết báo cáo]
→ [Quản lý review]

FUTURE STATE — mục tiêu dưới 30 phút

[Dùng form chung]
→ [Tổng hợp bảng số liệu]
→ [AI làm bản nháp có link nguồn]
→ [Người phụ trách kiểm + quản lý chốt việc]  <-- human boundary

Fallback: dữ liệu thiếu hoặc AI nói sai thì dùng bảng tổng hợp để viết báo cáo thủ công; không ra quyết định chỉ từ bản nháp AI.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Card #1 — Cảnh báo người thiếu mũ bảo hộ từ camera.
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Vấn đề này liên quan trực tiếp đến an toàn. Người phụ trách đang phải xem camera hoặc đi kiểm tra bằng tay; khi có nhiều khu vực, họ không thể quan sát liên tục. Pilot nhỏ có thể chỉ dùng một camera được phép, chỉ kiểm tra mũ bảo hộ và để AI gửi cảnh báo cho người phụ trách xem lại.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Biển báo, checklist và kiểm tra đầu ca có giải được phần lớn vấn đề chưa, hay camera AI thực sự giúp phát hiện nhanh hơn?
2. Nếu ảnh tối, mờ hoặc bị che, nhóm sẽ đo mức độ bỏ sót thế nào để không tin AI quá mức?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Một ảnh trông như không có mũ chưa chắc là vi phạm; người đó có thể ở ngoài khu bắt buộc hoặc ảnh không rõ.
- Tôi sửa gì: AI chỉ cảnh báo kèm khu vực/thời gian; người phụ trách xem lại trước khi xử lý; khi AI không chắc thì quay về kiểm tra trực tiếp.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
