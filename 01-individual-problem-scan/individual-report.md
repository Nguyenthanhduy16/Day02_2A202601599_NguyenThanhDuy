# Individual Problem Scan — Day 02

**Học viên:** Nguyễn Thanh Duy
**Mã học viên:** 2A202601599
**Mục tiêu phần cá nhân:** scan rộng các vấn đề thật quanh học tập/lab, chọn top 3 candidate problems đủ rõ để pitch với nhóm, và phác thảo workflow trước/sau cho từng problem.

## 1. Bảng scan 8 problems

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật / cách đo sơ bộ |
|---:|---|---|---|---|
| 1 | Tốn thời gian, lặp lại | Mỗi cuối ngày/tuần phải tự tổng hợp việc tồn, deadline và lịch cố định để lập kế hoạch; bước ước lượng và xếp lịch mất lâu. | Sinh viên/người tự quản lý nhiều deadline. | Draft ban đầu ghi 1–2 giờ/lần lập kế hoạch; cần đo lại 7 ngày để kiểm chứng. |
| 2 | Lặp lại, AI có thể tốt hơn | Mỗi cuối tuần sinh viên/leader mất khoảng 60 phút tổng hợp Weekly Lab Report từ Git commit log, Discord chat và note cá nhân. | Sinh viên/leader nhóm học tập AI. | 60 phút/tuần/người; nhóm 4 người có thể mất khoảng 240 phút/tuần tổng effort. |
| 3 | Pain từ nhóm, AI có thể tốt hơn | Khi làm task, sinh viên phải tìm lại quyết định/câu trả lời cũ trong Discord nhưng thông tin nằm rải rác ở nhiều thread. | Thành viên nhóm lab/đồ án mới hoặc người nhận task sau. | Hay hỏi lại “task này chốt thế nào?”, “deadline ở đâu?”, “file nào là bản cuối?”. |
| 4 | Tốn thời gian | Trước khi nộp bài, sinh viên không chắc bài đã đủ field theo worksheet/rubric, phải tự dò từng mục. | Sinh viên làm lab có nhiều checklist. | Dễ thiếu metric, boundary hoặc workflow sau; có thể đo bằng số lỗi/thiếu field sau self-review. |
| 5 | Tốn thời gian, học tập | Đọc tài liệu dài trước deadline nhưng khó rút ra phần cần áp dụng vào bài lab/code. | Sinh viên học AI hoặc kỹ thuật. | Mất nhiều thời gian đọc lại, highlight rời rạc; output cuối vẫn thiếu quyết định hành động. |
| 6 | Nhóm/dự án | Phân công task trong nhóm đôi khi không rõ owner, output và deadline, dẫn tới weekly meeting phải hỏi lại. | Nhóm 3–4 sinh viên làm đồ án/lab. | Task bị trễ vì “tưởng bạn khác làm”; có thể đo bằng số task không có owner/deadline rõ. |
| 7 | Đời sống cá nhân | Theo dõi chi tiêu nằm rải rác ở ví tiền mặt, app ngân hàng và ghi chú, cuối tháng khó biết tiền đi đâu. | Sinh viên tự quản lý chi tiêu. | Phải mở nhiều app, nhập tay; thường chỉ nhớ khoản lớn, bỏ sót khoản nhỏ. |
| 8 | Công việc/thực tập | Người mới vào nhóm phải hỏi lại quy trình setup, nộp file, đặt tên branch/commit vì tài liệu onboarding phân tán. | Thành viên mới trong nhóm học tập/thực tập. | Câu hỏi lặp lại trong chat; có thể đo bằng số lần hỏi lại cùng một quy trình. |

## 2. Chọn top 3 Problem Cards

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Weekly Lab Report | Có actor rõ, xảy ra đều mỗi tuần, workflow 7 bước rõ, impact đo được bằng phút/tuần và chất lượng weekly meeting. AI phù hợp ở bước tổng hợp và draft narrative. | Cần kiểm chứng dữ liệu đầu vào thật: Git log có đủ rõ không, Discord có export được không, giảng viên hỏi lại bao nhiêu câu. |
| 2 | Lập và theo dõi kế hoạch cá nhân hằng ngày/hằng tuần | Pain cá nhân rõ, có bottleneck ở ước lượng và phân bổ thời gian, có thể đo bằng thời gian lập kế hoạch và tỷ lệ hoàn thành việc ưu tiên. | Con số 1–2 giờ/ngày cần đo lại vì có thể là 1–2 giờ/lần lập kế hoạch tuần. |
| 3 | Tìm lại quyết định/câu trả lời cũ trong Discord | Đây là pain thường gặp trong nhóm học tập: thông tin tồn tại nhưng khó tìm đúng ngữ cảnh. Có thể giải bằng workflow search + summary + human confirm. | Cần biết nhóm dùng Discord thật hay công cụ chat khác; cần tránh đọc private messages hoặc dữ liệu không liên quan. |

## 3. Card muốn pitch nhất

**Card tôi muốn pitch nhất:** Problem Card #2 — Weekly Lab Report.

**Vì sao:** Problem này vừa đủ hẹp để làm trong lab, vừa có tác động nhóm rõ. Workflow hiện tại có nhiều nguồn dữ liệu nhưng output lại là một báo cáo có template ổn định, nên dễ so sánh No AI / Rule / Workflow / Agent. Bài toán cũng buộc nhóm giữ boundary tốt: AI chỉ draft và kiểm tra thiếu sót, sinh viên/leader vẫn phải review trước khi gửi.

**Câu hỏi tôi muốn nhóm challenge:**

- Nếu chỉ dùng template + daily checklist, đã đủ giảm từ 60 phút xuống dưới 20 phút chưa?
- Git commit log và Discord chat có đủ evidence để viết narrative không, hay vẫn cần note cá nhân của từng thành viên?
- Chất lượng report nên đo bằng gì ngoài thời gian: số câu hỏi giảng viên hỏi lại, số claim có evidence, hay mức phải sửa draft?
- Có cần Agent tự động chạy hằng tuần không, hay Workflow có nút bấm thủ công là đủ an toàn hơn?

---

# Problem Card #1 — Lập và theo dõi kế hoạch cá nhân hằng ngày/hằng tuần

## 1. Tóm tắt Problem Card

