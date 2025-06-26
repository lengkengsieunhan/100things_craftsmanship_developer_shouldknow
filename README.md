# 100things_craftsmanship_developer_shouldknow
Collection of principles and practices for software developers, emphasizing craftsmanship, strong sense of craftsmanship, focusing on quality and practices. 

* DAY 1: Communication
  
1/ Các cách nói mơ hồ nên tránh, không cụ thể khi trình bày nguyên nhân.

❌ Mơ hồ: "Có lỗi gì đó...” – không chuyên nghiệp, không cụ thể.

❌ Mơ hồ: “Tự nhiên không chạy nữa” – rất mơ hồ.

➡ Ghi rõ nội dung lỗi hoặc hành vi cụ thể → giúp người nghe hiểu chính xác.

➡ Mô tả rõ sự kiện xảy ra, dễ truy tìm nguyên nhân.


❌ Mơ hồ: “Có vẻ hơi khó, tôi sẽ thử xác nhận lại.” Vấn đề: Không nêu rõ phần nào khó, cần xác nhận với ai, khi nào.

➡ Không nêu rõ phần nào khó, cần xác nhận với ai, khi nào.


2/ Hứa mơ hồ về deadline

❌ Mơ hồ: “Tôi nghĩ là sẽ xong trong tuần sau.” Vấn đề: Không có ngày cụ thể, thiếu cam kết.

→ ✅ Rõ ràng: “Dự kiến hoàn thành vào ngày 26/6 (thứ Tư). Nếu có chậm trễ, sẽ thông báo trước ngày 24/6.”


3/ Trả lời khi bị truy vấn lỗi

❌ Mơ hồ: “Có lẽ thay đổi trước đó đã gây ảnh hưởng.” Vấn đề: làm mất sự tin cậy và thiếu tinh thần chịu trách nhiệm.

→ ✅ Rõ ràng: “Có khả năng cao là do thay đổi cấu hình ngày 5/6 làm ghi đè tham số. Chúng tôi đang kiểm tra lại dựa trên log.”


4/ Đề xuất giải pháp mơ hồ

❌ Mơ hồ: “Tạm thời thử cách này xem sao.”

Vấn đề đều không chắc chắn, khiến khách cảm thấy thiếu trách nhiệm.

→ ✅ Rõ ràng: “Sẽ áp dụng phương án A làm giải pháp tạm thời, và đề xuất phương án xử lý lâu dài trong tuần này.”


5/ Giải trình sự cố mơ hồ
❌ Mơ hồ: → “Không hiểu sao nó không chạy nữa.” 
🔍 Vấn đề: Câu này dễ khiến khách hàng mất niềm tin vì thiếu kiểm soát và không nêu nguyên nhân rõ ràng.

→ ✅ Rõ ràng: “Do lỗi timeout khi kết nối cơ sở dữ liệu, API đã không phản hồi. Hiện tại đã được khôi phục bằng cách khởi động lại.”


6/ Báo cáo tiến độ
❌ Mơ hồ: → “Công việc hầu như đã xong.”

✅ Rõ ràng: → “80% công việc đã hoàn thành, 5 test case còn lại sẽ được thực hiện trong hôm nay.”


* DAY 2:  Process & Development (Quy trình & Phát triển)
7/ No Meetings (or Few): Are you minimizing meetings and maximizing actual work time?
No Estimates (or Loose Ones): Are you focusing on clear, small tasks rather than trying to estimate large, uncertain projects?
Work Normal Hours: Are you avoiding burnout and fostering sustainable work habits by not overworking?
Just Enough Process: Have you eliminated unnecessary bureaucracy and formalities?
Embrace Constraints: Are you using limitations (time, budget, features) to foster creativity and focus?
Ship It: Are you prioritizing getting your product into users' hands over endless refinement?
Iterate Quickly: Are you releasing small updates frequently based on feedback?
Kill Things: Are you willing to cut features, projects, or even products that aren't working?

