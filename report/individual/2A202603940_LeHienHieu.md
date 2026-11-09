# Báo cáo cá nhân — 2A202603940_LeHienHieu

## 1. Thông tin học viên

- Họ tên: Le Hien Hieu
- MSSV: 2A202603940
- Email trường: 26ai.hieulh@vinuni.edu.vn
- Tên nhóm: NhomBanDau
- Link repo nhóm: https://github.com/TrGiaHuy1710-valid/K5-L3B-DAY02-NhomBanDau-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Lặp lại |Khi có nhân sự mới vào team cần dùng CycleGAN để sinh dữ liệu ảnh, tôi muốn họ có thể tự hoàn thành việc setup Docker, config thông số và mask mà không cần tôi cầm tay chỉ việc, để tôi không bị ngắt mạch code/train model của riêng mình |Bản thân, Nhân sự mới |Tần suất 4-5 lần/ngày (đặc biệt khi có người mới)|
| 2 |Tốn thời gian | Khi đang remote vào máy trạm để train AI mà tín hiệu mạng chập chờn hoặc bắt buộc gập laptop, tôi muốn tiến trình train vẫn được đảm bảo chạy ngầm và không bị văng session, để không bị kill tiến trình làm lãng phí tài nguyên và không tốn thêm thời gian login lại từ đầu |Bản thân | Mất khoảng 5-10p để login qua các lớp bảo mật |
| 3 |Pain từ người khác |Khi đi học về muộn và khu vực bếp chung có nhiều bát đĩa chưa rửa, tôi muốn quy trình nấu nướng và dọn rửa được phân chia, xử lý nhanh gọn, để tôi có thể ăn uống xong sớm và nghỉ ngơi mà không bị ức chế bởi đồ đạc bẩn của người khác |Bản thân |Tần suất xảy ra đều đặn 1-2 lần/ngày |
| 4 |Tốn thời gian |Khi có một ít quần áo lẻ tẻ cần giặt vào cuối ngày, tôi muốn biết chính xác khi nào máy giặt đang trống hoặc có ai đang muốn gom đồ giặt chung, để không phải mất công xách đồ ra vào kiểm tra liên tục hoặc trì hoãn việc giặt giũ sinh hoạt |Bản thân và người cùng phòng |Việc lặp lại hàng ngày, mất khoảng 10-15p đi thang máy xuống kiếm tra xem có máy giặt trống không |
| 5 |Đọc, tổng hợp nhiều thông tin |Khi hệ thống báo một lỗi mơ hồ có thể do nhiều nguyên nhân đan xen (module, layer, thư viện), tôi muốn khoanh vùng được ngay đoạn tài liệu liên quan nhất thay vì phải search mò mẫm, để không phải dò ngược thủ công từ dưới lên qua hàng chục file code hoặc tài liệu|Bản thân |Mất trung bình từ 20-30p cho một lỗi |
| 6 |Lặp lại |Khi cần định dạng lại các trích dẫn và hình ảnh cho bài báo khoa học trên LaTeX, phù hợp với nhiều định dạng, tôi muốn có sẵn một template tự động bắt lỗi cú pháp, để không phải biên dịch và sửa lỗi thủ công liên tục |Người viết, đồng tác giả |Mất khoảng 45-60 phút mỗi lần nộp bài chỉ để mò mẫm fix lỗi format/syntax LaTeX |
| 7 |Cần đọc, tổng hợp nhiều thông tin |Khi bắt tay vào thiết kế luồng tích hợp API cho một dự án AI, tôi muốn đối chiếu nhanh các tiêu chí đánh giá kỹ thuật, để chọn đúng mô hình LLM phù hợp mà không bị quá tải bởi hàng chục trang tài liệu rule |AI Engineer, thành viên team dự án |Tốn 2-3 tiếng đồng hồ rà soát PDF |
| 8 |Lặp lại |Khi cần thuê GPU mới trên cloud để test mô hình, tôi muốn môi trường Docker và thư viện tự động được setup y hệt máy cũ, để có thể chạy script train ngay lập tức |AI Developer, Researcher |Lặp lại 2-3 lần/tuần do thuê máy theo giờ, mỗi lần tốn 20-30 phút gõ lại lệnh cài dependencies.|

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

