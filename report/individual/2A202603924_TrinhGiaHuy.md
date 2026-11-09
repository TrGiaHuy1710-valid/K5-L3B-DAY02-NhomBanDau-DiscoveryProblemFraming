# Báo cáo cá nhân — 2A202603924_TrinhGiaHuy

> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).

## 1. Thông tin học viên

- Họ tên: Trịnh Gia Huy
- MSSV: 2A202603924
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: NhomBanDau
- Link repo nhóm: https://github.com/TrGiaHuy1710-valid/K5-L3B-DAY02-NhomBanDau-DiscoveryProblemFraming/tree/main

---

## 2. Scan problem (CP1)

**Định hướng:** Tìm kiếm các vấn đề trong quy trình quản lý, giám sát và đánh giá chất lượng cây trồng tại hộ nông dân, HTX và doanh nghiệp thu mua.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi cần kiểm tra tình trạng cây trồng của nhiều hộ, tôi muốn có quy trình ghi nhận thống nhất để tránh phải kiểm tra và tổng hợp thông tin nhiều lần. | Cán bộ kỹ thuật HTX | Kiểm tra lặp lại theo chu kỳ sinh trưởng; cần khảo sát số hộ và thời gian thực tế. |
| 2 | Tốn thời gian | Khi cần tổng hợp báo cáo sản xuất, tôi muốn dữ liệu từ các hộ được tập trung để giảm thời gian thu thập và nhập liệu thủ công. | Giám đốc HTX, cán bộ kỹ thuật | Dữ liệu có thể nằm trong sổ, Excel, Zalo và hình ảnh riêng lẻ. |
| 3 | Cần tổng hợp nhiều thông tin | Khi cần đánh giá chất lượng vùng trồng, tôi muốn đối chiếu tiêu chuẩn với tình trạng thực tế để biết hộ nào cần kiểm tra thêm. | HTX, doanh nghiệp thu mua | Phải tổng hợp tiêu chuẩn, nhật ký, hình ảnh và kết quả kiểm tra. |
| 4 | Pain từ người khác | Khi được yêu cầu cung cấp thông tin chất lượng vùng nguyên liệu, tôi muốn có hồ sơ theo từng hộ và từng chu kỳ để cung cấp bằng chứng nhanh chóng. | HTX, doanh nghiệp thu mua | Cần thu thập lại ảnh, nhật ký và thông tin từ nhiều hộ khi có yêu cầu báo cáo. |
| 5 | Lặp lại | Khi cần theo dõi tình trạng cây trồng qua nhiều thời điểm, tôi muốn lưu lại hình ảnh theo chu kỳ để so sánh biến động thay vì chỉ đánh giá tại một thời điểm. | Nông dân, cán bộ kỹ thuật | Ảnh thường được lưu riêng trên điện thoại, khó so sánh theo thời gian. |
| 6 | Tốn thời gian | Khi phát hiện cây trồng có dấu hiệu bất thường, tôi muốn biết khu vực và hộ cần kiểm tra trước để ưu tiên thời gian đi thực địa. | Cán bộ kỹ thuật HTX | Việc kiểm tra có thể phải thực hiện thủ công trên nhiều hộ và nhiều khu vực. |
| 7 | Cần tổng hợp nhiều thông tin | Khi cần đánh giá việc tuân thủ quy trình sản xuất, tôi muốn đối chiếu nhật ký canh tác với các tiêu chí đã thiết lập để phát hiện thông tin còn thiếu. | HTX, doanh nghiệp | Nhật ký phân bón, thuốc bảo vệ thực vật và hoạt động chăm sóc cần được tổng hợp. |
| 8 | Pain từ người khác | Khi cần biết chất lượng vùng nguyên liệu trước khi thu mua, tôi muốn xem báo cáo tình trạng từng hộ để giảm rủi ro khi lựa chọn nguồn cung. | Doanh nghiệp thu mua | Doanh nghiệp cần thông tin trước thu hoạch nhưng mức độ thiếu hụt dữ liệu cần phỏng vấn xác minh. |

### Nếu có dùng AI để gợi ý thêm

