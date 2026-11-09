# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: 4Nam
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Trưởng nhóm mất thời gian xác định đúng đầu ra từng checkpoint từ nhiều file hướng dẫn trước khi lên kế hoạch và phân công bài lab.
- Quyết định cuối: Go / Not Yet / No-Go

---

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện gợi ý |
|---:|---|---|---|---|---|
| 1 | Trần Anh Duy (D1) | Khi đồng nghiệp tiếp nhận phần việc tôi bàn giao, họ cần biết trạng thái và cách dùng để tiếp tục mà không phải hỏi lại. | Đồng nghiệp tiếp nhận; thực tập sinh bàn giao | Giải thích lại gần 30 phút/lần; CP1 ghi gần 10 lần hỏi. | Đồng nghiệp hỏi lại vì thiếu thông tin gì? |
| 2 | Trần Anh Duy (D2) | Khi vắng họp, tôi cần nắm nội dung, quyết định và việc tiếp theo để tiếp tục phần mình. | Thành viên vắng họp | Đọc và ghép thông tin rời rạc khoảng 8 phút, là phân bổ trong tổng 20–30 phút và cần xác nhận. | Bước nào mất nhiều thời gian nhất khi bắt kịp buổi họp? |
| 3 | Trần Anh Duy (D3) | Khi đọc đề lab có nhiều file, tôi cần xác định đúng đầu ra từng checkpoint để lập kế hoạch và phân công. | Trưởng nhóm; học viên nhận việc | Đối chiếu yêu cầu giữa các file khoảng 17 phút trong tổng 40 phút; phân bổ cần xác nhận. | 17 phút đối chiếu là số đo hay ước lượng? |
| 4 | Nguyễn Nhựt Linh (L1) | Khi bắt đầu Codelab nhiều giai đoạn, tôi cần nắm đủ nhiệm vụ và deliverable để làm đúng trọng tâm. | Sinh viên làm Codelab | Đọc và đối chiếu README/tài liệu, khoảng 15 phút hoặc hơn. | README đã đủ để biết việc cần làm chưa? |
| 5 | Nguyễn Nhựt Linh (L2) | Khi học công nghệ AI mới, tôi cần tổng hợp các nguồn đáng tin để hiểu đúng và áp dụng. | Sinh viên học AI | Tìm, đọc, chọn lọc nhiều nguồn, khoảng 30 phút/chủ đề. | Làm sao biết bản tổng hợp đúng với nguồn? |
| 6 | Nguyễn Nhựt Linh (L3) | Khi tích hợp LLM API gặp lỗi, tôi cần xác định nguyên nhân và khắc phục để tiếp tục thử nghiệm. | Sinh viên/lập trình viên dùng LLM API | Đọc log, tìm nguyên nhân, sửa cấu hình: khoảng 15–30 phút/sự cố; CP1 ghi khoảng 5 lần lỗi. | Loại lỗi nào xảy ra nhiều nhất? |
| 7 | Trần Dương Trung Tính (T1) | Khi trang danh sách sách tràn ngang trên điện thoại, tôi cần tìm phần tử gây lỗi để sửa trước bàn giao. | Người làm giao diện web | Đối chiếu chiều rộng thẻ sách và vùng chứa: dự kiến 65 phút trong tổng khoảng 180 phút. | Tìm phần tử gây tràn có thật là bước chậm nhất không? |
| 8 | Trần Dương Trung Tính (T2) | Khi tổng tiền giỏ hàng không đổi sau khi tăng số lượng, tôi cần tái hiện và tìm nguyên nhân để sửa trước bàn giao. | Người xử lý lỗi web bán quần áo | Kiểm tra luồng số lượng, giá và tổng tiền: dự kiến 45–55 phút trong tổng 3–4 giờ. | Lỗi tổng tiền còn tái hiện được không? |
| 9 | Trần Dương Trung Tính (T3) | Khi nối trang danh sách quần áo với API, tôi cần hiểu request/response để hiển thị và xử lý đúng các trạng thái. | Người tích hợp frontend với API | Viết kết nối và xử lý trạng thái: dự kiến 120–180 phút; baseline tổng 1–2 ngày. | Chờ thông tin API hay viết kết nối mất thời gian hơn? |
| 10 | Trương Lợi Vĩ (V1) | Khi chọn tài liệu nghiên cứu, tôi cần đánh giá nguồn công bố và phương pháp để chọn tài liệu đáng tin. | Người nghiên cứu | Đánh giá uy tín nguồn và phương pháp: ước tính 15 phút/bài hội nghị hoặc 30–60 phút/bài dài. | Bạn dùng tiêu chí nào để đánh giá bài báo? |
| 11 | Trương Lợi Vĩ (V2) | Khi quản lý tài liệu tham khảo, tôi cần bổ sung metadata còn thiếu để danh mục chính xác. | Người nghiên cứu dùng Zotero | Tra lại nguồn để bổ sung metadata: ước tính 1–2 phút/tài liệu, chưa xác nhận là bước chậm nhất. | Lần gần nhất có bao nhiêu tài liệu thiếu metadata? |
| 12 | Trương Lợi Vĩ (V3) | Khi theo dõi nhiệm vụ sinh viên, tôi cần xác định người chưa hoàn thành để nhắc đúng hạn. | Người quản lý/mentor; sinh viên nhận nhắc | Kiểm tra tiến độ và xác định người cần nhắc; chưa có số phút đo được. | Một đợt có bao nhiêu sinh viên cần nhắc? |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Hiểu yêu cầu lab | D3, L1 | Đầu việc và đầu ra nằm ở nhiều file; người học phải đọc, đối chiếu rồi mới bắt đầu làm. Hai card cùng pattern nhưng phạm vi đo khác nhau: Duy ghi 40 phút từ mở tài liệu đến bắt tay làm, Linh ghi khoảng 15 phút để nắm yêu cầu chính. |
| B — Tìm và đánh giá tri thức | L2, V1, V2 | Tìm, đối chiếu hoặc xác minh thông tin từ nhiều nguồn trước khi dùng cho học tập/nghiên cứu. V2 hẹp hơn và liên quan metadata thư mục. |
| C — Chuyển giao và theo dõi việc | D1, D2, V3 | Thông tin về trạng thái, quyết định, việc tiếp theo hoặc người cần nhắc chưa đến đúng người ở đúng thời điểm. |
| D — Xử lý lỗi và tích hợp kỹ thuật | L3, T1, T2, T3 | Người làm kỹ thuật phải khoanh vùng lỗi hoặc đối chiếu dữ liệu/cấu hình trước khi sửa và kiểm tra lại. |