Sau khi tự scan 5 ý từ #1 đến #5, tôi giữ lại ý #6, #7, #8. Bỏ ý "tự động chia train/val và format nhãn trước khi huấn luyện" vì mỗi quy trình train khác nhau thì yêu cầu khác nhau. 

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 |Quá tải thông tin khi đối chiếu tài liệu kỹ thuật/luật lệ để thiết kế luồng API và chọn mô hình LLM |Tốn nhiều giờ (2-3 tiếng) rà soát tài liệu; nếu chọn sai framework ban đầu sẽ phải đập đi làm lại, ảnh hưởng nghiêm trọng tiến độ dự án|Không rõ các AI Engineer khác có gặp khó khăn tương tự không, hay họ đã có sẵn template/quy trình chuẩn để đánh giá rule nhanh? |
| 2 |Mất thời gian setup lại môi trường (Docker, thư viện) từ đầu mỗi khi thuê máy chủ GPU mới trên cloud để train AI |Hành động lặp lại thường xuyên (2-3 lần/tuần), gây lãng phí chi phí thuê GPU theo giờ và làm gián đoạn mạch làm việc |Không chắc mức độ sẵn sàng trả tiền/sử dụng giải pháp của cộng đồng, vì nhiều người có thể đã quen viết bash script để chạy tự động |
| 3 |Bị ngắt mạch làm việc do phải liên tục hướng dẫn nhân sự mới setup môi trường CycleGAN (Docker, config, mask) |Xảy ra liên tục (4-5 lần/ngày) khi có người mới; làm giảm năng suất của cả mentor lẫn thực tập sinh |Liệu người mới có thực sự tin tưởng và tự sử dụng tool/tài liệu tự động không, hay do tâm lý vẫn muốn hỏi trực tiếp mentor cho "chắc ăn"? |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt tay vào thiết kế luồng tích hợp API cho một dự án AI, tôi muốn đối chiếu nhanh các tiêu chí đánh giá kỹ thuật, để chọn đúng mô hình LLM phù hợp mà không bị quá tải bởi hàng chục trang tài liệu rule |
| Actor | AI Engineer, Tech Lead |
| Thời điểm / bối cảnh |Giai đoạn đầu của dự án khi cần chốt model và framework |
| Quy trình hiện tại (3–7 bước) |1. Tải tài liệu specs · 2. Đọc lướt hàng chục trang · 3. Lọc ràng buộc kỹ thuật (size, format, tool-calling) · 4. Tìm kiếm các LLM trên HuggingFace · 5. Đối chiếu LLM với ràng buộc · 6. Chốt mô hình |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 2 & 3: Đọc và bóc tách các ràng buộc ẩn trong tài liệu dài (mất khoảng 120 phút), dễ bỏ sót chi tiết gây hậu quả lớn |
| Impact (nếu không giải thì sao) |Tốn 2-3 tiếng research ban đầu; rủi ro cao: nếu đọc sót rule và chọn sai framework/model, team sẽ phải đập đi làm lại toàn bộ hệ thống gây trễ deadline |
| Success metric (baseline → target) |Thời gian chốt mô hình và kiến trúc từ 120+ phút xuống dưới 20 phút. Tỉ lệ vi phạm rule do chọn sai tech stack = 0% |
| Phương án không dùng AI |Chia nhau ra đọc rule; lập bảng checklist đối chiếu trên Google Sheets thủ công |
| Giả thuyết về AI (nếu có) |AI đọc file PDF/Docs thể lệ, tự động trích xuất các ràng buộc kỹ thuật cứng thành checklist và gợi ý top 3 mô hình phù hợp nhất trên thị trường hiện tại |
| Cảm nhận nhanh | AI Agent (RAG kết hợp search) |

Quy trình nháp hiện tại:

```text
~ 180 phút
[1 Tải tài liệu: 5'] → [2 Đọc lướt tài liệu: 60'] → [3 Lọc ràng buộc: 60']← BOTTLENECK → [4 Tìm mô hình LLM: 30'] → [5 Đối chiếu thông số: 20'] → [6 Chốt mô hình: 5']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần thuê GPU mới trên cloud để test mô hình, tôi muốn môi trường Docker và thư viện tự động được setup y hệt máy cũ, để có thể chạy script train ngay lập tức |
| Actor |AI Developer, Researcher |
| Thời điểm / bối cảnh |Bắt đầu ca làm việc, khi vừa thuê máy chủ GPU mới theo giờ (ví dụ Vast.ai) để test mô hình |
| Quy trình hiện tại (3–7 bước) |1. Thuê instance mới · 2. SSH vào máy · 3. Pull code/Git · 4. Cài đặt môi trường cơ bản (CUDA, Docker) · 5. Cài dependencies/requirements · 6. Chạy script |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 4 & 5: Setup lại môi trường và thư viện, hay gặp lỗi xung đột version, tốn khoảng 25 phút |
| Impact (nếu không giải thì sao) |Lặp lại 2-3 lần/tuần gây ức chế tâm lý; lãng phí tiền thuê GPU tính theo giờ trong lúc chỉ ngồi nhìn thanh tiến trình cài đặt chạy |
| Success metric (baseline → target) |Thời gian chờ từ lúc SSH thành công đến khi bắt đầu train giảm từ 25-30 phút xuống dưới 5 phút |
| Phương án không dùng AI |Build sẵn custom Docker Image đẩy lên Docker Hub; viết Bash script tự động hóa toàn bộ luồng cài đặt |
| Giả thuyết về AI (nếu có) |AI Agent tự động đọc bash log, nếu cài đặt thư viện bị lỗi do xung đột version, tự động tìm và fix file requirements.txt rồi chạy lại |
| Cảm nhận nhanh | Rule (Bash Script) / No AI |

Quy trình nháp hiện tại:

```text
~ 35 phút
[1 Thuê instance: 3'] → [2 SSH vào máy: 2'] → [3 Pull code: 2'] → [4 Cài môi trường base: 10'] → [5 Cài dependencies: 15'] ← BOTTLENECK → [6 Chạy script: 3']