- Giữ lại ý tưởng hệ thống hóa quy trình kiểm tra chất lượng theo hộ, vùng trồng và chu kỳ vì đây là vấn đề có thể tạo ra giá trị cho HTX.
- Giữ lại ý tưởng Computer Vision hỗ trợ phân tích hình ảnh cây trồng vì hình ảnh là nguồn dữ liệu có thể thu thập trực tiếp từ nông dân.
- Giữ lại ý tưởng báo cáo và thống kê tự động vì có thể đo lường thời gian trước và sau khi triển khai.
- Không chọn ngay các ý tưởng dự báo năng suất, drone, IoT, blockchain và AI Agent vì cần nhiều dữ liệu, thiết bị và chi phí hơn phạm vi thử nghiệm ban đầu.
- Không xem kết quả AI nhận diện bệnh là kết luận chất lượng hoặc chứng nhận tiêu chuẩn sản xuất.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | HTX gặp khó khăn trong việc theo dõi và tổng hợp tình trạng cây trồng của nhiều hộ theo chu kỳ. | Ảnh hưởng trực tiếp đến hoạt động quản lý, kiểm tra và báo cáo. Có thể triển khai thử nghiệm bằng smartphone và phần mềm. | Thời gian tổng hợp hiện tại, số hộ và mức độ sẵn sàng sử dụng. |
| 2 | Cán bộ kỹ thuật mất thời gian kiểm tra và phát hiện các dấu hiệu bất thường trên nhiều khu vực trồng. | Có thể ứng dụng Computer Vision để hỗ trợ sàng lọc và ưu tiên kiểm tra. | Độ chính xác AI trên ảnh thực địa và khả năng phát hiện sớm. |
| 3 | Doanh nghiệp thu mua thiếu dữ liệu thống nhất để đánh giá chất lượng vùng nguyên liệu trước khi thu mua. | Có giá trị thương mại, liên quan đến truy xuất, kiểm soát chất lượng và quyết định thu mua. | Doanh nghiệp có thực sự cần dữ liệu này và có ngân sách chi trả hay không. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần quản lý tình trạng sản xuất của nhiều hộ, tôi muốn tập trung dữ liệu hình ảnh, nhật ký và kết quả kiểm tra theo từng chu kỳ để theo dõi chất lượng vùng trồng và giảm thời gian tổng hợp báo cáo. |
| Actor | Giám đốc HTX và cán bộ kỹ thuật. |
| Thời điểm / bối cảnh | Trong quá trình theo dõi cây trồng, kiểm tra định kỳ và chuẩn bị báo cáo cho doanh nghiệp thu mua. |
| Quy trình hiện tại (3–7 bước) | 1. Phân công hộ kiểm tra. 2. Nông dân ghi nhận tình trạng cây. 3. Gửi ảnh và thông tin qua các kênh liên lạc. 4. Cán bộ kỹ thuật kiểm tra. 5. Tổng hợp thông tin. 6. Lập báo cáo. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Khâu thu thập và tổng hợp dữ liệu từ nhiều hộ. Thời gian thực tế cần khảo sát và đo baseline trong tuần đầu. |
| Impact (nếu không giải thì sao) | Dữ liệu phân tán, khó theo dõi lịch sử, khó phát hiện hộ thiếu báo cáo và mất thời gian khi cần tổng hợp thông tin. |
| Success metric (baseline → target) | Thời gian lập báo cáo giảm tối thiểu 30%; tỷ lệ hộ hoàn thành lịch ghi nhận đạt tối thiểu 80%. Baseline sẽ đo trong tuần đầu. |
| Phương án không dùng AI | Xây dựng biểu mẫu điện tử, cơ sở dữ liệu tập trung, lịch kiểm tra và dashboard thống kê. |
| Giả thuyết về AI (nếu có) | Computer Vision hỗ trợ phân tích ảnh, phát hiện dấu hiệu bất thường và tự động gắn kết quả vào hồ sơ hộ. |
| Cảm nhận nhanh | Workflow kết hợp AI. |

Quy trình nháp hiện tại:

```text
HTX lập danh sách hộ và lịch kiểm tra
                |
                v
Phân công cán bộ / hộ nông dân
                |
                v
Nông dân ghi nhận tình trạng cây
                |
                v
Gửi ảnh, video và nhật ký
                |
                v
Cán bộ kỹ thuật kiểm tra
                |
                v
Tổng hợp dữ liệu từ nhiều nguồn
                |
                v
Lập báo cáo chất lượng vùng trồng
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần kiểm tra tình trạng cây trồng tại nhiều hộ, tôi muốn được hỗ trợ phát hiện những dấu hiệu bất thường từ hình ảnh để ưu tiên các khu vực cần kiểm tra thực tế. |
| Actor | Cán bộ kỹ thuật HTX. |
| Thời điểm / bối cảnh | Trong các đợt kiểm tra định kỳ hoặc khi nông dân gửi hình ảnh có dấu hiệu bất thường. |
| Quy trình hiện tại (3–7 bước) | 1. Nhận thông tin từ hộ. 2. Xem ảnh cây trồng. 3. Đánh giá dấu hiệu bất thường. 4. Liên hệ hộ để hỏi thêm. 5. Đi kiểm tra thực tế. 6. Đưa ra hướng xử lý. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Phân tích thủ công nhiều hình ảnh và xác định hộ cần ưu tiên kiểm tra. Cần đo thời gian thực tế. |
| Impact (nếu không giải thì sao) | Có thể bỏ sót dấu hiệu bất thường, chậm kiểm tra hoặc sử dụng thời gian không hiệu quả. |
| Success metric (baseline → target) | Macro F1 mục tiêu ban đầu ≥ 0,80 và Recall nhóm bất thường quan trọng ≥ 0,85 trên tập kiểm thử thực địa; cần xác nhận khả năng đạt được. |
| Phương án không dùng AI | Checklist hình ảnh, hướng dẫn chụp ảnh và phân công cán bộ kiểm tra theo lịch. |
| Giả thuyết về AI (nếu có) | Computer Vision kiểm tra chất lượng ảnh, nhận diện lá/cây và phân loại các nhóm dấu hiệu bất thường trong phạm vi một loại cây. |
| Cảm nhận nhanh | AI kết hợp Workflow. |

Quy trình nháp hiện tại:

```text
Nông dân gửi hình ảnh
          |
          v
Cán bộ kỹ thuật tiếp nhận
          |
          v
Quan sát và đánh giá thủ công
          |
          v
Xác định dấu hiệu bất thường
          |
          v
Kiểm tra thực địa nếu cần
          |
          v
Xác nhận và hướng dẫn xử lý
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần lựa chọn vùng nguyên liệu để thu mua, tôi muốn có dữ liệu chất lượng và lịch sử sản xuất theo từng hộ để đánh giá mức độ đáp ứng yêu cầu của doanh nghiệp. |
| Actor | Bộ phận thu mua và quản lý chất lượng doanh nghiệp. |
| Thời điểm / bối cảnh | Trước thu hoạch, trong quá trình kiểm tra vùng nguyên liệu và khi đánh giá nhà cung cấp. |
| Quy trình hiện tại (3–7 bước) | 1. Gửi yêu cầu chất lượng cho HTX. 2. HTX thu thập thông tin. 3. Cán bộ kỹ thuật kiểm tra. 4. Tổng hợp kết quả. 5. Doanh nghiệp đánh giá. 6. Quyết định lựa chọn nguồn cung. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Thu thập và đối chiếu thông tin giữa doanh nghiệp và HTX. Chưa xác định thời gian thực tế. |
| Impact (nếu không giải thì sao) | Khó đánh giá mức độ đáp ứng yêu cầu, thiếu hồ sơ bằng chứng và tăng thời gian kiểm tra trước thu mua. |
| Success metric (baseline → target) | 100% hồ sơ hộ trong pilot có trạng thái dữ liệu rõ ràng; giảm tối thiểu 30% thời gian tổng hợp báo cáo nếu baseline xác nhận có dư địa cải thiện. |
| Phương án không dùng AI | Hệ thống quản lý hồ sơ điện tử và checklist chất lượng theo từng hộ. |
| Giả thuyết về AI (nếu có) | AI hỗ trợ phân tích ảnh và tổng hợp các dấu hiệu bất thường vào báo cáo, không tự động quyết định chất lượng lô hàng. |
| Cảm nhận nhanh | Workflow kết hợp AI. |

Quy trình nháp hiện tại:

```text
Doanh nghiệp đưa ra yêu cầu chất lượng
                  |
                  v
HTX thu thập dữ liệu các hộ
                  |
                  v
Cán bộ kỹ thuật kiểm tra
                  |
                  v
Tổng hợp báo cáo vùng nguyên liệu
                  |
                  v
Doanh nghiệp đối chiếu yêu cầu
                  |
                  v
Đánh giá và quyết định thu mua
```

### Card muốn pitch nhất

- Card số: 1.
- Vì sao: Đây là vấn đề có phạm vi rõ ràng, ảnh hưởng trực tiếp đến hoạt động quản lý HTX và có thể giải quyết bằng một hệ thống phần mềm trước khi đầu tư vào AI phức tạp. Hệ thống cũng tạo ra dữ liệu đầu vào cho các chức năng Computer Vision, đánh giá và báo cáo ở giai đoạn sau.
- Câu hỏi muốn nhóm phản biện: Liệu việc tổng hợp dữ liệu và quản lý kiểm tra có đủ gây tốn thời gian để HTX sẵn sàng trả tiền hay không? Nếu HTX đã sử dụng Excel hoặc Zalo, sản phẩm cần tạo ra giá trị khác biệt nào để họ chuyển đổi?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Phạm vi ban đầu quá rộng, bao gồm nhiều loại cây và nhiều tiêu chuẩn. | Có | Giới hạn một loại cây, một HTX và một bộ tiêu chí trong MVP. |
| Chưa phân biệt người sử dụng và người trả tiền. | Có | Nông dân và cán bộ HTX là người sử dụng; HTX hoặc doanh nghiệp là khách hàng trả tiền tiềm năng. |
| Nhận diện bệnh cây không phải lợi thế cạnh tranh đủ mạnh. | Có | Chuyển trọng tâm sang quy trình thu thập bằng chứng, quản lý hộ, xác nhận và báo cáo. |
| Chưa có baseline nên chưa chứng minh được tiết kiệm thời gian. | Có | Bổ sung hoạt động đo thời gian thực tế trước khi triển khai. |
| AI có thể đưa ra kết luận sai về chất lượng cây trồng. | Có | AI chỉ đưa ra dấu hiệu và mức tin cậy; cán bộ kỹ thuật xác nhận. |
| Chưa có bằng chứng khách hàng sẵn sàng trả tiền. | Có | Bổ sung mục tiêu kiểm chứng willingness-to-pay trong giai đoạn pilot. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

