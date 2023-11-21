# AWS (Amazon Web Services)
## AWS là gì
AWS là viết tắt của Amazon Web Services, là một nền tảng dịch vụ điện toán đám mây cung cấp cho doanh nghiệp các giải pháp về sức mạnh tính toán, lưu trữ cơ sở dữ liệu, phân phối nội dung, công cụ phát triển phần mềm và nhiều hơn thế nữa. AWS có hơn 200 dịch vụ đầy đủ tính năng từ các trung tâm dữ liệu trên toàn thế giới, được sử dụng bởi hàng triệu khách hàng thuộc mọi ngành công nghiệp và quy mô. AWS được thiết kế để trở thành môi trường điện toán đám mây bảo mật và linh hoạt nhất hiện nay, với hơn 300 dịch vụ và tính năng bảo mật, tuân thủ và quản trị. AWS cũng liên tục đổi mới để phát minh ra các công nghệ mới như điện toán không máy chủ, machine learning và trí tuệ nhân tạo.

## Dịch vụ của AWS
### 1. Compute
#### Khái niệm
Điện toán AWS là cơ sở hạ tầng dưới dạng dịch vụ (IAAS). Nói một cách đơn giản, điện toán AWS là phương tiện để cung cấp và quản lý cơ sở hạ tầng (máy ảo/bộ chứa) cho trường hợp sử dụng của bạn. AWS cung cấp nhiều dịch vụ điện toán linh hoạt để đáp ứng yêu cầu của các tổ chức kinh doanh như Amazon Elastic Compute Cloud (EC2), Amazon Elastic Container Service (ECS), Amazon Elastic Container Service for Kubernetes (EKS), Amazon Lightsail, AWS Lambda và nhiều dịch vụ khác. Cơ sở hạ tầng này như một dịch vụ có thể được coi là sức mạnh xử lý theo yêu cầu của các ứng dụng của bạn, để lưu trữ các ứng dụng hoặc chạy các tác vụ tính toán chuyên sâu. Trong AWS, với việc sử dụng các dịch vụ điện toán này, người dùng có thể tự động cung cấp số lượng tài nguyên họ đang sử dụng và sau đó chỉ trả tiền cho các tài nguyên điện toán mà họ đã sử dụng. Từ đó, điều này dẫn đến việc giảm vốn đầu tư trả trước cần thiết.

Các tài nguyên điện toán này có liên quan chặt chẽ đến các thành phần máy chủ thông thường như CPU và RAM. Tuy nhiên, đối với các thành phần máy chủ thông thường, bạn cần quản lý và mua cơ sở hạ tầng, cung cấp các bản sao lưu và khôi phục khẩn cấp, đồng thời đảm bảo đủ dung lượng máy chủ để xử lý các thời gian sử dụng nhiều lưu lượng truy cập. Với điện toán AWS, tất cả vấn đề đau đầu này được giao cho nhóm AWS. Họ quản lý cơ sở hạ tầng và đảm bảo khôi phục ứng dụng của bạn trong trường hợp có bất kỳ lỗi hệ thống nào. Là người dùng, bạn chỉ trả tiền cho các dịch vụ bạn cung cấp miễn là bạn cung cấp chúng.

AWS Compute là một trong những dịch vụ đầu tiên được AWS cung cấp vào năm 2006, chỉ cung cấp một loại phiên bản EC-2 duy nhất. Amazon EC2 là dịch vụ AWS được sử dụng phổ biến nhất vì dịch vụ này có thể tích hợp với nhiều tính năng và dịch vụ khác như Auto Scaling, Elastic Block Store (EBS), Elastic Network Interface (ENI), Elastic Load Balancer (ELB), Amazon Machine Image (AMI), Instance Store, Elastic IP, Placements Groups, Security Groups và nhiều tính năng và dịch vụ khác.

#### Các tính năng
- Khả năng mở rộng: Đây là một trong những tính năng có lợi nhất của việc sử dụng cơ sở hạ tầng đám mây. Khả năng mở rộng có nghĩa là máy chủ ứng dụng của bạn có thể mở rộng theo chiều dọc (tăng khả năng tính toán hoặc các tính năng khác của tài nguyên của bạn) hoặc theo chiều ngang (cung cấp nhiều tài nguyên tương tự hơn) để xử lý nhu cầu của người dùng. Không cần phải nói rằng bạn sẽ chỉ trả tiền cho phiên bản mở rộng quy mô và không phải trả tiền cho việc sử dụng tính năng khả năng mở rộng này.

