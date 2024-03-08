---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: vi
product: "Total"
product_tag: "total"
platform: ".NET"
platform_tag: "net"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
      
############################# Head ############################
head_title: "Thư viện tự động hóa tài liệu tất cả trong một cho các ứng dụng .NET"
head_description: "GroupDocs.Total for .NET là bộ API tự động hóa tài liệu tất cả trong một dành cho các nhà phát triển .NET, cung cấp một bộ công cụ toàn diện để làm việc với nhiều định dạng tài liệu khác nhau, bao gồm PDF, Word, Excel, Hình ảnh, HTML, Sơ đồ, v.v. ."

############################# Header ##########################
title: "Hợp lý hóa việc tự động hóa tài liệu<br> trong ứng dụng .NET của bạn"
description: "Mở khóa tự động hóa tài liệu: chuyển đổi, xem và so sánh, chỉnh sửa và ký giữa hơn 200 định dạng một cách dễ dàng."
words:
  for: "for"

actions:
  main: "Tải xuống NuGet miễn phí"
  main_link: "https://www.nuget.org/packages/GroupDocs.Total"
  alt: "Cấp phép"
  alt_link: "https://purchase.groupdocs.com/pricing/total/net"
  title: "Sẵn sàng để bắt đầu?"
  description: "Dùng thử miễn phí các tính năng của GroupDocs.Total hoặc yêu cầu giấy phép"

release:
  title: "Đã phát hành phiên bản {0}"
  notes: "Xem có gì mới"
  downloads: "Tải xuống"
  link: "https://releases.groupdocs.com/total/net/release-notes/latest/"

