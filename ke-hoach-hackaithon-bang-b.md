# Kế hoạch tham gia HackAIthon Bảng B - Challenger

> Tài liệu làm việc cho đội thi. Cập nhật theo thông tin từ trang **Bảng B - Challenger** và **Thể lệ Bảng B** của HackAIthon.

## 1. Mục tiêu bảng thi

Bảng B - Challenger dành cho đội thi phát triển giải pháp AI ở cấp độ MVP, sử dụng hệ sinh thái API do Ban tổ chức cung cấp, có mentor đồng hành và trình diễn sản phẩm tại vòng chung kết nếu được chọn.

Mục tiêu của đội:

- Chọn một đề tài phù hợp năng lực đội và API được cung cấp.
- Nộp proposal Vòng 1 đúng hạn, rõ vấn đề, rõ giải pháp, rõ lý do cần AI.
- Nếu vào Vòng 2, phát triển MVP có thể demo, kiểm thử và cài đặt được.
- Chuẩn bị pitch, live-demo, câu trả lời phản biện và phương án triển khai thực tế.

## 2. Mốc thời gian chính

| Giai đoạn | Thời gian | Việc cần làm | Kết quả cần đạt |
|---|---:|---|---|
| Vòng 1 - Nộp ý tưởng | 02/06-16/06/2026 | Đăng ký đội, chọn đề tài, viết proposal PDF, có thể làm video thuyết minh | Hồ sơ ý tưởng hợp lệ |
| Công bố Vòng 2 | Trước 27/06/2026 | Theo dõi kết quả, chuẩn bị backlog MVP nếu được chọn | Tối đa 20 đội vào Vòng 2 |
| Vòng 2 - Phát triển MVP | 26/06-03/07/2026 | Build MVP, tích hợp API, làm repo, hướng dẫn chạy, script test, kế hoạch bảo mật và GTM | Demo MVP hoàn chỉnh |
| Chung kết | Dự kiến 14/07-15/07/2026 tại Hà Nội | HackAIthon 24 giờ, pitching, live-demo, trả lời BGK | Top 6 tranh giải chung cuộc |

Lưu ý: Vòng 1 còn hạn nộp đến **16/06/2026**. Tối đa mỗi vòng thi được **3 lần upload**, nếu quá 3 lần mà vẫn lỗi cần liên hệ BTC.

## 3. Đề tài có thể chọn

Theo Bảng B, đội có thể chọn một trong 6 hướng đề tài:

1. **AI hỗ trợ Ngân hàng số**  
   Tạo sản phẩm/dịch vụ ngân hàng mới, cá nhân hóa trải nghiệm, hỗ trợ khách hàng số.

2. **AI hỗ trợ công tác Hội và phong trào Sinh viên 5 tốt**  
   Hỗ trợ quản lý, đánh giá, xét chọn danh hiệu; trợ lý ảo giải đáp và hướng dẫn sinh viên.

3. **AI phục vụ đổi mới giáo dục**  
   Cá nhân hóa học tập, hỗ trợ giáo viên, nâng cao quản lý nhà trường.

4. **AI cho nội dung số và truyền thông**  
   Hỗ trợ xây dựng nội dung, nâng tương tác người xem, tối ưu vận hành truyền thông/báo chí/truyền hình.

5. **AI hỗ trợ y tế và trải nghiệm người bệnh**  
   Hỗ trợ khám chữa bệnh, tối ưu vận hành cơ sở y tế, cải thiện trải nghiệm người bệnh.

6. **AI hỗ trợ Hành chính công**  
   Hỗ trợ xử lý hồ sơ, minh bạch dịch vụ công, giao tiếp thân thiện, tăng hài lòng của người dân.

### Tiêu chí chọn đề tài cho đội

- Đội có hiểu biết hoặc dữ liệu mẫu về domain.
- Có pain-point rõ, càng cụ thể càng tốt.
- Có thể chứng minh "vì sao cần AI", không chỉ là app CRUD hoặc chatbot chung chung.
- MVP có thể demo trong thời gian ngắn.
- API BTC cung cấp có vai trò thật trong sản phẩm.
- Có câu chuyện tác động xã hội/kinh doanh và khả năng mở rộng.

## 4. API BTC cung cấp và ý tưởng sử dụng

