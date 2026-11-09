# Báo cáo cá nhân - MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.


## 1. Thông tin học viên

- Họ tên: Trần Duy Thành
- MSSV: 2A202603919
- Email trường: 
- Tên nhóm: 26ai.thanhtd2@vinuni.edu.vn
- Link repo nhóm: https://github.com/TrGiaHuy1710-valid/K5-L3B-DAY02-NhomBanDau-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi cuối tuần tôi xem lại các khoản đã tiêu bằng tiền mặt, chuyển khoản và ví điện tử, tôi muốn biết tiền đã đi vào những nhóm chi tiêu nào, để điều chỉnh ngân sách tuần tới. | Người tự quản lý tài chính | Khoảng 30 phút/tuần; đo bằng thời gian mở lịch sử giao dịch, ghi chép và phân loại. |
| 2 | Tốn thời gian | Khi nhận sao kê cuối tháng, tôi muốn nhận ra các giao dịch không nhớ mục đích hoặc bị ghi hai lần, để số liệu chi tiêu không sai lệch. | Người dùng nhiều phương thức thanh toán | Khoảng 40 phút/tháng; kiểm bằng danh sách giao dịch cần đối chiếu. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi định mua một món đồ có nhiều phiên bản và nơi bán, tôi muốn so sánh tổng tiền phải trả, bảo hành và điều kiện đổi trả, để tránh chọn nhầm. | Người mua sắm trực tuyến | Khoảng 45 phút/món; kiểm bằng lịch sử các trang và số lượt thay đổi lựa chọn. |
| 4 | Lặp lại | Khi có các dịch vụ tự gia hạn như ứng dụng, lưu trữ hoặc nội dung số, tôi muốn biết khoản nào sắp trừ tiền, để chủ động quyết định giữ hay hủy. | Người có gói đăng ký định kỳ | Khoảng 1 lần quên hủy trong vài tháng; xác minh bằng email và giao dịch thực, không đoán. |
| 5 | Pain từ người khác | Khi đặt đồ ăn hoặc hàng dùng chung, tôi muốn tính đúng phần tiền từng người và cập nhật ai đã trả, để không phải nhắc nhiều lần. | Bạn bè, người ở chung | Khoảng 10–15 phút/lần chia tiền; kiểm bằng chat đối soát và số lần nhắc. |
| 6 | Tốn thời gian | Khi một đơn hàng giao chậm hoặc có vấn đề, tôi muốn tìm lại mã đơn, bằng chứng thanh toán và lịch sử trao đổi, để xử lý đổi trả nhanh hơn. | Người mua hàng online | Khoảng 20 phút/vụ; kiểm bằng thời gian tìm thông tin và số lần liên hệ hỗ trợ. |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi mua một sản phẩm qua nhiều đợt khuyến mãi, tôi muốn hiểu điều kiện mã giảm, phí vận chuyển và mức hoàn tiền thực tế, để biết phương án nào có lợi. | Người mua sắm săn ưu đãi | Khoảng 25 phút/lần; kiểm bằng các phương án giá thực trả đã tính. |
| 8 | Pain từ người khác | Khi cả nhà cùng mua đồ sinh hoạt, tôi muốn biết món gì đã có và món gì cần mua, để tránh mua trùng hoặc thiếu. | Người sống cùng gia đình/bạn ở chung | Khoảng 2 lần mua trùng/tháng; kiểm bằng hóa đơn và danh sách đồ dùng. |
| 9 | Lặp lại | Khi đến hạn đóng điện, nước, mạng hoặc phí nhà, tôi muốn đối chiếu khoản đã thanh toán với hóa đơn, để tránh quên hoặc trả lặp. | Người tự trả hóa đơn sinh hoạt | Khoảng 15 phút/tháng; kiểm bằng lịch thanh toán thực. |
| 10 | Tốn thời gian | Khi cần quyết định có đủ ngân sách cho một khoản mua lớn, tôi muốn biết số tiền còn lại sau các khoản cố định, để không chi quá mức. | Người có ngân sách cá nhân | Khoảng 20 phút/lần; kiểm bằng bản tính trước và sau mua. |


## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3
| Rank | Problem | Vì sao chọn | Điều chưa chắc / phải kiểm chứng |
|---:|---|---|---|
| 1 | #1 - Tổng hợp chi tiêu đa kênh | Xuất hiện thường xuyên, có đầu vào/đầu ra cụ thể, dễ đo thời gian và lỗi phân loại | Bạn thực sự dùng bao nhiêu kênh thanh toán? Có duy trì ghi chép không? |
| 2 | #3 - So sánh lựa chọn mua hàng | Có bước nghẽn đọc và đối chiếu thông tin; dễ phỏng vấn người từng mua | Có thực sự tốn thời gian hay chỉ là sở thích tìm hiểu? |
| 3 | #5 - Chia tiền mua chung | Dễ quan sát tương tác nhiều người; lỗi và thời gian đối soát đo được | Bạn có thường xuyên mua chung và nhắc chuyển tiền không? |

### Problem Card #1 - Tổng hợp chi tiêu từ nhiều phương thức thanh toán
| Trường | Nội dung |
|---|---|
| Job Story | Khi cuối tuần cần xem lại tiền đã tiêu qua nhiều hình thức thanh toán, tôi muốn biết chính xác từng nhóm chi phí, để điều chỉnh chi tiêu tuần tiếp theo. |
| Actor | Người tự theo dõi chi tiêu cá nhân và dùng từ hai kênh thanh toán trở lên. |
| Thời điểm / bối cảnh | Cuối tuần, sau khi có nhiều khoản chi nhỏ. |
| Quy trình hiện tại (3–7 bước) | Mở lịch sử ngân hàng → xem ví điện tử → nhớ khoản tiền mặt → nhập vào bảng → phân loại → soát lại. |
| Bottleneck | Nhập thủ công và phân loại các giao dịch (~12 phút/tuần). |
| Impact | Mất thời gian, bỏ sót khoản tiền mặt, khó nhận ra nhóm tiêu vượt dự kiến. |
| Success metric | Baseline minh họa **30 phút/tuần** → mục tiêu **≤12 phút/tuần**; đo đồng hồ 3 tuần liên tiếp, so với số giao dịch thực tế; số giao dịch bị phân loại sai ≤1/tuần. |
| Phương án không dùng AI | Một bảng theo mẫu thống nhất, quy tắc phân loại theo từ khóa và lịch chốt giao dịch cố định. |
| Giả thuyết về AI | Hỗ trợ gợi ý nhóm cho mô tả giao dịch khó hiểu; người dùng duyệt và có quyền sửa. |
| Cảm nhận nhanh | **Rule / Workflow** |

Quy trình hiện tại - **30 phút/tuần, toàn bộ số phút là giả định cần đo lại**:

```text
[Mở giao dịch ngân hàng: 4'] → [Xem lịch sử ví: 3']
→ [Nhớ/ghi tiền mặt: 5'] → [Nhập và phân loại: 12'] ← BOTTLENECK
→ [Soát trùng/sai: 4'] → [Tổng kết: 2']
```

### Problem Card #2 - So sánh thông tin trước khi mua hàng
| Trường | Nội dung |
|---|---|
| Job Story | Khi cần mua một món đồ có nhiều nhà bán và phiên bản, tôi muốn đối chiếu giá thực trả cùng điều kiện đổi trả, để quyết định mà không mua nhầm. |
| Actor | Người thường mua đồ trên các sàn hoặc trang bán lẻ trực tuyến. |
| Thời điểm / bối cảnh | Trước khi đặt món hàng có giá trị đủ lớn để cân nhắc. |
| Quy trình hiện tại (3–7 bước) | Chọn tiêu chí → mở các nơi bán → ghi thông số → tính giá thực trả → đọc bảo hành/đổi trả → chọn. |
| Bottleneck | Đối chiếu thông số, điều kiện và giá từ các trang khác nhau (~18 phút/lần). |
| Impact | Mất thời gian, có thể bỏ sót phí, điều kiện đổi trả hoặc chọn sai phiên bản. |
| Success metric | Baseline minh họa **45 phút/lần** → mục tiêu **≤20 phút/lần**; đo với 3 lần mua tương đương, đối chiếu số thông số quan trọng bỏ sót (mục tiêu 0). |
| Phương án không dùng AI | Mẫu bảng so sánh cố định gồm giá cuối, model, bảo hành, phí, đổi trả; ưu tiên nguồn chính thức. |
| Giả thuyết về AI | Trích và chuẩn hóa các điều kiện từ trang người mua cung cấp, kèm nguồn để đối chiếu; không tự khẳng định giá hiện tại. |
| Cảm nhận nhanh | **Workflow**|