| Thành phần | Nội dung |
|---|---|
| **Problem một câu** | Mỗi cuối ngày hoặc cuối tuần, A phải tổng kết việc đã làm, xác định việc còn tồn và sắp xếp công việc tiếp theo vào lịch; bước ước lượng thời gian và phân bổ công việc vào từng khung giờ hiện mất khoảng 1–2 giờ/ngày nhưng A vẫn chưa biết kế hoạch có thực tế và khả thi hay không. |
| **Actor** | A — người học/người làm việc phải tự quản lý nhiều đầu việc, deadline và lịch cố định. |
| **Thời điểm / bối cảnh** | Cuối mỗi ngày để chuẩn bị cho ngày hôm sau; cuối tuần để rà soát và lập khung kế hoạch tuần tiếp theo. |
| **Bottleneck** | Ước lượng thời lượng, xác định ưu tiên và xếp công việc vào khung giờ phù hợp với thời gian khả dụng. |
| **Baseline** | Theo draft: 1–2 giờ/ngày. Cần đo lại trong 7 ngày vì con số này tương đương 7–14 giờ/tuần, chưa khớp với ước tính 7–8 giờ/tuần trong draft. |
| **Success metric chính** | Giảm thời gian lập kế hoạch xuống 15–30 phút/ngày mà không làm giảm tỷ lệ hoàn thành công việc ưu tiên. |
| **Quick gut** | **Workflow** — rule kiểm tra ràng buộc, AI tạo lịch nháp, A duyệt kế hoạch cuối cùng. |

## 2. Mô tả vấn đề chi tiết

A thường phải xử lý đồng thời ba nhóm công việc:
1. Việc có thời gian cố định, ví dụ lịch học, họp hoặc lịch hẹn.
2. Việc có deadline nhưng chưa có khung giờ thực hiện cụ thể.
3. Việc linh hoạt như tự học, đọc tài liệu, luyện tập hoặc việc cá nhân.
Mỗi cuối ngày/tuần, A phải tổng hợp các công việc, đánh giá mức độ quan trọng, ước lượng thời gian và sắp xếp chúng vào lịch. Công việc này tốn thời gian vì thông tin nằm rải rác, thời lượng chưa chắc chắn và có nhiều ràng buộc cần cân nhắc. Sau khi lập xong, A vẫn khó biết lịch có quá tải, có đủ thời gian nghỉ và khoảng đệm, hoặc có thực sự hoàn thành được hay không.
Vấn đề cốt lõi không phải là A “không có lịch”, mà là **quá trình biến danh sách công việc và các ràng buộc thành một lịch trình khả thi đang tốn nhiều thời gian và phụ thuộc nhiều vào phán đoán thủ công**.

## 3. Current workflow

### Workflow hiện tại — khoảng 60–120 phút/lần lập kế hoạch

| Bước | Hoạt động của A | Input | Output | Thời gian ước tính |
|---:|---|---|---|---:|
| 1 | Xem lại lịch cũ, đánh dấu việc hoàn thành/chưa hoàn thành | Lịch ngày/tuần hiện tại | Danh sách việc còn tồn | 5–10 phút |
| 2 | Thu thập việc mới, deadline và các lịch cố định | Ghi chú, tin nhắn, lịch | Danh sách đầu việc và ràng buộc | 10–15 phút |
| 3 | Ước lượng thời gian và độ khó của từng việc | Danh sách đầu việc | Thời lượng dự kiến | 10–20 phút |
| 4 | Xếp ưu tiên theo deadline, tầm quan trọng và phụ thuộc | Deadline, mục tiêu | Danh sách đã ưu tiên | 10–15 phút |
| 5 | Điền từng việc vào các khung giờ còn trống | Danh sách đã ưu tiên, lịch cố định | Bản lịch đầu tiên | 20–40 phút |
| 6 | Kiểm tra xung đột, quá tải và điều chỉnh | Bản lịch đầu tiên | Kế hoạch hoàn chỉnh | 5–15 phút |
| 7 | Thực hiện, cập nhật và dời việc chưa xong | Kế hoạch đã chốt | Trạng thái thực tế, việc chuyển tiếp | Trong ngày |
```text
[Rà soát kế hoạch cũ]
        ↓
[Thu thập việc mới và lịch cố định]
        ↓
[Ước lượng thời lượng]
        ↓
[Xếp mức ưu tiên]
        ↓
[Phân bổ vào khung giờ]  ← BOTTLENECK
        ↓
[Kiểm tra quá tải/xung đột]
        ↓
[Thực hiện, cập nhật và dời việc]
```

### Bottleneck

Bottleneck tập trung ở bước 3–6, đặc biệt là phân bổ công việc vào khung giờ. A phải đồng thời cân nhắc:
- deadline và độ quan trọng;
- lịch học, họp hoặc hẹn cố định;
- thời lượng và mức độ khó của việc;
- thời điểm có khả năng tập trung tốt;
- thời gian nghỉ, ăn uống, di chuyển và khoảng đệm;
- việc tồn từ ngày/tuần trước;
- quan hệ phụ thuộc giữa các công việc.
Khi một giả định thay đổi, ví dụ một việc kéo dài hơn dự kiến, A thường phải sắp xếp lại nhiều khung giờ.

## 4. Impact

### Tác động đã ghi nhận trong draft

- A mất khoảng 1–2 giờ/ngày cho việc lập kế hoạch, làm giảm thời gian thực hiện công việc.
- A chưa tự tin lịch đã được sắp xếp khoa học, hợp lý và có thể theo được.

### Tác động cần kiểm chứng

- Tỷ lệ công việc hoàn thành đúng kế hoạch có thể thấp.
- Việc phải chuyển sang ngày tiếp theo có thể tạo thêm thời gian lập lại kế hoạch.
- Lịch quá tải có thể khiến A làm việc quá giờ hoặc thiếu thời gian nghỉ.
- Việc lập kế hoạch quá lâu có thể gây mệt mỏi trước khi bắt đầu thực hiện.
Các ý trên là giả thuyết, chưa phải dữ liệu đã xác nhận.

## 5. Success metrics

| Metric | Baseline | Mục tiêu thử nghiệm | Cách đo |
|---|---:|---:|---|
| **Thời gian lập kế hoạch/ngày** | 60–120 phút theo draft | **≤ 30 phút**, kỳ vọng 15–30 phút | Bấm giờ từ lúc bắt đầu tổng kết đến lúc chốt lịch |
| **Tỷ lệ việc ưu tiên hoàn thành đúng ngày** | Chưa có dữ liệu | Không thấp hơn baseline; mục tiêu ban đầu ≥ 80% | Việc ưu tiên hoàn thành / việc ưu tiên đã lên lịch |
| **Tỷ lệ việc phải chuyển ngày** | Chưa có dữ liệu | Giảm ít nhất 20% so với baseline | Việc bị dời / tổng việc đã lên lịch |
| **Sai lệch thời gian dự kiến–thực tế** | Chưa có dữ liệu | Trung vị ≤ 30% | So sánh thời lượng dự kiến và thực tế của từng việc |
| **Mức hài lòng của A** | Chưa có dữ liệu | ≥ 4/5 | A tự chấm cuối ngày theo thang 1–5 |
Giải pháp được xem là có ích sau 2 tuần nếu:
1. Thời gian lập kế hoạch trung vị không quá 30 phút/ngày.
2. Tỷ lệ hoàn thành việc ưu tiên không giảm so với baseline.
3. Trong phần lớn số ngày, A không phải sửa quá 50% lịch do hệ thống đề xuất.