### 2.3. Opportunity Solution Tree rút gọn

```text
OUTCOME ĐỀ XUẤT: Giảm thời gian sinh viên xác định đúng và đủ đầu ra của một bài lab,
                  từ lúc mở hướng dẫn đến lúc sẵn sàng bắt đầu, không bỏ sót yêu cầu.
├── Opportunity A: Yêu cầu và đầu ra nằm rải ở nhiều file hoặc nhiều giai đoạn.
├── Opportunity B: Người học phải tự đối chiếu hướng dẫn, worksheet và tiêu chí chấm.
└── Opportunity C: Khó biết mục nào phải làm cá nhân, mục nào làm nhóm và ghi vào file nào.
```
Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- “Tạo checklist tự động” và “AI đọc README giúp” là **phương án**, không phải pain ở tầng opportunity. Đây là ví dụ phân loại từ các giả thuyết trong card, **chưa khẳng định nhóm đã thực sự nêu rồi gạch bỏ**; sau buổi thảo luận, thay bằng ý nhóm đã gạch bỏ thật (nếu có).

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Hiểu yêu cầu/đầu ra lab (D3) | 5 | 5 | 4 | 4 | 5 | 5 | 5 | **33** |
| Xử lý lỗi LLM API (L3) | 5 | 5 | 4 | 4 | 4 | 5 | 4 | **31** |
| Đồng nghiệp hỏi lại sau bàn giao (D1) | 5 | 4 | 4 | 5 | 3 | 4 | 3 | **28** |

**Candidate được chọn:** Khi đọc đề lab có nhiều file, trưởng nhóm phải xác định đúng đầu ra từng checkpoint để lên kế hoạch và phân công trước khi bắt đầu.

**Vì sao chọn:** Trong 12 card, D3 có actor, quy trình 5 bước, baseline tổng 40 phút và bước nghẽn dự kiến (khoảng 17 phút) đủ cụ thể để phân tích; L1 cho thấy một thành viên khác cũng gặp pattern này. Có thể hỏi sinh viên nhóm khác ngay trong buổi lab và thử cả hướng không dùng AI.

