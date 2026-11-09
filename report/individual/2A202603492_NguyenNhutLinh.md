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

### Problem Card #2

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


### Problem Card #3

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
| Pitch Problem Card | Trình bày Problem Card #2 về khó khăn khi tìm hiểu và tổng hợp kiến thức AI từ nhiều nguồn. | Đưa vấn đề cá nhân vào quá trình thảo luận, giúp nhóm có thêm một candidate để so sánh và lựa chọn. |
| Phản biện bài của bạn khác | Tham gia lắng nghe và đặt câu hỏi nhằm làm rõ actor, bối cảnh, tần suất xảy ra và tác động của các vấn đề được trình bày. | Giúp nhận diện những điểm còn thiếu bằng chứng và phân biệt vấn đề cốt lõi với các biểu hiện bên ngoài. |
| Nhận phản biện | Tiếp nhận góp ý về phạm vi vấn đề, cách xác định actor và sự khác biệt giữa pain point với các dấu hiệu như tài liệu phân tán hoặc hướng dẫn chưa thống nhất. | Điều chỉnh cách diễn đạt Problem Card, tập trung vào khó khăn trong việc tìm kiếm, đọc và tổng hợp thông tin. |
| Gom cluster / cây OST | Tham gia đối chiếu các Problem Card và nhóm những vấn đề có điểm chung về việc đọc, tìm kiếm, tổng hợp yêu cầu Codelab. | Nhận ra L1 của tôi và D3 của thành viên khác có liên quan đến cùng một nhóm vấn đề, tạo cơ sở để nhóm xem xét candidate chung. |
| Chọn candidate problem | Tham gia thảo luận và lựa chọn candidate D3 làm vấn đề nhóm tập trung giải quyết. | Nhóm thống nhất tập trung vào khó khăn của trưởng nhóm khi xác định đầu ra từng checkpoint từ nhiều tài liệu hướng dẫn trước khi lập kế hoạch và phân công. |
| Kiểm chứng / research | Tham gia xem xét và thảo luận các kết quả research, đối chiếu những nhận định ban đầu với bằng chứng nhóm thu thập được. | Giúp nhận diện những giả định chưa được xác nhận, xem xét các giải pháp hiện có và điều chỉnh phạm vi vấn đề cho phù hợp. |
| Quy trình nhóm | Tham gia phân tích quy trình hiện tại, xác định các bước đọc tài liệu, đối chiếu yêu cầu, xác định deliverables và lập kế hoạch; đồng thời xem xét quy trình đề xuất. | Làm rõ bước đối chiếu thông tin là bottleneck cần ưu tiên cải thiện, từ đó tạo cơ sở xây dựng workflow mới. |
| Problem Statement | Tham gia rà soát các thành phần của Problem Statement: actor, bối cảnh, quy trình, bottleneck, impact, success metric và boundary. | Giúp mô tả vấn đề D3 cụ thể hơn, phân biệt số liệu ước lượng với dữ liệu kiểm chứng và tránh đưa giải pháp vào phần mô tả vấn đề. |
| Mức can thiệp AI | Sử dụng AI để hỗ trợ phân tích ma trận độ mơ hồ × độ phức tạp, so sánh No AI, Rule, Workflow và Agent; đề xuất Workflow cho bài toán D3. | Làm rõ AI có thể hỗ trợ tổng hợp và tổ chức thông tin theo các bước xác định trước, trong khi con người vẫn kiểm tra và quyết định nội dung cuối cùng. |
| Quyết định | Tham gia xem xét các rủi ro Value, Usability, Feasibility và Viability trước khi đánh giá hướng triển khai candidate D3. | Nhóm xác định Workflow là hướng can thiệp phù hợp để tiếp tục xem xét, tuy nhiên vẫn cần kiểm chứng thêm về mức độ hữu ích, khả năng triển khai và hiệu quả thực tế trước khi đưa ra quyết định cuối cùng. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Nhờ AI gợi ý, phân loại và diễn đạt các vấn đề tôi thường gặp khi học tập, làm lab và thực hiện dự án AI. | Giúp mở rộng danh sách pain point, sắp xếp vấn đề theo nhóm và chuyển trải nghiệm cá nhân thành các mô tả rõ ràng. | Một số gợi ý còn chung chung, nhầm lẫn giữa vấn đề chính và dấu hiệu của vấn đề; có vấn đề chưa phản ánh đúng trải nghiệm thực tế. | Loại bỏ những vấn đề chưa có trải nghiệm hoặc bằng chứng rõ ràng, giữ lại các vấn đề thực sự gặp phải và bổ sung bối cảnh cụ thể. |
| CP2 Problem Card | Nhờ AI hỗ trợ chọn lọc top 3 vấn đề, xây dựng Problem Card, quy trình hiện tại và phản biện các giả thuyết giải pháp. | Giúp hệ thống hóa từng vấn đề theo đối tượng, bối cảnh, quy trình, bottleneck và tác động; gợi ý cách đo lường mức độ ảnh hưởng. | Một số nội dung còn rộng, đưa ra chỉ số thời gian và mức cải thiện chưa có dữ liệu kiểm chứng; đôi khi tập trung vào biểu hiện thay vì nguyên nhân cốt lõi. | Tự chọn 3 vấn đề phù hợp nhất từ các vấn đề số 1, 3 và 5 trong bảng CP1, tương ứng với Problem Card #1, #2 và #3. Tôi chỉnh sửa nội dung theo trải nghiệm thực tế và xem các con số ước lượng là giả thuyết cần kiểm chứng. |
| CP4 Research | Nhờ AI hỗ trợ tổng hợp thông tin về các cách giải quyết vấn đề xác định yêu cầu từ nhiều tài liệu, đồng thời phân tích và so sánh các giải pháp hiện có. | Giúp hệ thống hóa thông tin, nhận diện ưu nhược điểm của từng hướng tiếp cận và gợi ý các khía cạnh cần kiểm chứng thêm. | Một số nhận định còn mang tính tổng quát, chưa phản ánh đầy đủ bối cảnh thực tế của người dùng; thông tin do AI đưa ra chưa phải bằng chứng kiểm chứng. | Đối chiếu nội dung AI với tài liệu và kết quả research của nhóm, không xem các nhận định do AI tạo ra là kết luận thực tế nếu chưa có nguồn xác nhận. |
| CP5 Quy trình | Nhờ AI hỗ trợ mô tả quy trình hiện tại, phân tích các bước gây mất thời gian và đề xuất quy trình cải tiến cho candidate D3. | Giúp hệ thống hóa các bước từ đọc tài liệu, đối chiếu yêu cầu đến xác định deliverables và lập kế hoạch; làm rõ vị trí có thể cải thiện bằng AI. | Quy trình AI đề xuất đôi khi còn chung chung, chưa phân biệt rõ bước tự động hóa và bước cần người dùng kiểm tra, xác nhận. | Điều chỉnh quy trình theo bối cảnh thực tế của Codelab, giữ quyền kiểm tra và quyết định cuối cùng cho trưởng nhóm, không tự động hóa toàn bộ quy trình. |
| CP5–6 Problem Statement | Nhờ AI hỗ trợ xây dựng và rà soát Problem Statement cho candidate D3, tập trung vào actor, bottleneck, impact, success metric và boundary. | Giúp hệ thống hóa các thành phần của Problem Statement và nhận diện những thông tin còn thiếu. | AI có xu hướng tự bổ sung số liệu, giả định baseline và mô tả quy trình khi chưa có đủ bằng chứng từ nhóm. | Yêu cầu AI phân biệt số liệu ước lượng với kết quả kiểm chứng, đồng thời điều chỉnh nội dung để bám đúng candidate D3 thay vì nhầm sang Problem Card cá nhân. |
| CP6 Mức can thiệp / quyết định | Nhờ AI phân tích ma trận độ mơ hồ × độ phức tạp, so sánh No AI / Rule / Workflow / Agent, xây dựng AI Canvas và đánh giá bốn rủi ro trước khi đề xuất quyết định. | Giúp nhìn rõ ưu nhược điểm của từng mức can thiệp, xác định phần việc AI có thể hỗ trợ và vai trò kiểm tra của con người. | AI có thể đưa ra lựa chọn mức can thiệp hoặc quyết định Go khi chưa có đủ bằng chứng; một số số liệu và giả định được đưa ra chưa được xác minh. | Yêu cầu làm rõ cơ sở lựa chọn D3, phân biệt đề xuất với quyết định thực tế của nhóm và không xem các số liệu ước lượng là kết quả đã kiểm chứng. |

