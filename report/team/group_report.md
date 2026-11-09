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

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