| Nhóm API | Khả năng chính | Cách khai thác trong MVP |
|---|---|---|
| VNPT eKYC | OCR, liveness card/face, mask face, compare face | Định danh người dùng, xác thực hồ sơ, chống gian lận |
| vnFace | Quản lý face, lịch sử check-in, thông báo OTT | Điểm danh, xác thực tại điểm dịch vụ, theo dõi lịch sử |
| VNPT SmartVoice | Text to Speech, Speech to Text, tóm tắt cuộc gọi | Giao diện giọng nói, tổng đài AI, tóm tắt tư vấn |
| VNPT Smartbot | Smartbot, Smartbot nâng cao | Chatbot/LLM hỏi đáp theo kịch bản hoặc tri thức |
| VNPT SmartReader | OCR, bóc tách thông tin | Đọc biểu mẫu, hồ sơ, giấy tờ, minh chứng |
| vnSocial | Trending, phân tích cảm xúc | Theo dõi phản hồi xã hội, đo sentiment, phát hiện chủ đề nóng |
| VNPT SmartUX | Thu thập và trực quan hóa tương tác người dùng | Đo UX metrics, phân tích hành vi sử dụng |
| VNPT SmartVision | Phát hiện người, biển số/phương tiện, nhận diện khuôn mặt | Xử lý hình ảnh/video, giám sát, nhận diện tại hiện trường |

## 5. Việc cần soạn cho Vòng 1

### 5.1. Proposal PDF

Proposal cần có tối thiểu các phần sau:

- **Tên sản phẩm/dự án**: ngắn, dễ nhớ, gợi đúng vấn đề.
- **Thông tin đội**: tên đội, thành viên, vai trò, liên hệ.
- **Vấn đề cần giải quyết**: pain-point, người dùng mục tiêu, bối cảnh, số liệu hoặc dẫn chứng.
- **Giải pháp đề xuất**: sản phẩm làm gì, luồng sử dụng chính, điểm khác biệt.
- **Lý do dùng AI**: AI tạo giá trị gì mà cách truyền thống khó làm được.
- **Thiết kế tổng quan**: kiến trúc, các module, API dự kiến tích hợp, luồng dữ liệu.
- **Phương hướng triển khai**: roadmap MVP, công nghệ dự kiến, dữ liệu, nhân lực, rủi ro.
- **Tác động dự kiến**: lợi ích xã hội/kinh doanh, nhóm người hưởng lợi, mô hình mở rộng.
- **Kế hoạch bảo mật/pháp lý**: dữ liệu cá nhân, quyền riêng tư, lưu trữ, phân quyền.
- **Phụ lục nếu có**: wireframe, user journey, sơ đồ hệ thống, link demo mockup.

### 5.2. Video thuyết minh

Video không bắt buộc, nhưng nên làm nếu còn thời gian.

Khung video 2-3 phút:

1. Mở đầu: đội thi và tên sản phẩm.
2. Vấn đề: ai đang gặp khó, khó ở đâu, vì sao đáng giải quyết.
3. Giải pháp: demo wireframe hoặc mô phỏng luồng chính.
4. AI/API: dùng API nào, tạo giá trị gì.
5. Kết quả kỳ vọng: tác động, khả năng triển khai MVP.

### 5.3. Checklist trước khi nộp Vòng 1

- [ ] Đã đăng ký tài khoản/đội trên website cuộc thi.
- [ ] Đã chọn đúng Bảng B - Challenger.
- [ ] Đã chọn đề tài chính.
- [ ] Proposal xuất PDF, đọc được, không lỗi font.
- [ ] Có đầy đủ tên sản phẩm, thông tin đội, vấn đề, giải pháp, thiết kế tổng quan, hướng triển khai.
- [ ] Có pain-point bằng số liệu/dẫn chứng thực tế.
- [ ] Có lý do "vì sao AI" rõ ràng.
- [ ] Có sơ đồ kiến trúc hoặc wireframe.
- [ ] Có roadmap Vòng 2 nếu được chọn.
- [ ] File đặt tên rõ ràng: `BangB_TenDoi_TenSanPham_Proposal.pdf`.
- [ ] Nộp trước hạn, tránh sát giờ.