---

## 6. Reflection (CP7)

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi nghe các thành viên trình bày top 3 problems, tôi nhận ra mỗi người có những khó khăn khác nhau nhưng có thể có điểm chung về nguyên nhân hoặc quy trình. Một số vấn đề ban đầu nghe có vẻ khác nhau nhưng khi phân tích kỹ lại đều liên quan đến việc mất thời gian tìm kiếm, xử lý hoặc tổng hợp thông tin. Điều này giúp tôi hiểu rằng không nên chỉ nhìn vào biểu hiện bên ngoài mà cần tìm hiểu công việc thực tế mà người gặp vấn đề đang thực hiện. 

Ban đầu, tôi tập trung vào vấn đề cá nhân như tìm hiểu kiến thức AI từ nhiều nguồn hoặc xử lý lỗi khi sử dụng LLM API. Tuy nhiên, khi thảo luận cùng nhóm, tôi nhận ra cần đánh giá vấn đề dựa trên mức độ ảnh hưởng, tần suất xảy ra và khả năng kiểm chứng, thay vì chỉ chọn vấn đề mà bản thân cảm thấy thú vị. Tôi cũng học được cách đặt câu hỏi để làm rõ actor, bối cảnh và bottleneck của từng vấn đề trước khi nghĩ đến giải pháp.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Tôi nhận thấy nhóm có nguy cơ đi theo hướng solution-first khi bắt đầu thảo luận về việc sử dụng AI để giải quyết vấn đề. Khi thấy một công việc mất thời gian, chúng tôi khá dễ nghĩ ngay đến việc sử dụng chatbot hoặc một công cụ AI để tự động hóa. Tuy nhiên, việc sử dụng AI không đồng nghĩa với việc giải quyết đúng nguyên nhân của vấn đề.