## 6. Non-AI alternatives

| Phương án | Giải quyết được gì | Giới hạn |
|---|---|---|
| **Template lập kế hoạch** | Chuẩn hóa deadline, ưu tiên, thời lượng và khung giờ | A vẫn tự tính và xếp lịch |
| **Ma trận quan trọng/khẩn cấp** | Giúp xếp ưu tiên | Không phân bổ theo thời gian khả dụng |
| **Time blocking trên Calendar** | Biến công việc thành các khối thời gian rõ ràng | Khi lịch đổi, A vẫn sắp xếp lại thủ công |
| **Recurring blocks** | Giữ sẵn thời gian cho việc lặp lại | Ít linh hoạt với việc mới |
| **Rule-based scheduling** | Xếp theo deadline và giữ khoảng đệm | Khó xử lý các ưu tiên mềm và bối cảnh cá nhân |
| **Mentor/chuyên gia góp ý một lần** | Giúp xây nguyên tắc lập lịch phù hợp | Không hỗ trợ mỗi khi đầu việc thay đổi |
**Kết luận ban đầu:** template + rule + time blocking nên được thử trước hoặc dùng làm nền cho AI; chưa cần một Agent tự chủ.

## 7. AI hypothesis

Nếu A cung cấp danh sách công việc theo cấu trúc gồm deadline, mức độ quan trọng, thời lượng dự kiến, lịch cố định và thời gian khả dụng, AI có thể tạo một bản lịch ban đầu kèm giải thích. A review và chỉnh sửa trước khi áp dụng.

### AI có thể hỗ trợ

- Chuẩn hóa danh sách công việc từ ghi chú của A.
- Phát hiện dữ liệu còn thiếu như deadline hoặc thời lượng.
- Đề xuất thứ tự ưu tiên và chia việc lớn thành các phiên nhỏ.
- Tạo bản time-blocking theo ràng buộc đã khai báo.
- Chỉ ra ngày quá tải, xung đột hoặc thiếu khoảng đệm.
- Đề xuất phương án dời việc khi A chủ động yêu cầu.

### AI không được phép

- Tự quyết định mục tiêu hoặc ưu tiên quan trọng thay A.
- Tự thêm, xóa hoặc dời lịch cố định khi chưa được A xác nhận.
- Tự ghi lịch hoặc gửi thông báo khi A chưa phê duyệt.
- Bịa deadline, thời lượng hoặc công việc không có trong input.
- Cam kết mọi công việc chắc chắn hoàn thành đúng hạn.

### Quick gut: Workflow

```text
A cập nhật task và ràng buộc
        ↓
Rule kiểm tra deadline, lịch cố định và dữ liệu thiếu
        ↓
AI tạo bản kế hoạch nháp và giải thích
        ↓
A review, sửa và phê duyệt
        ↓
Calendar lưu lịch, nhắc nhở theo rule
        ↓
A cập nhật kết quả cho lần lập kế hoạch sau
```
Chọn **Workflow**, không chọn Agent, vì luồng xử lý tuyến tính và có điểm duyệt rõ. Nhắc theo giờ chỉ cần rule. AI phù hợp với bước đề xuất lịch dựa trên nhiều ràng buộc mềm, còn A vẫn quyết định ưu tiên và phê duyệt kế hoạch.

## 8. Draft future workflow

### Workflow tương lai — mục tiêu 15–30 phút

| Bước | Actor/hệ thống | Hoạt động | Thời gian mục tiêu |
|---:|---|---|---:|
| 1 | A | Cập nhật việc mới, deadline, thời lượng và lịch cố định vào template | 5–10 phút |
| 2 | Rule | Kiểm tra trường thiếu, xung đột cứng và tổng thời gian khả dụng | < 1 phút |
| 3 | AI | Tạo lịch nháp, giữ khoảng đệm và giải thích thứ tự ưu tiên | 1–2 phút |
| 4 | A | Kiểm tra, đổi ưu tiên và chỉnh khung giờ | 8–15 phút |
| 5 | Calendar/rule | Lưu time block và đặt nhắc sau khi A xác nhận | < 2 phút |
| 6 | A | Cuối ngày đánh dấu hoàn thành, ghi thời gian thực tế | 2–3 phút |

### Human boundary

A phải là người:
- xác nhận deadline, lịch cố định và mức ưu tiên;
- kiểm tra tổng khối lượng có thực tế hay không;
- phê duyệt trước khi ghi vào Calendar;
- quyết định dời hoặc hủy công việc;
- chịu trách nhiệm cho kế hoạch cuối cùng.

### Fallback

Nếu AI đưa ra lịch không phù hợp:
1. Không ghi bản nháp vào lịch thật.
2. Quay về template + rule-based time blocking.
3. A tự xếp các việc ưu tiên cao; việc còn lại đưa vào backlog.
4. Ghi lại lỗi để sửa rule hoặc input cho lần sau.

## 9. Boundary và rủi ro

### In scope

- Lập kế hoạch ngày/tuần cho một cá nhân.
- Dùng dữ liệu do A chủ động cung cấp.
- Đề xuất và nhắc nhở; A duyệt trước khi áp dụng.
- Công việc học tập, công việc và sinh hoạt thông thường.

### Out of scope

- Tự quyết định mục tiêu dài hạn thay A.
- Tự ý chỉnh lịch của người khác hoặc lịch nhóm.
- Xử lý lịch y tế, tài chính hoặc tình huống hậu quả nghiêm trọng.
- Đánh giá năng suất, sức khỏe hay năng lực như kết luận chuyên môn.
- Cam kết lịch đề xuất chắc chắn hoàn thành đúng hạn.
| Rủi ro | Hậu quả | Kiểm soát |
|---|---|---|
| Ước lượng thời lượng sai | Lịch quá tải | So sánh dự kiến–thực tế và cập nhật dần |
| AI hiểu sai ưu tiên | Việc quan trọng bị xếp muộn | A xác nhận ba việc ưu tiên cao nhất |
| Lịch quá kín | Không có chỗ cho phát sinh | Rule giữ 15–20% thời gian khả dụng làm buffer |
| AI tạo thông tin sai | Task/deadline không tồn tại | Chỉ dùng input; yêu cầu A duyệt |
| Lộ dữ liệu lịch cá nhân | Ảnh hưởng riêng tư | Chỉ thu thập trường cần thiết, tránh nội dung nhạy cảm |
| A phụ thuộc vào AI | Giảm khả năng tự quyết định | AI giải thích; A có quyền sửa hoặc bỏ toàn bộ draft |

