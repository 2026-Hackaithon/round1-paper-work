# Proposal Vòng 1 - AI-5Good

> Bản nháp proposal bám theo `proposal-vong-1-template.md`. Hiện chỉ hoàn thiện các mục **2. Tóm tắt ý tưởng**, **3. Đặt vấn đề** và **5. Tính đổi mới và khác biệt**; các mục còn lại giữ ở dạng khung điền thông tin.

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

**AI-5Good** là nền tảng Web App hỗ trợ số hóa và nâng cấp toàn bộ hành trình phấn đấu danh hiệu **Sinh viên 5 tốt**. Sản phẩm giúp sinh viên theo dõi tiến độ theo 5 tiêu chí, nộp minh chứng dễ hơn, được nhắc nhở tiêu chí còn thiếu và chuyển đổi thành tích thành **CV/Portfolio** có thể dùng cho thực tập, tuyển dụng hoặc học bổng.

Với nhà trường, Đoàn Thanh niên và Hội Sinh viên, AI-5Good giải quyết tình trạng quá tải khi xét duyệt hồ sơ thủ công. Thay vì cán bộ phải đọc từng giấy khen, chứng chỉ và đối chiếu bằng mắt thường, hệ thống sử dụng **OCR/Computer Vision** để đọc minh chứng, đề xuất phân loại theo tiêu chí và hỗ trợ tổng hợp hồ sơ trên dashboard quản lý.

Hệ thống cũng sử dụng **RAG Chatbot** để trả lời câu hỏi về quy chế Sinh viên 5 tốt theo từng trường, **eKYC** để tăng độ tin cậy của danh tính và **gợi ý hoạt động** dựa trên tiêu chí sinh viên còn thiếu. Mục tiêu của sản phẩm không chỉ là giảm thời gian xử lý hồ sơ, mà còn tạo một hệ sinh thái kết nối **Sinh viên - Nhà trường - CLB/Đội/Nhóm - Doanh nghiệp** quanh dữ liệu thành tích đã được xác thực.

## 3. Đặt vấn đề

### 3.1. Bối cảnh

Phong trào **Sinh viên 5 tốt** là một chương trình quan trọng tại các trường đại học, nhằm khuyến khích sinh viên phát triển toàn diện ở các nhóm tiêu chí như đạo đức, học tập, thể lực, tình nguyện và hội nhập. Mỗi năm có nhiều sinh viên đăng ký hoặc có mong muốn phấn đấu cho danh hiệu này, nhưng không phải ai cũng theo dõi được đầy đủ tiến độ của mình từ đầu năm đến cuối năm.

Quy trình hiện tại tại nhiều đơn vị vẫn mang tính thủ công. Sinh viên tự lưu giấy khen, chứng chỉ, ảnh hoạt động hoặc các minh chứng liên quan; đến cuối kỳ mới tổng hợp lại để điền Google Forms, Microsoft Forms hoặc nộp hồ sơ bản cứng. Cán bộ Đoàn/Hội sau đó phải kiểm tra từng minh chứng, phân loại theo tiêu chí và đối chiếu tính hợp lệ bằng mắt thường.

Cách làm này tạo áp lực cho cả hai phía. Sinh viên dễ quên mình còn thiếu tiêu chí gì, dễ thất lạc minh chứng hoặc chỉ phát hiện thiếu điều kiện khi đã quá muộn. Cán bộ phụ trách phải xử lý lượng hồ sơ lớn trong thời gian ngắn, dễ xảy ra sai sót, chậm tiến độ và khó theo dõi toàn cảnh phong trào trong năm học.

Bài toán này phù hợp để giải quyết bằng AI vì dữ liệu đầu vào có nhiều dạng phi cấu trúc như ảnh giấy khen, chứng chỉ PDF, văn bản quy chế và lịch sự kiện. Việc kết hợp **OCR**, **RAG**, **eKYC** và gợi ý cá nhân hóa có thể biến quy trình xét danh hiệu từ bị động, cuối kỳ và nặng thủ tục thành một hành trình được theo dõi liên tục, minh bạch và có giá trị nghề nghiệp rõ ràng hơn.

### 3.2. Khách hàng mục tiêu và người dùng cuối

