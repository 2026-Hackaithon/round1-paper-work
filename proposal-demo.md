# Proposal HackAIthon 2026 - Bảng B Challenger

## 1. Tên sản phẩm/dự án

**5Tot AI Portfolio - Trợ lý AI hỗ trợ hoàn thiện và xét duyệt hồ sơ Sinh viên 5 tốt**

## 2. Thông tin đội thi

- **Tên đội:** `<Điền tên đội>`
- **Bảng thi:** Bảng B - Challenger
- **Hướng đề tài:** AI hỗ trợ công tác Hội và phong trào Sinh viên 5 tốt
- **Thành viên:**

| STT | Họ tên | Vai trò dự kiến | Email/SĐT |
|---:|---|---|---|
| 1 |  | Product/Team Lead |  |
| 2 |  | Backend/API |  |
| 3 |  | Frontend/UI |  |
| 4 |  | AI/Prompt/Data |  |
| 5 |  | Research/Pitch |  |

## 3. Tóm tắt dự án

5Tot AI Portfolio là nền tảng hỗ trợ sinh viên chuẩn bị hồ sơ xét danh hiệu **Sinh viên 5 tốt** và hỗ trợ Đoàn - Hội sơ loại, kiểm duyệt hồ sơ theo tiêu chí. Hệ thống cho phép sinh viên tải lên minh chứng như giấy chứng nhận, bảng điểm, hoạt động ngoại khóa, thành tích, chứng chỉ và mô tả hoạt động. AI sẽ đọc, bóc tách, phân loại minh chứng theo từng nhóm tiêu chí, chỉ ra tiêu chí đã đạt, tiêu chí còn thiếu, minh chứng chưa hợp lệ hoặc cần bổ sung.

Ở phía cán bộ Đoàn - Hội, hệ thống cung cấp dashboard phân loại hồ sơ, gợi ý trạng thái xét duyệt, highlight lý do đạt/chưa đạt và hỗ trợ xuất nhận xét sơ bộ. Điểm quan trọng của giải pháp là **AI không thay thế người duyệt**, mà đóng vai trò trợ lý kiểm tra, giảm tải thao tác thủ công và tăng tính minh bạch cho cả sinh viên lẫn cán bộ phụ trách.

## 4. Bối cảnh và vấn đề cần giải quyết

### 4.1. Bối cảnh

Phong trào Sinh viên 5 tốt là một phong trào quan trọng trong môi trường đại học, khuyến khích sinh viên phát triển toàn diện theo nhiều nhóm tiêu chí như học tập, đạo đức, tình nguyện, hội nhập và thể lực. Tuy nhiên, quy trình chuẩn bị và xét duyệt hồ sơ thường có nhiều bước thủ công:

- Sinh viên phải tự đọc tiêu chí, tự đối chiếu với minh chứng cá nhân.
- Minh chứng nằm rải rác ở nhiều định dạng: ảnh, PDF, giấy chứng nhận, bảng điểm, link hoạt động.
- Cán bộ Đoàn - Hội phải kiểm tra từng hồ sơ, phân loại từng minh chứng, nhắc sinh viên bổ sung.
- Việc phản hồi thiếu minh chứng thường mất thời gian, dễ thiếu nhất quán giữa các người duyệt.

### 4.2. Pain-point của sinh viên

- Không biết mình đã đạt tiêu chí nào và còn thiếu tiêu chí nào.
- Không biết minh chứng nào phù hợp với tiêu chí nào.
- Nộp hồ sơ sát hạn nên khó bổ sung hoạt động/chứng chỉ còn thiếu.
- Khó tổng hợp các minh chứng thành một portfolio đẹp, dễ đọc và có giá trị sử dụng tiếp.

### 4.3. Pain-point của Đoàn - Hội

