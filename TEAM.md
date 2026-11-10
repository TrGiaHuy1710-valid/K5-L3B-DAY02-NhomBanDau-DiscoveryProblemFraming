# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: NhomBanDau
- Candidate problem nhóm chọn (1 câu): HTX và nông dân trồng Thanh Long xuất khẩu thiếu hệ thống quản lý, hướng dẫn chăm sóc và đối chiếu tình trạng cây trồng thực tế với tiêu chuẩn dư lượng hóa chất (MRLs), dẫn đến rủi ro bị trả hàng và thiệt hại kinh tế.
- Quyết định cuối (Go / Not Yet / No-Go): Go

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Trịnh Gia Huy | 2A202603924 | Nhóm trưởng (fork repo), đề xuất candidate problem, phụ trách §4 quy trình trước/sau (CP5) và §7 Problem Statement v1 + eval (CP6) | TrGiaHuy1710-valid |
| 2 | Lê Hiền Hiếu | 2A202603940 | Dẫn dắt hội tụ nhóm, Ghi chép, Thiết kế mức AI | hieulhaiwork |
| 3 | Trần Duy Thành | 2A202603919 | Xây dựng Problem Statement và đánh giá tính khả thi | thanh289 |
| 4 | Cao Minh Quang | 2A202603906 | Kiểm chứng vấn đề và nghiên cứu giải pháp hiện có | quang011105 |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Lê Hiền Hiếu | Cả nhóm | Clustering, OST, Bảng chấm điểm |
| CP4 — Kiểm chứng | Cao Minh Quang | Trịnh Gia Huy, Trần Duy Thành | Assumption map, snapshot hoặc survey |
| CP4 — Research | Cao Minh Quang | Trịnh Gia Huy | Bảng research có link |
| CP5 — Quy trình trước/sau | Trịnh Gia Huy | Lê Hiền Hiếu | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | Trần Duy Thành | Cả nhóm | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Lê Hiền Hiếu | Trịnh Gia Huy | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Trần Duy Thành | Cao Minh Quang | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### TrinhGiaHuy-2A202603924

**Phần việc phụ trách:**

- Nhóm trưởng: fork repo, quản lý repo chung của nhóm.
- Đề xuất Candidate C được nhóm chọn ở CP3: tra cứu kiến thức chăm sóc Thanh Long và quy định sử dụng thuốc, hóa chất phục vụ xuất khẩu.
- Người phụ trách §4 (CP5): quy trình hiện tại, quy trình tương lai, bảng before/after.
- Người phụ trách §7 (CP6): Problem Statement v1 và tiêu chí đánh giá đầu ra AI.
- Hỗ trợ Quang research giải pháp đã có ở CP4.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch hướng bài toán Thanh Long (Candidate C); trả lời phản biện về scope, mức cần AI và đối thủ có sẵn.
- Phản biện 3 candidate còn lại (tóm tắt slide, so sánh mua hàng, hỗ trợ intern) bằng câu hỏi về đối thủ có sẵn, người trả tiền và có cần AI không.
- Research Plantix, mobiAgri, NextFarm, Agrio; tìm văn bản quy định thuốc BVTV (Thông tư 75/2025/TT-BNNMT) và MRL của Úc (Schedule 20).
- §4: viết quy trình hiện tại với actor primary / secondary, bottleneck đề xuất; quy trình tương lai tách bước AI / Rule / con người, boundary, phương án quay về; bảng before/after và bộ metric M1–M3 để §5, §7, §8 dùng chung. Các ô chưa có dữ liệu để [PENDING CP4], không tự tạo số liệu.
- §7: bản nháp Problem Statement v1 và 5 tiêu chí eval (2 tiêu chí chặn: đúng con số về thuốc, biết từ chối và chuyển người).

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- Mục 4 và Mục 7 trong `report/team/group_report.md`.
- Báo cáo cá nhân: `report/individual/2A202603924_TrinhGiaHuy.md` (mục 3 "Idea sau phản biện", mục 4).
- Commit: `2A202603924 individual report`, `2A202603924 individual report v2`, `Add and update 2A202603924_TrinhGiaHuy.md`, `Add and update 2A202603924_TrinhGiaHuy.md and my role in team`.

**Điều mình học được từ phần nhóm:**

- *(Huy tự điền)*

### LeHienHieu-2A202603940

