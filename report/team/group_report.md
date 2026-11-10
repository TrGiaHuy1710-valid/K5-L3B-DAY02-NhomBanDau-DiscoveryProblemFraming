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

-