- Dịch vụ đa tiện ích: AWS Compute cung cấp các tài nguyên có thể được cung cấp và chạy trong nhiều năm, miễn là người dùng thực hiện thanh toán (EC2 và Elastic Beanstalk). Đồng thời, bạn cũng có thể sử dụng tài nguyên điện toán trong vài mili giây cho các tác vụ nhỏ (AWS Lambda).

- Phạm vi danh mục rộng: Tài nguyên điện toán có thể được cung cấp từ nhiều danh mục, với mỗi danh mục được sử dụng trong các khoảng thời gian khác nhau. Cung cấp sự linh hoạt hoàn toàn cho người dùng cho trường hợp sử dụng của họ.

- Tốc độ Ethernet: Tài nguyên điện toán có thể sử dụng tốc độ Ethernet lên đến 100Gbps.

- Nhiều địa điểm: Điện toán có thể được sử dụng trên phạm vi 22 Khu vực và 69 Vùng sẵn sàng trải rộng trên toàn cầu khi người dùng cần.

Hạn chế duy nhất của Điện toán AWS là, với số lượng lớn dịch vụ và các loại dịch vụ khác, đôi khi có thể khó chọn dịch vụ nào phù hợp nhất với trường hợp sử dụng của bạn. Tuy nhiên, AWS có một video hỗ trợ và cộng đồng và giải thích thực sự tốt có thể giúp bạn khắc phục nhược điểm này.

#### Các dịch vụ:
- EC-2 (Elastic Cloud Compute): Máy chủ ảo có thể được sử dụng cho tất cả các loại trường hợp sử dụng. Nền tảng cơ bản nhất của phiên bản EC2 thế hệ tiếp theo là Hệ thống AWS Nitro. Môi trường Server cho EC2 được gọi là instance. Gói hệ điều hành và một số cài đặt bổ sung trong mẫu có thể tái sử dụng của EC2 được gọi là Amazon Machine Images.

- Amazon Lightsail: Một trong những dịch vụ AWS dễ dàng nhất. Dễ dàng thiết lập máy chủ ảo cho các ứng dụng và trang web nhỏ. Cần ít cấu hình hơn so với EC2 hoặc các dịch vụ Điện toán AWS khác. Lightsail có tất cả các tiện ích bao gồm mọi thứ mà người dùng cần cho các trang web và ứng dụng web của họ như máy ảo (chọn HĐH Linux hoặc Windows), lưu trữ dựa trên SSD, truyền dữ liệu và nhiều hơn nữa.

- ECS (Elastic Container Service): Được sử dụng để chạy các ứng dụng container dựa trên docker. vì vậy, Elastic Container Service là một dịch vụ khu vực. ECS chủ yếu được sử dụng để tạo môi trường triển khai, mở rộng quy mô hàng loạt, xây dựng trải nghiệm và quản lý quy mô.

- ECR (Elastic Container Registry): Hiệu quả một cách dễ dàng để lưu trữ, quản lý và triển khai hình ảnh bộ chứa. Dịch vụ điện toán này là dịch vụ theo khu vực.

- EKS (Dịch vụ Kubernetes đàn hồi): Dịch vụ Kubernetes được quản lý hoàn toàn. EKS cho phép bạn chạy Kubernetes trên AWS mà không cần cài đặt, vận hành hoặc bảo trì.

- AWS Lambda: Máy chủ ít container hơn để chạy mã. Người dùng bị tính phí theo thời gian Lambda được sử dụng theo bội số của 100ms. Với Lambda, bạn có thể chạy mã bằng ngôn ngữ lập trình như Node.js, Java, C#, Go, Python, Ruby, PowerShell.

- AWS Fargate: Dịch vụ điện toán serverless cho bộ chứa. Dịch vụ điện toán này hoạt động với sự kết hợp của cả Amazon Elastic Container Service (ECS) và Amazon Elastic Kubernetes Service (EKS).