**Vì sao tạm không chọn hai candidate shortlist còn lại:** Lỗi LLM API có bằng chứng lặp lại nhưng nhiều nguyên nhân khác nhau (quota, key, model, kết nối), cần thu hẹp một loại lỗi. Bàn giao công việc cho đồng nghiệp có impact cao nhưng chưa tách được nguyên nhân và việc kiểm chứng phụ thuộc đồng nghiệp tiếp nhận ngoài nhóm.

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Sinh viên gặp khó khăn trong việc xác định đầy đủ yêu cầu và đầu ra của bài lab vì thông tin được phân tán ở nhiều tệp như README, worksheet và các tài liệu hướng dẫn khác. | Value | 5 | 2 | Có |
| 2 | Việc đọc và đối chiếu nhiều tệp hướng dẫn làm tăng thời gian chuẩn bị trước khi bắt đầu thực hiện bài lab. | Value | 5 | 2 | Có |
| 3 | Sinh viên có nguy cơ bỏ sót checkpoint, deliverables, định dạng tệp hoặc yêu cầu nộp bài khi thông tin chưa được tổng hợp rõ ràng. | Value | 5 | 1 | Có |
| 4 | Sinh viên có thể sử dụng một công cụ AI để tổng hợp thông tin từ nhiều tệp thành danh sách công việc có cấu trúc mà không cần nhiều kiến thức kỹ thuật. | Usability | 4 | 2 | Có |
| 5 | AI có khả năng trích xuất chính xác nhiệm vụ, đầu ra, thứ tự checkpoint và dẫn chiếu đến tài liệu nguồn. | Feasibility | 5 | 1 | Có |
| 6 | Giải pháp có thể được phát triển dựa trên các mô hình AI và công nghệ hiện có mà không cần huấn luyện mô hình riêng hoặc tích hợp sâu với hệ thống LMS. | Viability | 3 | 2 | Không |

Giả định nhóm kiểm chứng trong buổi này:
Nhóm ưu tiên kiểm chứng A1, A2 và A3 vì đây là những giả định liên quan trực tiếp đến mức độ tồn tại và ảnh hưởng của vấn đề đối với sinh viên. Cụ thể:

- **A1:** Sinh viên có thực sự gặp khó khăn khi thông tin về bài lab được phân tán ở nhiều tài liệu hay không?
- **A2:** Việc đọc và đối chiếu tài liệu có thực sự chiếm một phần đáng kể trong thời gian chuẩn bị bài lab không?
- **A3:** Việc thiếu một bản tổng hợp yêu cầu có dẫn đến nhầm lẫn hoặc bỏ sót nhiệm vụ, checkpoint và yêu cầu nộp bài không?

### 3.2. Kiểm chứng
**Cách đã dùng:** Phỏng vấn bán cấu trúc (Semi-structured Interview).

Nhóm lựa chọn phương pháp phỏng vấn bán cấu trúc để tìm hiểu trải nghiệm của sinh viên khi đọc và thực hiện các bài lab có nhiều tài liệu hướng dẫn. Nội dung phỏng vấn tập trung vào những tình huống đã xảy ra, hành vi xử lý, cách khắc phục và thời gian người tham gia đã sử dụng.

Các câu hỏi được xây dựng theo nguyên tắc **The Mom Test**, tập trung vào trải nghiệm thực tế thay vì hỏi về ý tưởng giải pháp hoặc những tình huống giả định.

**Các câu hỏi phỏng vấn:**

1. Lần gần nhất thực hiện một bài lab có nhiều tệp hướng dẫn là khi nào?
2. Hãy mô tả cách đã xác định các nhiệm vụ và đầu ra cần hoàn thành trong bài lab đó.
3. Trong quá trình thực hiện, có tình huống nào phải tìm lại thông tin hoặc xác nhận yêu cầu không? Hãy kể lại tình huống gần nhất.
4. Khi chưa rõ checkpoint tiếp theo hoặc yêu cầu nộp bài, đã xử lý tình huống đó như thế nào?
5. Đã dành khoảng bao lâu cho việc đọc, tìm kiếm và đối chiếu thông tin?
6. Có lần nào việc hiểu hướng dẫn diễn ra nhanh chóng và không gặp khó khăn? Điều gì khác biệt so với những lần gặp khó khăn?
7. Có từng phải sửa lại sản phẩm hoặc thay đổi cách làm vì hiểu thiếu hoặc nhầm yêu cầu không? Nếu có, chuyện gì đã xảy ra?
#### Interview Snapshot A – Sinh viên thực hiện bài lab cá nhân

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Sinh viên thực hiện bài lab cá nhân |
| Câu nói đáng nhớ nhất (nguyên văn) | "Em thường đọc README trước, nhưng khi mở worksheet thì lại thấy có thêm yêu cầu về định dạng và cách nộp bài. Em phải quay lại kiểm tra để chắc chắn không bỏ sót." |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Khi thực hiện một bài lab, người tham gia đọc README trước, sau đó mở worksheet và phát hiện thêm các yêu cầu chi tiết về định dạng và cách nộp sản phẩm. |
| Hiện đang xử lý bằng cách nào (workaround)? | Đọc lần lượt README và worksheet, ghi chú các đầu việc rồi quay lại đối chiếu thông tin giữa hai tài liệu. |
| Mất bao lâu, bao lần? | Ước tính khoảng 15–20 phút để đọc và tổng hợp yêu cầu của bài lab. |
| Insight / opportunity rút ra | Khi yêu cầu được trình bày ở nhiều tài liệu, sinh viên phải tự tổng hợp thông tin trước khi bắt đầu thực hiện. Có cơ hội hỗ trợ chuyển đổi nội dung từ nhiều nguồn thành danh sách yêu cầu thống nhất. |