- Tốn nhiều thời gian đọc và phân loại hồ sơ thủ công.
- Khó phát hiện nhanh hồ sơ thiếu minh chứng hoặc minh chứng không khớp tiêu chí.
- Khó theo dõi trạng thái xử lý khi số lượng hồ sơ lớn.
- Khó tạo phản hồi thống nhất, rõ ràng và có căn cứ cho từng sinh viên.

## 5. Người dùng mục tiêu

### 5.1. Người dùng chính

- **Sinh viên:** người chuẩn bị hồ sơ xét Sinh viên 5 tốt cấp khoa/trường.
- **Cán bộ Đoàn - Hội:** người tiếp nhận, kiểm tra, sơ loại và phản hồi hồ sơ.

### 5.2. Người dùng mở rộng

- Ban Thư ký Hội Sinh viên cấp trường.
- Cố vấn học tập hoặc phòng công tác sinh viên.
- Các đơn vị tổ chức hoạt động cần xác nhận minh chứng cho sinh viên.

## 6. Giải pháp đề xuất

5Tot AI Portfolio gồm hai không gian sử dụng chính: phía sinh viên và phía Đoàn - Hội.

### 6.1. Phía sinh viên

Sinh viên có thể:

- Tạo hồ sơ cá nhân và chọn cấp xét danh hiệu.
- Upload minh chứng ở nhiều định dạng: ảnh, PDF, văn bản, link.
- Để AI đọc và phân loại minh chứng theo tiêu chí Sinh viên 5 tốt.
- Nhận báo cáo: tiêu chí đã đạt, tiêu chí còn thiếu, minh chứng chưa đủ rõ, minh chứng cần thay thế.
- Nhận gợi ý hoạt động/chứng chỉ nên bổ sung theo tiêu chí còn thiếu.
- Render CV/portfolio Sinh viên 5 tốt từ các minh chứng đã được hệ thống phân loại.

### 6.2. Phía Đoàn - Hội

Cán bộ Đoàn - Hội có thể:

- Xem danh sách hồ sơ theo khoa/lớp/trạng thái/tiêu chí.
- Kiểm tra từng hồ sơ với các minh chứng đã được AI phân loại.
- Nhận gợi ý trạng thái: `Đạt sơ bộ`, `Cần bổ sung`, `Không phù hợp`, `Cần kiểm tra thủ công`.
- Xem lý do AI gợi ý trạng thái, ví dụ: thiếu minh chứng học tập, giấy chứng nhận không có ngày, hoạt động chưa khớp tiêu chí.
- Gửi phản hồi mẫu cho sinh viên.
- Xuất báo cáo sơ loại hoặc danh sách hồ sơ cần xử lý tiếp.

## 7. Điểm khác biệt

Các hệ thống quản lý hồ sơ thông thường thường chỉ hỗ trợ upload file và lưu trạng thái. 5Tot AI Portfolio tập trung vào lớp xử lý thông minh:

- **Bóc tách minh chứng tự động:** đọc nội dung từ giấy chứng nhận, bảng điểm, ảnh chụp, PDF.
- **Mapping minh chứng - tiêu chí:** gợi ý mỗi minh chứng thuộc tiêu chí nào.
- **Giải thích quyết định:** không chỉ báo "đạt/chưa đạt", mà nêu rõ thiếu gì, vì sao cần bổ sung.
- **Hỗ trợ cả hai phía:** sinh viên được hướng dẫn hoàn thiện hồ sơ, cán bộ được hỗ trợ sơ loại.
- **Tạo portfolio tái sử dụng:** minh chứng không chỉ dùng để xét danh hiệu, mà còn được render thành CV/portfolio phục vụ học bổng, thực tập, tuyển dụng.

## 8. Vì sao cần AI?

Quy trình xét hồ sơ Sinh viên 5 tốt có nhiều thao tác liên quan đến đọc hiểu, phân loại, đối chiếu và giải thích. Nếu làm bằng cách truyền thống, hệ thống chỉ có thể lưu file và bắt người dùng tự chọn tiêu chí. AI giúp tạo giá trị ở các điểm sau:

- **OCR và trích xuất thông tin:** đọc tên hoạt động, đơn vị cấp, thời gian, thành tích, điểm số từ minh chứng.
- **Phân loại ngữ nghĩa:** một minh chứng có thể liên quan đến nhiều tiêu chí; AI giúp gợi ý nhóm phù hợp.
- **Đối chiếu tiêu chí:** AI kiểm tra nội dung minh chứng với bộ tiêu chí đã cấu hình.
- **Gợi ý bổ sung cá nhân hóa:** mỗi sinh viên thiếu tiêu chí khác nhau, AI đưa ra khuyến nghị khác nhau.
- **Sinh phản hồi tự nhiên:** tạo nhận xét sơ bộ dễ hiểu cho sinh viên, giảm thời gian cán bộ soạn phản hồi.

## 9. API dự kiến tích hợp

| API/nhóm API | Vai trò trong sản phẩm | Luồng sử dụng |
|---|---|---|
| VNPT SmartReader | OCR và bóc tách thông tin từ ảnh/PDF/giấy chứng nhận | Sinh viên upload minh chứng, hệ thống trích xuất nội dung chính |
| VNPT Smartbot | Trợ lý hỏi đáp tiêu chí, gợi ý bổ sung, sinh phản hồi | Sinh viên hỏi "em còn thiếu gì?", cán bộ xem nhận xét AI |
| VNPT eKYC | Xác thực danh tính sinh viên khi cần | Đối chiếu thông tin cá nhân trên hồ sơ/minh chứng |
| VNPT SmartVoice | Tùy chọn giao diện giọng nói cho sinh viên/cán bộ | Sinh viên hỏi đáp bằng giọng nói, cán bộ ghi chú nhanh |
| VNPT SmartUX | Theo dõi hành vi sử dụng và cải thiện UX | Đo tỉ lệ hoàn thiện hồ sơ, bước bị nghẽn, thời gian xử lý |

Trong MVP, đội sẽ ưu tiên tích hợp **SmartReader** và **Smartbot**, vì đây là hai API gắn trực tiếp với giá trị lõi của sản phẩm.

## 10. Thiết kế tổng quan

### 10.1. Kiến trúc hệ thống

```text
Sinh viên/Cán bộ
      |
      v
Web App
      |
      v
Backend API
      |
      +-- Module quản lý hồ sơ
      +-- Module quản lý tiêu chí
      +-- Module xử lý minh chứng
      +-- Module AI scoring & recommendation
      +-- Module render portfolio
      |
      v
Database + Object Storage
      |
      +-- SmartReader API
      +-- Smartbot API
      +-- eKYC/SmartVoice/SmartUX optional
```

### 10.2. Luồng dữ liệu phía sinh viên

1. Sinh viên tạo hồ sơ.
2. Sinh viên upload minh chứng.
3. Backend lưu file và gửi file đến OCR/SmartReader.
4. Hệ thống nhận nội dung trích xuất.
5. AI phân loại minh chứng theo bộ tiêu chí.
6. Hệ thống tạo báo cáo thiếu/đủ.
7. Sinh viên bổ sung minh chứng hoặc render portfolio.

### 10.3. Luồng dữ liệu phía Đoàn - Hội

1. Cán bộ xem dashboard hồ sơ.
2. Hệ thống hiển thị trạng thái AI gợi ý.
3. Cán bộ mở từng hồ sơ, kiểm tra minh chứng và lý do gợi ý.
4. Cán bộ xác nhận, chỉnh sửa hoặc yêu cầu bổ sung.
5. Hệ thống gửi phản hồi cho sinh viên.
6. Cán bộ xuất danh sách sơ loại.

## 11. Phạm vi MVP

Trong thời gian HackAIthon, MVP tập trung vào một luồng end-to-end:

### 11.1. Chức năng bắt buộc

- Đăng nhập giả lập theo 2 vai trò: sinh viên và cán bộ.
- Sinh viên tạo hồ sơ.
- Upload minh chứng mẫu.
- OCR/trích xuất nội dung minh chứng.
- Phân loại minh chứng vào nhóm tiêu chí.
- Báo cáo tiêu chí đã đạt/chưa đạt.
- Gợi ý bổ sung hoạt động/chứng chỉ còn thiếu.
- Dashboard cán bộ xem trạng thái hồ sơ.
- Cán bộ duyệt hoặc yêu cầu bổ sung.
- Render portfolio cơ bản từ minh chứng.

### 11.2. Chức năng nếu còn thời gian

- Chatbot hỏi đáp tiêu chí.
- Xác thực danh tính bằng eKYC.
- Xuất PDF portfolio.
- Bộ lọc hồ sơ nâng cao.
- Lưu lịch sử phản hồi giữa sinh viên và cán bộ.

### 11.3. Ngoài phạm vi MVP

- Tích hợp hệ thống quản lý sinh viên thật của trường.
- Tự động quyết định kết quả cuối cùng không cần người duyệt.
- Xử lý toàn bộ biến thể tiêu chí của mọi cấp xét.
- Ký số hoặc xác thực pháp lý đầy đủ cho minh chứng.

## 12. Công nghệ dự kiến

| Thành phần | Công nghệ dự kiến |
|---|---|
| Frontend | React/Next.js hoặc Vite React |
| Backend | Node.js/NestJS hoặc Express |
| Database | PostgreSQL hoặc SQLite cho MVP |
| File storage | Local storage/S3-compatible storage |
| AI/API | VNPT SmartReader, VNPT Smartbot, LLM prompt layer |
| Render portfolio | HTML template -> PDF hoặc export trang portfolio |
| Deploy demo | Docker Compose hoặc Vercel/Render/Fly.io |

## 13. Mô hình dữ liệu sơ bộ

### 13.1. StudentProfile

- `id`
- `student_name`
- `student_code`
- `faculty`
- `class_name`
- `email`
- `phone`
- `status`

### 13.2. Criterion

- `id`
- `group_name`
- `criterion_name`
- `description`
- `required_evidence`
- `level`

### 13.3. Evidence

- `id`
- `profile_id`
- `file_url`
- `file_type`
- `ocr_text`
- `issued_by`
- `issued_date`
- `suggested_criteria`
- `confidence_score`
- `review_status`

### 13.4. Review

- `id`
- `profile_id`
- `reviewer_id`
- `ai_recommendation`
- `human_decision`
- `comment`
- `created_at`

## 14. Đánh giá kết quả MVP

Đội dự kiến đo MVP bằng các chỉ số:

- Tỉ lệ minh chứng mẫu được OCR thành công.
- Tỉ lệ minh chứng được phân loại đúng tiêu chí trong bộ dữ liệu demo.
- Thời gian sinh viên biết hồ sơ còn thiếu gì.
- Thời gian cán bộ sơ loại một hồ sơ.
- Số bước thao tác để sinh viên hoàn thiện hồ sơ.
- Mức độ dễ hiểu của phản hồi AI qua khảo sát nhanh.

Mục tiêu demo:

- Với một hồ sơ mẫu gồm 5-7 minh chứng, hệ thống có thể phân loại tối thiểu 70% minh chứng vào đúng nhóm tiêu chí.
- Sinh viên nhận được danh sách thiếu/đủ trong dưới 1 phút sau khi upload.
- Cán bộ có thể xem lý do gợi ý duyệt trong một màn hình.

## 15. Kế hoạch triển khai

### Giai đoạn Vòng 1 - Proposal

