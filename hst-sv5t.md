# Kế hoạch ý tưởng: Hệ sinh thái phong trào Sinh viên 5 tốt

## 1. Tên ý tưởng

**Hệ sinh thái phong trào Sinh viên 5 tốt**

**Tên tiếng Anh:** 5-Star Eco

Tagline đề xuất:

> 5-Star Eco là một nền tảng liên cấp giúp sinh viên tích lũy thành tích từ sớm, theo dõi, nộp, bổ sung và xét duyệt hồ sơ Sinh viên 5 tốt qua các tầng khoa, trường, thành phố/tỉnh và Trung ương.

## 2. Tóm tắt ý tưởng

5-Star Eco là hệ sinh thái số hóa toàn bộ hành trình phấn đấu và xét duyệt danh hiệu **Sinh viên 5 tốt**. Thay vì sinh viên phải tự gom hồ sơ rời rạc, nộp lại nhiều lần ở từng cấp và cán bộ phải kiểm duyệt thủ công qua form/file/bản cứng, hệ thống tạo một quy trình liên thông qua 4 cấp danh hiệu:

1. **Cấp khoa/viện/bộ môn**
2. **Cấp trường**
3. **Cấp thành phố/tỉnh**
4. **Cấp Trung ương**

Trong đó, **cấp khoa/viện/bộ môn** là cấp xét danh hiệu đầu tiên và gần sinh viên nhất. Khoa không chỉ truyền thông kế hoạch hoặc hỗ trợ sơ duyệt, mà có thể mở đợt xét riêng, cấu hình điều kiện đạt chi tiết, tiếp nhận hồ sơ, xét duyệt và công nhận danh hiệu Sinh viên 5 tốt cấp khoa. Sinh viên đạt cấp khoa mới đủ điều kiện tiếp tục xét cấp trường.

Hằng năm, hệ thống mở 4 đợt xét tương ứng với 4 cấp danh hiệu: khoa, trường, thành phố/tỉnh và Trung ương. Ở mỗi đợt, sinh viên được nộp, chỉnh sửa hoặc bổ sung hồ sơ trong thời gian cho phép. Ngoài thời gian xét duyệt, sinh viên vẫn có thể cập nhật thành tích và upload minh chứng vào kho cá nhân để chuẩn bị từ sớm. Khi đợt xét đầu tiên ở cấp khoa mở ra, admin cấu hình phạm vi thời gian minh chứng khả dụng cho chu kỳ xét; hệ thống chỉ cho phép đưa các minh chứng còn hiệu lực vào hồ sơ nộp chính thức và tự động đánh dấu/dọn dẹp minh chứng cũ không thể sử dụng để giảm dung lượng lưu trữ. Khi đến deadline, cổng hồ sơ khóa lại; cán bộ phụ trách cấp tương ứng đăng nhập để xét duyệt. AI hỗ trợ đọc minh chứng, phân loại tiêu chí, phát hiện thiếu sót và gợi ý trạng thái, nhưng **quyết định cuối cùng vẫn thuộc về cán bộ phụ trách**.

Điểm quan trọng của hệ sinh thái là **5 nhóm “tốt” luôn cố định, nhưng điều kiện để đạt từng nhóm tốt có thể khác nhau theo cấp và theo đơn vị triển khai**. Năm nhóm tốt gồm: **Đạo đức tốt, Học tập tốt, Thể lực tốt, Tình nguyện tốt và Hội nhập tốt**. Trung ương có bộ điều kiện chung; các thành phố/tỉnh triển khai kế hoạch theo bối cảnh địa phương nên có thể có ngưỡng đạt, yêu cầu minh chứng, biểu mẫu hoặc hoạt động được công nhận khác nhau; mỗi trường trong cùng thành phố cũng có thể có cách triển khai riêng; và mỗi khoa trong một trường cũng có thể có yêu cầu chi tiết hoặc hoạt động ưu tiên khác nhau.

Nếu sinh viên đạt ở một cấp, sinh viên nhận danh hiệu cấp đó và được quyền tiếp tục xét ở cấp cao hơn trong đợt tiếp theo. Nếu không đạt, sinh viên vẫn giữ danh hiệu cấp thấp hơn đã đạt, nhưng không thể xét tiếp ở cấp cao hơn trong cùng chu kỳ.

## 3. Bối cảnh và vấn đề

Quy trình Sinh viên 5 tốt hiện nay thường rườm rà vì hồ sơ phải đi qua nhiều cấp xét. Một sinh viên có thể phải:

- Theo dõi kế hoạch triển khai tại khoa/viện/bộ môn.
- Chuẩn bị và nộp hồ sơ cấp khoa.
- Sau khi đạt cấp khoa, tiếp tục bổ sung hồ sơ để xét cấp trường.
- Sau khi đạt cấp trường, tiếp tục bổ sung hồ sơ để xét cấp thành phố.
- Sau khi đạt cấp thành phố, tiếp tục hoàn thiện hồ sơ để xét cấp Trung ương.
- Nộp lại minh chứng đã đạt cấp cũ cùng hồ sơ bổ sung ở cấp mới.
- Theo dõi nhiều deadline khác nhau.
- Chờ phản hồi từ các đơn vị xét duyệt khác nhau.

