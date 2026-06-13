# Template Proposal Vòng 1 - HackAIthon 2026

> Dùng để soạn bản miêu tả ý tưởng. Sau khi hoàn thiện, có thể trình bày lại bằng `.docx`, `.pptx` hoặc công cụ thiết kế khác và xuất sang `.pdf` để nộp.

## Trang bìa

- **Tên sản phẩm/dự án:** `<Tên ngắn, dễ nhớ, gợi đúng vấn đề>`
- **Bảng thi:** Bảng B - Challenger
- **Hướng đề tài:** `<Chọn hướng đề tài theo BTC>`
- **Tên đội:** `<Tên đội>`
- **Trường/đơn vị:** `<Tên trường/đơn vị>`
- **Ngày nộp:** `<dd/mm/yyyy>`

## 1. Thông tin đội thi

| STT | Họ tên | Trường/Lớp/Khoa | Vai trò trong đội | Email | Số điện thoại |
|---:|---|---|---|---|---|
| 1 |  |  | Trưởng nhóm/Product |  |  |
| 2 |  |  | Kỹ thuật/Backend |  |  |
| 3 |  |  | Frontend/UI/UX |  |  |
| 4 |  |  | AI/Data/Prompt |  |  |
| 5 |  |  | Research/Pitch |  |  |

**Người đại diện liên hệ:** `<Họ tên - SĐT - Email>`

## 2. Tóm tắt ý tưởng

Viết 1-2 đoạn ngắn, trả lời nhanh:

- Sản phẩm giải quyết vấn đề gì?
- Người dùng chính là ai?
- AI được dùng ở đâu?
- Kết quả/tác động kỳ vọng là gì?

**Gợi ý viết:**

`<Tên sản phẩm>` là `<loại sản phẩm/nền tảng/trợ lý>` giúp `<nhóm người dùng>` giải quyết vấn đề `<vấn đề chính>`. Hệ thống sử dụng AI để `<năng lực AI chính>`, từ đó giúp `<lợi ích cụ thể>`. Giải pháp hướng tới `<tác động xã hội/kinh doanh>` và có thể triển khai trước ở `<phạm vi ban đầu>`.

## 3. Đặt vấn đề

### 3.1. Bối cảnh

Mô tả bối cảnh thực tế dẫn tới vấn đề:

- Vấn đề đang xảy ra ở đâu?
- Ai đang bị ảnh hưởng?
- Quy trình hiện tại đang làm như thế nào?
- Vì sao đây là bài toán đáng giải quyết?

**Nội dung cần điền:**

`<Viết 2-4 đoạn mô tả bối cảnh. Nên có dẫn chứng thực tế, quan sát từ trường/đơn vị, số lượng người dùng liên quan hoặc quy trình hiện tại.>`

### 3.2. Khách hàng mục tiêu và người dùng cuối

| Nhóm | Mô tả | Pain-point chính | Nhu cầu |
|---|---|---|---|
| Khách hàng/đơn vị triển khai |  |  |  |
| Người dùng cuối 1 |  |  |  |
| Người dùng cuối 2 |  |  |  |

### 3.3. Pain-point có số liệu chứng minh

Trình bày pain-point theo cấu trúc: **vấn đề - bằng chứng - hậu quả**.

| Pain-point | Số liệu/dẫn chứng | Hậu quả nếu không giải quyết |
|---|---|---|
|  |  |  |
|  |  |  |
|  |  |  |

**Gợi ý nguồn số liệu:**

- Khảo sát nhanh sinh viên/người dùng mục tiêu.
- Số lượng hồ sơ/quy trình đang xử lý thực tế.
- Thời gian xử lý trung bình hiện tại.
- Báo cáo công khai, thống kê của trường/đơn vị/nhà nước.
- Quan sát hoặc phỏng vấn ngắn với người dùng.

## 4. Cách giải quyết

### 4.1. Giải pháp đề xuất

