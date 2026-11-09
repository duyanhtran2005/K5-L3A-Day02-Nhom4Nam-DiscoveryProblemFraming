# Báo cáo cá nhân - 2A202603488_TranDuongTrungTinh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Trần Dương Trung Tính
- MSSV: 2A202603488
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Nhom4Nam
- Link repo nhóm: https://github.com/duyanhtran2005/K5-L3A-Day02-Nhom4Nam-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi kiểm tra trang danh sách sách trên điện thoại, tôi muốn tìm được phần tử làm trang bị tràn ngang, để chỉnh giao diện trước khi bàn giao. | Người kiểm tra website, người dùng điện thoại | Khoảng 3 tiếng từ lúc bắt đầu kiểm tra đến khi sửa và kiểm tra lại xong lỗi responsive. Đây là tổng thời gian ước lượng, gồm cả chờ nếu có. |
| 2 | Cần đọc, tổng hợp nhiều thông tin | Khi kết nối trang danh sách quần áo với API, tôi muốn hiểu đúng cách gửi request và cấu trúc response, để hiển thị dữ liệu sản phẩm và xử lý đúng các trạng thái của màn hình. | Người phụ trách API, người kiểm tra website | Khoảng 1–2 ngày từ lúc bắt đầu tích hợp đến khi kiểm tra xong một màn hình, gồm cả thời gian chờ nếu có. Chưa quy đổi thành số giờ làm việc mỗi ngày. |
| 3 | Pain từ người khác | Khi người kiểm tra báo tổng tiền giỏ hàng không đổi sau khi tăng số lượng sản phẩm, tôi muốn tái hiện và tìm được nguyên nhân, để sửa đúng lỗi trước khi bàn giao. | Người kiểm tra website, người dùng giỏ hàng | Khoảng 3–4 giờ từ lúc nhận báo lỗi đến khi sửa và kiểm tra lại xong, gồm cả thời gian chờ nếu có. Đây là tổng thời gian ước lượng cho toàn bộ xử lý bug. |
| 4 | Lặp lại | Khi chuẩn bị bàn giao website bán hàng, tôi muốn kiểm tra lại các luồng xem sản phẩm, tìm kiếm và giỏ hàng, để phát hiện lỗi trước khi người khác sử dụng. | Người kiểm tra và nhận bàn giao website | Đợt kiểm tra trước khi bàn giao kéo dài khoảng 5 ngày, theo ước lượng của tôi; chưa tách riêng thời gian kiểm tra và sửa lỗi. |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi sửa thẻ sản phẩm dùng chung giữa trang chủ và trang danh sách, tôi muốn biết những trang nào chịu ảnh hưởng, để tránh sửa đúng một chỗ nhưng làm lỗi ở chỗ khác. | Người kiểm tra website | Việc sửa và kiểm tra ảnh hưởng của component dùng chung kéo dài khoảng 1 tuần trên website nhỏ, theo ước lượng của tôi. |


