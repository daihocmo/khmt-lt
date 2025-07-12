# Lập trình Backend thì cần những gì?

Trích từ [Ask HN: What are must-know concepts for back end development?](https://news.ycombinator.com/item?id=18961793)

Để xây dựng những hệ thống backend mạnh mẽ và có khả năng mở rộng lớn, bạn cần nắm vững cả các thành phần kỹ thuật và các nguyên lý khái niệm. Dưới đây là danh sách chọn lọc các chủ đề thiết yếu dành cho lập trình viên backend, với trọng tâm mạnh mẽ vào **bảo mật** như một tư duy nền tảng.

### Công nghệ cốt lõi

Hiểu rõ các công nghệ sau là điều tối quan trọng để xây dựng hệ thống backend có khả năng mở rộng:

* **Load Balancers**: Phân phối lưu lượng truy cập đến nhiều máy chủ để đảm bảo hiệu suất và độ tin cậy.
* **Web Servers**: Xử lý các request HTTP và trả về response (ví dụ: Nginx, Apache).
* **Caching Systems**: Tăng hiệu suất với các công cụ như Redis hoặc Memcached.
* **Databases**:
  * Quan hệ (ví dụ: PostgreSQL, MySQL)
  * Phi quan hệ/Dạng tài liệu (ví dụ: MongoDB)
* **Search Datastores**: Hỗ trợ tìm kiếm hiệu quả với Elasticsearch hoặc Solr.
* **Message Processors**: Xử lý hệ thống theo sự kiện với các công cụ như Kafka.
* **Task Queues**: Quản lý các tác vụ bất đồng bộ với thư viện như Celery hoặc RabbitMQ.
* **Periodic Jobs**: Lên lịch chạy các tác vụ định kỳ bằng cron hoặc công cụ tương tự.

### Bảo mật là nền tảng

Một tư duy đặt bảo mật lên hàng đầu là điều không thể thương lượng trong phát triển backend. Nếu thiếu bảo mật, ngay cả hệ thống tiên tiến nhất cũng dễ bị tấn công. Một số yếu tố bảo mật then chốt bao gồm:

* **Secure Design**: Thiết kế bảo mật ngay từ đầu; việc bổ sung sau này thường tốn kém và kém hiệu quả.
* **Principle of Least Privilege**: Hạn chế quyền truy cập của người dùng, ứng dụng và dịch vụ (ví dụ: sử dụng kiểm soát truy cập dựa trên vai trò trong PostgreSQL: [https://www.postgresql.org/docs/9.0/user-manag.html](https://www.postgresql.org/docs/9.0/user-manag.html)).
* **OWASP Top 10 và xa hơn**: Hiểu rõ các lỗ hổng phổ biến (ví dụ: XSS, CSRF) và xem xét kỹ logic nghiệp vụ để tránh rò rỉ dữ liệu.
* **Secure Data Handling**: Lưu mật khẩu an toàn (ví dụ: sử dụng bcrypt), không lộ dữ liệu nhạy cảm cho client, và không để lộ secrets trong version control.
* **Availability (CIA Triad)**: Đảm bảo hệ thống luôn sẵn sàng thông qua kế hoạch khôi phục sau thảm họa, dự phòng và chiến lược high-availability.
* **DDoS Mitigation**: Chuẩn bị cho các tình huống xấu nhất và giới hạn mức độ thiệt hại mà không ảnh hưởng đến năng suất.
* **Stateless vs. Stateful Architecture**: Hiểu được trade-offs khi dùng JWTs, session cookies và các cơ chế liên quan.

### Các khái niệm then chốt

Để nâng cao chuyên môn backend, hãy tập trung vào các lĩnh vực sau:

1. **HTTP và REST**: Làm chủ thiết kế RESTful API và giao thức HTTP.
2. **GraphQL**: Học như một sự bổ sung hoặc thay thế REST để truy vấn dữ liệu linh hoạt hơn.
3. **Tối ưu hóa Database**:

   * Với cơ sở dữ liệu quan hệ (Relational): tránh vấn đề N+1 select bằng cách viết truy vấn hiệu quả.
   * Với NoSQL: hiểu rõ trade-offs theo định lý CAP (Consistency, Availability, Partition tolerance).
4. **Tránh tối ưu hóa sớm (Premature Optimization)**: Cần đo lường và đánh giá hiệu suất trước khi tối ưu.
5. **Testing**:

   * Viết unit test và hiểu cách mock.
   * Phân biệt giữa unit test và integration test.
6. **Tổ chức mã nguồn**:

   * Nghiên cứu các dự án mã nguồn mở để học về thiết kế module.
   * Hiểu về dependency injection và inversion of control.
7. **Cloud Patterns**: Áp dụng exponential backoff, throttling và các thực hành tốt nhất khác.
8. **Web Security**: Nắm vững về cookies, localStorage, XSS, CSRF, JWTs và quản lý phiên đăng nhập.
9. **DevOps**:

   * Khám phá container (ví dụ: Docker) và kiến trúc serverless.
   * Hiểu CI/CD pipeline để triển khai tự động hóa.
10. **Multithreading**: Học mô hình concurrency nếu làm việc với ngôn ngữ như Java hoặc C++.


### Nguyên lý khái niệm

Ngoài công cụ cụ thể, những nguyên lý sau rất quan trọng trong việc xây dựng và duy trì hệ thống vững chắc:

* **Reliability**: Đảm bảo hệ thống vẫn hoạt động ổn định khi bị tải cao.
* **Monitoring and Observability**: Theo dõi sức khỏe hệ thống và chẩn đoán sự cố hiệu quả.
* **Error/Failure Handling**: Thiết kế hệ thống có khả năng xử lý lỗi một cách duyên dáng.
* **Migration Strategies**: Lập kế hoạch cho các đợt di chuyển dữ liệu hoặc hệ thống một cách trơn tru.
* **Data Normalization/Denormalization**: Cân bằng giữa hiệu suất và tính nhất quán trong cấu trúc dữ liệu.
* **Scalability**: Hiểu rõ sự khác biệt giữa scaling theo chiều ngang (thêm máy chủ) và chiều dọc (nâng cấp phần cứng).