#### Interview Snapshot B – Sinh viên phụ trách điều phối nhóm

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Sinh viên phụ trách phân chia công việc trong nhóm |
| Câu nói đáng nhớ nhất (nguyên văn) | "Em biết phần mình cần làm, nhưng đôi khi không chắc sản phẩm đó phải đưa vào file nào của nhóm. Em phải hỏi lại trưởng nhóm hoặc kiểm tra repository." |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Khi nhóm chuẩn bị thực hiện bài lab theo nhiều checkpoint, người tham gia cần xác định đầu ra của từng thành viên và vị trí lưu sản phẩm. |
| Hiện đang xử lý bằng cách nào (workaround)? | Đọc hướng dẫn, kiểm tra cấu trúc repository, hỏi thành viên khác và sử dụng nhóm chat hoặc danh sách công việc chung để thống nhất đầu ra. |
| Mất bao lâu, bao lần? | Ước tính khoảng 10–15 phút để kiểm tra và xác nhận các yêu cầu liên quan đến việc phân chia công việc. |
| Insight / opportunity rút ra | Khó khăn không chỉ liên quan đến việc đọc tài liệu mà còn có thể xuất phát từ việc chưa thống nhất cách phân công và vị trí lưu sản phẩm. Có cơ hội tích hợp thông tin về nhiệm vụ và đầu ra vào một checklist chung. |

#### Interview Snapshot C – Sinh viên thực hiện bài lab nhiều checkpoint

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Sinh viên đã thực hiện bài lab có nhiều checkpoint |
| Câu nói đáng nhớ nhất (nguyên văn) | "Nếu README ghi rõ từng checkpoint thì em làm khá nhanh. Nhưng có bài phải đọc nhiều phần mới biết checkpoint nào cần hoàn thành trước." |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Khi thực hiện bài lab có nhiều giai đoạn, người tham gia chưa xác định rõ thứ tự giữa các nhiệm vụ và phải đọc lại nhiều phần hướng dẫn. |
| Hiện đang xử lý bằng cách nào (workaround)? | Đọc các phần hướng dẫn, đối chiếu yêu cầu giữa các checkpoint, hỏi bạn cùng nhóm khi chưa rõ và tự lập danh sách công việc theo thứ tự. |
| Mất bao lâu, bao lần? | Ước tính khoảng 10–15 phút để xác định thứ tự và tổng hợp các nhiệm vụ trước khi bắt đầu. |
| Insight / opportunity rút ra | Mức độ khó khăn phụ thuộc vào cách tổ chức tài liệu. Khi hướng dẫn rõ ràng, sinh viên không nhất thiết mất nhiều thời gian. Có cơ hội hỗ trợ xác định checkpoint và thứ tự thực hiện khi tài liệu chưa trình bày tập trung. |

#### Tổng hợp

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Interview A | 1 | Phải đọc README và worksheet, ghi chú rồi đối chiếu lại yêu cầu; ước tính mất 15–20 phút. | Chưa có bằng chứng cho thấy tình trạng này thường xuyên dẫn đến bỏ sót đầu ra hoặc phải làm lại sản phẩm. |
| Interview B | 1 | Phải kiểm tra repository và hỏi thành viên khác để xác nhận vị trí lưu sản phẩm; ước tính mất 10–15 phút. | Khó khăn có thể xuất phát từ việc phân công nhóm hoặc quy ước lưu tệp chưa rõ, không hoàn toàn do tài liệu phân tán. |
| Interview C | 1 | Phải đọc nhiều phần hướng dẫn, đối chiếu thứ tự checkpoint và tự lập danh sách công việc; ước tính mất 10–15 phút. | Khi README được tổ chức tốt, việc xác định yêu cầu diễn ra nhanh và không tạo ra khó khăn đáng kể. |
| CP3 – Problem Card D3 | 1 | Ước tính khoảng 40 phút để hiểu tổng thể bài lab, trong đó khoảng 17 phút dành cho việc đối chiếu yêu cầu. | Đây là ước tính cá nhân, chưa phải số liệu đo thời gian thực tế. |
| CP3 – Problem Card L1 | 1 | Ước tính khoảng 15 phút để nắm bắt yêu cầu và đầu ra của bài lab. | Phạm vi công việc khác với D3 nên không thể so sánh trực tiếp hai con số. |

