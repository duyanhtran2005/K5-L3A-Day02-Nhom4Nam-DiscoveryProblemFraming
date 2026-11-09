# Báo cáo cá nhân — 2A202603494_TranAnhDuy

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Trần Anh Duy
- MSSV: 2A202603494
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: 4Nhom
- Link repo nhóm: https://github.com/duyanhtran2005/K5-L3A-Day02-Nhom4Nam-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi nhóm làm một bài lab, tôi muốn nắm rõ người phụ trách, tiến độ và trạng thái commit của từng phần việc, để nắm bắt thông tin và quản lý các phần trước khi nộp bài. | Trưởng nhóm và các thành viên | Mỗi buổi họp mất 15 phút hỏi lại tiến độ, trước khi nộp bài tốn 10 phút kiểm tra repo. |
| 2 | Tốn thời gian | Khi cần tìm lại quyết định hoặc ý kiến mà nhóm đã thống nhất, tôi muốn xác định đủ và đúng quyết định kèm lý do, để không phải thảo luận hay hỏi lại từ đầu. | Các thành viên trong nhóm | Tốn 30 phút để tìm đọc lại các quyết định và ý kiễn kèm lý do. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi đọc đề bài lab có nhiều file hướng dẫn, tôi muốn hiểu bài lab và xác định chính xác đầu ra của từng checkpoint, để lên kế hoạch làm bài hay phân công cho các thành viên. | Trưởng nhóm, Học viên | Tốn 40 phút từ lúc đọc các file hướng dẫn đến bắt tay vào làm bài. |
| 4 | Pain từ người khác | Khi vắng một buổi họp, tôi muốn nắm được nội dung buổi họp, các quyết định và những việc nên làm tiếp theo, để tiếp tục phần việc của mình mà không cần phải hỏi lại mọi người. | Thành viên vắng họp | Tốn 20 - 30 phút để nắm rõ thông tin buổi họp đã vắng mặt. |
| 5 | Lặp lại | Khi kết thúc ngày làm việc, tôi muốn ghi lại việc đã làm và tiến độ công việc hiện tại, để hôm sau tiếp tục công việc một cách trôi chảy mà không mất thời gian nhớ lại. | Intern | Mỗi ngày tốn 15 - 20 phút |
| 6 | Pain từ người khác | Khi đồng nghiệp cần hiểu và tiếp tục phần việc tôi bàn giao, họ muốn biết trạng thái và cách sử dụng, để không phải nhờ tôi giải thích. | Đồng nghiệp, intern | Đồng nghiệp hỏi gần 10 lần, mỗi lần giải thích tốn gần 30 phút |


