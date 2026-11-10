# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |
| 8 | | | | | |
| 9 | | | | | |
| 10 | | | | | |
| 11 | | | | | |
| 12 | | | | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

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