Ở phía cán bộ Đoàn - Hội, quy trình cũng có nhiều điểm nghẽn:

- Mỗi cấp phải tiếp nhận số lượng lớn hồ sơ trong thời gian ngắn.
- Hồ sơ đến từ nhiều khoa, nhiều trường, nhiều thành phố/tỉnh, nhiều định dạng.
- 5 nhóm tốt là giống nhau, nhưng điều kiện đạt từng nhóm tốt và minh chứng hợp lệ có thể khác nhau theo từng khoa, trường, thành phố/tỉnh.
- Minh chứng khó kiểm tra thủ công, dễ thiếu, sai hoặc trùng.
- Việc tổng hợp danh sách đủ điều kiện lên cấp cao hơn dễ phát sinh sai sót.
- Thiếu một hệ thống minh bạch để theo dõi trạng thái hồ sơ qua từng cấp.

Vì vậy, bài toán không chỉ là “AI xét hồ sơ” mà là **số hóa hệ sinh thái phong trào Sinh viên 5 tốt theo chu kỳ liên cấp**.

## 4. Mục tiêu sản phẩm

5-Star Eco hướng đến các mục tiêu:

- Tạo một cổng nộp hồ sơ thống nhất cho sinh viên.
- Quản lý cây tổ chức nhiều tầng: khoa, trường, thành phố/tỉnh, Trung ương.
- Quản lý 4 đợt xét danh hiệu hằng năm: khoa, trường, thành phố/tỉnh, Trung ương.
- Cho phép mỗi đơn vị cấu hình điều kiện đạt cho từng nhóm tốt, biểu mẫu, deadline phụ và yêu cầu minh chứng riêng theo quyền được phân cấp.
- Cho phép sinh viên cập nhật kho thành tích/minh chứng cá nhân quanh năm, không phải chờ đến mùa xét mới gom hồ sơ.
- Cho phép admin cấu hình thời gian minh chứng khả dụng theo chu kỳ xét và tự động dọn dẹp/xóa minh chứng cũ không thể sử dụng theo chính sách lưu trữ.
- Cho phép sinh viên tái sử dụng hồ sơ cấp cũ và bổ sung minh chứng mới khi xét cấp cao hơn.
- Tự động kiểm tra điều kiện đầu vào: chỉ sinh viên đã đạt cấp dưới mới được nộp cấp trên.
- Hỗ trợ cán bộ từng cấp xét duyệt theo đúng phạm vi tổ chức của mình.
- Dùng AI để giảm tải các thao tác thủ công: OCR minh chứng, phân loại tiêu chí, phát hiện thiếu sót, tóm tắt hồ sơ.
- Đảm bảo người duyệt cuối vẫn là cán bộ phụ trách, không để AI tự quyết định danh hiệu.
- Tăng tính minh bạch qua lịch sử xét duyệt, trạng thái hồ sơ và log thao tác.

## 5. Người dùng và vai trò

| Vai trò | Mô tả | Quyền chính |
|---|---|---|
| Sinh viên | Người phấn đấu và nộp hồ sơ Sinh viên 5 tốt | Tạo hồ sơ, upload minh chứng, bổ sung hồ sơ theo đợt, theo dõi trạng thái, xem danh hiệu đã đạt |
| Cán bộ cấp khoa | Cán bộ Đoàn/Hội hoặc đơn vị phụ trách phong trào tại khoa/viện/bộ môn | Cấu hình kế hoạch và điều kiện đạt cấp khoa, hỗ trợ sinh viên, xét hồ sơ cấp khoa, yêu cầu bổ sung, duyệt/từ chối, chốt danh sách đạt cấp khoa |
| Cán bộ cấp trường | Cán bộ Đoàn/Hội tại trường hoặc Đoàn trường nếu trường chưa có Hội Sinh viên | Cấu hình kế hoạch cấp trường, nhận hồ sơ sinh viên đã đạt cấp khoa, xét hồ sơ cấp trường, yêu cầu bổ sung, duyệt/từ chối, chốt danh sách đạt cấp trường |
| Cán bộ cấp thành phố/tỉnh | Cán bộ Hội Sinh viên cấp thành phố/tỉnh | Cấu hình kế hoạch địa phương, xét hồ sơ sinh viên đã đạt cấp trường thuộc địa bàn, duyệt/từ chối, chốt danh sách đạt cấp thành phố/tỉnh |
| Cán bộ cấp Trung ương | Cán bộ Trung ương Hội Sinh viên Việt Nam | Xét hồ sơ sinh viên đã đạt cấp thành phố/tỉnh, duyệt/từ chối, chốt danh sách đạt cấp Trung ương |
| Admin hệ thống | Quản trị vận hành nền tảng | Tạo chu kỳ xét, mở/đóng cổng, cấu hình điều kiện đạt, quản lý tổ chức, phân quyền theo từng tầng |

## 6. Chu kỳ xét duyệt hằng năm

Mỗi năm hệ thống có một **chu kỳ xét Sinh viên 5 tốt** gồm 4 đợt danh hiệu:

| Đợt xét | Đối tượng được nộp | Đơn vị xét duyệt | Kết quả nếu đạt |
|---|---|---|---|
| Đợt 1 - Cấp khoa | Sinh viên thuộc khoa/viện/bộ môn, đủ điều kiện nộp cấp khoa | Đoàn/Hội hoặc đơn vị phụ trách phong trào cấp khoa | Danh hiệu Sinh viên 5 tốt cấp khoa |
| Đợt 2 - Cấp trường | Sinh viên đã đạt cấp khoa | Hội Sinh viên trường hoặc Đoàn trường | Danh hiệu Sinh viên 5 tốt cấp trường |
| Đợt 3 - Cấp thành phố/tỉnh | Sinh viên đã đạt cấp trường | Hội Sinh viên cấp thành phố/tỉnh | Danh hiệu Sinh viên 5 tốt cấp thành phố/tỉnh |
| Đợt 4 - Cấp Trung ương | Sinh viên đã đạt cấp thành phố/tỉnh | Trung ương Hội Sinh viên Việt Nam | Danh hiệu Sinh viên 5 tốt cấp Trung ương |

Ở mỗi đợt:

1. Admin/cán bộ có thẩm quyền mở cổng hồ sơ.
2. Ở đợt đầu tiên cấp khoa, admin cấu hình khoảng thời gian minh chứng khả dụng cho chu kỳ xét.
3. Sinh viên đủ điều kiện chọn minh chứng còn hiệu lực từ kho cá nhân hoặc bổ sung minh chứng mới để nộp hồ sơ.
4. Hệ thống cho phép chỉnh sửa trong thời gian cổng mở.
5. Đến deadline, cổng khóa lại.
6. Cán bộ cấp tương ứng bắt đầu xét duyệt.
7. Kết quả được ghi nhận vào hồ sơ danh hiệu của sinh viên.
8. Sinh viên đạt cấp hiện tại được quyền xét ở cấp cao hơn trong đợt sau.

### 6.1. Nguyên tắc tiêu chí phân cấp

Hệ thống cần hỗ trợ tiêu chí theo mô hình phân cấp. Cần phân biệt rõ hai lớp:

- **Lớp cố định:** danh hiệu Sinh viên 5 tốt luôn xoay quanh 5 nhóm tốt: **Đạo đức tốt, Học tập tốt, Thể lực tốt, Tình nguyện tốt, Hội nhập tốt**.
- **Lớp thay đổi theo đơn vị:** điều kiện để được xem là “đạt” từng nhóm tốt có thể khác nhau theo cấp và theo đơn vị triển khai. Phần thay đổi gồm ngưỡng đạt, loại minh chứng, biểu mẫu, hoạt động được công nhận, deadline nội bộ và cách xác nhận.

Ví dụ: cùng là **Hội nhập tốt**, cấp Trung ương có thể yêu cầu chứng chỉ hoặc thành tích hội nhập ở mức cao hơn; Thành phố Hồ Chí Minh có thể công nhận một nhóm hoạt động/chuỗi sự kiện cụ thể; Trường Đại học Khoa học Tự nhiên có thể yêu cầu thêm minh chứng theo quy định của trường; Khoa Công nghệ thông tin có thể ưu tiên các hoạt động học thuật, cuộc thi, workshop hoặc chứng chỉ phù hợp với sinh viên trong khoa.

| Tầng tổ chức | Cách tiêu chí được hình thành | Ví dụ |
|---|---|---|
| Trung ương | Ban hành khung chung và điều kiện cấp Trung ương cho 5 nhóm tốt | 5 nhóm tốt vẫn là đạo đức, học tập, thể lực, tình nguyện, hội nhập; nhưng yêu cầu minh chứng/ngưỡng đạt ở cấp Trung ương cao hơn |
| Thành phố/tỉnh | Nhận định hướng từ Trung ương và triển khai kế hoạch theo địa phương | TP.HCM có thể công nhận hoạt động, chiến dịch, biểu mẫu hoặc ngưỡng điểm khác Hà Nội hoặc Đà Nẵng |
| Trường | Nhận kế hoạch từ thành phố/tỉnh và triển khai theo đặc thù nhà trường | Mỗi trường có biểu mẫu, cách xác nhận hoạt động, quy định điểm rèn luyện hoặc deadline nội bộ khác nhau |
| Khoa/viện/bộ môn | Nhận kế hoạch từ trường và triển khai sát với sinh viên trong khoa | Khoa CNTT có thể ưu tiên cuộc thi học thuật/chứng chỉ công nghệ; Khoa Sinh học có thể ưu tiên nghiên cứu, hoạt động chuyên môn hoặc tình nguyện chuyên ngành |

Thiết kế hệ thống cần cho phép:

- Cấu hình 5 nhóm tốt cố định cho toàn hệ thống.
- Cấu hình điều kiện đạt cho từng nhóm tốt theo `level` và `organization`.
- Một bộ điều kiện có thể kế thừa từ cấp trên nhưng được bổ sung yêu cầu riêng.
- Bộ điều kiện có hiệu lực theo năm xét hoặc theo đợt xét.
- Sinh viên nộp hồ sơ theo đúng bộ điều kiện của đơn vị mình thuộc về.
- AI/RAG chatbot trả lời dựa trên 5 nhóm tốt cố định và bộ điều kiện đúng cấp, đúng đơn vị, đúng năm.
- Khi xét cấp cao hơn, hệ thống kiểm tra cả danh hiệu cấp dưới lẫn điều kiện đạt của cấp hiện tại.

