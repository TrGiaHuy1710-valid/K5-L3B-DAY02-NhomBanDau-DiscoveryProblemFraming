# Kế hoạch Kiểm chứng Thực địa (CP4 Validation Plan)

> **Tài liệu thuộc Checkpoint 4 (CP4) — Nhóm Ban Đầu**  
> **Dự án:** Hỗ trợ người trồng Thanh Long tiếp cận và xác minh thông tin chăm sóc cây, quy định thuốc BVTV phục vụ xuất khẩu.  
> **Trạng thái:** Kế hoạch thực hiện kiểm chứng sau vòng Discovery (Cơ sở để nhóm đưa ra quyết định **Not Yet**).

---

## 1. Bối cảnh và Lý do lập kế hoạch

Trong khuôn khổ thời gian giới hạn của buổi Lab 02, nhóm đã hoàn thành việc nghiên cứu tài liệu thứ cấp (Desk Research) về quy định kiểm dịch thực vật, tiêu chuẩn MRLs của các thị trường xuất khẩu (EU, Úc, Nhật) và rà soát các ứng dụng hiện có trên thị trường.

Tuy nhiên, nhóm nhận định trung thực rằng: **Chưa thể tiếp cận và phỏng vấn trực tiếp các hộ nông dân trồng thanh long và cán bộ kỹ thuật HTX tại địa bàn thực tế**. Vì vậy, toàn bộ các giả định về nỗi đau (Pain Point), nút thắt quy trình (Bottleneck) và các chỉ số Baseline hiện tại mới chỉ dừng lại ở mức **Giả thuyết nghiên cứu**.

Để đảm bảo tính liêm chính học thuật và tránh cái bẫy "Solution-first", nhóm quyết định chọn **Not Yet** và xây dựng kế hoạch kiểm chứng thực địa này để thực hiện trước khi quyết định phát triển giải pháp AI.

---

## 2. Đối tượng mục tiêu & Tiêu chí chọn mẫu (Sample Criteria)

Nhóm xác định 3 nhóm đối tượng cần tiếp cận thực địa:

| Nhóm đối tượng | Số lượng mẫu tối thiểu | Tiêu chí lựa chọn | Mục tiêu phỏng vấn |
|---|:---:|---|---|
| **Hộ nông dân trồng Thanh Long (Primary User)** | 5 – 8 hộ | - Trực tiếp canh tác thanh long diện tích $\ge 0.5$ ha.<br>- Có tham gia liên kết bán thanh long cho HTX hoặc doanh nghiệp xuất khẩu.<br>- Đa dạng độ tuổi (từ dưới 40 đến trên 55 tuổi) và mức độ sử dụng smartphone. | Kiểm chứng hành vi thực tế khi mua và phun thuốc; rào cản khi đọc nhãn thuốc; mức độ phụ thuộc đại lý; thói quen dùng điện thoại ngoài vườn. |
| **Cán bộ kỹ thuật HTX (Secondary User / Supporter)** | 2 – 3 người | - Trực tiếp phụ trách hướng dẫn kỹ thuật canh tác VietGAP/GlobalGAP.<br>- Chịu trách nhiệm giám sát nhật ký và lấy mẫu kiểm định dư lượng. | Xác minh mức độ quá tải khi hỗ trợ xã viên tra cứu quy định; thời gian và công cụ HTX đang dùng để cập nhật danh mục MRLs; mức độ sẵn sàng duyệt dữ liệu. |
| **Chủ đại lý thuốc BVTV tại vùng trồng (Stakeholder)** | 2 đại lý | - Kinh doanh thuốc BVTV tại các vùng chuyên canh (Hàm Thuận Nam - Bình Thuận hoặc Chợ Gạo - Tiền Giang). | Tìm hiểu tiêu chí tư vấn thuốc cho nông dân; đại lý có nắm được quy định cấm của các nước xuất khẩu không; nguồn thông tin đại lý dựa vào. |

---

## 3. Bộ câu hỏi phỏng vấn chuẩn Discovery (Interview Protocol)

> **Nguyên tắc phỏng vấn:**  
> - Hỏi về **hành vi và sự việc ĐÃ XẢY RA** trong quá khứ gần nhất.  
> - **Tuyệt đối không hỏi câu hỏi giả định hoặc dẫn dụ:** KHÔNG hỏi *"Bác có muốn một ứng dụng AI tra cứu thuốc không?"* vì người được hỏi sẽ luôn lịch sự trả lời "Có".  
> - Tập trung vào cảm xúc, thời gian, tiền bạc và các phương án xử lý tạm bợ (Workarounds) của họ.

### 3.1. Dành cho Hộ nông dân trồng Thanh Long