**Nhận định tổng hợp:**

- 3/3 người tham gia phỏng vấn mô phỏng mô tả ít nhất một hành vi tự xử lý hoặc xác nhận thông tin, chẳng hạn đọc nhiều tài liệu, ghi chú, kiểm tra repository, đối chiếu checkpoint hoặc hỏi thành viên khác.
- 2/3 người tham gia mô tả rõ việc phải tổng hợp hoặc xác nhận lại thông tin liên quan đến yêu cầu, checkpoint hoặc đầu ra.
- 1/3 người tham gia đưa ra tín hiệu phản bác có điều kiện: khi README được tổ chức rõ ràng, việc xác định yêu cầu diễn ra nhanh và không tạo ra khó khăn đáng kể.
- Chưa có bằng chứng đủ mạnh để kết luận rằng tình trạng này thường xuyên dẫn đến bỏ sót bài nộp hoặc phải làm lại sản phẩm.

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

**Problem statement ban đầu:**

Sinh viên mất nhiều thời gian đọc và tìm kiếm thông tin trong các tài liệu hướng dẫn bài lab.

**Problem statement sau khi kiểm chứng:**

Khi thực hiện các bài lab có nhiều checkpoint và yêu cầu được trình bày ở nhiều tài liệu hoặc vị trí khác nhau, sinh viên cần đọc, đối chiếu và tổng hợp thông tin để xác định nhiệm vụ, đầu ra, thứ tự thực hiện và vị trí lưu hoặc nộp sản phẩm. Quá trình này có thể làm tăng thời gian chuẩn bị, gây khó khăn khi phối hợp công việc và khiến sinh viên phải xác nhận lại những yêu cầu chưa rõ.

**Những điểm được điều chỉnh:**

- Thu hẹp đối tượng vào sinh viên thực hiện bài lab có nhiều checkpoint.
- Xác định rõ khó khăn trọng tâm là việc tổng hợp thông tin từ nhiều nguồn, không đơn thuần là đọc nhiều tài liệu.
- Bổ sung các nội dung cần xác định như nhiệm vụ, deliverables, thứ tự thực hiện và vị trí lưu/nộp sản phẩm.
- Ghi nhận yếu tố phản bác: nếu README được tổ chức tốt và yêu cầu rõ ràng, sinh viên có thể không gặp khó khăn đáng kể.

Do đó, nhóm không cho rằng mọi bài lab có nhiều tài liệu đều tạo ra vấn đề. Vấn đề cần tập trung là tình huống sinh viên phải tự kết nối thông tin từ nhiều nguồn để hiểu đầy đủ những gì cần làm và những gì cần nộp.

### 3.3. Research giải pháp đã có

Nhóm tìm hiểu ba công cụ hoặc trường hợp có liên quan đến việc đọc tài liệu, tổng hợp kiến thức và quản lý yêu cầu học tập.

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Gemini Notebook (trước đây là NotebookLM) | https://support.google.com/gemininotebook/answer/16215270 | Tiếp nhận nhiều nguồn tài liệu, truy vấn và tổng hợp thông tin dựa trên các nguồn đã thêm vào notebook. | Hỗ trợ nhiều loại nguồn tài liệu; người dùng có thể đặt câu hỏi và khai thác thông tin dựa trên các nguồn đã cung cấp. | Người dùng vẫn cần lựa chọn và đưa tài liệu vào notebook. Việc chuyển nội dung thành cấu trúc checkpoint, phân công và checklist nộp bài phụ thuộc vào yêu cầu người dùng đặt ra; kết quả cần được kiểm tra với tài liệu gốc. | Cần hỗ trợ nhiều định dạng tài liệu, tổng hợp thông tin dựa trên nguồn và cung cấp dẫn chiếu để sinh viên xác minh nội dung. |
| ChatGPT – Projects & File Upload | https://help.openai.com/en/articles/10169521-projects-in-chatgpt | Tập hợp các cuộc trò chuyện, tệp và hướng dẫn trong một không gian; hỗ trợ phân tích, tóm tắt và trả lời câu hỏi dựa trên tài liệu được cung cấp. | Có thể lưu nhiều tài liệu tham khảo trong cùng một project; sử dụng tệp và hướng dẫn làm ngữ cảnh cho các cuộc trò chuyện liên quan. | Người dùng vẫn cần cung cấp tài liệu và mô tả yêu cầu phù hợp. Đầu ra có thể cần được kiểm tra để bảo đảm không bỏ sót checkpoint, điều kiện hoặc yêu cầu nộp bài. | Cần thiết kế đầu ra theo cấu trúc cố định, chẳng hạn bảng checkpoint, nhiệm vụ, deliverables, vị trí lưu tệp và trạng thái hoàn thành; đồng thời cho phép kiểm tra thông tin với nguồn gốc. |
| GitHub Classroom (historical case) | https://github.blog/changelog/2026-08-27-github-classroom-deprecated/ | Trước đây hỗ trợ giảng viên phân phối assignment, tổ chức bài tập cá nhân/nhóm và quản lý bài nộp trong môi trường GitHub. | Cung cấp mô hình tổ chức assignment, repository và quy trình giao – nhận bài tập cho hoạt động lập trình. | GitHub Classroom đã ngừng hoạt động từ ngày 28/08/2026; chỉ sử dụng làm trường hợp tham khảo lịch sử. Công cụ tập trung vào quản lý assignment và bài nộp, không giải quyết trực tiếp việc đọc hiểu và trích xuất yêu cầu từ nhiều tài liệu. | Cần thể hiện rõ cấu trúc nhiệm vụ, trạng thái hoàn thành và đầu ra cần nộp. Tuy nhiên, vẫn cần giải quyết bước diễn giải tài liệu thành nhiệm vụ trước khi quản lý tiến độ. |
---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