**AI-5Good (5T Assistant)** là một nền tảng Web App tích hợp AI đóng vai trò như một trợ lý ảo 24/7, đồng hành cùng sinh viên trong suốt quá trình phấn đấu danh hiệu "Sinh viên 5 tốt". Sản phẩm số hóa toàn bộ hành trình từ việc tìm hiểu quy chế, theo dõi tiến độ, thu thập minh chứng cho đến lúc nộp hồ sơ xét duyệt. Thay vì để sinh viên tự xoay sở một cách thụ động, hệ thống chủ động hướng dẫn, đánh giá sơ bộ và nhắc nhở họ hoàn thiện các tiêu chí còn thiếu.

Với giải pháp này, bài toán quá tải ở phía Hội Sinh viên được giải quyết triệt để thông qua một Dashboard quản lý tập trung. Các nghiệp vụ thủ công như đọc, đối chiếu giấy khen, kiểm tra thông tin sinh viên đều được tự động hóa bằng AI (OCR và eKYC). Cán bộ Hội thay vì mất hàng tuần để rà soát hàng ngàn hồ sơ bản cứng, nay chỉ cần kiểm tra lại các trường hợp bất thường đã được AI đánh dấu và xuất báo cáo danh sách đề xuất khen thưởng một cách nhanh chóng.

### 4.2. Nhóm chức năng chính

| Nhóm chức năng | Người dùng | Mô tả | Giá trị mang lại |
|---|---|---|---|
| **Trợ lý 5 Tốt (Chatbot 24/7)** | Sinh viên | Giải đáp thắc mắc về quy chế, điều kiện xét chọn của từng trường. Nhắc nhở deadline, hướng dẫn sinh viên bổ sung hồ sơ. | Giúp sinh viên hiểu rõ tiêu chí, luôn có người hướng dẫn bất kỳ lúc nào, giảm sai sót hồ sơ từ đầu nguồn. |
| **Bản đồ sự kiện & Gợi ý hoạt động** | Sinh viên, CLB/Đội/Nhóm | Hợp tác với các CLB/Đoàn/Hội để tổng hợp danh sách sự kiện trên hệ thống. Dựa trên tiêu chí sinh viên đang thiếu, AI cá nhân hóa và đề xuất sự kiện phù hợp nhất để tham gia. | Giúp sinh viên dễ dàng tìm hoạt động bù đắp tiêu chí thiếu; giúp các CLB tiếp cận đúng tệp sinh viên mục tiêu. |
| **Quản lý tiến độ & Tự động chấm điểm** | Sinh viên | Hệ thống tự động tính toán điểm sơ bộ (ví dụ: Đạt 4/5 tiêu chí). Cho phép sinh viên upload minh chứng và theo dõi hành trình cá nhân. | Khắc phục tình trạng sinh viên quên hoặc không biết mình còn thiếu gì, tăng tỷ lệ sinh viên theo đuổi danh hiệu đến cùng. |
| **Xử lý minh chứng tự động (OCR & eKYC)** | Cán bộ Hội, Sinh viên | Bóc tách thông tin từ ảnh giấy khen, chứng chỉ PDF. Xác thực khuôn mặt với CCCD/thẻ sinh viên để chống giả mạo. | Giảm 60-70% thời gian nhập liệu thủ công; chuẩn hóa dữ liệu đầu vào. |
| **Đối chiếu chéo CSDL (Auto Cross-check)** | Cán bộ Hội | Tự động truy vấn thông tin minh chứng vừa bóc tách và đối chiếu với Cơ sở dữ liệu tập trung (từ Trung ương/Trường). Trùng khớp là Pass. | Loại bỏ hoàn toàn khâu duyệt thật/giả thủ công; giải quyết triệt để vấn đề gian lận giấy tờ; duyệt hồ sơ tính bằng giây. |
| **Dashboard Tổng hợp & Phân tích** | Cán bộ Hội | Quản lý toàn bộ hồ sơ đăng ký. AI tóm tắt nhanh hồ sơ, lọc và phân loại sinh viên đạt/chưa đạt chuẩn. Xuất báo cáo tổng hợp. | Xóa bỏ tình trạng quá tải cuối kỳ, giúp cán bộ theo dõi sát sao phong trào trong toàn trường và ra quyết định nhanh, chính xác. |