Để hạn chế điều này, nhóm cần quay lại phân tích quy trình hiện tại, xác định người gặp vấn đề, các bước thực hiện và bước nào thực sự gây mất thời gian. Đối với candidate D3, nhóm tập trung làm rõ khó khăn trong quá trình thực hiện công việc thay vì mặc định rằng cần xây dựng một Agent. Sau đó, nhóm mới xem xét AI có thể hỗ trợ ở bước nào và phần nào vẫn cần con người kiểm tra. Qua đó, tôi hiểu rằng cần xác định vấn đề và nhu cầu thực tế trước khi lựa chọn công nghệ hoặc thiết kế giải pháp.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Trong quá trình thực hiện bài tập, tôi nhận ra một vấn đề có thể được mô tả theo nhiều cách khác nhau. Ban đầu, khi xây dựng các problem card, tôi thường chú ý đến những biểu hiện dễ nhận thấy như tài liệu phân tán, hướng dẫn không thống nhất hoặc phải thử nghiệm nhiều lần. Tuy nhiên, những biểu hiện này chưa chắc đã thể hiện chính xác vấn đề cốt lõi mà người dùng đang gặp phải.

Sau khi xem xét và phản biện các problem card, tôi hiểu rằng cần tập trung vào công việc mà người dùng muốn hoàn thành và trở ngại khiến họ không thể thực hiện hiệu quả. Vì vậy, tôi điều chỉnh cách diễn đạt theo hướng nhấn mạnh vấn đề chính là mất thời gian tìm kiếm, đọc và tổng hợp thông tin, thay vì chỉ liệt kê những bất tiện trong quá trình thực hiện. Điều này giúp tôi nhận ra phản biện không chỉ nhằm tìm ra điểm chưa hợp lý mà còn giúp làm rõ vấn đề và cải thiện cách đặt problem statement.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Qua quá trình nghiên cứu và thảo luận về candidate D3, tôi nhận ra rằng khó khăn trong việc xác định yêu cầu từ nhiều tài liệu không phải lúc nào cũng xuất hiện ở mọi người hoặc mọi Codelab. Một số trường hợp có README được tổ chức tốt thì việc nắm bắt yêu cầu không quá khó khăn. Điều này cho thấy mức độ ảnh hưởng của vấn đề còn phụ thuộc vào cách tổ chức tài liệu và độ phức tạp của từng bài lab.

