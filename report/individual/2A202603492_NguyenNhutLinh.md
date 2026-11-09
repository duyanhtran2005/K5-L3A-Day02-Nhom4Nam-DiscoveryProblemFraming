# Báo cáo cá nhân — 2A202603492_NguyenNhutLinh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Nhựt Linh
- MSSV: 2A202603492
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Nhom4Nam
- Link repo nhóm: https://github.com/duyanhtran2005/K5-L3A-Day02-Nhom4Nam-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Đọc và tổng hợp | Khi nhận một bài lab có nhiều yêu cầu, tôi muốn xác định rõ các đầu việc và deliverables cần hoàn thành để tránh bỏ sót yêu cầu. | Sinh viên thực hiện bài lab | Đôi lúc mỗi bài lab có nhiều file README, hướng dẫn và nằm ở nhiều mục khác nhau khiến việc tổng hợp thông tin mất ít nhất khoảng 15p để nắm được thông tin chính. Ví dụ như bài codelab day02, cần phải đọc thông tin từ file khác nhau để xác định chính xác việc cần làm. |
| 2 | Tốn thời gian | Khi thiết lập môi trường Python cho dự án, tôi muốn nhanh chóng xác định nguyên nhân lỗi để không mất quá nhiều thời gian xử lý cấu hình. | Sinh viên, người học lập trình | Trong quá trình thiết lập môi trường Python, tôi gặp lỗi liên quan đến cài đặt thư viện, cấu hình môi trường ảo hoặc thiết lập API. Mỗi lần xử lý mất khoảng 2 đến 10 phút tùy vào trường hợp dễ hay khó, thường phải kiểm tra thông báo lỗi, cấu hình và thử lại nhiều lần. Cụ thể là tôi từng gặp phải lỗi xung đột thư viện khi cài các thư viện yêu cầu phiên bản khác nhau cho cùng 1 thư viện. |
| 3 | Đọc và tổng hợp | Khi học một chủ đề AI mới, tôi muốn tổng hợp kiến thức từ nhiều tài liệu và nguồn tham khảo để có cái nhìn đầy đủ và dễ hiểu. | Sinh viên AI/ML | Khi tìm hiểu một chủ đề AI, tôi thường tham khảo nhiều nguồn như tài liệu chính thức, bài viết kỹ thuật, notebook mẫu, YouTube và các công cụ AI như ChatGPT, Gemini,... Việc đọc và đối chiếu thông tin mất khoảng 30 phút cho mỗi chủ đề. Ví dụ: Khi tìm hiểu Gemini Enterprise Agent Platform, tôi gặp khó khăn do tài liệu phân tán, liên kết qua nhiều mục, code mẫu đôi khi bị lỗi và hướng dẫn giữa các phiên bản chưa nhất quán dẫn đến tôi không biết phải xem như nào cho chính xác. |
| 4 | Đọc và tổng hợp | Khi đọc tài liệu kỹ thuật dài, tôi muốn nhanh chóng xác định những nội dung quan trọng để tập trung vào kiến thức cần thiết. | Người học công nghệ | Khi triển khai Agent bằng Google ADK trên GEAP, tôi mất khoảng 30 phút hoặc lâu hơn để tìm đúng cú pháp khởi tạo Agent và cấu hình tools. Các documentation và notebook mẫu đôi khi sử dụng API hoặc cách viết khác nhau, khiến tôi khó xác định cú pháp phù hợp với phiên bản SDK đang sử dụng và phải thử nghiệm nhiều lần. |
| 5 | Tốn thời gian | Khi thử nghiệm nhiều mô hình LLM thông qua API, tôi muốn nhanh chóng xác định và xử lý các lỗi như Rate Limit, API Key hoặc kết nối để không làm gián đoạn quá trình thử nghiệm. | Người phát triển ứng dụng AI | Trong quá trình thử nghiệm LLM, tôi gặp khoảng 5 lần lỗi liên quan đến Rate Limit, API Key hoặc kết nối. Mỗi lần xử lý mất khoảng 15-30 phút, cần kiểm tra log, cấu hình API và thử lại. Tôi bị rate limit khi làm bài codelab day01 và phải tốn thời gian khoảng 20 phút để tìm các model được hỗ trợ hoặc api đủ rate. |
| 6 | Lặp lại | Khi thực hiện một dự án hoặc bài lab có nhiều giai đoạn và deliverables, tôi muốn theo dõi các công việc đã hoàn thành, đang thực hiện và còn tồn đọng để tránh bỏ sót yêu cầu hoặc trễ tiến độ. | Sinh viên, thành viên dự án | Trong mỗi bài lab nhiều giai đoạn, tôi thường kiểm tra lại README và danh sách task khoảng 2–3 lần để xác định tiến độ. Mỗi lần rà soát mất khoảng 5–10 phút. Bằng chứng: Bài lab VinUni Codelab Day02, gồm nhiều phase và deliverables cần hoàn thành. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- **Giữ lại:** AI gợi ý bổ sung vấn đề về khó quản lý và theo dõi tiến độ khi thực hiện các dự án hoặc bài lab có nhiều giai đoạn. Tôi giữ lại vì vấn đề này phù hợp với trải nghiệm thực tế, thường xuyên phải kiểm tra checklist, README và tổng hợp các công việc còn tồn đọng.

