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
> Số liệu lấy từ §3.2, có ghi nguồn và cỡ mẫu (n). Phần lớn mới có n = 1 nên được dùng làm mốc tham chiếu; baseline chính thức đo trong 2 tuần đầu pilot (§8.2).

### 4.1. Quy trình hiện tại

**Actor**

| Actor | Vai trò trong quy trình | Căn cứ |
|---|---|---|
| Hộ nông dân trồng Thanh Long | Primary actor: người cần thông tin và trực tiếp chọn thuốc, phun | Chốt ở CP3; 3 hộ phỏng vấn (§3.2) |
| Đại lý thuốc BVTV | Nguồn thông tin chính khi nông dân chọn thuốc | Cả 3 hộ "phụ thuộc hoàn toàn vào đại lý bán thuốc" (§3.2) |
| Cán bộ kỹ thuật HTX | Secondary actor: phổ biến danh mục thuốc, trả lời câu hỏi, lấy mẫu kiểm trước thu hoạch | 2 cán bộ phỏng vấn (§3.2) |

Sơ đồ:

```text
(1) Nông dân thấy sâu bệnh / đến đợt chăm sóc
        |
        v
(2) Ra đại lý thuốc quen, mua theo đại lý chỉ                       <== BOTTLENECK
    (bao bì chữ nhỏ, tên hoạt chất tiếng nước ngoài, không có thông tin MRL thị trường)
        |                                    ^
        | (đôi khi)                          | Kênh phổ biến của HTX ít hiệu quả:
        v                                    | tờ photo danh mục (ướt, rách, thất lạc),
(3) Gọi cán bộ HTX hỏi "thuốc này xịt được không"   PDF gửi nhóm Zalo (ít người mở),
        |                                    | tập huấn đầu vụ (chỉ đông lúc đầu)
        v
(4) Cán bộ tra danh mục thuốc VN + quy định MRL của nước nhập khẩu, trả lời từng cuộc gọi
        |
        v
(5) Nông dân pha thuốc, phun
        |
        v
(6) Sát thu hoạch: HTX / thương lái lấy mẫu kiểm dư lượng -> đạt: gom xuất khẩu
                                                          -> không đạt: bán nội địa giá thấp
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Nông dân | Quan sát vườn | Cần xử lý sâu bệnh | 3–4 lần mỗi vụ phải đắn đo chọn thuốc (Snapshot 1, n = 1) | |
| 2 | Nông dân, đại lý thuốc | Triệu chứng, lời khuyên của đại lý | Chai thuốc đã mua | mỗi đợt sâu bệnh mất 1–2 ngày "vừa mua vừa lo" (Snapshot 1, n = 1) | Nông dân không tự đọc được hoạt chất trên bao bì |
| 3 | Nông dân → cán bộ HTX | Tên thuốc | Câu hỏi qua điện thoại | Không thường xuyên; nông dân chủ yếu tin đại lý (§3.2) | Không phải lần nào cũng hỏi |
| 4 | Cán bộ HTX | Danh mục thuốc VN, quy định MRL nước nhập khẩu | Trả lời từng người; tài liệu phổ biến | 2–3 ngày mỗi tháng để soạn tài liệu và trả lời cuộc gọi; 2 cán bộ cho khoảng 100 hộ (Snapshot 2, n = 1) | Quy định MRL thay đổi thường xuyên (Snapshot 2) |
| 5 | Nông dân | Thuốc, cách pha | Lần phun | — | |
| 6 | HTX / thương lái | Mẫu trái | Lô đạt hoặc không đạt | 1 trường hợp: 4 tấn không được gom xuất khẩu, bán nội địa 4.000 đ/kg thay vì 18.000 đ/kg (Snapshot 1, n = 1) | Phát hiện quá muộn, thuốc đã phun |

**Bottleneck chính:** bước 2. Nông dân quyết định chọn thuốc tại đại lý mà **không có cách tự kiểm tra ngay** thuốc đó có được dùng cho thị trường xuất khẩu không và phải cách ly bao nhiêu ngày. Kênh xác minh duy nhất là cán bộ HTX (bước 3–4), nhưng 2 cán bộ không thể trả lời kịp khoảng 100 hộ. Vi phạm chỉ lộ ra ở bước 6, khi không còn sửa được.

- Căn cứ: §3.2 gồm Snapshot 1, Snapshot 2 và bảng tổng hợp (3 hộ, 2 cán bộ).
- Giới hạn: số liệu thời gian và thiệt hại mới đến từ 1 người mỗi vai trò; cần thêm dữ liệu trước khi dùng làm baseline chính thức (xem 4.3).

### 4.2. Quy trình tương lai

```text
LUỒNG TRA CỨU (mỗi lần nông dân cầm chai thuốc, tại đại lý hoặc tại vườn)

[NGƯỜI] Nông dân mở công cụ (không cần tài khoản), gõ vài chữ tên thuốc
        hoặc hỏi một câu ngắn
     |
     v
[AI] Hiểu câu hỏi, gợi ý đúng tên thương mại trong bảng (gõ sai, viết tắt)
     -> nông dân chọn đúng chai thuốc
     |
     v