**Bài của nhóm nằm ở ô: Độ phức tạp cao × Độ mơ hồ thấp.**

**Vì sao:**
- **Độ phức tạp cao:** Trưởng nhóm phải đối chiếu từ nhiều nguồn tài liệu như README, CHECKPOINTS, worksheet và RUBRIC, sau đó tổng hợp yêu cầu theo từng checkpoint và xác định nơi lưu deliverable.
- **Độ mơ hồ thấp:** Các đầu ra, yêu cầu và tiêu chí hoàn thành đã được quy định trong tài liệu. Kết quả cần xác định tương đối rõ ràng, không cần AI tự sáng tạo nội dung.
- Các bước xử lý có trình tự tương đối ổn định, có thể xác định trước thay vì để AI tự quyết định bước tiếp theo.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** | Tổng hợp yêu cầu vào một checklist chung, phân công và đánh dấu tiến độ thủ công. | Tài liệu ít, yêu cầu tập trung và checklist được cập nhật đầy đủ. | Vẫn tốn thời gian đọc, đối chiếu và cập nhật thủ công khi tài liệu thay đổi. | Không chọn làm hướng chính |
| **Rule** | Dùng template hoặc script để phân loại checkpoint, liệt kê deliverable và vị trí lưu file theo cấu trúc cố định. | Tài liệu có cấu trúc thống nhất, thông tin cần lấy rõ ràng và ít thay đổi. | Khó hiểu ngữ cảnh, tổng hợp yêu cầu nằm rải rác trong nhiều đoạn văn bản. | Dùng cho các bước cố định |
| **Workflow** | Đưa các tài liệu vào quy trình định sẵn → AI trích xuất yêu cầu → tổng hợp thành checklist theo checkpoint → con người kiểm tra và xác nhận. | Cần đọc hiểu và đối chiếu nhiều nguồn nhưng các bước xử lý vẫn xác định trước. | AI có thể bỏ sót, diễn giải sai hoặc gán nhầm yêu cầu vào checkpoint. | **Chọn** |
| **Agent** | AI tự tìm tài liệu, quyết định nguồn cần đọc, tự đối chiếu, cập nhật tiến độ và đề xuất phân công. | Quy trình có nhiều tình huống phát sinh, cần tự quyết định bước tiếp theo. | Phức tạp, khó kiểm soát, có thể tự đưa ra quyết định phân công không chính xác. | Không chọn |

**Mức chọn: Workflow.**

**Vì sao không chọn mức đơn giản hơn:**