- Chốt tên sản phẩm, người dùng mục tiêu và pain-point.
- Viết proposal.
- Chuẩn bị wireframe 3 màn hình: sinh viên upload, báo cáo thiếu/đủ, dashboard cán bộ.
- Chuẩn bị sơ đồ kiến trúc và luồng dữ liệu.
- Nếu còn thời gian, quay video thuyết minh 2-3 phút.

### Giai đoạn Vòng 2 - MVP

| Ngày | Việc cần làm | Đầu ra |
|---:|---|---|
| Ngày 1 | Dựng repo, schema dữ liệu, UI skeleton | App chạy local |
| Ngày 2 | Làm upload minh chứng, lưu hồ sơ, mock tiêu chí | Luồng sinh viên cơ bản |
| Ngày 3 | Tích hợp SmartReader/OCR hoặc adapter giả lập nếu API chưa ổn định | Trích xuất nội dung minh chứng |
| Ngày 4 | Làm AI mapping minh chứng - tiêu chí, báo cáo thiếu/đủ | Báo cáo AI |
| Ngày 5 | Làm dashboard cán bộ, duyệt/yêu cầu bổ sung | Luồng cán bộ |
| Ngày 6 | Render portfolio, UX polish, xử lý lỗi | Demo gần hoàn chỉnh |
| Ngày 7 | Viết README, script test, chuẩn bị pitch/demo | Gói nộp Vòng 2 |

### Giai đoạn Chung kết

- Chuẩn bị phương án mở rộng theo nhiệm vụ bí mật.
- Tối ưu live-demo.
- Hoàn thiện pitch 10 phút.
- Chuẩn bị câu trả lời về dữ liệu, bảo mật, khả năng triển khai và chi phí vận hành.

## 16. Tác động dự kiến

### 16.1. Với sinh viên

- Biết sớm hồ sơ còn thiếu gì, giảm rủi ro nộp thiếu minh chứng.
- Được gợi ý hoạt động/chứng chỉ phù hợp để phát triển toàn diện.
- Có portfolio đẹp, tái sử dụng được cho học bổng, thực tập, tuyển dụng.

### 16.2. Với Đoàn - Hội

- Giảm thời gian sơ loại hồ sơ.
- Tăng tính nhất quán trong phản hồi.
- Dễ theo dõi số lượng hồ sơ, trạng thái và tiêu chí thường bị thiếu.
- Có dữ liệu để cải thiện công tác truyền thông phong trào Sinh viên 5 tốt.

### 16.3. Với nhà trường

- Tăng tỉ lệ sinh viên hiểu và tham gia phong trào.
- Có công cụ số hóa quy trình xét duyệt.
- Có dữ liệu tổng hợp về năng lực, hoạt động và nhu cầu hỗ trợ của sinh viên.

## 17. Chiến lược triển khai và mở rộng

### 17.1. Khách hàng/người dùng ban đầu

- Hội Sinh viên cấp khoa.
- Hội Sinh viên cấp trường.
- Các câu lạc bộ/đơn vị tổ chức hoạt động sinh viên.

### 17.2. Mô hình triển khai

- MVP dùng cho một khoa hoặc một trường.
- Sau khi ổn định, mở rộng bộ tiêu chí theo từng cấp xét.
- Cho phép cấu hình tiêu chí theo từng năm học.
- Tích hợp với hệ thống SSO/sinh viên của trường nếu triển khai thật.

### 17.3. Roadmap 12 tháng

| Giai đoạn | Mục tiêu |
|---|---|
| 0-3 tháng | Hoàn thiện MVP, thử nghiệm với một nhóm sinh viên/khoa |
| 3-6 tháng | Bổ sung cấu hình tiêu chí, export báo cáo, portfolio PDF |
| 6-9 tháng | Tích hợp xác thực sinh viên, dashboard thống kê cấp trường |
| 9-12 tháng | Mở rộng sang học bổng, hoạt động ngoại khóa, hồ sơ năng lực sinh viên |

## 18. Bảo mật và pháp lý