[RULE] Tra BẢNG QUY ĐỊNH ĐÃ DUYỆT:
       tên thương mại -> hoạt chất -> có đăng ký cho Thanh Long? -> liều, thời gian cách ly
       -> MRL / trạng thái ở thị trường đích
     |
     +-- XANH: được phép theo bảng -> liều, số ngày cách ly tối thiểu + nguồn + ngày cập nhật
     +-- ĐỎ:   không được phép / không có MRL ở thị trường đích -> "không dùng cho trái xuất khẩu" + nguồn
     +-- VÀNG: không có trong bảng, hoạt chất lạ, dòng đang khóa -> "chưa xác minh"
               -> [NGƯỜI] chuyển cán bộ HTX xác nhận (HITL)
     |
     v
[AI] Diễn đạt kết quả bằng lời dễ hiểu; KHÔNG thay đổi con số và trạng thái từ bảng
     |
     v
[NGƯỜI] Nông dân tự quyết định mua và phun. Hệ thống không quyết định thay.

Câu hỏi chăm sóc chung (không phải về thuốc):
[AI] trả lời chỉ từ tài liệu kỹ thuật do HTX chọn, kèm trích nguồn; không có nguồn -> chuyển cán bộ

LUỒNG DUY TRÌ BẢNG QUY ĐỊNH (khi có văn bản mới, VD: danh mục thuốc VN, cập nhật MRL, EU 2019/1793)

[AI] Trích xuất văn bản thành các dòng bảng
     -> [NGƯỜI] cán bộ HTX / chuyên gia duyệt TỪNG DÒNG -> phát hành
     -> dòng bị văn bản mới ảnh hưởng: KHÓA (trả VÀNG) cho tới khi duyệt lại