## 7. Luồng nghiệp vụ tổng thể

```text
Sinh viên tạo hồ sơ nền
        |
        v
Sinh viên cập nhật kho thành tích/minh chứng quanh năm
        |
        v
Admin cấu hình thời gian minh chứng khả dụng cho chu kỳ xét
        |
        v
Đợt cấp khoa mở cổng
        |
        v
Sinh viên theo dõi điều kiện đạt của khoa
        |
        v
Sinh viên chọn minh chứng còn hiệu lực và nộp hồ sơ cấp khoa
        |
        v
AI hỗ trợ OCR, phân loại theo 5 nhóm tốt và bộ điều kiện cấp khoa
        |
        v
        Cán bộ cấp khoa xét duyệt
        |
        +-- Không đạt -> dừng ở trạng thái chưa đạt cấp khoa
        |
        +-- Đạt -> nhận danh hiệu cấp khoa
                    |
                    v
             Được quyền nộp cấp trường
                    |
                    v
             Sinh viên tái sử dụng hồ sơ cấp khoa và bổ sung minh chứng nếu cần
                    |
                    v
             Cán bộ cấp trường xét duyệt
                    |
                    +-- Không đạt -> giữ danh hiệu cấp khoa
                    |
                    +-- Đạt -> nhận danh hiệu cấp trường
                                |
                                v
                         Được quyền nộp cấp thành phố/tỉnh
                                |
                                v
                         Cán bộ cấp thành phố/tỉnh xét duyệt
                                |
                                +-- Không đạt -> giữ danh hiệu cấp trường
                                |
                                +-- Đạt -> nhận danh hiệu cấp thành phố/tỉnh
                                            |
                                            v
                                     Được quyền nộp cấp Trung ương
                                            |
                                            v
                                     Cán bộ Trung ương xét duyệt
                                            |
                                            +-- Không đạt -> giữ danh hiệu cấp thành phố/tỉnh
                                            |
                                            +-- Đạt -> nhận danh hiệu cấp Trung ương
```

## 8. Ví dụ nghiệp vụ

Một sinh viên Khoa Công nghệ thông tin, Trường Đại học Khoa học Tự nhiên thuộc Thành phố Hồ Chí Minh tham gia chu kỳ xét:

1. **Trước mùa xét:** Sinh viên cập nhật giấy khen, chứng chỉ, hoạt động tình nguyện, hoạt động hội nhập hoặc thành tích học tập vào kho minh chứng cá nhân ngay khi phát sinh. AI có thể OCR và phân loại sơ bộ để sinh viên biết minh chứng có khả năng phục vụ nhóm tốt nào.
2. **Đợt cấp khoa:** Khoa Công nghệ thông tin nhận kế hoạch từ trường, cấu hình deadline, điều kiện/minh chứng chi tiết cho cấp khoa và phạm vi thời gian minh chứng khả dụng. Sinh viên chọn minh chứng còn hiệu lực từ kho cá nhân để nộp hồ sơ trước deadline cấp khoa. Cán bộ cấp khoa xét duyệt với AI hỗ trợ đọc minh chứng, phân loại tiêu chí và chỉ ra điểm cần kiểm tra.
3. **Nếu đạt cấp khoa:** Sinh viên được ghi nhận danh hiệu Sinh viên 5 tốt cấp khoa và được quyền tham gia đợt cấp trường.
4. **Đợt cấp trường:** Khi Trường Đại học Khoa học Tự nhiên mở cổng xét cấp trường, sinh viên có thể tái sử dụng hồ sơ cấp khoa và bổ sung minh chứng nếu cần. Hệ thống chuyển sang bộ điều kiện cấp trường, đồng thời yêu cầu đính kèm hoặc tự động xác thực minh chứng đã đạt cấp khoa.
5. **Nếu đạt cấp trường:** Sinh viên được ghi nhận danh hiệu Sinh viên 5 tốt cấp trường và được quyền tham gia đợt cấp thành phố.
6. **Đợt cấp thành phố:** Khi Thành phố Hồ Chí Minh mở cổng xét cấp thành phố, sinh viên tiếp tục bổ sung hồ sơ nếu cần. Hệ thống chuyển sang bộ điều kiện cấp Thành phố Hồ Chí Minh, đồng thời xác thực minh chứng đã đạt cấp trường.
7. **Cán bộ cấp thành phố xét duyệt:** Cán bộ Thành phố Hồ Chí Minh chỉ thấy các hồ sơ đủ điều kiện thuộc địa bàn. Nếu sinh viên không đạt cấp thành phố, sinh viên vẫn giữ danh hiệu cấp trường nhưng không được xét tiếp cấp Trung ương.
8. **Đợt cấp Trung ương:** Chỉ các sinh viên đã đạt cấp thành phố/tỉnh mới được tham gia. Hệ thống chuyển sang bộ điều kiện chung cấp Trung ương cho 5 nhóm tốt. Cán bộ Trung ương xét hồ sơ từ nhiều tỉnh/thành và chốt danh sách đạt cấp Trung ương.