**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Bàn giao công việc cho đồng nghiệp (#6) | Actor và chi phí thời gian rõ, có thể vẽ quy trình bàn giao. | Đồng nghiệp cần những thông tin cụ thể nào? |
| 2 | Nắm được thông tin buổi họp đã vắng mặt (#4) | Actor rõ và có thể tách các bước tìm thông tin, xác định quyết định, việc được giao và hỏi lại chỗ thiếu. | Quyền truy cập dữ liệu khó (thông tin từ biên bản họp hoặc từ người dự họp)|
| 3 | Hiểu và lên kế hoạch làm bài lab (#3) | Pain nhiều người gặp | Phạm vi rộng, các bước đọc, đối chiếu và lên kế hoạch để phân tích. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi đồng nghiệp cần hiểu và tiếp tục phần việc tôi bàn giao, họ muốn biết trạng thái và cách sử dụng, để không phải nhờ tôi giải thích. |
| Actor | Đồng nghiệp tiếp nhận phần việc; thực tập sinh bàn giao và giải thích. |
| Thời điểm / bối cảnh | Sau khi tôi bàn giao một phần việc trong kỳ thực tập, lúc đồng nghiệp bắt đầu tiếp nhận hoặc sử dụng kết quả. |
| Quy trình hiện tại (3–7 bước) | 1. Đồng nghiệp mở phần việc đã bàn giao; 2. Gặp chỗ chưa rõ và hỏi tôi; 3. Tôi tìm lại ngữ cảnh, trạng thái và cách thực hiện; 4. Tôi giải thích hoặc hướng dẫn lại; 5. Đồng nghiệp xác nhận đã hiểu và tiếp tục làm. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4, giải thích lại cho đồng nghiệp: gần 30 phút/lần. |
| Impact (nếu không giải thì sao) | gần 30 phút/lần hỏi, khoảng 10 lần hỏi thì thời gian giải thích gần 300 phút. |
| Success metric (baseline → target) | Thời gian giải thích từ gần 30 xuống dưới 10 phút/lần; bấm giờ 5 lần hỏi tiếp theo và kiểm xem đồng nghiệp có tiếp tục được việc không. |
| Phương án không dùng AI | Bản bàn giao ngắn ghi trạng thái, cách sử dụng, việc tiếp theo, chỗ dễ nhầm và người có thể hỏi. |
| Giả thuyết về AI (nếu có) | Nếu thông tin nằm rải trong nhiều tài liệu được phép sử dụng, AI có thể gợi ý bản tóm tắt; tôi kiểm lại trước khi bàn giao. |
| Cảm nhận nhanh | No AI trước; thử mẫu bàn giao và đo lại số lần hỏi. |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — riêng bước giải thích gần 30 phút/lần

[1 Đồng nghiệp mở phần việc] → [2 Hỏi chỗ chưa rõ]
→ [3 Tôi tìm lại ngữ cảnh] → [4 Tôi giải thích lại: gần 30 phút] ← BOTTLENECK
→ [5 Đồng nghiệp xác nhận và tiếp tục]
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi vắng một buổi họp, tôi muốn nắm được nội dung buổi họp, các quyết định và những việc nên làm tiếp theo, để tiếp tục phần việc của mình mà không cần phải hỏi lại mọi người. |
| Actor | Thành viên vắng họp; người dự họp nếu phải giải thích lại. |
| Thời điểm / bối cảnh | Sau một buổi họp nhóm tôi không tham dự, trước khi tiếp tục phần việc của mình. |
| Quy trình hiện tại (3–7 bước) | 1. Tìm thông tin về buổi họp; 2. Đọc ghi chú hoặc tin nhắn có sẵn; 3. Xác định thông tin hay nội dung buổi họp; 4. Xác định việc tiếp theo và deadline liên quan đến mình; 5. Hỏi người dự họp chỗ còn thiếu. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2, đọc và ghép thông tin rời rạc, khoảng 8 phút trong tổng 20–30 phút. |
| Impact (nếu không giải thì sao) | 20–30 phút để nắm rõ thông tin buổi họp đã vắng. Phải hỏi lại nếu hiểu thiếu quyết định hoặc việc được giao. |
| Success metric (baseline → target) | Thời gian bắt kịp từ 20–30 phút xuống dưới 10 phút; đo bằng bấm giờ ở lần vắng họp tiếp theo và nhờ một người dự họp xác nhận ba mục: quyết định, việc cần làm, deadline. |
| Phương án không dùng AI | Cuối buổi họp, ghi bản tóm tắt chung gồm quyết định cuối, lý do, việc tiếp theo, người phụ trách và deadline. |
| Giả thuyết về AI (nếu có) | Nếu nhóm có ghi chú hoặc bản ghi được phép sử dụng, AI có thể tạo bản tóm tắt nháp; người dự họp phải kiểm lại trước khi chia sẻ. |
| Cảm nhận nhanh | No AI trước; thử ghi chú họp có cấu trúc. |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — tổng 20–30 phút

[1 Tìm thông tin buổi họp: khoảng 3 phút] → [2 Đọc ghi chú/tin nhắn: khoảng 8 phút] ← BOTTLENECK → [3 Xác định quyết định cuối: khoảng 6 phút] → [4 Xác định việc và hạn: khoảng 5 phút] → [5 Hỏi chỗ thiếu: khoảng 3 phút]

```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi đọc đề bài lab có nhiều file hướng dẫn, tôi muốn hiểu bài lab và xác định chính xác đầu ra của từng checkpoint, để lên kế hoạch làm bài hay phân công cho các thành viên. |
| Actor | Tôi trong vai trò trưởng nhóm; các thành viên nhận phần việc. |
| Thời điểm / bối cảnh | Đầu bài lab, từ lúc mở các file hướng dẫn đến lúc bắt đầu làm bài hoặc giao việc. |
| Quy trình hiện tại (3–7 bước) | 1. Xác định file hướng dẫn cần đọc; 2. Đọc các checkpoint; 3. Đối chiếu worksheet, rubric và mẫu báo cáo; 4. Ghi đầu ra, người phụ trách và deadline; 5. Bắt đầu làm hoặc phân công cho nhóm. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, đối chiếu đầu ra từng checkpoint giữa các file, khoảng 17 phút trong tổng 40 phút. |
| Impact (nếu không giải thì sao) | 40 phút từ lúc đọc hướng dẫn đến lúc bắt tay làm bài; nếu hiểu sai đầu ra, nhóm có thể phải sửa lại. |
| Success metric (baseline → target) | Thời gian từ lúc mở hướng dẫn đến lúc bắt đầu làm bài từ 40 phút xuống dưới 20 phút; đo bằng bấm giờ ở bài lab tiếp theo và đối chiếu danh sách đầu ra với tài liệu gốc. |
| Phương án không dùng AI | Lập bảng checkpoint gồm người làm, đầu ra, file cần điền và tiêu chí kiểm, kèm link tới đúng mục trong hướng dẫn. |
| Giả thuyết về AI (nếu có) | AI có thể lập nháp bảng yêu cầu từ các file, nhưng trưởng nhóm phải kiểm lại từng dòng trong tài liệu gốc. |
| Cảm nhận nhanh | No AI trước; thử bảng đầu ra và phân công trước khi cân nhắc AI. |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 40 phút từ lúc đọc đề đến lúc bắt tay làm

[1 Xác định file cần đọc: khoảng 3 phút] → [2 Đọc các checkpoint: khoảng 12 phút] → [3 Đối chiếu worksheet, rubric, mẫu: khoảng 17 phút] ← BOTTLENECK → [4 Ghi đầu ra và người phụ trách: khoảng 5 phút] → [5 Bắt đầu/giao việc: khoảng 3 phút]
```

### Card muốn pitch nhất

- Card số: 1 — Đồng nghiệp hỏi lại về phần việc được bàn giao.
- Vì sao: Gần 10 lần hỏi và gần 30 phút giải thích mỗi lần; nếu xác nhận được thời gian và nguyên nhân, đây là pain lớn nhất trong ba card.
- Câu hỏi muốn nhóm phản biện: Đồng nghiệp phải hỏi lại vì thiếu thông tin bàn giao, hay vì phần việc vốn khó và cần người hướng dẫn dù tài liệu đã đầy đủ?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card #1: Gần 10 lần hỏi chưa chứng minh nguyên nhân là thiếu thông tin bàn giao; công việc cũng có thể cần hướng dẫn trực tiếp. | Đồng ý | Cần ghi nội dung câu hỏi ở những lần tiếp theo để xác định nguyên nhân. |
| Card #2: Chưa rõ buổi họp có ghi chú để đọc hay không; 8 phút ở bước đọc chưa được đo riêng. | Đồng ý | Cần kiểm nguồn thông tin của lần vắng họp gần nhất và xác nhận thời gian đọc. |
| Card #3: Giảm thời gian từ 40 xuống dưới 20 phút chưa bảo đảm hiểu đúng yêu cầu. | Đồng ý | Cần thêm điều kiện không bỏ sót đầu ra checkpoint khi đánh giá thành công. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