- **Bỏ:** AI gợi ý vấn đề về khó kiểm chứng tính chính xác của kết quả do AI tạo ra. Tôi không chọn vì vấn đề này chưa phản ánh rõ một khó khăn cụ thể mà tôi muốn tập trung khai thác, đồng thời chưa xác định được dấu hiệu thực tế đủ rõ ràng.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Mất nhiều thời gian để nắm bắt yêu cầu và các đầu việc của một Codelab có nhiều giai đoạn. | Xảy ra ngay khi bắt đầu bài lab; có quy trình rõ ràng từ đọc tài liệu đến xác định nhiệm vụ; ảnh hưởng đến thời gian triển khai. | Có thể xác định đầy đủ yêu cầu chỉ từ README hay còn cần trao đổi với giảng viên/nhóm? |
| 2 | Mất nhiều thời gian để tìm hiểu và tổng hợp kiến thức mới từ nhiều nguồn. | Đây là nhu cầu thường xuyên khi học công nghệ AI mới; có thể đo thời gian tìm hiểu và mức độ hiểu đúng kiến thức. | Khó đánh giá thế nào là đã hiểu đủ và thông tin tổng hợp có chính xác hay không. |
| 3 | Mất nhiều thời gian xử lý và khắc phục lỗi khi sử dụng LLM API. | Có quy trình xử lý lỗi cụ thể; lỗi có thể làm gián đoạn tiến độ và việc thử nghiệm mô hình. | Thời gian xử lý phụ thuộc vào loại lỗi, nhà cung cấp API và mức độ rõ ràng của thông báo lỗi. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu một Codelab có nhiều giai đoạn và yêu cầu khác nhau, tôi muốn nhanh chóng nắm được các nhiệm vụ và deliverables cần hoàn thành, để có thể lên kế hoạch thực hiện đúng trọng tâm và không bỏ sót yêu cầu. |
| Actor | Sinh viên tham gia Codelab hoặc bài lab kỹ thuật. |
| Thời điểm / bối cảnh | Khi bắt đầu một bài lab mới, đặc biệt là bài có nhiều README, hướng dẫn và deliverables ở các thư mục hoặc giai đoạn khác nhau. |
| Quy trình hiện tại (3–7 bước) | 1. Mở repository của bài lab.<br>2. Tìm và đọc README chính.<br>3. Mở các README hoặc tài liệu liên quan.<br>4. Đối chiếu yêu cầu giữa các phần.<br>5. Ghi lại các nhiệm vụ và deliverables.<br>6. Kiểm tra lại để tránh bỏ sót. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2–4: Đọc và đối chiếu nhiều tài liệu để xác định đầy đủ yêu cầu, mất khoảng 15 phút hoặc hơn. |
| Impact (nếu không giải thì sao) | Có thể hiểu thiếu yêu cầu, bỏ sót deliverables, làm sai thứ tự hoặc phải quay lại đọc tài liệu trong quá trình thực hiện, gây lãng phí thời gian. |
| Success metric (baseline → target) | Thời gian nắm bắt yêu cầu: khoảng 15 phút → không quá 5 phút; không bỏ sót các deliverables được nêu trong README. |
| Phương án không dùng AI | Chuẩn hóa README, tạo checklist công việc và liên kết rõ ràng giữa từng giai đoạn với deliverables tương ứng. |
| Giả thuyết về AI (nếu có) | AI có thể đọc các README và tài liệu trong repository, tổng hợp nhiệm vụ theo từng giai đoạn và tạo checklist kèm tham chiếu đến nguồn gốc yêu cầu. |
| Cảm nhận nhanh | Workflow |

