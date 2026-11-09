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

### Idea sau phản biện: Trợ lý chăm sóc Thanh Long đạt chuẩn xuất khẩu (cập nhật sau CP3–CP4)

> Bản chi tiết idea của tôi sau khi nhận phản biện và sau khi nhóm chốt bài Thanh Long. Nguyên tắc: **problem trước, giải pháp sau**. LLM, RAG, embedding là công cụ có sẵn để tận dụng, không tự xây model. Mọi con số chưa có nguồn đều là **giả định cần kiểm**.

**Idea trong 1 câu:** một trợ lý trên Zalo do HTX vận hành, làm 3 việc: (1) trả lời câu hỏi chăm sóc Thanh Long theo đúng quy trình kỹ thuật của HTX; (2) trả lời "thuốc này có được dùng không, pha liều bao nhiêu, cách ly mấy ngày" theo danh mục thuốc BVTV của Việt Nam và mức dư lượng tối đa (MRL) của thị trường xuất khẩu; (3) gửi tin nhắc chăm sóc theo giai đoạn cây cho từng nhóm hộ (tuyên truyền). Mọi câu trả lời về thuốc đều kèm nguồn. Câu nào không có nguồn thì chuyển cho cán bộ kỹ thuật.

**Idea đã thay đổi qua 3 bản**

