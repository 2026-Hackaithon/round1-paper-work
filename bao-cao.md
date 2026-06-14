# Báo cáo rà soát proposal và flow xét duyệt Sinh viên 5 tốt

## 1. Phạm vi rà soát

Tài liệu được rà soát: `proposal-vong-1-template.md`.

Mục tiêu rà soát:

- Kiểm tra các phần nội dung trong proposal có thống nhất với nhau chưa.
- Đánh giá flow sản phẩm hiện tại có đáp ứng được quy trình nộp và xét duyệt Sinh viên 5 tốt đến **cấp Trung ương** hay chưa.
- Đề xuất phần cần bổ sung để proposal chặt chẽ hơn.

Quy trình xét duyệt liên cấp cần đối chiếu:

- **Cấp cơ sở:** Sinh viên hoàn thiện hồ sơ và nộp cho Hội Sinh viên trường, hoặc Đoàn trường nếu trường chưa có Hội Sinh viên.
- **Cấp tỉnh/thành:** Hội Sinh viên trường gửi hồ sơ lên Hội Sinh viên cấp tỉnh/thành phố để xét duyệt cấp tỉnh/thành.
- **Cấp Trung ương:** Hội Sinh viên cấp tỉnh/thành phố hoặc đơn vị trực thuộc tổng hợp, hoàn thiện hồ sơ và gửi văn bản đề nghị kèm danh sách chính thức lên Trung ương Hội Sinh viên Việt Nam.

## 2. Nhận xét tổng quan

Proposal hiện tại đã có nền tảng tốt cho một sản phẩm AI hỗ trợ phong trào Sinh viên 5 tốt. Các phần mạnh nhất là:

- Bài toán rõ: sinh viên khó theo dõi tiêu chí, cán bộ quá tải khi kiểm tra hồ sơ.
- Giải pháp có nhiều điểm AI hợp lý: OCR minh chứng, RAG chatbot, eKYC, gợi ý hoạt động, phân loại tiêu chí.
- Kiến trúc hệ thống tương đối đầy đủ cho MVP: frontend 2 vai trò, backend NestJS, OCR/LLM, database, object storage, cache.
- Có tư duy sản phẩm tốt: không chỉ nộp hồ sơ mà còn tạo CV/Portfolio và kết nối hoạt động.

Tuy nhiên, proposal hiện tại vẫn thiên về **cấp trường/cơ sở**. Nếu muốn chứng minh sản phẩm phục vụ được quy trình xét duyệt **cấp Trung ương**, cần bổ sung rõ workflow liên cấp, vai trò Hội Sinh viên tỉnh/thành, Trung ương Hội, cơ chế gửi danh sách chính thức và văn bản đề nghị.

## 3. Mức độ thống nhất nội dung

### 3.1. Những điểm đã thống nhất

Các phần sau đang tương đối khớp với nhau:

| Nội dung | Đánh giá |
|---|---|
| Vấn đề cần giải quyết | Thống nhất quanh pain-point sinh viên quên tiêu chí, cán bộ xét duyệt thủ công, hồ sơ rời rạc. |
| Người dùng chính | Có sinh viên và cán bộ Đoàn - Hội/Hội Sinh viên. |
| AI sử dụng | OCR/SmartReader, Smartbot/RAG, eKYC đều được nhắc nhất quán ở nhiều phần. |
| MVP | Tập trung vào core flow: đăng nhập 2 vai trò, upload minh chứng, OCR, phân loại 5 tiêu chí, dashboard sinh viên và cán bộ. |
| Kiến trúc | Đã bao được core flow MVP và có cache, storage, AI API, backend service. |
| Rủi ro | Có nhắc các rủi ro chính: thiếu dữ liệu, API lỗi, AI sai, bảo mật, tiêu chí thay đổi theo cấp/năm/trường. |

### 3.2. Những điểm chưa thống nhất hoặc cần làm rõ

