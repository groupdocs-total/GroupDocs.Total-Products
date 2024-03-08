---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Total"
product_tag: "total"

############################# Head ############################
head_title: "API tự động hóa tài liệu | API tại chỗ và dịch vụ trực tuyến"
head_description: "Tự động hóa thao tác tài liệu của bạn một cách dễ dàng và miễn phí"

############################# Header ##########################
title: "Tự động hóa tài liệu chính với bộ tất cả trong một"
description: |
  Đơn giản hóa các tác vụ tài liệu lặp đi lặp lại và hợp lý hóa quy trình công việc của bạn chỉ bằng một vài dòng mã. Các API mạnh mẽ giúp việc tích hợp trở nên dễ dàng, giúp bạn tập trung vào đổi mới chứ không phải cơ sở hạ tầng.

  Chuyển đổi, ký, xem, chú thích - chinh phục mọi tác vụ tài liệu với mã tối thiểu. Từ Word sang PDF, Excel đến hình ảnh, xử lý mọi thứ một cách liền mạch. Ít mã hơn, tác động lớn hơn.

  Tự động hóa các tác vụ tài liệu, tăng hiệu quả và di chuyển nhanh chóng với khả năng tích hợp tốc độ cực nhanh. Tiết kiệm thời gian và nguồn lực, tập trung vào những gì thực sự quan trọng đối với doanh nghiệp của bạn.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Chọn nền tảng của bạn"
  title: "Nền tảng được hỗ trợ"
  description: "Thư viện GroupDocs.Total hỗ trợ các hệ điều hành và framework sau"
  details_link_title: "Tìm hiểu thêm"
  items:
    # supported_platforms loop
    - title: ".NET"
      description: "GroupDocs.Total for .NET"
      color: "blue"
      tag: "net"
      link: "/total/net/"
      features_link: "https://docs.groupdocs.com/total/net/system-requirements/"
      features:
        # features loop
        - content: ".NET Framework 4.6.2+  <br>  .NET Core 3.1  <br>  .NET 6+"
          rows: "3"
        # features loop
        - content: "Windows, Linux"
          rows: "1"
        # features loop
        - content: "Hơn 200 định dạng tệp"
          rows: "1"
        # features loop
        - content: "Visual Studio <br> VS Code <br> Rider"
          rows: "15"
    
    # supported_platforms loop
    - title: "Java"
      description: "GroupDocs.Total for Java"
      color: "red"
      tag: "java"
      link: "/total/java/"
      features_link: "https://docs.groupdocs.com/total/java/system-requirements/"
      features:
        # features loop
        - content: "J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"       
        # features loop
        - content: "Hơn 200 định dạng tệp"
          rows: "1"
        # features loop
        - content:  "Eclipse <br> NetBeans <br> IntelliJ Idea"
          rows: "3"

############################# Features ############################

features:
  enable: true
  title: "Bộ tính năng của GroupDocs.Total"
  description: "Giải pháp duy nhất thống nhất chức năng của tất cả các sản phẩm GroupDocs riêng lẻ dưới một mái nhà và quản lý mọi tác vụ tài liệu mà không cần phần mềm của bên thứ ba."

  items:
    # feature loop
    - icon: "view"
      title: "Xem tài liệu và hình ảnh"
      content: "Kết xuất các tệp để xem chúng ở định dạng HTML, PDF, PNG và JPEG."

    # feature loop
    - icon: "convert"
      title: "Chuyển đổi giữa các định dạng"
      content: "Chuyển đổi các tập tin từ nguồn khác nhau sang các định dạng đích khác nhau."

    # feature loop
    - icon: "merge"
      title: "Hợp nhất nhiều tập tin thành một"
      content: "Kết hợp liền mạch nhiều tệp PDF, Office và các tệp khác vào một tài liệu duy nhất."
    
    # feature loop
    - icon: "settings"
      title: "Thêm sản phẩm và tính năng"
      content: "Khám phá tất cả các bộ API tự động hóa tài liệu GroupDocs: so sánh, hát điện tử, tìm kiếm, hình mờ và hơn thế nữa!"