- AWS EC2 AutoScaling: Thiết lập các chính sách (tiêu chí) để tự động mở rộng quy mô/sở hữu các ứng dụng. Với AWS Auto Scaling, việc thiết lập thay đổi quy mô ứng dụng trở nên dễ dàng đối với nhiều tài nguyên.

- AWS Batch: Xử lý hàng loạt được quản lý hoàn toàn ở mọi quy mô. Điều này quản lý hàng đợi tác vụ và môi trường điện toán. Vì vậy, AWS Batch là một dịch vụ theo khu vực giúp chạy các tác vụ theo lô ở nhiều Vùng sẵn sàng trong một khu vực.

- AWS Compute Optimizer: Đề xuất các tính năng tài nguyên điện toán phù hợp dựa trên trường hợp sử dụng của bạn.

- EC2 Image Builder: Xây dựng và duy trì hình ảnh Linux hoặc Windows Server an toàn.

- ELB (Elastic Load Balancing): Tất cả các yêu cầu tính toán tài nguyên đều thông qua ELB. ELB phân phối tải yêu cầu giữa các phiên bản máy chủ cơ bản.

- AWS Outposts: Chạy cơ sở hạ tầng và dịch vụ AWS tại chỗ để có trải nghiệm đám mây lai thực sự nhất quán. Có thể được sử dụng bởi các doanh nghiệp lớn cần bảo mật thêm.

- AWS Wavelength: Cung cấp ứng dụng có độ trễ cực thấp cho các thiết bị 5G.

- AWS Elastic Beanstalk: Dịch vụ này cho phép người dùng mà không phải lo lắng về cơ sở hạ tầng để chạy những ứng dụng có thể nhanh chóng triển khai trên Đám mây AWS.

- AWS Local Zones: Chạy các ứng dụng nhạy cảm với độ trễ gần hơn với người dùng cuối.

- Amazon EC2 Spot Instances: Tận dụng dung lượng EC2 chưa sử dụng trên đám mây AWS. Phiên bản Spot được giảm giá tới 90% so với giá Theo yêu cầu.

### 2. Storage
#### Khái niệm
Amazon Web Services (AWS) Storage là một dịch vụ lưu trữ đám mây do Amazon cung cấp. AWS cung cấp một loạt các dịch vụ lưu trữ khác nhau để đáp ứng nhu cầu đa dạng của người dùng, từ lưu trữ dữ liệu thông thường đến lưu trữ dành cho các ứng dụng lớn và phức tạp.

#### Các tính năng
- Khả năng mở rộng: AWS cung cấp các dịch vụ lưu trữ như Amazon S3 (Simple Storage Service) cho việc lưu trữ đối tượng, Amazon EBS (Elastic Block Store) cho lưu trữ dữ liệu liên kết với các máy ảo EC2, và nhiều dịch vụ khác với khả năng mở rộng linh hoạt.

- Dịch vụ đa tiện ích: AWS cung cấp nhiều dịch vụ đa tiện ích khác nhau, không chỉ giới hạn trong lưu trữ. Các dịch vụ khác bao gồm máy ảo EC2 cho việc chạy ứng dụng, RDS cho quản lý cơ sở dữ liệu, Lambda cho việc chạy mã không máy chủ, và nhiều dịch vụ khác.

- Phạm vi danh mục rộng: AWS cung cấp một danh mục rộng các dịch vụ đám mây, bao gồm lưu trữ, tính toán, mạng, AI/ML, IoT, dịch vụ quản lý và nhiều hơn nữa.

- Tốc độ Ethernet: AWS hỗ trợ nhiều tốc độ kết nối mạng, bao gồm cả tốc độ Ethernet cao, giúp đảm bảo khả năng truy cập và truyền tải dữ liệu nhanh chóng và hiệu quả.

- Nhiều địa điểm: AWS có nhiều trung tâm dữ liệu (data centers) trên toàn thế giới. Người dùng có thể triển khai ứng dụng và dịch vụ của họ ở nhiều vị trí khác nhau để cải thiện hiệu suất và khả năng khôi phục sau sự cố.

Tuy nhiên, việc sử dụng các dịch vụ lưu trữ AWS cũng có thể đi kèm với chi phí và cần phải được quản lý cẩn thận để tránh trang trải chi phí không cần thiết.