8/ People & Collaboration
Hire for Character: Are you prioritizing enthusiasm, curiosity, and good communication over just specific skills?
Don't Grow Too Fast: Are you maintaining a lean team to ensure clear communication and efficiency?
Manage by Not Managing: Are you trusting your team to do their best work without micromanagement?
Don't Do Peripherals: Are you focusing on your core business and outsourcing non-essential tasks?
Write It Down: Are you communicating ideas and decisions clearly in writing?


* DAY 3: Philosophies & Mindset (Triết lý & Tư duy)
Care About Your Craft: Do you take pride in your work and strive for excellence in every line of code?
Bạn có quan tâm đến nghề của mình và cố gắng đạt được sự xuất sắc trong từng dòng mã không?


Don't Live with Broken Windows: Do you fix small problems (like bad design, incorrect code, or poor comments) as soon as you find them, to prevent project degradation?
Bạn có sửa chữa các vấn đề nhỏ (như thiết kế tồi, mã sai, hoặc bình luận kém) ngay khi phát hiện ra chúng, để ngăn chặn dự án xuống cấp không?


Be a Catalyst for Change: Do you proactively suggest and implement improvements rather than waiting for permission?
Bạn có chủ động đề xuất và thực hiện các cải tiến thay vì chờ đợi sự cho phép không?


Remember the Big Picture: Do you understand the context of your work within the larger project and business goals?
Bạn có hiểu bối cảnh công việc của mình trong tổng thể dự án và mục tiêu kinh doanh không?


Don't Be a Parrot (Rubber Ducking): Do you articulate problems to yourself or an inanimate object to clarify your thoughts before seeking help?
Bạn có trình bày rõ ràng các vấn đề với bản thân hoặc một vật vô tri để làm rõ suy nghĩ của mình trước khi tìm kiếm sự giúp đỡ không?


Invest Regularly in Your Knowledge Portfolio: Do you continuously learn new technologies, read widely, and experiment to keep your skills current?
Bạn có đầu tư thường xuyên vào "danh mục kiến thức" của mình bằng cách liên tục học công nghệ mới, đọc nhiều sách, và thử nghiệm để giữ kỹ năng của mình luôn cập nhật không?


* DAY 4: Taking Responsibility (Chịu trách nhiệm)
Take Responsibility (DRY Principle Applied to Responsibility): Do you take personal responsibility for your actions and avoid blaming others?
Bạn có chịu trách nhiệm cá nhân về hành động của mình và tránh đổ lỗi cho người khác không?


Provide Options, Not Excuses: When faced with a problem, do you present potential solutions and their trade-offs, rather than just stating limitations?
Khi đối mặt với một vấn đề, bạn có đưa ra các giải pháp tiềm năng và đánh đổi của chúng, thay vì chỉ nêu ra những hạn chế không?


Sign Your Work: Do you stand behind the quality of your code as if you were signing your name to it?
Bạn có chịu trách nhiệm về chất lượng mã của mình như thể bạn đang ký tên vào đó không?


Failing to Deal with Reality: Do you acknowledge and address problems directly, even if they are uncomfortable?
Bạn có thừa nhận và giải quyết trực tiếp các vấn đề, ngay cả khi chúng khó chịu không?


* DAY 5: Communication & Collaboration (Giao tiếp & Hợp tác)
Communicate Effectively: Can you clearly and concisely explain technical concepts to both technical and non-technical audiences?
Bạn có thể giải thích các khái niệm kỹ thuật một cách rõ ràng và súc tích cho cả đối tượng kỹ thuật và không kỹ thuật không?


Don't Guess — Ask! Do you ask clarifying questions rather than making assumptions?
Bạn có hỏi các câu hỏi làm rõ thay vì đưa ra giả định không?


