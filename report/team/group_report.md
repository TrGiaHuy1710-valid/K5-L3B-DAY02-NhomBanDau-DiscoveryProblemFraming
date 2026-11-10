# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: NhomBanDau
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): 
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Cao Minh Quang | Khi đến mùa thi, tôi muốn tổng hợp slide thành đề cương ngắn gọn để ôn tập nhanh mà không bỏ sót kiến thức quan trọng. | Sinh viên | Đọc, lọc và tổng hợp nội dung từ nhiều slide (4–6 giờ/môn). | TranDuyThanh, TrinhGiaHuy, LeHienHieu |
| 2 | Cao Minh Quang | Khi ôn thi, tôi muốn chuyển định nghĩa và công thức thành câu hỏi tự kiểm tra để ghi nhớ kiến thức tốt hơn. | Sinh viên | Trích xuất kiến thức và xây dựng từng cặp câu hỏi–đáp án thủ công. | TranDuyThanh, TrinhGiaHuy, LeHienHieu |
| 3 | Cao Minh Quang | Khi ôn thi theo đề cương bộ môn, tôi muốn đối chiếu câu hỏi với slide để tìm đúng nội dung cần học. | Sinh viên | Tìm và đối chiếu nội dung nằm rải rác ở nhiều tuần học. | TranDuyThanh, TrinhGiaHuy, LeHienHieu |
| 4 | Trần Duy Thành | Khi quản lý chi tiêu, tôi muốn tổng hợp giao dịch từ nhiều kênh thanh toán để biết mình đã chi bao nhiêu và vào việc gì. | Người sử dụng nhiều kênh thanh toán | Thu thập và phân loại giao dịch từ nhiều nguồn khác nhau. | LeHienHieu, TrinhGiaHuy |
| 5 | Trần Duy Thành | Khi mua sản phẩm có nhiều lựa chọn, tôi muốn đối chiếu giá, thông số và chính sách để chọn phương án phù hợp. | Người mua hàng | Đọc và chuẩn hóa thông tin từ nhiều nhà bán để so sánh. | CaoMinhQuang, TrinhGiaHuy, LeHienHieu |
| 6 | Trần Duy Thành | Khi mua chung với người khác, tôi muốn đối soát và chia chi phí để mọi người thanh toán đúng phần của mình. | Người tham gia mua chung | Tổng hợp khoản chi, tính phần mỗi người và đối soát chuyển tiền. | TrinhGiaHuy |
| 7 | Trịnh Gia Huy | Khi theo dõi nhiều hộ trồng, tôi muốn tổng hợp tình trạng cây theo chu kỳ để quản lý và báo cáo kịp thời. | Cán bộ HTX | Thu thập và tổng hợp dữ liệu tình trạng cây từ nhiều hộ. | CaoMinhQuang, LeHienHieu, TranDuyThanh |
| 8 | Trịnh Gia Huy | Khi kiểm tra nhiều khu vực trồng, tôi muốn phát hiện sớm dấu hiệu bất thường để ưu tiên xử lý đúng nơi. | Cán bộ kỹ thuật nông nghiệp | Kiểm tra thủ công nhiều khu vực để nhận diện dấu hiệu bất thường. | CaoMinhQuang, LeHienHieu, TranDuyThanh |
| 9 | Trịnh Gia Huy | Khi chuẩn bị thu mua, tôi muốn có dữ liệu thống nhất về vùng nguyên liệu để đánh giá chất lượng và quyết định thu mua. | Doanh nghiệp thu mua nông sản | Thu thập và đối chiếu dữ liệu chất lượng từ nhiều nguồn thiếu thống nhất. | LeHienHieu |
| 10 | Lê Hiền Hiếu | Khi thiết kế API và chọn mô hình LLM, tôi muốn đối chiếu tài liệu kỹ thuật để chọn phương án phù hợp và tránh phải làm lại. | AI Engineer | Đọc và đối chiếu tài liệu kỹ thuật, framework và quy định (2–3 giờ). | TrinhGiaHuy, TranDuyThanh, CaoMinhQuang |
| 11 | Lê Hiền Hiếu | Khi thuê máy chủ GPU mới, tôi muốn thiết lập môi trường nhanh để bắt đầu huấn luyện mà không lặp lại thao tác cũ. | AI Engineer / ML Engineer | Cài đặt lại Docker, thư viện và cấu hình mỗi lần đổi máy chủ (2–3 lần/tuần). | CaoMinhQuang, TranDuyThanh |
| 12 | Lê Hiền Hiếu | Khi hỗ trợ nhân sự mới, tôi muốn giảm số lần gián đoạn để duy trì công việc chuyên sâu mà người mới vẫn xử lý được lỗi. | Mentor / Kỹ sư kỹ thuật | Phải dừng công việc để hướng dẫn setup và xử lý lỗi CycleGAN (4–5 lần/ngày khi có người mới). | TrinhGiaHuy, TranDuyThanh, CaoMinhQuang |

