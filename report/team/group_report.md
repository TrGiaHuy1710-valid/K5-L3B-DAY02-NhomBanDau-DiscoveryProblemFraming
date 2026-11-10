# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: NhomBanDau
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Người trồng thanh long gặp khó khăn trong việc tiếp cận hoặc xác minh thông tin chăm sóc cây, đặc biệt là các quy định và hướng dẫn liên quan đến thuốc, hóa chất phục vụ xuất khẩu.
- Quyết định cuối: **Not Yet**

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
| 6 | Trần Duy Thành | Khi quản lý công việc, tôi muốn gom việc từ tin nhắn, email và ghi chú về một danh sách để không bỏ sót đầu việc. | Người đi làm có nhiều kênh trao đổi | Sao chép và sắp xếp công việc từ nhiều ứng dụng khác nhau. | CaoMinhQuang, TrinhGiaHuy, LeHienHieu |
| 7 | Trịnh Gia Huy | Khi chăm sóc thanh long, tôi muốn biết chính xác quy định về thuốc và hóa chất để sản phẩm đạt tiêu chuẩn xuất khẩu. | Người trồng thanh long | Tìm, đối chiếu quy định xuất khẩu và hướng dẫn sử dụng thuốc. | CaoMinhQuang, TranDuyThanh, LeHienHieu |
| 8 | Trịnh Gia Huy | Khi thanh long có biểu hiện lạ, tôi muốn biết ngay cách xử lý an toàn để không ảnh hưởng đến chất lượng trái. | Người trồng thanh long | Phân biệt dấu hiệu và tra cứu cách xử lý phù hợp. | CaoMinhQuang, TranDuyThanh, LeHienHieu |
| 9 | Trịnh Gia Huy | Khi mua thuốc bảo vệ thực vật, tôi muốn kiểm tra thuốc có nằm trong danh mục được phép dùng hay không. | Người trồng thanh long | Tra cứu danh mục thuốc được phép và thời gian cách ly theo thị trường. | CaoMinhQuang, TranDuyThanh, LeHienHieu |
| 10 | Lê Hiền Hiếu | Khi intern gặp lỗi môi trường, tôi muốn tự xử lý được các lỗi phổ biến để không làm gián đoạn công việc của mentor. | Intern phần mềm | Tìm giải pháp phù hợp với ngữ cảnh dự án thay vì tra cứu chung chung. | CaoMinhQuang, TranDuyThanh, TrinhGiaHuy |
| 11 | Lê Hiền Hiếu | Khi bắt đầu dự án mới, tôi muốn dựng môi trường đúng tài liệu để có thể chạy thử trong ngày đầu. | Lập trình viên mới vào dự án | Đọc tài liệu dài, thiếu cập nhật và thiếu các bước cấu hình thực tế. | CaoMinhQuang, TranDuyThanh, TrinhGiaHuy |
| 12 | Lê Hiền Hiếu | Khi cập nhật thư viện bị lỗi, tôi muốn biết nguyên nhân do xung đột phiên bản hay sai cấu hình để sửa nhanh. | Lập trình viên | Đọc log lỗi dài và thử nhiều cách sửa không có định hướng. | CaoMinhQuang, TranDuyThanh, TrinhGiaHuy |

### 2.2. Gom cụm (Clustering)