## 10. Kế hoạch kiểm chứng nhanh

### Tuần 1 — Đo baseline

- A lập kế hoạch như hiện tại trong 7 ngày.
- Ghi thời gian lập kế hoạch, số việc ưu tiên, số việc hoàn thành, số việc bị dời và số lần chỉnh lịch lớn.
- Không thay đổi quy trình để tránh làm sai baseline.

### Tuần 2–3 — Thử workflow mới

- Dùng cùng một template input mỗi ngày.
- AI tạo lịch nháp nhưng chưa tự ghi vào Calendar.
- A review, sửa và ghi lại tỷ lệ nội dung phải chỉnh.
- So sánh các metric với tuần baseline.

### Quyết định

- **Go:** thời gian lập kế hoạch ≤ 30 phút và tỷ lệ hoàn thành việc ưu tiên không giảm.
- **Iterate:** có tiết kiệm thời gian nhưng A phải sửa hơn 50% lịch.
- **No-Go / quay về non-AI:** không tiết kiệm thời gian, thường xếp sai ưu tiên hoặc tạo lịch quá tải.

## 11. Phiên bản pitch ngắn

> Mỗi cuối ngày hoặc cuối tuần, A phải tổng hợp việc tồn, việc mới, deadline và lịch cố định để lập kế hoạch tiếp theo. Bước khó nhất là ước lượng thời lượng, xếp ưu tiên và đưa công việc vào các khung giờ; hiện mất khoảng 1–2 giờ/ngày nhưng lịch vẫn có thể quá tải hoặc thiếu thực tế. Mục tiêu là giảm thời gian lập kế hoạch xuống 15–30 phút mà không làm giảm tỷ lệ hoàn thành việc ưu tiên. Hướng ban đầu là workflow gồm template và rule để chuẩn hóa dữ liệu, AI tạo lịch nháp, A review/phê duyệt, còn Calendar lưu lịch và nhắc theo rule.

## 12. Các giả định cần xác nhận

- “1–2 giờ” là thời gian mỗi ngày hay chỉ ở buổi lập kế hoạch tuần?
- A hiện dùng giấy, Notion, Google Calendar, Excel hay công cụ nào khác?
- Pain lớn nhất là thời gian lập kế hoạch, tỷ lệ không hoàn thành hay việc phải chỉnh lịch liên tục?
- A có thể cung cấp deadline và thời lượng dự kiến cho phần lớn công việc không?
- Mục tiêu hoàn thành 80% việc ưu tiên có phù hợp với thực tế không?
> **Lưu ý:** Ngoài baseline 1–2 giờ/ngày và target 15–30 phút lấy từ draft, các con số khác là mục tiêu/giả thuyết thiết kế, chưa phải kết quả đã kiểm chứng. Cần đo baseline ít nhất 7 ngày trước khi chốt bản nộp cuối.

---

# Problem Card #2 — Weekly Lab Report

## 1. Tóm tắt Problem Card

| Thành phần | Nội dung |
|---|---|
| **Problem một câu** | Mỗi cuối tuần, sinh viên hoặc leader nhóm học tập AI mất khoảng 60 phút để tổng hợp Weekly Progress Report từ Git commit log, Discord chat và note cá nhân; bước viết narrative là phần tốn thời gian nhất, dễ kẹt ý và khiến báo cáo bị trễ hoặc sơ sài. |
| **Actor** | Sinh viên / leader nhóm học tập AI, đặc biệt là người chịu trách nhiệm tổng hợp tiến độ cho nhóm trước buổi sync. |
| **Thời điểm / bối cảnh** | Trước buổi sync tiến độ đồ án/lab với giảng viên; khi cần nộp weekly report hoặc chuẩn bị weekly meeting. |
| **Bottleneck** | Bước viết narrative tổng hợp: chuyển raw data rời rạc thành câu chuyện tiến độ rõ ràng, có kết quả, điểm nghẽn và kế hoạch tuần tới. |
| **Baseline** | 60 phút/tuần cho 1 sinh viên. Với nhóm 4 sinh viên, tổng effort khoảng 240 phút/tuần nếu mỗi người đều phải tự tổng hợp phần của mình. |
| **Success metric chính** | Giảm tổng thời gian làm báo cáo từ 60 phút xuống dưới 20 phút, đồng thời không làm tăng số câu hỏi giảng viên phải hỏi lại để hiểu tiến độ. |
| **Quick gut** | **Workflow** — script thu thập dữ liệu, AI cấu trúc và draft narrative, sinh viên/leader review trước khi gửi. |

## 2. Mô tả vấn đề chi tiết

Trong các nhóm học tập AI hoặc nhóm làm đồ án/lab, tiến độ hằng tuần thường nằm rải rác ở nhiều nguồn khác nhau. Git commit log phản ánh phần code đã thay đổi, Discord chat chứa thảo luận và quyết định trong quá trình làm, còn note cá nhân ghi lại việc đã hoàn thành, lỗi gặp phải hoặc hướng xử lý tiếp theo.
Vào cuối tuần, sinh viên hoặc leader phải gom các dữ liệu này lại để viết Weekly Progress Report. Báo cáo không chỉ liệt kê việc đã làm, mà còn cần giải thích được bức tranh tiến độ: nhóm đã đạt kết quả gì, đang bị nghẽn ở đâu, vì sao có task bị trễ và tuần tới nên tập trung vào phần nào.
Vấn đề cốt lõi không phải là thiếu dữ liệu, mà là **dữ liệu tiến độ đang ở dạng rời rạc, kỹ thuật và nhiều ngữ cảnh ngầm; người viết phải tốn nhiều công để biến chúng thành một narrative mạch lạc cho giảng viên hoặc nhóm hiểu nhanh**.

## 3. Current workflow

### Workflow hiện tại — khoảng 60 phút/báo cáo/tuần