Quy trình hiện tại - **45 phút/lần, giả định**:

```text
[Đặt tiêu chí: 4'] → [Mở 3–4 nơi bán: 8']
→ [So thông số/giá/đổi trả: 18'] ← BOTTLENECK
→ [Tính chi phí thực: 7'] → [Kiểm tra uy tín: 5'] → [Chốt: 3']
```

### Problem Card #3 - Chia tiền sau các khoản mua chung
| Trường | Nội dung |
|---|---|
| Job Story | Khi một người ứng tiền cho bữa ăn hoặc đồ dùng chung, tôi muốn xác định ai phải trả bao nhiêu và khoản nào đã chuyển, để chốt tiền minh bạch, không hỏi lại. |
| Actor | Nhóm bạn bè hoặc người ở chung có các khoản mua chung. |
| Thời điểm / bối cảnh | Sau bữa ăn, mua đồ sinh hoạt hoặc chuyến đi ngắn. |
| Quy trình hiện tại (3–7 bước) | Gom hóa đơn → xác định ai dùng món nào → tính phần mỗi người → gửi số tiền → theo dõi thanh toán → nhắc người chưa trả. |
| Bottleneck | Tính phần mỗi người khi có món riêng/chung, phí và khuyến mãi (~8 phút/lần). |
| Impact | Tính sai, phải chuyển bù hoặc nhắc lại, gây khó chịu cho người trong nhóm. |
| Success metric | Baseline minh họa **19 phút/lần** → mục tiêu **≤7 phút/lần**; đo thời gian chốt và số lần phải sửa bảng chia tiền (mục tiêu 0). |
| Phương án không dùng AI | Bảng chia tiền có công thức hoặc ứng dụng split bill; mọi người xác nhận trước khi chuyển. |
| Giả thuyết về AI | Có thể đọc hóa đơn để gợi ý các khoản, nhưng công thức chia tiền và xác nhận con người vẫn là trọng tâm; AI có thể không cần thiết. |
| Cảm nhận nhanh | **No AI / Rule**|

Quy trình hiện tại - **19 phút/lần, giả định**:

```text
[Chụp/gom hóa đơn: 2'] → [Gán món cho người: 3']
→ [Tính phần từng người: 8'] ← BOTTLENECK
→ [Gửi bảng: 2'] → [Đối chiếu thanh toán: 3'] → [Nhắc/đóng sổ: 1']
```

### Card muốn pitch nhất
- **Card số:** 2 - So sánh thông tin trước khi mua hàng.
- **Vì sao:** Trước khi mua một món hàng có nhiều phiên bản hoặc nhà bán, thông tin về thông số, giá sau ưu đãi, phí vận chuyển, bảo hành và đổi trả nằm rải rác ở nhiều nơi, đôi khi khác cách trình bày. Người mua phải tự mở từng trang, chuẩn hóa thông tin rồi đối chiếu. Đây là bottleneck cụ thể, có thể bấm giờ và kiểm tra mức độ bỏ sót. Bài toán có thể được cải thiện trước bằng bảng tiêu chí chuẩn; AI giúp hỗ trợ trích xuất và tổng hợp thông tin có dẫn nguồn.
- **Câu hỏi muốn nhóm phản biện:** “Việc dành thời gian so sánh trước khi mua là khó khăn thật hay là hành vi cần thiết để ra quyết định tốt? Nếu các sàn đã có bộ lọc, bảng so sánh và đánh giá, phần nào vẫn phải làm thủ công, và bằng chứng nào cho thấy pain đó đủ lớn?”