**Quy trình nháp hiện tại:**

```text
Bắt đầu Codelab
      |
      v
Mở repository và tìm README
      |
      v
Đọc README chính
      |
      v
Đọc và đối chiếu tài liệu liên quan
      |
      v
Ghi lại nhiệm vụ và deliverables
      |
      v
Kiểm tra lại yêu cầu
      |
      v
Bắt đầu thực hiện bài lab
```

### 3. Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần học một kiến thức hoặc công nghệ AI mới để phục vụ bài lab hoặc dự án, tôi muốn tìm hiểu và tổng hợp kiến thức từ các nguồn đáng tin cậy một cách có hệ thống, để hiểu đúng vấn đề và có thể áp dụng vào thực tế. |
| Actor | Sinh viên hoặc người học công nghệ AI. |
| Thời điểm / bối cảnh | Khi tiếp cận một chủ đề AI mới, cần đọc tài liệu, tìm hiểu cách hoạt động và thử áp dụng vào bài lab hoặc dự án. |
| Quy trình hiện tại (3–7 bước) | 1. Xác định chủ đề hoặc kiến thức cần tìm hiểu.<br>2. Tìm kiếm tài liệu từ các nguồn khác nhau.<br>3. Đọc documentation, bài viết hoặc notebook mẫu.<br>4. So sánh và chọn lọc thông tin.<br>5. Ghi chú, tổng hợp kiến thức.<br>6. Thử áp dụng vào bài lab hoặc dự án. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2–4: Tìm kiếm, đọc và chọn lọc thông tin từ nhiều nguồn, mất khoảng 30 phút cho một chủ đề; có thể lâu hơn nếu nội dung phức tạp. |
| Impact (nếu không giải thì sao) | Mất nhiều thời gian tự nghiên cứu, khó hình thành kiến thức có hệ thống và có nguy cơ hiểu sai hoặc áp dụng thông tin không phù hợp với phiên bản công nghệ đang sử dụng. |
| Success metric (baseline → target) | Thời gian tìm hiểu một chủ đề: khoảng 30 phút → không quá 15 phút; nội dung tổng hợp phải có nguồn tham khảo và đủ thông tin để thực hiện một thử nghiệm cơ bản. |
| Phương án không dùng AI | Xây dựng danh sách nguồn tài liệu đáng tin cậy, phân loại theo chủ đề và tạo template ghi chú thống nhất. |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ tìm kiếm, tổng hợp và đối chiếu thông tin từ nhiều nguồn, đồng thời cung cấp đường dẫn tham khảo để người học kiểm chứng trước khi áp dụng. |
| Cảm nhận nhanh | Workflow / Agent |

**Quy trình nháp hiện tại:**

```text
Xác định chủ đề cần tìm hiểu
      |
      v
Tìm kiếm các nguồn tài liệu
      |
      v
Đọc documentation, bài viết, notebook
      |
      v
So sánh và chọn lọc thông tin
      |
      v
Ghi chú và tổng hợp kiến thức
      |
      v
Thử áp dụng vào bài lab/dự án
```


### 4. Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi tích hợp LLM API vào bài lab hoặc dự án, tôi muốn nhanh chóng xác định nguyên nhân và cách khắc phục các lỗi phát sinh, để có thể tiếp tục thử nghiệm và phát triển ứng dụng mà không bị gián đoạn quá lâu. |
| Actor | Sinh viên hoặc lập trình viên đang phát triển ứng dụng sử dụng LLM API. |
| Thời điểm / bối cảnh | Khi gọi API từ ứng dụng hoặc notebook, đặc biệt trong quá trình thử nghiệm nhiều model hoặc làm việc với các nhà cung cấp API khác nhau. |
| Quy trình hiện tại (3–7 bước) | 1. Gửi request đến LLM API.<br>2. Nhận thông báo lỗi hoặc kết quả không mong muốn.<br>3. Đọc thông báo lỗi và kiểm tra log.<br>4. Tìm nguyên nhân trong tài liệu hoặc cộng đồng.<br>5. Điều chỉnh API key, model, tham số hoặc cấu hình.<br>6. Gửi lại request để kiểm tra. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–5: Xác định nguyên nhân và tìm cách khắc phục lỗi, mất khoảng 15–30 phút cho mỗi sự cố. |
| Impact (nếu không giải thì sao) | Làm gián đoạn quá trình phát triển, tốn thời gian thử đi thử lại và có thể ảnh hưởng đến tiến độ hoàn thành bài lab hoặc dự án. |
| Success metric (baseline → target) | Thời gian xử lý một sự cố: khoảng 15–30 phút → không quá 10 phút; giải pháp đề xuất phải được kiểm tra lại bằng một request thành công. |
| Phương án không dùng AI | Xây dựng bảng tra cứu lỗi thường gặp, checklist kiểm tra API key, model, quota, kết nối và cấu hình request. |
| Giả thuyết về AI (nếu có) | AI có thể phân tích error message và log, phân loại nguyên nhân, đề xuất các bước kiểm tra và hướng dẫn cách khắc phục dựa trên tài liệu của nhà cung cấp. |
| Cảm nhận nhanh | Workflow |

