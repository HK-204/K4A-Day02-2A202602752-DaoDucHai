# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Đào Đức Hải
- Mã học viên: 2A202602752
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): intern Web Manager tại 1 công ty chuyên về làm web, marketing có quy mô khoảng 100 người. 
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): 
+ Viết content SEO cho các trang web
+ Quản lý các thông số website, lưu lượng truy cập
+ Lên ý tưởng, lên khung, tạo hình ảnh cho trang web và các thành phần bên trong
+ Xây dựng và hoàn thiện hiệu ứng, giao diện web bằng CSS
+ Quản lý nhóm, phân nhóm công việc dựa trên nội dung

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|Lăng kính|Problem quan sát được|Ai chịu ảnh hưởng?|Dấu hiệu thật|
| 1 |Lặp lại |Lên ý tưởng về chủ đề, nội dung và hình ảnh cho các bài viết SEO theo web yêu cầu |web manager, designer, team member |mất khoảng 120 phút/tuần |
| 2 |Lặp lại |Tổng hợp lại các dữ liệu, thông số bằng google search console và thực hiện phân tích |web manager |45 phút/tuần |
| 3 |AI có thể làm tốt hơn |Lên ý tưởng về khung, về bảng màu dành cho trang web theo chủ đề của yêu cầu |web manager, designer |1 tiếng/web |
| 4 |Lặp lại |Thực hiện bản demo web theo các ý tưởng đã được lập ra từ trước |cả team |6 tiếng/web |
| 5 |Lặp lại |Đưa web lên chính thức, xây dựng database hoàn chỉnh cho web |web manager, technical manager |1 tiếng/web |
| 6 |AI có thể làm tốt hơn |Viết các bài viết SEO giới thiệu về web, các dịch vụ liên quan của web, quảng cáo web |cả team |4 ngày/web |
| 7 |AI có thể làm tốt hơn |Tổng hợp lại dữ liệu của các bài SEO đã viết theo web |web manager |30-60 phút/web |
| 8 |Tốn thời gian |Tổng hợp lại thông số các web trong tuần, khả năng của team trong tuần qua |web manager |60 phút/tuần |
| 9 |Pain từ người khác |designer phải hỏi và hướng lại các phần hình ảnh cần tinh chỉnh của team |designer, web manager, team member |10-15 phút/lần |
| 10 |Pain từ người khác |technical manager rà soát lại và hướng dẫn tinh chỉnh cho team về web để đúng theo yêu cầu |technical manager, cả team |30 phút/lần |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|Rank|Problem|Vì sao chọn|Điều còn chưa chắc|
| 1 |Viết các bài viết SEO giới thiệu về web, các dịch vụ liên quan của web |Pain lớn nhất (tốn 4 ngày/web). AI đặc biệt mạnh ở mảng xử lý ngôn ngữ và tạo văn bản |Bài viết AI tạo ra có đủ độ tự nhiên và tối ưu chuẩn SEO 100% như người viết hay không? |
| 2 |Lên ý tưởng về chủ đề, nội dung và hình ảnh cho bài viết SEO |Việc lặp lại hàng tuần (120 phút). Thường xuyên bị bí ý tưởng. AI brainstorm rất nhanh |Ý tưởng của AI có bám sát đúng insight (nhu cầu) của ngành hàng/khách hàng thực tế không? |
| 3 |Tổng hợp lại thông số các web trong tuần, khả năng của team |Tính khuôn mẫu cao, lặp lại hàng tuần (60 phút). Dữ liệu có cấu trúc dễ xử lý |Việc cấp quyền (API) cho AI truy cập vào các dashboard dữ liệu nội bộ có dễ dàng và bảo mật không? |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Tên problem]

```text
Problem 1 câu: Cả team mất đến 4 ngày để hoàn thành việc viết các bài chuẩn SEO, bài giới thiệu dịch vụ và quảng cáo mỗi khi cần đẩy nội dung cho một website mới

Actor: Web manager, Team member (Content Creator)

Thời điểm / bối cảnh: Khi website chuẩn bị go-live hoặc cần đẩy mạnh chiến dịch SEO mới

Current workflow 3-7 bước:
1. Nhận yêu cầu và bộ từ khóa (keywords)
2. Nghiên cứu tài liệu và bài của đối thủ
3. Lập dàn ý (Outline) cho các bài viết
4. Viết nội dung chi tiết
5. Kiểm tra chính tả, format lại cho chuẩn SEO
6. Đăng bài lên website

Bottleneck: Bước 4 — Viết nội dung chi tiết (thường chiếm 2-3 ngày vì cần viết rất nhiều bài)

Impact: Làm chậm tiến độ ra mắt nội dung của web. Team bị quá tải, không có thời gian làm các web khác (tốn 4 ngày/web)

Success metric: Giảm thời gian hoàn thành cụm bài SEO từ 4 ngày xuống còn dưới 1 ngày

Non-AI alternative: Tạo sẵn các template bài viết điền vào chỗ trống, hoặc thuê thêm CTV viết bài (tốn kém chi phí)

AI hypothesis: Sử dụng AI để tự động sinh ra bản nháp (draft) dựa trên dàn ý và bộ từ khóa đã chốt. Con người chỉ cần chỉnh sửa văn phong và tính xác thực

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 32 giờ (4 ngày làm việc)

[1 Nhận keyword: 1h] → [2 Research: 4h] → [3 Lên Outline: 3h] → [4 Viết content: 20h]  <-- bottleneck → [5 Review & SEO: 3h] → [6 Đăng bài: 1h]

FUTURE STATE — 7.5 giờ (Khoảng 1 ngày)

[1 Nhận keyword & Outline: 3h] → [2 AI Draft Content: 0.5h] → [3 Người edit & duyệt: 3h]  <-- human boundary → [4 Đăng bài: 1h]

Fallback: nếu AI viết sai sự thật hoặc giọng văn quá máy móc → Team member tự viết lại dựa trên sườn ý tưởng của AI
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — [Tên problem]

```text
Problem 1 câu: Mỗi tuần, Web Manager và team mất khoảng 120 phút họp bàn chỉ để chốt ý tưởng về chủ đề, nội dung và yêu cầu hình ảnh cho các bài SEO

