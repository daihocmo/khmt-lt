# Định hướng tự học Fullstack
Hiện tại lộ trình này mình viết cho cá nhân mình dùng nên nó vẫn chưa được hoàn chỉnh. Mình cũng sẽ chỉnh sửa và cải thiện trong quá trình học luôn.

## Fullstack là cái gì?

> Practically all web applications have (at least) two "layers": the browser, being closer to the end-user, is the top layer, and the server the bottom one. There is often also a database layer below the server. We can therefore think of the architecture of a web application as a stack of layers.
>
> Often, we also talk about the frontend and the backend. The browser is the frontend, and the JavaScript that runs on the browser is the frontend code. The server on the other hand is the backend.
>
> In the context of this course, full-stack web development means that we focus on all parts of the application: the frontend, the backend, and the database. Sometimes the software on the server and its operating system are seen as parts of the stack, but we won't go into those.

## Chọn lộ trình khác

Nếu bạn muốn học những lộ trình khác thì có thể thử:

- [Fullstack Open](https://fullstackopen.com/en/)
- [TheOdinProject](https://www.theodinproject.com/)
- [FreeCodeCamp](https://www.freecodecamp.org/learn/full-stack-developer/)

Bạn hoàn toàn có thể sử dụng những hướng dẫn Fullstack trên để hỗ trợ quá trình học của mình.

## Lộ trình học
Lộ trình sẽ được chia ra làm 26 tuần. Cách học cơ bản của lộ trình là trong mỗi tuần sẽ có những phần kiến thức mà bạn cần (mình nghĩ là cần) học. Bạn hoàn toàn có thể bỏ qua những phần bạn đã học từ trước hoặc muốn học sau (Khi dự án bạn muốn xây dựng cần đến phần kiến thức đó). Lộ trình này được xây dựng dựa trên [lộ trình Fullstack của Repo này](https://github.com/nishant-Tiwari24/coding-resources).

Mỗi tuần bạn nên thử làm ít nhất một dự án (một ứng dụng đơn giản để áp dụng các nội dung bạn đã học trong tuần, gì cũng được). Mình sẽ để một danh sách gợi ý bên dưới.

### Định hướng cho chương trình học
Chương trình học của mình sẽ yêu cầu mọi người đào sâu về Backend hơn Frontend và không đi vào một lựa chọn cụ thể nào. Với Frontend bạn cũng sẽ tự chọn thứ bạn muốn học.

- Ví dụ: Ở mục Frontend, bạn muốn học Vue.js thì tự tìm các nội dung "cơ bản" mà bạn cần học.
- Ở Backend cũng không bắt bạn đi theo một lựa chọn cụ thể nào cả

Bọn mình sẽ tập trung vào hiểu cốt lõi của cả một ứng dụng. Ở Backend thì có những khái niệm như HTTP GET/POST hay Database, còn Frontend thì có HTML/CSS/JS (Còn lại Framework do bạn chọn).

Lập trình Web phát triển quá nhanh, hết frontend framework này đến cái khác, công cụ này đến công cụ khác và bạn sẽ rất dễ để bắt gặp các câu hỏi như "Mình nên học cái gì?". Bạn cần phải tự tìm thông tin thêm về thứ bạn muốn chọn.

Chương trình này không dạy bạn hết về Fullstack và bạn vẫn sẽ còn phải học rất nhiều để nâng cao khả năng của bản thân.

### Tuần 1: HTML, CSS, Layout (Flexbox, Grid)

#### Bạn sẽ học
HTML/CSS cơ bản và responsive design. Đồng thời, học cách thiết lập và sử dụng cơ bản các công cụ hỗ trợ cho quá trình lập trình như: VS Code, Chrome DevTools, Postman (cho API testing, bạn chưa cần dùng đến cái này trong quá trình học ban đầu).

#### Nguồn tài nguyên học

Nếu bạn muốn xem video thì xem [Khóa HTML/CSS cơ bản của F8 - Tiếng Việt](https://www.youtube.com/playlist?list=PL_-VfJajZj0U9nEXa4qyfB4U5ZIYCMPlz). Hoặc có thể học cả [HTML Foundations](https://www.theodinproject.com/paths/foundations/courses/foundations#html-foundations) và [CSS Foundations](https://www.theodinproject.com/paths/foundations/courses/foundations#css-foundations) của TheOdinProject. Bạn cũng sẽ được học thêm về: Flexbox, Grid (Layout).

Đọc thêm các nội dung khác liên quan đến HTML/CSS:

- [Giới thiệu về DOM](https://viblo.asia/p/gioi-thieu-ve-dom-WAyK8J2ElxX) - Tìm hiểu về DOM (Document Object Model). Sẽ có một chút phần code của JavaScript, bạn có thể bỏ qua và chỉ cần tập trung vào hiểu DOM là gì.
- [Guide to Writing Semantic HTML](https://cs.fyi/guide/writing-semantic-html) - Cách viết semantic HTML (Semantic HTML refers to the use of HTML markup to convey the meaning of the content on a web page, rather than just its appearance)
- [Don't click here](https://www.dont-click-here.com/)  

Sau đó bạn cũng có thể lựa chọn sử dụng CSS Framework để giúp việc trang trí Website của bạn được đơn giản hơn nhiều, dưới đây là một số CSS Framework được gợi ý:

- [Bootstrap](https://getbootstrap.com/)
- [TailwindCSS](https://tailwindcss.com/docs/installation/play-cdn)
- [Pure CSS](https://pure-css.github.io/start/) - Siêu tối giản

### Tuần 2: JavaScript cơ bản
#### Bạn sẽ học
JavaScript cơ bản

- Các nội dung cơ bản như: variables (biến), loops (vòng lặp), functions (hàm), và arrays (chuỗi).
- Tìm hiểu về các chức năng ES6 như let, const, và arrow functions.
- DOM manipulation

#### Nguồn tài nguyên học

Học từ đầu trong 30 ngày thông qua khóa [30-Days-Of-JavaScript](https://github.com/Asabeneh/30-Days-Of-JavaScript). Sau đó bạn có thể đọc thêm: [33 Concepts Every JavaScript Developer Should Know](https://github.com/leonardomso/33-js-concepts) (Nếu bạn mới học hoàn toàn thì có thể những kiến thức này sẽ khiến bạn thấy ngợp, bạn sẽ còn học lâu dài nên chỉ đọc tham khảo qua cũng được). Nếu bạn thích học thêm thì học khóa [JavaScript nâng cao](https://www.youtube.com/playlist?list=PL_-VfJajZj0U1MSx1IMu13oLJq2nM97ac) của F8.

#### Làm bài tập luyện tập
Có thể lên một số trang như Exercism để luyện tập lập trình. Có thể thử đọc [Tổng hợp bài tập JavaScript có code mẫu](https://quantrimang.com/hoc/bai-tap-javascript-co-giai-159572)

Luyện tập DOM Manipulation thông qua [Bài tập về DOM](https://javascript.uduer.com/bai-tap-ve-dom)

### Tuần 3: Backend (Phần 1)
Thường mình thấy trong các khóa học hoặc chương trình khác thì mọi người thường hay cho học Frontend trước. Chương trình này sẽ lựa chọn Backend để khởi đầu trước. Lý do là Backend cung cấp các kiến thức cốt lõi như cơ sở dữ liệu, hệ thống, thuật toán, mạng .v.v.. – những yếu tố quan trọng giúp bạn hiểu cách một ứng dụng web hoạt động từ bên trong.

Trích từ [một bình luận của một vozer khác](https://voz.vn/t/lo-trinh-tu-hoc-phat-trien-website-fullstack-fullstack-web-development.970731/post-33389959) trên Thread Fullstack của tôi (Thanks bác, lộ trình này sẽ học Backend trước rồi mới học Frontend):

> mình nghĩ nên bắt đầu từ BE trước, nắm vững các kiến thức cơ bản về DB, OOP, thuật toán, mạng, Linux,...
> rồi học liên quan đến setup, build web trên server qua Docker, VPS,...
> sau đấy mới move dần qua FE. Bắt đầu từ SSR để làm quen với HTML, CSS, JS sau đó chuyển qua CSR làm quen với các lib, framework như React, Vue, Angular

Vậy thì bạn cần học gì về Backend?  

#### Bạn sẽ học
- Kiến thức nền tảng về Internet:  
    - Cách Internet hoạt động, HTTP, DNS, hosting, trình duyệt, client-server.
    - 📖 [Fundamentals of Web apps](https://fullstackopen.com/en/part0/fundamentals_of_web_apps).
- JavaScript Runtime Environment & Web Server:  
    - 📖 [JavaScript runtime environment là gì?](https://topdev.vn/blog/javascript-runtime-environment-la-gi/)  
    - 📖 [Web Server là gì?](https://viblo.asia/p/web-server-la-gi-tim-hieu-ve-web-server-WR5JRv0rJGv)  
- Xây dựng HTTP Server từ đầu:  
    - 📖 [The HTTP server explained](https://scribe.rip/@gabriellamedas/the-http-server-explained-c41380307917).
- Lựa chọn ngôn ngữ Backend:  
    - Bạn có thể chọn JavaScript (Node.js), Ruby, Java, Go, Rust, v.v. (Từ tuần này bạn có thể bắt đầu học luôn hoặc để sang tuần sau và tuần này tập trung học những phần siu cơ bản đã được liệt kê ở đây). 
    - 📖 [Hướng dẫn bắt đầu lập trình từ con số 0](https://old.reddit.com/r/learnprogramming/comments/pxg54p/how_to_start_programming_from_zero/).
- Hệ thống kiểm soát phiên bản (Git & GitHub):  
    - 📺 [Từ gà tới pro Git và Github trong 20 phút](https://www.youtube.com/watch?v=1JuYQgpbrW0).
    - 📺 [Git and GitHub Crash Course](https://www.youtube.com/watch?v=RGOj5yH7evk).
- Thiết kế API cơ bản:  
    - 📖 [Learn API Design](https://github.com/dwyl/learn-api-design).

#### Nguồn tài nguyên học
- 📖 [Awesome Lập trình](https://daihocmo.github.io/awesome-lap-trinh/) - Tổng hợp tài liệu học lập trình và Khoa học Máy tính bằng tiếng Việt.
- Nếu bạn học Rust, tham khảo [Hướng dẫn cày Rust](https://daihocmo.github.io/awesome-lap-trinh/ngon-ngu/rust.html).

#### Đọc thêm
- [Commit Messages](https://www.theodinproject.com/lessons/foundations-commit-messages) - Học cách viết Commit Message mỗi khi thực hiện commit trong Git.
- [Problem Solving](https://www.theodinproject.com/lessons/foundations-problem-solving) - Giải quyết vấn đề trong lập trình.
- [Understanding Errors](https://www.theodinproject.com/lessons/foundations-understanding-errors) - Hiểu về lỗi trong lập trình (Bài viết này tập trung vào JS, nhưng đọc để hiểu về tư duy về lỗi lập trình khá hay)
- [Clean Code](https://www.theodinproject.com/lessons/foundations-clean-code) - Phần lớn thời gian lập trình được dành để đọc Code. Hướng dẫn viết Code dễ đọc.

### Tuần 4: Backend (Phần 2)

#### Bạn sẽ học
- 📖 [HTTP Basics](https://www.freecodecamp.org/news/what-is-http/) - Hiểu cách HTTP hoạt động.
- 📖 [Request-Response Cycle](https://davisgitonga.dev/blog/request-response-cycle) - Hiểu vòng đời của một request.
- 📖 [REST APIs](https://viblo.asia/p/restful-api-la-gi-1Je5EDJ4lnL) - Cách thiết kế API RESTful.

#### Lựa chọn định hướng
- Nếu bạn chọn Fullstack JavaScript, học:  
    - 📖 [Full Stack JavaScript - The Odin Project](https://www.theodinproject.com/paths/full-stack-javascript).
    - 📺 [NodeJS & ExpressJS](https://www.youtube.com/playlist?list=PL_-VfJajZj0VatBpaXkEHK_UPHL7dW6I3) (Khóa học Tiếng Việt của F8).
- Ruby on Rails - Ruby on Rails là một framework mạnh mẽ giúp tăng tốc phát triển ứng dụng web:
    - 
- Java + Spring - Java Spring là một framework phổ biến để xây dựng ứng dụng doanh nghiệp:
    - [Chia sẻ lộ trình tự học đến khi có OFFER FRESHER (Java) đầu tiên](https://voz.vn/t/chia-se-lo-tinh-tu-hoc-%C4%91en-khi-co-offer-fresher-java-%C4%91au-tien.757819/)
- Rust - Rust là một ngôn ngữ lập trình hệ thống hiện đại, tập trung vào hiệu suất và an toàn bộ nhớ.
    - [Hướng dẫn cày Rust](https://daihocmo.github.io/awesome-lap-trinh/ngon-ngu/rust.html)
    - [Zero To Production In Rust - An introduction to backend development](https://www.zero2prod.com/assets/sample_zero2prod.pdf) - Bạn cũng có thể đọc bản Sample đầy đủ của cả sách trên [Blog của tác giả](https://lpalmieri.com/posts/2020-05-24-zero-to-production-0-foreword/)

#### Đọc thêm
- 📖 [Request-Response Cycle Through A Story](https://scribe.rip/@castonboyd/request-response-cycle-through-a-story-e552a7afff41).
- 📖 [CRUD là gì? So sánh sự khác biệt giữa CRUD và REST](https://vietnix.vn/crud-la-gi/).

### Tuần 5: NoSQL Databases (MongoDB)

#### Bạn sẽ học
- 📖 [NoSQL concepts](https://viblo.asia/p/gioi-thieu-ve-nosql-database-djeZ1a9jZWz).
- 📖 [CRUD với MongoDB](https://viblo.asia/p/crud-la-gi-lap-trinh-website-crud-crud-database-Ljy5VyLzlra).
- 📖 [Database Schema Design](https://viblo.asia/p/lam-the-nao-de-thiet-ke-mot-co-so-du-lieu-phan-1-rYvGwavgKVw).
- 📖 [Indexing trong Database](https://viblo.asia/p/index-trong-database-la-gi-tai-sao-can-index-database-Az45bYDzlxY).

#### Nguồn tài nguyên học
- 📖 [A Comprehensive NoSQL Tutorial Using MongoDB](https://www.datacamp.com/tutorial/nosql-tutorial).
- 📺 [Learn About NoSQL Databases in This 3-hour Course](https://www.freecodecamp.org/news/learn-nosql-in-3-hours/).

### Tuần 6: SQL cơ bản

#### Bạn sẽ học
- 📖 Học cú pháp SQL từ [SQLBolt](https://sqlbolt.com/).
- 📖 Thực hiện CRUD operations với MySQL/PostgreSQL.

#### Nguồn tài nguyên học
- 📖 [Fullstack Vỡ Lòng (8 bài viết về MySQL)](https://viblo.asia/s/fullstack-vo-long-5OXLA0AvJGr).
- 📖 [CRUD Node.js với MySQL](https://viblo.asia/p/crud-nodejs-voi-mysql-RnB5pbPGZPG).

### Tuần 7: ORMs (Sequelize/Mongoose)

#### Bạn sẽ học
- 📖 [Object-Relational Mapping (ORM)](https://viblo.asia/p/object-relational-mapping-djeZ1PQ3KWz).
- 📖 [Sequelize cho SQL](https://viblo.asia/p/tim-hieu-va-su-dung-sequelize-va-sequelize-cli-jvElaRY65kw).
- 📖 [Mongoose cho MongoDB](https://www.mongodb.com/developer/languages/javascript/getting-started-with-mongodb-and-mongoose/).
- 📖 [Mô hình quan hệ - thực thể (ER Model)](https://viblo.asia/p/mo-hinh-quan-he-thuc-the-entity-relationship-model-oOVlYEenl8W).

#### Nguồn tài nguyên học
- 📖 [Introduction to Mongoose for MongoDB](https://www.freecodecamp.org/news/introduction-to-mongoose-for-mongodb-d2a7aa593c57/).


### Tuần 8: Lựa chọn Framework Frontend

#### Bạn sẽ học
- **Tìm hiểu về các Framework phổ biến**: React, Vue.js, Svelte, Angular.
- **Đánh giá ưu và nhược điểm** của từng Framework.
- **Xác định mục tiêu cá nhân** và **nhu cầu thị trường** để chọn Framework phù hợp.

#### Nguồn tài nguyên học
- [Lộ trình học Front-end toàn diện A-Z khoảng 10-12 tháng](https://itviec.com/blog/lo-trinh-hoc-front-end/)

#### Đọc thêm:
Ở đây mình chọn React để thêm tài nguyên vì cơ bản ai cũng học =))

- [React - Cấu trúc thư mục dự án và đặt tên Component](https://viblo.asia/p/react-cau-truc-thu-muc-du-an-va-dat-ten-component-aWj53GMY56m)
- [Một vài mindset khi làm việc với React](https://viblo.asia/p/mot-vai-mindset-khi-lam-viec-voi-react-L4x5xkoalBM)
- [ReactJS: Một vài lỗi thường gặp khi làm việc với React](https://viblo.asia/p/reactjs-mot-vai-loi-thuong-gap-khi-lam-viec-voi-react-djeZ1n4JlWz)
- [Nguyên Lý SOLID: Bí Quyết Viết Code Hiệu Quả Trong React và React Native](https://viblo.asia/p/nguyen-ly-solid-bi-quyet-viet-code-hieu-qua-trong-react-va-react-native-zOQJw5vyVMP)

### Tuần 9: Học Framework đã chọn (Tiếp tục)
Sau khi đã đọc và trải nghiệm đôi chút, đồng thời đưa ra quyết định lựa chọn Framework mà mình muốn học, đồng thời đã học cơ bản về nó rồi thì bắt đầu tuần thứ 9!

#### Bạn sẽ học
- **Cài đặt môi trường phát triển** cho Framework.
- **Cấu trúc dự án** và **các khái niệm cơ bản**: components, state management, routing, v.v.
- **Xây dựng các ứng dụng nhỏ** để thực hành.

#### Nguồn tài nguyên học
- **React**: [Học thông qua trang chủ của React](https://react.dev/learn)
- **Vue.js**: [Hướng dẫn chính thức của Vue.js](https://vuejs.org/guide/introduction.html)
- **Svelte**: [Tutorial của Svelte](https://svelte.dev/tutorial)
- **Angular**: [Tour of Heroes - Angular](https://angular.io/tutorial)

### Tuần 10: TypeScript cơ bản

#### Bạn sẽ học
- Học [TypeScript](https://viblo.asia/p/tim-hieu-typescript-va-kien-thuc-co-ban-PmeRQpnyGoB) syntax và [static typing](https://stackoverflow.com/a/1517670): **Cú pháp TypeScript** và **typing cơ bản**.
- **Tích hợp TypeScript** vào Framework đã chọn.
- Tìm hiểu về [type declarations](https://www.typescriptlang.org/docs/handbook/2/type-declarations.html) cho APIs và models.

#### Nguồn tài nguyên học

- [The TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
- [Strong vs Weak, Static vs Dynamic typing là cái khỉ gì?](https://viblo.asia/p/strong-vs-weak-static-vs-dynamic-typing-la-cai-khi-gi-JQVkVzZokyd)
- [Adding TypeScript](https://create-react-app.dev/docs/adding-typescript/)

### Tuần 11: Next.js cơ bản
Phần này đang sửa... (vì mình đang học)

#### Bạn sẽ học
- Học [server-side rendering (SSR) và static site generation (SSG)](https://viblo.asia/p/so-sanh-server-side-rendering-vs-client-side-rendering-vs-pre-rendering-vs-dynamic-rendering-LzD5dWoOljY) - Hoặc đọc [Thread trên StackOverflow về chủ đề này](https://stackoverflow.com/questions/75457090/static-site-generation-ssg-vs-server-side-rendering-vs-client-side-rendering).
- Xây dựng ứng dụng thân thiện với SEO (SEO-friendly).
- **State management**: Redux, Vuex, Svelte Store, Angular Services.
- **Công cụ hỗ trợ**: DevTools, linters, formatters.
- **Tích hợp với API**: fetch, axios.

#### Nguồn tài nguyên học
- [Redux - A Predictable State Container for JS Apps](https://redux.js.org/)
- [Vuex - State Management Pattern + Library for Vue.js Applications](https://vuex.vuejs.org/)
- [Svelte Store](https://svelte.dev/tutorial/writable-stores)
- [Angular Services](https://angular.io/guide/architecture-services)

### Tuần 12: Monorepos và Turborepo

#### Bạn sẽ học
- Học [monorepos]() và tìm hiểu cách sắp xếp nhiều dự án khác nhau (?).
- Sử dụng Turborepo để tối ưu performance.

#### Nguồn tài nguyên học
- [Beginner's guide to monorepos and turborepo](https://dev.to/sammaji/beginners-guide-to-monorepos-and-turborepo-590c)
- [Modern Monorepo with Turborepo. Bắt đầu với một project cơ bản từ Turborepo](https://viblo.asia/p/modern-monorepo-with-turborepo-bat-dau-voi-mot-project-co-ban-tu-turborepo-gwd43ogA4X9)

### Tuần 13: Websockets & RTC cơ bản

#### Bạn sẽ học
- Học [Giao tiếp thời gian thực với Websockets](https://viblo.asia/p/websocket-chia-khoa-mo-ra-the-gioi-giao-tiep-thoi-gian-thuc-x7Z4DO9oVnX).
- Học RTC cho video/audio communication.

#### Nguồn tài nguyên học
- [Mastering Real-Time Communication: A Comprehensive WebSocket Tutorial](https://scribe.rip/@sergey.dudik/mastering-real-time-communication-a-comprehensive-websocket-tutorial-0f6cf384d1e8)
- [How To Develop A WebRTC-Based Audio/Video Communication With No Code](https://jason-wills343.medium.com/how-to-develop-a-webrtc-based-audio-video-communication-with-no-code-a7ad8177121)
- [WebRTC vs WebSocket: If WebRTC can do Video, Audio, and Data, why do I need WebSocket?](https://stackoverflow.com/questions/18799364/webrtc-vs-websocket-if-webrtc-can-do-video-audio-and-data-why-do-i-need-webs)

### Tuần 14: Testing cơ bản

#### Bạn sẽ học
- Học unit và integration testing:
    - [Sự khác nhau giữa Unit, Integration và Functional Testing](https://viblo.asia/p/su-khac-nhau-giua-unit-integration-va-functional-testing-YmjeoLZrkqa)
    - [What's the difference between unit tests and integration tests?](https://stackoverflow.com/a/5357837)
- Sử dụng Jest và React Testing Library (Nếu bạn chọn học React ở trên, cá nhân mình không học nên sẽ bổ sung phần này sau)
- Test APIs và các frontend components.
    - [Sơ lược về API Testing](https://anhtester.com/blog/blog/so-luoc-ve-api-testing)
    - [Học cách test API đơn giản và dễ dàng trong 10 phút](https://viblo.asia/p/hoc-cach-test-api-don-gian-va-de-dang-trong-10-phut-Do7546xBZM6)

#### Nguồn tài nguyên học
- [API Testing With Postman](https://www.youtube.com/playlist?list=PLgcMOggxCIP1X0wyYsqzdAgYQJnsJAOKU) - Khóa này bằng Tiếng Việt.
- [Postman Beginner's Course - API Testing](https://www.youtube.com/watch?v=VywxIQ2ZXw4)

### Tuần 15: Authentication & JWT

#### Bạn sẽ học
- [Tìm hiểu về khái niệm xác thực người dùng Authentication](https://viblo.asia/p/tim-hieu-ve-khai-niem-xac-thuc-nguoi-dung-authentication-ByEZkrM4KQ0) và [phân biệt sự khác nhau giữa Authentication và Authorization](https://viblo.asia/p/phan-biet-su-khac-nhau-giua-authentication-va-authorization-Eb85oad4Z2G)
- Sử dụng JWT (JSON Web Token) và cookies cho session management:
    - [JWT và Session một số thông tin bạn nên biết](https://www.facebook.com/groups/devoiminhdidauthe/posts/25529417370035293/)
    - [JWT – JSON Web Tokens và Session Cookies trong việc Authentication](https://viblo.asia/p/jwt-json-web-tokens-va-session-cookies-trong-viec-authentication-XL6lA9QDlek)
    - [JSON Web Token hay Session Cookies, đâu mới là chân ái ?](https://viblo.asia/p/json-web-token-hay-session-cookies-dau-moi-la-chan-ai-Qbq5Q0oJlD8)
    - [Lưu JWT trong cookie hay local storage?](https://haiconmeo.info/blog/code-blog/jwt-cookie)

#### Nguồn tài nguyên học
- [Session, cookie, CORS, JWT, SSO](https://www.youtube.com/playlist?list=PL_-VfJajZj0VaEt6Q1Z_CSg_Ci9aP9oQ1) - Danh sách phát của F8

### Tuần 16: Tối ưu cơ sở dữ liệu

#### Bạn sẽ học
- Tìm hiểu về kĩ thuật tối ưu cơ sở dữ liệu (database optimization techniques). Ví dụ như indexing, query optimization .etc.

#### Nguồn tài nguyên học
- [Tự học SQL: 10 Kỹ thuật tối ưu hóa lệnh truy vấn hiệu quả](https://datapot.vn/tu-hoc-sql-10-ky-thuat-toi-uu-hoa-lenh-truy-van-sql/?srsltid=AfmBOor8LgzTt4DmuIDGQ_TJ2ABDFTBk-5RZZ8q1QlFJHEHGBYsGsLMR)
- [11 Database Optimization Techniques](https://danielfoo.medium.com/11-database-optimization-techniques-97fdbed1b627)

### Tuần 17: Khái niệm Backend nâng cao

#### Bạn sẽ học
- Học thêm về [asynchronous programming](https://fullstack.edu.vn/blog/co-ban-tong-quan-lap-trinh-synchronous-va-asynchronous.html) và [error handling](https://viblo.asia/p/javascript-error-handling-vyDZO1N95wj) (Lưu ý cho ai chưa biết thì hai khái niệm này không chỉ giới hạn trong JavaScript).
- Học middleware chaining - Theo mình tìm hiểu thì khái niệm này chỉ giới hạn trong Express.js. Đọc bài ['Express Middleware' is just a fancy way of chaining a bunch of functions.](https://dev.to/getd/express-middleware-is-just-a-fancy-way-of-chaining-a-bunch-of-functions-explained-in-3-mins-43jf)
- [Các khái niệm Backend "cao cấp hơn"](https://medium.com/@zalewski/exploring-advanced-backend-concepts-databases-software-design-and-architecture-90d76d2a82c5):

#### Cập nhật dự án của bạn
- Viết API và có thêm những tính năng nâng cao như rate limiting và complex queries:
    - [API Rate Limiting là gì và một số thuật toán hay dùng](https://viblo.asia/p/api-rate-limiting-la-gi-va-mot-so-thuat-toan-hay-dung-bJzKmPyr59N)
    - [What does it mean to be able to write "complex" SQL queries?](https://www.reddit.com/r/datascience/comments/z6mot6/what_does_it_mean_to_be_able_to_write_complex_sql/)


#### Nguồn tài nguyên học

### Tuần 18: Ref, Populate, và API Design

Đang trong quá trình thêm

### Tuần 19: Các chức năng Frontend nâng cao

#### Bạn sẽ học
- Học dynamic form handling, animations, và accessibility features trong React.
- Tìm hiểu về Framer Motion cho animations.

### Tuần 20: Project Planning

#### Bạn sẽ học
- Lên kế hoạch cho một [capstone project](https://domyessay.com/blog/capstone-project-outline) (Dự án tốt nghiệp)
- Định nghĩa các tính năng, Tạo high-level (HLD) và low-level designs (LLD)

#### Ghi chú
Đây sẽ là một dự án (tương đối) lớn. Trước khi bắt tay vào làm dự án này, bạn nên hoàn thành một số các dự án cỡ nhỏ và vừa. Bạn có thể xem [Những DỰ ÁN CÁ NHÂN nên làm khi TỰ HỌC lập trình](https://www.youtube.com/watch?v=XIcWaewPAjQ) của ông Dev để tìm hiểu thêm.


### Tuần 21: Capstone Backend Development
Sau khoảng một tuần lập kế hoạch và học thêm một số các khái niệm liên quan đến HLD và LLD, bây giờ sẽ là lúc bắt đầu.

#### Bạn sẽ làm
- Xây dựng phần Backend cho **dự án tốt nghiệp** của bạn.
- Implement CRUD APIs, authentication, và error handling.

### Tuần 22: Capstone Frontend Development

#### Bạn sẽ làm
- Xây dựng Frontend cho **dự án tốt nghiệp** của bạn.
- Có thể sử dụng React/Next.js với Tailwind CSS. 


### Tuần 23: Real-Time Features trong Capstone

#### Bạn sẽ học
- Thêm những tính năng real-time sử dụng Websockets hoặc RTC.
- Implement live chat hoặc real-time notifications

### Tuần 24: Testing và Deployment

#### Bạn sẽ học
- Test ứng dụng
- Deploy lên một nền tảng cloud (e.g., Vercel, Heroku)

#### Nguồn tài nguyên học

### Tuần 25: Linting và Performance Optimization

#### Bạn sẽ học
- Thiết lập các công cụ [Linting](https://toidicodedao.com/2018/05/15/viet-code-tot-hon-voi-linter-eslint-visual-studio-code/) (e.g., ESLint, Prettier).
- Tối ưu performance cho cả Backend và Frontend.
- Học về [caching strategies](https://viblo.asia/p/chien-luoc-caching-caching-strategies-zXRJ8jPOVGq)

#### Đọc thêm
- [Cache Strategies](https://medium.com/@mmoshikoo/cache-strategies-996e91c80303)
- [9 Caching Strategies for System Design Interviews](https://dev.to/somadevtoo/9-caching-strategies-for-system-design-interviews-369g)

### Tuần 26: Final Enhancements & Portfolio
Thêm thắt chỉnh sửa đôi chút cho dự án tốt nghiệp

#### Đặc biệt chút
- Thêm dự án vào trang Portfolio của bản thân.
- Chuẩn bị đi phỏng vấn với dự án đó, và một resume nữa. 
- Tạo một portfolio cá nhân sử dụng Next.js.
- Showcase tất cả 10 dự án trong portfolio của bạn. 

### Sau khi hoàn thành
Sau khi bạn hoàn thành xong 26 tuần này, sẽ còn rất nhiều thứ nữa bạn (cần) nên học để có thể cải thiện hơn nữa sản phẩm của bạn.

## Danh sách dự án gợi ý

- [9 project nhỏ mà bạn có thể code để luyện tập kĩ năng lập trình](https://toidicodedao.com/2018/09/04/project-luyen-tap-ki-nang-lap-trinh/)
- [Những DỰ ÁN CÁ NHÂN nên làm khi TỰ HỌC lập trình](https://www.youtube.com/watch?v=XIcWaewPAjQ)