| Cụm | Nhãn cụm | Các ý thuộc cụm (số #) | Insight từ cụm |
|---:|---|---|---|
| A | Hỗ trợ học tập và ôn thi cho sinh viên | #1, #2, #3 | Sinh viên tốn nhiều thời gian tổng hợp slide, tạo câu hỏi tự kiểm tra và đối chiếu nội dung ôn tập. Vấn đề có tần suất cao vào mùa thi, tuy nhiên đã có nhiều công cụ tạo tóm tắt và câu hỏi từ tài liệu nên giải pháp dễ trùng lặp. |
| B | Quản lý thông tin cá nhân và hỗ trợ quyết định mua sắm | #4, #5, #6 | Người dùng phân tán dữ liệu ở nhiều kênh, mất thời gian gom việc, tổng hợp chi tiêu hoặc so sánh sản phẩm. Nhu cầu phân tích rõ ràng nhưng khó chuẩn hóa cấu trúc dữ liệu đầu vào và phụ thuộc vào API hoặc quyền truy cập tài khoản. |
| C | Hỗ trợ người trồng thanh long tra cứu kiến thức và quy định xuất khẩu | #7, #8, #9 | Người trồng khó tiếp cận và xác minh thông tin thuốc BVTV theo tiêu chuẩn xuất khẩu. Rủi ro sai sót lớn, có thể dẫn đến thiệt hại kinh tế cao nếu vi phạm dư lượng hóa chất. Thị trường thiếu công cụ tra cứu tích hợp giữa quy định trong nước và nước nhập khẩu. |
| D | Hỗ trợ lập trình viên xử lý lỗi môi trường và tài liệu kỹ thuật | #10, #11, #12 | Lập trình viên mới mất nhiều thời gian cấu hình môi trường và sửa lỗi phát sinh. Vấn đề mang tính kỹ thuật cao, dễ kiểm tra đúng sai nhưng ngữ cảnh từng dự án rất khác nhau, phụ thuộc lớn vào tài liệu nội bộ và quyền truy cập mã nguồn. |

- **Ý tưởng bị loại bỏ từ sớm:** Các ý tưởng thuộc nhóm Quản lý chi tiêu và So sánh mua sắm online (#4, #5) bị loại bỏ sớm do rào cản kỹ thuật thu thập dữ liệu (các sàn thương mại điện tử chặn cào dữ liệu) và phạm vi quá rộng, khó triển khai trong khuôn khổ bài lab.

### 2.3. Opportunity Solution Tree rút gọn

- **Outcome:** Người dùng xác minh được thông tin kỹ thuật chính xác để giảm thiểu rủi ro trong công việc hoặc hoạt động sản xuất.
  - **Opportunity 1:** Người trồng thanh long cần biết thuốc BVTV dự định dùng có được phép xuất khẩu sang thị trường mục tiêu hay không.
    - *Candidate solution:* Tra cứu danh mục thuốc kết hợp kiểm tra chéo quy định xuất khẩu (Được chọn để phát triển).
  - **Opportunity 2:** Sinh viên cần rút ngắn thời gian chuẩn bị tài liệu ôn thi từ bài giảng số lượng lớn.
    - *Candidate solution:* Tạo đề cương tự động từ slide (Bị loại do trùng lặp với công cụ sẵn có).
  - **Opportunity 3:** Intern cần giải quyết lỗi môi trường nhanh mà không phụ thuộc hoàn toàn vào mentor.
    - *Candidate solution:* Trợ lý tra cứu lỗi dựa trên tài liệu dự án (Bị loại do khó thu thập ngữ cảnh nội bộ).

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

**Vì sao chọn:** Mặc dù có tổng điểm thấp nhất, điểm trừ chủ yếu nằm ở việc nhóm chưa có sẵn kiến thức chuyên ngành và quy trình ban đầu chưa được định hình rõ, nhưng bài toán này có lợi thế độc quyền rất mạnh: thị trường chưa có công cụ kiểm tra chéo luật hóa chất xuất khẩu. Những điểm yếu về Quy trình và Hiểu domain có thể bù đắp thông qua bước Research (CP4) và Thiết kế Workflow (CP5). Bài toán có tính thực tiễn cao, giải quyết nỗi đau thiệt hại kinh tế lớn và tạo ra một MVP rất trực quan kết hợp giữa bảng luật chuẩn và hỗ trợ ngôn ngữ.

**Vì sao loại các candidate còn lại:**
- Cao Minh Quang (Tóm tắt slide): Điểm số cao nhất vì bài toán quá gần gũi với sinh viên, nhưng bị loại do hoàn toàn không có tính mới. Các công cụ như Google NotebookLM hay ChatGPT hiện tại đã giải quyết quá xuất sắc việc đọc và tóm tắt PDF. Nếu làm nhóm dễ rơi vào tình trạng không tạo ra được giá trị cạnh tranh nào.
- Trần Duy Thành (Đối chiếu mua sắm online): Bị loại vì nhóm nhận định đây là một ý tưởng có rào cản công nghệ khá lớn. Rào cản kỹ thuật chủ yếu nằm ở các sàn TMĐT (Shopee, Lazada, Tiki) đều có cơ chế chặn crawler và đóng API. Ngoài ra nhóm chưa có kinh nghiệm xử lý API của Facebook Market hay Tiktok Shop và các trang tương tự.
- Lê Hiền Hiếu (Giảm phụ thuộc mentor): Bị loại do nhóm thấy đây là một dự án khá phức tạp. Rào cản lớn nhất nằm ở tính bảo mật dữ liệu của doanh nghiệp và sự khó khăn trong việc thu thập đủ dataset để xây dựng hệ thống RAG chuẩn xác. Ngoài ra, tệp người dùng quá ngách, khó có khả năng upscale và thương mại hóa tốt.

**Xử lý bất đồng (nếu có):** Nhóm đã thảo luận kỹ lưỡng và thống nhất lựa chọn bài toán hỗ trợ người trồng thanh long vì giá trị thực tế và khả năng định hình một workflow kiểm soát rủi ro chặt chẽ.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

*(Phụ trách chính: Cao Minh Quang)*

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Người trồng thanh long có nhu cầu chủ động tự tra cứu và xác minh thuốc BVTV/quy định xuất khẩu trước khi phun, thay vì chỉ phụ thuộc hoàn toàn vào tư vấn của đại lý bán thuốc. | Value | 5 | 1 | Có (Ưu tiên số 1) |
| 2 | Hộ nông dân (độ tuổi trung niên, ít thành thạo công nghệ) có thể tự sử dụng một công cụ tra cứu số đơn giản (gõ tên thương mại tiếng Việt hoặc giọng nói) để hiểu đúng hoạt chất và thời gian cách ly (PHI). | Usability | 5 | 1 | Có (Ưu tiên số 2) |
| 3 | Có thể xây dựng cơ sở dữ liệu ánh xạ (mapping) chính xác giữa hàng nghìn tên thương mại thuốc BVTV lưu hành tại Việt Nam với tên hoạt chất hóa học và ngưỡng MRLs của các thị trường xuất khẩu đích. | Feasibility | 4 | 3 | Có (Đã kiểm tra nguồn luật) |
| 4 | Nông dân tin tưởng thông tin khuyến cáo từ công cụ số đủ để thay đổi hành vi canh tác và lựa chọn thuốc thực tế. | Usability / Value | 4 | 1 | Có |
| 5 | HTX sẵn sàng đóng vai trò điểm tựa (hỗ trợ xác minh chuyên môn và bảo chứng vùng trồng) mà không cần can thiệp trực tiếp vào từng lượt tra cứu hàng ngày của nông dân. | Viability | 4 | 2 | Không |

*Giả định nhóm cần kiểm chứng:* Giả định 1 (Nhu cầu tự tra cứu thực sự của nông dân) và Giả định 2 (Khả năng tiếp cận công nghệ). Hiện tại các giả định về hành vi người dùng mới chỉ ở mức bằng chứng 1/5 (chưa có khảo sát thực tế).

### 3.2. Kiểm chứng

**Thực trạng kiểm chứng tại CP4:**

> **Do giới hạn thời gian của buổi Lab và việc chưa tiếp cận được đúng đối tượng người dùng, nhóm chưa hoàn thành phỏng vấn/survey trực tiếp với nông dân trồng thanh long và cán bộ HTX. Vì vậy, những pain point và quy trình hiện tại nhóm đưa ra vẫn là giả thuyết hình thành từ quá trình research, chưa được kiểm chứng bằng hành vi thực tế.**

Để đảm bảo tính liêm chính học thuật (không bịa đặt số liệu phỏng vấn người dùng theo đúng Rubric C7), nhóm đã:
1. Đánh giá lại toàn bộ các giả định về người dùng ở mức "chưa có bằng chứng thực tế" (1/5).
2. Xây dựng một kế hoạch kiểm chứng thực địa chi tiết để thực hiện sau buổi Lab: [`report/assets/cp4-validation-plan.md`](../assets/cp4-validation-plan.md) (bao gồm tiêu chí chọn mẫu 5–8 hộ nông dân, 2 cán bộ HTX, 2 đại lý thuốc; bộ câu hỏi phỏng vấn chuẩn Discovery không dẫn dụ; và tiêu chí chuyển đổi trạng thái quyết định).

**Dữ kiện đã được kiểm chứng thông qua Desk Research (Tài liệu thứ cấp chính thống):**

| Nguồn tài liệu | Dữ kiện xác thực | Tác động đến bài toán của nhóm |
|---|---|---|
| Báo cáo giám sát từ Cục BVTV & Văn phòng SPS Việt Nam | Thanh long Việt Nam liên tục nằm trong danh sách kiểm soát tăng cường tại EU (theo Quy định EU 2019/1793) với tần suất kiểm tra 30–50% do phát hiện dư lượng hoạt chất (Carbendazim, Dithiocarbamates, Difenoconazole). | Xác thực tầm quan trọng vĩ mô của vấn đề: rủi ro vi phạm dư lượng hóa chất xuất khẩu là có thật và gây thiệt hại kinh tế nghiêm trọng cho ngành hàng. |
| Hệ thống tra cứu quy chuẩn MRLs quốc tế (EU Pesticides Database, DAFF Úc, MAFF Nhật) | Danh mục MRLs liên tục cập nhật, sử dụng thuật ngữ hóa học tiếng Anh và mã hóa ngưỡng mg/kg kỹ thuật cao; không có sự liên kết trực tiếp với tên thương phẩm thuốc bán tại thị trường VN. | Xác thực khoảng trống thông tin: Nông dân và HTX thiếu một công cụ "thông dịch" từ tên thuốc mua ngoài tiệm sang ngưỡng an toàn xuất khẩu. |

**Nhóm đã sửa định hướng problem thế nào sau research:**
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
> Toàn bộ quy trình, bottleneck và metric dưới đây là **giả thuyết cần kiểm chứng** hình thành từ desk research. Baseline chính thức sẽ được đo lường thực tế trong đợt kiểm chứng hiện trường theo kế hoạch [`report/assets/cp4-validation-plan.md`](../assets/cp4-validation-plan.md).

### 4.1. Quy trình hiện tại

**Actor**

| Actor | Vai trò trong quy trình | Căn cứ |
|---|---|---|
| Hộ nông dân trồng Thanh Long | Primary actor: người cần thông tin và trực tiếp chọn thuốc, phun | Chốt ở CP3; đối tượng người dùng chính cần kiểm chứng hành vi |
| Đại lý thuốc BVTV | Nguồn thông tin chính khi nông dân chọn thuốc | Giả thuyết thực tế canh tác theo phản ánh ngành |
| Cán bộ kỹ thuật HTX | Secondary actor: phổ biến danh mục thuốc, trả lời câu hỏi, lấy mẫu kiểm trước thu hoạch | Đối tượng hỗ trợ chuyên môn và kiểm duyệt |

Sơ đồ:

```text
(1) Nông dân thấy sâu bệnh / đến đợt chăm sóc
        |
        v
(2) Ra đại lý thuốc quen, mua theo đại lý chỉ                       <== BOTTLENECK [Giả thuyết cần kiểm chứng]
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
| 1 | Nông dân | Quan sát vườn | Cần xử lý sâu bệnh | [Giả thuyết] Ước tính 3–4 lần mỗi vụ phải đắn đo chọn thuốc | Cần đo đạc thực tế |
| 2 | Nông dân, đại lý thuốc | Triệu chứng, lời khuyên của đại lý | Chai thuốc đã mua | [Giả thuyết] Mất 1–2 ngày đắn đo, vừa mua vừa lo | Nông dân khó tự đọc hiểu hoạt chất trên bao bì |
| 3 | Nông dân → cán bộ HTX | Tên thuốc | Câu hỏi qua điện thoại | Không thường xuyên; nông dân chủ yếu tin đại lý [giả thuyết] | Không phải lần nào cũng hỏi |
| 4 | Cán bộ HTX | Danh mục thuốc VN, quy định MRL nước nhập khẩu | Trả lời từng người; tài liệu phổ biến | [Giả thuyết] Ước tính mất 2–3 ngày mỗi tháng để soạn tài liệu và trả lời cuộc gọi; cán bộ mỏng so với số hộ | Quy định MRL thay đổi thường xuyên |
| 5 | Nông dân | Thuốc, cách pha | Lần phun | — | Theo lịch mùa vụ |
| 6 | HTX / thương lái | Mẫu trái | Lô đạt hoặc không đạt | [Giả thuyết] Nguy cơ lô hàng bị loại khỏi luồng xuất khẩu do vi phạm MRLs, bán nội địa giá thấp | Phát hiện quá muộn khi thuốc đã phun |

**Bottleneck chính [Giả thuyết cần kiểm chứng]:** bước 2. Nông dân quyết định chọn thuốc tại đại lý mà **không có cách tự kiểm tra ngay** thuốc đó có được dùng cho thị trường xuất khẩu không và phải cách ly bao nhiêu ngày. Kênh xác minh duy nhất là cán bộ HTX (bước 3–4), nhưng đội ngũ cán bộ không thể trả lời kịp cho toàn bộ xã viên. Vi phạm chỉ lộ ra ở bước 6, khi không còn sửa được.

- Căn cứ: Giả thuyết hình thành từ desk research và tài liệu ngành (chưa được kiểm chứng qua phỏng vấn thực địa, xem validation plan tại [`report/assets/cp4-validation-plan.md`](../assets/cp4-validation-plan.md)).
- Giới hạn: Toàn bộ số liệu thời gian và tần suất trên là giả thuyết cần kiểm chứng; chưa có baseline chính thức.

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
| Thời gian nông dân có được câu trả lời đã xác minh | [Giả thuyết cần kiểm chứng, ước tính 1–2 ngày; chờ đo thực tế] | Dưới 1 phút với thuốc có trong bảng; câu VÀNG trong ngày làm việc | Cần đo đạc thực tế trên nông dân |
| Thời gian cán bộ HTX trả lời và soạn tài liệu | [Giả thuyết cần kiểm chứng, ước tính 2–3 ngày/tháng; chờ đo thực tế] | Giảm ≥ 50%, chỉ còn câu VÀNG và duyệt bảng | Duyệt bảng là việc mới, cần đo thêm |
| Số bước thủ công | 6 (mọi bước do người làm) | 2 trong luồng tra (chọn thuốc, quyết định) + bước duyệt bảng khi có văn bản mới | |
| Bottleneck chính | Chọn thuốc tại đại lý mà không tự xác minh được; cán bộ không kịp trả lời | Chuyển thành việc **duy trì bảng quy định đã duyệt** | |
| Thời điểm phát hiện vi phạm | Sát thu hoạch (bước 6), khi đã phun | Trước khi mua và phun | Đây là thay đổi quan trọng nhất |
| Rủi ro mới phát sinh | — | (1) AI gợi ý nhầm tên thuốc gần giống; (2) bảng lỗi thời khi quy định đổi; (3) nông dân tin máy quá mức, bỏ qua nhãn; (4) cán bộ quá tải câu VÀNG; (5) chi phí duy trì bảng | Kiểm soát bằng boundary, phương án quay về ở 4.2 và eval ở §7 |

**Metric dùng thống nhất cho §5, §7, §8:**

| # | Metric | Baseline | Target | Cách đo |
|---:|---|---|---|---|
| M1 | % lần phun của hộ pilot dùng thuốc ở trạng thái XANH cho thị trường đích, đủ thời gian cách ly | [Chưa có baseline, chờ đo đạc nhật ký canh tác theo validation plan] | ≥ 95% và 0 lần dùng thuốc trạng thái ĐỎ | Cán bộ audit nhật ký mỗi 2 tuần |
| M2 | Thời gian từ lúc nông dân có câu hỏi đến lúc có thông tin đã xác minh | [Chưa có baseline, chờ đo đạc thực tế theo validation plan] | Dưới 1 phút (XANH / ĐỎ); trong ngày làm việc (VÀNG) | Log công cụ; bấm giờ khi khảo sát |
| M3 | % kết quả về thuốc khớp bảng đã duyệt và có nguồn | Không áp dụng | 100% | Bộ eval §7 |
| M4 | Thời gian cán bộ HTX trả lời câu hỏi và soạn tài liệu mỗi tháng | [Chưa có baseline, chờ đo đạc thực tế theo validation plan] | Giảm ≥ 50% | Cán bộ tự ghi |
| M5 (kết quả trễ) | Số lô hoặc hộ pilot bị loại vì dư lượng | [Chưa có baseline, chờ đo đạc thực tế theo validation plan] | 0 trường hợp do thuốc trạng thái ĐỎ | Kết quả kiểm mẫu của HTX / thương lái |

---

## 5. Problem Statement v0 (CP5)

> Người phụ trách: Trần Duy Thành. Bản v0 viết ở CP5, **trước khi** chọn mức can thiệp AI, nên chưa có "AI intervention point". Các trường khớp với actor, quy trình hiện tại, bottleneck và metric ở §4 (Dependency C). Toàn bộ bottleneck, impact và baseline được ghi nhận là giả thuyết cần kiểm chứng thực địa.

| Trường | Nội dung |
|---|---|
| **Actor** | Primary: Hộ nông dân trồng Thanh Long bán vào kênh xuất khẩu, người trực tiếp chọn và phun thuốc. Secondary: Cán bộ kỹ thuật HTX, người phổ biến danh mục thuốc và trả lời câu hỏi (§4.1). |
| **Quy trình** | Thấy sâu bệnh → Ra đại lý mua thuốc theo lời đại lý chỉ → (Đôi khi) gọi cán bộ HTX hỏi → Cán bộ tra danh mục thuốc và quy định của nước nhập khẩu → Nông dân phun → HTX / thương lái kiểm mẫu sát thu hoạch (§4.1). |
| **Bottleneck** | **[Giả thuyết cần kiểm chứng]** Bước chọn thuốc tại đại lý: Nông dân không tự kiểm tra được thuốc đó có được dùng cho trái xuất khẩu không và cách ly bao nhiêu ngày. Bao bì ghi tên hoạt chất khó hiểu; kênh xác minh duy nhất là cán bộ HTX nhưng lực lượng mỏng, không thể hỗ trợ tức thời mọi lúc (§4.1). |
| **Impact** | **[Giả thuyết cần kiểm chứng]** Vi phạm chỉ lộ ra khi kiểm mẫu sát thu hoạch, lúc đã phun xong. Rủi ro nông sản bị loại khỏi luồng xuất khẩu, phải bán đổ bán tháo tại thị trường nội địa với giá rẻ mạt, gây thiệt hại tài chính nặng nề cho nông dân và uy tín HTX. Cán bộ HTX mất nhiều thời gian trả lời lặp đi lặp lại. |
| **Success Metric** (baseline → target, cách đo) | - **M1:** % lần phun dùng thuốc được phép cho thị trường đích, đủ thời gian cách ly. Baseline: [Chưa có baseline, chờ đo đạc thực tế] $\rightarrow$ Target đề xuất: $\ge 95\%$; đo bằng audit nhật ký phun.<br>- **M2:** Thời gian từ lúc có câu hỏi đến lúc có thông tin đã xác minh. Baseline: [Chờ đo đạc thực tế] $\rightarrow$ Target: Dưới 1 phút (thuốc trong bảng), trong ngày (câu VÀNG); đo bằng log hệ thống.<br>- **M4:** Thời gian cán bộ HTX trả lời và soạn tài liệu. Baseline: [Chờ đo đạc thực tế] $\rightarrow$ Target: Giảm $\ge 50\%$; đo bằng tự ghi nhận. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | Mọi giải pháp không được quyết định thay nông dân việc dùng thuốc và không được kết luận một thuốc "đạt chuẩn xuất khẩu" khi chưa có nguồn chính thức. Cán bộ kỹ thuật HTX phải kiểm tra khi thông tin thiếu, mâu thuẫn hoặc là thuốc mới. |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

| # | Phản biện (nguồn: AI rà soát v0, chỉ hỏi lỗ hổng) | Nhóm có đồng ý không | Xử lý |
|---:|---|---|---|
| 1 | Boundary còn chung chung: chưa nói rõ AI không được tự đưa ra con số liều, thời gian cách ly hay trạng thái được phép / không được phép | Đồng ý | v1 (§7) tách rõ: kết luận do Rule trên bảng đã duyệt, AI chỉ diễn đạt lại |
| 2 | M1 chưa có baseline; M2 và M4 chưa có số liệu thực địa, chưa đủ làm baseline | Đồng ý | Không tự tạo baseline giả; đánh dấu là giả thuyết và chờ đo đạc trong kế hoạch kiểm chứng ([`report/assets/cp4-validation-plan.md`](../assets/cp4-validation-plan.md)) trước khi xem xét pilot (§8.2) |
| 3 | "Thị trường đích" chưa xác định: bằng chứng ở §3 nói về EU, còn pilot cũ ghi Úc | Đồng ý | Chốt 1 thị trường đích trong đợt kiểm chứng (§8.2) và lập bảng quy định cho thị trường đó |

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

### 6.2. So sánh bốn mức can thiệp

| Tiêu chí | No AI (Sổ tay/bảng tra in sẵn) | Rule-based thuần túy | Workflow kết hợp Rule + AI | Autonomous AI Agent |
|---|---|---|---|---|
| **Cách hoạt động** | Cán bộ kỹ thuật HTX biên soạn sổ tay hoặc tờ rơi danh mục thuốc; nông dân tự lật tìm thủ công | Phần mềm tra cứu theo từ khóa chính xác (Exact match), bảng điều kiện If-Else cố định | AI phân loại câu hỏi và chuẩn hóa tên thương mại $\rightarrow$ Rule tra bảng MRLs đã duyệt $\rightarrow$ AI diễn đạt kết quả dễ hiểu (HITL xử lý ngoại lệ) | Agent tự lập kế hoạch nhiều bước, tự động duyệt web/cào dữ liệu luật quốc tế và tự ra quyết định khuyến nghị thuốc |
| **Ưu điểm** | Không tốn chi phí công nghệ; không rủi ro kỹ thuật; dễ in ấn phát hành | Dữ liệu tuyệt đối chính xác; kết quả có thể giải thích 100%; tốc độ phản hồi tức thì | Xử lý được phương ngữ/tên gõ sai của nông dân; bảo đảm 100% tính chính xác của dữ liệu thuốc nhờ Rule; có kiểm duyệt HITL an toàn | Tự động hóa cao nhất; có khả năng xử lý linh hoạt mọi tình huống phức tạp mà không cần người can thiệp |
| **Nhược điểm** | Tờ rơi dễ rách, ướt, thất lạc; không cập nhật kịp khi luật MRLs quốc tế đổi 6 tháng/lần | Nông dân gõ sai chính tả hoặc gõ tên thương mại khác tên hoạt chất thì hệ thống báo lỗi, không tìm thấy kết quả | Đòi hỏi cán bộ HTX phải duy trì và kiểm duyệt bảng dữ liệu đầu vào định kỳ | Nguy cơ ảo giác (Hallucination) cực kỳ nguy hiểm trong bài toán hóa chất độc hại; không thể giải trình pháp lý |
| **Phù hợp không?** | Dùng làm phương án đối chứng (No-AI baseline test) ở bước kiểm chứng | Không đủ linh hoạt cho giao diện người dùng nông dân | **Phù hợp nhất** (Phương án đề xuất của nhóm) | Không phù hợp, rủi ro pháp lý và an toàn vượt tầm kiểm soát |

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung chi tiết |
|---|---|
| **Prediction** — AI dự đoán điều gì? | (1) Dự đoán tên thương mại chuẩn từ câu hỏi gõ sai chính tả hoặc viết tắt của nông dân.<br>(2) Dự đoán ý định câu hỏi (tra cứu thuốc, hỏi kỹ thuật chăm sóc, hay câu ngoài phạm vi). |
| **Judgment** — Đánh giá giá trị và chi phí rủi ro | Việc xác định thuốc có được phép xuất khẩu hay không **không** thuộc thẩm quyền phán đoán của AI; thuộc về Rule đối chiếu trên bảng dữ liệu do cán bộ HTX phê duyệt. Chi phí rủi ro khi AI phán đoán sai tên thuốc là cực cao (dẫn đến nguy cơ vi phạm dư lượng). |
| **Action** — Hành động hệ thống thực hiện | Trả về kết quả: Đèn XANH (Được phép, kèm liều và số ngày cách ly PHI), Đèn ĐỎ (Cấm/Không có MRLs), hoặc Đèn VÀNG (Chưa xác minh, tự động chuyển cán bộ HTX hỗ trợ qua kênh HITL). |
| **Outcome** — Kết quả mong đợi | Nông dân nhận được hướng dẫn an toàn, rõ ràng trong vòng dưới 1 phút; cán bộ HTX giảm tải công việc trả lời lặp lại; tỷ lệ tuân thủ MRLs trong vùng trồng đạt chuẩn xuất khẩu. |
| **Input** — Dữ liệu đầu vào cần thiết | Tên thuốc do nông dân nhập (văn bản hoặc giọng nói); thị trường xuất khẩu mục tiêu (mặc định theo vùng trồng HTX); Cơ sở dữ liệu danh mục thuốc Cục BVTV và bảng MRLs đã duyệt. |
| **Feedback** — Thu thập phản hồi để cải tiến | Ghi nhận phản hồi trực tiếp của nông dân (Đã hiểu / Chưa hiểu); log các trường hợp đèn VÀNG chuyển người để cán bộ cập nhật bảng tra; kết quả audit định kỳ nhật ký phun thuốc. |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**?: Chọn: Augment - hỗ trợ ra quyết định, không tự động quyết định thay người dùng. Lý do:
  - Nông dân cần sự hỗ trợ nhanh chóng để giải mã các thông tin kỹ thuật phức tạp trên chai thuốc và quy chuẩn xuất khẩu, nhưng họ cần giữ quyền tự chủ và trách nhiệm đối với mùa màng của mình.
  - Cán bộ kỹ thuật HTX muốn giảm bớt áp lực tư vấn thủ công lặp lại nhưng bắt buộc phải nắm quyền kiểm soát đối với tính an toàn của thông tin phổ biến trong vùng trồng.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: Ưu tiên kiểm soát lỗi **báo nhầm** (False Positive - khẳng định sai rằng một loại thuốc là an toàn/được phép dùng khi thực tế bị cấm hoặc vượt ngưỡng MRLs).
  - Hậu quả: Một lần báo nhầm có thể khiến cả lô hàng hàng chục tấn nông sản bị đối tác nước ngoài trả về hoặc tiêu hủy tại cảng, gây thiệt hại hàng trăm triệu đồng và khiến cả vùng trồng bị áp mã phạt kiểm tra nghiêm ngặt.
  - Thiết kế xử lý:
    - AI tuyệt đối không tự sinh ra kết luận XANH / ĐỎ; chỉ có Rule chạy trên bảng dữ liệu đã qua cán bộ HTX duyệt mới được quyền trả về kết quả.
    - Mọi trường hợp không có trong cơ sở dữ liệu hoặc có độ tin cậy thấp lập tức trả về trạng thái VÀNG và kích hoạt cơ chế Human-in-the-Loop (chuyển cán bộ chuyên môn xác nhận).

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

> Người phụ trách: Trịnh Gia Huy. Bản này dùng bằng chứng ở §3 và quy trình ở §4.
> Toàn bộ các trường dữ kiện được giữ nhất quán với v0 (§5) và mức can thiệp ở §6 (Workflow + Rule + HITL).

| Trường | Nội dung |
|---|---|
| **Actor** | Primary: Hộ nông dân trồng Thanh Long, người trực tiếp chọn và phun thuốc (Đối tượng chính cần kiểm chứng). Secondary: Cán bộ kỹ thuật HTX, người duyệt bảng quy định và xác nhận trường hợp ngoại lệ (§4.1). |
| **Quy trình** | Thấy sâu bệnh → Mua thuốc theo đại lý → (Đôi khi) gọi cán bộ HTX → Cán bộ tra danh mục thuốc và quy định MRL → Nông dân phun → HTX / thương lái kiểm mẫu sát thu hoạch (§4.1). |
| **Bottleneck** | **[Giả thuyết cần kiểm chứng]** Nông dân chọn thuốc tại đại lý mà không có cách tự kiểm tra ngay thuốc đó có được dùng cho thị trường xuất khẩu không và phải cách ly bao nhiêu ngày. Kênh xác minh duy nhất là cán bộ HTX nhưng lực lượng mỏng (§4.1). |
| **Impact** | **[Giả thuyết cần kiểm chứng]** Vi phạm chỉ lộ ra khi kiểm mẫu sát thu hoạch. Nguy cơ nông sản bị từ chối xuất khẩu, bán nội địa giá thấp gây thiệt hại kinh tế nặng nề. Ở cấp ngành, thanh long Việt Nam liên tục nằm trong diện kiểm soát tăng cường của EU theo Quy định 2019/1793 (§3.2, §10). |
| **Success Metric** (baseline → target, cách đo) | - **M1:** % lần phun dùng thuốc XANH, đủ thời gian cách ly (Baseline: [Chờ đo đạc thực tế theo validation plan] $\rightarrow$ Target đề xuất: $\ge 95\%$, 0 lần ĐỎ; đo bằng audit nhật ký).<br>- **M2:** Thời gian có thông tin đã xác minh (Baseline: [Chờ đo đạc thực tế] $\rightarrow$ Target: dưới 1 phút với XANH / ĐỎ; đo bằng log).<br>- **M3:** 100% kết quả về thuốc khớp bảng và có trích nguồn (đo bằng bộ eval).<br>- **M4:** Thời gian cán bộ mỗi tháng (Baseline: [Chờ đo đạc thực tế] $\rightarrow$ Target: giảm $\ge 50\%$; tự ghi). |
| **Boundary** | AI **không**: tự đưa ra con số liều, thời gian cách ly hay trạng thái XANH / ĐỎ; không khuyến nghị thuốc ngoài bảng; không chẩn đoán bệnh; không trả lời khi không có nguồn; không quyết định thay nông dân. **HITL:** Cán bộ HTX / chuyên gia duyệt từng dòng bảng trước khi phát hành; xác nhận mọi trường hợp VÀNG (thuốc lạ, dòng đang khóa, câu ngoài phạm vi). |
| **AI intervention point** | (1) Hiểu câu hỏi và gợi ý đúng tên thương mại khi nông dân gõ sai hoặc viết tắt; (2) diễn đạt kết quả tra bảng thành lời dễ hiểu; (3) trả lời câu chăm sóc chung chỉ từ tài liệu HTX đã chọn, kèm nguồn; (4) trích xuất văn bản quy định mới thành dòng bảng để người duyệt. Kết luận XANH / ĐỎ / VÀNG do **Rule** làm trên bảng đã duyệt. |
| **Mức chọn** | **Workflow kết hợp Rule và Human-in-the-Loop** (theo §6.2). |
| **Rủi ro & người kiểm tra** | Gợi ý nhầm tên thuốc gần giống → nông dân phải xác nhận đúng chai thuốc; tiêu chí 1 (người kiểm: nhóm vận hành pilot). Sai con số / trạng thái → Rule lấy từ bảng; tiêu chí 2 (cán bộ HTX). Bảng lỗi thời → khóa dòng khi có văn bản mới (cán bộ HTX / chuyên gia). Trả lời không nguồn → tiêu chí 3–4 (nhóm vận hành pilot). |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Boundary | Chung: không quyết định thay nông dân, không kết luận "đạt chuẩn" khi chưa có nguồn; cán bộ kiểm tra khi thông tin thiếu hoặc là thuốc mới | Cụ thể: AI không tự đưa ra con số hay trạng thái XANH / ĐỎ; Rule kết luận trên bảng đã duyệt; VÀNG chuyển cán bộ; khóa dòng khi luật đổi | Phản biện #1 ở §5: boundary v0 chưa nói AI không được làm gì; §6 chọn Workflow + Rule nên cần chỉ rõ chỗ nào là AI |
| Success Metric | M1, M2, M4; M2 target "trong ngày" | Thêm M3 (100% kết quả khớp bảng, có nguồn); M2 target dưới 1 phút với XANH / ĐỎ, trong ngày với VÀNG; giữ nguyên target, baseline chờ đo thực tế theo validation plan | Có bước AI nên cần metric chất lượng đầu ra; công cụ tra cứu cho phép trả lời tức thì với thuốc có trong bảng; đảm bảo tính liêm chính dữ liệu |
| AI intervention point | Chưa có (v0 viết trước CP6) | Tách rõ 4 điểm can thiệp kỹ thuật như bảng trên; kết luận thuốc do Rule thực hiện | CP6 chọn mức can thiệp |
| Mức chọn, rủi ro & người kiểm tra | Chưa có | Workflow + Rule + HITL; rủi ro gắn với tiêu chí eval và người kiểm tra | CP6 phân tích rủi ro và phương án triển khai |
| Actor, Quy trình, Bottleneck, Impact | Như §5 | Giữ nguyên (ghi rõ giả thuyết cần kiểm chứng) | Không tự tạo số liệu giả, chờ kiểm chứng hiện trường |

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

> Người phụ trách: Trần Duy Thành. Đánh giá dựa trên §3 (bằng chứng), §6 (Workflow + Rule + HITL) và §7 (eval).

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | **Cao** | Nhóm chưa phỏng vấn trực tiếp nông dân để xác nhận họ có thực sự muốn tự tra cứu hay vẫn giữ thói quen ra đại lý thuốc bảo gì xịt nấy. Giả định 1 ở §3.1 mới có bằng chứng ở mức 1/5. |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | **Cao** | Người trồng thanh long thường lớn tuổi, ít tiếp cận công nghệ; chưa kiểm chứng được họ có tự gõ được tên thuốc và hiểu kết quả XANH / ĐỎ / VÀNG hay không. Giả định 2 ở §3.1 mới có bằng chứng ở mức 1/5. |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | **TB** | Nguồn chính thức có sẵn trên cổng SPS và Cục BVTV (§3.3, §10), nhưng việc ánh xạ (mapping) từ tên thương mại sang hoạt chất và ngưỡng MRLs đòi hỏi nhiều công sức chuẩn hóa và duyệt dữ liệu. |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | **TB / Cao** | Chưa có cam kết từ HTX về việc cử cán bộ kỹ thuật kiểm duyệt bảng dữ liệu định kỳ; chưa rõ ai sẽ chịu chi phí duy trì hệ thống và trách nhiệm pháp lý khi xảy ra sai sót. |

### 8.2. Kết luận

* **Quyết định:** **Not Yet**
* **Lý do:** Do giới hạn thời gian của buổi Lab và việc chưa tiếp cận được đúng đối tượng người dùng, nhóm chưa hoàn thành phỏng vấn/survey trực tiếp với nông dân trồng thanh long và cán bộ HTX. Vì vậy, những pain point và quy trình hiện tại nhóm đưa ra vẫn là giả thuyết hình thành từ quá trình research, chưa được kiểm chứng bằng hành vi thực tế. Các rủi ro về Value và Usability hiện tại vẫn đang ở mức Cao.
* **Tuyên bố của nhóm:** Nhóm quyết định **Not Yet** thay vì vội vàng triển khai giải pháp AI. Bước tiếp theo là phỏng vấn người dùng, kiểm chứng bottleneck, đo baseline và thử phương án tra cứu đơn giản không dùng AI trước khi quyết định có tiếp tục hay không.
* **Nếu Not Yet — Cần kiểm chứng gì trước (Kế hoạch hành động):**
  - Triển khai kiểm chứng thực địa theo kế hoạch tại: [`report/assets/cp4-validation-plan.md`](../assets/cp4-validation-plan.md).
  - Phỏng vấn sâu tối thiểu 5–8 hộ nông dân, 2 cán bộ HTX và 2 đại lý thuốc tại vùng chuyên canh (Bình Thuận / Tiền Giang) theo bộ câu hỏi hành vi quá khứ (không dùng câu hỏi dẫn dụ).
  - Đo đạc baseline thực tế về thời gian tra cứu (M2) và tỷ lệ lần phun đúng quy định (M1).
  - Thử nghiệm phương án tra cứu đơn giản No-AI (Bảng tra cứu in sẵn / file tra cứu nhanh trên Zalo) để đo độ sẵn sàng và khả năng tự tra cứu của nông dân.
* **Ngưỡng dừng & Điều kiện xem xét lại quyết định:**
  - *Chuyển sang "Go":* Khi $\ge 70\%$ nông dân được hỏi xác nhận gặp khó khăn khi tra cứu thuốc xuất khẩu và sẵn sàng dùng công cụ số; ít nhất 3/5 hộ thử nghiệm tự tra đúng trên bảng tra đơn giản; đo được baseline rõ ràng; và HTX cam kết cử nhân sự duyệt bảng quy định.
  - *Chuyển sang "No-Go":* Nếu khảo sát thực tế cho thấy nông dân hoàn toàn phó mặc cho tiệm thuốc và không có nhu cầu tự kiểm tra; hoặc phương án No-AI (bảng tra in sẵn / Zalo) đã giải quyết trọn vẹn nhu cầu mà không cần đến công nghệ AI.

---

## 9. Hạn chế và hướng tiếp theo

> Người tổng hợp: Trần Duy Thành.

**Hạn chế**

- **Chưa hoàn thành phỏng vấn/survey thực địa:** Do giới hạn thời gian lab và khó khăn tiếp cận đối tượng tại vùng chuyên canh, nhóm chưa thể khảo sát thực tế với nông dân và cán bộ HTX; toàn bộ dữ liệu hiện tại là giả thuyết nghiên cứu từ tài liệu thứ cấp.
- **Chưa có baseline M1:** Chưa audit nhật ký phun thuốc thực tế, nên chưa có con số baseline chính thức về tỷ lệ phun đúng chuẩn.
- **Thị trường đích chưa chốt:** Bằng chứng ở §3 tập trung vào EU theo cảnh báo SPS, trong khi thị trường Úc cũng được đề xuất; cần chốt 1 thị trường cụ thể để xây dựng bảng quy tắc chuẩn.
- **Chưa kiểm chứng usability:** Chưa thử nghiệm thực tế xem nông dân có tự gõ được tên thuốc và hiểu kết quả phân loại XANH / ĐỎ / VÀNG hay không.
- **Chưa rõ người trả tiền và trách nhiệm pháp lý** khi thông tin xảy ra sai sót.
- **Chi phí duy trì bảng quy định** (duyệt từng dòng, khóa dòng khi luật đổi) chưa được đo lường cụ thể với nguồn lực thực tế của HTX.
- **Lab chưa xây hay thử sản phẩm:** Bộ eval ở §7 mới thử nghiệm trên tập dữ liệu mẫu giả định.

**Hướng tiếp theo trước khi xem xét lại Not Yet**

1. Thực hiện kế hoạch kiểm chứng thực địa theo [`report/assets/cp4-validation-plan.md`](../assets/cp4-validation-plan.md): Phỏng vấn sâu 5–8 hộ nông dân, 2 cán bộ HTX và 2 đại lý thuốc tại Bình Thuận hoặc Tiền Giang.
2. Chốt 1 thị trường đích cụ thể (ví dụ: EU). Lập bảng tra thí điểm cho các loại thuốc phổ biến và nhờ cán bộ HTX duyệt.
3. Rà soát nhật ký phun thực tế để đo baseline chuẩn cho M1, M2 và M4.
4. Thử nghiệm giải pháp No-AI (Bảng tra in sẵn / file tóm tắt Zalo) với 5 hộ để kiểm tra khả năng tự thao tác và mức độ hiểu kết quả.
5. Làm việc với HTX và bên thu mua về quy trình duyệt, cập nhật bảng dữ liệu, xử lý ngoại lệ, chi phí vận hành và trách nhiệm pháp lý.
6. Đối chiếu kết quả thu thập được với các điều kiện ở §8.2 để nhóm xem xét lại quyết định (chuyển sang Go hoặc No-Go).

---

## 10. Tài liệu tham khảo

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
