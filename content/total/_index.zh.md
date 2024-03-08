---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Total"
product_tag: "total"

############################# Head ############################
head_title: "文档自动化 API |本地 API 和在线服务"
head_description: "轻松、免费地自动化您的文档操作"

############################# Header ##########################
title: "通过一体化套件掌握文档自动化"
description: |
  只需几行代码即可简化重复的文档任务并简化您的工作流程。强大的 API 使集成变得毫不费力，使您能够专注于创新，而不是基础设施。

  转换、签名、查看、注释 - 用最少的代码完成任何文档任务。从 Word 到 PDF、Excel 到图像，无缝处理一切。代码更少，影响更大。

  自动执行文档任务、提高效率并通过闪电般的集成速度快速推进。节省时间和资源，专注于对您的业务真正重要的事情。

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "选择您的平台"
  title: "支持的平台"
  description: "GroupDocs.Total 库支持以下操作系统和框架"
  details_link_title: "了解更多"
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
        - content: "200 多种文件格式"
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
        - content: "200 多种文件格式"
          rows: "1"
        # features loop
        - content:  "Eclipse <br> NetBeans <br> IntelliJ Idea"
          rows: "3"

############################# Features ############################

features:
  enable: true
  title: "GroupDocs.Total 的功能集"
  description: "单一解决方案将所有单独的 GroupDocs 产品的功能统一在一个屋檐下，无需第三方软件即可管理任何文档任务。"

  items:
    # feature loop
    - icon: "view"
      title: "查看文档和图像"
      content: "渲染文件以 HTML、PDF、PNG 和 JPEG 格式查看。"

    # feature loop
    - icon: "convert"
      title: "格式之间转换"
      content: "将文件从不同源转换为各种目标格式。"

    # feature loop
    - icon: "merge"
      title: "将多个文件合并为一个"
      content: "将多个 PDF、Office 等无缝合并到一个文档中。"
    
    # feature loop
    - icon: "settings"
      title: "更多产品和功能"
      content: "探索所有 GroupDocs 文档自动化 API 集：比较、电子唱、搜索、水印等等！"


############################# Code samples ############################
# code_samples:
#   enable: true
#   title: "GroupDocs.代码示例总数"
#   description: "C#、Java、TypeScript 中典型 GroupDocs.Total 操作的一些用例"
#   items:
#     # code sample loop
#     - title: "如何将 DOCX 文件渲染为 PDF"
#       content: |
#        将 DOCX 文档渲染为 PDF，无需安装 Microsoft Word 或其他软件。在您的应用程序中轻松加载和查看 DOCX 文件，无论是 Web 应用程序还是桌面应用程序。以下是如何将 DOCX 文件呈现为 PDF 的示例：
#       samples:
#         - language: "C#"
#           color: "blue"
#           content: |
#             ```csharp {style=abap}   
#             // 加载 DOCX 文件进行渲染
#             using (Viewer viewer = new Viewer("sample.docx"))
#             {
#               // 将 DOCX 渲染为 PDF 文件
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
#             // 加载 DOCX 文件进行渲染
#             try (Viewer viewer = new Viewer("sample.docx")) {
#                 // 将 DOCX 渲染为 PDF 文件
#                 PdfViewOptions viewOptions = new PdfViewOptions();
#                 viewer.view(viewOptions);
#             }
#             ```
#         - language: "TypeScript"
#           color: "green"
#           content: |
#             ```javascript {style=abap}  
#             // 加载 DOCX 文件进行渲染
#             const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
#             // 将 DOCX 渲染为 PDF 文件
#             const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
#             viewer.view(viewOptions)
#             ```