**Quy trình nháp hiện tại:**

```text
Gửi request đến LLM API
      |
      v
Nhận thông báo lỗi
      |
      v
Đọc error message và kiểm tra log
      |
      v
Tìm nguyên nhân trong tài liệu
      |
      v
Điều chỉnh cấu hình hoặc request
      |
      v
Gửi lại request để kiểm tra
```

### Card muốn pitch nhất

- **Card số:** 2
- **Vì sao:** Đây là vấn đề thường gặp khi học và làm việc với công nghệ AI mới. Việc tìm hiểu kiến thức từ nhiều nguồn mất thời gian, khó tổng hợp thành một luồng kiến thức thống nhất và có thể dẫn đến áp dụng thông tin không phù hợp. Vấn đề có tiềm năng cải thiện bằng AI nhưng vẫn cần kiểm chứng độ chính xác và nguồn tham khảo.
- **Câu hỏi muốn nhóm phản biện:** Làm thế nào để xác định một công cụ hỗ trợ tìm hiểu kiến thức AI thực sự giúp tiết kiệm thời gian mà vẫn đảm bảo thông tin tổng hợp chính xác, cập nhật và có nguồn tham khảo đáng tin cậy?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Vấn đề ban đầu có thể bị mô tả quá rộng, chưa xác định rõ người gặp vấn đề và thời điểm xảy ra. | Đồng ý | Xác định actor là sinh viên/người học AI và bối cảnh là khi cần tìm hiểu công nghệ mới để làm bài lab hoặc dự án. |
| Các dấu hiệu như tài liệu phân tán hoặc ví dụ code không đồng nhất chỉ là biểu hiện, chưa phải vấn đề cốt lõi. | Đồng ý | Tập trung vào vấn đề chính là mất thời gian tìm hiểu và tổng hợp kiến thức từ nhiều nguồn. |
| Chưa có tiêu chí cụ thể để đánh giá giải pháp có hiệu quả hay không. | Đồng ý | Bổ sung metric về thời gian tìm hiểu và yêu cầu nội dung tổng hợp có nguồn tham khảo, đủ để thực hiện thử nghiệm cơ bản. |

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
| CP1 Scan | Nhờ AI gợi ý, phân loại và diễn đạt các vấn đề tôi thường gặp khi học tập, làm lab và thực hiện dự án AI. | Giúp mở rộng danh sách pain point, sắp xếp vấn đề theo nhóm và chuyển trải nghiệm cá nhân thành các mô tả rõ ràng. | Một số gợi ý còn chung chung, nhầm lẫn giữa vấn đề chính và dấu hiệu của vấn đề; có vấn đề chưa phản ánh đúng trải nghiệm thực tế. | Loại bỏ những vấn đề chưa có trải nghiệm hoặc bằng chứng rõ ràng, giữ lại các vấn đề thực sự gặp phải và bổ sung bối cảnh cụ thể. |
| CP2 Problem Card | Nhờ AI hỗ trợ chọn lọc top 3 vấn đề, xây dựng Problem Card, quy trình hiện tại và phản biện các giả thuyết giải pháp. | Giúp hệ thống hóa từng vấn đề theo đối tượng, bối cảnh, quy trình, bottleneck và tác động; gợi ý cách đo lường mức độ ảnh hưởng. | Một số nội dung còn rộng, đưa ra chỉ số thời gian và mức cải thiện chưa có dữ liệu kiểm chứng; đôi khi tập trung vào biểu hiện thay vì nguyên nhân cốt lõi. | Tự chọn 3 vấn đề phù hợp nhất (1, 3, 5), chỉnh sửa nội dung theo trải nghiệm thực tế, phân biệt vấn đề chính với dấu hiệu và xem các con số ước lượng là giả thuyết cần kiểm chứng.
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
