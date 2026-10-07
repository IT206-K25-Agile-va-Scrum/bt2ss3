# BÁO CÁO RÀ SOÁT TIẾN ĐỘ SPRINT 1 VÀ PHÂN TÍCH BURNDOWN CHART

> 👤 **Học viên:** Đỗ Hoàng Sơn | **Mã SV:** PTIT-HCM-066
> 🏫 **Môn học:** IT206-K25-Agile-va-Scrum

---

## Phần 1 - Phân tích nhận định báo cáo tiến độ Sprint 1

Sau khi nhận được báo cáo tiến độ của thành viên mới về Sprint 1 thuộc Epic 'Đặt xe ghép' (dài 10 ngày, tổng cam kết 40 Story Points), mình đã tiến hành đối chiếu từng nhận định với bảng số liệu thực tế của Sprint để kiểm tra tính chính xác.

- Bảng số liệu khối lượng công việc còn lại (Story Points) theo từng ngày trong Sprint 1:
- Ngày 0: 40 | Ngày 1: 38 | Ngày 2: 36 | Ngày 3: 36 | Ngày 4: 36 | Ngày 5: 36
- Ngày 6: 32 | Ngày 7: 29 | Ngày 8: 26 | Ngày 9: 23 | Ngày 10: 20

| Nhận định | Đúng / Sai | Dẫn chứng số liệu | Cách hiểu đúng |
| --- | --- | --- | --- |
| N1. Trục dọc thể hiện số giờ làm việc mà đội đã dùng. | Sai | Theo quy tắc Scrum, trục Y của Burndown Chart hiển thị khối lượng công việc còn lại tính bằng Story Points, không phải số giờ làm việc (Hours). | Trục dọc (Y) biểu diễn tổng số Story Points còn lại của Sprint cần hoàn thành. |
| N2. Đường lý tưởng giảm đều 4 điểm mỗi ngày và chạm 0 vào ngày 10. | Đúng | Tổng khối lượng 40 điểm chia đều cho 10 ngày, mỗi ngày giảm đúng 4 điểm (Ngày 0: 40 -> Ngày 10: còn 0). | Đường lý tưởng là đường tham chiếu tuyến tính từ tổng điểm về 0 vào ngày cuối cùng của Sprint. |
| N3. Từ ngày 2 đến ngày 5, đường thực tế đi ngang, chứng tỏ đội đang làm việc rất ổn định. | Sai | Từ ngày 2 đến ngày 5, số điểm còn lại giữ nguyên ở mức 36 điểm (không có Story Point nào được hoàn thành thêm trong 3 ngày liên tiếp). | Đường thực tế đi ngang không phải là ổn định, mà là dấu hiệu cảnh báo 'Bị chặn' (Blocked) do team đang gặp vướng mắc kỹ thuật hoặc phụ thuộc. |
| N4. Suốt Sprint, đường thực tế luôn nằm dưới đường lý tưởng nên đội đang nhanh hơn kế hoạch. | Sai | Từ ngày 0 đến ngày 7, đường thực tế (40 -> 29) luôn nằm TRÊN đường lý tưởng (ví dụ tại ngày 5: thực tế còn 36 điểm trong khi lý tưởng chỉ còn 20 điểm). | Đội đang bị trễ lịch trình trong phần lớn thời gian Sprint, mãi đến cuối mới cố gắng đẩy nhanh nhưng đến ngày 10 vẫn còn dư 20 điểm chưa hoàn thành. |

## Phần 2 - Vá lỗi và Hành động xử lý hiện tượng

Từ việc phát hiện các nhận định sai và nhìn vào thực trạng số liệu của Sprint, mình rút ra hai hiện tượng bất thường lớn nhất mà thành viên mới đã bỏ qua. Dưới đây là phương án xử lý cụ thể cho từng hiện tượng:

- Hiện tượng 1: Đường thực tế đi ngang từ ngày 2 đến ngày 5 (Tồn đọng 36 Story Points không nhúc nhích).
- Hành động cần làm: Scrum Master phải tổ chức Daily Standup khẩn cấp để gỡ vướng, xác định rõ các điểm nghẽn kỹ thuật (ví dụ: API tích hợp bản đồ hoặc cổng thanh toán bị nghẽn), đồng thời yêu cầu Product Owner hỗ trợ làm rõ yêu cầu nghiệp vụ nếu đội đang bị mơ hồ.
- Ai chịu trách nhiệm: Scrum Master phối hợp cùng Development Team.
- Thực hiện vào lúc nào: Ngay trong Daily Standup của ngày 3 khi phát hiện đường đi ngang.
- Hiện tượng 2: Đường thực tế nằm trên đường lý tưởng suốt Sprint và kết thúc ngày 10 vẫn còn dư 20 Story Points (chỉ hoàn thành được một nửa khối lượng cam kết).
- Hành động cần làm: Đội ngũ phải thực hiện kỹ thuật 'Scope Reduction' (cắt giảm phạm vi các User Story chưa thực sự cốt lõi) bàn bạc với Product Owner để chuyển bớt sang Sprint sau, tránh tình trạng dồn việc gây áp lực quá tải (Burnout). Đồng thời, trong buổi Sprint Retrospective cần nhìn nhận lại năng lực ước lượng (Velocity) để điều chỉnh kế hoạch Sprint 2 thực tế hơn.
- Ai chịu trách nhiệm: Product Owner và Development Team (có sự điều phối của Scrum Master).
- Thực hiện vào lúc nào: Thực hiện điều chỉnh phạm vi từ giữa Sprint (khoảng ngày 6-7 khi thấy trễ nặng) và tổ chức đánh giá nghiêm túc trong buổi Sprint Retrospective vào cuối ngày 10.

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `bt2.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