## 9. Nhóm chức năng chính

### 9.1. Phía sinh viên

- Tạo hồ sơ cá nhân nền cho toàn bộ chu kỳ Sinh viên 5 tốt.
- Cập nhật thành tích và upload minh chứng vào kho cá nhân quanh năm.
- Xem minh chứng nào còn hiệu lực/hết hạn theo chu kỳ xét hiện tại.
- Theo dõi tiến độ theo 5 nhóm tốt và từng điều kiện đạt.
- Xem các đợt xét đang mở và điều kiện được nộp.
- Nộp hồ sơ cấp khoa.
- Tái sử dụng hồ sơ cấp cũ khi xét cấp cao hơn.
- Bổ sung hồ sơ/minh chứng trong thời gian cổng mở.
- Không thể chỉnh sửa sau deadline.
- Xem trạng thái xét duyệt theo từng cấp.
- Xem danh hiệu đã đạt: cấp khoa, cấp trường, cấp thành phố/tỉnh, cấp Trung ương.
- Render CV/Portfolio từ thành tích đã được duyệt.

### 9.2. Phía cán bộ cấp khoa

- Đăng nhập theo phạm vi khoa/viện/bộ môn.
- Xem danh sách sinh viên thuộc khoa nộp hồ sơ cấp khoa.
- Cấu hình điều kiện đạt chi tiết của cấp khoa theo kế hoạch trường giao.
- Cấu hình thời gian mở/đóng cổng cấp khoa.
- Xác nhận minh chứng hoạt động nội bộ của khoa.
- Xem tóm tắt AI và minh chứng đã OCR.
- Yêu cầu sinh viên bổ sung trong thời gian cho phép.
- Duyệt/từ chối hồ sơ cấp khoa.
- Chốt danh sách đạt cấp khoa.
- Gửi danh sách đủ điều kiện lên cấp trường.
- Theo dõi tỷ lệ sinh viên trong khoa hoàn thiện từng tiêu chí.

### 9.3. Phía cán bộ cấp trường

- Đăng nhập theo phạm vi trường.
- Xem danh sách sinh viên đã đạt cấp khoa và nộp hồ sơ cấp trường.
- Kiểm tra điều kiện đầu vào: sinh viên phải đã đạt cấp khoa.
- Lọc hồ sơ theo trạng thái, khoa/lớp, tiêu chí thiếu, danh hiệu cấp khoa.
- Xem tóm tắt AI và minh chứng đã OCR.
- Yêu cầu sinh viên bổ sung trong thời gian cho phép.
- Duyệt/từ chối hồ sơ.
- Chốt danh sách đạt cấp trường.
- Gửi danh sách đủ điều kiện lên cấp thành phố/tỉnh.

### 9.4. Phía cán bộ cấp thành phố/tỉnh

- Đăng nhập theo phạm vi thành phố/tỉnh.
- Nhận hồ sơ từ các trường thuộc địa bàn.
- Kiểm tra điều kiện đầu vào: sinh viên phải đã đạt cấp trường.
- Xem minh chứng đạt cấp trường và hồ sơ bổ sung.
- Duyệt/từ chối hồ sơ cấp thành phố/tỉnh.
- Trả hồ sơ về trường/sinh viên để bổ sung nếu còn trong thời gian cho phép.
- Chốt danh sách đạt cấp thành phố/tỉnh.
- Gửi danh sách đủ điều kiện xét cấp Trung ương.

### 9.5. Phía cán bộ Trung ương

- Đăng nhập theo phạm vi Trung ương.
- Nhận hồ sơ từ các thành phố/tỉnh hoặc đơn vị trực thuộc.
- Kiểm tra điều kiện đầu vào: sinh viên phải đã đạt cấp thành phố/tỉnh.
- Xem lịch sử xét duyệt liên cấp của từng hồ sơ.
- Xem văn bản đề nghị/danh sách chính thức từ cấp thành phố/tỉnh.
- Duyệt/từ chối hồ sơ cấp Trung ương.
- Chốt danh sách đạt danh hiệu Sinh viên 5 tốt cấp Trung ương.

### 9.6. Phía admin hệ thống

- Tạo năm xét/chu kỳ xét.
- Cấu hình 4 đợt xét: khoa, trường, thành phố/tỉnh, Trung ương.
- Cấu hình thời gian mở/đóng cổng.
- Cấu hình thời gian minh chứng khả dụng khi mở đợt xét đầu tiên.
- Quản lý chính sách đánh dấu hết hạn, dọn dẹp hoặc xóa minh chứng cũ không thể sử dụng.
- Cấu hình điều kiện đạt theo cấp, đơn vị, năm và đợt xét.
- Quản lý quan hệ kế thừa điều kiện đạt giữa Trung ương, thành phố/tỉnh, trường và khoa.
- Quản lý cây tổ chức: khoa, trường, tỉnh/thành, Trung ương.
- Phân quyền cán bộ theo cấp và phạm vi tổ chức.
- Theo dõi log thao tác và xuất báo cáo.

## 10. AI hỗ trợ ở đâu?