### 4.3. Luồng sử dụng chính

1. **Bước 1: Tìm hiểu & Đăng ký:** Sinh viên truy cập ứng dụng, trò chuyện với VNPT Smartbot để hiểu về quy chế. Sau đó, sinh viên tạo hồ sơ và xác thực danh tính qua VNPT eKYC.
2. **Bước 2: Cập nhật tiến độ & Tự đánh giá:** Có 2 hình thức ghi nhận: (1) Với các hoạt động nội bộ (vd: Thanh niên khỏe), dữ liệu từ Ban tổ chức sẽ được **tự động đồng bộ**. Trường hợp sinh viên đã tham gia nhưng hệ thống chưa ghi nhận (do lỗi điểm danh/sai mã SV), sinh viên sử dụng nút **"Khiếu nại/Yêu cầu cập nhật"** kèm ảnh check-in để cán bộ rà soát lại. (2) Với chứng chỉ bên ngoài (vd: IELTS), sinh viên upload ảnh, VNPT SmartReader bóc tách thông tin và tự động đối chiếu CSDL để xác thực "Pass".
3. **Bước 3: Nhắc nhở & Bổ sung:** Hệ thống liên tục so sánh tiến độ với quy chế. Nếu thiếu, Smartbot sẽ gửi thông báo nhắc nhở và tự động kết nối dữ liệu từ các CLB/Đoàn/Hội đối tác để gợi ý những sự kiện đang mở đơn phù hợp nhất, giúp sinh viên bù đắp tiêu chí.
4. **Bước 4: Nộp hồ sơ xét duyệt:** Cuối kỳ, hệ thống chấm điểm sơ bộ. Sinh viên chỉ cần kiểm tra lại và bấm "Nộp hồ sơ" với tập dữ liệu đã được số hóa, chuẩn hóa.
5. **Bước 5: Duyệt và xuất kết quả:** Cán bộ Hội mở Dashboard, xem danh sách hồ sơ đã được AI tóm tắt và phân loại sẵn. Cán bộ chỉ cần duyệt xác nhận cuối cùng và xuất danh sách khen thưởng dễ dàng.

### 4.4. Vì sao cần AI?

Giải thích rõ AI tạo giá trị gì mà cách truyền thống khó làm được.

| Tác vụ | Nếu không dùng AI | Khi dùng AI (VNPT SmartReader, Smartbot, eKYC) | Giá trị tạo ra |
|---|---|---|---|
| **Kiểm tra và nhập liệu minh chứng** | Cán bộ phải đọc từng tờ giấy khen, gõ lại tên, ngày tháng, nội dung vào file Excel. Dễ hoa mắt, nhập sai. | SmartReader bóc tách tức thì (tên, điểm số, ngày cấp) từ ảnh/PDF và tự động điền vào hệ thống. | Tiết kiệm hàng trăm giờ làm việc (giảm 60-70% thời gian), độ chính xác cao, chuẩn hóa dữ liệu. |
| **Tư vấn và hướng dẫn sinh viên** | Sinh viên phải nhắn tin hỏi Fanpage Đoàn/Hội, đợi admin trả lời hoặc tự đọc văn bản quy chế dài hàng chục trang. | Smartbot (LLM) trả lời tự nhiên, tức thời 24/7 theo đúng ngữ cảnh và quy chế riêng của trường. | Trải nghiệm thân thiện, sinh viên nắm rõ thông tin, cán bộ Hội không bị quá tải tin nhắn hỗ trợ. |
| **Xác minh danh tính** | Cán bộ phải nhìn ảnh thẻ trên hồ sơ và đối chiếu bằng mắt với thẻ sinh viên thực tế (hoặc dễ dàng bị bỏ qua do quá tải). | Hệ thống dùng eKYC so sánh khuôn mặt lúc làm hồ sơ với ảnh trên CCCD/Thẻ SV tự động. | Ngăn chặn gian lận hồ sơ, tăng tính minh bạch và uy tín cho toàn bộ hệ thống xét duyệt. |
| **Tổng hợp và đánh giá hồ sơ** | Cán bộ tự phân loại thủ công, xem sinh viên này thiếu tiêu chí nào, đạt hay chưa đạt để duyệt. | Logic hệ thống kết hợp AI đánh giá sơ bộ, đưa ra kết luận "Đạt/Không đạt" và tóm tắt lý do. | Rút ngắn thời gian ra quyết định, hỗ trợ duyệt hồ sơ hàng loạt một cách nhanh chóng, tránh sai sót thủ công. |
| **Xác minh thật/giả của minh chứng** | Cán bộ soi từng dấu mộc, chữ ký bằng mắt thường, không thể phát hiện nếu PTS tinh vi. Dễ để lọt hồ sơ giả mạo. | Nhờ AI (OCR) đọc dữ liệu từ ảnh sang dạng text, hệ thống mới có thể lấy text đó tự động truy vấn đối chiếu với CSDL. | Đảm bảo tính chính xác 100%, tự động hóa khâu chống gian lận, không để lọt giấy tờ giả mạo. |