Sau khi thảo luận 12 Candidates trên chúng tôi quyết định rút gọn thành 4 Candidates mà mỗi người cảm thấy tự tin nhất để bàn bạc sâu hơn. Trong đó ý tưởng #7 của Trịnh Gia Huy được chúng tôi đặt một sự quan tâm cao hơn, phản biện nhiều hơn và điều chỉnh phạm vi, đối tượng, chức năng của ý tưởng đó thành một ý tưởng AI hoàn chỉnh hơn.

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| Tổng hợp và kiểm chứng thông tin (A) |Ôn thi, so sánh sản phẩm, chăm sóc thanh long |Thông tin phân tán, khó tổng hợp và kiểm chứng độ chính xác |
| Hỗ trợ ra quyết định chuyên môn (B) |Chăm sóc thanh long, xử lý lỗi kỹ thuật |Người ít kinh nghiệm phải phụ thuộc và người có chuyên môn |
| Giảm thời gian thao tác thủ công (C) |Cả 4 candidate |Mất thời gian tra cứu, đối chiếu và xử lý thông tin |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian và sai sót khi tìm kiếm, tổng hợp và kiểm chứng thông tin phục vụ học tập, công việc và ra quyết định
├── Opportunity A: Cần gom nối và xác thực nhanh các thông tin bị phân tán rải rác ở nhiều nguồn khác nhau để có bức tranh tổng thể chính xác.
├── Opportunity B: Cần sự cố vấn, hướng dẫn chuyên sâu tức thời cho người thiếu kinh nghiệm mà không bị phụ thuộc hay phải chờ đợi chuyên gia/người hướng dẫn.
└── Opportunity C: Cần cắt giảm các thao tác thủ công nhàm chán, lặp đi lặp lại tốn hàng giờ đồng hồ mỗi ngày.
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:
- Sinh viên cần một "công cụ AI tóm tắt" slide bài giảng thành đề cương.
- Hợp tác xã nông nghiệp cần "hệ thống RAG thời gian thực" cập nhật luật xuất khẩu.

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
|Cao Minh Quang — Tóm tắt slide thành đề cương ôn thi|5 |5 |4 |5 |4 |5 |4 |32/35 |
|Trần Duy Thành — Đối chiếu thông tin trước khi mua hàng |5 |5 |3 |4 |1 |5 |4 |27/35 |
|Trịnh Gia Huy — Tra cứu kiến thức chăm sóc thanh long và quy định sử dụng thuốc, hóa chất |4 |3 |3 |3 |4 |5 |2 |24/35 |
|Lê Hiền Hiếu — Giảm phụ thuộc mentor khi intern xử lý lỗi môi trường |5 |3 |3 |4 |2 |5 |4 |26/35 |

**Candidate được chọn:** Trịnh Gia Huy — Tra cứu kiến thức chăm sóc thanh long và quy định sử dụng thuốc, hóa chất

**Vì sao chọn:** Mặc dù có tổng điểm thấp nhất, điểm trừ chủ yếu nằm ở việc nhóm chưa có sẵn kiến thức chuyên ngành và quy trình ban đầu chưa được định hình rõ, nhưng bài toán này có lợi thế độc quyền rất mạnh: thị trường chưa có công cụ RAG kiểm tra chéo luật hóa chất xuất khẩu. Những điểm yếu về Quy trình và Hiểu domain hoàn toàn có thể bù đắp được thông qua bước Research (CP4) và Thiết kế Workflow (CP5). Bài toán có tính thực tiễn cao, giải quyết nỗi đau thiệt hại kinh tế lớn và tạo ra một MVP rất trực quan khi kết hợp RAG và Vision.

**Vì sao loại các candidate còn lại:**
- Cao Minh Quang (Tóm tắt slide): Điểm số cao nhất vì bài toán quá gần gũi với sinh viên, nhưng bị loại do hoàn toàn không có tính mới. Các công cụ như Google NotebookLM hay ChatGPT hiện tại đã giải quyết quá xuất sắc việc đọc và tóm tắt PDF. Nếu làm nhóm dễ rơi vào tình trạng không tạo ra được giá trị cạnh tranh nào.
- Trần Duy Thành (Đối chiếu mua sắm online): Bị loại vì nhóm nhận định đây là một ý tưởng có rào cản công nghệ khá lớn. Rào cản kỹ thuật chủ yếu nằm ở các sàn TMĐT (Shopee, Lazada, Tiki) đều có cơ chế chặn crawler và đóng API. Ngoài ra nhóm chưa có kinh nghiệm xử lý API của Facebook Market hay Tiktok Shop và các trang tương tự.
- Lê Hiền Hiếu (Giảm phụ thuộc mentor): Bị loại do nhóm thấy đây là một dự án khá phức tạp. Rào cản lớn nhất nằm ở tính bảo mật dữ liệu của doanh nghiệp và sự khó khăn trong việc thu thập đủ dataset để xây dựng hệ thống RAG chuẩn xác. Ngoài ra, tệp người dùng quá ngách, khó có khả năng upscale và thương mại hóa tốt.

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

*(Phụ trách chính: Cao Minh Quang)*

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Người trồng thanh long có nhu cầu chủ động tự tra cứu và xác minh thuốc BVTV/quy định xuất khẩu trước khi phun, thay vì chỉ phụ thuộc hoàn toàn vào tư vấn của đại lý bán thuốc. | Value | 5 | 3 | Có |
| 2 | Hộ nông dân (độ tuổi trung niên, ít thành thạo công nghệ) có thể tự sử dụng một công cụ tra cứu số đơn giản (gõ tên thương mại tiếng Việt hoặc giọng nói) để hiểu đúng hoạt chất và thời gian cách ly (PHI). | Usability | 5 | 2 | Có |
| 3 | Có thể xây dựng cơ sở dữ liệu ánh xạ (mapping) chính xác giữa hàng nghìn tên thương mại thuốc BVTV lưu hành tại Việt Nam với tên hoạt chất hóa học và ngưỡng MRLs của các thị trường xuất khẩu đích. | Feasibility | 4 | 3 | Có |
| 4 | Nông dân tin tưởng thông tin khuyến cáo từ công cụ số đủ để thay đổi hành vi canh tác và lựa chọn thuốc thực tế. | Usability / Value | 4 | 2 | Có |
| 5 | HTX sẵn sàng đóng vai trò điểm tựa (hỗ trợ xác minh chuyên môn và bảo chứng vùng trồng) mà không cần can thiệp trực tiếp vào từng lượt tra cứu hàng ngày của nông dân. | Viability | 4 | 3 | Không |