AI trong hệ thống đóng vai trò **trợ lý xử lý và kiểm tra**, không thay thế cán bộ duyệt cuối.

| Năng lực AI | Cách dùng trong hệ sinh thái |
|---|---|
| OCR minh chứng | Đọc ảnh/PDF giấy khen, chứng chỉ, bảng điểm, quyết định công nhận danh hiệu cấp cũ |
| Phân loại theo 5 nhóm tốt | Gợi ý minh chứng thuộc nhóm Đạo đức tốt, Học tập tốt, Thể lực tốt, Tình nguyện tốt hoặc Hội nhập tốt theo bộ điều kiện đúng cấp, đúng đơn vị, đúng năm |
| Kiểm tra thiếu sót | Chỉ ra hồ sơ còn thiếu điều kiện đạt, thiếu ngày cấp, thiếu đơn vị cấp, thiếu minh chứng cấp cũ |
| Tóm tắt hồ sơ | Tóm tắt nhanh điểm mạnh/yếu của hồ sơ cho cán bộ xét duyệt |
| Gợi ý bổ sung | Gợi ý sinh viên cần bổ sung minh chứng hoặc hoạt động nào trước deadline |
| RAG chatbot | Trả lời câu hỏi theo đúng bộ quy chế/tiêu chí của khoa, trường, thành phố/tỉnh hoặc Trung ương |
| Phát hiện bất thường | Gắn cờ các minh chứng mờ, thông tin không khớp, hồ sơ nghi ngờ cần kiểm tra thủ công |

Nguyên tắc quan trọng:

- AI chỉ đưa ra gợi ý.
- Cán bộ từng cấp là người xác nhận cuối cùng.
- Mọi quyết định duyệt/từ chối phải có log người duyệt, thời gian và lý do.

## 11. Trạng thái hồ sơ đề xuất

### 11.1. Trạng thái chung

```text
draft
submitted
locked_after_deadline
under_review
request_changes
approved
rejected
```

### 11.2. Trạng thái theo cấp

```text
faculty_draft
faculty_submitted
faculty_locked
faculty_reviewing
faculty_request_changes
faculty_approved
faculty_rejected

school_draft
school_submitted
school_locked
school_reviewing
school_request_changes
school_approved
school_rejected

city_draft
city_submitted
city_locked
city_reviewing
city_request_changes
city_approved
city_rejected

central_draft
central_submitted
central_locked
central_reviewing
central_request_changes
central_approved
central_rejected
```

### 11.3. Quy tắc chuyển cấp

| Điều kiện | Kết quả |
|---|---|
| Đạt cấp khoa | Được quyền nộp cấp trường |
| Không đạt cấp khoa | Không được nộp cấp trường |
| Đạt cấp trường | Được quyền nộp cấp thành phố/tỉnh |
| Không đạt cấp trường | Giữ danh hiệu cấp khoa, không được nộp cấp thành phố/tỉnh |
| Đạt cấp thành phố/tỉnh | Được quyền nộp cấp Trung ương |
| Không đạt cấp thành phố/tỉnh | Giữ danh hiệu cấp trường, không được nộp cấp Trung ương |
| Đạt cấp Trung ương | Được ghi nhận danh hiệu Sinh viên 5 tốt cấp Trung ương |

## 12. Thiết kế dữ liệu sơ bộ

### 12.1. StudentProfile

- `id`
- `student_code`
- `full_name`
- `school_id`
- `faculty_id`
- `faculty`
- `class_name`
- `email`
- `phone`
- `identity_verified`

### 12.2. Organization

- `id`
- `name`
- `type`: `faculty`, `school`, `city`, `central`
- `parent_id`
- `location`

### 12.3. CriteriaSet

Đây là bộ điều kiện triển khai theo từng đơn vị/cấp/năm. Nó không thay thế 5 nhóm tốt cố định, mà quy định cách đạt từng nhóm tốt ở một đơn vị cụ thể.

- `id`
- `organization_id`
- `level`: `faculty`, `school`, `city`, `central`
- `year`
- `round_id`
- `name`
- `parent_criteria_set_id`
- `status`: `draft`, `active`, `archived`
- `effective_from`
- `effective_to`
- `rules_json`

### 12.4. GoodCategory

Đây là danh mục cố định toàn hệ thống.

- `id`
- `code`: `dao_duc`, `hoc_tap`, `the_luc`, `tinh_nguyen`, `hoi_nhap`
- `name`: `Đạo đức tốt`, `Học tập tốt`, `Thể lực tốt`, `Tình nguyện tốt`, `Hội nhập tốt`
- `description`

### 12.5. CriterionRequirement

Đây là điều kiện đạt từng nhóm tốt theo từng `CriteriaSet` của đơn vị.

- `id`
- `criteria_set_id`
- `good_category_id`
- `requirement_name`
- `description`
- `required_evidence`
- `min_requirement`
- `is_required`
- `weight`
- `validation_rule_json`

### 12.6. ReviewCycle

- `id`
- `year`
- `name`
- `status`
- `evidence_valid_from`
- `evidence_valid_to`
- `evidence_retention_policy_id`

### 12.7. ReviewRound