| Bước | Hoạt động của sinh viên/leader | Input | Output | Thời gian ước tính |
|---:|---|---|---|---:|
| 1 | Export Git commit logs trong tuần | Git repository, commit history | Danh sách commit, tác giả, thời gian, message | 5–10 phút |
| 2 | Đọc lại thảo luận và chốt task trên các kênh chat | Discord chat, thread, pinned messages | Các quyết định chính, task đã/chưa chốt | 10–15 phút |
| 3 | Lấy nội dung ghi chú cá nhân và ghi chú của thành viên | Note cá nhân, task list, file nháp | Ghi chú tiến độ và vấn đề gặp phải | 5–10 phút |
| 4 | Copy số liệu và thông tin chính vào template báo cáo | Commit log, chat, note, template | Bản report có dữ liệu thô | 5–10 phút |
| 5 | Viết narrative: kết quả đạt được, điểm nghẽn, kế hoạch tuần tới | Dữ liệu thô đã gom | Đoạn báo cáo có lập luận và bối cảnh | 20–30 phút |
| 6 | Self-review và format lại Markdown/Word | Bản report nháp | Bản report sạch, dễ đọc | 5–10 phút |
| 7 | Nộp báo cáo cho giảng viên hoặc chia sẻ cho nhóm | File Markdown/Word/Docs | Report đã gửi | 1–5 phút |
```text
[Export Git commit logs]
        ↓
[Đọc lại Discord chat]
        ↓
[Tổng hợp note cá nhân/thành viên]
        ↓
[Điền dữ liệu vào template]
        ↓
[Viết narrative tổng hợp]  ← BOTTLENECK
        ↓
[Review và format]
        ↓
[Nộp báo cáo / gửi nhóm]
```

### Bottleneck

Bottleneck nằm ở bước 5 vì người viết phải làm ba việc cùng lúc:
- chọn thông tin đáng đưa vào báo cáo từ nhiều raw data;
- nhóm các hoạt động nhỏ thành kết quả hoặc chủ đề lớn;
- diễn giải tiến độ theo ngôn ngữ dễ hiểu cho giảng viên, không chỉ theo log kỹ thuật.
Ví dụ, 12 commit nhỏ như `fix loader`, `update prompt`, `handle empty response`, `refactor eval` có thể cần được viết thành một narrative ngắn: “Nhóm đã hoàn thiện luồng gọi model, xử lý lỗi phản hồi rỗng và bắt đầu refactor phần đánh giá kết quả.” Đây là thao tác tổng hợp có tính ngữ cảnh, không phải copy-paste đơn thuần.

## 4. Impact

### Tác động đã ghi nhận từ draft

- Mỗi sinh viên mất khoảng 60 phút/tuần để làm weekly report.
- Nhóm 4 sinh viên có thể mất khoảng 240 phút/tuần tổng công sức nếu mỗi người đều phải tự tổng hợp và viết phần của mình.
- Báo cáo trễ hoặc viết sơ sài khiến giảng viên thiếu bối cảnh để đánh giá tiến độ thật của nhóm.

### Tác động vận hành

- Leader phải đọc lại nhiều nguồn thông tin vào sát deadline, dễ bỏ sót việc quan trọng.
- Báo cáo có thể thiên về liệt kê commit, thiếu phần giải thích “vì sao việc này quan trọng”.
- Các điểm nghẽn như lỗi kỹ thuật, thiếu dữ liệu, chia task chưa rõ hoặc phụ thuộc giữa thành viên có thể không được nêu đủ rõ.
- Weekly meeting tốn thêm thời gian để hỏi lại những điều report chưa diễn đạt tốt.

### Tác động học tập

- Sinh viên mất thời gian vào việc tổng hợp hành chính thay vì phân tích vấn đề hoặc cải thiện sản phẩm.
- Nhóm ít nhìn lại pattern tiến độ qua từng tuần, nên khó phát hiện task thường bị trễ ở bước nào.
- Giảng viên khó phân biệt giữa nhóm thật sự không có tiến độ và nhóm có tiến độ nhưng báo cáo chưa đủ rõ.

## 5. Success metrics

| Metric | Baseline hiện tại | Target sau cải tiến | Cách đo |
|---|---:|---:|---|
| Thời gian làm report/tuần/người | 60 phút | Dưới 20 phút | Bấm giờ từ lúc bắt đầu gom dữ liệu đến lúc có bản gửi được |
| Thời gian viết narrative | 20–30 phút | Dưới 8 phút review/edit | So sánh thời gian ở bước 5 trước và sau workflow mới |
| Số câu hỏi giảng viên phải hỏi lại vì thiếu bối cảnh | Chưa đo | Không tăng so với baseline | Ghi lại câu hỏi trong weekly meeting hoặc comment của giảng viên |
| Tỷ lệ thông tin quan trọng bị bỏ sót | Chưa đo | Giảm hoặc không tăng | So checklist task/issue/decision với nội dung report |
| Mức độ phải sửa draft AI | Chưa có | Dưới 30% nội dung chính | Leader đánh dấu phần phải viết lại sau khi AI draft |

### Điều kiện thành công tối thiểu

Workflow được xem là thành công nếu:
- tổng thời gian làm report giảm xuống dưới 20 phút/người/tuần;
- report vẫn có đủ ba phần: kết quả đạt được, bottleneck, kế hoạch tuần tới;
- giảng viên không phải hỏi lại nhiều hơn vì report thiếu bối cảnh;
- sinh viên/leader vẫn review trước khi gửi, không gửi tự động.

## 6. Non-AI alternative

Các giải pháp không dùng AI có thể giúp giảm một phần effort:
| Giải pháp | Cách hoạt động | Điểm mạnh | Giới hạn |
|---|---|---|---|
| Template report cố định | Chuẩn hóa các mục: Done, Blockers, Next week, Evidence | Giảm thời gian format và giúp không quên mục | Không tự biến raw data thành narrative |
| Checklist cuối ngày | Thành viên ghi daily log ngắn sau mỗi buổi làm | Giảm việc phải nhớ lại vào cuối tuần | Cần kỷ luật ghi đều; vẫn phải tổng hợp |
| Bảng task Kanban | Dùng To do / Doing / Done / Blocked | Dễ nhìn trạng thái task | Không phản ánh đầy đủ thảo luận trong chat và commit |
| Commit convention | Viết commit message theo format chuẩn | Dễ nhóm commit theo feature/bug/refactor | Chỉ bao phủ phần code, không bao phủ quyết định và blockers |
| Leader review định kỳ giữa tuần | Tổng hợp dần thay vì dồn cuối tuần | Giảm áp lực sát deadline | Tăng số lần context switching trong tuần |
Non-AI alternative tốt nhất có thể là template + checklist + commit convention. Tuy nhiên, hướng này vẫn chưa giải quyết tốt phần khó nhất: viết narrative tổng hợp từ dữ liệu rời rạc và có nhiều ngữ cảnh ngầm.

## 7. AI hypothesis

### Giả thuyết chính