**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- **Ý giữ lại:** Tôi giữ 5 gợi ý liên quan đến giao diện, API, xử lý bug, kiểm tra trước bàn giao và component dùng chung. Tôi từng làm web bán sách và bán quần áo nên giới hạn bài trong các công việc lập trình liên quan đến hai dự án này.
- **Ý không chọn:** Tôi không chọn các gợi ý về roadmap và quản lý thay đổi giữa sprint vì không sát phần việc lập trình website nhỏ của tôi.
- **Điều tôi điều chỉnh:** Tôi bổ sung thời gian mình ước lượng và thu hẹp mỗi ý vào một công việc cụ thể. Tôi đã xác nhận 3 tình huống đưa vào CP2 đều từng gặp trong dự án của mình. Các mốc thời gian của 3 tình huống là tổng từ lúc bắt đầu đến khi hoàn tất, gồm cả chờ nếu có.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | #1 CP1 - Lỗi responsive ở danh sách sách | Gần phần giao diện tôi đã làm; phạm vi một trang, có thể kiểm tra kết quả bằng trình duyệt. Thời gian ban đầu khoảng 3 tiếng. | Thời gian từng bước hiện là phân bổ ước lượng từ tổng khoảng 3 tiếng, chưa phải kết quả bấm giờ; cần kiểm tra bước tìm quy tắc CSS có thực sự chậm nhất. |
| 2 | #3 CP1 - Lỗi tổng tiền giỏ hàng quần áo | Liên quan trực tiếp đến một thao tác của người dùng và có kết quả đúng/sai để kiểm tra. Toàn bộ xử lý bug khoảng 3–4 giờ. | Chưa có số đo từng bước để xác nhận thời gian phân tích luồng cập nhật chiếm bao nhiêu; tổng 3–4 giờ đã bao gồm thời gian chờ nếu có. |
| 3 | #2 CP1 - Tích hợp API cho danh sách quần áo | Sát công việc kết nối frontend với backend; giới hạn ở một màn hình, từ gửi request đến xử lý response và kiểm tra kết quả. Thời gian ban đầu khoảng 1–2 ngày. | Chưa tách rõ thời gian đọc tài liệu, viết kết nối, kiểm tra và chờ làm rõ thông tin API. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi kiểm tra trang danh sách sách trên điện thoại, tôi muốn tìm được phần tử làm trang bị tràn ngang, để chỉnh giao diện trước khi bàn giao. |
| Actor | Người trực tiếp làm giao diện website bán sách. |
| Thời điểm / bối cảnh | Khi kiểm tra giao diện trang danh sách sách ở màn hình 375px, trang bị tràn ngang dù hiển thị bình thường trên desktop. Cần kiểm tra chiều rộng của thẻ sách và vùng chứa danh sách. |
| Quy trình hiện tại (3–7 bước) | 1. Mở trang ở kích thước gặp lỗi → 2. Kiểm tra phần tử và CSS bằng DevTools → 3. Đối chiếu chiều rộng của thẻ sách với phần tử cha → 4. Sửa CSS → 5. Kiểm tra màn hình nhỏ → 6. Kiểm tra desktop và trang dùng chung thẻ sách. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Dự kiến là bước 3, khoảng 65 phút trong phân bổ ước lượng cho tổng 180 phút. Công việc chính là kiểm tra chiều rộng của thẻ sách và vùng chứa để tìm quy tắc gây tràn ngang. |
| Impact (nếu không giải thì sao) | Tôi ước lượng mất khoảng 3 tiếng cho việc tìm và sửa responsive. Trang bị cuộn ngang và một phần nội dung thẻ sách có thể nằm ngoài vùng nhìn thấy. |
| Success metric (baseline → target) | Từ tổng khoảng 180 phút xuống không quá 120 phút cho một lỗi responsive có phạm vi tương tự. Tôi sẽ ghi thời điểm bắt đầu kiểm tra và kết thúc kiểm tra bản sửa, gồm cả thời gian chờ nếu có. Trang phải hết tràn ngang ở 375px, 768px và vẫn hiển thị đúng trên desktop. |
| Phương án không dùng AI | Dùng DevTools kiểm tra từ vùng bị tràn lên các phần tử cha, thay đổi từng thuộc tính và kiểm tra lại. Lập checklist kích thước màn hình để không bỏ sót. Tham khảo cách hoạt động của [min-width trên MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/min-width). |
| Giả thuyết về AI (nếu có) | Nhờ AI đọc đoạn HTML/CSS liên quan và gợi ý thuộc tính cần kiểm tra. Tôi tự thử trên trình duyệt, không dùng ngay đề xuất nếu chưa kiểm tra tác động lên desktop. |
| Cảm nhận nhanh | No AI |

Quy trình nháp hiện tại:

```text
Phân bổ ước lượng theo tổng 180 phút, chưa bấm giờ riêng từng bước:
[1. Mở danh sách sách và tái hiện tràn ngang: 15 phút]
  → [2. Kiểm tra phần tử và CSS: 35 phút]
  → [3. Đối chiếu chiều rộng thẻ sách và vùng chứa: 65 phút] ← BOTTLENECK DỰ KIẾN
  → [4. Sửa CSS: 15 phút]
  → [5. Kiểm tra màn hình nhỏ: 20 phút]
  → [6. Kiểm tra desktop và trang liên quan: 30 phút]
Tổng: 180 phút, gồm cả chờ nếu có, không cộng thêm thời gian chờ ngoài tổng.
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi người kiểm tra báo tổng tiền giỏ hàng không đổi sau khi tăng số lượng sản phẩm, tôi muốn tái hiện và tìm được nguyên nhân, để sửa đúng lỗi trước khi bàn giao. |
| Actor | Tôi, người xử lý lỗi của website bán quần áo. |
| Thời điểm / bối cảnh | Khi kiểm tra giỏ hàng của website bán quần áo, thao tác tăng số lượng làm số lượng sản phẩm thay đổi nhưng tổng tiền vẫn giữ giá trị cũ. Chưa kết luận nguyên nhân trước khi kiểm tra luồng cập nhật dữ liệu và hiển thị. |
| Quy trình hiện tại (3–7 bước) | 1. Đọc báo lỗi và hỏi thêm thông tin nếu thiếu → 2. Chuẩn bị dữ liệu giỏ hàng và tái hiện → 3. Kiểm tra luồng cập nhật số lượng, giá và tổng tiền → 4. Xác định chỗ tính hoặc hiển thị chưa được cập nhật → 5. Sửa code → 6. Kiểm tra tăng, giảm số lượng và xóa sản phẩm. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Dự kiến là bước 3, khoảng 45–55 phút để kiểm tra luồng cập nhật số lượng, đơn giá và tổng tiền. Bước 4 xác định chỗ sai cụ thể được tách riêng, ước lượng 30–35 phút. |
| Impact (nếu không giải thì sao) | Ước lượng mất khoảng 3–4 giờ cho toàn bộ xử lý một bug. Tổng tiền không khớp số lượng sẽ khiến người kiểm tra hoặc người dùng không biết giá trị giỏ hàng nào là đúng. |
| Success metric (baseline → target) | Từ tổng khoảng 180–240 phút xuống không quá 150 phút cho một bug tương tự. Tôi sẽ ghi từ lúc nhận báo lỗi đến khi kiểm tra xong, gồm cả thời gian chờ, ghi riêng phần làm và chờ để phân tích, không cộng trùng. Tổng tiền phải khớp tổng đơn giá nhân số lượng sau các thao tác tăng, giảm và xóa. |
| Phương án không dùng AI | Dùng mẫu báo lỗi có bước thao tác và kết quả mong đợi/thực tế. Kiểm tra lần lượt dữ liệu số lượng, đơn giá, phép tính và phần hiển thị, chuẩn bị các giỏ hàng mẫu để kiểm tra bản sửa. |
| Giả thuyết về AI (nếu có) | Nhờ AI gợi ý các điểm cần kiểm tra từ mô tả lỗi và đoạn code được cung cấp. Tôi xác nhận bằng dữ liệu và thao tác thực tế; không coi một đoạn code đề xuất là bản sửa đã đúng. |
| Cảm nhận nhanh | No AI |

Quy trình nháp hiện tại:

```text
Phân bổ ước lượng theo tổng 180–240 phút, chưa bấm giờ riêng từng bước:
[1. Đọc báo lỗi giỏ hàng: 15–20 phút làm + 15–25 phút chờ]
  → [2. Tạo giỏ hàng và tái hiện lỗi: 30–40 phút]
  → [3. Kiểm tra luồng cập nhật số lượng và tổng tiền: 45–55 phút] ← BOTTLENECK DỰ KIẾN
  → [4. Xác định nguyên nhân cụ thể: 30–35 phút]
  → [5. Sửa code: 15–25 phút]
  → [6. Kiểm tra tăng, giảm và xóa sản phẩm: 30–40 phút]