- No AI chỉ giúp chuẩn hóa cách trình bày, nhưng trưởng nhóm vẫn phải tự đọc và đối chiếu nhiều tài liệu.
- Rule có thể xử lý việc phân loại và liệt kê thông tin theo cấu trúc cố định, nhưng khó xử lý các yêu cầu cần hiểu ngữ cảnh hoặc được diễn đạt ở nhiều phần khác nhau.
- Workflow cho phép kết hợp Rule với AI để xử lý phần đọc hiểu và tổng hợp, trong khi con người vẫn kiểm tra kết quả.
- Không cần Agent vì trình tự xử lý đã xác định trước, không cần AI tự quyết định công việc tiếp theo.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Trích xuất và tổng hợp các yêu cầu, deliverable, checkpoint, người thực hiện và vị trí lưu file thành checklist có cấu trúc. |
| **Judgment** — con người cân nhắc, quyết định gì? | Trưởng nhóm kiểm tra yêu cầu, đối chiếu nguồn gốc, xử lý thông tin mâu thuẫn và quyết định nội dung cuối cùng. |
| **Action** — hành động cuối cùng là gì, ai làm? | Trưởng nhóm xác nhận checklist, lập kế hoạch và phân công nhiệm vụ cho thành viên. |
| **Outcome** — đo kết quả bằng gì? | Thời gian xác định deliverable, số yêu cầu bị bỏ sót hoặc phân loại sai và số lần phải kiểm tra lại tài liệu. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | README, CHECKPOINTS, worksheet, RUBRIC và các hướng dẫn liên quan. Các tài liệu đã có trong repository. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Các lỗi trích xuất, yêu cầu bị bỏ sót, nội dung thành viên phải sửa và phản hồi của trưởng nhóm sau mỗi lần sử dụng. |

### 6.4. Hai câu hỏi của Google PAIR

- **Người dùng muốn được hỗ trợ (augment) hay giao hẳn việc (automate)?**

  Augment. Trưởng nhóm muốn giảm thời gian đọc, tìm kiếm và tổng hợp thông tin, nhưng vẫn cần tự kiểm tra yêu cầu và quyết định phân công. AI chỉ hỗ trợ chuẩn bị checklist, không thay thế vai trò của trưởng nhóm.

- **AI sai kiểu nào tệ hơn, báo nhầm hay bỏ sót? Vì sao, và thiết kế đã xử lý thế nào?**

  Bỏ sót yêu cầu nghiêm trọng hơn vì có thể khiến nhóm không hoàn thành deliverable hoặc nộp thiếu nội dung. Báo nhầm cũng gây mất thời gian kiểm tra nhưng có thể được phát hiện khi đối chiếu nguồn.

  Thiết kế xử lý bằng cách yêu cầu mỗi mục checklist có nguồn tham chiếu cụ thể, đánh dấu thông tin chưa chắc chắn và bắt buộc con người kiểm tra trước khi xác nhận.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Trưởng nhóm và các thành viên tham gia thực hiện bài lab nhiều checkpoint. |
| **Quy trình** | Đọc các tài liệu hướng dẫn, đối chiếu yêu cầu từng checkpoint, xác định deliverable, vị trí lưu file, sau đó lập kế hoạch và phân công. |
| **Bottleneck** | Đối chiếu thông tin giữa nhiều tài liệu để xác định đầy đủ đầu ra của từng checkpoint. |
| **Impact** | Trưởng nhóm mất khoảng 40 phút để tìm hiểu và chuẩn bị, trong đó khoảng 17 phút dành cho việc đối chiếu tài liệu (số liệu ước lượng từ CP3). Việc này làm chậm quá trình lập kế hoạch và có nguy cơ bỏ sót yêu cầu. |
| **Success Metric** | Baseline: khoảng 40 phút/lần, trong đó 17 phút đối chiếu tài liệu. Target đề xuất: không quá 20 phút tổng thời gian và không quá 5 phút đối chiếu. Đo bằng cách bấm giờ trong 5 lần thực hiện pilot và ghi nhận số yêu cầu bị bỏ sót hoặc phân loại sai. |
| **Boundary** | AI không tự ý bổ sung yêu cầu không có trong tài liệu, không tự quyết định phân công hoặc đánh dấu hoàn thành. Các nội dung không rõ ràng phải được đánh dấu để con người xác minh. |
| **AI intervention point** | Sau khi xác định các tài liệu đầu vào và trước bước trưởng nhóm kiểm tra, tổng hợp checklist cuối cùng. |
| **Mức chọn** | Workflow |
| **Rủi ro & người kiểm tra** | AI có thể bỏ sót, diễn giải sai hoặc nhầm checkpoint. Trưởng nhóm chịu trách nhiệm đối chiếu từng yêu cầu với tài liệu gốc trước khi sử dụng checklist. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Success Metric | Đo thời gian xác định yêu cầu. | Bổ sung số yêu cầu bị bỏ sót hoặc phân loại sai. | Chỉ giảm thời gian chưa đủ chứng minh kết quả chính xác. |
| Boundary | Con người kiểm tra kết quả cuối cùng. | Bổ sung yêu cầu AI phải chỉ rõ nguồn tham chiếu và đánh dấu nội dung chưa chắc chắn. | Giảm nguy cơ AI tự diễn giải hoặc tạo ra yêu cầu không có trong tài liệu. |
| AI intervention point | Chưa xác định cụ thể. | AI tham gia ở bước đọc hiểu, trích xuất và tổng hợp yêu cầu. | Xác định rõ vị trí AI hỗ trợ trong quy trình. |
| Mức chọn | Chưa xác định. | Workflow. | Kết hợp xử lý theo quy trình cố định với khả năng đọc hiểu tài liệu của AI. |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Độ đầy đủ | Liệt kê đầy đủ các yêu cầu và deliverable có trong tài liệu nguồn. | Bỏ sót checkpoint hoặc deliverable bắt buộc. |
| 2 | Độ chính xác | Nội dung tổng hợp đúng với yêu cầu trong tài liệu gốc. | Diễn giải sai hoặc tự tạo thêm yêu cầu. |
| 3 | Phân loại checkpoint | Mỗi yêu cầu được gán đúng checkpoint và đúng phạm vi cá nhân/nhóm. | Gán nhầm yêu cầu hoặc nhầm người thực hiện. |
| 4 | Truy xuất nguồn | Mỗi yêu cầu có tên file và vị trí tham chiếu để kiểm tra lại. | Không xác định được nguồn hoặc dẫn nguồn không liên quan. |
| 5 | Khả năng sử dụng | Checklist có cấu trúc rõ ràng, xác định được deliverable và vị trí lưu file. | Thông tin thiếu cấu trúc, không thể sử dụng để lập kế hoạch và phân công. |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | Trung bình | Candidate D3 và L1 cho thấy hai thành viên gặp vấn đề tương tự. Tuy nhiên, mức độ phổ biến và baseline vẫn cần được kiểm chứng thêm với người dùng ngoài nhóm. |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Thấp | Checklist có cấu trúc quen thuộc, trưởng nhóm có thể đối chiếu với tài liệu gốc và chỉnh sửa trước khi sử dụng. |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | Thấp | Các tài liệu đầu vào đã tồn tại dưới dạng Markdown và có cấu trúc tương đối rõ. Có thể thử nghiệm bằng một quy trình AI đơn giản, chưa cần xây dựng Agent. |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | Thấp | Phạm vi thử nghiệm nhỏ, có thể sử dụng công cụ AI hiện có. Trưởng nhóm chịu trách nhiệm kiểm tra và cập nhật checklist khi tài liệu thay đổi. |