#### Dịch vụ
- Amazon Simple Storage Service (S3) là một dịch vụ lưu trữ đối tượng cung cấp khả năng mở rộng, khả dụng và bảo mật hàng đầu trong ngành cho việc lưu trữ và truy xuất bất kỳ lượng dữ liệu nào từ bất cứ đâu. Bạn có thể sử dụng Amazon S3 để lưu trữ dữ liệu cho các trang web, ứng dụng di động, sao lưu và khôi phục, lưu trữ, phân tích dữ liệu lớn và nhiều hơn nữa.

- Amazon Elastic Block Store (EBS) là một dịch vụ lưu trữ khối cung cấp các tập lưu trữ có tính liên tục và hiệu năng cao để sử dụng với các phiên bản Amazon EC2. Bạn có thể sử dụng Amazon EBS để lưu trữ cơ sở dữ liệu, hệ thống tệp và ứng dụng yêu cầu truy cập dữ liệu nhất quán và độ trễ thấp.

- Amazon Elastic File System (EFS) là một dịch vụ lưu trữ tệp cung cấp một hệ thống tệp đơn giản, có thể mở rộng và linh hoạt cho các tải làm việc dựa trên Linux. Bạn có thể sử dụng Amazon EFS để chia sẻ dữ liệu tệp giữa hàng nghìn phiên bản Amazon EC2 và máy chủ nội bộ, và để chạy các ứng dụng yêu cầu mức độ thông lượng và IOPS cao.

- Amazon FSx là một nhóm các dịch vụ lưu trữ tệp được quản lý hoàn toàn, cung cấp các khả năng và hiệu suất của các hệ thống tệp thương mại và mã nguồn mở phổ biến. Bạn có thể chọn từ Amazon FSx for Windows File Server, Amazon FSx for Lustre, Amazon FSx for OpenZFS và Amazon FSx for NetApp ONTAP, tùy thuộc vào nhu cầu và sở thích của bạn.

- Amazon File Cache là một dịch vụ lưu trữ đệm tốc độ cao, giúp bạn dễ dàng xử lý dữ liệu tệp, bất kể dữ liệu được lưu trữ ở đâu. Bạn có thể sử dụng Amazon File Cache để liên kết bộ nhớ đệm với nhiều nguồn NFS hoặc Amazon S3, và truy cập dữ liệu của bạn với tốc độ cao và góc nhìn thống nhất.

- AWS DataSync là một dịch vụ chuyển dữ liệu trực tuyến, tối ưu hóa băng thông mạng và tăng tốc độ di chuyển dữ liệu giữa lưu trữ nội bộ và lưu trữ AWS. Bạn có thể sử dụng AWS DataSync để di chuyển dữ liệu lên đám mây, chuyển dữ liệu tới và từ các thiết bị AWS Snow, hoặc sao chép dữ liệu tới AWS để sao lưu và khôi phục dữ liệu khi xảy ra sự cố.

- AWS Snow Family là một bộ sưu tập các thiết bị chuyển dữ liệu ngoại tuyến, có tích hợp các tính năng bảo mật và logistics để đơn giản hóa việc di chuyển dữ liệu. Bạn có thể sử dụng các thiết bị AWS Snow để di chuyển lượng lớn dữ liệu vào và ra khỏi AWS, hoặc để thực hiện các tải làm việc tính toán cạnh trong các môi trường xa hoặc không kết nối.

- AWS Storage Gateway là một dịch vụ lưu trữ lai, cho phép bạn kết nối liền mạch các ứng dụng nội bộ của bạn với các dịch vụ lưu trữ AWS. Bạn có thể sử dụng AWS Storage Gateway để lưu trữ và truy cập dữ liệu của bạn trong Amazon S3, Amazon S3 Glacier, Amazon EBS, hoặc Amazon FSx for Windows File Server, sử dụng các giao thức lưu trữ tiêu chuẩn như NFS, SMB, iSCSI, hoặc iSCSI-VTL.

- AWS Backup là một dịch vụ sao lưu được quản lý hoàn toàn, giúp bạn dễ dàng trung tâm hóa và tự động hóa việc sao lưu dữ liệu của bạn trên các dịch vụ AWS và tài nguyên nội bộ. Bạn có thể sử dụng AWS Backup để bảo vệ dữ liệu của bạn khỏi việc xóa nhầm, hỏng hóc, hoặc tấn công mã độc, và để tuân thủ các yêu cầu kinh doanh và quy định.