| Vấn đề | Hiện trạng | Tác động | Đề xuất chỉnh |
|---|---|---|---|
| Tên sản phẩm chưa thống nhất | Có nơi dùng `AI-5Good`, có nơi dùng `AI-5Good (5T Assistant)`, file cũ/notes dùng `5Tot AI Portfolio`. | Làm proposal thiếu nhận diện thương hiệu rõ ràng. | Chọn một tên chính. Khuyến nghị: **AI-5Good**. Tên phụ/tagline: **Trợ lý AI cho hành trình Sinh viên 5 tốt**. |
| Trang bìa còn placeholder | Trang bìa vẫn có `<Tên ngắn...>`, `<Tên đội>`, `<Trường/đơn vị>`, `<dd/mm/yyyy>`. | Nếu xuất PDF sẽ trông chưa hoàn chỉnh. | Điền thông tin thật trước khi nộp hoặc ghi rõ là bản nháp nội bộ. |
| 6.2, 6.3, 6.4 còn trống | Bảng module chính, API/AI, dữ liệu sử dụng chưa được điền. | Đây là các phần quan trọng để chứng minh thiết kế tổng quan và tính khả thi. | Điền các module từ kiến trúc: Auth, Profile, Evidence, Criteria, Eval, Review, Portfolio, VoiceChat, UX; điền SmartReader/Smartbot/eKYC/SmartVoice/SmartUX; điền dữ liệu hồ sơ/minh chứng/tiêu chí/log. |
| 7.2, 7.3, 7.4, 7.6 còn thiếu | Backend đã có NestJS, nhưng Frontend/Database/Deploy/chi phí/roadmap còn trống. | Ảnh hưởng tiêu chí tính khả thi, chi phí, GTM. | Hoàn thiện stack: React/Vite hoặc Next.js, PostgreSQL, Redis, S3-compatible storage, Docker, Vercel/EC2. Bổ sung chi phí MVP và roadmap. |
| Claim quá mạnh về xác minh giả mạo | Có câu “Đảm bảo tính chính xác 100%” ở phần xác minh thật/giả minh chứng. | Dễ bị ban giám khảo phản biện vì AI/OCR và CSDL đối chiếu không thể đảm bảo 100%. | Sửa thành “tăng khả năng phát hiện bất thường”, “giảm đáng kể rủi ro giả mạo”, “đưa hồ sơ nghi ngờ vào trạng thái cần kiểm tra thủ công”. |
| Người dùng doanh nghiệp/CLB hơi rộng so với MVP | Tóm tắt và tác động nhắc doanh nghiệp/CLB khá nhiều, trong khi MVP không có module đầy đủ cho hai nhóm này. | Có thể làm scope bị rộng, giảm cảm giác khả thi. | Đưa CLB/doanh nghiệp vào phần mở rộng/roadmap, không đặt ngang hàng với luồng xét duyệt MVP. |
| “Auto Cross-check” chưa có kiến trúc/data source tương ứng | Có chức năng đối chiếu CSDL từ Trung ương/Trường, nhưng kiến trúc chưa có `Verification Source` hoặc `External Evidence Registry`. | Đây là tính năng quan trọng nhưng hiện chưa chứng minh được nguồn dữ liệu hợp pháp/khả thi. | Với MVP, ghi là mô phỏng bằng dữ liệu mẫu; bản mở rộng thêm `Verification Registry / Evidence Source Connector`. |
| Cấp xét chưa được mô hình hóa | Có nhắc tiêu chí theo trường/cấp/năm, nhưng chưa có workflow cơ sở → tỉnh/thành → Trung ương. | Chưa đủ để đáp ứng xét duyệt cấp Trung ương. | Bổ sung vai trò tổ chức, trạng thái hồ sơ theo cấp, batch hồ sơ, văn bản đề nghị, danh sách chính thức. |

## 4. Đánh giá flow hiện tại so với quy trình liên cấp

### 4.1. Cấp cơ sở

Flow hiện tại **đáp ứng khá tốt cấp cơ sở**.

Các phần đã có:

- Sinh viên tạo hồ sơ.
- Sinh viên upload minh chứng.
- OCR đọc minh chứng.
- AI phân loại vào 5 tiêu chí.
- Dashboard sinh viên hiển thị đạt/thiếu.
- Dashboard cán bộ xem hồ sơ, kết quả AI và duyệt/từ chối/yêu cầu bổ sung.
- Có phân quyền sinh viên/cán bộ.
- Có lưu hồ sơ, minh chứng, OCR text, trạng thái duyệt.

Điểm cần bổ sung cho cấp cơ sở:

- Vai trò **Hội Sinh viên trường** và **Đoàn trường nếu chưa có Hội Sinh viên** cần được ghi rõ trong mô hình quyền.
- Cần có trạng thái hồ sơ cấp cơ sở, ví dụ:
  - `draft`
  - `submitted_to_school`
  - `school_reviewing`
  - `school_request_changes`
  - `school_approved`
  - `school_rejected`
- Cần có thao tác “gửi lên cấp tỉnh/thành” sau khi trường duyệt.

### 4.2. Cấp tỉnh/thành

Flow hiện tại **chưa đáp ứng đầy đủ cấp tỉnh/thành**.

Hiện proposal mới mô tả “cán bộ Đoàn - Hội” khá chung, chủ yếu giống cán bộ cấp trường/khoa. Chưa có:

- Tài khoản/role Hội Sinh viên cấp tỉnh/thành.
- Dashboard riêng cho cấp tỉnh/thành.
- Luồng nhận hồ sơ từ nhiều trường.
- Cơ chế duyệt cấp tỉnh/thành.
- Cơ chế trả hồ sơ về trường để bổ sung.
- Cơ chế tổng hợp danh sách cấp tỉnh/thành.
- Trạng thái xét duyệt cấp tỉnh/thành.

Các trạng thái nên bổ sung:

- `submitted_to_province`
- `province_reviewing`
- `province_request_changes`
- `province_approved`
- `province_rejected`
- `selected_for_central_submission`

Module cần bổ sung:

- `Organization Service`: quản lý cấp trường, cấp tỉnh/thành, đơn vị trực thuộc.
- `Submission Batch Service`: gom hồ sơ từ nhiều trường thành một đợt gửi.
- `Province Review Service`: duyệt/nhận xét/trả bổ sung ở cấp tỉnh/thành.

### 4.3. Cấp Trung ương

Flow hiện tại **chưa đủ để nói là đáp ứng cấp Trung ương**.

Quy trình cấp Trung ương yêu cầu: Hội Sinh viên cấp tỉnh/thành phố hoặc đơn vị trực thuộc **tổng hợp, hoàn thiện hồ sơ và gửi văn bản đề nghị kèm danh sách chính thức** lên Trung ương Hội Sinh viên Việt Nam.

Proposal hiện tại chưa có:

- Vai trò Trung ương Hội Sinh viên Việt Nam.
- Vai trò Hội Sinh viên tỉnh/thành hoặc đơn vị trực thuộc như cấp gửi hồ sơ chính thức.
- Chức năng tổng hợp danh sách chính thức cấp tỉnh/thành.
- Chức năng tạo/gắn **văn bản đề nghị**.
- Chức năng khóa danh sách sau khi gửi.
- Chức năng Trung ương tiếp nhận, kiểm tra, phản hồi, duyệt cuối.
- Audit trail liên cấp.
- Export đúng định dạng danh sách/văn bản phục vụ quy trình hành chính.

Các trạng thái nên bổ sung:

- `central_package_draft`
- `central_package_submitted`
- `central_received`
- `central_reviewing`
- `central_request_changes`
- `central_approved`
- `central_rejected`
- `central_finalized`

Module cần bổ sung:

- `Central Submission Service`: tạo gói hồ sơ gửi Trung ương.
- `Official Document Service`: quản lý văn bản đề nghị, số văn bản, ngày ký, đơn vị gửi, file đính kèm.
- `Official List Export`: xuất danh sách chính thức theo mẫu.
- `Central Review Dashboard`: dashboard tiếp nhận và xét duyệt cấp Trung ương.
- `Audit Log Service`: ghi lịch sử thao tác liên cấp.
- `Notification Service`: thông báo trả bổ sung/đã tiếp nhận/đã duyệt.

