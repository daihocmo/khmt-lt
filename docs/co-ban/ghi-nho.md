# Ghi nhớ trong lập trình

Cá nhân mình sẽ phân loại ra thành 2 loại kiến thức:

- Cần hiểu & ghi nhớ (& Sử dụng thường xuyên).
- Chỉ cần biết và có thể tìm kiếm hoặc tra cứu để sử dụng lại.

## Sử dụng Anki (SRS và Active Recall) cho loại 1

Đọc phương pháp Janki thông qua hai bài viết dưới đây:

- [Janki Method — Using SRS to Improve Programming](https://www.semicolonandsons.com/articles/janki-method)
- [Janki Method Refined](https://www.semicolonandsons.com/articles/janki-method-refined)
- [Memorizing a programming language using spaced repetition software](https://sive.rs/srs)

(Phần dưới đây trích dẫn từ [using_anki_to_learn_programming](https://old.reddit.com/r/Anki/comments/hxmcmg/using_anki_to_learn_programming/fz7n01k/))

**Anki là một công cụ tuyệt vời để học lập trình** — *đặc biệt* nếu bạn muốn nắm vững một lượng lớn ngôn ngữ và công cụ (chứ không chỉ dừng ở những kiến thức cơ bản). Tôi là một kỹ sư AI, và Anki đã trở thành một phần không thể thiếu trong quy trình làm việc chuyên nghiệp của tôi. Tôi nhận thấy rằng nó giúp tôi làm được rất nhiều điều mà phương pháp truyền thống kiểu “cứ dùng StackOverflow rồi cuối cùng cũng nhớ những thứ hay dùng” không thể.

### Hướng dẫn thiết kế thẻ cơ bản

Đây là một vài ví dụ về các thẻ lập trình tôi tạo ra trong Anki (có ví dụ Python ở gần cuối):
[https://imgur.com/a/LxS18YK](https://imgur.com/a/LxS18YK)

**Thiết kế thẻ tốt là điều thiết yếu.** Luôn thêm **hình ảnh** (bắt buộc), **tránh dùng cloze** (tôi chưa từng tạo thẻ cloze nào về lập trình mà sau này không cảm thấy khó chịu), và như với bất kỳ chủ đề nào, hãy cố tìm các **câu hỏi mốc** quan trọng — những câu hỏi mang tính định hướng và giúp bạn hiểu hệ thống từ trên xuống (thay vì chui ngay vào các cú pháp chi tiết mà có khi bạn chẳng bao giờ dùng tới). Tránh tạo **thẻ đơn lẻ**: các thẻ nên được nhóm lại thành một tổng thể trực quan; học một thẻ sẽ giúp bạn dễ nhớ những thẻ còn lại.

Tất nhiên, bạn cũng phải **áp dụng** những gì đã học thì mới có kỹ năng thực sự, và lập trình (như bất kỳ kỹ năng nào khác) không thể rút gọn hoàn toàn thành việc ghi nhớ — nhưng điều đó thì ai cũng biết rồi. Với mọi lĩnh vực học qua Anki, từ ngôn ngữ tự nhiên (như tiếng Pháp, tiếng Hàn) đến lịch sử, điều này đều đúng.

**Cảnh báo:** những thứ tùy tiện, vô nghĩa rất khó để tạo thẻ Anki hiệu quả. Và trong lập trình, **rất nhiều chi tiết về cú pháp thực sự vô nghĩa**. Ví dụ: là `s.strip()` hay `s.trim()`? Một cái là Python, một cái là Java, nhưng phân biệt chúng qua flashcard rất khó về lâu dài, vì không có liên hệ trực quan nào để giải thích hay khắc sâu sự khác biệt. Theo cách đó, lập trình có thể còn khó học bằng Anki hơn các chủ đề trừu tượng như thuật toán hay toán học.

**Cách tiếp cận của tôi** là tập trung vào các **mốc khái niệm** trong một hệ thống, rồi mới dần đi xuống phần cú pháp, nhưng chỉ khi tôi dự đoán sẽ dùng công cụ đó nhiều, hoặc thấy nó thực sự thú vị.

#### Tạo thẻ để nhớ **một công cụ nào đó**:

- “Thư viện đồ họa tiêu chuẩn cho Python là gì?” → `TkInter`.
- “Framework web chính của Facebook là gì?” → React.
- “Framework serialize dữ liệu do Google phát triển?” → Protocol Buffers.
- “Dịch vụ đám mây nào của Amazon dùng cho mô phỏng và điều khiển robot?” → AWS RoboMaker.
- “Thư viện quản lý workflow của Python do Spotify phát triển?” → Luigi.

#### Các khái niệm **tổng quát, không phụ thuộc ngôn ngữ**
- “Bốn loại chính của cơ sở dữ liệu no-SQL là gì?” → Columnar, Graph, Key-value store, Document.
- “Hai chế độ render chính của trình duyệt web là gì?” → Standards mode và quirks mode.
- “Container orchestration là gì?”
- “Sự khác biệt giữa mảng dạng row-oriented và column-oriented là gì?”
- “Tại sao tốc độ xung nhịp CPU lại dừng lại từ khoảng năm 2004?”

#### Kết nối công cụ với các khái niệm quan trọng

“Cơ sở dữ liệu document-oriented phổ biến nhất là gì?” → MongoDB.

#### Tạo thẻ cấp cao để nhớ các **thành phần quan trọng** của một hệ thống
  
- “File YAML bao gồm hai loại phần tử nào?” → lists và maps.
- “Thuật ngữ nào chỉ các đối tượng lưu trữ cơ bản trong Kubernetes cluster?” → Resources.
- “Loại resource Kubernetes nào duy trì số lượng Pod ổn định và đảm bảo luôn có đủ số Pod?” → `ReplicaSet`.
- “Loại resource Kubernetes nào thêm lệnh mới vào CLI?” → `CustomResourceDefinition`.

Tới bước này, tôi đã nắm đủ kiến thức để suy luận về các quyết định thiết kế và lập kế hoạch dự án — đây chính là một trong những mục tiêu chính khi tôi dùng Anki (để biết đủ về công nghệ hiện có và chọn đúng công cụ/thết kế cho dự án).

Cuối cùng, **khi đã có bức tranh tổng thể** để giúp trí nhớ có điểm liên kết và tôi đã có lý do để đi sâu hơn, tôi sẽ chuyển sang học **cú pháp** — tập trung vào những cú pháp quan trọng mà tôi nghĩ là sẽ hay dùng:

- “Map trông như thế nào trong file YAML?”
- “Cách thể hiện resource type trong file YAML của Kubernetes?”
- “Lệnh nào tạo hoặc cập nhật resource Kubernetes từ một file YAML?” v.v.

### Chọn nội dung để thêm vào Anki

#### Không nên đưa vào Anki

Một số thứ không nên đưa vào Anki. Việc tạo thẻ Anki tốn thời gian, nên bạn cần đảm bảo là mình nhận được lợi ích tương xứng. Các nội dung sau đây thường có giá trị thấp, thậm chí là không có giá trị gì cả:

* **Cú pháp ngôn ngữ:** giá trị thấp. Đa số ngôn ngữ lập trình đều na ná nhau. Bạn không cần phải tạo thẻ để nhớ Java viết là `x.length()`, `x.length`, hay `len(x)` — sau một thời gian sử dụng thực tế, bạn sẽ tự nhớ thôi.
* **Chi tiết cụ thể về API / thư viện:** cần phân biệt rõ — bạn nên tạo thẻ cho **các khái niệm quan trọng** của thư viện, nhưng **đừng phí thời gian** tạo thẻ cho từng hàm riêng lẻ hay chữ ký hàm (function signature).
* **Những thứ sắp lỗi thời:** nếu nội dung nhanh chóng lỗi thời, thì không đáng để ghi nhớ lâu dài bằng Anki.

#### Nên đưa vào Anki

* **Design Patterns** (mẫu thiết kế phần mềm)
* **Software Principles** (các nguyên lý thiết kế phần mềm)
* **Testing Principles** (các nguyên lý kiểm thử phần mềm)
* **Version control / Git:** hãy học sâu vào phần này. Nó là một siêu năng lực trong công việc hằng ngày của bạn.
* **Networking:** hiểu sâu về HTTP, IP, TCP, UDP,... Học nhiều hơn bạn nghĩ mình cần — sẽ rất có ích.
* **Unix/Linux:** tương tự như trên, học sâu hơn mức bạn dùng hàng ngày, vì về lâu dài sẽ giúp bạn rất nhiều.
* **Mô hình xử lý song song**: threads, coroutines, reactive programming, event loop, actor model.
* **Công cụ dòng lệnh Unix**: awk, sed, grep,... Không cần học hết tất cả lệnh, chỉ cần biết chúng tồn tại và được dùng để giải quyết vấn đề gì.
* **Phím tắt quan trọng** (keyboard shortcuts)
* **Ôn luyện phỏng vấn**: các dạng câu hỏi leetcode, leetcode patterns, câu hỏi hành vi (behavioral questions)
* **Cấu trúc dữ liệu và Thuật toán**
* **Nguyên lý lập trình hướng đối tượng** (OOP)
* **Nguyên lý lập trình hàm** (Functional programming)
* **Kiến thức nền tảng về Cơ sở dữ liệu**
* **Tất cả nội dung trong sách “Designing Data-Intensive Applications”**
* Nếu bạn muốn vươn tới **các cấp độ cao hơn Senior Software Engineer**, thì nên đưa vào Anki một số bài báo học thuật như: **MapReduce**, **BigTable**, **Dynamo**, **Spanner**, **Kafka**, v.v.
* Sau khi **giải quyết một bài toán khó** hoặc **sửa được một bug khó**, hãy cân nhắc tạo vài thẻ về: *tại sao nó khó*, và *có thể tiếp cận tốt hơn thế nào* nếu gặp lại.
* Và còn nhiều nữa...

## Loại 2

Hay còn được gọi là Code Diary. Đọc thêm trong bài [Nhật kí lập trình](nhat-ky-code.md)