### 3. Networking & Content Delivery
#### Khái niệm
Kết nối mạng và phân phối nội dung là hai khía cạnh quan trọng của AWS cho phép bạn kết nối, bảo mật và tối ưu hóa các ứng dụng cũng như dữ liệu của mình trên đám mây. AWS cung cấp nhiều dịch vụ kết nối mạng và phân phối nội dung giúp bạn xây dựng và quản lý cơ sở hạ tầng mạng, phân phối nội dung của bạn đến khách hàng với hiệu suất cao và độ trễ thấp, đồng thời bảo vệ ứng dụng của bạn khỏi các cuộc tấn công và gián đoạn.

#### Các tính năng
- Khả năng mở rộng: AWS Networking and Content Delivery có khả năng mở rộng linh hoạt, giúp bạn mở rộng hạ tầng mạng của mình theo nhu cầu.

- Dịch vụ đa tiện ích: Nó cung cấp nhiều dịch vụ đa tiện ích, bao gồm mạng CDN (Content Delivery Network), Load Balancing, DNS quản lý và nhiều tính năng khác để tối ưu hóa hiệu suất và độ tin cậy của ứng dụng.

- Phạm vi danh mục rộng: AWS Networking and Content Delivery cung cấp một danh mục đa dạng của các dịch vụ và công nghệ mạng, từ Amazon VPC (Virtual Private Cloud) cho đến Amazon CloudFront (dịch vụ CDN).

- Tốc độ Ethernet: Cung cấp hỗ trợ cho các tốc độ Ethernet đa dạng, từ Fast Ethernet đến Gigabit và thậm chí 100 Gigabit, giúp đáp ứng nhu cầu về băng thông của các ứng dụng và dịch vụ.

- Nhiều địa điểm: AWS có nhiều trung tâm dữ liệu trên khắp thế giới, cho phép bạn triển khai ứng dụng và dịch vụ của mình gần với người dùng cuối để cải thiện hiệu suất và độ trễ.

Mặc dù có nhiều tính năng và linh hoạt, việc triển khai và quản lý có thể đối mặt với một số hạn chế, đặc biệt là đối với người dùng mới vào AWS. Cần có kiến thức vững về các dịch vụ và kiến trúc mạng để tối ưu hóa sự linh hoạt của nó.

#### Dịch vụ
- Amazon API Gateway: là một dịch vụ được quản lý hoàn toàn làm cho các nhà phát triển dễ dàng tạo, xuất bản, duy trì, giám sát và bảo mật API ở mọi quy mô. Với một vài cú nhấp chuột trong Bảng điều khiển quản lý AWS, bạn có thể tạo API hoạt động như một "cửa trước" cho các ứng dụng để truy cập dữ liệu, logic nghiệp vụ hoặc chức năng từ các dịch vụ back-end của bạn, chẳng hạn như khối lượng công việc chạy trên Amazon EC2, mã chạy trên AWS Lambda hoặc bất kỳ ứng dụng web nào. Amazon API Gateway xử lý tất cả các tác vụ liên quan đến việc chấp nhận và xử lý tới hàng trăm nghìn lệnh gọi API đồng thời, bao gồm quản lý lưu lượng, ủy quyền và kiểm soát truy cập, giám sát và phiên bản API sự quản lý.

- Amazon CloudFront: là một mạng phân phối nội dung nhanh (CDN) dịch vụ cung cấp dữ liệu, video, ứng dụng và API một cách an toàn cho khách hàng trên toàn cầu Với độ trễ thấp, tốc độ truyền cao, tất cả trong một môi trường thân thiện với nhà phát triển. CloudFront là được tích hợp với AWS – cả hai vị trí thực tế được kết nối trực tiếp với AWS toàn cầu cơ sở hạ tầng, cũng như các dịch vụ AWS khác. CloudFront hoạt động liền mạch với các dịch vụ bao gồm: AWS Shield để giảm thiểu DDoS, Amazon S3, Elastic Load Balancing hoặc Amazon EC2 làm nguồn cho các ứng dụng của bạn và Lambda@Edge chạy mã tùy chỉnh gần hơn với người dùng của khách hàng và tùy chỉnh trải nghiệm người dùng. Bạn có thể bắt đầu với mạng phân phối nội dung trong vài phút bằng cách sử dụng cùng một AWS các công cụ mà bạn đã quen thuộc: API, Bảng điều khiển quản lý AWS, AWS CloudFormation, CLI và SDK. Amazon CDN Cung cấp một mô hình định giá đơn giản, thanh toán theo mức sử dụng mà không có phí trả trước hoặc yêu cầu dài hạn hợp đồng và hỗ trợ cho CDN được bao gồm trong gói đăng ký AWS Support hiện có của bạn.