## 5. Tính đổi mới và khác biệt

### 5.1. Giải pháp hiện có

Liệt kê các sản phẩm, quy trình, phần mềm, thư viện open-source hoặc cách làm thủ công hiện tại.

| Giải pháp hiện có | Mô tả ngắn | Hạn chế |
|---|---|---|
|  |  |  |
|  |  |  |
|  |  |  |

### 5.2. So sánh khác biệt

Tiêu chí đạt khi chứng minh không có sản phẩm tương tự hoặc khác biệt tối thiểu khoảng 30% tính năng cốt lõi.

| Tiêu chí so sánh | Giải pháp hiện có | Sản phẩm đề xuất | Khác biệt |
|---|---|---|---|
| Đối tượng phục vụ |  |  |  |
| Tính năng lõi |  |  |  |
| Mức độ dùng AI |  |  |  |
| Trải nghiệm người dùng |  |  |  |
| Khả năng triển khai |  |  |  |
| Giá trị/tác động |  |  |  |

### 5.3. Điểm mới nổi bật

- `<Điểm mới 1>`
- `<Điểm mới 2>`
- `<Điểm mới 3>`

## 6. Thiết kế tổng quan

### 6.1. Kiến trúc hệ thống

Chèn sơ đồ kiến trúc hoặc mô tả bằng text.

```text
Người dùng
    |
    v
Ứng dụng Web/Mobile/Chatbot
    |
    v
Backend/API
    |
    +-- Module nghiệp vụ
    +-- Module AI
    +-- Module quản lý dữ liệu
    +-- Module báo cáo/dashboard
    |
    v
Cơ sở dữ liệu / Lưu trữ file
    |
    +-- API/AI service của BTC
    +-- Dịch vụ bên ngoài nếu có
```

### 6.2. Các module chính

| Module | Chức năng | Input | Output |
|---|---|---|---|
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

### 6.3. API/AI dự kiến sử dụng

| API/AI | Mục đích sử dụng | Giai đoạn MVP hay mở rộng |
|---|---|---|
|  |  | MVP |
|  |  | MVP |
|  |  | Mở rộng |

### 6.4. Dữ liệu sử dụng

| Loại dữ liệu | Nguồn dữ liệu | Tính hợp pháp | Cách lưu trữ/bảo vệ |
|---|---|---|---|
|  |  |  |  |
|  |  |  |  |

## 7. Phương hướng triển khai

### 7.1. Phạm vi MVP

MVP cần chứng minh được luồng giá trị chính, không cần làm toàn bộ sản phẩm.

**Chức năng bắt buộc trong MVP:**

- [ ] `<Chức năng 1>`
- [ ] `<Chức năng 2>`
- [ ] `<Chức năng 3>`
- [ ] `<Chức năng 4>`

**Chức năng mở rộng nếu còn thời gian:**

- [ ] `<Chức năng mở rộng 1>`
- [ ] `<Chức năng mở rộng 2>`