### 8.2. Kết luận

**Quyết định: Go — thử nghiệm ở phạm vi nhỏ (Pilot).**

**Lý do:**

- Vấn đề có quy trình và bottleneck tương đối rõ, có hai candidate cùng thể hiện pattern đọc và đối chiếu nhiều tài liệu.
- Workflow có thể giảm công việc đọc, trích xuất và tổng hợp thủ công.
- Các bước xử lý có thể xác định trước nên chưa cần xây dựng Agent.
- Rủi ro AI bỏ sót hoặc diễn giải sai có thể hạn chế bằng nguồn tham chiếu, tiêu chí đánh giá và bước kiểm tra của con người.
- Tuy nhiên, mức độ hiệu quả và nhu cầu thực tế vẫn cần được xác nhận qua pilot.

**Nếu Go — pilot nhỏ nhất:**

1. Chọn một bài lab có nhiều checkpoint và nhiều file hướng dẫn.
2. Cung cấp README, CHECKPOINTS, worksheet và RUBRIC cho AI.
3. Yêu cầu AI tạo checklist gồm checkpoint, yêu cầu, deliverable, người thực hiện và vị trí lưu file.
4. Trưởng nhóm đối chiếu checklist với tài liệu gốc, ghi nhận lỗi và thời gian chỉnh sửa.
5. So sánh thời gian và độ đầy đủ với cách làm thủ công.

**Nếu Not Yet — cần kiểm chứng gì trước:**

- Xác nhận baseline bằng cách bấm giờ thực tế.
- Kiểm tra mức độ bỏ sót yêu cầu trong quy trình hiện tại.
- Thử nghiệm với các bài lab khác nhau để xác định khả năng áp dụng.

**Nếu No-Go — nên làm gì thay AI:**

Sử dụng một checklist Markdown thống nhất, tổng hợp sẵn yêu cầu từng checkpoint và cập nhật khi có thay đổi trong tài liệu hướng dẫn.

**Ngưỡng dừng:**

Nếu sau 1 tuần hoặc 5 lần thử nghiệm, thời gian chuẩn bị vẫn trên 20 phút/lần hoặc AI liên tục bỏ sót, phân loại sai yêu cầu quan trọng, nhóm sẽ dừng Workflow và quay về phương án checklist thủ công kết hợp Rule để xử lý các thông tin cố định.

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