## 5. Đánh giá kiến trúc hiện tại

### 5.1. Kiến trúc hiện tại đáp ứng tốt MVP cấp trường

Kiến trúc hiện tại gồm:

- `Auth & Role-based Access`
- `Profile Service`
- `Evidence Service`
- `Criteria Service`
- `AI Evaluation Engine`
- `Review Service`
- `Portfolio Service`
- `Voice/Chat Service`
- `Analytics/UX Service`
- `Database`
- `Object Storage`
- `Redis Cache`
- `VNPT SmartReader`, `VNPT Smartbot`, `VNPT eKYC`, `VNPT SmartVoice`, `VNPT SmartUX`

Như vậy, kiến trúc đủ cho core flow:

```text
Sinh viên tạo hồ sơ
-> upload minh chứng
-> OCR
-> AI phân loại tiêu chí
-> cán bộ trường/cơ sở duyệt
-> sinh viên xem kết quả/portfolio
```

### 5.2. Kiến trúc chưa đủ cho flow liên cấp

Để đáp ứng cấp Trung ương, kiến trúc cần thêm lớp tổ chức và quy trình liên cấp:

```text
Sinh viên
-> Hội Sinh viên trường / Đoàn trường
-> Hội Sinh viên tỉnh/thành
-> Trung ương Hội Sinh viên Việt Nam
```

Kiến trúc hiện tại chỉ có 2 lane:

- Sinh viên
- Cán bộ Đoàn - Hội

Lane “Cán bộ Đoàn - Hội” đang quá chung. Nên tách thành:

- Cán bộ cấp cơ sở/trường.
- Cán bộ cấp tỉnh/thành.
- Cán bộ cấp Trung ương.

Hoặc nếu không muốn vẽ quá phức tạp trong MVP, cần ghi rõ:

- MVP xử lý cấp cơ sở.
- Roadmap mở rộng hỗ trợ cấp tỉnh/thành và Trung ương.

## 6. Flow đề xuất để đáp ứng cấp Trung ương

### 6.1. Vai trò cần có

| Vai trò | Quyền chính |
|---|---|
| Sinh viên | Tạo hồ sơ, upload minh chứng, theo dõi thiếu/đủ, gửi hồ sơ lên cấp cơ sở. |
| Cán bộ cấp cơ sở/trường | Xem hồ sơ sinh viên thuộc trường, yêu cầu bổ sung, duyệt/từ chối, lập danh sách gửi cấp tỉnh/thành. |
| Cán bộ cấp tỉnh/thành | Nhận hồ sơ từ nhiều trường, xét duyệt cấp tỉnh/thành, trả bổ sung, chọn danh sách gửi Trung ương. |
| Cán bộ đơn vị trực thuộc | Có quyền tương tự cấp tỉnh/thành nếu là đơn vị được gửi trực tiếp. |
| Cán bộ Trung ương | Nhận văn bản đề nghị và danh sách chính thức, kiểm tra, phản hồi, duyệt cuối. |
| Admin hệ thống | Cấu hình năm xét, cấp xét, tiêu chí, đơn vị, biểu mẫu, phân quyền. |

### 6.2. Trạng thái hồ sơ đề xuất

```text
draft
submitted_to_school
school_reviewing
school_request_changes
school_approved
school_rejected
submitted_to_province
province_reviewing
province_request_changes
province_approved
province_rejected
selected_for_central_submission
central_package_draft
central_package_submitted
central_received
central_reviewing
central_request_changes
central_approved
central_rejected
central_finalized
```

### 6.3. Flow nghiệp vụ đề xuất

