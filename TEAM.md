# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: NhomBanDau
- Candidate problem nhóm chọn (1 câu): HTX và nông dân trồng Thanh Long xuất khẩu thiếu hệ thống quản lý, đối chiếu tình trạng cây trồng thực tế với tiêu chuẩn dư lượng hóa chất (MRLs), dẫn đến rủi ro bị trả hàng và thiệt hại kinh tế.
- Quyết định cuối (Go / Not Yet / No-Go): Go

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 2 | Lê Hiền Hiếu | 2A202603940 | Người phản biện chính, Cố vấn AI | hieulhaiwork |
| 3 | Trần Duy Thành | 2A202603919 | Đánh giá rủi ro (Risk Assessment), Viết Problem Statement | thanh289 |
| 4 | Cao Minh Quang | 2A202603906 | Metrics, Boundary & Formatting | quang011105 |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm |Lê Hiền Hiếu  | | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Cao Minh Quang | Trần Duy Thành | Assumption map, snapshot hoặc survey |
| CP4 — Research | Cao Minh Quang | Trịnh Gia Huy | Bảng research có link |
| CP5 — Quy trình trước/sau |Lê Hiền Hiếu  | | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | Trần Duy Thành | Cả nhóm | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Cao Minh Quang | Trần Duy Thành | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Trần Duy Thành | Cao Minh Quang | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### LeHienHieu-2A202603940

**Phần việc phụ trách:**
- Dẫn dắt quá trình tổng hợp ở CP3: Điều phối việc đánh giá chéo và loại suy trực tiếp các ý tưởng để lập bảng chấm điểm chốt Candidate Problem.
- Thiết kế và chuẩn hóa quy trình ở CP5: Sơ đồ hóa luồng vận hành hiện tại và thiết kế luồng tương lai với các điểm nghẽn được xử lý.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):
- Trong bước Hội tụ nhóm, tôi đã chủ động đề xuất bỏ qua bước gom Cluster và vẽ cây OST hình thức để tiết kiệm thời gian.
- Thay vào đó, tôi đề xuất nhóm đi thẳng vào việc mổ xẻ rào cản kỹ thuật (như web chặn crawl data của app so sánh giá, RAG bị nhiễu của bot intern và scope quá nhỏ, AI tóm tắt thì không có gì hơn được NotebookLM).
- Qua đó, tôi giúp nhóm lập Bảng chấm điểm nhanh gọn và chốt dự án giám sát Thanh Long.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):
- Mục 5. Problem Statement v0 và Mục 8. Quyết định (CP6) trong `group_report.md`.
- Commit: `thanh289: fill TEAM.md`

**Điều mình học được từ phần nhóm:**
- Càng đào sâu vào một ngách hẹp (1 loại cây, 1 hợp tác xã), các rủi ro (Viability, Usability) càng dễ kiểm soát hơn là vẽ ra một "siêu ứng dụng" cho toàn ngành nông nghiệp.
- 
### Trần Duy Thành - 2A202603919

**Phần việc phụ trách:**
- Phản biện tính khả thi, đánh giá 4 rủi ro (Value, Usability, Feasibility, Viability) ở CP6.
- Đúc kết các nội dung thảo luận để viết Problem Statement.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):
- Loại bỏ các ý tưởng cào dữ liệu TMĐT vướng rào cản pháp lý (chặn API).
- Chốt bảng đánh giá rủi ro, phân định rõ ràng giữa người dùng (nông dân) và người trả tiền (HTX/Doanh nghiệp thu mua).
- Đưa ra quyết định "Go" với quy mô Pilot nhỏ nhất gọn gàng.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):
- Mục 5. Problem Statement v0 và Mục 8. Quyết định (CP6) trong `group_report.md`.
- Commit: `thanh289: fill TEAM.md`

**Điều mình học được từ phần nhóm:**
- Càng đào sâu vào một ngách hẹp (1 loại cây, 1 hợp tác xã), các rủi ro (Viability, Usability) càng dễ kiểm soát hơn là vẽ ra một "siêu ứng dụng" cho toàn ngành nông nghiệp.

### CaoMinhQuang-2A202603906

**Phần việc phụ trách:**

- Phụ trách review và hoàn thiện Mục 7 (Problem Statement v1 + tiêu chí đánh giá AI), Mục 9 (Hạn chế và hướng tiếp theo), Mục 10 (Tài liệu tham khảo) trong Báo cáo nhóm (`group_report.md`).
- Rà soát format, đối chiếu tính nhất quán của Success Metrics, Boundary và chuẩn hóa trình bày file Markdown của nhóm.
- Tham gia phản biện đa chiều ở vòng Pitching (CP3) và phụ trách nghiên cứu đối thủ cạnh tranh (Plantix, NextFarm) ở CP4.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Xây dựng bộ tiêu chí đánh giá chất lượng đầu ra AI (AI Output Evaluation) tại Mục 7: AI Vision đạt Recall ≥ 85% (nguyên tắc ưu tiên không bỏ sót bệnh), AI RAG trích xuất thông tin chất cấm chính xác 100%.
- Chuẩn hóa các chỉ số định lượng Success Metrics (rút ngắn thời gian từ 5–7 ngày xuống <2 giờ, giảm tỷ lệ vi phạm thuốc BVTV từ >20% xuống <5%) và ranh giới Boundary (Human-in-the-loop, AI chỉ cảnh báo và tra cứu, cán bộ HTX duyệt).
- Thực hiện bảng phân tích đối thủ cạnh tranh (CP4): mổ xẻ Plantix (thiếu chuẩn VietGAP và luật MRLs bản địa) và NextFarm (UI nặng nề, thiếu AI phân tích).
- Soạn thảo Mục 9 (Hạn chế về thời tiết/thổ nhưỡng và hướng mở rộng Sầu riêng, Bưởi) và Mục 10 (Danh mục tài liệu tham khảo chính thống từ DAFF Úc, MAFF Nhật, TCVN VietGAP).

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- Mục 3.3 (Bảng research giải pháp), Mục 7 (Problem Statement v1 & Eval criteria), Mục 9, Mục 10 trong `report/team/group_report.md`.
- Báo cáo cá nhân: `report/individual/2A202603906_CaoMinhQuang.md`.

**Điều mình học được từ phần nhóm:**

- Hiểu sâu sắc tư duy "Problem-first" và "Workflow-first": Không vội vã đưa AI Agent vào khi quy trình thu thập dữ liệu hiện trường chưa được chuẩn hóa và rào cản người dùng chưa được giải quyết.
- Nắm vững cách thiết lập Boundary và Metrics an toàn trong việc ứng dụng AI cho các bài toán có rủi ro kinh tế cao.
- Trải nghiệm bài học thực tế về tinh thần hợp tác nhóm: biết lắng nghe phản biện, dám từ bỏ ý tưởng cá nhân chưa tối ưu để cùng hướng tới mục tiêu chung có giá trị thực tế lớn nhất.