Một workflow có AI có thể giảm thời gian viết Weekly Progress Report bằng cách:
1. Script thu thập dữ liệu từ Git commit log, Discord export và note cá nhân.
2. AI phân nhóm dữ liệu theo chủ đề: feature, bug fix, experiment, blocker, decision, next step.
3. AI tạo bản draft narrative theo template báo cáo.
4. Sinh viên hoặc leader review, sửa lỗi ngữ cảnh và xác nhận trước khi gửi.
```text
[Git logs] ─┐
[Discord] ──┼──> [Normalize dữ liệu] ──> [AI phân nhóm] ──> [Draft narrative]
[Notes] ────┘                                      ↓
                                             [Human review]
                                                   ↓
                                            [Final weekly report]
```

### AI nên làm gì

- Tóm tắt commit log thành các nhóm công việc có ý nghĩa.
- Rút ra các quyết định hoặc blockers từ chat và note.
- Viết draft narrative theo giọng văn báo cáo học thuật/ngắn gọn.
- Gợi ý phần “next week plan” dựa trên task chưa hoàn thành hoặc blocker còn mở.
- Chỉ ra dữ liệu thiếu, ví dụ “chưa thấy blocker rõ ràng” hoặc “chưa có kế hoạch tuần tới”.

### AI không nên làm gì

- Tự bịa tiến độ, kết quả, số liệu hoặc quyết định không có trong nguồn.
- Tự nộp báo cáo mà không có người review.
- Đánh giá năng lực thành viên theo cách nhạy cảm hoặc thiếu căn cứ.
- Tự kết luận nguyên nhân trễ task nếu dữ liệu không nói rõ.

### Quick gut

Bài toán này phù hợp nhất với hướng **Workflow**, không phải Agent tự trị hoàn toàn.
Lý do: quy trình có các bước lặp lại, nguồn dữ liệu rõ và output có template ổn định. Tuy nhiên, nội dung báo cáo ảnh hưởng đến đánh giá của giảng viên, nên con người vẫn phải duyệt trước khi gửi.

## 8. Future workflow đề xuất

### Workflow mới — mục tiêu dưới 20 phút/báo cáo

| Bước | Hoạt động | Người/Tool chịu trách nhiệm | Output | Thời gian mục tiêu |
|---:|---|---|---|---:|
| 1 | Chạy script lấy commit log trong tuần | Script | File `git-log-week.md` hoặc JSON | 1–2 phút |
| 2 | Export hoặc copy các đoạn Discord liên quan | Sinh viên/leader | Raw chat đã lọc | 3–5 phút |
| 3 | Gom note cá nhân/thành viên theo template ngắn | Thành viên | Note dạng bullet | 3–5 phút |
| 4 | AI phân nhóm dữ liệu và nhận diện thiếu sót | AI workflow | Bảng themes, blockers, next steps | 2–3 phút |
| 5 | AI viết draft narrative theo template | AI workflow | Weekly report nháp | 1–2 phút |
| 6 | Sinh viên/leader review, sửa và xác nhận | Human | Báo cáo cuối cùng | 5–8 phút |
| 7 | Nộp report và lưu lại dữ liệu tuần | Human | Report đã gửi, archive tuần | 1–2 phút |

### Template input tối thiểu

```markdown

# Weekly raw input

## Git commits

- <hash/date/author/message>

## Discord decisions

- <decision/context/date>

## Notes

- Done:
- Blockers:
- Evidence/link:
- Next week:
```

### Template output mong muốn

```markdown

# Weekly Progress Report

## 1. Summary

<2–3 câu tóm tắt tiến độ tuần>

## 2. Completed

<Các kết quả đã đạt được, nhóm theo chủ đề>

## 3. Blockers / Risks

<Điểm nghẽn, nguyên nhân nếu có bằng chứng, ảnh hưởng>

## 4. Plan for Next Week

<Task ưu tiên, owner nếu có, expected output>

## 5. Evidence

<Link commit, PR, note, demo, issue>
```

## 9. Boundary và rủi ro

### In scope

- Báo cáo tiến độ học tập, đồ án hoặc lab hằng tuần.
- Dữ liệu đầu vào do sinh viên/leader chủ động cung cấp.
- Draft narrative, phân nhóm dữ liệu và kiểm tra thiếu sót.
- Xuất báo cáo Markdown/Word/Google Docs tùy yêu cầu lớp.

### Out of scope

- Tự động đọc toàn bộ Discord/private messages nếu chưa có quyền rõ ràng.
- Tự động nộp báo cáo thay sinh viên.
- Tự tạo bằng chứng tiến độ không tồn tại trong commit, note hoặc chat.
- Đánh giá điểm số, năng lực cá nhân hoặc quy trách nhiệm cho thành viên.
| Rủi ro | Hậu quả | Kiểm soát |
|---|---|---|
| AI bịa hoặc suy diễn quá mức | Report sai sự thật, mất niềm tin | Yêu cầu mỗi claim quan trọng có evidence từ commit/chat/note |
| Bỏ sót thông tin trong Discord | Narrative thiếu bối cảnh | Dùng checklist chọn kênh/thread cần export |
| Commit message quá mơ hồ | AI nhóm sai công việc | Áp dụng commit convention hoặc thêm note ngắn cho commit quan trọng |
| Draft nghe hay nhưng không đúng tiến độ | Giảng viên hiểu sai tình hình | Human review bắt buộc trước khi gửi |
| Lộ thông tin nhạy cảm trong chat | Ảnh hưởng riêng tư nhóm | Chỉ đưa đoạn liên quan, ẩn token/tài khoản/thông tin cá nhân |
| Phụ thuộc quá nhiều vào AI | Sinh viên ít tự phản tư tiến độ | Giữ phần review: “Điều nhóm học được tuần này” do người viết xác nhận |

## 10. Kế hoạch kiểm chứng nhanh

### Tuần 1 — Đo baseline

- Làm report theo cách hiện tại.
- Ghi thời gian cho từng bước: lấy Git log, đọc Discord, gom note, viết narrative, format/review.
- Ghi số câu hỏi giảng viên hỏi lại trong weekly meeting.
- Lưu một bản report làm mẫu baseline.

### Tuần 2 — Thử workflow AI có kiểm soát

- Chuẩn bị input theo template tối thiểu.
- Dùng AI để phân nhóm raw data và viết draft narrative.
- Leader review, sửa, đánh dấu phần AI sai hoặc thiếu evidence.
- So sánh thời gian hoàn thành với baseline.

### Tuần 3 — Lặp lại và cải thiện prompt/template

- Cập nhật template input nếu tuần 2 thiếu dữ liệu.
- Thêm rule: mỗi bullet quan trọng phải có evidence.
- Đo lại thời gian, chất lượng report và số câu hỏi giảng viên phải hỏi lại.

### Quyết định