1. Sinh viên tạo hồ sơ, upload minh chứng, nhận đánh giá sơ bộ.
2. Sinh viên bấm “Nộp cấp cơ sở”.
3. Hội Sinh viên trường hoặc Đoàn trường xét duyệt.
4. Nếu thiếu, hồ sơ trả về sinh viên để bổ sung.
5. Nếu đạt, cấp cơ sở đưa hồ sơ vào danh sách gửi tỉnh/thành.
6. Hội Sinh viên tỉnh/thành nhận danh sách từ nhiều trường.
7. Cấp tỉnh/thành xét duyệt, yêu cầu trường bổ sung nếu cần.
8. Cấp tỉnh/thành chốt danh sách chính thức đề nghị Trung ương.
9. Hệ thống tạo gói gửi Trung ương gồm:
   - danh sách chính thức,
   - văn bản đề nghị,
   - hồ sơ/minh chứng số hóa,
   - lịch sử xét duyệt.
10. Trung ương tiếp nhận, kiểm tra, phản hồi hoặc duyệt cuối.
11. Kết quả cuối cùng được trả về cấp tỉnh/thành, cấp cơ sở và sinh viên.

## 7. Đề xuất chỉnh proposal

### 7.1. Nếu muốn giữ scope MVP gọn

Nên ghi rõ:

> MVP trong HackAIthon tập trung chứng minh luồng cấp cơ sở: sinh viên nộp hồ sơ, AI xử lý minh chứng, cán bộ Hội Sinh viên trường/Đoàn trường duyệt sơ bộ. Flow cấp tỉnh/thành và Trung ương được thiết kế trong roadmap mở rộng bằng các module Submission Batch, Organization, Official Document và Central Review.

Cách này giúp proposal khả thi hơn, tránh bị hỏi vì sao 1 tuần MVP mà làm cả quy trình Trung ương.

### 7.2. Nếu muốn claim có khả năng phục vụ cấp Trung ương

Cần bổ sung vào proposal:

- Vai trò cấp tỉnh/thành và Trung ương trong mục người dùng.
- Module `Organization Service`.
- Module `Submission Batch Service`.
- Module `Official Document Service`.
- Module `Central Review Dashboard`.
- Trạng thái hồ sơ theo cấp.
- Export danh sách chính thức và văn bản đề nghị.
- Audit log liên cấp.
- Phân quyền theo tổ chức và cấp xét.

### 7.3. Nên hoàn thiện các phần còn trống

Các phần cần điền trước khi nộp:

- Trang bìa.
- Thông tin đội thi.
- 6.2 Các module chính.
- 6.3 API/AI dự kiến sử dụng.
- 6.4 Dữ liệu sử dụng.
- 7.2 Kế hoạch kỹ thuật build/deploy.
- 7.3 Nguồn lực nhân sự.
- 7.4 Ước tính chi phí.
- 7.6 Roadmap.
- 10 Link video nếu có.
- 11 Phụ lục: Figma, ảnh kiến trúc, nguồn tham khảo.

## 8. Kết luận

Proposal hiện tại **đã đủ mạnh để trình bày một MVP cấp cơ sở/trường** cho bài toán Sinh viên 5 tốt. Core flow hiện tại phù hợp với HackAIthon vì có thể demo trong thời gian ngắn:

```text
Sinh viên -> upload minh chứng -> OCR -> AI phân loại -> cán bộ duyệt -> dashboard/portfolio
```

Tuy nhiên, flow hiện tại **chưa đủ để khẳng định đáp ứng hoàn chỉnh quy trình xét duyệt cấp Trung ương**. Để phục vụ cấp Trung ương, hệ thống phải hỗ trợ workflow liên cấp:

```text
Cấp cơ sở -> cấp tỉnh/thành -> cấp Trung ương
```

Khuyến nghị chiến lược:

- Trong proposal Vòng 1, trình bày MVP là **luồng cấp cơ sở**.
- Ghi rõ thiết kế mở rộng cho cấp tỉnh/thành và Trung ương trong roadmap.
- Nếu muốn nhấn mạnh tiềm năng toàn quốc, bổ sung module liên cấp và chức năng văn bản đề nghị/danh sách chính thức, nhưng không nên cam kết làm hết trong MVP 1 tuần.