Vì hệ thống xử lý hồ sơ sinh viên và minh chứng cá nhân, đội xác định bảo mật là yêu cầu quan trọng ngay từ MVP.

Các nguyên tắc:

- Không lưu API key trong source code.
- Sử dụng biến môi trường và file `.env.example`.
- Phân quyền theo vai trò sinh viên/cán bộ.
- Sinh viên chỉ xem được hồ sơ của mình.
- Cán bộ chỉ xem hồ sơ thuộc phạm vi được phân quyền.
- Minh chứng nhạy cảm được lưu với đường dẫn bảo vệ, không public trực tiếp.
- Log hệ thống không ghi thông tin cá nhân nhạy cảm.
- Cho phép xóa dữ liệu demo sau cuộc thi.
- AI chỉ đưa ra gợi ý, quyết định cuối cùng thuộc về người duyệt.

## 19. Rủi ro và phương án xử lý

| Rủi ro | Tác động | Phương án xử lý |
|---|---|---|
| OCR đọc sai minh chứng ảnh mờ | Phân loại sai tiêu chí | Hiển thị confidence score, cho phép người dùng chỉnh sửa text |
| Tiêu chí Sinh viên 5 tốt có biến thể theo từng cấp/năm | Mapping chưa chính xác | Thiết kế bộ tiêu chí dạng cấu hình |
| AI gợi ý sai trạng thái hồ sơ | Ảnh hưởng kết quả xét duyệt | Không tự động duyệt cuối; bắt buộc cán bộ xác nhận |
| Thiếu dữ liệu thật để test | Demo kém thuyết phục | Tạo bộ hồ sơ mẫu và minh chứng giả lập hợp lý |
| API bên ngoài chậm/lỗi khi demo | Gián đoạn live-demo | Có cache kết quả OCR và fallback demo data |
| Dữ liệu cá nhân bị lộ | Rủi ro pháp lý/uy tín | Ẩn thông tin nhạy cảm, phân quyền, xóa dữ liệu demo |

## 20. Kịch bản demo đề xuất

1. Sinh viên đăng nhập và tạo hồ sơ Sinh viên 5 tốt.
2. Sinh viên upload 5 minh chứng: bảng điểm, chứng nhận tình nguyện, chứng nhận hội nhập, chứng chỉ thể lực, một minh chứng không hợp lệ.
3. Hệ thống OCR và phân loại minh chứng.
4. AI báo: đạt 3 tiêu chí, thiếu 1 tiêu chí, 1 minh chứng cần kiểm tra.
5. Sinh viên nhận gợi ý hoạt động/chứng chỉ cần bổ sung.
6. Sinh viên bấm render portfolio.
7. Cán bộ Đoàn - Hội đăng nhập dashboard.
8. Cán bộ xem hồ sơ, lý do AI gợi ý, duyệt hoặc yêu cầu bổ sung.

## 21. Kết luận

5Tot AI Portfolio giải quyết một vấn đề cụ thể trong công tác Hội và phong trào Sinh viên 5 tốt: sinh viên khó tự đối chiếu hồ sơ, cán bộ mất nhiều thời gian sơ loại và phản hồi. Giải pháp tận dụng AI để đọc minh chứng, phân loại theo tiêu chí, gợi ý bổ sung và hỗ trợ kiểm duyệt có giải thích. Với phạm vi MVP rõ ràng, khả năng demo end-to-end và hướng mở rộng sang portfolio năng lực sinh viên, dự án phù hợp với Bảng B - Challenger của HackAIthon 2026.

## 22. Nguồn tham khảo

- Thông báo số 1 HackAIthon 2026: `hackaithon-2026-thong-bao-so-1_1780034931.pdf`
- Bảng B - Challenger: <https://hackaithon.vsds.vn/bang-b-challenger/>
- Thể lệ Bảng B: <https://hackaithon.vsds.vn/the-le-bang-b/>