```

| Bước | Ai làm | Boundary |
|---|---|---|
| Hiểu câu hỏi, gợi ý tên thuốc | AI | Không đoán; nông dân phải chọn đúng chai thuốc trong danh sách gợi ý |
| Kết luận XANH / ĐỎ / VÀNG, liều, thời gian cách ly | **Rule** trên bảng đã duyệt | AI **không** tự đưa ra con số hoặc trạng thái |
| Diễn đạt lại kết quả | AI | Không thêm thông tin ngoài dòng bảng; luôn kèm nguồn và ngày cập nhật |
| Thuốc lạ, dòng khóa, câu ngoài phạm vi, hỏi chẩn đoán bệnh | Cán bộ HTX | AI không trả lời thay |
| Duyệt bảng quy định | Cán bộ HTX / chuyên gia | Chưa duyệt thì chưa dùng |
| Quyết định mua và phun | Nông dân | Hệ thống chỉ cung cấp thông tin có nguồn |

**Phương án quay về khi AI sai:** tắt phần AI (gợi ý tên, diễn đạt lại), chỉ giữ **tra bảng theo đúng tên** (Rule thuần) và **bảng tra in sẵn** xuất từ bảng đã duyệt. Câu hỏi khác quay về cán bộ HTX qua điện thoại như hiện tại. Bảng quy định vẫn dùng được khi không có AI.

**Điều kiện kích hoạt quay về (khớp ngưỡng dừng ở §8.2):** chỉ cần một kết quả sai trạng thái, sai liều hoặc sai thời gian cách ly đến tay nông dân.

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước để biết thuốc có dùng được không | 4 (bước 1–4; có khi dừng ở bước 2 mà không xác minh) | 3 (mở công cụ → chọn thuốc → đọc kết quả) | Đếm theo sơ đồ 4.1 và 4.2 |
| Thời gian nông dân có được câu trả lời đã xác minh | 1–2 ngày mỗi đợt sâu bệnh (n = 1) | Dưới 1 phút với thuốc có trong bảng; câu VÀNG trong ngày làm việc | Cần đo lại trên nhiều hộ |
| Thời gian cán bộ HTX trả lời và soạn tài liệu | 2–3 ngày mỗi tháng (n = 1) | Giảm ≥ 50%, chỉ còn câu VÀNG và duyệt bảng | Duyệt bảng là việc mới, cần đo thêm |
| Số bước thủ công | 6 (mọi bước do người làm) | 2 trong luồng tra (chọn thuốc, quyết định) + bước duyệt bảng khi có văn bản mới | |
| Bottleneck chính | Chọn thuốc tại đại lý mà không tự xác minh được; cán bộ không kịp trả lời | Chuyển thành việc **duy trì bảng quy định đã duyệt** | |
| Thời điểm phát hiện vi phạm | Sát thu hoạch (bước 6), khi đã phun | Trước khi mua và phun | Đây là thay đổi quan trọng nhất |
| Rủi ro mới phát sinh | — | (1) AI gợi ý nhầm tên thuốc gần giống; (2) bảng lỗi thời khi quy định đổi; (3) nông dân tin máy quá mức, bỏ qua nhãn; (4) cán bộ quá tải câu VÀNG; (5) chi phí duy trì bảng | Kiểm soát bằng boundary, phương án quay về ở 4.2 và eval ở §7 |

**Metric dùng thống nhất cho §5, §7, §8:**

| # | Metric | Baseline | Target | Cách đo |
|---:|---|---|---|---|
| M1 | % lần phun của hộ pilot dùng thuốc ở trạng thái XANH cho thị trường đích, đủ thời gian cách ly | Đo bằng audit nhật ký phun của 10 hộ pilot trong tuần 1–2 (§8.2); §3.2 ghi nhận 1 trường hợp vi phạm (n = 1) | ≥ 95% và 0 lần dùng thuốc trạng thái ĐỎ | Cán bộ audit nhật ký mỗi 2 tuần |
| M2 | Thời gian từ lúc nông dân có câu hỏi đến lúc có thông tin đã xác minh | 1–2 ngày (Snapshot 1, n = 1); đo lại tuần 1–2 pilot | Dưới 1 phút (XANH / ĐỎ); trong ngày làm việc (VÀNG) | Log công cụ; bấm giờ khi phỏng vấn |
| M3 | % kết quả về thuốc khớp bảng đã duyệt và có nguồn | Không áp dụng | 100% | Bộ eval §7 |
| M4 | Thời gian cán bộ HTX trả lời câu hỏi và soạn tài liệu mỗi tháng | 2–3 ngày (n = 1) | Giảm ≥ 50% | Cán bộ tự ghi |
| M5 (kết quả trễ) | Số lô hoặc hộ pilot bị loại vì dư lượng | 1 trường hợp ghi nhận (§3.2, n = 1); tỷ lệ đo trong pilot | 0 trường hợp do thuốc trạng thái ĐỎ | Kết quả kiểm mẫu của HTX / thương lái |

---

## 5. Problem Statement v0 (CP5)

> Người phụ trách: Trần Duy Thành. Bản v0 viết ở CP5, **trước khi** chọn mức can thiệp AI, nên chưa có "AI intervention point". Các trường khớp với actor, quy trình hiện tại, bottleneck và metric ở §4 (Dependency C). Số liệu lấy từ §3.2, phần lớn có n = 1.

| Trường | Nội dung |
|---|---|
| **Actor** | Primary: hộ nông dân trồng Thanh Long bán vào kênh xuất khẩu, người trực tiếp chọn và phun thuốc. Secondary: cán bộ kỹ thuật HTX, người phổ biến danh mục thuốc và trả lời câu hỏi (§4.1) |
| **Quy trình** | Thấy sâu bệnh → ra đại lý mua thuốc theo lời đại lý → (đôi khi) gọi cán bộ HTX hỏi → cán bộ tra danh mục thuốc và quy định của nước nhập khẩu → nông dân phun → HTX / thương lái kiểm mẫu sát thu hoạch (§4.1) |
| **Bottleneck** | Bước chọn thuốc tại đại lý: nông dân không tự kiểm tra được thuốc đó có được dùng cho trái xuất khẩu không và cách ly bao nhiêu ngày. Bao bì ghi tên hoạt chất khó hiểu; kênh xác minh duy nhất là 2 cán bộ cho khoảng 100 hộ (§3.2, §4.1) |
| **Impact** | Vi phạm chỉ lộ ra khi kiểm mẫu sát thu hoạch, lúc đã phun. Trường hợp ghi nhận: 4 tấn không được gom xuất khẩu, bán 4.000 đ/kg thay vì 18.000 đ/kg (Snapshot 1, n = 1). Cán bộ HTX mất 2–3 ngày mỗi tháng trả lời và soạn tài liệu (Snapshot 2, n = 1) |
| **Success Metric** (baseline → target, cách đo) | M1: % lần phun dùng thuốc được phép cho thị trường đích, đủ thời gian cách ly. Baseline chưa có → target ≥ 95%; cách đo: audit nhật ký phun. M2: thời gian từ lúc có câu hỏi đến lúc có thông tin đã xác minh. Baseline 1–2 ngày (n = 1) → target trong ngày; cách đo: bấm giờ, log. M4: thời gian cán bộ HTX trả lời và soạn tài liệu. Baseline 2–3 ngày mỗi tháng (n = 1) → giảm ≥ 50%; cách đo: cán bộ tự ghi (§4.3) |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | Mọi giải pháp không được quyết định thay nông dân việc dùng thuốc và không được kết luận một thuốc "đạt chuẩn xuất khẩu" khi chưa có nguồn chính thức. Cán bộ kỹ thuật HTX phải kiểm tra khi thông tin thiếu, mâu thuẫn hoặc là thuốc mới (theo yêu cầu của HTX ở §3.2) |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

| # | Phản biện (nguồn: AI rà soát v0, chỉ hỏi lỗ hổng) | Nhóm có đồng ý không | Xử lý |
|---:|---|---|---|
| 1 | Boundary còn chung chung: chưa nói rõ AI không được tự đưa ra con số liều, thời gian cách ly hay trạng thái được phép / không được phép | Đồng ý | v1 (§7) tách rõ: kết luận do Rule trên bảng đã duyệt, AI chỉ diễn đạt lại |
| 2 | M1 chưa có baseline; M2 và M4 mới từ 1 người, chưa đủ làm baseline | Đồng ý | Giữ nhãn n = 1; đo baseline trong 2 tuần đầu pilot (§8.2) |
| 3 | "Thị trường đích" chưa xác định: bằng chứng ở §3 nói về EU, còn pilot cũ ghi Úc | Đồng ý | Pilot chọn 1 thị trường đích ngay tuần 1 (§8.2); bảng quy định chỉ xây cho thị trường đó |

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

* **Bài của nhóm nằm ở ô:** Độ mơ hồ Cao × Độ phức tạp Cao
* **Vì sao:**
  - Về độ mơ hồ: Cao
    - Người trồng thanh long thường đặt câu hỏi theo ngôn ngữ đời thường, sử dụng tên thương mại của thuốc thay vì tên hoạt chất. Một câu hỏi có thể thiếu thông tin về đối tượng phòng trừ, thị trường xuất khẩu hoặc thời điểm thu hoạch.
    - Cùng một loại thuốc có thể cần đối chiếu nhiều điều kiện khác nhau: đăng ký sử dụng tại Việt Nam, hướng dẫn trên nhãn, thời gian cách ly và giới hạn dư lượng tối đa tại thị trường đích.
    - Kết quả CP4 cho thấy nông dân gặp khó khăn khi đọc thuật ngữ kỹ thuật, trong khi cán bộ HTX phải xử lý thông tin từ nhiều nguồn. Hệ thống cần nhận biết những trường hợp thiếu dữ kiện hoặc không thể đưa ra kết luận.
  - Về độ phức tạp: Cao
    - Quy trình xác minh liên quan đến nhiều nguồn dữ liệu có cấu trúc và phi cấu trúc: danh mục thuốc BVTV, nhãn thuốc, tài liệu kỹ thuật, quy định MRL và cảnh báo SPS.
    - Hệ thống cần kết hợp các bước: phân loại câu hỏi, chuẩn hóa tên thuốc, tra cứu dữ liệu, kiểm tra điều kiện, tạo câu trả lời dễ hiểu và chuyển cán bộ kỹ thuật khi gặp ngoại lệ.
    - Dữ liệu quy định có thể thay đổi, đòi hỏi cơ chế cập nhật, xác minh và khóa thông tin chưa được duyệt.

Bài toán có độ mơ hồ cao tại khâu hiểu câu hỏi và diễn đạt thông tin, nhưng phần kiểm tra điều kiện thuốc phải được chuẩn hóa thành các quy tắc rõ ràng. Vì vậy, nhóm ưu tiên phối hợp AI với Rule và Human-in-the-Loop, thay vì để AI tự quyết định toàn bộ quy trình.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
| --- | --- | --- | --- | --- |
| **No AI** |HTX chuẩn hóa danh mục thuốc, hướng dẫn canh tác và quy định xuất khẩu thành tài liệu đơn giản; cập nhật định kỳ và phổ biến qua Zalo, bản in hoặc tập huấn |Phạm vi thuốc nhỏ, quy định ít thay đổi; nông dân có thể tự tìm đúng thông tin hoặc dễ dàng liên hệ cán bộ  |Thông tin dễ lỗi thời; nông dân vẫn phải tìm kiếm thủ công; cán bộ HTX tiếp tục chịu tải tư vấn| Không ưu tiên |
| **Rule** |Xây dựng bảng tra cứu tên thương mại → hoạt chất → đăng ký sử dụng → thông tin nhãn → MRL thị trường đích; lọc và cảnh báo theo điều kiện đã được phê duyệt|Dữ liệu đã chuẩn hóa, người dùng nhập đủ thông tin theo biểu mẫu và chủ yếu cần tra cứu các trường hợp xác định |Khó xử lý câu hỏi tự nhiên, tên thuốc nhập sai, thông tin thiếu hoặc yêu cầu giải thích phức tạp |Chọn làm thành phần kiểm tra bắt buộc |
| **Workflow** |Quy trình cố định: tiếp nhận câu hỏi → AI phân loại → truy xuất dữ liệu/tài liệu → Rule kiểm tra thông tin thuốc → AI diễn đạt kết quả có dẫn nguồn → chuyển cán bộ khi thiếu dữ liệu hoặc có ngoại lệ |Các nhánh nghiệp vụ xác định được từ trước, AI chỉ cần xử lý ngôn ngữ và tổng hợp thông tin trong phạm vi kiểm soát |AI có thể phân loại sai hoặc diễn đạt sai; dữ liệu nguồn lỗi thời; cần cơ chế kiểm tra, fallback và bảo trì |Đề xuất chọn |
| **Agent** |AI tự quyết định các bước tra cứu tiếp theo, lựa chọn nguồn/công cụ, yêu cầu bổ sung thông tin và điều phối các tác vụ tùy tình huống  |Quy trình có nhiều tình huống khó dự đoán, cần lập kế hoạch động mà Workflow cố định không đáp ứng được |Khó kiểm soát đường đi xử lý, khó truy vết lỗi, chi phí và độ phức tạp cao hơn; tăng rủi ro khi liên quan đến thông tin thuốc BVTV |Chưa cần thiết |


**Mức chọn:** Workflow kết hợp Rule và Human-in-the-Loop

**Vì sao không chọn mức đơn giản hơn:**
- No AI chưa giải quyết triệt để bottleneck: Theo CP4, HTX đã sử dụng tài liệu in, PDF và tập huấn nhưng người trồng vẫn gặp khó khăn trong việc tìm kiếm, hiểu và đối chiếu thông tin. Chỉ cải thiện tài liệu có thể giảm một phần khó khăn nhưng chưa đáp ứng tốt nhu cầu tra cứu trực tiếp tại vườn.
- Rule đơn thuần chưa đủ cho toàn bộ trải nghiệm: Rule phù hợp để kiểm tra dữ liệu chuẩn hóa, nhưng người dùng thường đặt câu hỏi bằng tiếng Việt tự nhiên, tên thương mại hoặc thông tin không đầy đủ. Việc yêu cầu nông dân điền biểu mẫu phức tạp cũng mâu thuẫn với tín hiệu phản bác về khả năng sử dụng ở CP4.
- Workflow giải quyết phần còn thiếu: AI hỗ trợ hiểu yêu cầu, tìm tài liệu và diễn đạt thông tin; Rule chịu trách nhiệm kiểm tra các điều kiện có cấu trúc; cán bộ HTX xác minh ngoại lệ.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? |Phân loại câu hỏi của nông dân thành chăm sóc cây, thuốc/hóa chất hoặc ngoài phạm vi; nhận diện thông tin còn thiếu; truy xuất và tổng hợp hướng dẫn từ nguồn đã được chọn; diễn đạt kết quả bằng ngôn ngữ dễ hiểu, có dẫn nguồn. AI không tự dự đoán mức dư lượng thực tế hoặc tự kết luận thuốc an toàn cho xuất khẩu  |
| **Judgment** — Con người cân nhắc, quyết định gì? |Nông dân quyết định hành động canh tác sau khi xem thông tin và hướng dẫn chính thức. Cán bộ kỹ thuật HTX hoặc chuyên gia xác minh trường hợp chưa đủ dữ kiện, thuốc chưa có trong bảng hoặc nguồn mâu thuẫn. Người phụ trách dữ liệu duyệt các bản ghi quy định trước khi sử dụng  |
| **Action** — Hành động cuối cùng là gì, ai làm? |Hệ thống cung cấp thông tin tra cứu có nguồn, ngày cập nhật và cảnh báo khi chưa thể kết luận. Nông dân đối chiếu hướng dẫn và quyết định bước tiếp theo; trường hợp nhạy cảm được chuyển cho cán bộ kỹ thuật xác minh. AI không tự thực hiện hoặc phê duyệt việc sử dụng thuốc |
| **Outcome** — Đo kết quả bằng gì? |M1: Tỷ lệ lần phun trong pilot đáp ứng các điều kiện sử dụng thuốc được kiểm tra qua nhật ký và hồ sơ liên quan. M2: Thời gian từ lúc gửi câu hỏi đến khi nhận được thông tin đã xác minh. M3: Tỷ lệ câu trả lời về thuốc có nguồn và khớp bảng dữ liệu đã duyệt (target đề xuất: 100%). Baseline và target của M1/M2 cần được nhóm xác nhận theo §4.3 và §5 |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? |Câu hỏi tiếng Việt của nông dân; tên thương mại/hoạt chất; cây trồng, mục đích sử dụng, thị trường đích và thông tin liên quan nếu cần. Nguồn tham chiếu gồm danh mục thuốc BVTV, dữ liệu nhãn, hướng dẫn kỹ thuật và MRL theo thị trường. CP4 đã xác định các loại nguồn có thể tra cứu, nhưng chưa chứng minh đã có cơ sở dữ liệu mapping đầy đủ, chính xác và được cập nhật |
| **Feedback** — Lấy phản hồi ở đâu để cải thiện? |Phản hồi của nông dân về mức dễ hiểu và tính hữu ích của câu trả lời; các trường hợp được cán bộ HTX kiểm tra/chỉnh sửa; log câu hỏi bị chuyển người; kết quả chấm bộ eval; lịch sử cập nhật dữ liệu. Cán bộ chuyên môn rà soát lỗi để cập nhật bảng dữ liệu, quy tắc và tài liệu tham chiếu |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**?: Chọn: Augment - hỗ trợ ra quyết định, không tự động quyết định thay người dùng. Lý do:
  - Nông dân gặp khó khăn khi đối chiếu tên thương mại trên chai thuốc với hoạt chất và quy định xuất khẩu. Nhu cầu được ghi nhận là có thể tự tra cứu nhanh, ngay tại vườn.
  - Các hộ được phỏng vấn phản đối giao diện yêu cầu tạo tài khoản phức tạp, nhập văn bản dài hoặc điền nhiều biểu mẫu.
  - Cán bộ HTX muốn giảm khối lượng tư vấn lặp lại nhưng vẫn duy trì trách nhiệm xác minh những trường hợp nhạy cảm.
  - Do đó, hệ thống nên tự động hóa các thao tác hỗ trợ như phân loại câu hỏi, tìm kiếm và tổng hợp thông tin. Việc kiểm tra quy định được thực hiện bằng Rule trên dữ liệu đã duyệt; các quyết định canh tác vẫn thuộc con người.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: Ưu tiên kiểm soát lỗi báo nhầm theo nghĩa khẳng định sai rằng một phương án sử dụng thuốc là phù hợp hoặc an toàn cho mục tiêu xuất khẩu.
  - Hậu quả có thể là người dùng tin vào kết luận sai, áp dụng thuốc không phù hợp, làm tăng rủi ro không đạt yêu cầu thu mua hoặc kiểm nghiệm.
  - Thiết kế:
    - Không để LLM tự kết luận thuốc được phép sử dụng; sử dụng Rule dựa trên dữ liệu đã duyệt để kiểm tra các điều kiện xác định.
    - Chỉ cung cấp thông tin khi có nguồn phù hợp, nêu rõ giới hạn của kết quả và thời điểm cập nhật.
    - Không suy ra rằng sản phẩm chắc chắn đạt tiêu chuẩn xuất khẩu chỉ từ một giá trị MRL hoặc thời gian cách ly.
    - Nếu dữ liệu thiếu, mâu thuẫn hoặc chưa được phê duyệt, hệ thống phải trả trạng thái "Chưa đủ thông tin để xác minh" và chuyển cán bộ kỹ thuật.
    - Có cơ chế khóa dữ liệu bị ảnh hưởng bởi thay đổi quy định cho đến khi được rà soát.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

> Người phụ trách: Trịnh Gia Huy. Bản này dùng bằng chứng ở §3 và quy trình ở §4.
> Bản này giữ nguyên các dữ kiện của v0 (§5), chỉ thay đổi những trường ghi trong bảng so sánh bên dưới, và theo mức đã chọn ở §6 (Workflow + Rule + HITL): hệ thống chạy theo các bước cố định, AI không tự quyết bước tiếp theo.

| Trường | Nội dung |
|---|---|
| **Actor** | Primary: hộ nông dân trồng Thanh Long, người trực tiếp chọn và phun thuốc (3 hộ phỏng vấn, §3.2). Secondary: cán bộ kỹ thuật HTX, người duyệt bảng quy định và xác nhận trường hợp ngoại lệ (2 cán bộ phỏng vấn, §3.2) |
| **Quy trình** | Thấy sâu bệnh → mua thuốc theo đại lý → (đôi khi) gọi cán bộ HTX → cán bộ tra danh mục thuốc và quy định MRL → nông dân phun → HTX / thương lái kiểm mẫu sát thu hoạch (§4.1) |
| **Bottleneck** | Nông dân chọn thuốc tại đại lý mà không có cách tự kiểm tra ngay thuốc đó có được dùng cho thị trường xuất khẩu không và phải cách ly bao nhiêu ngày. Kênh xác minh duy nhất là 2 cán bộ HTX cho khoảng 100 hộ (§4.1; §3.2) |
| **Impact** | Vi phạm chỉ lộ ra khi kiểm mẫu sát thu hoạch. Trường hợp ghi nhận: 4 tấn không được gom xuất khẩu, bán 4.000 đ/kg thay vì 18.000 đ/kg (§3.2, Snapshot 1, n = 1). Cán bộ HTX mất 2–3 ngày mỗi tháng trả lời và soạn tài liệu (Snapshot 2, n = 1). Ở cấp ngành, thanh long Việt Nam nằm trong diện kiểm soát tăng cường của EU theo Quy định 2019/1793 (§3.2, §10) |
| **Success Metric** (baseline → target, cách đo) | M1: % lần phun dùng thuốc XANH, đủ thời gian cách ly (baseline đo bằng audit nhật ký tuần 1–2 pilot → ≥ 95%, 0 lần ĐỎ). M2: thời gian có thông tin đã xác minh (1–2 ngày, n = 1 → dưới 1 phút với XANH / ĐỎ; log). M3: 100% kết quả về thuốc khớp bảng và có nguồn (bộ eval). M4: thời gian cán bộ mỗi tháng (2–3 ngày, n = 1 → giảm ≥ 50%; cán bộ tự ghi). Định nghĩa đầy đủ ở §4.3 |
| **Boundary** | AI **không**: tự đưa ra con số liều, thời gian cách ly hay trạng thái XANH / ĐỎ; khuyến nghị thuốc ngoài bảng; chẩn đoán bệnh; trả lời khi không có nguồn; quyết định thay nông dân. **HITL:** cán bộ HTX / chuyên gia duyệt từng dòng bảng trước khi phát hành; xác nhận mọi trường hợp VÀNG (thuốc lạ, dòng đang khóa, câu ngoài phạm vi), đúng yêu cầu của HTX ở §3.2 |
| **AI intervention point** | (1) Hiểu câu hỏi và gợi ý đúng tên thương mại khi nông dân gõ sai hoặc viết tắt; (2) diễn đạt kết quả tra bảng thành lời dễ hiểu; (3) trả lời câu chăm sóc chung chỉ từ tài liệu HTX đã chọn, kèm nguồn; (4) trích xuất văn bản quy định mới thành dòng bảng để người duyệt. Kết luận XANH / ĐỎ / VÀNG do **Rule** làm trên bảng đã duyệt |
| **Mức chọn** | **Workflow kết hợp Rule và Human-in-the-Loop** (theo §6.2) |
| **Rủi ro & người kiểm tra** | Gợi ý nhầm tên thuốc gần giống → nông dân phải xác nhận đúng chai thuốc; tiêu chí 1 (người kiểm: nhóm vận hành pilot). Sai con số / trạng thái → Rule lấy từ bảng; tiêu chí 2 (cán bộ HTX). Bảng lỗi thời → khóa dòng khi có văn bản mới (cán bộ HTX / chuyên gia). Trả lời không nguồn → tiêu chí 3–4 (nhóm vận hành pilot) |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Boundary | Chung: không quyết định thay nông dân, không kết luận "đạt chuẩn" khi chưa có nguồn; cán bộ kiểm tra khi thông tin thiếu hoặc là thuốc mới | Cụ thể: AI không tự đưa ra con số hay trạng thái XANH / ĐỎ; Rule kết luận trên bảng đã duyệt; VÀNG chuyển cán bộ; khóa dòng khi luật đổi | Phản biện #1 ở §5: boundary v0 chưa nói AI không được làm gì; §6 chọn Workflow + Rule nên cần chỉ rõ chỗ nào là AI |
| Success Metric | M1, M2, M4; M2 target "trong ngày" | Thêm M3 (100% kết quả khớp bảng, có nguồn); M2 target dưới 1 phút với XANH / ĐỎ, trong ngày với VÀNG | Có bước AI nên cần metric chất lượng đầu ra; công cụ tra cứu cho phép trả lời tức thì với thuốc có trong bảng |
| AI intervention point | Chưa có (v0 viết trước CP6) | 4 điểm can thiệp như bảng trên | CP6 chọn mức can thiệp |
| Mức chọn, rủi ro & người kiểm tra | Chưa có | Workflow + Rule + HITL; rủi ro gắn với tiêu chí eval và người kiểm tra | CP6 |
| Actor, Quy trình, Bottleneck, Impact | Như §5 | Giữ nguyên | Không có bằng chứng mới làm thay đổi |

**Tiêu chí đánh giá đầu ra của AI:**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Nhận đúng chai thuốc | Tên thương mại AI gợi ý trùng với chai thuốc nông dân hỏi; nếu có từ 2 tên gần giống trở lên thì hỏi lại để nông dân chọn | Tự chọn một tên gần giống mà không hỏi lại |
| 2 | Đúng trạng thái và con số | Trạng thái XANH / ĐỎ / VÀNG, liều, thời gian cách ly khớp 100% với dòng bảng đã duyệt | Bất kỳ con số hoặc trạng thái nào khác bảng, hoặc AI tự đưa ra con số không có trong bảng |
| 3 | Có nguồn | Mọi kết quả về thuốc ghi văn bản nguồn và ngày cập nhật bảng | Thiếu nguồn, hoặc nguồn không chứa thông tin được trích |
| 4 | Biết dừng và chuyển người | Thuốc không có trong bảng, dòng đang khóa, câu hỏi chẩn đoán bệnh, câu ngoài phạm vi đều trả VÀNG và chuyển cán bộ HTX | Tự trả lời câu ngoài phạm vi, hoặc trả XANH cho thuốc không có trong bảng |
| 5 | Dễ hiểu với người trồng | Câu trả lời ngắn, dùng từ thông dụng, nói rõ "được xịt / không được xịt cho trái xuất khẩu" và số ngày cách ly | Dùng thuật ngữ pháp lý, tên hoạt chất mà không giải thích; người trồng phải hỏi lại |

Tiêu chí 2 và 4 là **chặn**: một lỗi là không đạt cả bộ eval, vì lỗi tệ nhất là **báo nhầm theo nghĩa ở §6.4**: khẳng định sai rằng một thuốc được phép dùng (trả XANH sai).

**Bộ eval mẫu 10 cặp input / đầu ra mong đợi:** [report/assets/cp6-eval-set.md](../assets/cp6-eval-set.md).

---

## 8. Quyết định (CP6)

> Người phụ trách: Trần Duy Thành. Đánh giá dựa trên §3 (bằng chứng), §6 (Workflow + Rule + HITL) và §7 (eval). Bản trước của mục này dựa trên chụp ảnh và Vision, đã được thay vì phạm vi CP3 không gồm hướng đó.

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | TB | Có tín hiệu xác nhận: 3 hộ đều phụ thuộc đại lý và từng hoang mang về quy định; 2 cán bộ HTX xác nhận quá tải; 1 trường hợp thiệt hại cụ thể (§3.2). Nhưng mẫu nhỏ, số liệu mới n = 1, và chưa có bằng chứng nông dân sẽ tra cứu trước khi mua thuốc |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Cao | Giả định 2 ở §3.1 quan trọng 5/5 nhưng bằng chứng chỉ 2/5. Nông dân phản đối tài khoản, gõ dài, biểu mẫu (§3.2). Chưa thử xem nông dân có gõ được tên thuốc và hiểu kết quả XANH / ĐỎ / VÀNG không |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | TB | Nguồn chính thức có sẵn: danh mục thuốc BVTV Việt Nam, cơ sở dữ liệu MRL của nước nhập khẩu (§3.3, §10). Nhưng chưa có bảng mapping tên thương mại → hoạt chất → MRL đã duyệt; phải giới hạn ở các thuốc hộ pilot thực sự dùng |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | Cao | Chưa có bằng chứng ai trả tiền. Trách nhiệm khi thông tin sai về thuốc chưa rõ. Duyệt bảng quy định là việc mới cho HTX, trong khi 2 cán bộ đã quá tải (§3.2) |

### 8.2. Kết luận

**Quyết định:** **Go có điều kiện**, phạm vi pilot nhỏ.

**Lý do:**
- Value có tín hiệu thật (§3.2) và bottleneck rõ, đo được (§4).
- Usability và Viability đang ở mức Cao, các giả định quan trọng chưa được kiểm chứng. Vì vậy chưa xây ngay hệ thống AI mà chia pilot thành các giai đoạn có cổng kiểm tra; không qua cổng thì dừng.
- Mức Workflow + Rule + HITL (§6) cho phép bắt đầu bằng phần không cần AI (bảng tra đã duyệt), rồi mới thêm AI.

**Pilot nhỏ nhất:** 1 HTX, 10 hộ, 1 thị trường đích (chọn ở tuần 1 giữa EU, theo bằng chứng §3, và Úc), chỉ gồm các thuốc hộ pilot thực sự dùng, trong 8 tuần.

| Giai đoạn | Việc làm | Cổng kiểm tra để đi tiếp |
|---|---|---|
| Tuần 1–2 (chưa có AI) | Chọn thị trường đích; cán bộ HTX duyệt bảng quy định cho các thuốc hộ pilot dùng; phát bảng tra in sẵn; audit nhật ký để có baseline M1; bấm giờ M2, M4; thử với 5 hộ xem họ có tra và hiểu XANH / ĐỎ / VÀNG không | Có baseline M1; ≥ 3/5 hộ tra đúng và hiểu kết quả |
| Tuần 3 | Chạy bộ eval §7 (10 cặp) trên công cụ | ≥ 9/10 cặp đạt và không có lỗi ở tiêu chí chặn |
| Tuần 4–8 | Cho 10 hộ dùng công cụ; câu VÀNG chuyển cán bộ | Không chạm ngưỡng dừng |

**Nếu Not Yet (phương án thay thế):** cần kiểm chứng trước (1) nông dân có tự tra trước khi mua thuốc không, bằng thử nghiệm với bảng tra in sẵn; (2) ai trả chi phí vận hành; (3) chốt thị trường đích.

**Nếu No-Go — nên làm gì thay AI:** HTX duy trì bảng tra in sẵn đã duyệt cho các thuốc phổ biến và một kênh hỏi đáp cố định với cán bộ.

**Ngưỡng dừng:**
- Nếu sau 4 tuần dùng công cụ, **dưới 30% hộ pilot tra cứu ít nhất 1 lần trong 2 tuần** → dừng, quay về bảng tra in sẵn + cán bộ trả lời qua điện thoại.
- Nếu có **bất kỳ kết quả XANH sai** (khẳng định sai rằng thuốc được dùng) đến tay nông dân → tắt phần AI ngay, chỉ giữ tra bảng theo đúng tên (§4.2).
- Nếu sau 8 tuần **thời gian cán bộ HTX** (duyệt bảng + câu VÀNG) **không thấp hơn baseline M4** → Not Yet, xem lại Viability trước khi mở rộng.

---

## 9. Hạn chế và hướng tiếp theo

> Người tổng hợp: Trần Duy Thành.

**Hạn chế**

- **Mẫu kiểm chứng nhỏ:** 3 hộ và 2 cán bộ (§3.2); các số liệu thời gian và thiệt hại mới đến từ 1 người mỗi vai trò, chưa đủ làm baseline chính thức.
- **Chưa có baseline M1:** chưa audit nhật ký phun, nên chưa biết tỷ lệ lần phun đúng quy định hiện tại.
- **Thị trường đích chưa chốt:** bằng chứng ở §3 nói về EU, pilot cũ ghi Úc. Bảng quy định và metric phụ thuộc vào lựa chọn này.
- **Chưa kiểm chứng usability:** chưa thử nông dân có tự gõ tên thuốc và hiểu kết quả XANH / ĐỎ / VÀNG không.
- **Chưa rõ người trả tiền và trách nhiệm pháp lý** khi thông tin sai.
- **Chi phí duy trì bảng quy định** (duyệt từng dòng, khóa dòng khi luật đổi) chưa được đo, trong khi cán bộ HTX đã quá tải.
- **Lab chưa xây hay thử sản phẩm:** bộ eval ở §7 mới dùng bảng giả lập.

**Hướng tiếp theo**

1. Phỏng vấn thêm ít nhất 5 hộ ở ít nhất 2 tỉnh trồng Thanh Long, ghi đủ thời gian, cách hỏi và nguồn cho từng buổi.
2. Audit nhật ký phun của 10 hộ pilot để có baseline M1.
3. Thử bảng tra in sẵn (chưa có AI) với 5 hộ để kiểm giả định usability.
4. Nhóm chốt thị trường đích, rồi xây bảng quy định chỉ cho các thuốc hộ pilot dùng và nhờ cán bộ HTX duyệt.
5. Hỏi HTX và bên thu mua về việc ai chịu chi phí vận hành, ai chịu trách nhiệm nội dung.
6. Thay bảng giả lập trong bộ eval §7 bằng dữ liệu thật đã duyệt và câu hỏi thật của nông dân.

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