| | Bản 1: lúc pitch (Card #1) | Bản 2: thu hẹp lần 1 | Bản 3: hiện tại |
|---|---|---|---|
| Phạm vi | Mọi loại cây, mọi dữ liệu sản xuất của HTX | Thanh Long, 1 HTX, thị trường Úc | Thanh Long, 1 HTX, thị trường Úc |
| Người dùng chính | Giám đốc HTX, cán bộ kỹ thuật | Cán bộ kỹ thuật | Nông dân thành viên HTX (cán bộ kỹ thuật duyệt) |
| Thời điểm can thiệp | Sau khi có dữ liệu, lúc lập báo cáo | **Sau khi phun**: kiểm nhật ký trước thu hoạch | **Trước khi phun**: lúc nông dân chọn thuốc và pha liều |
| Vai trò AI | CV nhận diện bệnh, báo cáo tự động | Đọc ảnh nhật ký viết tay | RAG trích xuất quy định + trả lời có nguồn; con số lấy từ bảng đã duyệt |

**Vì sao đổi từ bản 2 sang bản 3:** kiểm nhật ký sau khi phun chỉ *phát hiện* vi phạm khi thuốc đã phun, không rút lại được, và hộ đó bị loại khỏi lô. Chặn ở thời điểm nông dân chọn thuốc thì rẻ hơn và đúng với gốc của vấn đề hơn (giả định: nông dân dùng sai vì *không biết* quy định, không phải cố tình). Candidate của nhóm cũng có vế "thiếu hướng dẫn chăm sóc".

#### 1. Persona

**Người dùng chính:** hộ nông dân thành viên của **một HTX Thanh Long đã có mã số vùng trồng xuất khẩu**. Đặc điểm (giả định, cần kiểm khi phỏng vấn):

- Tự quyết định mua và phun thuốc, thường theo tư vấn của đại lý thuốc, hàng xóm hoặc nhóm Zalo.
- Dùng Zalo hằng ngày; không đọc văn bản pháp luật, không biết MRL của thị trường nhập khẩu là gì.
- Bán trái qua HTX vào lô xuất khẩu; nếu bị loại thì phải bán nội địa giá thấp hơn.

**Người dùng phụ, đồng thời là người duyệt:** cán bộ kỹ thuật HTX, người đang phải phổ biến quy trình và trả lời câu hỏi của các hộ.

**Không nhắm tới:** nông dân trồng bán nội địa, nông dân ngoài HTX, các loại cây khác.

#### 2. Problem (chưa nói giải pháp)

**Job Story (nông dân):** Khi chuẩn bị phun thuốc cho vườn Thanh Long đang nuôi trái bán xuất khẩu, tôi muốn biết chắc thuốc này có được dùng cho thị trường đó không, pha liều bao nhiêu và phải cách ly bao nhiêu ngày trước khi hái, để trái của tôi không bị loại khỏi lô xuất.

**Job Story (cán bộ kỹ thuật):** Khi bước vào giai đoạn chăm sóc mới hoặc có quy định mới, tôi muốn phổ biến đúng và đủ cho mọi hộ và trả lời được các câu hỏi lặp lại, để không hộ nào dùng sai thuốc chỉ vì không biết.

**Quy trình hiện tại** (thời gian là giả định, đo ở tuần 1–2 pilot):

| Bước | Actor | Việc | Thời gian / tần suất |
|---:|---|---|---|
| 1 | Nông dân | Thấy sâu bệnh hoặc đến lịch phun | Nhiều lần mỗi vụ |
| 2 | Nông dân | Hỏi đại lý thuốc, hàng xóm, nhóm Zalo | Vài phút đến vài giờ |
| 3 | Nông dân → cán bộ | (Đôi khi) nhắn hỏi cán bộ HTX rồi chờ | **Vài giờ đến 1 ngày (chưa đo)** |
| 4 | Cán bộ | Tra tên thương mại ra hoạt chất, tra danh mục thuốc được phép, nhãn thuốc (liều, cách ly), MRL thị trường | **Chưa đo; tài liệu dài, rải rác** |
| 5 | Cán bộ | Trả lời từng người, cùng một câu hỏi lặp lại nhiều lần | Chưa đo |
| 6 | Nông dân | Pha thuốc, phun, ghi sổ (hoặc không ghi) | — |
| song song | Cán bộ | Tuyên truyền: họp HTX, phát tờ hướng dẫn theo mùa | Vài lần mỗi vụ; không theo từng hộ, tờ cũ vẫn lưu hành khi quy định đổi |

**Bottleneck:** bước 3–4. Nông dân phải quyết định *ngay*, cán bộ tra và trả lời không kịp. Vì vậy quyết định thực tế dựa vào đại lý, mà đại lý là người bán thuốc nên có xung đột lợi ích.

**Problem Statement (bản của tôi)**

| Trường | Nội dung |
|---|---|
| **Actor** | Nông dân thành viên 1 HTX Thanh Long xuất khẩu (người hỏi); cán bộ kỹ thuật HTX (người trả lời, người duyệt) |
| **Quy trình** | Chọn thuốc → hỏi → tra quy định → pha liều → phun → cách ly → thu hoạch vào lô xuất |
| **Bottleneck** | Tra và trả lời "thuốc nào được dùng, liều bao nhiêu, cách ly mấy ngày" cho thị trường xuất khẩu, tại thời điểm nông dân cần quyết định |
| **Impact** | Hộ dùng thuốc không được phép hoặc không đủ thời gian cách ly → trái bị loại khỏi lô, lô có thể bị trả, HTX có thể bị cảnh báo mã vùng trồng. Mức thiệt hại: **cần số liệu thật** |
| **Success Metric** | Tỷ lệ lần phun đúng quy định (xem mục 10): baseline đo bằng audit sổ nhật ký tuần 1–2 → target ≥ 95% và 0 lần dùng chất cấm |
| **Boundary** | AI không chẩn đoán bệnh, không tự đưa ra con số liều hay thời gian cách ly ngoài bảng đã duyệt, không trả lời khi không có nguồn (xem mục 11) |

#### 3. How Might We

| # | Chúng ta có thể dùng AI để… không? | Dùng ở đâu |
|---:|---|---|
| 1 | …trả lời ngay câu hỏi "thuốc này dùng được không, liều bao nhiêu, cách ly mấy ngày" từ đúng văn bản quy định, có trích nguồn | Bước 3–4, thay cho việc chờ cán bộ tra |
| 2 | …trích xuất văn bản quy định dài (Thông tư, nhãn thuốc, bảng MRL) thành bảng có cấu trúc để cán bộ duyệt | Khâu chuẩn bị dữ liệu, chạy trước, không chạy lúc nông dân hỏi |
| 3 | …soạn tin tuyên truyền theo giai đoạn cây (ra hoa, nuôi trái, trước thu hoạch) cho từng nhóm hộ | Lịch nhắc chăm sóc; cán bộ duyệt trước khi gửi |

**Không dùng AI ở:** kết luận thuốc có được phép hay không và các con số liều, thời gian cách ly (lấy từ bảng đã duyệt bằng Rule); chẩn đoán bệnh.

#### 4. Cách hoạt động: 2 kho tri thức, 1 bảng đã duyệt

| Kho | Nguồn | AI làm gì | Ai kiểm |
|---|---|---|---|
| **A. Quy trình chăm sóc** | Quy trình kỹ thuật Thanh Long mà HTX đang áp dụng, tài liệu khuyến nông, VietGAP | RAG: tìm đoạn liên quan và trả lời câu hỏi chăm sóc (bón phân, tỉa cành, xử lý ra hoa, bao trái…), có trích đoạn nguồn | Cán bộ chọn tài liệu nào được đưa vào kho |
| **B. Quy định thuốc** | Danh mục thuốc BVTV được phép sử dụng tại Việt Nam (Thông tư 75/2025/TT-BNNMT, sửa đổi bởi Thông tư 28/2026/TT-BNNMT); nhãn thuốc đã đăng ký (liều, thời gian cách ly); MRL của Úc (Schedule 20, Food Standards Code) | RAG trích xuất thành bảng: tên thương mại, hoạt chất, có đăng ký cho Thanh Long không, liều, thời gian cách ly, MRL Úc, nguồn, ngày cập nhật | **Cán bộ duyệt từng dòng** trước khi bảng được dùng |

Khi nông dân hỏi về thuốc: tra bảng đã duyệt (Rule), LLM chỉ diễn đạt lại cho dễ hiểu và gắn nguồn. Không có trong bảng thì trả lời "chưa có thông tin đã kiểm, đã chuyển cán bộ".

Một rule quan trọng: theo Food Standards Code của Úc, nếu không có MRL cho hoạt chất đó trên loại thực phẩm đó thì không được bán khi phát hiện dư lượng. Vì vậy **hoạt chất không có MRL cho Thanh Long trong Schedule 20 thì mặc định "không dùng cho lô xuất Úc"**.

**Quy trình tương lai**

```text
Nông dân nhắn câu hỏi trên Zalo
        |
        v
[AI] Hiểu câu hỏi, phân loại: chăm sóc / thuốc / ngoài phạm vi
        |
        +-- chăm sóc ----> [AI] RAG kho A -> trả lời + trích đoạn nguồn
        |
        +-- thuốc -------> [Rule] tra bảng đã duyệt (kho B)
        |                     |-- có    -> [AI] diễn đạt lại + nguồn + ngày cập nhật
        |                     |-- không -> chuyển cán bộ
        |
        +-- ngoài phạm vi / chẩn đoán bệnh / AI không chắc --> [Người] cán bộ kỹ thuật trả lời

Song song:
[AI] trích xuất văn bản mới -> [Người] cán bộ duyệt từng dòng -> cập nhật bảng (kho B)
[AI] soạn tin nhắc theo giai đoạn cây -> [Người] cán bộ duyệt -> gửi cho nhóm hộ

Phương án quay về: tắt tự trả lời câu về thuốc, quay về cán bộ trả lời trên Zalo
+ bảng tra in sẵn từ kho B (bảng vẫn dùng được khi không có AI).
```

#### 5. Mức can thiệp: gọi là "trợ lý AI" nhưng kiến trúc là Workflow

| Mức | Phương án cho idea này | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** | Cán bộ làm bảng tra in sẵn, họp HTX, trả lời Zalo | Ít thuốc, nông dân chịu tra bảng | Bảng lỗi thời; nông dân không tra; cán bộ quá tải | Giữ làm phương án quay về |
| **Rule** | Chatbot menu: chọn tên thuốc → trả về từ bảng | Nông dân gõ đúng tên thương mại | Không hiểu câu hỏi tự nhiên, viết tắt, sai chính tả; không trả lời được câu chăm sóc | Dùng cho bước kết luận về thuốc |
| **Workflow** | Các bước cố định như sơ đồ trên: phân loại → truy xuất → tra bảng → trả lời có nguồn → không chắc thì chuyển người | Các bước đã biết trước | Trả lời sai nếu bảng sai → cán bộ duyệt bảng | **Có** |
| **Agent** | AI tự quyết bước tiếp: tự tìm web, tự khuyến nghị thuốc theo bệnh, tự gửi tin | — | Tự sinh liều, dùng nguồn chưa kiểm, khó truy trách nhiệm | Không |

- **Vì sao không chọn mức đơn giản hơn:** câu hỏi thật của nông dân là ngôn ngữ tự nhiên ("xịt con nhện đỏ bằng thuốc gì", tên thuốc viết tắt), Rule không hiểu được. Văn bản quy định dài hàng trăm trang; nếu nhập tay toàn bộ thì cán bộ không làm nổi, nên cần AI trích xuất để cán bộ chỉ phải duyệt.
- **Vì sao không lên Agent:** các bước đã biết trước, không cần AI tự lên kế hoạch. Cho AI tự quyết trong bài có rủi ro hóa chất là thêm rủi ro mà không thêm giá trị.

#### 6. Stakeholder map: 5 vai trò quanh hệ thống

| Vai trò | Ai | Họ cần gì / sợ gì |
|---|---|---|
| **Ai dùng** | Nông dân: hỏi trên Zalo, nhận tin nhắc. Cán bộ kỹ thuật: dùng để trả lời nhanh và soạn tin tuyên truyền | Nông dân cần câu trả lời ngắn, nhanh, dễ hiểu, không phải cài app. Cán bộ cần giảm số câu hỏi lặp lại |
| **Ai duyệt output** | Cán bộ kỹ thuật HTX: duyệt bảng thuốc, duyệt tin tuyên truyền, trả lời câu được chuyển lên | Cần thấy nguồn gốc của từng dòng trong bảng; cần biết câu nào AI không chắc |
| **Ai chịu rủi ro** | Nông dân (trái bị loại, cây bị hại nếu sai liều), HTX (mất hợp đồng, bị cảnh báo mã vùng trồng), doanh nghiệp xuất khẩu (bị trả lô) | Sợ nhất là AI nói "được dùng" cho thuốc không được phép |
| **Ai approve** | Giám đốc HTX: quyết định đưa trợ lý vào quy trình, chịu trách nhiệm về nội dung HTX phát ra. Doanh nghiệp thu mua: chấp nhận đây là hướng dẫn chính thức cho vùng nguyên liệu | Trách nhiệm pháp lý với nội dung hướng dẫn |
| **Ai trả tiền** | Giả thuyết: HTX (phí dịch vụ hoặc nguồn hỗ trợ khuyến nông, chuyển đổi số) hoặc doanh nghiệp thu mua (giảm rủi ro vùng nguyên liệu). Nông dân không trả | Chưa kiểm chứng willingness-to-pay |

Hệ quả: người dùng (nông dân) khác người trả tiền (HTX, doanh nghiệp). Với nông dân, sản phẩm phải gần như không tốn công: dùng Zalo, không cài app, không nhập liệu. Với người trả tiền, giá trị phải chứng minh bằng metric "lần phun đúng quy định" và "lô đạt kiểm dư lượng".

#### 7. AI Leverage: khác biệt nằm ở đâu

| So với | Họ đã làm được | Idea này khác ở đâu |
|---|---|---|
| Hỏi thẳng ChatGPT / Gemini | Hiểu câu hỏi tự nhiên, trả lời nhanh | Không gắn với danh mục thuốc Việt Nam hiện hành, MRL Úc và quy trình của HTX; có thể bịa liều. Ở đây mọi con số lấy từ bảng đã duyệt, có nguồn và ngày cập nhật |
| Plantix | Chẩn đoán bệnh qua ảnh, gợi ý xử lý | Không xét quy định của thị trường xuất khẩu (theo research của nhóm, cần kiểm lại). Idea này không làm chẩn đoán |
| NextFarm, mobiAgri | Nhật ký điện tử, quản lý trang trại | Nông dân phải nhập liệu; không trả lời câu hỏi về quy định |
| Đại lý thuốc, nhóm Zalo | Trả lời ngay, gần gũi | Đại lý bán thuốc nên có xung đột lợi ích; thông tin không có nguồn |
| Tờ rơi, họp HTX | Chính thống | Không cá nhân hóa, lỗi thời khi quy định đổi |

- **Tận dụng có sẵn:** LLM qua API cho hiểu câu hỏi và trích xuất văn bản; embedding và vector DB có sẵn cho RAG; Zalo làm kênh. Không train model.
- **Lợi thế thật không nằm ở model** mà ở: (1) bảng quy định đã được cán bộ duyệt theo từng thị trường; (2) niềm tin vì nội dung do HTX phát ra; (3) dữ liệu câu hỏi thật của nông dân để cải thiện kho A.

#### 8. MVP scope

| Trong MVP | Ngoài MVP |
|---|---|
| 1 HTX, 10–20 hộ, 1 thị trường (Úc), 1 vụ trái (ra hoa → thu hoạch) | Nhiều cây, nhiều thị trường |
| Kho A: 1 bộ quy trình kỹ thuật HTX đang dùng | Tự động cập nhật văn bản pháp luật mới |
| Kho B: chỉ những thuốc các hộ pilot thực sự dùng (số lượng đếm ở tuần 1) | Toàn bộ danh mục thuốc BVTV |
| Kênh Zalo, chỉ nhắn chữ | App riêng, hỏi bằng giọng nói (giai đoạn 2) |
| Tin nhắc theo giai đoạn cây, cán bộ duyệt trước khi gửi | Chẩn đoán bệnh qua ảnh (dùng công cụ có sẵn nếu cần), bán thuốc, đặt hàng |

**Lộ trình 8 tuần**

1. **Tuần 1–2 (baseline, chưa có AI):** đếm số câu hỏi cán bộ nhận mỗi tuần, đo thời gian trả lời; audit sổ nhật ký 1 tháng gần nhất của các hộ pilot; thu 50 câu hỏi thật làm bộ eval; AI trích xuất kho B, cán bộ duyệt từng dòng.
2. **Tuần 3:** chạy eval offline trên 50 câu. Không đạt tiêu chí ở mục 10 thì sửa kho hoặc dừng.
3. **Tuần 4–5 (shadow mode):** AI soạn câu trả lời, cán bộ duyệt rồi mới gửi. Đo tỷ lệ cán bộ phải sửa.
4. **Tuần 6–8:** tự trả lời câu chăm sóc và câu về thuốc có trong bảng; câu ngoài bảng vẫn qua cán bộ. Audit sổ nhật ký lần 2, so với baseline.

#### 9. Chi phí vận hành (công thức, chưa có số thật)

- **Chi phí AI mỗi tháng** ≈ số hộ × số câu hỏi/hộ/tháng × chi phí mỗi câu (token vào + token ra × giá model), cộng chi phí trích xuất lại kho B mỗi khi có văn bản mới.
- **Chi phí người:** giờ cán bộ duyệt bảng và duyệt tin tuyên truyền. Dự đoán đây mới là chi phí lớn nhất, lớn hơn chi phí AI. Cần đo ở tuần 1–2.
- **Hạ tầng:** Zalo OA, server nhỏ, vector DB.
- Tính lại cho 3 mức: 20 hộ (pilot), 200 hộ (cả HTX), 2.000 hộ (nhiều HTX), để xem chi phí mỗi hộ có giảm khi mở rộng không.

#### 10. Metric

| Loại | Metric | Baseline | Target | Cách đo |
|---|---|---|---|---|
| **Truth metric** | % lần phun (theo sổ nhật ký hộ pilot) dùng thuốc được phép cho thị trường Úc, đúng liều, đủ thời gian cách ly | Audit tuần 1–2 | ≥ 95%; 0 lần dùng chất cấm | Cán bộ audit sổ mỗi 2 tuần |
| Kết quả trễ | Lô của hộ pilot đạt kiểm dư lượng | Kết quả vụ trước (nếu HTX có) | Không lô nào bị loại vì dư lượng | Kết quả kiểm của doanh nghiệp |
| Chất lượng AI (thuốc) | Con số liều, thời gian cách ly trong câu trả lời khớp bảng đã duyệt | — | **100%**; sai 1 con số là không đạt | Bộ eval 50 câu hỏi thật |
| Chất lượng AI (nguồn) | % câu trả lời về thuốc có ghi nguồn và ngày cập nhật | — | 100% | Bộ eval |
| An toàn | % câu ngoài phạm vi / không có nguồn được chuyển cán bộ thay vì tự trả lời | — | ≥ 95% | Bộ eval có câu "bẫy" |
| Chất lượng AI (chăm sóc) | % câu trả lời chăm sóc được cán bộ chấm đúng | — | ≥ 85% | Cán bộ chấm trong shadow mode |
| Tốc độ | Thời gian từ lúc hỏi đến lúc có câu trả lời | Đo tuần 1–2 | Dưới 2 phút với câu AI trả lời; dưới 24 giờ với câu chuyển cán bộ | Log Zalo |
| Tải cán bộ | Số câu cán bộ phải tự trả lời mỗi tuần | Đo tuần 1–2 | Giảm ≥ 50% | Log |
| Adoption | % hộ hỏi ít nhất 1 lần trong 2 tuần | — | ≥ 60% | Log |
| Trả tiền | HTX hoặc doanh nghiệp đồng ý trả, hoặc làm tiếp sau pilot | — | Ít nhất 1 cam kết | Biên bản sau pilot |

**Ngưỡng dừng:**
- Sau 4 tuần mà dưới 30% hộ dùng → dừng, quay về bảng tra in sẵn + cán bộ trả lời Zalo.
- Chỉ cần 1 câu trả lời sai liều hoặc sai thời gian cách ly đến tay nông dân → tắt tự trả lời câu về thuốc, quay lại shadow mode.

#### 11. Boundary

- **AI không được:** chẩn đoán bệnh; khuyến nghị thuốc ngoài bảng đã duyệt; tự đưa ra con số liều hoặc thời gian cách ly; trả lời khi không tìm thấy nguồn; trả lời cho cây khác hoặc thị trường khác.
- **Khi nào cần con người (HITL):** cán bộ duyệt từng dòng bảng thuốc trước khi phát hành; duyệt mọi tin tuyên truyền trước khi gửi; trả lời mọi câu được chuyển lên. Khi có văn bản quy định mới, các dòng liên quan bị khóa cho tới khi duyệt lại.
- **Báo nhầm hay bỏ sót tệ hơn:** bỏ sót tệ hơn, tức là nói "được dùng" cho thuốc không được phép. Vì vậy khi không chắc, mặc định trả lời "chưa xác nhận, hỏi cán bộ".

#### 12. Giả định chưa kiểm (phải hỏi người thật, không hỏi AI)

| # | Giả định | Nếu sai thì sao |
|---:|---|---|
| 1 | Nông dân chọn thuốc chủ yếu theo đại lý hoặc hàng xóm, không theo danh mục của thị trường | Bottleneck không nằm ở thông tin → quay lại bản 2 (kiểm nhật ký) |
| 2 | Có lô hoặc hộ bị loại vì dư lượng, chất cấm | Impact nhỏ → Not Yet |
| 3 | Nông dân sẽ nhắn hỏi trước khi phun | Chuyển trọng tâm sang tin nhắc chủ động |
| 4 | Cán bộ nhận nhiều câu hỏi lặp lại | Giá trị với HTX thấp |
| 5 | HTX có quy trình kỹ thuật bằng văn bản để làm kho A | Phải soạn quy trình trước, tăng chi phí |
| 6 | HTX hoặc doanh nghiệp sẵn sàng trả tiền | Không có mô hình thu tiền → No-Go về thương mại |

**Câu hỏi phỏng vấn (Mom Test):**
- Nông dân: "Lần phun thuốc gần nhất, anh/chị chọn thuốc đó thế nào, hỏi ai?"; "Lần gần nhất có trái bị HTX loại khỏi lô là khi nào, vì sao?"
- Cán bộ: "Tuần trước anh/chị nhận bao nhiêu câu hỏi về thuốc, trả lời mỗi câu mất bao lâu?"; "Lần gần nhất có quy định thuốc thay đổi, anh/chị phổ biến cho các hộ thế nào?"

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch Card #1: HTX khó theo dõi và tổng hợp tình trạng cây trồng của nhiều hộ theo chu kỳ. Actor: giám đốc HTX, cán bộ kỹ thuật. Bottleneck: gom dữ liệu rải rác ở sổ, Excel, Zalo. Câu hỏi tôi đưa nhóm phản biện: "HTX đã dùng Excel, Zalo thì sản phẩm khác biệt ở đâu để họ chịu chuyển?" | Card được nhóm chọn làm nền, sau đó gộp với ý Vision/RAG của Hiếu và thu hẹp vào Thanh Long xuất khẩu. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:<br>1. **Quang (tóm tắt slide thành đề cương ôn thi):** "NotebookLM đã tóm tắt được PDF rồi, ý tưởng của bạn làm được gì tốt hơn?"<br>2. **Thành (tổng hợp, phân tích chi tiêu cá nhân):** "Có thật sự cần AI không hay Rule là đủ? Đã có app nào làm chưa? Mình có tính năng gì hơn họ? Vì sao người dùng phải trả tiền cho tính năng này?"<br>3. **Hiếu (bot đọc log lỗi giúp intern setup Docker/CycleGAN, lỗi khó thì đẩy ticket lên senior):** "Sản phẩm này bán cho ai? Vì sao công ty công nghệ không tự build? Tự build có khó không?" | 1. Quang thừa nhận khoảng trống so với NotebookLM chưa đủ rõ; ý bị loại ở CP3.<br>2. Thành đồng ý Rule là đủ cho bài chi tiêu, chuyển sang card #2 (so sánh thông tin trước khi mua); ý này sau đó bị loại vì rào cản crawl dữ liệu và API của các sàn.<br>3. Hiếu thu hẹp định vị từ "giải pháp nội bộ cho cả công ty" xuống "trợ lý cho từng dự án". Ý này có điểm cao nhất (33) nhưng nhóm không chọn vì impact nhỏ hơn bài Thanh Long. |
| Nhận phản biện | Câu hỏi tôi nhận được:<br>1. **Quang:** nông dân kén công nghệ, lười nhập liệu; ảnh chụp rung, thiếu sáng; scope quá rộng nếu làm cho mọi loại cây.<br>2. **Hiếu:** scope tư vấn luật xuất khẩu quá lớn, phủ mọi loại cây, làm sao bảo đảm RAG trả lời đúng? (Hiếu đề xuất thêm chụp ảnh phân tích bệnh.)<br>3. **Cả nhóm:** AI có thật sự cần không? Thị trường Việt Nam và quốc tế đã có sản phẩm nào chưa? | Tôi đã sửa (chi tiết ở mục 3, "Idea sau phản biện"):<br>- Thu hẹp còn 1 cây (Thanh Long), 1 thị trường (Úc), 1 HTX 10–20 hộ.<br>- Với "lười nhập liệu": nông dân không phải nhập liệu, chỉ nhắn hỏi trên Zalo đang dùng hằng ngày; không phải cài app.<br>- Với "RAG có đúng không": RAG chỉ dùng để trích xuất văn bản và tìm đoạn nguồn; con số liều, thời gian cách ly lấy từ bảng đã được cán bộ duyệt từng dòng; câu không có nguồn thì chuyển cán bộ.<br>- Với ý chụp ảnh bệnh của Hiếu: để ngoài MVP vì Plantix đã làm; idea của tôi tập trung vào bước nông dân chọn thuốc.<br>- Với "đã có sản phẩm chưa": research Plantix, NextFarm, mobiAgri, Agrio, thấy chưa ai trả lời câu hỏi thuốc theo quy định thị trường xuất khẩu (cần kiểm thêm). |
| Gom cluster / cây OST | Cùng nhóm gom candidate thành 3 cụm: A. Công cụ cá nhân / học tập (tóm tắt slide, chi tiêu, so sánh mua hàng); B. Công cụ nội bộ / DevOps (bot intern); C. B2B / Agritech (giám sát vùng trồng). Outcome chung: giảm tỷ lệ lô Thanh Long bị trả về do lỗi chất lượng và dư lượng hóa chất. Trong cụm C, tôi tách các vấn đề của mình thành quản lý dữ liệu, giám sát cây trồng, kiểm tra chất lượng và báo cáo. | Thấy rõ cụm A đã có công cụ lớn (NotebookLM, sàn TMĐT), cụm B quy mô hẹp, cụm C có impact kinh tế lớn nhất. |
| Chọn candidate problem | Cùng nhóm chấm shortlist: Agritech 32 điểm, bot intern 33 điểm. Tôi ủng hộ Agritech vì impact: một lô bị trả là thiệt hại cả lô hàng, còn bot intern chỉ tiết kiệm thời gian của mentor. | Nhóm chốt bài Thanh Long xuất khẩu cho HTX, gộp Workflow của tôi với ý Vision/RAG của Hiếu. |
| Kiểm chứng / research | Hỗ trợ Quang làm bảng research: tìm hiểu Plantix, mobiAgri, NextFarm, Agrio; tìm hiểu tiêu chuẩn VietGAP và khả năng ứng dụng CV. | Nhận thấy không nên cạnh tranh bằng chức năng nhận diện bệnh cây đơn thuần. |
| Quy trình nhóm (người chính CP5, quy trình trước/sau) | Đề xuất quy trình end-to-end: thiết lập tiêu chuẩn → tạo baseline → thu thập dữ liệu theo chu kỳ → phân tích → cán bộ xác nhận → báo cáo, tổng hợp từ quy định nhà nước xuống đến từng hộ. Phụ trách chính phần quy trình hiện tại / tương lai: chỉ ra bottleneck ở bước nông dân hỏi và cán bộ tra quy định thuốc; quy trình tương lai tách rõ bước AI, Rule, con người và phương án quay về (xem mục 3, phần 2 và 4). | Làm khung cho mục 4 (quy trình trước/sau) trong báo cáo nhóm. |
| Problem Statement | Xác định khó khăn trong thu thập, quản lý và đối chiếu dữ liệu chất lượng cây trồng giữa nhiều hộ. Sau phản biện, thu về một bottleneck: lúc nông dân chọn thuốc, không biết thuốc nào được dùng cho thị trường xuất khẩu, liều bao nhiêu, cách ly mấy ngày, và cán bộ tra trả lời không kịp. Chuyển từ kiểm sau khi phun sang hướng dẫn trước khi phun. | Problem Statement có một bước nghẽn cụ thể và truth metric đo được (% lần phun đúng quy định). |
| Mức can thiệp AI | Đề xuất Workflow (không phải Agent): RAG trả lời câu chăm sóc và trích xuất quy định thuốc; Rule tra bảng đã duyệt cho con số liều, thời gian cách ly; cán bộ kỹ thuật duyệt bảng, duyệt tin tuyên truyền và nhận câu AI không chắc. | Giới hạn vai trò AI, giữ con số và quyết định cuối cùng cho bảng đã duyệt và cán bộ kỹ thuật. |
| Quyết định | Đề xuất MVP 1 HTX, 1 loại cây, 10–20 hộ, thử nghiệm 8 tuần, có 2 tuần đo baseline và 2 tuần shadow mode. Đề xuất thêm ngưỡng dừng: chỉ cần 1 câu trả lời sai liều đến tay nông dân thì tắt tự trả lời câu về thuốc. | Nhóm chốt Go với pilot 1 HTX, 10 hộ, thị trường Úc, 8 tuần; dừng nếu sau 4 tuần tỷ lệ nông dân dùng dưới 30%. |

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
| Sau lab: tinh gọn idea (mục 3, mục 4) | Dùng Claude Code đối chiếu báo cáo của tôi với báo cáo của 3 bạn để ghi đúng ai hỏi gì; trình bày chi tiết idea trợ lý chăm sóc Thanh Long theo khung Persona / Problem / AI Leverage / MVP / Metric / Stakeholder map; tìm nguồn văn bản quy định thuốc. | Chỉ ra RAG không nên tự sinh con số liều, thời gian cách ly mà phải lấy từ bảng đã duyệt; tìm được Thông tư 75/2025/TT-BNNMT và Schedule 20 của Úc. | *(Huy tự điền)* | *(Huy tự điền)* |

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
5. TCVN 11892-1 – VietGAP trồng trọt. Cần kiểm lại năm ban hành (bản tôi biết là 11892-1:2017) trên văn bản chính thức trước khi dùng làm căn cứ.
6. Hệ thống truy xuất nguồn gốc nông sản Việt Nam: https://truyxuat.gov.vn/
7. Tài liệu nghiên cứu về chuyển đổi số trong hợp tác xã nông nghiệp Việt Nam.
8. Các kết quả phỏng vấn HTX, cán bộ kỹ thuật và hộ nông dân: [Bổ sung sau khi khảo sát].
9. Các tài liệu và dữ liệu thực địa do nhóm thu thập: [Bổ sung].
10. Thông tư 75/2025/TT-BNNMT ban hành Danh mục thuốc BVTV được phép sử dụng, cấm sử dụng tại Việt Nam (văn bản gốc): https://datafiles.chinhphu.vn/cpp/files/vbpq/2025/12/75-bnnmt.pdf
11. Thông tư 28/2026/TT-BNNMT sửa đổi, bổ sung Thông tư 75/2025/TT-BNNMT: https://thuvienphapluat.vn/van-ban/Linh-vuc-khac/Thong-tu-28-2026-TT-BNNMT-sua-doi-Thong-tu-75-2025-TT-BNNMT-713084.aspx
12. Australia New Zealand Food Standards Code, Schedule 20 – Maximum residue limits (Federal Register of Legislation): https://www.legislation.gov.au/F2015L00468