- `id`
- `cycle_id`
- `level`: `faculty`, `school`, `city`, `central`
- `organization_id`
- `criteria_set_id`
- `open_at`
- `close_at`
- `review_start_at`
- `review_end_at`
- `status`: `upcoming`, `open`, `locked`, `reviewing`, `completed`

### 12.8. Application

- `id`
- `student_id`
- `cycle_id`
- `round_id`
- `level`
- `organization_id`
- `criteria_set_id`
- `status`
- `previous_award_id`
- `source_application_id`
- `submitted_at`
- `locked_at`

### 12.9. Evidence

- `id`
- `student_id`
- `application_id`
- `file_url`
- `file_type`
- `issued_at`
- `valid_status`: `valid`, `expired`, `pending_review`
- `ocr_text`
- `metadata`
- `suggested_criteria`
- `confidence_score`
- `verified_status`
- `deleted_at`

### 12.10. EvidenceRetentionPolicy

- `id`
- `cycle_id`
- `valid_from`
- `valid_to`
- `soft_delete_after_days`
- `hard_delete_after_days`
- `created_by_admin_id`

### 12.11. Award

- `id`
- `student_id`
- `cycle_id`
- `level`
- `organization_id`
- `issued_at`
- `decision_number`
- `certificate_file_url`

### 12.12. ReviewDecision

- `id`
- `application_id`
- `reviewer_id`
- `level`
- `decision`: `approved`, `rejected`, `request_changes`
- `comment`
- `created_at`

## 13. Kiến trúc module đề xuất

```text
Frontend Web App
    +-- Không gian Sinh viên
    +-- Dashboard Cán bộ cấp khoa
    +-- Dashboard Cán bộ cấp trường
    +-- Dashboard Cán bộ cấp thành phố/tỉnh
    +-- Dashboard Cán bộ Trung ương
    +-- Admin Console

Backend API
    +-- Auth & Role-based Access
    +-- Organization Service
    +-- Review Cycle/Round Service
    +-- Criteria Set Inheritance Service
    +-- Profile Service
    +-- Application Service
    +-- Evidence Service
    +-- Evidence Vault & Retention Service
    +-- Criteria Service
    +-- AI Evaluation Service
    +-- Review Workflow Service
    +-- Award Service
    +-- Portfolio Service
    +-- Notification Service
    +-- Audit Log Service

Storage
    +-- Database
    +-- Object Storage
    +-- Redis Cache

AI/API
    +-- VNPT SmartReader
    +-- VNPT Smartbot
    +-- VNPT eKYC
    +-- VNPT SmartVoice
    +-- VNPT SmartUX
```

## 14. MVP đề xuất cho HackAIthon

Vì thời gian thi ngắn, MVP nên chứng minh được logic liên cấp nhưng không cần làm đầy đủ mọi nghiệp vụ Trung ương.

### 14.1. MVP bắt buộc

- Đăng nhập giả lập theo vai trò:
  - Sinh viên
  - Cán bộ cấp khoa
  - Cán bộ cấp trường
  - Cán bộ cấp thành phố/tỉnh
  - Cán bộ Trung ương
- Tạo một chu kỳ xét năm học mẫu.
- Tạo cây tổ chức mẫu: 1 khoa, 1 trường, 1 thành phố/tỉnh, Trung ương.
- Tạo bộ điều kiện đạt mẫu khác nhau cho khoa, trường, thành phố/tỉnh và Trung ương.
- Tạo 4 đợt xét danh hiệu: khoa, trường, thành phố/tỉnh, Trung ương.
- Admin cấu hình thời gian minh chứng hợp lệ cho chu kỳ xét.
- Sinh viên upload minh chứng vào kho cá nhân và hệ thống đánh dấu minh chứng còn hiệu lực/hết hạn.
- Sinh viên chọn minh chứng còn hiệu lực để nộp hồ sơ cấp khoa trong thời gian cổng mở.
- Sau deadline, hồ sơ bị khóa.
- Cán bộ cấp khoa duyệt hồ sơ có AI hỗ trợ.
- Nếu đạt, hệ thống cấp danh hiệu cấp khoa và mở quyền nộp cấp trường.
- Sinh viên bổ sung hồ sơ cấp trường.
- Cán bộ cấp trường duyệt.
- Nếu đạt, hệ thống cấp danh hiệu cấp trường và mở quyền nộp cấp thành phố/tỉnh.
- Sinh viên bổ sung hồ sơ cấp thành phố/tỉnh.
- Cán bộ cấp thành phố/tỉnh duyệt.
- Nếu đạt, hệ thống mở quyền nộp cấp Trung ương.
- Cán bộ Trung ương xem hồ sơ đã qua cấp thành phố/tỉnh và duyệt cuối.

### 14.2. AI trong MVP

- Upload minh chứng ảnh/PDF.
- OCR bằng SmartReader hoặc mock adapter nếu API chưa ổn định.
- AI chọn đúng bộ điều kiện đạt theo khoa/trường/thành phố/Trung ương trước khi đánh giá.
- AI phân loại minh chứng vào 5 nhóm tốt theo bộ điều kiện của đúng đơn vị xét.
- AI báo thiếu minh chứng cấp cũ khi sinh viên xét cấp cao hơn.
- AI tóm tắt hồ sơ cho cán bộ.