## 6. Tiêu chí chấm Vòng 1 và cách đáp ứng

| Tiêu chí | Điểm | Cách đội nên thể hiện |
|---|---:|---|
| Tính phù hợp đề bài | 25 | Bám sát một trong 6 đề tài; mô tả pain-point bằng số liệu; nêu rõ người dùng cuối; chứng minh cần AI |
| Tính đổi mới và khác biệt | 20 | So sánh với giải pháp hiện có, open-source hoặc thị trường; nêu khác biệt tối thiểu ở tính năng lõi |
| Tính khả thi | 25 | Có dữ liệu/nhân lực hợp pháp; kỹ thuật build/deploy khả thi; dự trù chi phí; có bảo mật, pháp lý, roadmap |
| Tác động dự kiến | 20 | Nêu lợi ích xã hội/kinh doanh, người dùng tiềm năng, ưu thế cạnh tranh, mô hình doanh thu/giá trị |
| Chất lượng hồ sơ | 10 | Proposal logic, có sơ đồ/wireframe, ngôn ngữ rõ ràng, không lỗi chính tả |

## 7. Kế hoạch làm việc đề xuất cho Vòng 1

| Ngày | Mục tiêu | Đầu ra |
|---:|---|---|
| D-4 đến D-3 | Chốt đề tài, người dùng mục tiêu, pain-point, API chính | 1 trang problem-solution fit |
| D-3 đến D-2 | Viết proposal nháp, dựng wireframe/sơ đồ kiến trúc | Proposal bản 0.8 |
| D-2 | Review theo tiêu chí chấm, bổ sung số liệu, rủi ro, roadmap | Proposal bản 0.9 |
| D-1 | Chỉnh câu chữ, xuất PDF, kiểm tra upload, nếu kịp quay video | Proposal final + video optional |
| Ngày nộp | Nộp bài sớm, lưu biên nhận/link dashboard | Hồ sơ đã nộp |

## 8. Nếu vào Vòng 2: bộ sản phẩm cần chuẩn bị

### 8.1. MVP

- [ ] Luồng chính chạy được end-to-end.
- [ ] Có dữ liệu mẫu hoặc môi trường demo.
- [ ] Có tích hợp ít nhất một API BTC cung cấp theo đúng mục đích sản phẩm.
- [ ] Demo ổn định, chạy được tối thiểu 3 lần liên tiếp.
- [ ] Có xử lý lỗi cơ bản khi API lỗi, dữ liệu thiếu, người dùng nhập sai.
- [ ] Có logging hoặc màn hình trạng thái để dễ debug khi demo.

### 8.2. Repo và hướng dẫn cài đặt

- [ ] Repo sạch, có README.
- [ ] Có hướng dẫn cài đặt một lệnh nếu có thể.
- [ ] Có file `.env.example` và hướng dẫn biến môi trường.
- [ ] Có script chạy local.
- [ ] Có script test tự động.
- [ ] Có dữ liệu mẫu hoặc seed script.
- [ ] Có mô tả kiến trúc thư mục.

### 8.3. Bảo mật dữ liệu

- [ ] Không commit API key/token thật.
- [ ] Phân loại dữ liệu nhạy cảm.
- [ ] Có phương án mã hóa/lưu trữ tối thiểu.
- [ ] Có phân quyền cơ bản nếu sản phẩm có nhiều vai trò.
- [ ] Có chính sách xóa/ẩn dữ liệu demo.
- [ ] Có nêu rủi ro pháp lý và cách giảm thiểu.

### 8.4. UX và Go-to-market

- [ ] Xác định persona chính.
- [ ] Có user journey.
- [ ] Có 1-2 UX metrics: thời gian hoàn thành tác vụ, tỷ lệ lỗi, mức hài lòng, tỷ lệ quay lại.
- [ ] Có mô hình khách hàng mục tiêu.
- [ ] Có mô hình chi phí/doanh thu hoặc giá trị phi lợi nhuận.
- [ ] Có lộ trình mở rộng 12 tháng.

## 9. Tiêu chí chấm Vòng 2 và cách đáp ứng