Share Your Knowledge: Do you actively share what you've learned with your team and the wider community?
Bạn có chủ động chia sẻ những gì mình đã học được với nhóm của mình và cộng đồng rộng lớn hơn không?


Listen Actively: Do you truly listen to understand others' perspectives and needs?
Bạn có thực sự lắng nghe để hiểu quan điểm và nhu cầu của người khác không?


* DAY 5: Code Quality & Design (Chất lượng mã & Thiết kế)
DRY (Don't Repeat Yourself): Have you eliminated all forms of duplication in your code, knowledge, and processes?
Bạn đã loại bỏ tất cả các hình thức trùng lặp trong mã, kiến thức và quy trình của mình chưa?


Orthogonality: Are components of your system independent and loosely coupled, so changes in one don't affect others?
Các thành phần trong hệ thống của bạn có độc lập và ít phụ thuộc vào nhau không, để thay đổi ở một phần không ảnh hưởng đến các phần khác?


Tracer Bullets: Do you build early, end-to-end prototypes to gain feedback and learn rapidly?
Bạn có xây dựng các nguyên mẫu đầu tiên, từ đầu đến cuối để nhận phản hồi và học hỏi nhanh chóng không?


Separate Views from Models: Do you clearly separate the data (model) from its presentation (view)?
Bạn có tách biệt rõ ràng dữ liệu (model) khỏi cách trình bày của nó (view) không?


Use Metaprogramming (When Appropriate): Do you use code that writes code to reduce duplication and improve flexibility (but wisely)?
Bạn có sử dụng metaprogramming (khi thích hợp) để giảm trùng lặp và cải thiện tính linh hoạt (nhưng một cách khôn ngoan) không?


Code for the Future: Do you write code that is adaptable and extensible, anticipating likely future changes?
Bạn có viết mã có khả năng thích nghi và mở rộng, dự đoán các thay đổi có thể xảy ra trong tương lai không?


Quality First: Is quality built in from the start, rather than being an afterthought or something to "test in" later?

Process Improvement: Are managers and teams continuously looking for ways to improve their development process, focusing on human efficiency?

Respect for Work: Is there a culture of respect for the work itself and the effort involved in creating quality software?

* DAY 6: Testing (Kiểm thử)
Test Early, Test Often: Do you integrate testing throughout the development lifecycle?
Bạn có tích hợp việc kiểm thử xuyên suốt vòng đời phát triển không?


Test Your Assumptions: Do you write tests to validate your understanding of requirements and system behavior?
Bạn có viết các bài kiểm thử để xác nhận sự hiểu biết của mình về các yêu cầu và hành vi của hệ thống không?


Use Automated Tests: Do you rely on automated unit, integration, and acceptance tests?
Bạn có dựa vào các bài kiểm thử tự động ở cấp đơn vị, tích hợp và chấp nhận không?


Testing is Not Debugging: Do you understand that testing is about proving correctness, while debugging is about finding the cause of incorrectness?
Bạn có hiểu rằng kiểm thử là để chứng minh tính đúng đắn, trong khi gỡ lỗi là để tìm ra nguyên nhân của sự không đúng đắn không?


* DAY 7: Estimation

Realistic Estimation: Are your project estimates based on careful analysis, not just wishful thinking or pressure?

Phase Distribution: Is your schedule roughly allocating 1/3 planning, 1/6 coding, 1/4 component testing, and 1/4 system testing?

Tracking Progress: Do you have clear, objective ways to track project progress (e.g., lines of code designed, components integrated, not just written)?


* DAY 8: Risk & Fear (Rủi ro & Sợ hãi)
  Reduce Fear: Is the workplace free from an atmosphere of fear (e.g., fear of failure, job insecurity, arbitrary decisions)?
  
  
  Embrace Mistakes as Learning: Are mistakes viewed as opportunities for learning and improvement, rather than solely as failures?

  Safe-to-Fail Experimentation: Are teams encouraged to experiment and try new things in a safe-to-fail environment?
