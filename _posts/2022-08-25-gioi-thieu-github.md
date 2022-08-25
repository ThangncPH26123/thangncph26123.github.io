---
layout: post
title: Giới thiệu Github
subtitle: Các khái niệm trong Github
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/github.png
share-img: /assets/img/path.jpg
tags: [Giới thiệu Github]
---

* Git là gì? Git là hệ thống kiểm soát phiên bản phân tán mà nguồn mở ( Open Source Distributed Version Control System). Các dự án thực tế thường có nhiều nhà phát triển làm việc song song. Vì vậy, một hệ thống kiểm soát phiên bản như Git là cần thiết để đảm bảo không có xung đột mã giữa các nhà phát triển. Ngoài ra, các yêu cầu trong dự án thay đổi thường xuyên. Vì vậy, cần một hệ thống cho phép nhà phát triển quay lại phiên bản cũ hơn của mã.

* Thế nào là repository, branch?

*Repository là gì ?

Repository hay còn gọi là Repo, dịch ra tiếng Việt có nghĩa là kho, đây chính là nơi chứa tất cả mã nguồn cho một dự án được tạo bởi Git. Bạn có thể hiểu một cách khác là Repository chính khai báo thư mục chứa dự án của bạn trên local hoặc remote. Một repo sẽ có hai cấu trúc dữ liệu chính đó là Object store và Index được lưu trữ ẩn trong thư mục .git .

*Có hai loại repository là local repository và remote repository:

Local repository: là repo được cài đặt trên máy tính của lập trình viên, repo này sẽ đồng bộ hóa với remote bằng các lệnh của Git.
Remote repository: là repo được cài đặt trên server chuyên dụng, điển hình hiện nay là Github.

*Branch là gì ?

Đối với những dự án có nhiều thành viên tham gia thì mỗi thành viên sẽ nhận được nhiều task từ leader, vì vậy việc xử lý task này trên cùng một thời gian là rất khó vì dễ bị đụng code. Để giải quyết vấn đề này thì chúng ta sẽ sử dụng branch của Git, tương ứng với mỗi nhiệm vụ chúng ta sẽ tạo một branh và làm việc trên đó, các branch này sẽ hoạt động riêng lẻ và không anh hưởng lẫn nhau.
Vậy branch là những phân nhánh ghi lại luồng thay đổi của lịch sử, các hoạt động trên mỗi branch sẽ không ảnh hưởng lên các branch khác nên có thể tiến hành nhiều thay đổi đồng thời trên một repository giúp giải quyết nhiều nhiệm vụ cùng lúc.
Khi bạn tạo một repository thì Git sẽ thiết lập branch mặc định là master, nghĩa là nó sẽ tự tạo một branch master và mọi hoạt động của ban lúc này đều nằm trên branch master.

*Github là gì?

Chúng ta đã nghe tới Git và có thể đã dùng GitHub nhưng chúng ta đa phần vẫn nhầm lẫn Git vs GitHub là một bởi vì cứ nói đến Git là nghĩ tới GitHub. Đó là một sự hiểu lầm vì Git như đã giải thích ở trên đó là tên gọi của một mô hình hệ thống, các máy tính có thể clone lại mã nguồn từ một repository , còn GitHub là tên của một công ty cũng cấp dịch vụ máy chủ repository công cộng, mỗi người có thể truy cập vào website trang chủ để tạo tài khoản trên đó và tạo ra kho chứa source của riêng mình khi làm việc.

*Tại sao nên sử dụng Git?

+ Git mang đến nhiều lợi thế cho công việc lập trình:
+ Git dễ sử dụng, an toàn và nhanh chóng.
+ Quản lý source code dễ dàng chuyên nghiệp
+ Có thể giúp quy trình làm việc code theo nhóm đơn giản hơn rất nhiều bằng việc kết hợp các phân nhánh (branch).
+ Hạn chế được lỗi xảy ra trong quá trình code trong 1 team
+ Khi gặp lỗi có thể dễ dàng Backup lại phiên bản trước
+ Code không giới hạn khoảng cách giữa các thành viên trong team, bạn có thể làm việc ở bất cứ đâu vì chỉ cần 
+ clone mã nguồn từ kho chứa hoặc clone một phiên bản thay đổi nào đó từ kho chứa, hoặc một nhánh nào đó từ kho chứa.
+ Dễ dàng trong việc deployment sản phẩm.