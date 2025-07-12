# Lên kế hoạch cho dự án lập trình
Bài viết này được dịch từ bài viết gốc [How to Plan and Build a Programming Project - A Legitimate Guide for Beginners](https://www.peterlunch.com/blog/how-to-plan-and-build-a-programming-project). Vì bản dịch này sẽ là dịch cho cá nhân mình đọc nên là nếu mọi người đọc mà thấy có vấn đề ở đoạn nào thì gửi Issue hoặc Pull Request lên Github nha. 

Bài viết này sẽ giải thích cách lập kế hoạch và xây dựng một dự án lập trình, cách chia nhỏ một dự án để bạn có thể bắt đầu thực hiện những dự án đỉnh của chóp nhằm giúp nâng cao kỹ năng lập trình.

Bài viết này sẽ không hướng dẫn cách cấu trúc thư mục, các practices tốt nhất để có thể xây dựng dự án hoặc cách cài đặt Extensions của VSCode để giúp đạt được clean code. Bài này được viết ra để giúp những người mới lập trình cảm thấy bớt sợ hãi hơn khi họ cố gắng thoát khỏi tutorial hell (tutorial hell, học quá nhiều nhưng không áp dụng) và xây dựng những dự án lập trình của riêng mình.

Khi mới bắt đầu thì đống dự án trông sẽ rất dễ khiến bạn nản. Khi mới bắt đầu học lập trình, tôi sẽ bắt đầu học một khóa học hoặc làm theo hướng dẫn và nghĩ rằng mình đã hiểu hướng dẫn. Tuy nhiên, khi ngừng xem và cố gắng thực hiện lại lại những gì đã học, tôi đã không thể làm được.

Để khắc phục điều này, tôi đã đăng bài viết về sự thất vọng của mình lên subreddit [r/learnprogramming](https://www.reddit.com/r/learnprogramming/). Những phản hồi tôi nhận được đều tập trung vào việc xây dựng những dự án của riêng mình. Lời khuyên này thoạt nghe có vẻ hay và là lời khuyên đúng đắn, tuy nhiên vấn đề đối với tôi là tôi thậm chí không thể xem hướng dẫn và tự viết lại được. Tôi phải xây dựng một dự án như thế nào? Một dự án lớn hơn 10 cấp độ so với phần hướng dẫn và vào thời điểm đó, dường như những dự án đó vượt xa khả năng của tôi. Tôi thậm chí còn không biết phải bắt đầu như thế nào chứ đừng nói đến việc tôi sẽ kết hợp tất cả lại với nhau như thế nào. Vấn đề cơ bản là tôi không biết cách đi từ điểm A đến điểm B.

![](https://www.peterlunch.com/_next/image?url=%2Fimages%2FarticleImgs%2Fgood-example-of-build-something-800x467.png&w=1920&q=75)

Những người mới bắt đầu cảm thấy thất vọng vì dường như họ không thể thoát khỏi tutorial hell và vì vậy họ tìm kiếm lời khuyên. Tuy nhiên, redditor lại phản hồi mà không hề cân nhắc rằng nếu người mới bắt đầu đó không thể bắt chước lại một tutorial thì họ sẽ tự tạo dự án của riêng mình như thế nào. Trong thời gian học lập trình, tôi đã thấy rất nhiều ví dụ về cùng một câu hỏi mà tôi có và những câu trả lời giống nhau.

Để lập kế hoạch và xây dựng một dự án lập trình, hiện nay tôi sử dụng ba bước chính khi xây dựng dự án, vì vậy hãy bắt đầu với bước đầu tiên.

## Bước 1: Xác định dự án

Bước đầu tiên khi lập kế hoạch cho một dự án lập trình là xác định nó.

Định nghĩa dự án là một mô tả về dự án bằng ngôn ngữ viết. Nó phải cực kỳ đơn giản để bất kỳ ai đọc nó cũng có thể hiểu dự án nói về cái gì.

Khi bắt đầu định nghĩa dự án của mình, hãy tự hỏi 4 điều sau:

1. Dự án của bạn là gì và về cái gì?
2. [MVP](https://www.productplan.com/glossary/minimum-viable-product/) (Minimal Viable Product hay "Sản phẩm khả thi tối thiểu") của dự án đó là gì?
3. Sprinkles là gì?
4. Khi nào dự án sẽ hoàn thành?

> Sprinkles ở đây có nghĩa là trang trí (bánh donut), và nó không liên quan gì đến thuật ngữ Tiếng Anh chuyên ngành đâu. Ở đây có thể hiểu Sprinkles là "trang trí dự án của bạn thêm lung linh" (Đọc tiếp sẽ rõ). 

### Doughnut (MVP) before the sprinkles

Một trong những bài học mà tôi đã học được ngay từ đầu khóa bootcamp của mình là ta cần có bánh donut thì mới có thể trang trí được.

![three donuts on table with sprinkles](https://www.peterlunch.com/_next/image?url=%2Fimages%2FarticleImgs%2Fpatrick-fore-ZmH0g1ievTg-unsplash.jpg&w=1920&q=75)

Có thể bạn luôn muốn làm cho một cái gì đó trông thật ngầu và thêm các tính năng hay. Tuy nhiên, nếu ứng dụng của bạn không hoàn thành được các chức năng cơ bản thì những tính năng tuyệt vời đó sẽ chẳng đi đến đâu cả. The sprinkles have no doughnut to go on (Nếu chưa có bánh donut thì làm sao mà có thể trang trí được).

Vì vậy, hãy đảm bảo rằng bạn xác định được MVP là gì trước khi bắt đầu quá trình sprinkles của mình.

### Một bản định nghĩa dự án mẫu

Để đưa ra một ví dụ đơn giản, giả sử chúng ta sắp xây dựng một ứng dụng máy tính (calculator), chúng ta sẽ có bản định nghĩa dự án cơ bản như thế nào:

**Dự án "ứng dụng máy tính"**

**Dự án của bạn là gì và về cái gì?**: Dự án máy tính là một dự án xây dựng một máy tính có thể truy cập trên trình duyệt. Dự án sẽ được xây dựng bằng HTML, CSS và JavaScript. Nó sẽ cho phép người dùng nhập số và tính kết quả của những số đó dựa trên phép toán mà họ chọn.

**MVP là gì?**: Một máy tính hiển thị trong trình duyệt web có thể thực hiện các phép tính cộng, trừ, nhân và chia dựa trên input của người dùng và hiển thị cho người dùng kết quả của phép tính ấy.

**Sprinkles là gì?**: Là styling cho ứng dụng máy tính, nhận Input từ bàn phím chứ không chỉ là bấm các nút ở trên màn hình. Đồng thời một số các chức năng cao cấp hơn ví dụ như là tính số mũ của x.

**Khi nào dự án sẽ hoàn thành?**: Dự án sẽ hoàn thành sau khi tất cả các tính năng MVP đã được implemented và ứng dụng máy tính đã được viết và thiết kế giao diện xong (Ở đây có thể hiểu từ "thiết kế" là hoàn thành viết phần HTML/CSS cho máy tính đó).

Định nghĩa trên rất đơn giản và dễ hiểu. Nếu người khác đọc nó, họ sẽ hiểu dự án đó là gì. Bản thiết kế đấy cho bạn biết dự án là gì, các tính năng MVP mà bạn phải xây dựng, những features hay có thể sẽ được thêm và khi nào dự án sẽ hoàn thành. Bằng cách xác định dự án, bạn sẽ làm cho dự án bớt khó nhằn hơn.

Khi bạn đã xác định được dự án, bạn có thể bắt đầu bước tiếp theo.

## Bước 2: Tạo quy trình làm việc

Bước tiếp theo là đơn giản nhất. Thông thường, bước này có thể được kết hợp với bước 3. Tuy nhiên, bây giờ chúng ta sẽ xem nó ở đây như một bước riêng biệt để tôi có thể chỉ cho bạn cách thiết lập quy trình làm việc rất cơ bản cho những dự án của riêng bạn. Khi bạn đã thực hiện nó một lần, nó có thể là bước mặc định cho những dự án còn lại của bạn.

Sử dụng một công cụ miễn phí như [Trello](https://trello.com/) để quản lý dự án, sử dụng khung quy trình làm việc [Kanban](https://www.atlassian.com/agile/kanban). Bạn không cần phải biết hoặc hiểu Kanban là gì khi mới bắt đầu, bạn chỉ cần sử dụng như cách làm ở đây.

Để xây dựng bảng Kanban, hãy tạo 4 cột:

1.  TODO (Cần làm)
2.  DOING (Đang làm)
3.  DONE (Đã làm xong)
4.  BUGS / NOT SURE HOW TO DO (Lỗi, không biết nên làm gì)

![Trello kanban board with 4 columns todo, doing, done and bugs.](https://www.peterlunch.com/_next/image?url=%2Fimages%2FarticleImgs%2Fkanban-1-800x415.png&w=1920&q=75)

Trong các cột này, chúng ta sẽ thêm thẻ. Khi làm việc trên các thẻ đó, chúng ta sẽ chuyển chúng vào cột **DOING** và sau khi hoàn thành thẻ đó, chúng ta có thể chuyển nó sang cột **DONE**. Nếu bạn gặp phải một lỗi nào đó hoặc không chắc chắn về cách thực hiện điều gì đó, chúng ta có thể chuyển lỗi đó sang cột **BUGS / NOT SURE HOW TO DO**.

Quy trình này là một phiên bản siêu đơn giản của Kanban và khi làm việc với vai trò là một developer, rất có thể bạn sẽ có nhiều cột hơn như testing, coding review, backlog và các cột khác. Tuy nhiên, đối với những dự án cá nhân và đặc biệt là với người mới bắt đầu, chỉ cần như này là đủ.

Bây giờ chúng ta đã thiết lập xong quy trình làm việc, chúng ta có thể bắt đầu bước cuối cùng.

## Bước 3: Chia dự án thành các phần nhỏ hơn

Chìa khóa để xây dựng những dự án của riêng bạn bắt đầu bằng việc chia dự án lớn thành các phần nhỏ hơn, bớt khó nhằn hơn. Những thành phần nhỏ hơn này sẽ trở thành thẻ của chúng ta từ bước 2.

Bây giờ điều này nghe có vẻ đơn giản, nhưng khi tôi mới bắt đầu, tôi đã không nghĩ rằng bạn có thể làm được điều này. Tôi nghĩ hầu hết các nhà phát triển khi bắt đầu lập trình thì dự án của họ cứ hoàn thành một cách tự nhiên giống như bạn thấy trong phim. Tôi đã nghĩ đó là điều tôi phải làm được. Tuy nhiên, khi được làm việc trong ngành này, tôi biết rằng điều đó là chưa đúng, trên thực tế, một nhà phát triển giỏi sẽ chia dự án đó thành các phần nhỏ nhỏ hơn.

![estefannie giả vờ lập trình như trong phim](https://www.peterlunch.com/_next/image?url=%2Fimages%2FarticleImgs%2Fgiphy-downsized.gif&w=1080&q=75)

Tuy nhiên, là người mới bắt đầu, có thể khó biết cách chia nhỏ một việc gì đó thành các phần nhỏ hơn. Nếu bạn không biết cách thực sự xây dựng dự án thì làm sao bạn có thể chia nhỏ nó?

Chà, điều đầu tiên bạn cần làm là xem xét định nghĩa dự án của mình và sau đó chia nó thành các phần nhỏ hơn.

Hãy tiếp tục sử dụng ví dụ về ứng dụng máy tính để tạo các thẻ thành phần của chúng ta:

1. Hàm tính toán – MVP
2. Nhận input của người dùng - MVP
3. Giao diện người dùng HTML - MVP
4. Tạo kiểu CSS cho giao diện người dùng - sprinkles ✨
5. EventListener cho JavaScript - MVP
6. Thêm animation cho phép tính - sprinkles ✨

![bảng trello với thẻ việc cần làm từ danh sách trên](https://www.peterlunch.com/_next/image?url=%2Fimages%2FarticleImgs%2Fkanban-2-800x373.png&w=1920&q=75)

Bạn sẽ nhận thấy rằng đối với mỗi thẻ, chúng ta đã gán nhãn MVP hoặc nhãn sprinkles. Điều này nhằm giúp bạn nhìn thấy một cách trực quan những thẻ nào là quan trọng nhất và do đó thẻ nào nên được sử dụng đầu tiên.

Lợi ích lớn nhất của các tấm thẻ là chúng đã đơn giản hóa những gì chúng ta phải làm rồi. Điều này làm cho những dự án bớt khó nhằn hơn và thay vì nghĩ rằng phải ngồi viết tất cả ứng dụng máy tính trong một lần code, bạn sẽ làm 6 dự án nhỏ hơn sẽ kết hợp để tạo ra một dự án lớn.

Khi bạn đang trong quá trình hoàn thiện nhiệm vụ trên một thẻ, bạn sẽ di chuyển nó vào cột đang làm. Dành thời gian để thành phần hoạt động trước khi bạn chuyển sang thẻ tiếp theo.

Nhưng chúng ta vẫn chưa xong đâu! Chúng ta còn có thể đơn giản hóa và cải thiện quy trình làm việc của mình hơn nữa để đảm bảo rằng chúng ta không bị cản trở bởi quy mô của dự án trong quá trình phát triển.

### Chia từng thành phần (component) thành các checklists nhỏ hơn

Sau khi có thẻ cấp cao, chúng ta có thể chia các thành phần đó thành các nhiệm vụ nhỏ hơn bằng cách chia các nhiệm vụ đó thành một checklist (hay danh sách kiểm tra hoặc na ná to-do list) gồm các nhiệm vụ nhỏ khác để chúng ta có thể theo dõi tiến trình của mình.

Ví dụ: Hãy sử dụng thẻ "chức năng tính toán" làm ví dụ về cách chia nhỏ một thành phần hơn nữa.

Vì nhiệm vụ này là nhiệm vụ MVP và tôi đã xác định MVP là các phép tính cơ bản cộng, trừ, nhân và chia nên chúng ta cần thêm các hàm đó vào checklist, từng hàm một, cộng, trừ, nhân, chia (Nhìn ở hình bên dưới).

![checklist các nhiệm vụ cần hoàn thành](https://www.peterlunch.com/_next/image?url=%2Fimages%2FarticleImgs%2Fkanban-3-600x483.png&w=1200&q=75)

Bây giờ chúng ta đã chia thẻ chức năng tính toán thành 4 dự án nhỏ mà chúng ta có thể thực hiện. Điều đó dễ dàng hơn nhiều so với ôm cả một nhiệm vụ lớn là xây dựng một ứng dụng máy tính hoặc thậm chí là viết các chức năng của máy tính (các thẻ chức năng chính).

Bây giờ chúng ta có thể tập trung và tìm ra cách thực hiện từng chức năng này. Khi làm điều đó, chúng ta có thể đánh dấu những mục đó là đã xong, mang lại cảm giác hoàn thành nhiệm vụ trong bạn. Sau đó, khi chúng ta đã hoàn thành tất cả bốn mục đó, chúng ta có thể di chuyển thẻ đó vào cột đã hoàn thành (Done) và tiếp tục xử lý nhiệm vụ tiếp theo.

Từ đây trở đi chúng ta chỉ cần lặp lại quy trình cho mỗi thẻ. Tuy nhiên, bạn không nên dành nhiều thời gian để cố gắng làm cho mỗi thẻ có đủ các nhiệm vụ nhỏ (phần tiếp theo sẽ nói rõ hơn).

### Đừng cố khiến nó trở nên hoàn hảo

Khi chia các thẻ và các nhiệm vụ trong checklist, bạn không nhất thiết phải cố chia ra toàn bộ các function hoặc các chi tiếp trong bất kì một thẻ chức năng (component) nào.

Nếu làm vậy, bạn sẽ bị mắc kẹt trong giai đoạn lên kế hoạch mà không chuyển qua giai đoạn xây dựng dự án, hoặc dự án của bạn có thể sẽ trở nên quá cứng nhắc. Bạn cần một số khoảng trống trong những dự án của mình.

Điều tôi nhận thấy khi thực hiện những dự án của mình là tôi thường xuyên phải thêm nhiều thẻ và nhiệm vụ hơn khi thực hiện. Điều này khó có thể tránh khỏi, bạn đang xây dựng một thứ gì đó lần đầu tiên nên bạn sẽ không biết chính xác những gì bạn cần xây dựng trước khi bắt đầu.

Ví dụ: bạn có thể không có thẻ tạo kiểu (styling) khi lần đầu tiên bắt đầu lập kế hoạch cho ứng dụng máy tính của mình và chỉ nhận ra sau khi hoàn thành phần HTML rằng bạn nên tạo kiểu cho ứng dụng.

Vì vậy, đừng mắc kẹt trong việc làm một bản kế hoạch hoàn hảo, hãy viết đủ để bạn có thể bắt đầu và bổ sung thêm khi thực hiện. Bạn cũng có thể sử dụng cột **Lỗi/không biết nên làm gì** để đặt những thẻ mà bạn chưa thể làm được hoặc những thẻ bạn đang bị bí và không nghĩ ra cách và chuyển qua phần việc khác.

## Bắt đầu xây dựng dự án lập trình của bạn

Bây giờ bạn đã có thể thử lập kế hoạch và xây dựng một dự án lập trình được rồi á. Hy vọng bài đăng này giúp cho việc xây dựng dự án bớt khó nhằn và đáng sợ hơn.

Điều quan trọng là xác định rõ ràng dự án, thiết lập quy trình làm việc của bạn và sau đó chia dự án thành các thành phần nhỏ hơn để tạo ra dự án lớn hơn. Bằng cách đó, dự án sẽ không còn như một ngọn núi khổng lồ để leo lên nữa và nó sẽ trông như một chiếc thang với mỗi bước giúp bạn đạt được mục tiêu của mình.

Nếu bạn thấy ai đó đang gặp khó khăn để thoát khỏi tutorial hell, đừng chỉ bảo họ "làm nhiều dự án vào". Hãy cho họ biết cách lập kế hoạch và xây dựng.

Lập kế hoạch là điều tuyệt vời, nhưng điều quan trọng là sau đó hãy bắt đầu và xây dựng. Vì vậy, hãy tiếp tục xây dựng những dự án tuyệt vời, đồng thời nâng cao kỹ năng lập trình của bạn.
