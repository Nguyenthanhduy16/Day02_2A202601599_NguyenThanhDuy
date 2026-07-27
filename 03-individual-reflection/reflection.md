# Individual Reflection — Day 02

**Học viên:** Nguyễn Thanh Duy
**Mã học viên:** 2A202601599

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Liệt kê 8 problems từ bối cảnh học tập, lab, nhóm và đời sống cá nhân. | Có đủ pool ban đầu để chọn top 3 thay vì nhảy ngay vào một solution AI. |
| Pitch Problem Card | Chuẩn bị và pitch 3 Problem Cards cá nhân: lập kế hoạch cá nhân, Weekly Lab Report, tìm lại quyết định trong Discord. | Trình bày được actor, workflow, bottleneck, metric và mức phù hợp với AI cho từng candidate cá nhân. |
| Challenge bài của bản thân | Tự kiểm tra xem từng problem có quá rộng không, metric có đo được không, AI có cần thiết không. | Loại bớt cách nghĩ “làm Agent cho ngầu”, chuyển sang Workflow có human review. |
| Challenge bài của bạn khác | Khi nghe các candidate khác, tập trung hỏi về actor, bottleneck, metric, evidence và boundary thay vì hỏi ngay solution. | Giúp nhóm so sánh các bài theo tiêu chí chung, nhất là khi chọn giữa CV/JD, tìm phòng trọ và sàng lọc paper. |
| Gom trùng / cluster | Cùng nhóm nhìn các candidate theo cụm: hồ sơ/học thuật, báo cáo/năng suất học tập, tra cứu tri thức, tìm kiếm/đời sống. | Nhóm thấy bài CV/Cover Letter theo JD thuộc cụm hồ sơ/học thuật, có workflow và output rõ để làm pilot. |
| Chọn candidate problem | Ban đầu tôi có problem cá nhân muốn pitch, nhưng sau khi so sánh nhóm đồng thuận chọn **Điều chỉnh CV và Cover Letter theo JD**. | Tôi chấp nhận đổi trọng tâm từ problem cá nhân sang candidate nhóm vì bài CV/JD có baseline, workflow và boundary rõ hơn cho bài nộp nhóm. |
| Validation / research | Góp phần giữ các số liệu ở mức giả thuyết cần kiểm chứng: 20 phút/hồ sơ là self-report của một problem owner, chưa phải baseline đại diện. | Group report không khẳng định quá mức; quyết định chuyển sang pilot nhỏ thay vì tuyên bố solution đã hiệu quả. |
| Workflow nhóm | Rà workflow hiện tại và workflow tương lai cho bài CV/JD: đọc JD, đối chiếu master CV, chọn evidence, chỉnh CV/CL, review và tự nộp. | Nhìn rõ AI chỉ nên hỗ trợ map evidence và draft, còn người dùng vẫn verify/edit/submit. |
| Problem Statement | Góp phần làm rõ actor, bottleneck, impact, success metric và boundary cho Problem Statement v0/v1. | Problem Statement tránh mục tiêu quá xa như “tăng tỷ lệ được tuyển” và chuyển sang metric đo được trong pilot. |
| Rule / Workflow / Agent | So sánh No AI/template, Rule, Workflow và Agent cho bài CV/JD. | Nhóm chọn Workflow: Rule validate/extract, AI map evidence/draft, human verify/edit/submit; không chọn Agent. |
| Decision | Đồng thuận với quyết định **Go với pilot giới hạn**, **Not Yet cho production integration hoặc auto-submit**. | Quyết định dựa trên rủi ro hallucination/overclaim/privacy và khả năng rollback trước khi nộp hồ sơ thật. |