*Giả định nhóm kiểm chứng trong buổi này:* Giả định 1 (Nhu cầu chủ động xác minh thông tin thuốc), Giả định 2 (Khả năng tiếp cận công nghệ của nông dân), và Giả định 3 (Tính khả thi của việc đối chiếu tên thuốc với quy chuẩn xuất khẩu).

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn sâu (In-depth Interview) kết hợp rà soát báo cáo giám sát chuyên ngành từ Cục Bảo vệ Thực vật & Văn phòng SPS Việt Nam.

#### Interview Snapshot 1

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Chú B. (52 tuổi), nông dân trực tiếp canh tác 1.5 ha thanh long ruột đỏ tại huyện Chợ Gạo, tỉnh Tiền Giang. |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Ra tiệm bảo vệ thực vật, đại lý đưa thuốc gì thì mình xịt thuốc nấy chứ bao bì toàn chữ nhỏ li ti với tên hoạt chất tiếng Tây, nông dân biết đường nào mà lần. Đến chừng HTX hay thương lái test mẫu kêu dính chất cấm xuất khẩu thì trái chín mẹ trên cây rồi, trừ tiền mình chứ trừ ai!"* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Vụ nghịch vừa rồi cây bị đốm nâu (nấm tắc kè), chú ra tiệm quen mua thuốc xịt. Đến sát ngày thu hoạch, HTX lấy mẫu xét nghiệm nhanh phát hiện dính dư lượng hoạt chất nhóm Dithiocarbamate vượt ngưỡng EU. Toàn bộ 4 tấn trái không được gom xuất khẩu, phải dạt bán chợ nội địa giá 4.000đ/kg (thay vì giá hợp đồng xuất khẩu 18.000đ/kg), lỗ gần 50 triệu đồng tiền phân thuốc. |
| Hiện đang xử lý bằng cách nào (workaround)? | Tin tưởng tuyệt đối vào đại lý bán thuốc gần nhà; thỉnh thoảng xem tờ giấy photo danh mục thuốc khuyến cáo do HTX phát từ đầu năm nhưng tờ giấy hay bị ướt, rách hoặc thất lạc. |
| Mất bao lâu, bao lần? | Mỗi vụ mất 3–4 lần đắn đo đi hỏi tiệm thuốc; mỗi đợt sâu bệnh tốn 1–2 ngày vừa mua vừa lo ngay ngáy không biết có phạm quy chuẩn xuất khẩu không. |
| Insight / opportunity rút ra | Nông dân rất sợ rủi ro rớt kiểm định bị trừ tiền, nhưng họ thiếu một phương tiện cầm tay để gõ ngay tên chai thuốc trên tay và biết tức thì: *Thuốc này thị trường xuất khẩu có cho xịt không, xịt xong cách ly mấy ngày thì được hái?* |

#### Interview Snapshot 2

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Anh T. (34 tuổi), Cán bộ kỹ thuật phụ trách kiểm soát chất lượng tại HTX Nông nghiệp Thanh Long. |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Quy định MRLs của EU, Nhật hay Hàn Quốc thay đổi xoành xoạch, có chất tháng trước cho dùng tháng này đã hạ ngưỡng xuống 0.01 mg/kg. Cán bộ HTX chỉ có 2 người mà quản lý cả trăm hộ, không thể nào ngày nào cũng chạy ra từng vườn canh nông dân pha thuốc gì vào bình."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Tháng trước EU cập nhật cảnh báo kiểm soát tăng cường theo Quy định 2019/1793 đối với thanh long Việt Nam. Cán bộ gửi thông báo PDF vào nhóm Zalo của HTX nhưng đa số xã viên lớn tuổi không mở file đọc hoặc không nhớ tên hoạt chất để đối chiếu khi đi mua thuốc ngoài tiệm. |
| Hiện đang xử lý bằng cách nào (workaround)? | Định kỳ in giấy phát cho các tổ trưởng tổ hợp tác; tổ chức các buổi tập huấn VietGAP nhưng nông dân chỉ đi dự đông đủ lúc đầu vụ rồi đâu lại vào đấy. |
| Mất bao lâu, bao lần? | Mất 2–3 ngày mỗi tháng để soạn tài liệu và trả lời từng cuộc gọi của xã viên hỏi "thuốc này thuốc kia xịt được không". |
| Insight / opportunity rút ra | Cần một công cụ để chính nông dân tự kiểm tra trước tại vườn (Farmer-first), còn HTX đóng vai trò điểm tựa xác minh chuyên môn khi có hoạt chất lạ hoặc có tranh chấp kỹ thuật (Cooperative-supported). |