Actor: Web manager, Designer, Team member

Thời điểm / bối cảnh: Đầu mỗi tuần khi cần lên kế hoạch Content Calendar (Lịch lên bài)

Current workflow 3-7 bước:
1. Web manager xem lại các bài tuần trước
2. Search Google/Mạng xã hội xem trend hiện tại
3. Cả team họp brainstorm chủ đề mới
4. Chốt nội dung và phác thảo yêu cầu hình ảnh
5. Gửi brief (bản mô tả) cho Designer

Bottleneck: Bước 3 — Họp brainstorm thường xuyên rơi vào bế tắc hoặc tranh luận lan man

Impact: Tốn 2 tiếng của nhiều nhân sự cùng lúc

Success metric: Giảm thời gian chốt ý tưởng từ 120 phút/tuần xuống còn 30 phút/tuần

Non-AI alternative: Tạo một file tính Excel lưu trữ các chủ đề xoay vòng (đến tuần thì lôi ra xài lại)

AI hypothesis: Web manager nhập bối cảnh trang web và mục tiêu tuần vào AI, AI sẽ trả ra 10-15 ý tưởng (gồm tiêu đề + mô tả nội dung + gợi ý hình ảnh) để team chỉ việc chọn lọc

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 120 phút

[1 Review cũ: 15'] → [2 Search Trend: 30'] → [3 Họp Brainstorm: 60']  <-- bottleneck → [4 Viết brief ảnh: 15']

FUTURE STATE — 30 phút

[1 Nhập bối cảnh cho AI: 5'] → [2 AI gen ý tưởng + brief ảnh: 5'] → [3 Team họp chọn lọc & chốt: 20']  <-- human boundary

Fallback: Ý tưởng AI quá nhàm chán → Quay lại họp tự brainstorm như cũ
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — [Tên problem]

```text
Problem 1 câu: Web Manager tốn 60 phút mỗi tuần để thủ công gom nhặt dữ liệu từ các công cụ (như Google Search Console) thành báo cáo đánh giá năng lực team

Actor: Web Manager

Thời điểm / bối cảnh: Cuối tuần (thứ 6) hoặc đầu tuần (thứ 2) khi cần báo cáo tiến độ

Current workflow 3-7 bước:
1. Đăng nhập Google Search Console / Analytics
2. Export dữ liệu ra file Excel
3. Copy/paste các chỉ số quan trọng (Traffic, Clicks, Keywords) vào slide/doc
4. Gõ đánh giá, nhận xét nguyên nhân tăng giảm
5. Gửi cho team

Bottleneck: Bước 2 & 3 — Lấy và format dữ liệu lắt nhắt từ nhiều tab mất rất nhiều công

Impact: Tốn 1 tiếng mỗi tuần cho việc chân tay, Web Manager ít thời gian tập trung vào phân tích chiến lược

Success metric: Giảm thời gian làm báo cáo tuần từ 60 phút xuống 15 phút

Non-AI alternative: Thiết lập Google Looker Studio (Data Studio) để tự động hiển thị biểu đồ

AI hypothesis: Dùng AI kết nối với file dữ liệu thô (hoặc dashboard), AI tự động đọc hiểu số liệu và viết ra đoạn tóm tắt nhận xét (narrative)

Quick gut:
[x] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 60 phút

[1 Mở tools: 5'] → [2 Export Excel: 15']  <-- bottleneck → [3 Format báo cáo: 20'] → [4 Viết nhận xét: 15'] → [5 Gửi: 5']

FUTURE STATE — 15 phút

[1 Auto-pull data / Dùng Looker Studio: 0'] → [2 Đẩy data vào AI: 2'] → [3 AI viết draft nhận xét: 3'] → [4 Web Manager review: 10']  <-- human boundary

Fallback: Nhận xét AI sai lệch do không hiểu thuật toán Google update → Manager tự nhìn biểu đồ viết tay
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```Problem Card #1: Dùng AI hỗ trợ viết nội dung bài SEO cho website mới

```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```Quá trình tạo content SEO đang là điểm nghẽn nặng nề nhất, "ngốn" của cả team 4 ngày/web. Nếu dùng AI để viết bản nháp, ta có thể giảm workflow xuống chỉ còn 1 ngày, giải phóng thời gian khổng lồ để team nhận thêm dự án web mới mà không cần tăng nhân sự

```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```Google ngày càng thắt chặt và phạt các nội dung do AI tạo ra (AI Spam). Vậy làm sao để đảm bảo nội dung ở Future Workflow an toàn cho SEO của Web?

```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: AI tạo content thường thiếu chiều sâu, thiếu ví dụ thực tế và không có giọng văn thương hiệu (Brand voice)
- Tôi sửa gì: Đưa thêm Human Boundary (Ranh giới con người) vào quy trình, bắt buộc phải có 3 giờ để người thật thêm các số liệu thực tế, hình ảnh độc quyền và chỉnh lại văn phong trước khi xuất bản, không dùng 100% chữ của AI

### Self-check nộp phần 01
- [ ] Có 5+ problems + top 3 Cards đủ field
- [ ] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ ] Đã chọn 1 card pitch + câu hỏi challenge