Điều khiến tôi chú ý là cần phân biệt giữa trải nghiệm cá nhân, nhận định từ research và bằng chứng đã được kiểm chứng. Chẳng hạn, thời gian thực hiện một công việc do người tham gia ước lượng chưa thể xem là số liệu đại diện cho toàn bộ người dùng. Tôi rút ra rằng kiểm chứng không chỉ nhằm xác nhận giả thuyết ban đầu mà còn giúp nhóm nhận diện những trường hợp ngoại lệ, điều chỉnh phạm vi vấn đề và tránh lựa chọn giải pháp dựa trên những giả định chưa đủ cơ sở.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Theo tôi, khó nhất khi viết Problem Statement là xác định đúng bottleneck và diễn đạt vấn đề đủ cụ thể mà không đưa giải pháp vào quá sớm. Khi mô tả một khó khăn, tôi thường có xu hướng liệt kê nhiều biểu hiện khác nhau. Tuy nhiên, nếu không phân tích quy trình thì rất dễ nhầm lẫn giữa triệu chứng và nguyên nhân chính khiến công việc mất thời gian.

Ngoài ra, việc xây dựng Success Metric cũng là một thách thức. Một mục tiêu như tiết kiệm thời gian hoặc tăng hiệu quả vẫn còn chung chung nếu không xác định được cách đo lường. Cần có baseline để biết tình trạng hiện tại và target để đánh giá mức cải thiện. Boundary cũng cần được xác định rõ để tránh việc AI tự đưa ra những quyết định vượt quá phạm vi hỗ trợ. Qua bài tập này, tôi hiểu rằng một Problem Statement tốt không cần mô tả quá dài nhưng phải làm rõ ai gặp vấn đề, vấn đề xảy ra ở đâu, ảnh hưởng như thế nào và kết quả nào được xem là cải thiện.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu được thực hiện lại, tôi sẽ dành nhiều thời gian hơn cho việc thu thập bằng chứng ngay từ CP1 và CP2 thay vì chủ yếu dựa vào trải nghiệm cá nhân. Tôi cũng sẽ ghi nhận cụ thể thời gian thực hiện từng bước trong quy trình để xác định bottleneck chính xác hơn. Điều này giúp việc lựa chọn candidate và xây dựng Problem Statement có cơ sở rõ ràng hơn.

Trong quá trình phản biện, tôi muốn tập trung nhiều hơn vào tính hợp lý của baseline, target và các giả định về người dùng. Chẳng hạn, nếu nhóm cho rằng một công việc mất nhiều thời gian thì cần làm rõ số liệu được lấy từ đâu, có bao nhiêu người gặp vấn đề và tần suất xảy ra như thế nào. Tôi cũng sẽ đặt câu hỏi về việc liệu AI có thực sự cần thiết hay một checklist hoặc quy trình Rule đơn giản đã đủ giải quyết vấn đề. Tôi nghĩ cách tiếp cận này sẽ giúp nhóm tránh lựa chọn công nghệ quá sớm và tập trung hơn vào giá trị thực tế của giải pháp.

**6.7. Hiểu bài**

Với candidate D3, trước tiên nhóm cần xác định rõ vấn đề mà người dùng gặp phải và quy trình hiện tại dẫn đến vấn đề đó. Sau khi xác định bottleneck, nhóm sử dụng các Success Metric để đo lường tình trạng ban đầu và đánh giá mức độ cải thiện mong muốn. Tiếp theo, cần xác định Boundary để làm rõ AI được phép hỗ trợ phần nào và những quyết định nào vẫn thuộc về con người. Dựa trên độ phức tạp và độ mơ hồ của công việc, nhóm so sánh các mức can thiệp từ No AI, Rule, Workflow đến Agent để chọn phương án phù hợp. Với D3, Workflow là hướng được đề xuất vì có thể kết hợp các bước xử lý cố định với khả năng hỗ trợ của AI mà không cần giao toàn bộ quyền quyết định cho Agent. Cuối cùng, nhóm đánh giá các rủi ro về Value, Usability, Feasibility và Viability trước khi đưa ra quyết định Go, Not Yet hoặc No-Go dựa trên bằng chứng.

---

## 7. Tài liệu tham khảo