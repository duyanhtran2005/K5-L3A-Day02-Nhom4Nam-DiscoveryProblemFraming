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
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

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