- **Go:** report hoàn thành dưới 20 phút và giảng viên không phải hỏi lại nhiều hơn baseline.
- **Iterate:** tiết kiệm thời gian nhưng AI còn bỏ sót nhiều hoặc draft cần sửa hơn 30% nội dung chính.
- **No-Go / quay về non-AI:** report nhanh hơn không đáng kể, sai ngữ cảnh nhiều hoặc làm leader mất thêm thời gian kiểm chứng.

## 11. Phiên bản pitch ngắn

> Mỗi cuối tuần, sinh viên hoặc leader nhóm AI mất khoảng 60 phút để tổng hợp Weekly Progress Report từ Git commit log, Discord chat và note cá nhân. Phần khó nhất là viết narrative mạch lạc từ raw data rời rạc: kết quả đạt được, điểm nghẽn và kế hoạch tuần tới. Mục tiêu là giảm thời gian làm report xuống dưới 20 phút mà không làm tăng số câu hỏi giảng viên phải hỏi lại. Hướng giải pháp là một workflow gồm script thu thập dữ liệu, AI phân nhóm và draft narrative, sau đó sinh viên/leader review trước khi gửi.

## 12. Các giả định cần xác nhận

- Nhóm hiện dùng Discord thật hay một công cụ chat khác như Zalo, Messenger, Slack?
- Git commit log có đủ rõ để hiểu task, hay cần thêm issue/PR/task board?
- Weekly report hiện nộp bằng Markdown, Word, Google Docs hay LMS?
- Giảng viên đánh giá cao phần nào nhất: tiến độ code, blocker, reflection hay kế hoạch tuần tới?
- Có cần report theo cá nhân từng thành viên hay theo nhóm chung?
- Số “60 phút/tuần” là cho một người viết toàn report nhóm hay cho mỗi thành viên viết phần riêng?
> **Lưu ý:** Các số liệu baseline 60 phút/người/tuần và 240 phút/nhóm 4 người/tuần lấy trực tiếp từ draft. Các target phụ như thời gian narrative dưới 8 phút, mức sửa draft dưới 30% là giả thuyết thiết kế, cần đo qua 2–3 tuần trước khi kết luận.

---

# Problem Card #3 — Tìm lại quyết định và câu trả lời cũ trong Discord

## 1. Tóm tắt Problem Card

| Thành phần | Nội dung |
|---|---|
| **Problem một câu** | Khi làm bài lab hoặc đồ án nhóm, sinh viên mất thời gian tìm lại quyết định/câu trả lời cũ trong Discord vì thông tin nằm rải rác ở nhiều kênh, thread và tin nhắn, khiến task dễ bị hiểu sai hoặc phải hỏi lại. |
| **Actor** | Thành viên nhóm lab/đồ án, đặc biệt là người nhận task sau buổi họp hoặc người vắng mặt một phần thảo luận. |
| **Thời điểm / bối cảnh** | Trước khi bắt đầu làm task, trước deadline, hoặc trước weekly meeting khi cần nhớ lại nhóm đã chốt gì. |
| **Bottleneck** | Tìm đúng message có ngữ cảnh và chuyển nó thành quyết định/action item rõ ràng. |
| **Baseline** | Chưa đo chính thức; ước tính 10–20 phút/lần tìm lại quyết định nếu phải đọc nhiều đoạn chat. |
| **Success metric chính** | Giảm thời gian tìm lại quyết định xuống dưới 5 phút/lần, đồng thời giảm số lần hỏi lại những câu đã được trả lời trong chat. |
| **Quick gut** | **Workflow** — rule/tag để chuẩn hóa quyết định, AI hỗ trợ search/tóm tắt, con người xác nhận trước khi dùng làm căn cứ. |

## 2. Mô tả vấn đề chi tiết

Trong quá trình làm lab hoặc đồ án nhóm, nhiều quyết định nhỏ được chốt trực tiếp trong Discord: deadline, owner, cách đặt tên file, hướng xử lý lỗi, link tài liệu, hoặc tiêu chí nộp bài. Những thông tin này thường không được chuyển ngay vào một tài liệu chính thức, nên sau vài ngày thành viên phải kéo lại lịch sử chat để tìm.
Vấn đề khó không chỉ là “search không ra”, mà là search ra quá nhiều đoạn rời rạc. Người tìm phải tự hiểu tin nhắn nào là câu hỏi, tin nhắn nào là ý kiến tạm thời, tin nhắn nào là quyết định cuối cùng và quyết định đó còn hiệu lực hay đã bị thay đổi.
Vấn đề cốt lõi là **tri thức vận hành của nhóm đang nằm trong chat dạng bán cấu trúc; khi cần hành động, sinh viên phải tốn công biến chat thành quyết định và task rõ ràng**.

## 3. Current workflow

### Workflow hiện tại — khoảng 10–20 phút/lần tìm lại

| Bước | Hoạt động | Input | Output | Thời gian ước tính |
|---:|---|---|---|---:|
| 1 | Nhớ mơ hồ keyword hoặc người từng nói | Trí nhớ cá nhân | Keyword ban đầu | 1–2 phút |
| 2 | Search trong Discord theo keyword/người/kênh | Discord search | Danh sách message liên quan | 2–5 phút |
| 3 | Mở từng message để đọc context trước/sau | Thread, channel history | Ngữ cảnh thảo luận | 5–10 phút |
| 4 | Tự xác định quyết định cuối cùng | Nhiều message rời rạc | Decision/action item tạm hiểu | 2–5 phút |
| 5 | Hỏi lại nhóm nếu chưa chắc | Discord chat | Xác nhận lại hoặc tranh luận lại | 5–15 phút, có thể chờ phản hồi |
| 6 | Làm task theo phần hiểu được | Quyết định đã hiểu | Task output | Tùy task |
```text
[Nhớ keyword mơ hồ]
        ↓
[Search Discord]
        ↓
[Đọc nhiều message/context]  ← BOTTLENECK
        ↓
[Xác định quyết định cuối]
        ↓
[Hỏi lại nếu chưa chắc]
        ↓
[Làm task]
```

### Bottleneck

Bottleneck nằm ở bước 3–4. Discord lưu message theo thời gian, trong khi người làm task cần thông tin theo dạng quyết định: “Ai làm gì, deadline nào, evidence ở đâu, còn hiệu lực không?”. Khi thiếu cấu trúc này, mỗi lần tìm lại đều giống như đọc lại một phần lịch sử nhóm.

## 4. Impact

- Thành viên mất 10–20 phút/lần để tìm lại thông tin đã từng được chốt.
- Nhóm phải hỏi lại cùng một câu, làm loãng chat và tốn thời gian người khác.
- Task có thể bị làm sai vì dùng quyết định cũ hoặc hiểu nhầm ý kiến tạm thời thành quyết định cuối.
- Weekly meeting mất thời gian nhắc lại bối cảnh thay vì tập trung xử lý blocker mới.