## 2. Bảng dùng AI trong quá trình làm bài

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm góc nhìn problem quanh học tập/lab sau khi đã có vài ý ban đầu. | Giúp mở rộng từ 2 problem ban đầu thành nhiều nhóm pain khác nhau. | Một số ý quá rộng như “trợ lý học tập toàn năng”, khó đo trong lab. | Giữ lại các problem có workflow thật, actor rõ và metric đo được. |
| Problem Card | Nhờ AI cấu trúc card chi tiết hơn theo template. | Giúp không sót field: actor, context, workflow, bottleneck, metric, boundary. | AI có xu hướng thêm số liệu chưa kiểm chứng hoặc viết nghe quá chắc. | Đánh dấu các số liệu là baseline/giả thuyết cần đo, không trình bày như sự thật đã kiểm chứng. |
| Workflow | Dùng AI hỗ trợ chuyển workflow thành bảng và sơ đồ text. | Workflow dễ đọc hơn, thấy rõ bước nghẽn và human boundary. | Ban đầu AI có thể đưa AI vào quá nhiều bước hoặc đẩy sang Agent quá sớm. | Thu hẹp AI về bước map evidence/draft; các quyết định và nộp hồ sơ vẫn do người thật làm. |
| Research/validation | Dùng AI để gợi ý cách kiểm chứng nhanh và các solution/pattern cần so sánh. | Có thêm ý tưởng metric như time reduction, unsupported claim, relevance/readability và human approval. | AI không thể xác nhận pain thật nếu chưa có interview/log; link hoặc claim về tool cũng cần kiểm tra. | Giữ validation ở mức “một phần”, yêu cầu pilot và không dùng tỷ lệ được tuyển làm metric chính. |
| Problem Statement | Dùng AI để kiểm tra tính đầy đủ của actor, workflow, bottleneck, impact. | Giúp câu Problem Statement rõ hơn và không solution-first. | Một số câu ban đầu dễ hứa quá mức, ví dụ cá nhân hóa CV sẽ làm tăng khả năng được tuyển. | Sửa metric thành thời gian ≤10 phút/hồ sơ, 0 unsupported claim, relevance/readability ≥4/5. |
| Rule / Workflow / Agent | Dùng AI để phản biện mức phù hợp. | Giúp nhận ra No AI/template và Rule vẫn là baseline/fallback cần có. | AI dễ đề xuất automation rộng như tự tìm job hoặc tự nộp hồ sơ. | Chọn Workflow, không chọn Agent; cấm auto-submit và yêu cầu người dùng approve bản cuối. |
| Decision | Dùng AI để tự phản biện Go/Not Yet/No-Go. | Giúp nhìn rõ rủi ro hallucination, overclaim, privacy và rollback. | AI không biết dữ liệu thật của người tìm việc nếu không có master CV/JD cụ thể. | Chốt Go chỉ cho pilot giới hạn; Not Yet cho production integration hoặc auto-submit. |

## 3. Reflection cá nhân

Điều tôi học được rõ nhất trong lab này là bắt đầu từ problem khó hơn nhưng đúng hơn bắt đầu từ solution. Lúc đầu tôi dễ nghĩ theo hướng “có AI thì để AI tự lập kế hoạch/tự viết báo cáo”, nhưng khi vẽ workflow từng bước, tôi thấy phần đáng giải quyết thường nằm ở một vài bottleneck cụ thể, không phải toàn bộ quy trình.

Khi chuẩn bị top 3 Problem Cards cá nhân, tôi nhận ra một problem tốt cần có actor và tình huống đủ cụ thể. Ví dụ “quản lý thời gian tốt hơn” là quá rộng, nhưng “mỗi cuối ngày A mất 1–2 giờ để biến task và deadline thành lịch khả thi” thì có thể đo, có workflow và có boundary. Tuy nhiên khi vào phần nhóm, tôi cũng thấy rằng problem cá nhân tốt chưa chắc là candidate nhóm tốt nhất. Nhóm đã chọn bài **Điều chỉnh CV và Cover Letter theo JD** vì workflow rõ hơn, có baseline ban đầu khoảng 20 phút/hồ sơ và có thể thiết kế pilot nhỏ.

AI hữu ích nhất ở vai trò phản biện và cấu trúc hóa. AI giúp tôi không quên các trường quan trọng như success metric, non-AI alternative, human boundary và fallback. Nhưng AI cũng có điểm nguy hiểm: nó có thể viết rất thuyết phục ngay cả khi dữ liệu còn yếu. Vì vậy trong group report, tôi thấy việc ghi rõ “20 phút/hồ sơ mới là self-report của một problem owner” là cần thiết; không nên biến nó thành kết luận đại diện cho mọi người tìm việc.

