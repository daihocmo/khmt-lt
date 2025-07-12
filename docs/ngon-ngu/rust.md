# Hướng dẫn tự học Rust

## 1. Cơ bản về Rust

### 1.1. Tài liệu lý thuyết
- **[The Rust Programming Language Book](https://doc.rust-lang.org/book/)**: Cuốn sách chính thức về Rust, lý tưởng cho người mới bắt đầu. Đọc kỹ trong tuần đầu tiên, chú ý các khái niệm về ownership, borrowing, và lifetimes. Quay lại các chương chưa rõ khi cần.
- **[Rust by Example](https://doc.rust-lang.org/stable/rust-by-example/)**: Bộ sưu tập các ví dụ thực tế về cú pháp và cách sử dụng Rust. Học song song với Rust Book để củng cố kiến thức.
- **[Rust Cheat Sheet](https://cheats.rs/)**: Tài liệu tham khảo nhanh về cú pháp và các mẫu code phổ biến. Sử dụng khi cần tra cứu nhanh trong quá trình học hoặc lập trình.

### 1.2. Bài tập thực hành
- **[Rustlings](https://github.com/rust-lang/rustlings)**: Bộ bài tập tương tác giúp làm quen với cú pháp và các khái niệm cơ bản của Rust. Hoàn thành toàn bộ (hoặc ít nhất cố gắng làm hết, kể cả các bài khó).
- **[Rust by Practice](https://practice.rs/)**: Các bài tập thực hành có giải thích chi tiết, phù hợp để củng cố kiến thức cơ bản.

**Lộ trình đề xuất**: Bắt đầu với Rust Book và Rust by Example để nắm lý thuyết, sau đó làm bài tập trong Rustlings và Rust by Practice để áp dụng kiến thức.

## 2. Các dự án thực hành cơ bản

Thực hiện các dự án sau để áp dụng kiến thức cơ bản và hiểu cách tổ chức code trong Rust.

- **[PNGme](https://jrdngr.github.io/pngme_book/)**: Dự án trung cấp xây dựng trình mã hóa/giải mã file PNG. Giúp bạn làm quen với xử lý file, cấu trúc dữ liệu, và quản lý lỗi.
- **[Triangle From Scratch](https://rust-tutorials.github.io/triangle-from-scratch/)**: Dự án vẽ hình tam giác sử dụng Win32 API mà không cần thư viện bên ngoài. Tốt để hiểu về lập trình hệ thống cấp thấp với Rust.
- **[Build Your Own JIRA with Rust](https://github.com/LukeMathWalker/build-your-own-jira-with-rust/)**: Xây dựng một phiên bản đơn giản của JIRA, tập trung vào phát triển theo hướng kiểm thử (TDD) và kiến trúc phần mềm.

**Lộ trình đề xuất**: Hoàn thành ít nhất một dự án sau khi nắm vững cơ bản. PNGme phù hợp cho người muốn học về xử lý file, trong khi Triangle From Scratch dành cho những ai quan tâm đến lập trình hệ thống.

## 3. Các chủ đề trung cấp

### 3.1. Ownership và Lifetimes
- **[Common Rust Lifetime Misconceptions](https://github.com/pretzelhammer/rust-blog/blob/master/posts/common-rust-lifetime-misconceptions.md)**: Bài viết giải thích chi tiết các hiểu lầm phổ biến về lifetimes trong Rust. Đọc sau khi đã quen với ownership.
- **[Rustonomicon: Ownership](https://doc.rust-lang.org/nomicon/ownership.html)**: Tài liệu nâng cao về ownership và borrowing, phù hợp để hiểu sâu hơn về cách Rust quản lý bộ nhớ.
- **[Rustowl](https://github.com/cordx56/rustowl)**: Công cụ trực quan hóa ownership và lifetimes, giúp hình dung các khái niệm trừu tượng.

**Lộ trình đề xuất**: Đọc các tài liệu trên sau khi hoàn thành Rust Book. Sử dụng Rustowl để kiểm tra hiểu biết của bạn về lifetimes.

### 3.2. Xử lý lỗi

- **[Parse, Don’t Validate](https://lexi-lambda.github.io/blog/2019/11/05/parse-don-t-validate/)**: Bài viết về cách thiết kế mã Rust để giảm thiểu kiểm tra thủ công và tận dụng hệ thống kiểu.
- **[Modular Errors](https://sabrinajewson.org/blog/errors)**: Hướng dẫn xây dựng hệ thống lỗi có tổ chức, dễ bảo trì trong Rust.
- **[Railway Oriented Programming](https://fsharpforfunandprofit.com/posts/recipe-part2/)**: Giới thiệu cách xử lý lỗi theo phong cách lập trình hướng đường ray, có thể áp dụng trong Rust.

**Lộ trình đề xuất**: Đọc các bài viết trên và thử áp dụng trong các dự án nhỏ để hiểu cách quản lý lỗi hiệu quả.

### 3.3. Design Patterns
- **[Rust Design Patterns](https://rust-unofficial.github.io/patterns/)**: Danh mục các mẫu thiết kế phổ biến trong Rust, giúp viết code dễ bảo trì và tái sử dụng.
- **[Effective Rust](https://www.lurklurk.org/effective-rust/)**: Hướng dẫn viết code Rust theo cách tối ưu, tập trung vào tính hiệu quả và idiomatic.

**Lộ trình đề xuất**: Đọc các tài liệu này sau khi hoàn thành ít nhất một dự án cơ bản. Áp dụng các mẫu thiết kế vào dự án tiếp theo để cải thiện chất lượng code.

## 4. Các chủ đề nâng cao

### 4.1. Lập trình bất đồng bộ (Async)
- **[Rust Async Book](https://rust-lang.github.io/async-book/)**: Tài liệu chính thức về lập trình bất đồng bộ trong Rust. Đọc để hiểu cơ chế async/await.
- **[Tokio Tutorial](https://tokio.rs/tokio/tutorial)**: Hướng dẫn sử dụng Tokio, một runtime phổ biến cho lập trình async trong Rust. Học sau khi nắm vững Async Book.

**Lộ trình đề xuất**: Chỉ bắt đầu học async sau khi đã thành thạo các khái niệm cơ bản và lifetimes. Thử viết một ứng dụng mạng đơn giản với Tokio.

### 4.2. Lập trình hệ thống
- **[Writing a File System from Scratch in Rust](https://blog.carlosgaldino.com/writing-a-file-system-from-scratch-in-rust.html)**: Hướng dẫn xây dựng hệ thống file đơn giản, tập trung vào lập trình cấp thấp.
- **[Writing an OS in Rust](https://os.phil-opp.com/)**: Hướng dẫn chi tiết xây dựng một hệ điều hành bằng Rust. Phù hợp cho người muốn học sâu về hệ thống.
- **[The Theseus OS Book](https://www.theseus-os.com/Theseus/book/)**: Tài liệu về Theseus, một hệ điều hành thử nghiệm viết bằng Rust.
- **[intermezzOS](http://intermezzos.github.io/book/second-edition/)**: Dự án xây dựng hệ điều hành đơn giản, tập trung vào giáo dục.

**Lộ trình đề xuất**: Chọn một trong các dự án trên để thực hành sau khi đã quen với lập trình hệ thống cơ bản (như Triangle From Scratch).

### 4.3. Cơ sở dữ liệu và hệ thống phân tán
- **[Async Raft](https://async-raft.github.io/async-raft/)**: Tài liệu về giao thức Raft trong Rust, tập trung vào hệ thống phân tán bất đồng bộ.
- **[TiKV Training Program](https://github.com/pingcap/talent-plan)**: Khóa học về xây dựng hệ thống phân tán, bao gồm Raft và giao thức giao dịch Percolator.
- **[CS186: Introduction to Database Systems](https://cs186berkeley.net/)**: Khóa học về cơ sở dữ liệu, cần thiết để hiểu cách tích hợp Rust với cơ sở dữ liệu.

**Lộ trình đề xuất**: Học sau khi đã nắm vững async và lập trình hệ thống. Thử áp dụng kiến thức vào một dự án như TiKV.

### 4.4. Biên dịch và trình thông dịch
- **[Crafting Interpreters](https://craftinginterpreters.com/)**: Sách hướng dẫn xây dựng trình thông dịch. Kết hợp với **[Rust Ports of Crafting Interpreters](https://www.youtube.com/playlist?list=PLib6-zlkjfXluRjBgK8grQH2IUSZjn-YN)** để học cách triển khai bằng Rust.
- **[Writing Interpreters in Rust: A Guide](https://rust-hosted-langs.github.io/book/introduction.html)**: Hướng dẫn chi tiết về xây dựng trình thông dịch trong Rust.
- **[Make a Lisp](https://github.com/kanaka/mal)**: Dự án xây dựng trình thông dịch Lisp bằng Rust.
- **[Brainfuck Interpreter in Rust](https://rtoch.com/posts/brainfuck-interpreter-implementation-part-1/)**: Dự án đơn giản để làm quen với xây dựng trình thông dịch.

**Lộ trình đề xuất**: Bắt đầu với Crafting Interpreters và thử triển khai một trình thông dịch nhỏ như Brainfuck hoặc Lisp.

## 5. Kiến thức nền tảng về Khoa học Máy tính

Để sử dụng Rust hiệu quả trong các dự án phức tạp, bạn cần nắm vững các khái niệm về khoa học máy tính.

### Toán rời rạc
- **[Discrete Mathematics: An Open Introduction](http://discrete.openmathbooks.org/dmoi3/dmoi.html)**: Sách giáo khoa miễn phí về toán rời rạc.
- **[Trefor Bazett’s Discrete Math Playlist](https://www.youtube.com/watch?v=rdXw7Ps9vxc&list=PLHXZ9OQGMqxersk8fUxiUMSIx0DBqsKZS)**: Video bài giảng dễ hiểu về toán rời rạc.
- **[Discrete Math Study Guide](https://github.com/jongwoojeff/DiscreteMathematics/wiki)**: Tài liệu tóm tắt ngắn gọn các khái niệm quan trọng.

**Lộ trình đề xuất**: Học song song với các dự án Rust để hiểu các khái niệm như cấu trúc dữ liệu và thuật toán.

### Thuật toán
- **[Algorithm Cookbook in Rust](https://github.com/EbTech/rust-algorithms)**: Bộ sưu tập các thuật toán được triển khai bằng Rust.
- **[Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/)**: Hướng dẫn xây dựng danh sách liên kết trong Rust, giúp hiểu sâu về quản lý bộ nhớ.
- **[Rust Gym](https://github.com/warycat/rustgym)**: Kho lưu trữ code giải các bài tập thuật toán từ LeetCode, Advent of Code, v.v.
- **[Project Euler Rust](https://github.com/gifnksm/ProjectEulerRust)**: Các bài toán từ Project Euler được giải bằng Rust.

**Lộ trình đề xuất**: Học lý thuyết thuật toán trước, sau đó giải bài tập trên Rust Gym hoặc Project Euler.

### Mạng máy tính
- **[Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/)**: Sách giáo khoa về mạng máy tính.
- **[Beej’s Guide to Network Programming](https://beej.us/guide/bgnet/)**: Hướng dẫn thực hành về lập trình mạng.
- **[Building a DNS Server in Rust](https://github.com/EmilHernvall/dnsguide)**: Dự án xây dựng máy chủ DNS bằng Rust.

**Lộ trình đề xuất**: Đọc sách và làm dự án DNS để áp dụng kiến thức mạng.

## 6. Tài nguyên tham khảo

### 6.1. Tài liệu chính thức
- **[Rust Official Learn Page](https://www.rust-lang.org/learn)**: Tổng hợp tài liệu chính thức, bao gồm Rust Book, Cargo Book, và Rustdoc.
- **[Rust Standard Library](https://doc.rust-lang.org/std)**: Tài liệu tham khảo về thư viện chuẩn của Rust.
- **[Rust API Guidelines](https://rust-lang.github.io/api-guidelines/)**: Hướng dẫn viết API idiomatic trong Rust.

### 6.2. Công cụ và tài nguyên bổ trợ
- **[Awesome Rust](https://github.com/rust-unofficial/awesome-rust)**: Danh sách các crate và công cụ hữu ích cho lập trình Rust.
- **[The Little Book of Rust Macros](https://veykril.github.io/tlborm)**: Hướng dẫn chi tiết về macro trong Rust.
- **[Rust FFI Omnibus](https://jakegoulding.com/rust-ffi-omnibus)**: Hướng dẫn tích hợp Rust với các ngôn ngữ khác.
- **[Rust Quiz](https://dtolnay.github.io/rust-quiz/)**: Các câu hỏi kiểm tra kiến thức Rust, từ cơ bản đến nâng cao.

### 6.3. Blog và cộng đồng
- **[Read Rust](https://readrust.net/)**: Bộ sưu tập bài viết và tài nguyên về Rust.
- **[This Week in Rust](https://this-week-in-rust.org/)**: Bản tin hàng tuần về cập nhật Rust.
- **[Possible Rust](https://www.possiblerust.com/)**: Blog dành cho lập trình viên Rust trung cấp, tập trung vào các mẫu thiết kế thực tế.

## 7. Quản lý dự án và phát triển mã nguồn mở

- **[Guide on Writing Documentation for a Rust Crate](https://blog.guillaume-gomez.fr/articles/2020-03-12+Guide+on+how+to+write+documentation+for+a+Rust+crate)**: Hướng dẫn viết tài liệu cho crate Rust.
- **[TP 101: Introduction to Open Source Software](https://github.com/pingcap/talent-plan/blob/master/courses/tp101-intro-to-oss.md)**: Giới thiệu về phát triển mã nguồn mở.
- **[TP 102: How to Use Git and GitHub](https://github.com/pingcap/talent-plan/blob/master/courses/tp102-how-to-use-git-github.md)**: Hướng dẫn sử dụng Git và GitHub cho dự án Rust.
- **[Keeping README Code Examples Up-to-Date](https://blog.guillaume-gomez.fr/articles/2019-04-13+Keeping+Rust+projects%27+README.md+code+examples+up-to-date)**: Mẹo giữ tài liệu dự án luôn cập nhật.

**Lộ trình đề xuất**: Học các kỹ năng này khi bắt đầu đóng góp vào các dự án mã nguồn mở hoặc phát triển crate của riêng bạn.