| Nhóm | Mô tả | Pain-point chính | Nhu cầu |
|---|---|---|---|
| Khách hàng/đơn vị triển khai | Đoàn Thanh niên, Hội Sinh viên trường hoặc đơn vị phụ trách phong trào Sinh viên 5 tốt | Quá tải khi duyệt hồ sơ thủ công, dễ sai sót, khó theo dõi tiến độ phong trào theo thời gian thực | Hệ thống quản lý tập trung, hỗ trợ tự động phân loại minh chứng, theo dõi tiến độ và tổng hợp hồ sơ |
| Người dùng cuối 1 | Sinh viên đang phấn đấu hoặc quan tâm đến danh hiệu Sinh viên 5 tốt | Thường xuyên quên tiêu chí, không biết mình còn thiếu gì, nộp minh chứng rời rạc, chưa thấy rõ giá trị sau khi đạt danh hiệu | Trợ lý theo dõi tiến độ, nhắc nhở tiêu chí còn thiếu, hỗ trợ nộp minh chứng và chuyển thành tích thành CV/Portfolio |
| Người dùng cuối 2 | CLB/Đội/Nhóm và doanh nghiệp đối tác | Khó tiếp cận đúng nhóm sinh viên tích cực, có năng lực và có thành tích được xác thực | Kênh giới thiệu hoạt động đúng đối tượng và nguồn ứng viên sinh viên chất lượng cho thực tập/tuyển dụng |

### 3.3. Pain-point có số liệu chứng minh

| Pain-point | Số liệu/dẫn chứng | Hậu quả nếu không giải quyết |
|---|---|---|
| **Thất thoát nhân tài** do sinh viên bỏ cuộc giữa chừng | Quan sát thực tế từ các trường cho thấy khoảng **60-70% sinh viên** đăng ký từ đầu năm nhưng không nộp hồ sơ cuối năm vì quên mình còn thiếu tiêu chí gì | Phong trào giảm hiệu quả, nhiều sinh viên tích cực không được ghi nhận, sinh viên bỏ lỡ quyền lợi và cơ hội phát triển |
| **Lãng phí nguồn lực** trong xét duyệt hồ sơ | Một trường đại học cỡ trung khoảng **20.000 sinh viên** có thể tốn **3-4 tuần làm việc liên tục** của hơn **20 cán bộ Hội** chỉ để đối chiếu minh chứng | Cán bộ quá tải, thời gian xét duyệt kéo dài, chi phí vận hành phong trào tăng nhưng chất lượng kiểm tra không ổn định |
| **Sai sót khi xử lý thủ công** | Khi kiểm tra số lượng lớn giấy khen, chứng chỉ và biểu mẫu thủ công, tỷ lệ sai sót như duyệt nhầm, sót hồ sơ hoặc phân loại sai có thể lên tới **15%** | Làm giảm độ tin cậy của quy trình xét duyệt, ảnh hưởng quyền lợi sinh viên và uy tín của chương trình |

## 4. Cách giải quyết

### 4.1. Giải pháp đề xuất

Mô tả sản phẩm sẽ làm gì và giải quyết pain-point như thế nào.

`<Viết 2-4 đoạn mô tả giải pháp tổng thể. Nên nói rõ sản phẩm là web app, mobile app, chatbot, dashboard, API platform hay công cụ nội bộ.>`

### 4.2. Nhóm chức năng chính

| Nhóm chức năng | Người dùng | Mô tả | Giá trị mang lại |
|---|---|---|---|
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

### 4.3. Luồng sử dụng chính

1. `<Bước 1: Người dùng làm gì?>`
2. `<Bước 2: Hệ thống xử lý gì?>`
3. `<Bước 3: AI/API tham gia ở đâu?>`
4. `<Bước 4: Người dùng nhận kết quả gì?>`
5. `<Bước 5: Quy trình kết thúc hoặc chuyển sang bước tiếp theo thế nào?>`

### 4.4. Vì sao cần AI?

Giải thích rõ AI tạo giá trị gì mà cách truyền thống khó làm được.

| Tác vụ | Nếu không dùng AI | Khi dùng AI | Giá trị tạo ra |
|---|---|---|---|
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

**Gợi ý viết:**