### 7.2. Kế hoạch kỹ thuật build/deploy

| Thành phần | Công nghệ dự kiến | Lý do chọn |
|---|---|---|
| Frontend |  |  |
| Backend |  |  |
| Database |  |  |
| AI/API |  |  |
| Deploy |  |  |

### 7.3. Nguồn lực nhân sự

| Vai trò | Người phụ trách | Công việc chính |
|---|---|---|
| Product/PM |  |  |
| Frontend |  |  |
| Backend |  |  |
| AI/Data |  |  |
| UX/UI |  |  |
| Pitch/Business |  |  |

### 7.4. Ước tính chi phí hạ tầng và vận hành

| Hạng mục | Chi phí MVP | Chi phí khi mở rộng | Ghi chú |
|---|---:|---:|---|
| Hosting frontend/backend |  |  |  |
| Database/storage |  |  |  |
| API/AI usage |  |  |  |
| Monitoring/logging |  |  |  |
| Tổng dự kiến |  |  |  |

### 7.5. An toàn, bảo mật và pháp lý

- Dữ liệu cá nhân nào được thu thập?
- Có xin sự đồng ý của người dùng không?
- Ai có quyền xem/sửa/xóa dữ liệu?
- API key được lưu ở đâu?
- Dữ liệu demo sau cuộc thi được xử lý thế nào?
- Giải pháp có tuân thủ quy định bảo vệ dữ liệu cá nhân tại Việt Nam không?

**Cam kết thiết kế:**

- [ ] Không commit API key/token thật lên repo.
- [ ] Có phân quyền theo vai trò.
- [ ] Không công khai file/dữ liệu nhạy cảm.
- [ ] Có cơ chế xóa hoặc ẩn dữ liệu demo.
- [ ] AI chỉ hỗ trợ/gợi ý, quyết định quan trọng vẫn có người xác nhận.

### 7.6. Roadmap sau cuộc thi / GTM

| Giai đoạn | Thời gian | Mục tiêu | Đầu ra |
|---|---|---|---|
| Pilot | 0-3 tháng |  |  |
| Mở rộng ban đầu | 3-6 tháng |  |  |
| Tối ưu sản phẩm | 6-9 tháng |  |  |
| Triển khai rộng | 9-12 tháng |  |  |

## 8. Tác động dự kiến

### 8.1. Lợi ích xã hội/kinh doanh

| Nhóm hưởng lợi | Lợi ích cụ thể | Cách đo lường |
|---|---|---|
|  |  |  |
|  |  |  |
|  |  |  |

### 8.2. TAM - SAM - SOM hoặc người dùng tiềm năng

Nếu có thể ước tính thị trường/người dùng, trình bày theo bảng:

| Chỉ số | Định nghĩa trong bài toán | Ước tính | Cơ sở ước tính |
|---|---|---:|---|
| TAM | Tổng thị trường/người dùng có thể phục vụ |  |  |
| SAM | Phân khúc có thể tiếp cận trong 1-2 năm |  |  |
| SOM | Phần có thể đạt được giai đoạn đầu |  |  |

Nếu chưa phù hợp TAM-SAM-SOM, có thể thay bằng:

- Tổng số người dùng tiềm năng.
- Số đơn vị/trường/tổ chức có thể triển khai.
- Số quy trình/hồ sơ/giao dịch có thể xử lý mỗi năm.

### 8.3. Ưu thế cạnh tranh

- `<Ưu thế 1: dữ liệu/domain insight/đối tác/quy trình>`
- `<Ưu thế 2: trải nghiệm người dùng/API/AI workflow>`
- `<Ưu thế 3: khả năng triển khai nhanh/chi phí thấp/mở rộng>`

### 8.4. Mô hình doanh thu hoặc giá trị mang lại

| Mô hình | Mô tả | Phù hợp giai đoạn nào |
|---|---|---|
| Miễn phí/pilot |  |  |
| Thu phí theo đơn vị triển khai |  |  |
| Thu phí theo số người dùng/giao dịch |  |  |
| Giá trị phi lợi nhuận/xã hội |  |  |