**Phần việc phụ trách:**
- Dẫn dắt quá trình tổng hợp ở CP3: Điều phối việc đánh giá chéo và loại suy trực tiếp các ý tưởng để lập bảng chấm điểm chốt Candidate Problem.
- Thiết kế và chuẩn hóa quy trình ở CP5: Sơ đồ hóa luồng vận hành hiện tại và thiết kế luồng tương lai với các điểm nghẽn được xử lý.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):
- Trong bước Hội tụ nhóm, tôi đã chủ động đề xuất bỏ qua bước gom Cluster và vẽ cây OST hình thức để tiết kiệm thời gian.
- Thay vào đó, tôi đề xuất nhóm đi thẳng vào việc mổ xẻ rào cản kỹ thuật (như web chặn crawl data của app so sánh giá, RAG bị nhiễu của bot intern và scope quá nhỏ, AI tóm tắt thì không có gì hơn được NotebookLM). Qua đó, tôi giúp nhóm lập Bảng chấm điểm nhanh gọn và chốt dự án giám sát Thanh Long.
- Ở CP5, tôi vẽ sơ đồ quy trình 4 bước

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):


**Điều mình học được từ phần nhóm:**



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

- Phụ trách chính §3.1 (Assumption Map) và §3.2 (Kiểm chứng / Validation) trong Báo cáo nhóm (`group_report.md`).
- Phụ trách chính §3.3 (Research giải pháp hiện có: Ứng dụng Thuốc BVTV của Cục BVTV, mobiAgri, Cổng SPS Việt Nam & EU Pesticides Database).
- Tổng hợp và hoàn thiện §10 (Tài liệu tham khảo) với các nguồn chính thống từ cơ quan quản lý nhà nước và quốc tế.
- Hỗ trợ nhóm rà soát tính nhất quán về dữ liệu đầu vào (bằng chứng phỏng vấn, số liệu thiệt hại thực tế, rào cản MRLs xuất khẩu) để làm căn cứ cho quy trình As-Is (§4) và Problem Statement v0 (§5).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Xây dựng Assumption Map (§3.1) gồm 5 giả định bao phủ 4 khía cạnh Value, Usability, Feasibility, Viability theo nguyên tắc Farmer-first, Cooperative-supported.
- Thực hiện 2 cuộc phỏng vấn sâu (§3.2) với nông dân trực tiếp canh tác thanh long (chú B., Tiền Giang) và cán bộ kỹ thuật HTX (anh T.), thu thập các dữ kiện thật về hành vi đã xảy ra (thiệt hại 50 triệu/vụ do dính chất cấm EU, khó khăn khi đọc nhãn thuốc, thói quen phụ thuộc đại lý).
- Tổng hợp bảng tín hiệu xác nhận và phản bác (§3.2), rút ra bài học giúp nhóm sửa định hướng bài toán: trao công cụ tự tra cứu thuốc cho nông dân, HTX giữ vai trò bảo chứng xác minh.
- Phân tích chi tiết 3 giải pháp hiện có (§3.3) với link uy tín, chỉ ra rõ khoảng trống cốt lõi (thiếu dữ liệu MRLs xuất khẩu, thuật ngữ tiếng Anh phức tạp) để định vị bài học thiết kế cho nhóm.
- Tổng hợp danh mục 7 tài liệu tham khảo chính thống (§10) từ Cục BVTV, Văn phòng SPS Việt Nam, Quy định EU 2019/1793, DAFF Úc, MAFF Nhật Bản, VietGAP TCVN 11892-1:2017.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- Section 3: §3.1 (Assumption Map), §3.2 (Kiểm chứng & Interview Snapshots), §3.3 (Bảng research giải pháp hiện có) trong `report/team/group_report.md`.
- Section 10: §10 (Tài liệu tham khảo tổng hợp) trong `report/team/group_report.md`.
- Báo cáo cá nhân: `report/individual/2A202603906_CaoMinhQuang.md`.

**Điều mình học được từ phần nhóm:**

- Hiểu sâu sắc phương pháp kiểm chứng (Validation) trong Discovery: Phải hỏi về hành vi và sự việc ĐÃ XẢY RA trong quá khứ kèm con số thiệt hại thực tế, tuyệt đối không hỏi câu hỏi giả định ("Bạn có muốn...").
- Nắm vững nguyên tắc Dependency giữa các section: Dữ liệu từ khâu Research & Validation (CP4) là nền móng bắt buộc để xây dựng quy trình thực tế (CP5) và viết Problem Statement sắc bén, không được để các phần sau tự tạo số liệu.
- Học được tư duy Farmer-first: Thiết kế giải pháp cho nông dân phải giải quyết đúng nút thắt tâm lý (sợ bị trừ tiền nhưng ngại nhập liệu phức tạp), biến công nghệ thành công cụ tra cứu tức thì thay vì một phần mềm quản lý hành chính cồng kềnh.