############################# Formats ############################
formats:
  enable: true
  title:  "支持 200 多种文件格式"
  description: "GroupDocs.Total 支持最流行的的操作[文件格式](https://docs.groupdocs.com/total/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "深入的指标和统计见解"
  description: "深入了解我们的关键数据的详细分类，提供有关我们的成就、影响和增长的全面指标和统计见解。"

  items:
    # metrics loop
    - number: "200+"
      title: "支持的格式"
      content: "轻松轻松地查看 200 多种文件格式，包括文档、图像和 CAD 绘图。借助我们全面的查看解决方案，打破兼容性障碍并轻松访问各种文件。"
    # metrics loop
    - number: "550K"
      title: "NuGet 下载"
      content: "我们的 NuGet 包解决方案已成为开发人员社区中值得信赖且广泛采用的资源，为无数项目提供无缝集成和有价值的功能。"

    # metrics loop
    - number: "10+"
      title: "图书馆"
      content: "我们的产品包括 10 多个库，提供先进的功能来优化性能。这些库旨在以无与伦比的功能满足不同的开发需求。"
    
    # metrics loop
    - number: "100+"
      title: "快乐的顾客"
      content: "为全球最具标志性的品牌提供服务。了解为什么数百人喜欢 GroupDocs.Total！探索无缝导航、便捷协作和无与伦比的易用性。立即加入！"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "我们满意的客户"
  description: "GroupDocs 库被世界各地的全球知名和杰出品牌所采用。"

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
  title: "准备好开始了吗？"
  description: "免费试用 GroupDocs.Total 功能或申请许可证"

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
  title: "常见问题和疑虑"
  description: "在我们的常见问题解答部分查找常见问题的答案，以快速解决您的疑问和疑虑。"

  items:
    #  loop
    - question: "什么是 GroupDocs.Total，它与其他 GroupDocs 产品有何不同？"
      answer: |
        GroupDocs.Total 是一个综合套件，它将所有单独的 GroupDocs 产品的功能组合到一个包中。这有几个优点: <br><br>
        <ul>
          <li>
            <b>统一功能:</b> 您可以在单个 API 中访问所有文档处理功能，包括查看、转换、合并、注释、签名等。 <br><br>
          </li>
          <li>
            <b>增强兼容性:</b> GroupDocs.Total 可确保在所有受支持的文件格式和平台上保持一致且可靠的性能，从而消除使用单独产品时可能出现的兼容性问题。 <br><br>
          </li>
          <li>
            <b>优化的封装尺寸:</b> 该套件作为一个紧凑的软件包提供，与使用单独安装的单个产品相比，可减少资源消耗并简化与应用程序的集成。
          </li>
        <ul>

    #  loop
    - question: "为什么更喜欢 GroupDocs.Total 而不是购买单独的 GroupDocs 产品？"
      answer: |
        购买单个 GroupDocs.Total 许可证的成本通常低于购买两个或多个单独的 GroupDocs 产品的许可证。 <br>
        这将为您带来几个关键的好处: <br><br>
        <b>节约成本:</b> 与购买单个产品相比，GroupDocs.Total 提供大幅折扣，让您进一步节省预算。 <br><br>
        <b>简化管理:</b> 借助 GroupDocs.Total，您可以在一份许可证下管理所有内容，从而无需跟踪和维护不同产品的多个许可证。这简化了您的管理任务并降低了总体成本。 <br><br>
        如果您正在寻找一个经济高效且功能丰富的解决方案来满足您的文档管理需求，那么 GroupDocs.Total 是您的完美选择。

    #  loop
    - question: "如何开始使用 GroupDocs.Total？"
      answer: |
        您可以从免费试用开始，探索这些功能并看看它是否满足您的需求。 GroupDocs 还提供各种[文档](https://docs.groupdocs.com/total/)资源和[教程](https://groupdocs.github.io)来帮助您开始集成和开发。
        
    #  loop
    - question: "GroupDocs.Total 提供任何技术支持吗？"
      answer: |
        是的，GroupDocs 提供全面的技术支持，以确保您成功使用 GroupDocs.Total。他们有两个选择: <br><br>
        <b>[免费支持论坛](https://forum.groupdocs.com):</b> 通过该论坛，您可以与 GroupDocs 工作人员联系，他们可以回答您的问题并根据他们的经验提供解决方案。这是解决常见问题和一般查询的绝佳资源。 <br><br>
        <b>[付费支持服务台](https://helpdesk.groupdocs.com):</b> 此选项提供优先支持。如果您遇到复杂的问题或需要更快的解决方案，付费支持可以提供个性化的帮助和更快的响应时间。 <br><br>
        通过提供免费和付费选项，GroupDocs 可满足不同的需求和预算，确保您获得通过 GroupDocs.Total 蓬勃发展所需的支持。

    #  loop
    - question: "GroupDocs.Total 是否需要额外的软件来进行文档操作？"
      answer: |
        GroupDocs.Total 是一个独立的套件，不需要任何额外的第三方软件来执行基本的文档操作任务，例如查看、转换、注释或签名。但是，根据您使用的特定功能（例如扫描文档的 OCR），可能需要外部库。

############################# Cloud and Apps ############################

cloud_links:
  enable: true
  title: "GroupDocs.整体解决方案"
  description: "使用我们的云 REST API 和免费在线应用程序增强应用程序中的文档处理能力"

  items:
    #  loop
    - icon: "groupdocs_total-cloud"
      title: "GroupDocs.Total Cloud"
      link: "https://products.groupdocs.cloud/total"
      content: "强大的云解决方案可在您的应用程序中高效地自动化处理 Microsoft Office、PDF 文档。"

    #  loop
    - icon: "groupdocs_total-apps"
      title: "GroupDocs.Total Online Apps"
      link: "https://products.groupdocs.app"
      content: "免费的在线网络应用程序，用于查看和编辑文档内容，比较和合并不同的 Microsoft Office、OpenOffice、图像和其他流行的文件格式。"    

    #  loop
    - icon: "groupdocs_total-windows"
      title: "GroupDocs.Total Windows"
      link: "https://products.groupdocs.app/total/windows"
      content: "离线应用程序可在任何操作系统上转换、注释、比较、签名、组装、解析、分类、编辑和搜索文档。"   

---