Nếu làm lại, tôi sẽ validation sớm hơn. Với bài CV/JD, tôi sẽ hỏi thêm 3–5 người đang tìm việc xem họ thật sự mất bao lâu để chỉnh CV/Cover Letter cho mỗi JD, họ dùng template hay tool nào, và phần nào làm họ mất thời gian nhất. Tôi cũng sẽ bấm giờ từng bước trên vài JD thật để biết bottleneck nằm ở đọc JD, map evidence, viết lại bullet points hay review claim.

Đóng góp quan trọng nhất của tôi là giữ bài toán ở mức **Workflow có human review**. Với bài CV/JD, AI có thể hỗ trợ map yêu cầu trong JD với evidence có sẵn trong master CV và tạo draft CV/Cover Letter. Nhưng AI không được bịa kỹ năng, không được nâng khống thành tích, không được tự chọn job và không được tự nộp hồ sơ. Người dùng phải verify từng claim, sửa giọng văn và approve bản cuối. Đây là ranh giới làm cho hướng AI có thể thử nghiệm mà vẫn kiểm soát rủi ro.

## 4. Tự kiểm tra hiểu bài cá nhân

| Mạch lập luận | Câu trả lời ngắn của tôi |
|---|---|
| Problem | Người muốn tìm việc mất khoảng 20 phút/hồ sơ để điều chỉnh CV và Cover Letter theo từng JD; với 10–20 hồ sơ/kỳ, effort lặp lại đủ lớn để đáng kiểm tra. |
| Workflow | Chọn JD → đọc/trích tiêu chí → đối chiếu master CV → chọn evidence → chỉnh CV → viết Cover Letter → review và tự nộp. |
| Bottleneck | Đối chiếu yêu cầu được viết tự do trong JD với kinh nghiệm thật, rồi diễn đạt lại CV/Cover Letter phù hợp mà không bịa hoặc nâng khống claim. |
| Metric | Pilot pass nếu median time không quá 10 phút/hồ sơ và giảm ít nhất 40% so với baseline thủ công; 0 unsupported claim; relevance/readability đạt tối thiểu 4/5. |
| Boundary | Chỉ dùng JD và master CV do ứng viên cung cấp; không suy diễn dữ liệu nhạy cảm; không bịa claim; không tự chọn job; không tự nộp hồ sơ; ứng viên approve bản cuối. |
| AI fit | Chọn Workflow vì đường đi cố định nhưng mapping/drafting có độ mơ hồ cao; Rule hỗ trợ validate/extract, AI hỗ trợ map/draft, human verify/edit/submit. |
| Decision | Go với pilot giới hạn; Not Yet cho production integration hoặc auto-submit vì baseline còn yếu và rủi ro hallucination/overclaim/privacy vẫn cần kiểm soát. |

## 5. Checklist cuối bài

- [x] Cá nhân có 5+ problems từ trải nghiệm thật.
- [x] Có top 3 Problem Cards đủ rõ để pitch.
- [x] Mỗi card có current workflow và future workflow/direction.
- [x] Có metric, boundary, non-AI alternative và AI hypothesis.
- [x] Reflection cá nhân đã khớp với candidate nhóm chọn: Điều chỉnh CV và Cover Letter theo JD.
- [x] Có reflection về cách dùng AI, chỗ AI hữu ích, chỗ AI hời hợt và phần tôi tự sửa.
- [x] Tự giải thích được mạch problem → workflow → metric → boundary → AI fit → decision của nhóm.

## 6. Các điểm cần cá nhân hóa trước khi nộp chính thức

- Nếu bạn có câu hỏi challenge cụ thể đã hỏi trong buổi nhóm, nên thêm nguyên văn 1–2 câu vào mục “Challenge bài của bạn khác”.
- Nếu nhóm có timer log hoặc interview thật sau buổi lab, hãy thay các chỗ “self-report/giả thuyết cần kiểm chứng” bằng số liệu thật.
- Nếu vai trò của bạn trong nhóm khác “thành viên góp ý/challenge/workflow”, hãy sửa bảng vai trò cho sát thực tế hơn.