############################# Code samples ############################
# code_samples:
#   enable: true
#   title: "Mẫu mã GroupDocs.Total"
#   description: "Một số trường hợp sử dụng các thao tác GroupDocs.Total điển hình trong C#, Java, TypeScript"
#   items:
#     # code sample loop
#     - title: "Cách hiển thị tệp DOCX thành PDF"
#       content: |
#        Hiển thị tài liệu DOCX thành PDF mà không cần cài đặt Microsoft Word hoặc phần mềm khác. Dễ dàng tải và xem các tệp DOCX trong ứng dụng của bạn, cho dù đó là ứng dụng web hay máy tính để bàn. Dưới đây là ví dụ về cách hiển thị tệp DOCX thành PDF:
#       samples:
#         - language: "C#"
#           color: "blue"
#           content: |
#             ```csharp {style=abap}   
#             // Tải tệp DOCX để kết xuất
#             using (Viewer viewer = new Viewer("sample.docx"))
#             {
#               // Kết xuất DOCX thành tệp PDF
#               PdfViewOptions viewOptions = new PdfViewOptions();
#               viewer.View(viewOptions);
#             }
#             ```
#         - language: "Java"
#           color: "red"
#           content: |
#             ```java {style=abap}   
#             import com.groupdocs.viewer.Viewer;
#             import com.groupdocs.viewer.options.PdfViewOptions;
#             // ...
#             // Tải tệp DOCX để kết xuất
#             try (Viewer viewer = new Viewer("sample.docx")) {
#                 // Kết xuất DOCX thành tệp PDF
#                 PdfViewOptions viewOptions = new PdfViewOptions();
#                 viewer.view(viewOptions);
#             }
#             ```
#         - language: "TypeScript"
#           color: "green"
#           content: |
#             ```javascript {style=abap}  
#             // Tải tệp DOCX để kết xuất
#             const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
#             // Kết xuất DOCX thành tệp PDF
#             const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
#             viewer.view(viewOptions)
#             ```


############################# Formats ############################
formats:
  enable: true
  title:  "Hơn 200 định dạng tệp được hỗ trợ"
  description: "GroupDocs.Total hỗ trợ các thao tác với  phổ biến nhất [định dạng tệp](https://docs.groupdocs.com/total/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "Số liệu chuyên sâu và hiểu biết thống kê"
  description: "Đi sâu vào phân tích chi tiết về các số liệu quan trọng của chúng tôi, cung cấp số liệu toàn diện và thông tin thống kê chuyên sâu về thành tích, tác động và sự phát triển của chúng tôi."

  items:
    # metrics loop
    - number: "200+"
      title: "Các định dạng được hỗ trợ"
      content: "Dễ dàng xem hơn 200 định dạng tệp bao gồm tài liệu, hình ảnh và bản vẽ CAD một cách dễ dàng. Phá vỡ các rào cản tương thích và truy cập các tệp đa dạng một cách dễ dàng bằng giải pháp xem toàn diện của chúng tôi."
    # metrics loop
    - number: "550K"
      title: "Tải xuống NuGet"
      content: "Giải pháp gói NuGet của chúng tôi đã trở thành tài nguyên đáng tin cậy và được áp dụng rộng rãi trong cộng đồng nhà phát triển, cung cấp khả năng tích hợp liền mạch và chức năng có giá trị cho vô số dự án."

    # metrics loop
    - number: "10+"
      title: "Thư viện"
      content: "Sản phẩm của chúng tôi bao gồm hơn 10 thư viện, cung cấp các tính năng nâng cao để tối ưu hóa hiệu suất. Những thư viện này được thiết kế để đáp ứng các nhu cầu phát triển khác nhau với khả năng tuyệt vời."
    
    # metrics loop
    - number: "100+"
      title: "Khách hàng hạnh phúc"
      content: "Phục vụ các thương hiệu mang tính biểu tượng nhất trên toàn cầu. Khám phá lý do tại sao hàng trăm người yêu thích GroupDocs.Total! Khám phá khả năng điều hướng liền mạch, cộng tác thuận tiện và tính dễ sử dụng chưa từng có. Tham gia ngay!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Khách hàng hạnh phúc của chúng tôi"
  description: "Thư viện GroupDocs được các thương hiệu nổi tiếng và nổi tiếng trên toàn thế giới sử dụng."

  items:
    # customers loop
    - title: "BenQ Corporation"
      logo: "benq"
    # customers loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
    # customers loop
    - title: "AT&T Inc."
      logo: "att"
    # customers loop
    - title: "AstraZeneca"
      logo: "astrazeneca"
    # customers loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
    # customers loop
    - title: "Roche Holding AG"
      logo: "roche"
    # customers loop
    - title: "Capita"
      logo: "capita"
    # customers loop
    - title: "Axa S.A."
      logo: "axa"
    # customers loop
    - title: "Instructure Inc."
      logo: "instructure"
     # customers loop
    - title: "Wipro"
      logo: "wipro"