- Amazon Route 53: là dịch vụ web Hệ thống tên miền trên nền tảng đám mây có khả năng mở rộng cao và có tính sẵn sàng cao. Nó được thiết kế để cung cấp cho các nhà phát triển và doanh nghiệp một cách cực kỳ đáng tin cậy và tiết kiệm chi phí để định tuyến người dùng đến các ứng dụng internet bằng cách dịch các tên mà con người có thể đọc được, chẳng hạn như , thành địa chỉ IP dạng số, chẳng hạn như , mà các máy tính sử dụng để kết nối với nhau. Amazon Route 53 cũng hoàn toàn tương thích với IPv6. Bạn có thể sử dụng Amazon Route 53 để đặt cấu hình kiểm tra tình trạng DNS nhằm định tuyến lưu lượng truy cập đến các điểm cuối hoạt động tốt hoặc để giám sát độc lập tình trạng ứng dụng của bạn và các điểm cuối của ứng dụng đó.

- AWS Verified Access: cung cấp cho người dùng doanh nghiệp Truy cập an toàn vào các ứng dụng của bạn mà không cần sử dụng mạng riêng ảo (VPN). Dựa trên AWS Nguyên tắc Zero Trust, Quyền truy cập đã xác minh đánh giá từng yêu cầu ứng dụng trong thời gian thực để giúp đảm bảo rằng Người dùng chỉ có thể truy cập các ứng dụng của bạn sau khi chúng đáp ứng các yêu cầu bảo mật cụ thể. Bạn có thể Nhóm các ứng dụng hoặc xác định các chính sách truy cập duy nhất cho từng ứng dụng, với các điều kiện dựa trên trên dữ liệu nhận dạng người dùng và tư thế thiết bị.

- Amazon Virtual Private Cloud (Amazon VPC): cho phép bạn cung cấp một phần riêng biệt về mặt logic của Đám mây AWS nơi bạn có thể khởi chạy các tài nguyên AWS trong mạng ảo do bạn xác định. Bạn có toàn quyền kiểm soát môi trường mạng ảo của mình, bao gồm việc lựa chọn dải địa chỉ IP của riêng bạn, tạo mạng con và cấu hình bảng định tuyến và cổng mạng. Bạn có thể dễ dàng tùy chỉnh cấu hình mạng cho VPC của mình. Ngoài ra, bạn có thể tạo kết nối mạng riêng ảo phần cứng giữa trung tâm dữ liệu công ty và VPC, đồng thời tận dụng Đám mây AWS như một phần mở rộng của trung tâm dữ liệu công ty.

- Amazon VPC Lattice: cung cấp quản lý hoàn toàn Hỗ trợ kết nối và liên lạc giữa dịch vụ với dịch vụ. Với VPC Lattice, bạn có thể sử dụng Các chính sách xác định quản lý, truy cập và giám sát lưu lượng mạng để kết nối các dịch vụ điện toán theo cách đơn giản và bảo mật trên các phiên bản, bộ chứa và ứng dụng serverless.