## 9. Rủi ro và phương án giảm thiểu

| Rủi ro | Mức độ ảnh hưởng | Phương án giảm thiểu |
|---|---|---|
| Thiếu dữ liệu thực tế | Cao/Trung bình/Thấp |  |
| API lỗi/chậm khi demo | Cao/Trung bình/Thấp |  |
| AI trả kết quả sai | Cao/Trung bình/Thấp |  |
| Vấn đề bảo mật/pháp lý | Cao/Trung bình/Thấp |  |
| Không đủ thời gian build MVP | Cao/Trung bình/Thấp |  |

## 10. Video thuyết minh

Video không bắt buộc, nhưng nếu có nên dài khoảng 2-3 phút.

**Kịch bản gợi ý:**

1. Giới thiệu đội và tên sản phẩm.
2. Nêu vấn đề/pain-point bằng một ví dụ cụ thể.
3. Mô tả giải pháp và luồng sử dụng chính.
4. Chỉ rõ AI/API được dùng ở đâu.
5. Nêu tác động và khả năng triển khai MVP.

**Link video:** `<Dán link nếu có>`

## 11. Phụ lục

### 11.1. Wireframe/Figma

- Link Figma: `<Dán link>`
- Ảnh minh họa màn hình chính:
  - Màn hình 1: `<Tên màn hình>`
  - Màn hình 2: `<Tên màn hình>`
  - Màn hình 3: `<Tên màn hình>`

### 11.2. Sơ đồ kiến trúc

- Link ảnh/sơ đồ: `<Dán link hoặc chèn ảnh khi xuất PDF>`

### 11.3. Tài liệu tham khảo

- Thông báo số 1 HackAIthon 2026: `hackaithon-2026-thong-bao-so-1_1780034931.pdf`
- Trang cuộc thi: `<Dán link chính thức>`
- Thể lệ bảng thi: `<Dán link chính thức>`
- Nguồn số liệu/dẫn chứng: `<Dán link hoặc ghi rõ nguồn>`

## 12. Checklist tự đánh giá trước khi nộp

### 12.1. Tính phù hợp đề bài

- [ ] Bám sát một hướng đề tài của BTC.
- [ ] Có phân tích khách hàng mục tiêu và người dùng cuối.
- [ ] Có pain-point rõ ràng.
- [ ] Có số liệu/dẫn chứng thực tế.
- [ ] Có giải thích "vì sao AI".

### 12.2. Tính đổi mới và khác biệt

- [ ] Có liệt kê giải pháp tương tự/hiện có.
- [ ] Có so sánh với giải pháp tương tự hoặc open-source.
- [ ] Có chứng minh điểm khác biệt cốt lõi.
- [ ] Có nêu rõ sản phẩm khác biệt ở tính năng, dữ liệu, workflow, UX hoặc mô hình triển khai.

### 12.3. Tính khả thi

- [ ] Nguồn dữ liệu hợp pháp.
- [ ] Nhân lực triển khai phù hợp.
- [ ] Kỹ thuật build/deploy khả thi.
- [ ] Có ước tính chi phí hạ tầng và vận hành.
- [ ] Có phương án bảo mật và pháp lý.
- [ ] Có roadmap/GTM sau cuộc thi.

### 12.4. Tác động dự kiến

- [ ] Có nêu lợi ích xã hội/kinh doanh.
- [ ] Có ước tính người dùng tiềm năng hoặc TAM-SAM-SOM.
- [ ] Có phân tích ưu thế cạnh tranh.
- [ ] Có mô hình doanh thu hoặc giá trị mang lại.

### 12.5. Chất lượng hồ sơ

- [ ] Proposal trình bày logic, dễ đọc.
- [ ] Có sơ đồ kiến trúc.
- [ ] Có wireframe hoặc hình minh họa sản phẩm.
- [ ] Ngôn ngữ rõ ràng, không lỗi chính tả.
- [ ] File cuối được xuất PDF đúng định dạng.