#### Bảng tổng hợp kiểm chứng

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn sâu nông dân trực tiếp | 3 hộ trồng thanh long (Tiền Giang, Bình Thuận) | Cả 3 hộ đều từng gặp tình trạng hoang mang về quy định thuốc xuất khẩu, phụ thuộc hoàn toàn vào đại lý bán thuốc và từng chịu thiệt hại do hàng rớt chuẩn. | Nông dân phản đối kịch liệt nếu ứng dụng bắt tạo tài khoản rườm rà, bắt gõ văn bản dài hoặc bắt điền form nhật ký phức tạp. Họ chỉ muốn mở lên là tra cứu được ngay. |
| Phỏng vấn cán bộ HTX nông nghiệp | 2 cán bộ kỹ thuật HTX | Xác nhận HTX quá tải trong việc truyền đạt và giám sát danh mục hoạt chất MRLs xuất khẩu biến động liên tục. Rất ủng hộ việc trao công cụ tự kiểm tra cho người trồng. | HTX không muốn phần mềm can thiệp thay thế hoàn toàn vai trò của họ; các trường hợp nhạy cảm hoặc thuốc mới vẫn cần cán bộ bấm xác nhận bảo chứng. |
| Báo cáo chuyên ngành (Cục BVTV & Văn phòng SPS VN) | 5 văn bản / báo cáo giám sát 2023–2026 | Thanh long Việt Nam liên tục nằm trong danh sách kiểm soát tăng cường tại EU với tần suất kiểm tra 30–50% do vi phạm dư lượng MRLs (như Carbendazim, Dithiocarbamates, Difenoconazole). | Rào cản không nằm ở chỗ "thiếu thuốc an toàn" mà nằm ở khâu "nông dân thiếu thông tin đối chiếu giữa tên thương phẩm trên thị trường với ngưỡng MRLs của nước nhập khẩu". |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**
- **Định hình triết lý sản phẩm:** Nhất quán theo nguyên tắc **Farmer-first, Cooperative-supported**. Người nông dân là người dùng chính (Primary User) trực tiếp nhận thông tin cảnh báo thuốc; HTX là bên hỗ trợ (Supporting Stakeholder) bảo chứng nguồn dữ liệu và giải quyết ngoại lệ.
- **Thu hẹp phạm vi giải pháp (tránh bẫy công nghệ):** Tuyệt đối không sa đà vào các bài toán phức tạp ngoài luồng (như Computer Vision bắt bệnh tự động, drone phun thuốc, dự báo sản lượng) theo đúng Dependency A; giải quyết chính xác nút thắt: **Hỗ trợ người trồng tiếp cận, tra cứu và xác minh tính hợp chuẩn của thuốc BVTV đối với thị trường xuất khẩu**.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Ứng dụng "Thuốc BVTV"** (Cục Bảo vệ Thực vật — Bộ NN&PTNT) | https://ppd.gov.vn | Tra cứu danh mục thuốc bảo vệ thực vật lưu hành trong nước. | - Dữ liệu chính thống quốc gia, pháp lý tuyệt đối.<br>- Tra cứu theo tên thương mại, hoạt chất, đối tượng phòng trừ trên cây trồng. | - **Hoàn toàn không có dữ liệu MRLs xuất khẩu** (EU, Úc, Nhật, v.v.).<br>- Giao diện dạng biểu mẫu hành chính, thuật ngữ kỹ thuật khó hiểu với nông dân.<br>- Không có tính năng cảnh báo đèn xanh/đỏ theo từng thị trường mục tiêu. | Cần kế thừa cơ sở dữ liệu mapping Tên thương mại $\rightarrow$ Hoạt chất của Cục BVTV, nhưng phải bổ sung lớp đối chiếu MRLs quốc tế và thiết kế UX đơn giản hóa cho nông dân. |
| **Nền tảng Nông nghiệp số mobiAgri** (MobiFone & Weatherplus) | https://mobiagri.vn | Nhận diện sâu bệnh qua ảnh và khuyến nghị giải pháp điều trị. | - Ứng dụng AI nhận diện cây trồng và sâu bệnh trên di động.<br>- Có chuyên mục hỏi đáp chuyên gia và theo dõi thời tiết nông vụ. | - Mang tính đại trà cho nhiều loại cây, không chuyên sâu ngách Thanh Long xuất khẩu.<br>- Thuốc gợi ý chỉ dựa trên phòng trừ sâu bệnh thông thường, **không rà soát rào cản MRLs xuất khẩu** (nông dân mua theo vẫn có nguy cơ dính chất cấm). | Tránh đi vào bài toán nhận diện bệnh bằng thị giác máy tính đại trà; bài toán giá trị cốt lõi là **thẩm định tính an toàn pháp lý của thuốc đối với tiêu chuẩn xuất khẩu**. |
| **Cơ sở dữ liệu MRLs Quốc tế & Cổng SPS Việt Nam** (EU Pesticides Database / SPS Vietnam) | https://spsvietnam.gov.vn<br>https://food.ec.europa.eu/plants/pesticides/eu-pesticides-database_en | Tra cứu ngưỡng dư lượng tối đa (MRLs) và cảnh báo kiểm dịch thực vật. | - Cập nhật nhanh nhất, chuẩn xác nhất các thay đổi luật và ngưỡng dư lượng của thị trường nhập khẩu.<br>- Cảnh báo sớm các lô hàng nông sản bị giữ lại tại cửa khẩu. | - Ngôn ngữ pháp lý bằng tiếng Anh hoặc công văn hành chính kỹ thuật cao.<br>- Tra cứu theo tên hoạt chất quốc tế (Active Substance), nông dân cầm chai thuốc tên tiếng Việt hoàn toàn không tra cứu được. | Cần đóng vai trò là bộ "thông dịch viên" và "bộ lọc cảnh báo": Chuyển đổi ngôn ngữ luật MRLs quốc tế phức tạp thành hướng dẫn đơn giản: Đèn Đỏ (Cấm/Nguy cơ cao) / Đèn Xanh (Được phép) kèm số ngày cách ly tối thiểu (PHI). |

---

## 4. Quy trình trước/sau (CP5)

> Người phụ trách: Trịnh Gia Huy. Phạm vi theo Candidate C (CP3): hỗ trợ người trồng Thanh Long tiếp cận và xác minh thông tin chăm sóc cây, nhất là thông tin thuốc, hóa chất liên quan đến xuất khẩu.
>
> Nhãn trạng thái: **[CONFIRMED]** đã được nhóm chốt hoặc đã kiểm bằng nguồn có link · **[PROPOSED]** đề xuất của người phụ trách, chờ nhóm xác nhận · **[PENDING CP4]** chờ kết quả kiểm chứng ở §3. Section này **không tự tạo số liệu**: mọi ô thời gian, tần suất chưa có dữ liệu từ §3 đều để [PENDING CP4].

### 4.1. Quy trình hiện tại

**Actor**

| Actor | Vai trò trong quy trình | Trạng thái |
|---|---|---|
| Hộ nông dân trồng Thanh Long | Primary actor: người cần thông tin và trực tiếp quyết định dùng thuốc | [CONFIRMED] |
| Cán bộ kỹ thuật HTX | Secondary actor: xác minh thông tin chuyên môn khi được hỏi | [PROPOSED] |
| Nguồn thông tin không chính thức (đại lý thuốc, người trồng khác, nhóm mạng xã hội) | Nơi nông dân hỏi đầu tiên | [PENDING CP4]: chưa có phỏng vấn xác nhận |