- AWS App Mesh: giúp dễ dàng giám sát và kiểm soát các vi dịch vụ chạy trên AWS. App Mesh tiêu chuẩn hóa cách các vi dịch vụ của bạn giao tiếp, mang lại cho bạn khả năng hiển thị toàn diện và giúp đảm bảo tính sẵn sàng cao cho các ứng dụng của bạn. Các ứng dụng hiện đại thường bao gồm nhiều vi dịch vụ, mỗi vi dịch vụ thực hiện một chức năng cụ thể. Mỗi microservice tương tác với tất cả các microservice khác thông qua API. Khi số lượng vi dịch vụ tăng lên trong một ứng dụng, việc xác định chính xác vị trí lỗi, định tuyến lại lưu lượng truy cập sau lỗi và triển khai các thay đổi mã một cách an toàn ngày càng trở nên khó khăn. App Mesh loại bỏ nhu cầu cập nhật mã ứng dụng để thay đổi cách thu thập dữ liệu giám sát hoặc định tuyến lưu lượng truy cập giữa các vi dịch vụ. App Mesh định cấu hình từng vi dịch vụ để xuất dữ liệu giám sát và triển khai logic kiểm soát truyền thông nhất quán trên ứng dụng của bạn. Điều này giúp bạn dễ dàng nhanh chóng xác định chính xác vị trí lỗi và tự động định tuyến lại lưu lượng truy cập mạng khi có lỗi hoặc khi cần triển khai thay đổi mã.

- AWS Cloud Map: là dịch vụ khám phá tài nguyên đám mây. Với AWS Cloud Map, bạn có thể xác định tên tùy chỉnh cho tài nguyên ứng dụng của mình và nó duy trì vị trí cập nhật của những tài nguyên thay đổi linh hoạt này. Mỗi dịch vụ tương tác với nhiều tài nguyên khác như cơ sở dữ liệu, hàng đợi, kho đối tượng và vi dịch vụ do khách hàng xác định, đồng thời chúng cũng cần có khả năng tìm thấy vị trí của tất cả các tài nguyên cơ sở hạ tầng mà nó phụ thuộc vào để hoạt động. Bạn thường quản lý thủ công tất cả các tên tài nguyên này và vị trí của chúng trong mã ứng dụng. AWS Cloud Map cho phép bạn đăng ký mọi tài nguyên ứng dụng như cơ sở dữ liệu, hàng đợi, vi dịch vụ và các tài nguyên đám mây khác bằng tên tùy chỉnh.

- AWS Direct Connect: giúp dễ dàng thiết lập kết nối mạng chuyên dụng từ cơ sở của bạn đến AWS. AWS Direct Connect cho phép bạn thiết lập kết nối mạng chuyên dụng giữa mạng của bạn và một trong các vị trí AWS Direct Connect. Điều này cho phép bạn sử dụng cùng một kết nối để truy cập các tài nguyên công cộng, chẳng hạn như các đối tượng được lưu trữ trong Amazon S3 sử dụng không gian địa chỉ IP công cộng và các tài nguyên riêng tư như phiên bản EC2 chạy trong VPC sử dụng không gian địa chỉ IP riêng tư, trong khi vẫn duy trì sự tách biệt mạng giữa các tài nguyên công cộng. và môi trường riêng tư.

- AWS Global Accelerator: là một dịch vụ mạng giúp cải thiện tính khả dụng và hiệu suất của các ứng dụng mà bạn cung cấp cho người dùng toàn cầu của mình. AWS Global Accelerator sử dụng mạng toàn cầu AWS có tính sẵn sàng cao và không bị tắc nghẽn để hướng lưu lượng truy cập Internet từ người dùng đến ứng dụng của bạn trên AWS, giúp trải nghiệm của người dùng trở nên nhất quán hơn. AWS Global Accelerator cũng giúp bạn quản lý các ứng dụng toàn cầu dễ dàng hơn bằng cách cung cấp địa chỉ IP tĩnh đóng vai trò là điểm truy cập cố định vào ứng dụng của bạn được lưu trữ trên AWS, giúp loại bỏ sự phức tạp trong việc quản lý địa chỉ IP cụ thể cho các Khu vực AWS và Availability Zones khác nhau.

- AWS PrivateLink: đơn giản hóa việc bảo mật dữ liệu được chia sẻ với các ứng dụng dựa trên đám mây bằng cách loại bỏ việc dữ liệu bị lộ ra Internet công cộng. AWS PrivateLink cung cấp kết nối riêng tư giữa các VPC, dịch vụ AWS và ứng dụng tại chỗ một cách an toàn trên mạng Amazon. AWS PrivateLink giúp dễ dàng kết nối các dịch vụ trên các tài khoản và VPC khác nhau để đơn giản hóa đáng kể kiến ​​trúc mạng.