############################# Actions ############################

actions:
  enable: true
  title: "Sẵn sàng để bắt đầu?"
  description: "Dùng thử miễn phí các tính năng của GroupDocs.Total hoặc yêu cầu giấy phép"

  items:
    #  loop
    - title: ".NET"
      link: "/total/net/"
      color: "blue"
        #  loop
    - title: "Java"
      link: "/total/java/"
      color: "red"


############################# Faq ############################

faq:
  enable: true
  title: "Các câu hỏi và mối quan tâm thường gặp"
  description: "Tìm câu trả lời cho các câu hỏi thường gặp trong phần Câu hỏi thường gặp của chúng tôi để nhanh chóng giải quyết các thắc mắc và mối quan tâm của bạn."

  items:
    #  loop
    - question: "GroupDocs.Total là gì và nó khác với các sản phẩm GroupDocs khác như thế nào?"
      answer: |
        GroupDocs.Total là một bộ toàn diện kết hợp các chức năng của tất cả các sản phẩm GroupDocs riêng lẻ thành một gói duy nhất. Điều này mang lại một số lợi thế: <br><br>
        <ul>
          <li>
            <b>Tính năng hợp nhất:</b> Bạn có quyền truy cập vào tất cả các khả năng xử lý tài liệu, bao gồm xem, chuyển đổi, hợp nhất, chú thích, ký và hơn thế nữa, trong một API duy nhất. <br><br>
          </li>
          <li>
            <b>Khả năng tương thích nâng cao:</b> GroupDocs.Total đảm bảo hiệu suất nhất quán và đáng tin cậy trên tất cả các định dạng và nền tảng tệp được hỗ trợ, loại bỏ các vấn đề tương thích có thể phát sinh khi sử dụng các sản phẩm riêng biệt. <br><br>
          </li>
          <li>
            <b>Kích thước gói được tối ưu hóa:</b> Bộ phần mềm này được cung cấp dưới dạng một gói nhỏ gọn, giảm mức tiêu thụ tài nguyên và đơn giản hóa việc tích hợp vào các ứng dụng của bạn so với việc sử dụng các sản phẩm riêng lẻ với các cài đặt riêng biệt.
          </li>
        <ul>

    #  loop
    - question: "Tại sao nên ưu tiên GroupDocs.Total thay vì mua từng sản phẩm GroupDocs riêng lẻ?"
      answer: |
        Mua một giấy phép GroupDocs.Total thường có giá thấp hơn so với mua giấy phép cho hai hoặc nhiều sản phẩm GroupDocs riêng lẻ. <br>
        Điều này mang lại một số lợi ích chính cho bạn: <br><br>
        <b>Tiết kiệm chi phí:</b> GroupDocs.Total cung cấp mức giảm giá đáng kể so với việc mua từng sản phẩm riêng lẻ, cho phép bạn kéo dài ngân sách của mình hơn nữa. <br><br>
        <b>Quản lý đơn giản hóa:</b> Với GroupDocs.Total, bạn quản lý mọi thứ theo một giấy phép, loại bỏ nhu cầu theo dõi và duy trì nhiều giấy phép cho các sản phẩm khác nhau. Điều này giúp đơn giản hóa các nhiệm vụ quản trị của bạn và giảm chi phí tổng thể. <br><br>
        Nếu bạn đang tìm kiếm một giải pháp tiết kiệm chi phí và giàu tính năng cho nhu cầu quản lý tài liệu của mình thì GroupDocs.Total là sự lựa chọn hoàn hảo.

    #  loop
    - question: "Làm cách nào để bắt đầu với GroupDocs.Total?"
      answer: |
        Bạn có thể bắt đầu bằng bản dùng thử miễn phí để khám phá các tính năng và xem liệu nó có đáp ứng nhu cầu của bạn hay không. GroupDocs cũng cung cấp nhiều tài nguyên [tài liệu](https://docs.groupdocs.com/total/) và [hướng dẫn](https://groupdocs.github.io) để giúp bạn bắt đầu tích hợp và phát triển.
        
    #  loop
    - question: "GroupDocs.Total có cung cấp bất kỳ hỗ trợ kỹ thuật nào không?"
      answer: |
        Có, GroupDocs cung cấp hỗ trợ kỹ thuật toàn diện để đảm bảo thành công của bạn với GroupDocs.Total. Họ có hai lựa chọn: <br><br>
        <b>[Diễn đàn hỗ trợ miễn phí](https://forum.groupdocs.com):</b> Diễn đàn này cho phép bạn kết nối với nhân viên GroupDocs, những người có thể trả lời câu hỏi của bạn và đưa ra giải pháp dựa trên kinh nghiệm của họ. Đó là một nguồn tài nguyên tuyệt vời cho các vấn đề chung và các câu hỏi chung. <br><br>
        <b>[Bộ phận trợ giúp hỗ trợ trả phí](https://helpdesk.groupdocs.com):</b> Tùy chọn này cung cấp hỗ trợ trên cơ sở ưu tiên. Nếu bạn gặp phải các vấn đề phức tạp hoặc yêu cầu giải pháp nhanh hơn, dịch vụ hỗ trợ có trả phí sẽ cung cấp hỗ trợ được cá nhân hóa và thời gian phản hồi nhanh hơn. <br><br>
        Bằng cách cung cấp cả tùy chọn miễn phí và trả phí, GroupDocs đáp ứng các nhu cầu và ngân sách khác nhau, đảm bảo bạn có được sự hỗ trợ cần thiết để phát triển mạnh mẽ với GroupDocs.Total.

    #  loop
    - question: "GroupDocs.Total có yêu cầu phần mềm bổ sung để thao tác tài liệu không?"
      answer: |
        GroupDocs.Total là một bộ ứng dụng độc lập và không yêu cầu bất kỳ phần mềm bổ sung nào của bên thứ ba cho các tác vụ thao tác tài liệu cơ bản như xem, chuyển đổi, chú thích hoặc ký. Tuy nhiên, tùy thuộc vào các tính năng cụ thể mà bạn sử dụng (ví dụ: OCR cho tài liệu được quét), có thể cần có các thư viện bên ngoài.

############################# Cloud and Apps ############################

cloud_links:
  enable: true
  title: "Giải pháp GroupDocs.Total"
  description: "Tăng cường xử lý tài liệu trong ứng dụng của bạn với API REST trên đám mây và các ứng dụng trực tuyến miễn phí của chúng tôi"

  items:
    #  loop
    - icon: "groupdocs_total-cloud"
      title: "GroupDocs.Total Cloud"
      link: "https://products.groupdocs.cloud/total"
      content: "Các giải pháp đám mây mạnh mẽ để tự động hóa hiệu quả việc xử lý Microsoft Office, tài liệu PDF trong ứng dụng của bạn."

    #  loop
    - icon: "groupdocs_total-apps"
      title: "GroupDocs.Total Online Apps"
      link: "https://products.groupdocs.app"
      content: "Các ứng dụng web trực tuyến miễn phí để xem và chỉnh sửa nội dung tài liệu, so sánh và hợp nhất các Microsoft Office, OpenOffice, hình ảnh và các định dạng tệp phổ biến khác."    

    #  loop
    - icon: "groupdocs_total-windows"
      title: "GroupDocs.Total Windows"
      link: "https://products.groupdocs.app/total/windows"
      content: "Ứng dụng ngoại tuyến để chuyển đổi, chú thích, so sánh, ký tên, tập hợp, phân tích cú pháp, phân loại, biên tập và tìm kiếm tài liệu trên bất kỳ hệ điều hành nào."   

---