- AI giúp đọc hiểu dữ liệu phi cấu trúc.
- AI giúp phân loại, dự đoán, gợi ý hoặc cá nhân hóa.
- AI giúp giảm thời gian xử lý thủ công.
- AI giúp tạo phản hồi tự nhiên, dễ hiểu.
- AI giúp phát hiện bất thường hoặc hỗ trợ ra quyết định.

## 5. Tính đổi mới và khác biệt

### 5.1. Giải pháp hiện có

| Giải pháp hiện có | Mô tả ngắn | Hạn chế |
|---|---|---|
| **Google Form / Microsoft Form** | Dùng để thu thập minh chứng cuối năm, thường kèm file upload và câu hỏi tự khai báo | Dữ liệu rời rạc, tĩnh, không kiểm tra được giả mạo, sinh viên phải tự tổng hợp lại từ đầu |
| **Quy trình nộp hồ sơ bản cứng** | Sinh viên in hoặc photo giấy tờ, cán bộ đối chiếu trực tiếp từng minh chứng | Tốn thời gian, khó tra cứu, dễ thất lạc, không phù hợp khi số lượng hồ sơ lớn |
| **Phần mềm quản lý Đoàn/Hội nội bộ** | Một số trường có hệ thống quản lý điểm rèn luyện hoặc hoạt động sinh viên | Thường tập trung vào quản trị nội bộ, giao diện lạc hậu, cán bộ vẫn thao tác tay nhiều, thiếu tính năng đồng hành sinh viên |

### 5.2. So sánh khác biệt

| Tiêu chí so sánh | Giải pháp hiện có | Sản phẩm đề xuất | Khác biệt |
|---|---|---|---|
| Đối tượng phục vụ | Chủ yếu phục vụ cán bộ quản lý hoặc thu thập hồ sơ cuối kỳ | Đa bên: sinh viên, cán bộ, CLB/Đội/Nhóm và doanh nghiệp | Mở rộng từ công cụ thu hồ sơ sang hệ sinh thái kết nối nhiều bên |
| Tính năng lõi | Lưu trữ minh chứng, thu form và tính điểm tĩnh | OCR tự động, RAG Chatbot, gợi ý hoạt động, sinh CV/Portfolio | Tập trung vào workflow thông minh và giá trị sau danh hiệu |
| Mức độ dùng AI | Hầu như không có hoặc chỉ dùng ở mức hỗ trợ rời rạc | Cao: eKYC, OCR/Computer Vision, RAG và gợi ý cá nhân hóa | AI tham gia trực tiếp vào các điểm nghẽn tốn thời gian nhất |
| Trải nghiệm người dùng | Thụ động, nặng thủ tục, thường chỉ được dùng mạnh vào cuối năm | Chủ động, theo dõi tiến độ quanh năm như một personal coach | Chuyển từ “nộp hồ sơ” sang “đồng hành rèn luyện” |
| Khả năng triển khai | Phụ thuộc nhiều vào thao tác thủ công và cách làm riêng của từng đơn vị | Có thể cấu hình quy chế theo từng trường và mở rộng theo module | Phù hợp pilot ở một trường/khoa rồi mở rộng liên trường |
| Giá trị/tác động | Dừng lại ở giấy khen hoặc danh sách công nhận | Chuyển hóa thành CV/Portfolio và nguồn dữ liệu nhân tài | Biến danh hiệu thành giá trị nghề nghiệp cụ thể cho sinh viên |

### 5.3. Điểm mới nổi bật

- **Proactive Companion:** Từ bỏ mô hình “đến hẹn lại lên” thụ động. Hệ thống theo dõi tiến độ theo thời gian thực, nhắc sinh viên khi còn thiếu tiêu chí và gợi ý hoạt động phù hợp để kịp hoàn thiện hồ sơ.
- **Value Transformation:** Giải quyết câu hỏi “Đạt Sinh viên 5 tốt để làm gì?” bằng cách chuyển minh chứng học thuật và hoạt động phong trào thành **CV/Portfolio thực chiến**, có thể dùng cho thực tập, tuyển dụng hoặc học bổng.
- **Hyper-local RAG:** Không dùng AI chung chung để tư vấn. Chatbot được neo vào bộ quy chế đặc thù của từng trường, giúp câu trả lời sát bối cảnh, có căn cứ và giảm nguy cơ tư vấn sai.

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