*Các nội dung dưới đây là khung mô tả công việc dự kiến theo hướng dự án. Chỉ giữ những hoạt động thực sự đã thực hiện và bổ sung kết quả cụ thể.*

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày vấn đề HTX gặp khó khăn trong việc quản lý và tổng hợp tình trạng cây trồng của nhiều hộ. | Đề xuất tập trung vào một quy trình nghiệp vụ thay vì phát triển ứng dụng nông nghiệp tổng quát. |
| Phản biện bài của bạn khác | Mỗi bạn nghiên cứu môt ý tưởng (AI tóm tắt bài học, AI phân tích chi tiêu, AI phân tích log lỗi của intern, gửi ticket đến senior khi lỗi level cao hơn). Câu hỏi tôi đã đặt. 1) Cho AI tóm tắt bài học: Có giải pháp nào đã có chưa cho ? NotebookLM đã làm được hết thì bạn có gì tốt hơn, 2) Phân tích chi tiêu: Có thật sự cần ai không? Đã có ai làm? Có tính năng gì hơn? Tại sao phản trả tiền cho tính năng này. 3) Bài phân tích log: dự án này bán được cho ai? Tại sao công ty công nghệ không thể tự build? có khó khi tự build không | Bổ sung góc nhìn về persona và mô hình khách hàng. |
| Nhận phản biện | Câu hỏi tôi nhận được: AI có thực sự cần thiết không, Scope có đang quá rộng không? Đã có sản phẩm ở thị trường chưa? Có ở quốc tế chưa? | Cần kiểm tra khả năng giải quyết bằng phần mềm thông thường trước khi quyết định sử dụng AI. |
| Gom cluster / cây OST | Gom các vấn đề thành nhóm quản lý dữ liệu, giám sát cây trồng, kiểm tra chất lượng và báo cáo. | Xác định hướng giải pháp tập trung vào quản lý chất lượng vùng trồng. |
| Chọn candidate problem | Chọn vấn đề tổng hợp và theo dõi dữ liệu sản xuất của các hộ HTX. | Phạm vi có thể kiểm chứng bằng pilot trong 8 tuần. |
| Kiểm chứng / research | Nghiên cứu các giải pháp Plantix, mobiAgri, NextFarm, Agrio; tìm hiểu tiêu chuẩn và khả năng ứng dụng CV. | Nhận thấy không nên cạnh tranh bằng chức năng nhận diện bệnh cây đơn thuần. |
| Quy trình nhóm | Đề xuất quy trình từ thiết lập tiêu chuẩn, tạo baseline, thu thập dữ liệu đến phân tích, xác nhận và báo cáo, quy trình được tổng hợp và phân tích từ nguồn uy tín, baseline end to end từ chính phủ đến từng hộ gia đình. | Hình thành quy trình nghiệp vụ thống nhất. |
| Problem Statement | Xác định khó khăn trong thu thập, quản lý và đối chiếu dữ liệu chất lượng cây trồng giữa nhiều hộ. | Chuyển mô tả giải pháp thành một vấn đề cụ thể của HTX. |
| Mức can thiệp AI | Đề xuất CV hỗ trợ kiểm tra ảnh và phát hiện dấu hiệu bất thường; Rule Engine đối chiếu checklist. | Giới hạn vai trò AI và giữ quyết định cuối cùng cho cán bộ kỹ thuật. |
| Quyết định | Đề xuất MVP một HTX, một loại cây, 10–20 hộ, thử nghiệm trong 8 tuần. | Có phạm vi, chỉ số và điều kiện đánh giá khả thi hơn. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Gợi ý các vấn đề trong quy trình sản xuất, kiểm tra và quản lý cây trồng. | Mở rộng góc nhìn về các pain point của nông dân, HTX và doanh nghiệp. | Một số vấn đề được đề xuất nhưng chưa có bằng chứng thực tế. | Chỉ giữ các vấn đề có thể khảo sát và đo lường. |
| CP2 Problem Card | Hỗ trợ xây dựng Job Story, Actor và quy trình hiện tại. | Phân tách vấn đề theo từng nhóm người dùng. | Ban đầu dễ tập trung vào giải pháp AI thay vì vấn đề thực tế. | Đưa hoạt động quản lý dữ liệu và tổng hợp báo cáo lên trước chức năng AI. |
| CP4 Research | Nghiên cứu các sản phẩm cạnh tranh và xu hướng Agritech. | Xác định đối thủ và khoảng trống có thể khai thác. | Thông tin quảng bá sản phẩm không phản ánh đầy đủ hiệu năng thực tế. | Phân biệt chức năng công khai với tính năng đã được kiểm chứng bằng demo. |
| CP5 Quy trình | Xây dựng quy trình giám sát cây trồng theo chu kỳ. | Hỗ trợ mô tả các bước thu thập, xử lý và xác nhận. | Quy trình ban đầu có nhiều chức năng vượt quá MVP. | Giới hạn một loại cây, một HTX và một luồng kiểm tra. |
| CP5–6 Problem Statement | Hỗ trợ viết lại vấn đề theo Actor, bối cảnh, pain và impact. | Làm rõ đối tượng chịu ảnh hưởng và kết quả mong muốn. | Có thể đưa ra các tác động chưa có số liệu. | Để các số liệu chưa xác minh ở dạng giả thuyết cần khảo sát. |
| CP6 Mức can thiệp / quyết định | So sánh No AI, Rule, Workflow và AI. | Xác định phần việc nào thực sự cần Computer Vision. | Có xu hướng đề xuất nhiều mô hình và công nghệ không cần thiết. | Chỉ dùng CV cho phân tích ảnh; các chức năng quản lý, phân quyền và báo cáo sử dụng logic thông thường. |

---

## 6. Reflection (CP7)

> Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). Không dùng AI để viết thay.

### 6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?

- Problem scope cần đơn giản hơn, không bị vĩ mô
- Tính khả thi của dự án, phân tích kỹ đối thủ

### 6.2. Nhóm có lúc nào bị solution-first không?