## 5. Success metrics

| Metric | Baseline | Target | Cách đo |
|---|---:|---:|---|
| Thời gian tìm lại quyết định | 10–20 phút/lần | Dưới 5 phút/lần | Bấm giờ từ lúc bắt đầu search đến lúc có câu trả lời dùng được |
| Số câu hỏi lặp lại trong chat | Chưa đo | Giảm ít nhất 30% sau 2 tuần | Đếm câu hỏi đã có câu trả lời trước đó |
| Tỷ lệ quyết định có owner/deadline rõ | Chưa đo | ≥ 80% decision quan trọng | Checklist sau mỗi buổi họp/thảo luận |
| Tỷ lệ summary cần sửa | Chưa có | Dưới 30% nội dung chính | Thành viên review summary của AI |

## 6. Non-AI alternative

| Phương án | Điểm mạnh | Giới hạn |
|---|---|---|
| Pin message quan trọng | Dễ làm, không cần tool mới | Pin quá nhiều sẽ loãng; vẫn thiếu summary theo task |
| Quy ước tag `[DECISION]`, `[TODO]`, `[BLOCKER]` | Giúp search dễ hơn | Cần mọi người nhớ dùng tag đều |
| Tạo file decision log thủ công | Rõ ràng, dễ kiểm tra | Tốn công cập nhật sau mỗi thảo luận |
| Dùng task board/Kanban | Quản lý owner và deadline tốt | Không lưu đủ lý do và context từ chat |
Non-AI alternative tốt nhất là tag + decision log. Đây nên là nền tảng bắt buộc, vì nếu dữ liệu chat quá lộn xộn thì AI cũng dễ tóm tắt sai.

## 7. AI hypothesis

AI có thể hỗ trợ bằng cách nhận input là đoạn chat đã lọc hoặc export theo kênh, sau đó:
- phát hiện các message có khả năng là quyết định, blocker hoặc action item;
- nhóm các message liên quan theo task/chủ đề;
- tạo decision log nháp gồm decision, owner, deadline, evidence link và mức độ chắc chắn;
- cảnh báo các quyết định thiếu owner/deadline hoặc có dấu hiệu bị thay đổi sau đó.
```text
[Discord messages đã chọn]
        ↓
[Rule lọc tag/channel/time range]
        ↓
[AI nhóm theo task và tóm tắt decision]
        ↓
[Human xác nhận decision log]
        ↓
[Task board/report dùng decision đã xác nhận]
```

### AI không nên làm gì

- Tự đọc private messages hoặc kênh không được nhóm đồng ý.
- Tự coi một ý kiến cá nhân là quyết định cuối nếu không có dấu hiệu xác nhận.
- Tự giao task, đổi deadline hoặc nhắc tên thành viên như kết luận trách nhiệm.
- Xóa hoặc sửa lịch sử chat.

## 8. Draft future workflow

### Workflow tương lai — mục tiêu dưới 5 phút/lần tìm lại

| Bước | Actor/hệ thống | Hoạt động | Thời gian mục tiêu |
|---:|---|---|---:|
| 1 | Nhóm | Khi chốt việc, dùng tag `[DECISION]`, `[TODO]`, `[BLOCKER]` hoặc react xác nhận | Trong lúc chat |
| 2 | Rule/script | Lọc message theo tag, channel và khoảng thời gian | < 1 phút |
| 3 | AI | Tạo decision log nháp và nhóm theo task | 1–2 phút |
| 4 | Thành viên/leader | Review, sửa và xác nhận decision log | 2–3 phút |
| 5 | Nhóm | Dùng decision log để làm task/report/meeting | Khi cần |

### Human boundary

Con người phải xác nhận decision log trước khi dùng. AI chỉ hỗ trợ tóm tắt và chỉ ra điểm thiếu; quyết định cuối cùng vẫn thuộc về nhóm.

### Fallback

Nếu AI summary sai hoặc thiếu ngữ cảnh, nhóm quay về decision log thủ công với tag `[DECISION]` và chỉ dùng AI để kiểm tra field thiếu, không dùng AI để diễn giải chat.

## 9. Boundary và rủi ro

| Rủi ro | Hậu quả | Kiểm soát |
|---|---|---|
| AI hiểu nhầm sarcasm/ý kiến tạm thời | Ghi sai quyết định | Chỉ nhận decision khi có tag hoặc xác nhận của leader |
| Thiếu quyền truy cập dữ liệu chat | Không chạy được workflow | Chỉ dùng export do nhóm chủ động cung cấp |
| Lộ thông tin riêng tư | Ảnh hưởng quyền riêng tư nhóm | Lọc dữ liệu, bỏ token/tài khoản/tin nhắn cá nhân |
| Nhóm không dùng tag đều | Dữ liệu đầu vào kém | Bắt đầu bằng quy ước đơn giản trước khi dùng AI |

## 10. Kế hoạch kiểm chứng nhanh

- Trong 1 tuần, ghi lại số lần thành viên phải tìm lại quyết định và thời gian mỗi lần.
- Chọn 1 kênh Discord của nhóm, áp dụng tag `[DECISION]`, `[TODO]`, `[BLOCKER]` cho các quyết định mới.
- Cuối tuần, thử tạo decision log nháp từ các message đã tag.
- So sánh thời gian tìm lại quyết định trước/sau và số câu hỏi lặp lại trong chat.

### Quyết định ban đầu

**Not Yet** cho AI workflow đầy đủ, vì trước tiên nhóm cần chuẩn hóa tag/decision log. Sau khi có dữ liệu có cấu trúc hơn, có thể chuyển sang **Workflow** với AI tóm tắt và human review.

## 11. Phiên bản pitch ngắn

> Khi làm lab nhóm, nhiều quyết định quan trọng nằm rải rác trong Discord. Thành viên phải search, đọc lại context và hỏi lại để biết nhóm đã chốt gì, mất khoảng 10–20 phút/lần và dễ hiểu sai. Mục tiêu là giảm thời gian tìm lại quyết định xuống dưới 5 phút/lần. Hướng phù hợp là chuẩn hóa tag/decision log trước, sau đó dùng AI để tóm tắt decision log nháp và để người thật xác nhận.

## 12. Các giả định cần xác nhận

- Nhóm có dùng Discord làm kênh chính không?
- Thành viên có sẵn sàng dùng tag `[DECISION]`, `[TODO]`, `[BLOCKER]` không?
- Có thể export hoặc copy chat mà không vi phạm riêng tư nhóm không?
- Pain lớn nhất là tìm lại decision, owner/deadline hay evidence/link?