### AI phản biện card thế nào
| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa |
|---|---|---|
| Chưa tách được thời gian tìm hiểu cần thiết với thời gian lãng phí do thông tin phân tán. | Có | Chỉ xem là bottleneck các thao tác lặp lại: sao chép thông số, quy đổi giá cuối và đọc điều kiện ở nhiều nguồn; không coi toàn bộ thời gian cân nhắc là lãng phí. |
| Các sàn và website đã có bộ lọc, đánh giá và so sánh sản phẩm; chưa chứng minh khoảng trống. | Có | Kiểm tra 3 trường hợp mua thật: người mua phải mở mấy trang, dữ liệu quan trọng nào không thể đối chiếu ngay trên một màn hình. |
| Giá, khuyến mãi và chính sách có thể thay đổi; AI dễ tổng hợp sai hoặc bịa nguồn. | Có | Mỗi thông tin quan trọng cần lưu đường dẫn và thời điểm kiểm tra; đối chiếu lại tại bước thanh toán, không để AI tự quyết định mua. |
| Thời gian 45 phút và mục tiêu 20 phút chưa phải số đo thực tế. | Có | Nếu có thể cần đo ít nhất 3 lần so sánh sản phẩm tương tự, ghi thời gian theo bước và số thông tin bị bỏ sót. |


---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Tạo pitch này | Đã được mọi người xem xét |
| Phản biện bài của bạn khác | Hỏi: "AI tóm tắt slide đã có rồi, như NoteLLM, nếu có thể tạo ưu thê thì sẽ làm private nhưng LLM thì rất khó" | Giúp loại bỏ bớt problem này. |
| Phản biện bài của bạn khác | Hỏi: "Agent hỗ trợ Intern liệu có cần thiết không khi nếu dự án đã private thì chẳng lẽ công ty lại không cho dùng công cụ code hỗ trợ để gỡ bỏ các bug?" | Nhận được câu trả lời: "Các công ty thưởng sẽ không cung cấp model dùng token cho intern, vì vậy mới cần một model local nhỏ giúp hỗ trợ vấn đề này." |
| Nhận phản biện | "Với problem liên quan tới AI giúp kiểm soát chi tiêu, liệu có nhất thiết phải dùng AI không khi mà suy nghĩ kĩ lại thì rule thôi là cũng ổn" | Đồng ý với ý kiến này, vì vậy card muốn pick là cái #2|
| Nhận phản biện | "Với việc dùng AI để tổng hợp ra các kênh, trang của sản phẩm, vấn đề là việc lấy API từ các kênh, có nơi không cho, hoặc API cũng sẽ quá nhiều" | Có thể ưu tiên các API  chính thức, hay là cho người dùng cung cấp website hay dùng chẳng hạn.|
| Kiểm chứng / research | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 | Gợi ý thêm 4 pain | Mở rộng các bối cảnh đời sống. | Số liệu hiện tại vẫn chỉ tạm thời là giả định, chưa đo thật. | Tạm thời giữ nguyên số liệu. |
| CP2 | Đóng vai PM hoài nghi | Làm rõ actor, bước nghẽn, cách đo. | Tất cả thời gian/tần suất đang là giả định. | Trước mắt dựa trên tình hình cá nhân để cho ra quy trình theo làm thật. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Ý tưởng của mọi người đến từ những lĩnh vực khác nhau, cho cái nhìn rộng mở hơn về các vấn đề. Nghe mọi người trình bày, phản biện cũng giúp làm rõ hơn các vướng mắc, vấn đề.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?** 

Không, nhóm luôn hướng tới việc problem-first.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có, cụ thể như việc chuyển first pick thừ card #1 sáng card #2 như đã nói ở trên

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Về research thì có thể nói vấn đề được nhóm chọn khá bất ngờ là chưa phổ biến khi Việt Nam là nước nông nghiệp mà problem này lại chưa có nhiều.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Suy nghĩ ra nhiều các problem, đồng thời chuẩn xác nó thành các bước. 

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Trước mắt chưa có suy nghĩ gì.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