- Phân tích là có thể chưa có data, mô hình cho loại trái cây đặc thù
- Chưa có tài liệu chi tiết về việc xử lý của từng HTX
- Nhu cầu thực tế, Việt Nam là nước xuất khẩu trái cây lớn
- Thu hẹp phạm vi xuống sầu riêng hoặc thanh long, rồi triển khai nhân rộng scope cây trồng sau

### 6.3. Tôi có đổi ý sau khi bị phản biện không?

- Dữ nguyên mức tầng người dùng
- Scope rộng thách thức khả năng triển khai
- Xác định khách hàng là các HTX, doanh nghiệp trả phí kết hợp với chính phủ
- Xác định rõ hơn bài toán

### 6.4. Kết quả kiểm chứng có làm tôi bất ngờ không?

Nghiên cứu thêm
- Những thông tin thu được từ phỏng vấn, khảo sát hoặc nghiên cứu đối thủ.
- Khác biệt giữa giả định ban đầu và thông tin thực tế.
- Khả năng HTX sử dụng phần mềm và khả năng trả tiền.
- Những giả thuyết vẫn chưa được xác nhận.

### 6.5. Điều khó nhất khi viết Problem Statement là gì?

- Khó khăn khi tìm thông tin đối thủ, thông tin HTX.
- Cần thời gian để chứng tác động thực tế
- Giới hạn phạm vi để Problem Statement không quá rộng.

### 6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?

Nếu làm lại, tôi sẽ khảo sát HTX, cán bộ kỹ thuật và nông dân sớm hơn để xác định chính xác vấn đề thay vì dựa nhiều vào giả định. Tôi sẽ đo thời gian thực hiện quy trình hiện tại, tìm hiểu khả năng chi trả và phân tích đối thủ trước khi đề xuất chức năng. Khi phản biện nhóm, tôi sẽ tập trung vào ba câu hỏi: Giải pháp có thực sự cần AI không? Dữ liệu thực tế có đủ để xây dựng mô hình đáng tin cậy không? Chi phí vận hành có tương xứng với giá trị mang lại không?



### 6.7. Hiểu bài

Bài toán nhóm lựa chọn là khó khăn trong việc quản lý và giám sát chất lượng cây trồng tại nhiều hộ sản xuất thuộc HTX. Quy trình cần bắt đầu từ việc thiết lập tiêu chuẩn, tạo baseline và thu thập hình ảnh, nhật ký canh tác theo chu kỳ. Các metric chính gồm thời gian tổng hợp báo cáo, tỷ lệ hộ hoàn thành ghi nhận, chất lượng ảnh và hiệu năng phân loại bất thường của AI. Phạm vi MVP được giới hạn ở một HTX, một loại cây và khoảng 10–20 hộ trong 8 tuần. Computer Vision chỉ hỗ trợ phân tích hình ảnh và phát hiện dấu hiệu bất thường, trong khi Rule Engine đối chiếu checklist và cán bộ kỹ thuật xác nhận kết quả. Nhóm lựa chọn giải pháp Workflow kết hợp AI hỗ trợ nông dân HTX ra quyết định. Sau giai đoạn thử nghiệm, nhóm sẽ quyết định mở rộng, điều chỉnh hoặc dừng dựa trên hiệu quả thực tế và khả năng khách hàng trả phí.

---

## 7. Tài liệu tham khảo

1. Plantix – Crop diagnosis and plant disease identification: https://plantix.net/
2. mobiAgri – Giải pháp nông nghiệp số: https://mobiagri.vn/
3. NextFarm – Giải pháp quản lý trang trại: https://nextfarm.vn/
4. Agrio – AI crop monitoring: https://agrio.app/
5. TCVN 11892-1:2026 – VietGAP trồng trọt. Cần đối chiếu văn bản tiêu chuẩn chính thức trước khi sử dụng làm căn cứ pháp lý.
6. Hệ thống truy xuất nguồn gốc nông sản Việt Nam: https://truyxuat.gov.vn/
7. Tài liệu nghiên cứu về chuyển đổi số trong hợp tác xã nông nghiệp Việt Nam.
8. Các kết quả phỏng vấn HTX, cán bộ kỹ thuật và hộ nông dân: [Bổ sung sau khi khảo sát].
9. Các tài liệu và dữ liệu thực địa do nhóm thu thập: [Bổ sung].