Phần làm: 165–215 phút. Phần chờ đã tính trong bước 1: 15–25 phút.
Tổng làm và chờ: 180–240 phút; không cộng thời gian chờ thêm lần nữa.
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi kết nối trang danh sách quần áo với API, tôi muốn hiểu đúng cách gửi request và cấu trúc response, để hiển thị dữ liệu sản phẩm và xử lý đúng các trạng thái của màn hình. |
| Actor | Người tích hợp API cho giao diện website bán quần áo. |
| Thời điểm / bối cảnh | Khi chuyển trang danh sách quần áo từ dữ liệu mẫu sang dữ liệu lấy từ backend. Phần việc gồm xác định endpoint, tham số request, cấu trúc response và cách xử lý khi API trả dữ liệu rỗng hoặc lỗi. |
| Quy trình hiện tại (3–7 bước) | 1. Đọc yêu cầu màn hình và tài liệu API → 2. Gửi request thử để kiểm tra endpoint, tham số và response → 3. Đối chiếu cấu trúc dữ liệu với nhu cầu giao diện → 4. Viết phần gọi API và xử lý các trạng thái màn hình → 5. Kiểm tra dữ liệu thành công, rỗng và lỗi → 6. Làm rõ điểm chưa khớp, sửa và kiểm tra lại. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Theo bảng phân bổ tham khảo, dự kiến là bước 4, khoảng 120–180 phút: viết kết nối và xử lý trạng thái đang tải, thành công, rỗng và lỗi. Bước 3 đối chiếu dữ liệu dự kiến 90–150 phút. Chưa có số đo thực tế để xác nhận bước nghẽn. |
| Impact (nếu không giải thì sao) | Ước lượng mất khoảng 1–2 ngày cho việc tích hợp một màn hình. Nếu hiểu sai request hoặc response, dữ liệu sản phẩm có thể không hiển thị đúng và phần xử lý lỗi phải sửa lại. |
| Success metric (baseline → target) | Baseline ước lượng: tổng 1–2 ngày từ lúc bắt đầu tích hợp đến khi kiểm tra xong một màn hình, đã gồm chờ nếu có. Target đề xuất: không quá 1 ngày cho phạm vi tương tự, theo cùng cách tính. Tôi sẽ ghi thời điểm bắt đầu/kết thúc và theo dõi riêng các phiên làm, chờ; không mặc định một ngày bằng 8 giờ. Điều kiện chất lượng: request đúng yêu cầu, dữ liệu hiển thị khớp response, xử lý được trạng thái đang tải, rỗng và lỗi. |
| Phương án không dùng AI | Thống nhất tài liệu request/response với người phụ trách API, lưu dữ liệu mẫu và lập checklist kiểm tra trước khi viết kết nối. Dùng công cụ gửi request và tab Network để đối chiếu dữ liệu. Tham khảo [hướng dẫn Fetch API của MDN](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch). |
| Giả thuyết về AI (nếu có) | Có thể nhờ AI đọc tài liệu API và response mẫu để gợi ý điểm chưa khớp hoặc trường hợp còn thiếu. Tôi kiểm lại bằng request thực tế; chưa có căn cứ cần AI cho toàn bộ quá trình tích hợp. |
| Cảm nhận nhanh | No AI |

Quy trình nháp hiện tại:

```text
Ước lượng tham khảo theo bước, chưa phải kết quả bấm giờ:
[1. Đọc yêu cầu và tài liệu API: 45–90 phút]
  → [2. Gửi request thử, kiểm tra tham số và response: 30–60 phút]
  → [3. Đối chiếu cấu trúc dữ liệu với giao diện: 90–150 phút]
  → [4. Viết gọi API và xử lý trạng thái màn hình: 120–180 phút] ← BOTTLENECK DỰ KIẾN
  → [5. Kiểm tra thành công, dữ liệu rỗng và lỗi: 60–120 phút]
  → [6. Làm rõ điểm chưa khớp, sửa và kiểm tra: 60–120 phút làm + 30–120 phút chờ]
Phân bổ trong các phiên làm việc: 405–720 phút làm và 30–120 phút chờ.
Baseline tổng từ bắt đầu đến hoàn tất: 1–2 ngày, đã gồm chờ nếu có.
Các khoảng phút là ước lượng tham khảo trong phiên làm việc, không phải phép quy đổi 1–2 ngày.
Khi ghi nhận thực tế, dùng thời điểm bắt đầu/kết thúc để đo tổng và ghi riêng các phiên làm, chờ.
```

### Card muốn pitch nhất

- Card số: 1 - Tìm và sửa lỗi responsive ở trang danh sách sách.
- Vì sao: Tôi đã có kinh nghiệm làm giao diện web bán sách nên dễ mô tả và kiểm tra trường hợp này. Phạm vi một trang cũng vừa sức để phân tích trong buổi lab.
- Câu hỏi muốn nhóm phản biện: Tôi mất nhiều thời gian vì chưa có cách khoanh vùng lỗi CSS, hay vì phải kiểm tra lại quá nhiều kích thước màn hình? Chỉ dùng checklist và DevTools đã đủ chưa?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Phạm vi và cách cộng thời gian ở CP1–CP2 chưa thống nhất: 3–4 giờ bị hiểu là chỉ tái hiện; phần chờ có thể bị cộng thêm ngoài baseline. Card API cũng bị thu hẹp vào dữ liệu ảnh. | Đồng ý: tôi xác nhận 3 case đã từng làm và các baseline đều tính từ bắt đầu đến hoàn tất, gồm cả chờ nếu có. | Đồng bộ CP1–CP2, tách phần làm/chờ trong cùng tổng, hiệu chỉnh phân bổ ước lượng và sửa card API theo toàn bộ quá trình gửi request, xử lý response, hiển thị và kiểm tra. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Tôi trình bày 3 card đã chọn ở CP2: sửa lỗi responsive trang danh sách sách, xử lý lỗi tổng tiền giỏ hàng và tích hợp API cho trang danh sách quần áo. | Đóng góp các candidate T1, T2, T3 vào danh sách 12 candidate của nhóm để so sánh và gom nhóm. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | Tôi tiếp nhận bản CP4 từ bạn phụ trách, cung cấp bản này để đối chiếu với CP5 và xác nhận các snapshot A–C là phỏng vấn người thật. | CP5 sử dụng kết quả kiểm chứng của nhóm; các mốc thời gian khác phạm vi được tách riêng thay vì gộp thành một baseline. |
| Quy trình nhóm | Tôi phụ trách rà soát và hoàn thiện CP5, đối chiếu CP3–CP4 và tính đủ các bước chuẩn bị, kiểm tra, phân công. | Mục 4 có quy trình trước/sau, actor, input, output, thời gian, điểm kiểm tra của con người và phương án quay về. |
| Problem Statement | Tôi yêu cầu thống nhất mốc đo giữa sơ đồ và v0, bổ sung đầy đủ các quyền AI không được tự thực hiện và người chịu trách nhiệm kiểm nguồn. Tôi xác nhận nhóm đồng ý các phản biện đã nêu. | Mốc đo kết thúc khi phân công xong và thành viên xác nhận tiếp nhận; Boundary v0 thống nhất với quy trình tương lai. |
| Mức can thiệp AI | Trong CP5, tôi rà soát vị trí các bước Rule, AI. | Quy trình thể hiện AI tạo nháp, các bước kiểm tra cố định và bước người dùng duyệt trước khi phân công. |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Nhờ AI gợi ý và soạn bản nháp 5 vấn đề trong công việc lập trình website để tôi rà soát. | Giúp chuyển từ ví dụ PM sang bối cảnh làm web bán sách và bán quần áo. | AI từng đề xuất các chi tiết case trước khi hỏi lại tôi và có lúc tự thay đổi bố cục template. | Tôi cung cấp 5 mốc thời gian ước lượng, xác nhận 3 case đưa vào CP2 đã từng làm, giới hạn chủ đề vào lập trình website và yêu cầu giữ nguyên khung mẫu. |
| CP2 Problem Card | Nhờ AI soạn bản nháp 3 card, gợi ý quy trình và phản biện phạm vi, thời gian, mức can thiệp. | Giúp phân biệt tổng thời gian với thời gian từng bước và làm rõ phương án không dùng AI. | AI từng hiểu 3–4 giờ là chỉ tái hiện lỗi, thu hẹp tích hợp API vào dữ liệu ảnh và thêm mục ngoài template. Các khoảng thời gian từng bước vẫn là tham khảo. | Tôi xác nhận 3–4 giờ là toàn bộ xử lý bug và các baseline đều gồm chờ nếu có; yêu cầu đồng bộ CP1–CP2, sửa phạm vi card API và giữ đúng template. |
| CP4 Research | | | | |
| CP5 Quy trình | Hỗ trợ biểu diễn dữ liệu CP3–CP4 thành sơ đồ và bảng trước/sau, rà soát sự nhất quán với template. | Giúp thể hiện rõ actor, đầu vào, đầu ra, vị trí kiểm tra và phương án quay về. | AI từng đánh giá CP5 hoàn chỉnh khi mốc đo và Boundary v0 còn chưa nhất quán; đã có lúc tự thêm mục ngoài khung. | Xác nhận bối cảnh phỏng vấn, yêu cầu đọc lại rule, giữ đúng bố cục và chỉnh các điểm chưa nhất quán trước khi push. |
| CP5–6 Problem Statement | Hỗ trợ chuyển các ý đã có ở CP3–CP4 vào mẫu v0 và phản biện metric, Boundary. | Chỉ ra khác biệt giữa mốc kết thúc ở sơ đồ và trong metric, cùng các quyền hạn chưa được ghi đầy đủ. | Mô tả ban đầu chưa thống nhất việc có tính bước phân công; Boundary v0 ngắn hơn các giới hạn đã có ở mục 4.2. | Tôi yêu cầu dùng một mốc đo đến khi phân công xong và thành viên xác nhận tiếp nhận, bổ sung giới hạn AI không tự sửa tài liệu, phân công, gửi thông báo hoặc nộp bài. |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.** Nội dung trả lời dưới đây là bản nháp do AI hỗ trợ để tôi tham khảo và tự viết lại theo trải nghiệm trước khi nộp.

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Qua các Problem Card của các bạn, tôi thấy kinh nghiệm của mỗi người giúp nhóm nhìn ra những vấn đề khác nhau. Tôi trình bày các vấn đề từ việc làm web bán sách và bán quần áo, còn nhóm ghi nhận thêm khó khăn khi đọc đề, bàn giao công việc và quản lý tài liệu. Điều tôi rút ra là một vấn đề quen thuộc với mình chưa chắc phù hợp nhất để cả nhóm kiểm chứng trong thời gian lab. Tôi cần nhìn thêm actor, phạm vi và dữ liệu có thể thu thập.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Trong phần research CP4, nhóm đã có định hướng về công cụ tổng hợp yêu cầu bằng AI. Tôi thấy cần giữ rõ bước tìm hiểu vấn đề trước khi chốt cách giải quyết. Ở phần CP5 mình phụ trách, tôi tập trung rà quy trình hiện tại, đầu ra từng bước và phần việc trưởng nhóm vẫn phải tự kiểm tra. Tôi giữ phương án quay về checklist thủ công để nhóm có cách xử lý khi bản tổng hợp sai hoặc công cụ gặp lỗi.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Ban đầu tôi chủ yếu kiểm tra xem báo cáo đã điền đủ các mục hay chưa. Khi rà soát kỹ hơn, tôi đồng ý rằng đủ ô chưa có nghĩa là nội dung đã nhất quán. Sơ đồ và Success Metric từng dùng hai cách diễn đạt khác nhau về mốc kết thúc. Tôi yêu cầu sửa cả hai về thời điểm phân công xong và thành viên xác nhận tiếp nhận, đồng thời đưa các giới hạn đã có trong quy trình vào đúng ô Boundary của v0.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Điểm đáng chú ý từ CP4 là không phải người nào cũng mất nhiều thời gian khi đọc hướng dẫn. Một người cho biết nếu README rõ thì việc xác định yêu cầu diễn ra nhanh. Các mốc 10–20 phút trong phỏng vấn cũng đo những phần việc khác với tổng 40 phút của D3. Khi tiếp nhận kết quả từ bạn phụ trách CP4 để hoàn thiện CP5, tôi yêu cầu giữ riêng các phạm vi này. Tôi không dùng chúng để khẳng định mọi sinh viên đều gặp cùng mức độ khó khăn.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Khó nhất với tôi khi rà soát Problem Statement là giữ cùng một phạm vi giữa quy trình, baseline, target và boundary. Tôi phải làm rõ tổng thời gian có tính phần phân công hay không, ai chịu trách nhiệm kiểm kết quả và AI được làm đến đâu. Tôi cũng phân biệt 40 phút là ước lượng từ D3, còn 19 phút là ngân sách mục tiêu của phương án mới. Nếu viết hai loại số này như kết quả đã đo thì báo cáo sẽ thiếu chính xác.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu làm lại, tôi sẽ thống nhất mốc bắt đầu, kết thúc và cách ghi thời gian ngay khi nhóm chọn candidate. Tôi cũng muốn nhóm thử checklist thủ công trước để có cơ sở so sánh với phương án có AI. Khi phản biện, tôi sẽ hỏi rõ ai kiểm tra, dùng nguồn nào và phải làm gì nếu thiếu thông tin. Tôi sẽ kiểm tra bố cục và sự thống nhất giữa các phần sớm hơn, thay vì chờ đến lúc chuẩn bị push mới rà lại.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Trưởng nhóm chịu trách nhiệm tổng hợp yêu cầu từ nhiều file. Việc này được thực hiện trước khi phân công bài lab dựa trên quy trình xác định nguồn, đọc checkpoint, đối chiếu yêu cầu, ghi đầu ra và phân công, nhằm giải quyết bottleneck đối chiếu nhiều tài liệu. Mục tiêu CP5 đặt target hoàn thành dưới 20p với ngân sách thiết kế 19p, tính từ lúc bắt đầu cho đến khi phân công xong và thành viên xác nhận tiếp nhận. Về giới hạn thì AI chỉ đóng vai trò tạo nháp, trưởng nhóm phải kiểm toàn bộ nguồn trước khi sử dụng. Đồng thời AI tuyệt đối không tự sửa tài liệu, tự động phân công hay nộp bài. Nhóm đã lựa chọn mức can thiệp là workflow, kết hợp các bước cố định với tính năng trích xuất bằng AI và sự phê duyệt trực tiếp từ người dùng. Dự án quyết định Go ở phạm vi pilot, với điều kiện nếu sau 1 tuần hoặc 5 lượt mà thời gian thực tế vẫn vượt quá 20 phút mỗi lượt, hoặc AI liên tục bỏ sót và phân loại sai các yêu cầu quan trọng, nhóm sẽ lập tức quay về phương pháp checklist thủ công.

---

## 7. Tài liệu tham khảo

- [MDN: min-width](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/min-width); [MDN: Using the Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch).