- AWS Private 5G: cung cấp một cách dễ dàng để sử dụng công nghệ di động nhằm tăng cường mạng hiện tại của bạn. Bạn sẽ nhận được tất cả phần cứng và phần mềm 5G riêng mà bạn cần để triển khai mạng di động riêng và kết nối thiết bị với ứng dụng của mình. Với một vài cú nhấp chuột trong Bảng điều khiển quản lý AWS, hãy triển khai mạng di động riêng đáp ứng yêu cầu kết nối của bạn. Sau khi bật nguồn thiết bị, AWS sẽ tự động định cấu hình và triển khai mạng di động. AWS Private 5G cũng được tích hợp với AWS Identity and Access Management, giúp bạn truy cập và quản lý các dịch vụ và tài nguyên AWS một cách an toàn, bao gồm tất cả các thiết bị được kết nối với mạng 5G riêng tư của bạn. 5G riêng tư quản lý và duy trì tất cả các thành phần phần mềm và phần cứng để cung cấp hoạt động mạng đáng tin cậy, có thể dự đoán được cũng như khả năng mở rộng quy mô theo yêu cầu để phù hợp với mọi số lượng thiết bị và cảm biến.

- AWS Transit Gateway: là dịch vụ cho phép khách hàng kết nối Đám mây riêng ảo Amazon và mạng tại chỗ của họ với một cổng duy nhất. Để kết nối tại chỗ, bạn cần đính kèm AWS VPN của mình với từng Amazon VPC riêng lẻ. Giải pháp này có thể tốn thời gian xây dựng và khó quản lý khi số lượng VPC tăng lên hàng trăm. Mô hình trung tâm và nan hoa này giúp đơn giản hóa đáng kể việc quản lý và giảm chi phí vận hành vì mỗi mạng chỉ phải kết nối với Transit Gateway chứ không phải với mọi mạng khác.

- AWS Virtual Private Network(AWS VPN): thiết lập kết nối an toàn giữa mạng tại chỗ, văn phòng từ xa, thiết bị khách và mạng toàn cầu AWS. Mỗi dịch vụ đều cung cấp giải pháp VPN đám mây có độ sẵn sàng cao, được quản lý và linh hoạt để bảo vệ lưu lượng mạng của bạn. Để quản lý quyền truy cập từ xa, AWS Client VPN kết nối người dùng của bạn với AWS hoặc tài nguyên tại chỗ bằng ứng dụng khách phần mềm VPN.

- Elastic Load Balancing(ELB): tự động phân phối lưu lượng truy cập ứng dụng đến trên nhiều mục tiêu, chẳng hạn như phiên bản, bộ chứa và địa chỉ IP của Amazon EC2. Hoạt động ở cấp độ yêu cầu riêng lẻ, Cân bằng tải ứng dụng định tuyến lưu lượng truy cập đến các mục tiêu trong Amazon Virtual Private Cloud dựa trên nội dung của yêu cầu. Gateway Load Balancer giúp dễ dàng triển khai, mở rộng quy mô và chạy các thiết bị mạng ảo của bên thứ ba. Cung cấp khả năng cân bằng tải và tự động thay đổi quy mô cho nhóm thiết bị của bên thứ ba, Gateway Load Balancer minh bạch đối với nguồn và đích của lưu lượng truy cập.

- The Integrated Private Wireless on AWS: chương trình được thiết kế để cung cấp cho các doanh nghiệp các dịch vụ không dây riêng được quản lý và xác thực từ các Nhà cung cấp dịch vụ truyền thông hàng đầu. Kiến trúc sư giải pháp AWS Telco xác nhận về mặt kỹ thuật các dịch vụ có kiến ​​trúc phù hợp và tuân thủ các biện pháp thực hành tốt nhất của AWS. Chương trình này cũng sử dụng kiến ​​thức chuyên môn phong phú của các đối tác Nhà cung cấp phần mềm độc lập AWS toàn cầu đã được xác thực để tăng tốc thời gian tạo ra giá trị cho hoạt động triển khai không dây riêng tư. Không dây riêng tư tích hợp trên AWS loại bỏ các chu trình lập kế hoạch dài và tích hợp phức tạp thường được yêu cầu để thiết lập và mở rộng mạng không dây riêng tư.

### Analysis