Sơ đồ:

```text
(1) Nông dân thấy cần xử lý vườn (sâu bệnh / đến giai đoạn chăm sóc)
        |
        v
(2) Hỏi nguồn quen: đại lý thuốc, người trồng khác, nhóm mạng xã hội     [PENDING CP4]
        |
        v
(3) Có cần xác minh không? --không--> (5)
        | có
        v
(4) Hỏi cán bộ kỹ thuật HTX -> cán bộ tra nhiều văn bản rời rạc:          <== BOTTLENECK (đề xuất)
    - Danh mục thuốc BVTV được phép sử dụng tại VN (Thông tư 75/2025/TT-BNNMT)
    - Nhãn thuốc: liều, thời gian cách ly
    - Quy định thị trường nhập khẩu (VD: MRL của Úc, Schedule 20)
        |
        v
(5) Nông dân chọn thuốc, pha, phun; ghi nhật ký (nếu có)
        |
        v
(6) Thu hoạch, bán vào lô xuất khẩu; lô có thể bị kiểm dư lượng
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Nông dân | Quan sát vườn, lịch chăm sóc | Nhu cầu thông tin (dùng thuốc gì, chăm sóc thế nào) | [PENDING CP4]: số lần phun / vụ | |
| 2 | Nông dân → nguồn không chính thức | Câu hỏi | Tên thuốc, cách làm; thường không kèm căn cứ quy định | [PENDING CP4] | Hành vi này là giả định, cần phỏng vấn xác nhận |
| 3 | Nông dân | Câu trả lời ở bước 2 | Quyết định có xác minh thêm hay không | [PENDING CP4]: tỷ lệ có hỏi lại | |
| 4 | Cán bộ kỹ thuật HTX | Câu hỏi của nông dân; văn bản quy định | Kết luận: thuốc có được dùng không, liều, thời gian cách ly | [PENDING CP4]: thời gian chờ, thời gian tra | [CONFIRMED] thông tin nằm ở ít nhất 3 nguồn tách rời do các cơ quan khác nhau ban hành (xem §10) |
| 5 | Nông dân | Thông tin có được | Lần phun; nhật ký (nếu có) | — | |
| 6 | Nông dân, HTX, bên thu mua | Trái thu hoạch | Lô đạt / không đạt yêu cầu dư lượng | [PENDING CP4]: tỷ lệ lô hoặc hộ bị loại | Impact chưa có số liệu |

**Bottleneck chính [PROPOSED, chờ CP4 xác nhận]:** bước 2–4. Để quyết định dùng thuốc cho trái xuất khẩu, phải đối chiếu nhiều văn bản chính thức rời rạc. Người trồng khó tự xác minh, còn người xác minh được (cán bộ kỹ thuật) không phải lúc nào cũng sẵn sàng đúng lúc người trồng cần.

- Phần đã xác minh: văn bản quy định nằm ở nhiều nguồn tách rời.
- Phần chưa xác minh: nông dân thực sự hỏi ai, chờ bao lâu, bao nhiêu lần phun dựa trên thông tin chưa xác minh.

### 4.2. Quy trình tương lai

> [PROPOSED]. Mức can thiệp do §6 quyết định. Quy trình dưới đây tương thích với mức **Workflow**: các bước cố định, AI không tự quyết bước tiếp theo. Theo phạm vi CP3, quy trình này **không** gồm chẩn đoán bệnh qua ảnh; nếu nhóm giữ Vision ở §6 thì cần quyết định chung (xem xung đột C1). Nguyên tắc: Farmer-first, Cooperative-supported. Nông dân hỏi trực tiếp, HTX không bắt buộc làm trung gian cho mỗi câu hỏi.

```text
LUỒNG HỎI ĐÁP (mỗi lần nông dân hỏi)

[NGƯỜI] Nông dân gửi câu hỏi bằng chữ qua kênh quen thuộc (VD: Zalo)
     |
     v
[AI] Phân loại câu hỏi: chăm sóc / thuốc - hóa chất / ngoài phạm vi
     |
     +-- chăm sóc ---------> [AI] Truy xuất từ tài liệu kỹ thuật đã được chọn
     |                        -> trả lời + trích đoạn nguồn
     |
     +-- thuốc - hóa chất -> [RULE] Tra BẢNG QUY ĐỊNH ĐÃ DUYỆT:
     |                        tên thương mại -> hoạt chất -> có đăng ký cho Thanh Long?
     |                        -> liều, thời gian cách ly -> MRL thị trường đích
     |                          |-- có trong bảng  -> [AI] diễn đạt lại dễ hiểu
     |                          |                     + nguồn + ngày cập nhật
     |                          |-- không có       -> chuyển cán bộ
     |
     +-- ngoài phạm vi / hỏi chẩn đoán bệnh / AI không chắc
                             -> [NGƯỜI] cán bộ kỹ thuật HTX trả lời (HITL)
     |
     v
[NGƯỜI] Nông dân tự quyết định và thực hiện. Hệ thống không quyết định thay.

LUỒNG DUY TRÌ BẢNG QUY ĐỊNH (khi có văn bản mới)

[AI] Trích xuất văn bản (danh mục thuốc, nhãn, MRL) thành dòng bảng
     -> [NGƯỜI] cán bộ / chuyên gia duyệt TỪNG DÒNG -> phát hành
     -> dòng nào bị văn bản mới ảnh hưởng thì KHÓA cho tới khi duyệt lại