code:
  title: "Hợp nhất và xem các tệp Word trong C#"
  more: "Thêm ví dụ"
  more_link: "https://github.com/groupdocs-total/GroupDocs.Total-for-.NET"
  install: "dotnet add package GroupDocs.Total"
  content: |
    ```csharp {style=abap} 
    // Tải tệp DOCX nguồn
    using (Merger merger = new Merger("sample1.docx"))
    {
        // Thêm một tệp DOCX khác để hợp nhất
        merger.Join("sample2.docx");

        // Hợp nhất các tệp DOCX và lưu kết quả
        merger.Save("merged.docx");
    }

    // Tải tệp DOCX đã hợp nhất vào trình xem
    using (var viewer = new Viewer("merged.docx"))
    {
        // Đặt tùy chọn HTML đầu ra, một tệp trên mỗi trang
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // Kết xuất DOCX sang HTML bằng tài nguyên được nhúng        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "Sơ lược về GroupDocs.Total"
  description: "Tự động xem tệp, chuyển đổi, chỉnh sửa, so sánh, tìm kiếm, đóng dấu hình mờ và các quy trình công việc khác trong ứng dụng .NET"
  features:
    # feature loop
    - title: "Kết hợp sức mạnh của nhiều sản phẩm GroupDocs thành một giải pháp toàn diện, duy nhất"
      content: | 
        Bạn có thể sử dụng các tính năng của các sản phẩm GroupDocs khác nhau để tạo ra phương pháp tùy chỉnh đáp ứng nhu cầu cụ thể của mình.
        <br><br>
        Ví dụ: bạn có thể chuyển đổi tệp Word thành PDF rồi thêm chữ ký điện tử. Hoặc điền dữ liệu mẫu tài liệu từ cơ sở dữ liệu hoặc trích xuất văn bản từ hình ảnh rồi dịch nó sang ngôn ngữ khác.
        <br><br>
        Khả năng là vô tận!
          
    # feature loop
    - title: "Nắm vững sự đa dạng của các định dạng tập tin"
      content: "GroupDocs.Total for .NET mở ra khả năng tương thích với hơn 200 định dạng tệp, cho phép bạn xử lý tất cả các loại tài liệu phổ biến. Từ các định dạng văn phòng như Word và Excel đến hình ảnh, mã và tệp được mã hóa, chúng tôi đều hỗ trợ bạn."

    # feature loop
    - title: "Hỗ trợ đa nền tảng"
      content: "Giải phóng bản thân khỏi những hạn chế của nền tảng. GroupDocs.Total cung cấp khả năng tương thích đa nền tảng, cho phép bạn cung cấp hiệu suất tối ưu và tính khả dụng của giải pháp cho người dùng trên bất kỳ hệ thống nào có thể cài đặt .NET."

############################# Platforms ############################
platforms:
  enable: true
  title: "Nền tảng độc lập"
  description: "GroupDocs.Total for .NET hỗ trợ các hệ điều hành, khung và trình quản lý gói sau"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "Các định dạng tập tin được hỗ trợ"
  description: |
    GroupDocs.Total for .NET hỗ trợ các thao tác với sau [định dạng tệp](https://docs.groupdocs.com/total/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument và các định dạng văn bản
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE
        * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG
        * **Fixed Page Layout:** PDF, TEX, XPS, OXPS
        * **e-Books:** EPUB, MOBI, DjVu
        * **Delimiter-Separated Values:** CSV, TSV
    # group loop
    - color: "blue"
      content: |
        ### Hình ảnh, Đồ họa & Sơ đồ
        * **Hình ảnh raster:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
        * **Windows Icon:** ICO
        * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ        
        * **Adobe Photoshop:** PSD, PSB        
        * **Stereo Lithography (3D Printing):** STL        
        * **Medical Imaging:** DICOM
        * **Plotter Documents:** PLT, HPG
        * **Autodesk Design Web Formats:** DWF, DWG
        * **AutoCAD Drawing:** DWT, IFC, STL, CF2        
      # group loop
    - color: "red"
      content: |
        ### Khác        
        * **Web:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Lưu trữ:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Khác:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Các tính năng của GroupDocs.Total"
  description: "Quản lý, kết xuất và chuyển đổi toàn diện các tệp PDF và Tài liệu Office"

  items:
    # feature loop
    - icon: "viewer"
      title: "Xem tập tin mở rộng"
      content: "Xem tài liệu toàn diện với hơn 180 định dạng, bao gồm HTML, hình ảnh và PDF."

    # feature loop
    - icon: "conversion"
      title: "Chuyển đổi định dạng"
      content: "Chuyển đổi liền mạch giữa các định dạng tài liệu khác nhau mà không cần công cụ bên ngoài."

    # feature loop
    - icon: "annotation"
      title: "Chú thích tương tác"
      content: "Khả năng chú thích nâng cao cho các thành phần văn bản và hình ảnh trong tài liệu."

    # feature loop
    - icon: "comparison"
      title: "So sánh nội dung"
      content: "So sánh tài liệu chính xác, làm nổi bật sự khác biệt về nội dung và phong cách."

    # feature loop
    - icon: "signature"
      title: "Tính linh hoạt của chữ ký"
      content: "Tùy chọn chữ ký đa năng, bao gồm chữ ký văn bản, hình ảnh và chữ ký số."

    # feature loop
    - icon: "assembly"
      title: "Tạo tài liệu dựa trên mẫu"
      content: "Tạo tài liệu tự động từ các mẫu và nguồn dữ liệu bên ngoài."

    # feature loop
    - icon: "metadata"
      title: "Quản lý siêu dữ liệu"
      content: "Truy cập và thao tác siêu dữ liệu mạnh mẽ để tăng cường kiểm soát tài liệu."

    # feature loop
    - icon: "search"
      title: "tìm kiếm nâng cao"
      content: "Chức năng tìm kiếm mạnh mẽ với sự hỗ trợ cho các thuật toán mờ và đồng nghĩa."

    # feature loop
    - icon: "watermark"
      title: "Kiểm soát hình mờ"
      content: "Quản lý hình mờ tài liệu dễ dàng, cung cấp các tính năng tùy chỉnh và trích xuất."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Mẫu mã"
  description: "Một số tình huống thực tế của GroupDocs.Total khi sử dụng .NET"
  items:
    # code sample loop
    - title: "Bảo mật và sắp xếp hợp đồng: Áp dụng hình mờ và quản lý siêu dữ liệu trong tệp DOCX"
      content: |
        Bảo vệ và sắp xếp tài liệu Word của bạn một cách hiệu quả bằng ví dụ về mã toàn diện này. Mẫu bên dưới cho phép bạn triển khai tính năng quản lý siêu dữ liệu và hình mờ mạnh mẽ trong quy trình làm việc theo hợp đồng của bạn để tăng cường quản lý thông tin và bảo mật. Nó trình bày cách: <br><br>
        <b>Áp dụng hình mờ tùy chỉnh:</b> Thêm hình mờ 'Dự thảo hợp đồng' nổi bật vào tài liệu để có hình ảnh rõ ràng và bảo vệ. [Tùy chỉnh hình mờ](https://docs.groupdocs.com/watermark/net/basic-usage/customize/) với các tùy chọn phông chữ, màu sắc, độ mờ và căn chỉnh. <br><br>
        <b>Nâng cao siêu dữ liệu:</b> Dễ dàng [sửa đổi siêu dữ liệu tài liệu](https://docs.groupdocs.com/metadata/net/working-with-metadata-in-wordprocessing-documents/) để bao gồm các chi tiết cần thiết như tác giả, thời gian tạo, công ty, danh mục và từ khóa để cải thiện tổ chức và khả năng tìm kiếm.
       
        {{< landing/code title="C#">}}
        ```csharp {style=abap}  
        using GroupDocs.Metadata;
        using GroupDocs.Watermark;
        using GroupDocs.Watermark.Common;
        using GroupDocs.Watermark.Watermarks;
        
        // Tải tài liệu của bạn vào hình mờ
        using (Watermarker watermarker = new Watermarker("contract.docx"))
        {
            // Đặt văn bản và phông chữ mong muốn cho hình mờ
            TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 60, FontStyle.Bold));
            
            // Chọn màu phông chữ và độ mờ văn bản, xoay và căn chỉnh
            watermark.ForegroundColor = Color.DarkGreen;
            watermark.Opacity = 0.5;
            watermark.HorizontalAlignment = HorizontalAlignment.Center;
            watermark.VerticalAlignment = VerticalAlignment.Center;
            
            // Áp dụng hình mờ
            watermarker.Add(watermark);
            
            // Lưu tài liệu kết quả
            watermarker.Save("watermarked-contract.docx");
        }

        using (Metadata metadata = new Metadata("watermarked-contract.docx"))
        {
          var root = metadata.GetRootPackage<WordProcessingRootPackage>();

          // Cập nhật thuộc tính siêu dữ liệu tài liệu
          root.DocumentProperties.Author = "Name Surname";
          root.DocumentProperties.CreatedTime = DateTime.Now;
          root.DocumentProperties.Company = "Company Name";
          root.DocumentProperties.Category = "Work materials";
          root.DocumentProperties.Keywords = "contract, watermarked";

          // Lưu tài liệu với siêu dữ liệu được cập nhật
          metadata.Save("contract-final.docx");
        }        
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Sắp xếp hợp lý tài liệu"
      content: |
        <b>Kịch bản:</b> Một công ty luật lớn thường xuyên xử lý các tài liệu đa dạng chứa thông tin bí mật của khách hàng phải được biên tập lại trước khi chia sẻ với bên thứ ba hoặc để tiết lộ công khai. Việc biên tập lại thông tin nhạy cảm này theo cách thủ công có thể tẻ nhạt, tốn thời gian và dễ xảy ra lỗi của con người. Để đảm bảo tính hiệu quả, chính xác và tuân thủ các quy định bảo vệ dữ liệu, công ty pháp lý tìm kiếm giải pháp tự động để hợp lý hóa quy trình biên tập tài liệu. 
        
        <br>

        <b>Giải pháp:</b>
        GroupDocs.Total tự động hóa quy trình, kích hoạt chỉnh sửa khi nhận được tài liệu. Hơn nữa, [tùy chọn linh hoạt](https://docs.groupdocs.com/redaction/net/text-redactions/) cho phép tùy chỉnh bằng cách cho phép bạn đặt quy tắc, chọn chế độ biên tập (ví dụ: tắt, thay thế bằng dấu hoa thị) và chỉ định các phần hoặc trang cụ thể để biên tập. Cuối cùng, [đầu ra thân thiện với người dùng](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) tạo ra các tài liệu đã được biên tập lại ở định dạng PDF để dễ dàng chia sẻ và xem xét, đồng thời khả năng kiểm tra và bảo mật nâng cao đảm bảo toàn bộ quy trình được ghi lại để tuân thủ và chịu trách nhiệm. 
        <br><br>
        Giải pháp toàn diện này trao quyền cho các chuyên gia pháp lý và các tổ chức khác giảm đáng kể thời gian và chi phí soạn thảo, giảm thiểu lỗi của con người và xử lý thông tin nhạy cảm một cách nhất quán một cách tự tin.        
              
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Redaction;
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;

        // Tải tài liệu có dữ liệu riêng tư vào trình chỉnh sửa 
        using (Redactor redactor = new Redactor("customer-info.docx"))
        {
          // Thiết lập và tùy chỉnh các tùy chọn biên tập 
          redactor.Apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
          // Áp dụng các chỉnh sửa và lưu kết quả 
          redactor.Save();
        }

        // Tải tệp đã được biên tập lại để xem xét 
        using (var viewer = new Viewer("customer-info.docx"))
        {
          // Thiết lập PDF như định dạng xem mong muốn       
          var viewOptions = new PdfViewOptions("redacted-info.pdf");

          // Lưu tài liệu thành PDF      
          viewer.View(viewOptions);
        }
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Đánh giá sản phẩm GroupDocs"
# description: "Đừng chỉ tin lời chúng tôi. Xem những nhà phát triển khác nói gì về API của chúng tôi"

# items:
#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Dịch vụ tuyệt vời và sản phẩm tuyệt vời. Chúng cực kỳ hữu ích và phản hồi nhanh trong quá trình triển khai GroupDocs.Viewer cho .NET, không thể giới thiệu chúng đủ cao."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Sau khi triển khai và sử dụng GroupDocs.Viewer cho Java trong dự án, có vẻ như nó hoạt động rất tốt. Tôi đã thử nghiệm với rất nhiều tài liệu và cho đến nay vẫn tốt. Mọi thứ tôi đưa vào nó đều hiển thị độc đáo và trông đẹp như trong trình xem PDF hoặc MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---