| Tiêu chí | Điểm | Cách đội nên thể hiện |
|---|---:|---|
| Hoàn thiện sản phẩm | 20 | Demo MVP, repo, hướng dẫn cài đặt một lệnh, script test pass, chạy ổn định, đảm bảo an toàn thông tin |
| Trải nghiệm người dùng | 20 | Hiểu đối tượng mục tiêu, đáp ứng nhu cầu chính, UI/accessibility tốt, có UX metrics |
| Khả năng triển khai và mở rộng | 20 | Có phương án hạ tầng, tối ưu vận hành, kế hoạch scale |
| Chiến lược Go-to-market | 25 | Phân khúc khách hàng, mô hình doanh thu, định giá/chi phí đơn vị, kênh phân phối, đối tác, truyền thông, roadmap 12 tháng |
| Tính nâng cấp | 10 | Cải tiến so với proposal Vòng 1, áp dụng phản hồi mentor, có tính năng phụ hữu ích |

## 10. Chuẩn bị Chung kết

### 10.1. HackAIthon 24 giờ

- [ ] Chuẩn bị template repo, component UI, module API wrapper, logging.
- [ ] Chuẩn bị quy trình chia việc nhanh: backend, frontend, AI/API, pitch/demo.
- [ ] Chuẩn bị checklist demo offline/fallback.
- [ ] Chuẩn bị mẫu slide cập nhật nhanh sau nhiệm vụ bí mật.
- [ ] Chuẩn bị thiết bị, sạc, mạng dự phòng, tài khoản truy cập.

### 10.2. Pitching và trả lời câu hỏi

Theo thể lệ, phần pitching có tối đa 10 phút trình bày, gồm giới thiệu sản phẩm, live-demo hấp dẫn và trả lời câu hỏi/phản biện.

Khung pitch đề xuất:

1. **30 giây** - Hook: vấn đề lớn và người dùng bị ảnh hưởng.
2. **90 giây** - Insight: vì sao vấn đề khó, vì sao cần AI.
3. **2 phút** - Giải pháp và luồng sản phẩm.
4. **3 phút** - Live-demo.
5. **1 phút** - Công nghệ/API/kiến trúc.
6. **1 phút** - Tác động, GTM, khả năng mở rộng.
7. **30 giây** - Kết luận và lời cam kết triển khai.

Câu hỏi cần chuẩn bị trước:

- Vì sao giải pháp này cần AI?
- Khác biệt với chatbot/app hiện có là gì?
- Dữ liệu lấy từ đâu, có hợp pháp không?
- Nếu API lỗi hoặc chậm thì sản phẩm xử lý thế nào?
- Bảo vệ dữ liệu cá nhân ra sao?
- Chi phí vận hành mỗi người dùng/giao dịch là bao nhiêu?
- Làm sao scale từ demo sang triển khai thật?
- Rủi ro lớn nhất là gì và đội xử lý thế nào?

## 11. Phân công nội bộ

| Vai trò | Người phụ trách | Việc chính | Deadline |
|---|---|---|---|
| Product/PM |  | Chốt đề tài, scope MVP, tiêu chí thành công |  |
| Research/Proposal |  | Pain-point, số liệu, viết proposal, kiểm tra tiêu chí chấm |  |
| UX/UI |  | Wireframe, user journey, prototype, slide demo |  |
| Backend/API |  | Thiết kế backend, tích hợp API, bảo mật key |  |
| Frontend |  | Giao diện demo, luồng người dùng, trạng thái lỗi/loading |  |
| AI/Data |  | Prompt, dữ liệu mẫu, đánh giá đầu ra, test case |  |
| Pitch/Demo |  | Script pitch, quay video optional, Q&A, demo flow |  |

## 12. Cấu trúc thư mục đề xuất

```text
hackaithon-bang-b/
+-- docs/
|   +-- proposal.pdf
|   +-- proposal-source.md
|   +-- pitch-deck.pptx
|   +-- architecture.png
+-- app/
|   +-- frontend/
|   +-- backend/
+-- scripts/
|   +-- setup.*
|   +-- test.*
|   +-- seed-demo-data.*
+-- samples/
|   +-- demo-data/
+-- .env.example
+-- README.md
```

## 13. Nguồn tham khảo

- Bảng B - Challenger: <https://hackaithon.vsds.vn/bang-b-challenger/>
- Thể lệ Bảng B: <https://hackaithon.vsds.vn/the-le-bang-b/>