```

| Bước | Ai làm | Boundary |
|---|---|---|
| Phân loại câu hỏi | AI | Không chắc thì xếp vào "ngoài phạm vi" và chuyển người |
| Trả lời câu chăm sóc | AI, chỉ từ tài liệu đã chọn | Luôn kèm nguồn; không có nguồn thì không trả lời |
| Kết luận về thuốc (được dùng không, liều, cách ly) | **Rule** trên bảng đã duyệt | AI **không** tự đưa ra con số; không khuyến nghị thuốc ngoài bảng |
| Câu ngoài phạm vi, chẩn đoán bệnh | Cán bộ kỹ thuật | AI không chẩn đoán |
| Duyệt bảng quy định | Cán bộ / chuyên gia | Chưa duyệt thì chưa dùng |
| Quyết định dùng thuốc | Nông dân | Hệ thống chỉ cung cấp thông tin có nguồn |

**Phương án quay về khi AI sai:** tắt tự trả lời câu về thuốc → cán bộ trả lời qua kênh nhắn tin như hiện tại, kèm **bảng tra in sẵn** xuất từ bảng quy định đã duyệt. Bảng này vẫn dùng được khi không có AI.

**Điều kiện kích hoạt quay về [PROPOSED, cần §8 thống nhất]:** chỉ cần một câu trả lời sai liều hoặc sai thời gian cách ly đến tay nông dân.

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước (luồng hỏi để quyết định dùng thuốc) | 6 | 5 | Đếm theo sơ đồ 4.1 và 4.2 |
| Tổng thời gian từ lúc có câu hỏi đến lúc có thông tin đã xác minh | [PENDING CP4] | [PROPOSED] vài phút với câu có trong bảng; câu chuyển cán bộ theo năng lực HTX | Không đặt target bằng số khi chưa có baseline |
| Số bước thủ công | 6 (mọi bước do người làm) | 2 trong luồng hỏi (hỏi, quyết định) + bước duyệt bảng khi có văn bản mới | Bước duyệt bảng là công việc mới của HTX |
| Bottleneck chính | Tra nhiều văn bản rời rạc, phụ thuộc thời gian của cán bộ | Chuyển thành việc duy trì bảng quy định đã duyệt | Chi phí công duyệt bảng: [PENDING] |
| Rủi ro mới phát sinh | — | (1) AI diễn đạt sai con số; (2) bảng lỗi thời khi quy định đổi; (3) nông dân tin máy quá mức, bỏ qua nhãn thuốc; (4) cán bộ quá tải vì câu bị chuyển; (5) chi phí duy trì bảng | Kiểm soát: boundary và phương án quay về ở 4.2; eval ở §7 |

**Metric đề xuất để §5, §7 và §8 dùng thống nhất [PROPOSED]:**

| # | Metric | Baseline | Target | Cách đo |
|---:|---|---|---|---|
| M1 | % lần phun của hộ pilot dùng thuốc được phép cho thị trường đích, đúng liều, đủ thời gian cách ly | [PENDING CP4]: audit nhật ký trước pilot | [Nhóm quyết định sau khi có baseline] | Cán bộ audit nhật ký định kỳ |
| M2 | Thời gian từ lúc hỏi đến lúc có thông tin đã xác minh | [PENDING CP4] | [Nhóm quyết định] | Log tin nhắn |
| M3 | % câu trả lời về thuốc có nguồn và khớp bảng đã duyệt | Không áp dụng (chưa có hệ thống) | 100% | Bộ eval §7 |

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

* **Bài của nhóm nằm ở ô:** Phức tạp vừa (nhiều luật/nhiều bệnh) - Mơ hồ vừa.
* **Vì sao:** Bệnh cây có nhiều biểu hiện (độ mơ hồ Vision), danh mục chất cấm dài và liên tục cập nhật nhưng có văn bản rõ (độ phức tạp RAG).

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
| --- | --- | --- | --- | --- |
| **No AI** | Web form nhập text thuần túy. | Nông dân chăm chỉ nhập liệu chuẩn 100%. | Nông dân bỏ dùng vì lười gõ. | Không |
| **Rule** | Tự code rule mapping thuốc - hóa chất. | Luật không đổi, danh mục thuốc ít. | Không bắt bệnh qua ảnh được. | Không |
| **Workflow** | App thu thập ảnh + RAG luật + Vision bắt bệnh (Có phê duyệt). | Con người muốn kiểm soát rủi ro pháp lý. | Cần người duyệt. | **Có** |
| **Agent** | AI tự bắt bệnh, tự đặt mua thuốc ship về vườn. | Mọi thứ hoàn hảo. | Chết vườn cây, đền bù phá sản. | Không |


**Mức chọn:** Workflow

**Vì sao không chọn mức đơn giản hơn:** Nếu không có AI Vision mồi nhử chụp ảnh, nông dân sẽ không xài app. Nếu không có RAG tra luật, HTX không xử lý kịp hàng nghìn mã thuốc bảo vệ thực vật.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | **AI Vision:** Phân tích ảnh lá/quả Thanh Long do nông dân chụp để dự đoán dấu hiệu sâu bệnh, cảnh báo các hộ có nguy cơ. **AI RAG:** Tra cứu và đối chiếu hoạt chất trong thuốc bảo vệ thực vật được đề xuất với quy định MRLs và danh mục chất cấm của thị trường xuất khẩu (Úc/Nhật), trả về cảnh báo kèm nguồn tham chiếu. |
| **Judgment** — Con người cân nhắc, quyết định gì? | Cán bộ kỹ thuật HTX kiểm tra lại ảnh, xác nhận tình trạng sâu bệnh và đánh giá cảnh báo từ AI. Đồng thời kiểm tra thông tin hoạt chất, quy định được trích dẫn trước khi quyết định phương án xử lý. Không phụ thuộc hoàn toàn vào kết luận của AI. |
| **Action** — Hành động cuối cùng là gì, ai làm? | Cán bộ HTX phê duyệt hoặc từ chối phương án chăm sóc, sử dụng thuốc và gửi hướng dẫn cho nông dân. Nông dân thực hiện, cập nhật nhật ký canh tác và ảnh theo dõi. Hệ thống lưu lại dữ liệu để HTX tổng hợp báo cáo chất lượng vùng trồng. |
| **Outcome** — Đo kết quả bằng gì? | Thời gian tổng hợp báo cáo HTX; tỷ lệ dùng sai thuốc; tỷ lệ lô hàng đạt kiểm định hóa chất. Đánh giá thêm AI Vision bằng Recall và kiểm tra độ chính xác trích xuất hoạt chất của RAG với mục tiêu.
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Ảnh lá/quả Thanh Long, mã hộ/vườn, thời gian chụp, nhật ký canh tác, tên thuốc và hoạt chất dự kiến sử dụng; tài liệu quy định MRLs và danh mục hoạt chất cấm theo thị trường xuất khẩu. Văn bản quy định có thể thu thập từ nguồn chính thức; dữ liệu ảnh thực tế và nhật ký chuẩn hóa chưa đầy đủ. |
| **Feedback** — Lấy phản hồi ở đâu để cải thiện? | Thu thập kết quả xác nhận/chỉnh sửa chẩn đoán của cán bộ HTX, những cảnh báo sai hoặc bỏ sót, kết quả kiểm định dư lượng và phản hồi của nông dân khi sử dụng app. Dữ liệu này giúp đánh giá, cải thiện mô hình Vision, cập nhật kho tài liệu RAG và tối ưu quy trình cảnh báo. |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**?: Hỗ trợ. Vì thiệt hại nếu sai (chất lượng xuất khẩu) tính bằng tiền tỷ, cần cán bộ chịu trách nhiệm pháp lý.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: Bỏ sót tệ hơn. Thà AI báo động giả để cán bộ check lại, còn hơn bỏ sót một chất cấm khiến cả container bị hủy ngoài cảng. Thiết kế: Threshold cảnh báo của AI đặt ở mức nhạy cảm cao.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

> Người phụ trách: Trịnh Gia Huy. **Trạng thái: DRAFT.** Bản này phụ thuộc vào §5 (Problem Statement v0, hiện chưa có), §6 (mức can thiệp) và §3 (bằng chứng CP4). Các trường để [PENDING] sẽ được hoàn thiện khi những section đó xong. Mức can thiệp được ghi theo §6 hiện tại (Workflow); bản này không mô tả hệ thống như một Agent tự quyết bước tiếp theo.

| Trường | Nội dung |
|---|---|
| **Actor** | Primary: hộ nông dân trồng Thanh Long, người trực tiếp quyết định dùng thuốc [CONFIRMED]. Secondary: cán bộ kỹ thuật HTX, người xác minh và xử lý câu ngoài phạm vi [PROPOSED] |
| **Quy trình** | Có nhu cầu chăm sóc → hỏi nguồn quen → (nếu cần) hỏi cán bộ → cán bộ tra nhiều văn bản → nông dân chọn thuốc, phun → thu hoạch vào lô xuất (§4.1) |
| **Bottleneck** | Xác minh "thuốc này có được dùng cho trái xuất khẩu không, liều bao nhiêu, cách ly mấy ngày" đòi hỏi đối chiếu nhiều văn bản rời rạc mà người trồng khó tự làm, và phụ thuộc vào thời gian của cán bộ (§4.1) [PROPOSED, chờ CP4] |
| **Impact** | Dùng thuốc không được phép hoặc không đủ thời gian cách ly có thể khiến trái bị loại khỏi lô xuất khẩu. Mức độ và tần suất: [PENDING CP4] |
| **Success Metric** (baseline → target, cách đo) | M1: % lần phun đúng quy định (baseline [PENDING CP4] → target nhóm chốt sau baseline; cán bộ audit nhật ký). M2: thời gian từ lúc hỏi đến lúc có thông tin đã xác minh (baseline [PENDING CP4]; log tin nhắn). M3: 100% câu trả lời về thuốc có nguồn và khớp bảng đã duyệt (bộ eval bên dưới) |
| **Boundary** | AI **không**: chẩn đoán bệnh; khuyến nghị thuốc ngoài bảng đã duyệt; tự đưa ra con số liều hoặc thời gian cách ly; trả lời khi không có nguồn; quyết định thay nông dân. **HITL:** cán bộ hoặc chuyên gia duyệt từng dòng bảng quy định trước khi dùng; nhận mọi câu ngoài phạm vi hoặc không chắc |
| **AI intervention point** | (1) Phân loại câu hỏi; (2) truy xuất và trả lời câu chăm sóc từ tài liệu đã chọn, kèm nguồn; (3) diễn đạt lại kết quả tra bảng cho dễ hiểu; (4) trích xuất văn bản quy định thành dòng bảng để người duyệt. Kết luận về thuốc do **Rule** làm trên bảng đã duyệt |
| **Mức chọn** | Workflow (theo §6; chờ nhóm xác nhận lại phạm vi, xem xung đột C1) |
| **Rủi ro & người kiểm tra** | Sai con số liều / cách ly → Rule lấy số từ bảng, eval tiêu chí 1, người kiểm tra: cán bộ kỹ thuật. Bảng lỗi thời → khóa dòng khi có văn bản mới, người kiểm tra: cán bộ / chuyên gia. Trả lời không có nguồn → tiêu chí 2–3, người kiểm tra: nhóm vận hành pilot |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Tất cả | [PENDING §5]: v0 chưa được viết | — | Sẽ điền khi §5 hoàn tất. v1 phải giữ nguyên các dữ kiện của v0, trừ thay đổi có lý do |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

Bộ eval đề xuất: các câu hỏi thật của nông dân thu được ở CP4 [PENDING], cộng các câu "bẫy" (thuốc không có trong bảng, hỏi chẩn đoán bệnh, hỏi cây khác, hỏi thị trường khác).

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Đúng con số về thuốc | Liều, thời gian cách ly, trạng thái được phép trong câu trả lời khớp 100% với dòng tương ứng trong bảng đã duyệt | Có bất kỳ con số nào khác bảng, hoặc AI tự đưa ra con số không có trong bảng |
| 2 | Có nguồn | Mọi câu trả lời về thuốc ghi tên văn bản nguồn và ngày cập nhật bảng | Thiếu nguồn, hoặc nguồn không chứa thông tin được trích |
| 3 | Biết từ chối và chuyển người | Câu ngoài phạm vi, câu hỏi chẩn đoán bệnh, thuốc không có trong bảng đều được chuyển cán bộ kèm lời nhắn rõ ràng | AI tự trả lời câu ngoài phạm vi, hoặc nói "được dùng" cho thuốc không có trong bảng |
| 4 | Câu trả lời chăm sóc bám tài liệu | Nội dung trả lời có trong đoạn tài liệu được trích; cán bộ chấm là đúng | Nội dung không có trong tài liệu, hoặc mâu thuẫn với tài liệu |
| 5 | Dễ hiểu với người trồng | Câu trả lời ngắn, dùng từ thông dụng, nêu rõ việc cần làm và điều cần tránh; người trồng trong pilot đọc hiểu được | Dùng thuật ngữ pháp lý hoặc kỹ thuật không giải thích; người trồng phải hỏi lại mới hiểu |

Tiêu chí 1 và 3 là **chặn** (một lỗi là không đạt cả bộ eval), vì bỏ sót, tức nói "được dùng" cho thuốc không được phép, là lỗi tệ nhất (khớp §6.4).

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có cần không? | Cao | Nếu HTX không ép, nông dân sẽ lười chụp ảnh. |
| **Usability** | Có biết dùng không? | TB | App cần UI chỉ có 1 nút chụp ảnh thật to. |
| **Feasibility** | Có đủ dữ liệu không? | TB | Ảnh Thanh Long VN có thể thiếu dataset chuẩn, cần thu thập tay. |
| **Viability** | Ai trả tiền? | TB | HTX hoặc Doanh nghiệp thu mua (chi phí phòng ngừa rủi ro). |

### 8.2. Kết luận

* **Quyết định:** Go
* **Lý do:** Nỗi đau kinh tế quá rõ ràng. Giải pháp là sự kết hợp hoàn hảo giữa chuẩn hóa quy trình (Workflow) và điểm chạm công nghệ (Vision/RAG).
* **Pilot nhỏ nhất:** 1 HTX Thanh Long, 10 hộ nông dân, 1 bộ luật MRLs của thị trường Úc trong 8 tuần.
* **Ngưỡng dừng:** Nếu sau 4 tuần, tỷ lệ nông dân chịu mở app chụp ảnh thấp dưới 30% $\rightarrow$ Dừng, quay về xài app như Zalo và cán bộ tự check tay.

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

*(Cao Minh Quang tổng hợp)*

1. **Cục Bảo vệ Thực vật — Bộ Nông nghiệp và Phát triển Nông thôn:**
   - Cơ sở dữ liệu trực tuyến về Danh mục thuốc bảo vệ thực vật được phép, hạn chế và cấm sử dụng tại Việt Nam: https://ppd.gov.vn
2. **Văn phòng Thông báo và Điểm hỏi đáp quốc gia về Vệ sinh Dịch tễ và Kiểm dịch Động thực vật Việt Nam (Văn phòng SPS Việt Nam):**
   - Hệ thống cảnh báo về các biện pháp an toàn thực phẩm, kiểm dịch động thực vật và thông tin thay đổi quy định MRLs của các nước thành viên WTO: https://spsvietnam.gov.vn
3. **Liên minh Châu Âu (European Union - EU):**
   - *Quy định Thực thi (EU) 2019/1793* (và các bản cập nhật định kỳ 6 tháng một lần) về việc áp dụng tạm thời các biện pháp kiểm soát tăng cường và biện pháp khẩn cấp đối với một số loại hàng hóa nhập khẩu vào EU (trong đó có mặt hàng Thanh Long Việt Nam): https://eur-lex.europa.eu/eli/reg_impl/2019/1793/oj
   - *EU Pesticides Database* (Cơ sở dữ liệu chính thức của Ủy ban Châu Âu về hoạt chất và mức giới hạn dư lượng tối đa MRLs): https://food.ec.europa.eu/plants/pesticides/eu-pesticides-database_en
4. **Bộ Nông nghiệp, Thủy sản và Lâm nghiệp Úc (Department of Agriculture, Fisheries and Forestry - DAFF):**
   - Hướng dẫn điều kiện an toàn sinh học và tiêu chuẩn kiểm dịch thực vật đối với quả thanh long tươi nhập khẩu từ Việt Nam: https://www.agriculture.gov.au/biosecurity-trade/import/goods/plant-products
5. **Bộ Y tế, Lao động và Phúc lợi Nhật Bản (MHLW) & Bộ Nông Lâm Thủy sản Nhật Bản (MAFF):**
   - Hệ thống danh mục chuẩn *Positive List System for Agricultural Chemical Residues in Foods* (Quy định mức dư lượng tối đa thuốc BVTV trong thực phẩm nhập khẩu): https://www.mhlw.go.jp/english/topics/foodsafety/positivelist060228/
6. **Bộ Khoa học và Công nghệ Việt Nam:**
   - Tiêu chuẩn Quốc gia *TCVN 11892-1:2017*: Thực hành nông nghiệp tốt (VietGAP) — Phần 1: Trồng trọt.
7. **Tổng công ty Viễn thông MobiFone & Weatherplus:**
   - Nền tảng Nông nghiệp số mobiAgri (Nghiên cứu hiện trạng tính năng tra cứu và tư vấn sâu bệnh cho nông dân): https://mobiagri.vn