### 14.3. Phần có thể mô phỏng

- Văn bản đề nghị cấp thành phố gửi Trung ương.
- Danh sách chính thức gửi Trung ương.
- Chứng nhận/danh hiệu cấp cũ.
- CSDL đối chiếu minh chứng.

## 15. Giá trị mang lại

### 15.1. Với sinh viên

- Không phải quản lý hồ sơ rời rạc ở nhiều nơi.
- Biết mình đủ điều kiện nộp cấp nào.
- Biết chính xác bộ điều kiện đạt đang áp dụng cho khoa/trường/thành phố/tỉnh của mình.
- Tái sử dụng hồ sơ cấp cũ, chỉ bổ sung phần còn thiếu.
- Theo dõi rõ trạng thái xét duyệt.
- Có danh hiệu và portfolio được ghi nhận theo từng cấp: khoa, trường, thành phố/tỉnh, Trung ương.

### 15.2. Với cán bộ Đoàn - Hội

- Giảm thời gian kiểm tra hồ sơ thủ công.
- Dễ lọc hồ sơ theo cấp, khoa, trường, thành phố/tỉnh, trạng thái.
- Dễ cấu hình điều kiện đạt theo đơn vị thay vì dùng một biểu mẫu cứng cho tất cả.
- Có AI hỗ trợ đọc minh chứng và tóm tắt hồ sơ.
- Có log xét duyệt minh bạch.
- Dễ tổng hợp danh sách đạt từng cấp.

### 15.3. Với hệ thống phong trào Sinh viên 5 tốt

- Chuẩn hóa quy trình từ khoa đến Trung ương.
- Vẫn cho phép mỗi khoa, trường, thành phố/tỉnh triển khai điều kiện đạt linh hoạt theo kế hoạch riêng.
- Tăng tính minh bạch và truy vết.
- Giảm sai sót khi chuyển hồ sơ giữa các cấp.
- Tạo dữ liệu dài hạn về hành trình phấn đấu của sinh viên.
- Biến danh hiệu Sinh viên 5 tốt thành một hồ sơ năng lực có giá trị sử dụng tiếp.

## 16. Rủi ro và hướng xử lý

| Rủi ro | Hướng xử lý |
|---|---|
| Quy trình mỗi khoa/trường/tỉnh có biến thể riêng | Thiết kế tiêu chí, deadline, biểu mẫu và phân quyền dạng cấu hình; hỗ trợ kế thừa tiêu chí từ cấp trên và bổ sung điều kiện riêng của đơn vị |
| AI OCR hoặc phân loại sai | Hiển thị OCR text, confidence score, lý do gợi ý; cán bộ duyệt cuối |
| Sinh viên bổ sung sau deadline | Hệ thống khóa hồ sơ theo đợt; chỉ admin có quyền mở lại trong trường hợp đặc biệt |
| Hồ sơ cấp cao thiếu minh chứng cấp cũ | Hệ thống kiểm tra `Award` cấp cũ trước khi cho nộp cấp mới |
| Xóa nhầm minh chứng còn cần dùng | Dùng trạng thái hết hạn, thông báo trước, soft delete và retention window; không xóa ngay minh chứng đã gắn với hồ sơ đã nộp, quyết định duyệt hoặc audit log |
| Dữ liệu cá nhân nhạy cảm | Phân quyền theo cấp tổ chức, signed URL cho file, log truy cập, xóa dữ liệu demo |
| MVP quá rộng | Demo 1 sinh viên, 1 khoa, 1 trường, 1 thành phố, 1 chu kỳ xét với 4 đợt liên tiếp |

## 17. Kết luận

5-Star Eco nên được định vị là **hệ sinh thái phong trào Sinh viên 5 tốt**, không chỉ là công cụ upload và xét hồ sơ. Điểm khác biệt cốt lõi nằm ở việc hệ thống mô hình hóa đúng hành trình liên cấp:

```text
Cấp khoa -> Cấp trường -> Cấp thành phố/tỉnh -> Cấp Trung ương
```

Trong đó, cả 4 cấp đều là các cấp xét danh hiệu trong hệ sinh thái; cấp khoa là cấp đầu tiên và gần sinh viên nhất, giúp sinh viên bắt đầu hành trình từ môi trường trực tiếp của mình trước khi lên cấp trường. Năm nhóm tốt luôn cố định, nhưng mỗi đơn vị có thể có bộ điều kiện đạt, deadline, cán bộ phụ trách và yêu cầu minh chứng riêng. Sinh viên đạt cấp dưới mới được quyền xét cấp cao hơn; hồ sơ cấp cũ và minh chứng danh hiệu cấp cũ được tái sử dụng để giảm rườm rà.

AI giúp tối ưu các bước nặng thao tác như đọc minh chứng, phân loại tiêu chí, phát hiện thiếu sót và tóm tắt hồ sơ. Tuy nhiên, quyết định cuối cùng luôn thuộc về cán bộ phụ trách từng cấp. Cách tiếp cận này vừa đảm bảo tính minh bạch, vừa phù hợp với thực tế vận hành phong trào Sinh viên 5 tốt trên phạm vi nhiều trường, nhiều thành phố/tỉnh và cấp Trung ương.
