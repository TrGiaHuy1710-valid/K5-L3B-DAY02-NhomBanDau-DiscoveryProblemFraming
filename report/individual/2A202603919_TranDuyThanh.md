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
- **Card số:** 1 - Tổng hợp chi tiêu đa kênh.
- **Vì sao:** Có hành vi lặp lại, dễ xác định bottleneck, có thể đo thử trong một tuần; có thể đánh giá liệu quy tắc đơn giản đã đủ hay cần AI.
- **Câu hỏi muốn nhóm phản biện:** “Nếu ngân hàng hoặc ví đã có báo cáo chi tiêu, pain còn nằm ở đâu, và chúng ta có bằng chứng rằng người dùng thực sự phải tổng hợp nhiều nơi không?”

### AI phản biện card thế nào (mẫu phản biện để tự đối chiếu)
| Điểm yếu AI chỉ ra | Đồng ý? | Cần sửa / đã sửa trong bản nháp |
|---|---|---|
| Chưa chứng minh người dùng thực sự làm việc này hàng tuần; có thể họ không quan tâm theo dõi. | Có | Thu hẹp actor: người đã theo dõi chi tiêu; yêu cầu ghi lại 2–3 lần gần nhất. |
| Không phải ngân hàng/ứng dụng nào cũng cho trích xuất dữ liệu; rủi ro bảo mật tài chính. | Có | Giới hạn ở dữ liệu tự nhập hoặc mẫu giao dịch ẩn danh; không yêu cầu mật khẩu hay kết nối tài khoản. |
| Với chia tiền, công thức và app sẵn có có thể giải quyết đủ tốt, không cần AI. | Có | Giữ No AI / Rule như phương án chính để so sánh. |
| Thời gian giả định không chứng minh impact thật. | Có | Đánh dấu rõ mọi thời gian là minh họa; đo bằng đồng hồ và log trước khi đưa vào báo cáo chính thức. |


---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
