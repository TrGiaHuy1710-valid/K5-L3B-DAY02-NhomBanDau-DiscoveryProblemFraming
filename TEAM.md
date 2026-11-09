# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm:
- Candidate problem nhóm chọn (1 câu):
- Quyết định cuối (Go / Not Yet / No-Go):

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |
| 4 | | | | |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | | | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | | | Assumption map, snapshot hoặc survey |
| CP4 — Research | | | Bảng research có link |
| CP5 — Quy trình trước/sau | | | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | | | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | | | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | | | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

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