1. **Khám phá bối cảnh:** *"Trong vụ thanh long vừa rồi, vườn nhà mình gặp phải loại sâu bệnh nào khó trị nhất? Bác đã phát hiện và xử lý như thế nào?"*
2. **Hành vi lựa chọn thuốc:** *"Khi thấy cành/trái có dấu hiệu bệnh, bác quyết định mua loại thuốc nào bằng cách nào? Bác tự chọn hay ra tiệm nhờ người ta đưa?"*
3. **Sự cố thực tế:** *"Lần gần nhất bác mua một chai thuốc về mà băn khoăn không biết xịt có an toàn cho hàng xuất khẩu không là khi nào? Lúc đó bác làm gì để kiểm tra lại?"*
4. **Trải nghiệm đọc nhãn & quy định:** *"Khi cầm chai thuốc trên tay, bác thường đọc những thông tin nào trên bao bì? Có thông tin nào bác thấy khó hiểu hoặc chữ quá nhỏ không?"*
5. **Hậu quả & thiệt hại:** *"Đã có lần nào vườn của bác hoặc người quen trong xóm bị thương lái/HTX trả hàng hoặc trừ tiền vì dính dư lượng thuốc chưa? Chuyện gì đã xảy ra lúc đó?"*
6. **Thói quen công nghệ:** *"Bác thường dùng điện thoại để làm những việc gì hàng ngày? Bác có hay nhắn tin hay xem thông báo trên Zalo không? Khi ở ngoài vườn, bác có mang điện thoại theo không?"*

### 3.2. Dành cho Cán bộ kỹ thuật HTX

1. **Quy trình hỗ trợ hiện tại:** *"Khi xã viên thắc mắc một loại thuốc BVTV có được dùng cho thị trường xuất khẩu (EU, Úc, Nhật) hay không, anh/chị xử lý yêu cầu đó như thế nào? Anh/chị tra cứu ở đâu?"*
2. **Thời gian và công sức:** *"Trung bình mỗi tuần anh/chị nhận được bao nhiêu câu hỏi liên quan đến danh mục thuốc và thời gian cách ly? Mỗi lần tra cứu và trả lời mất bao lâu?"*
3. **Nút thắt thông tin:** *"Lần gần nhất thị trường nhập khẩu cập nhật danh mục hoạt chất cấm hoặc hạ ngưỡng MRLs, HTX đã phổ biến cho bà con bằng cách nào? Có gặp khó khăn gì trong việc đảm bảo bà con nhớ và tuân thủ không?"*
4. **Độ tin cậy của nhật ký:** *"Hiện tại HTX kiểm soát việc ghi nhật ký canh tác của bà con bằng cách nào? Tỷ lệ bà con ghi chép đầy đủ và trung thực ước tính khoảng bao nhiêu %?"*

---

## 4. Kế hoạch Thử nghiệm Phương án Không dùng AI (No-AI Baseline Test)

Trước khi quyết định áp dụng công nghệ AI (Workflow / RAG), nhóm sẽ tiến hành thử nghiệm phương án No-AI đơn giản nhất:

1. **Hình thức:** Biên soạn một **Bảng tra cứu thuốc nhanh dạng tóm tắt (Cheat Sheet)** gồm:
   - Cột 1: Tên thương mại phổ biến tại địa phương.
   - Cột 2: Hoạt chất tương ứng.
   - Cột 3: Tình trạng cho thị trường EU/Úc (Đèn Xanh: Được phép / Đèn Đỏ: Cấm).
   - Cột 4: Thời gian cách ly tối thiểu (PHI - số ngày).
2. **Kênh phân phối thử nghiệm:**
   - In màu ép plastic phát cho 10 hộ nông dân thử nghiệm.
   - Lưu trữ dạng file ảnh tra cứu nhanh gửi ghim trên nhóm Zalo HTX.
3. **Mục tiêu đo lường:**
   - Xem nông dân có thực sự mở bảng ra tra cứu trước khi đi mua thuốc không.
   - Đo thời gian tra cứu thủ công (để làm Baseline so sánh).
   - Nhận diện những trường hợp mà bảng tra cứu cứng không giải quyết được (ví dụ: thuốc mới xuất hiện trên thị trường, đại lý đổi tên thuốc, hoặc câu hỏi phức tạp về phối trộn nhiều loại thuốc).

---

## 5. Tiêu chí Chuyển trạng thái (Transition Criteria)

Quyết định **Not Yet** sẽ được nhóm họp lại và xem xét chuyển sang trạng thái mới dựa trên các tiêu chí định lượng rõ ràng:

```text
                           [KẾT QUẢ KIỂM CHỨNG THỰC ĐỊA]
                                        │
           ┌────────────────────────────┴────────────────────────────┐
           ▼                                                         ▼
[ĐỦ ĐIỀU KIỆN CHUYỂN "GO"]                                 [CHUYỂN SANG "NO-GO"]
- ≥ 4/5 nông dân xác nhận khó khăn khi tra cứu            - Nông dân hoàn toàn phó mặc cho tiệm thuốc
  và mong muốn có công cụ tra cứu tức thời.                  và không có nhu cầu tự kiểm tra.
- Xác định được baseline thời gian tra cứu ≥ 30 phút.      - Phương án Bảng tra cứu Zalo/giấy No-AI
- HTX cam kết cử đầu mối kỹ thuật duyệt bảng dữ liệu.        đã giải quyết được > 80% nhu cầu.
- Rủi ro Value và Usability hạ từ Cao xuống TB/Thấp.      - Không tìm được nguồn duy trì dữ liệu MRLs.
```

---
*Kế hoạch được lập ngày 10/11/2026 bởi Nhóm Ban Đầu (AI20K K5).*