```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi có nhân sự mới vào team cần dùng CycleGAN để sinh dữ liệu ảnh, tôi muốn họ có thể tự hoàn thành việc setup Docker, config thông số và mask mà không cần tôi cầm tay chỉ việc, để tôi không bị ngắt mạch code/train model của riêng mình. |
| Actor |Mentor (Bản thân mình) và Nhân sự mới |
| Thời điểm / bối cảnh |Onboarding người mới hoặc khi giao task tạo dữ liệu defect ảnh bằng CycleGAN |
| Quy trình hiện tại (3–7 bước) |1. Giao task/docs · 2. Intern tự mò docs · 3. Kẹt ở khâu config mask/Docker · 4. Intern ping Mentor hỏi · 5. Mentor phải dừng việc · 6. Mentor remote máy hướng dẫn trực tiếp · 7. Chạy thử |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 5 & 6: Mentor phải dừng việc đang làm để chỉ lỗi trực tiếp, mất 20-30 phút mỗi lần |
| Impact (nếu không giải thì sao) |Mentor bị ngắt flow làm việc 4-5 lần/ngày làm giảm nghiêm trọng năng suất; Intern tốn thời gian ngồi chờ mentor rảnh để hỏi |
| Success metric (baseline → target) |Số lần Intern cần hỏi Mentor trực tiếp về setup giảm từ 4-5 lần/ngày xuống 0-1 lần/ngày; Mentor không bị ngắt mạch code |
| Phương án không dùng AI |Quay sẵn video thao tác mẫu; cập nhật wiki nội bộ với list các lỗi phổ biến (FAQ) |
| Giả thuyết về AI (nếu có) |Bot nội bộ được train riêng trên bộ docs và log lỗi của dự án, Intern chỉ cần paste mã lỗi/ảnh màn hình vào, Bot sẽ chỉ ra dòng config nào đang sai và cách sửa |
| Cảm nhận nhanh | AI Agent (RAG) |

Quy trình nháp hiện tại:

```text
~ 60 phút
[1 Giao task: 5'] → [2 Intern mò docs: 20'] → [3 Kẹt config: 10'] → [4 Ping Mentor: 2'] → [5 Mentor dừng việc: 3'] → [6 Mentor chỉ bài: 25']← BOTTLENECK → [7 Chạy thử: 5']
```

### Card muốn pitch nhất

- Card số: 3
- Vì sao: Vì nó giải quyết trực tiếp một điểm nghẽn nghiêm trọng trong vận hành đội ngũ kỹ thuật: chi phí ẩn của việc chuyển đổi bối cảnh làm việc. Trong môi trường R&D, việc kỹ sư nòng cốt phải liên tục gián đoạn luồng công việc chuyên sâu để xử lý các lỗi thiết lập môi trường sơ cấp không chỉ gây lãng phí quỹ thời gian chuyên môn mà còn làm suy giảm hiệu suất tổng thể của dự án. Bài toán này mang lại bức tranh ROI rõ ràng: một hệ thống AI hỗ trợ nội bộ sẽ giải phóng nguồn lực nhân sự chất lượng cao để tập trung vào giá trị cốt lõi, đồng thời rút ngắn thời gian chờ đợi và tăng tính chủ động cho nhân sự mới.
- Câu hỏi muốn nhóm phản biện: 
    + Liệu người mới có thực sự tin tưởng sử dụng AI Bot không, hay tâm lý họ vẫn muốn hỏi trực tiếp mentor cho "chắc ăn" và để tạo mối quan hệ?
    + Làm sao để bot không đưa ra các lệnh sửa lỗi "ảo" (hallucination) khiến môi trường Docker của intern càng lỗi nặng hơn?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
|Tần suất 4-5 lần/ngày có thể chỉ đúng trong 1-2 tuần đầu có Intern mới, sau đó nhu cầu sẽ giảm mạnh. Nhìn dài hạn, đây không phải vấn đề lặp lại đủ lớn để duy trì sản phẩm. |Đồng ý một phần |Mở rộng bối cảnh: Không chỉ áp dụng cho người mới, mà định vị đây là "Internal Troubleshooting Agent" cho cả team phần mềm mỗi khi dự án đổi stack, đổi server hoặc có update framework mới (CycleGAN chỉ là case study chứng minh) |
|Giải pháp AI Agent có thể bị "Over-engineering". Tại sao không bắt intern đọc kỹ một tài liệu Wiki/FAQ hoặc xem video Record hướng dẫn?|Đồng ý|Làm rõ hơn ở phần "Phương án không dùng AI": Các lỗi config thường mang tính động (phụ thuộc vào version OS, phần cứng từng máy) nên FAQ tĩnh không bao giờ bao phủ hết được. Cần AI đọc log lỗi cụ thể để bắt bệnh chuẩn xác.|
|Target Metric "giảm số lần hỏi Mentor xuống 0" là phi thực tế với một hệ thống AI chưa hoàn hảo.|Đồng ý|Điều chỉnh lại Success Metric thực tế hơn: AI Agent tự động xử lý 80% các lỗi config phổ biến (Tier 1), chỉ đẩy lên Mentor các lỗi hệ thống sâu (Tier 2)"|

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card |Trình bày Card 3 (Setup môi trường)|Nêu rõ giải pháp dùng Local LLM (Qwen-2.5-coder) để trace log nhằm bảo mật dữ liệu công ty, tiết kiệm thời gian cho mentor và tiết kiệm chi phí token so với việc cho Intern dùng Claude/ChatGPT bừa bãi |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: 1. (Với app quản lý chi tiêu): "App hiện tại làm quá tốt rồi, pain point này có thực sự cần AI không?" 2. (Với app Nông nghiệp): "Scope tư vấn luật xuất khẩu đang quá lớn, bao phủ mọi loại cây. Làm sao đảm bảo RAG chạy chính xác?" | 1. Bạn (1) đổi ý tưởng sang AI search/so sánh giá cross-platform, tôi tiếp tục cảnh báo rào cản kỹ thuật (chặn crawl data, API đa nền tảng). Nhóm loại ý tưởng này. 2. Bạn (2) đồng ý thu hẹp scope. Tôi đề xuất thêm: Nên có cơ chế chụp ảnh phân tích bệnh. Nhóm chốt ý tưởng này và thu hẹp hẹp vào Cây Thanh Long. |
| Nhận phản biện | Câu hỏi tôi nhận được: 1. "Có công cụ nào cạnh tranh chưa? Tại sao không cho dùng ChatGPT/Claude luôn?" 2. "Dự án này chắc chỉ mấy công ty công nghệ mới dùng thôi đúng không?" | Tôi đã sửa gì: 1. Làm rõ rủi ro bảo mật (leak data) và chi phí token, intern dễ accept code mù quáng. 2. Pivot (Đổi định hướng cốt lõi): Thu hẹp định vị từ "Internal Solution cho toàn công ty" xuống thành "Trợ lý hỗ trợ Intern cho từng dự án". Lý do tự nhận ra: Tổng hợp log mọi dự án vào 1 RAG sẽ gây nhiễu, quá tải và giảm hiệu suất báo lỗi chính xác của AI.|
| Gom cluster / cây OST | Bỏ qua bước vẽ cây OST, đi thẳng vào đánh giá chéo và loại suy trực tiếp các bài toán dựa trên tính khả thi|Tiết kiệm thời gian, tập trung phân tích sâu vào rủi ro kỹ thuật của từng ý tưởng (như tính khả thi của RAG và Web Crawling) |
| Chọn candidate problem |Cùng nhóm phân tích và vote chốt dự án AI tư vấn Thanh Long (RAG quy trình + Vision chẩn đoán) |Lý do chốt: Tính cấp thiết cực cao (luật kiểm dịch, dư lượng hóa chất MRLs của Úc, Nhật thay đổi liên tục khiến nông dân dễ bị trả hàng, rớt giá) và Khả năng scale tốt (Từ thanh long làm chuẩn, có thể nhân rộng cấu trúc RAG sang sầu riêng, cà phê sau này) |
| Kiểm chứng / research |Research thị trường: Tìm kiếm các giải pháp Agri-tech hiện có tại Việt Nam và Thế giới |Kết quả kiểm chứng: Phát hiện các app quốc tế như Plantix làm rất tốt phần nhận diện bệnh (Vision), các app VN thì chủ yếu ghi chép nhật ký nông vụ tĩnh. Chưa có app nào làm RAG real-time về tiêu chuẩn xuất khẩu/hóa chất cấm. Điều này chứng minh USP (Lợi thế độc quyền) của nhóm rất rõ ràng và khả thi |
| Quy trình nhóm |Trình bày ý tưởng -> Phản biện -> Research -> Chốt vấn đề |Thống nhất được vấn đề chung của nhóm |
| Problem Statement |Góp ý vào quá trình hình thành statement cuối |Nông dân trồng Thanh Long gặp khó khăn trong việc chẩn đoán bệnh chính xác và cập nhật kịp thời các thay đổi về tiêu chuẩn xuất khẩu (dư lượng hóa chất), dẫn đến rủi ro bị trả hàng và thiệt hại kinh tế lớn |
| Mức can thiệp AI |Xác định giới hạn hành động của AI (AI làm đến đâu, con người làm đến đâu) |Chốt mức: AI chỉ đóng vai trò phân tích ảnh bệnh và tra cứu luật/cảnh báo hóa chất cấm. Quyết định cuối cùng vẫn thuộc về nông dân. |
| Quyết định |Đóng vai trò người phản biện chính và làm rõ vấn đề |Giúp nhóm không bị sa đà vào các ý tưởng viển vông (như web crawling so sánh giá), nhìn nhận thực tế giới hạn của AI (RAG dễ bị nhiễu nếu scale quá to), và gọt giũa ý tưởng cuối cùng trở nên cực kỳ thực tế |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan |Nhập bối cảnh cá nhân (thực tập sinh, làm AI, ở trọ) và nhờ AI sinh ra các kịch bản vấn đề theo format Job Story |Giúp cấu trúc hóa suy nghĩ lộn xộn thành câu chuẩn "Khi... tôi muốn... để...", rút ngắn thời gian format |Đưa ra các vấn đề quá chung chung, lý tưởng hóa (vd: "quên deadline", "khó tìm tài liệu") và thiếu các con số đo lường thực tế |Bác bỏ các ý chung chung. Tôi tự bơm data thực tế của mình vào (vd: kẹt setup CycleGAN tốn 30p, tần suất 4-5 lần/ngày) để ép AI viết lại sát với nỗi đau thật |
| CP2 Problem Card |Nhờ AI điền thử các trường trong Problem Card dựa trên Job Story đã chốt để xem luồng logic |Khá tốt ở việc phân tách các bước trong quy trình hiện tại và định hình bức tranh "Impact" | AI hay vẽ vời các hệ thống quá to (vd: Agent tự động fix mọi lỗi code của công ty) |Tôi tự thu hẹp scope lại. Nhận định rằng AI Agent tự fix code sẽ rủi ro hỏng hệ thống, nên tôi đổi thành định vị "Trợ lý hỗ trợ tra log và giải đáp thắc của của Intern" để giữ an toàn |
| CP4 Research |Dùng AI để tra cứu nhanh các đối thủ/ứng dụng Agri-tech hoặc tool hỗ trợ dev trên thị trường |Lên danh sách nhanh các app quốc tế (như Plantix) và tóm tắt các tính năng cơ bản của họ |AI bị "ảo giác" (hallucinate) thông tin về thị trường Việt Nam, đưa ra các app không tồn tại hoặc không nắm được luật kiểm dịch xuất khẩu mới nhất |Tự Google search kiểm chứng lại. Tôi nhận ra các app VN chỉ làm nhật ký tĩnh, từ đó tôi tự đúc kết ra USP (điểm khác biệt) là làm RAG real-time cho luật xuất khẩu |
| CP5 Quy trình |Nhờ AI phân tích các bước thắt cổ chai (bottleneck) trong hành trình của người dùng |Vẽ ra được một flow 5-7 bước liền mạch, logic |Chỉ vẽ đường đi lý tưởng AI bỏ qua yếu tố tâm lý con người (người mới ngại hỏi Mentor, nông dân mù mờ công nghệ) |Bổ sung thêm "chi phí ẩn". Nhận định bottleneck thực sự không phải là đọc tài liệu chậm, mà là sự ngắt quãng mạch làm việc của Mentor ảnh hưởng rất nhiều |
| CP5–6 Problem Statement |Quăng toàn bộ Problem Card và Research vào để AI tóm tắt thành 1-2 câu Problem Statement |Cô đọng văn bản dài thành một đoạn ngắn, ngữ pháp chỉn chu |Hay nhét các từ khóa kiểu đột phá, toàn diện,... |Cắt bỏ toàn bộ các từ đó và phải chỉnh lại giọng văn |
| CP6 Mức can thiệp / quyết định |Hỏi AI xem với bài toán này nên dùng Rule-based, Copilot hay Agent |Giải thích rõ ràng ưu/nhược điểm kỹ thuật của từng mô hình |Luôn có xu hướng khuyên dùng Agent tự trị (vd: AI tự chốt đơn, tự ra lệnh xịt thuốc, tự sửa file config) – cực kỳ xa rời thực tế rủi ro |Bác bỏ phương án Agent. Tôi quyết định chốt mức độ Copilot, trợ lú, đưa ra gợi ý cho con người. Con người mới là người quyết định. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Tôi nhận ra là dân kỹ thuật, đặc biệt là các bạn bên software dễ bị rơi vào tình huống là áp dụng AI cho những giải pháp vốn không cần đến AI, hoặc khi áp dụng AI chưa đúng scope. Ví dụ, khi nghe ý tưởng dùng AI crawl data từ các sàn thương mại điện tử để tìm giá rẻ, thoạt nghe rất hay, nhưng lại bỏ qua rào cản thực tế về việc các web chặn API hoặc cấm crawl. Tôi có base AI nên có kinh nghiệm phản biện hơn, ngoài ra các dự án cũng thiếu metrics rõ ràng, mặc dù của tôi cũng cố ý bỏ qua.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có, chính là lúc bàn về dự án nông nghiệp. Ban đầu, một bạn đưa ra ý tưởng là làm một hệ thống RAG thời gian thực cập nhật dữ liệu từ Bộ Nông nghiệp để tư vấn cho nông dân. Với vai trò phản biện, tôi đã hỏi lại là "Thế rốt cuộc nỗi đau thật sự ở đây là gì?". Sau đó nhóm phải lùi lại một bước, phân tích và nhận ra vấn đề gốc rễ không phải là "nông dân thiếu RAG", mà là nỗi đau "thiệt hại kinh tế vì thanh long bị trả về do vi phạm dư lượng hóa chất xuất khẩu". Từ đó, giải pháp mới bám sát vào thực tế.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Có. Ban đầu, tôi pitch ý tưởng làm một công cụ AI nội bộ cho toàn công ty - như trước AI tư vấn cho tôi, nghe cũng hợp lý, để hỗ trợ Intern tra cứu lỗi setup môi trường. Khi bị team vặn vẹo về việc tại sao không dùng ChatGPT và vấn đề chi phí, tôi đã phải nhìn nhận lại. Tôi nhận ra nếu dồn log của mọi dự án vào một RAG chung thì AI sẽ bị quá tải, nhiễu thông tin dễ bị halluciation. Tôi đã đổi ý, đổi giải pháp thành một "Trợ lý ảo cục bộ (Local LLM như Qwen-2.5-coder) triển khai riêng cho dự án hỗ trợ Intern" làm sample trước, vừa giải quyết được bài toán bảo mật data công ty, vừa tiết kiệm tiền token, lại đảm bảo AI trả lời trúng đích hơn.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Điều làm tôi bất ngờ nhất khi đi research thị trường ứng dụng Agri-tech là "khoảng trống" của việc cập nhật luật. Tôi cứ nghĩ thị trường đã bão hòa, nhưng hóa ra các app nổi tiếng (như Plantix) chủ yếu chỉ làm rất tốt phần AI Vision (nhận diện bệnh qua ảnh), còn các app Việt Nam thì đa số chỉ là sổ ghi chép nhật ký nông vụ tĩnh. Gần như chưa có bên nào làm tính năng RAG real-time cảnh báo tức thời về danh mục hóa chất bị cấm hay tiêu chuẩn dư lượng của các thị trường khó tính như Nhật, Úc. Điều này mang lại cho dự án của nhóm một lợi thế cạnh tranh rất rõ ràng

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Khó nhất là cưỡng lại thói quen "nhét giải pháp và công nghệ" vào câu phát biểu vấn đề. Cứ phải có RAG, LLM,... nhưng sau cùng chúng tôi nhận ra là Problem Statement phải đơn giản nên chúng tôi đã hoàn thiện lại Problem Statement là "Nông dân trồng Thanh Long gặp khó khăn trong việc chẩn đoán bệnh chính xác và cập nhật kịp thời các thay đổi về tiêu chuẩn xuất khẩu (dư lượng hóa chất), dẫn đến rủi ro bị trả hàng và thiệt hại kinh tế lớn"

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu làm lại, tôi sẽ mạnh tay ngắt lời và cắt thời gian thảo luận ở những ý tưởng không khả thi sớm hơn. Trong lúc chọn Candidate Problem, nhóm đã tốn hơi nhiều thời gian để tranh luận về tính khả thi kỹ thuật của app gom nhóm mua sắm, trong khi lẽ ra tôi nên đề xuất về Impact của bài toán Nông nghiệp, nếu không giải quyết thì sao? Nó là ý tưởng cấp thiết và thiết thực hơn.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
- Problem của nhóm là việc nông dân trồng thanh long bị thiệt hại kinh tế nặng nề do bị trả hàng vì không cập nhật kịp luật kiểm dịch hoặc dư lượng hóa chất xuất khẩu và chẩn đoán sai bệnh.
- Quy trình hiện tại của họ rất thụ động: dựa vào kinh nghiệm mắt thường để bắt bệnh và chỉ biết thông tin hóa chất cấm khi nghe thương lái báo lại.
- Metric thành công của dự án là giảm tỷ lệ lô hàng thanh long xuất khẩu bị đánh trượt do lỗi hóa chất và sâu bệnh.
- Boundary của hệ thống được khoanh vùng chặt chẽ: AI chỉ phân tích ảnh bệnh và tra cứu luật, tuyệt đối không can thiệp vào logistics hay định giá bán.
- Mức can thiệp AI được chốt ở mức Copilot, AI chỉ đưa ra gợi ý, cảnh báo.
- Quyết định cuối cùng (chốt phun loại thuốc gì, thu hoạch ngày nào) bắt buộc phải do con người tự đưa ra để tránh các rủi ro pháp lý về mùa màng.

## 7. Tài liệu tham khảo
- Plantix App (PEAT GmbH), ứng dụng nhận diện bệnh cây trồng bằng AI
- Các quy định về Dư lượng tối đa cho phép đối với nông sản nhập khẩu của Bộ Nông nghiệp, Lâm nghiệp và Thủy sản Nhật Bản (MAFF) và Bộ Nông nghiệp Úc.
