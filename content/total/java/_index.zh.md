---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: zh
product: "Total"
product_tag: "total"
platform: "Java"
platform_tag: "java"

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
head_title: "适用于 Java 应用程序的一体化文档自动化套件"
head_description: "GroupDocs.Total for Java 是一个为 Java 开发人员量身定制的综合文档自动化库，提供广泛的功能来处理不同的文档格式，例如 PDF、Word、Excel、图像、HTML、图表等。"

############################# Header ############################
title: "简化 Java 项目中的文档自动化<br>"
description: "增强文档自动化功能：轻松转换、查看、比较、编辑和签署 200 多种文件格式。"
words:
  for: "for"

actions:
  main: "免费 Maven 下载"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-total/"
  alt: "许可"
  alt_link: "https://purchase.groupdocs.com/pricing/total/java"
  title: "准备好开始了吗？"
  description: "免费试用 GroupDocs.Total 功能或申请许可证"

release:
  title: "版本 {0} 已发布"
  notes: "看看有什么新鲜事"
  downloads: "下载"
  link: "https://releases.groupdocs.com/total/java/release-notes/latest/"

code:
  title: "在 Java 中合并和查看 Word 文件"
  more: "更多示例"
  more_link: "https://github.com/groupdocs-total/GroupDocs.Total-for-Java"
  install: |
    <dependencies>
      <dependency>
        <groupId>com.groupdocs</groupId>
        <artifactId>groupdocs-total</artifactId>
        <version>{0}</version>
      </dependency>
    </dependencies>

    <repositories>
      <repository>
        <id>repository.groupdocs.com</id>
        <name>GroupDocs Repository</name>
        <url>https://repository.groupdocs.com/repo/</url>
      </repository>
    </repositories>
  content: |
    ```java {style=abap}
    // 加载源 DOCX 文件 
    Merger merger = new Merger("sample1.docx");
    
    // 添加另一个 DOCX 文件进行合并
    merger.join("sample2.docx");

    // 合并 DOCX 文件并保存结果
    merger.save("merged.docx");
    
    // 将合并的 DOCX 文件加载到查看器中
    try (Viewer viewer = new Viewer("merged.docx"))
    {
      // 设置输出 HTML 选项，每页一个文件
      HtmlViewOptions viewOptions =   
      HtmlViewOptions.forEmbeddedResources("page{0}.html");
          
      // 使用嵌入资源将 DOCX 渲染为 HTML        
      viewer.view(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Total 一目了然"
  description: "在 Java 应用程序中自动执行文件查看、转换、编辑、比较、搜索、水印和其他工作流程"
  features:
    # feature loop
    - title: "将多个 GroupDocs 产品的强大功能结合到一个综合解决方案中"
      content: | 
        您可以使用不同 GroupDocs 产品的功能来创建满足您特定需求的定制方法。
        <br><br>
        例如，您可以将 Word 文件转换为 PDF，然后添加数字签名。或者从数据库填充文档模板数据，或者从图像中提取文本，然后将其翻译成另一种语言。
        <br><br>
        可能性是无止境！
          
    # feature loop
    - title: "掌握文件格式的多样性"
      content: "GroupDocs.Total for Java 解锁了与 200 多种文件格式的兼容性，使您能够处理所有流行类型的文档。从 Word 和 Excel 等办公格式到图像、代码和加密文件，我们都能满足您的需求。"

    # feature loop
    - title: "跨平台支持"
      content: "摆脱平台限制。 GroupDocs.Total 提供跨平台兼容性，允许您在任何可以安装 Java 的系统上为用户提供最佳性能和解决方案可用性。"

############################# Platforms ############################
platforms:
  enable: true
  title: "平台独立性"
  description: "GroupDocs.Total for Java 支持以下操作系统、框架和包管理器"
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
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "Maven"
      image: "maven"


############################# File formats ############################
formats:
  enable: true
  title: "支持的文件格式"
  description: |
    GroupDocs.Total for Java 支持以下[文件格式](https://docs.groupdocs.com/total/java/supported-document-formats/) 的操作。
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office、OpenDocument 和文本格式
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
        ### 图像、图形和图表
        * **光栅图像:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### 其他        
        * **网络:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **档案:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **其他:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Total 总功能"
  description: "全面管理、渲染和转换 PDF 和 Office 文档"

  items:
    # feature loop
    - icon: "viewer"
      title: "广泛的文件查看"
      content: "全面查看 180 多种格式的文档，包括 HTML、图像和 PDF。"

    # feature loop
    - icon: "conversion"
      title: "格式转换"
      content: "各种文档格式之间的无缝转换，无需外部工具。"

    # feature loop
    - icon: "annotation"
      title: "交互式注释"
      content: "针对文档中文本和图像元素的高级注释功能。"

    # feature loop
    - icon: "comparison"
      title: "内容比较"
      content: "精确的文档比较，突出内容和风格的差异。"

    # feature loop
    - icon: "signature"
      title: "签名灵活性"
      content: "多种签名选项，包括文本、图像和数字签名。"

    # feature loop
    - icon: "assembly"
      title: "基于模板的文档创建"
      content: "从模板和外部数据源自动生成文档。"

    # feature loop
    - icon: "metadata"
      title: "元数据管理"
      content: "强大的元数据访问和操作可增强文档控制。"

    # feature loop
    - icon: "search"
      title: "高级搜索"
      content: "强大的搜索功能，支持模糊和同义词算法。"

    # feature loop
    - icon: "watermark"
      title: "水印控制"
      content: "轻松的文档水印管理，提供定制和提取功能。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "代码示例"
  description: "Java 使用 GroupDocs.Total 的一些真实场景"
  items:
    # code sample loop
    - title: "保护和组织合同：应用水印并管理 DOCX 文件中的元数据"
      content: |
        使用此全面的代码示例有效保护和组织您的 Word 文档。下面的示例使您能够在合同工作流程中实施强大的水印和元数据管理，以增强安全性和信息管理。它演示了如何： <br><br>
        <b>应用自定义水印:</b> 在文档中添加显着的“合同草案”水印，以提高视觉清晰度和保护性。 [自定义水印](https://docs.groupdocs.com/watermark/java/adding-text-watermarks/)，包含字体、颜色、不透明度和对齐选项。 <br><br>
        <b>增强元数据:</b> 轻松[修改文档元数据](https://docs.groupdocs.com/metadata/java/working-with-metadata-in-word-processing-documents/)以包含基本详细信息，例如作者、创建时间、公司、类别、和关键字以改进组织和可搜索性。
       
        {{< landing/code title="Java">}}
        ```java {style=abap}  
        import com.groupdocs.metadata.Metadata;
        import com.groupdocs.watermark.Watermark;
        import com.groupdocs.watermark.Watermark.Common;
        import com.groupdocs.watermark.Options.HtmlViewOptions;
        
        // 将文档加载到水印中
        Watermarker watermarker = new Watermarker("contract.docx");
        
        // 设置水印所需的文本和字体
        TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 36));
          
        // 选择字体颜色和文本不透明度、旋转和对齐方式
        watermark.setForegroundColor(Color.getRed());                                                            
        watermark.setHorizontalAlignment(HorizontalAlignment.Center);                                            
        watermark.setVerticalAlignment(VerticalAlignment.Center);                               

        // 应用水印
        watermarker.add(watermark);
        
        // 保存生成的文档
        watermarker.save("watermarked-contract.docx");
        
        Metadata metadata = new Metadata("watermarked-contract.docx");        
        WordProcessingRootPackage root = metadata.getRootPackageGeneric();

        // 更新文档元数据属性
        root.getDocumentProperties().setAuthor("Name Surname");
        root.getDocumentProperties().setCreatedTime(new Date());
        root.getDocumentProperties().setCompany("Company Name");
        root.getDocumentProperties().setCategory("Work materials");
        root.getDocumentProperties().setKeywords("contract, watermarked");

        // 使用更新的元数据保存文档
        metadata.save("contract-final.docx");                
        ```
        {{< /landing/code >}}

    # code sample loop
    - title: "简化的文档编辑"
      content: |
        <b>设想:</b> 大型律师事务所经常处理包含机密客户信息的各种文件，这些文件在与第三方共享或公开披露之前必须进行编辑。手动编辑这些敏感信息可能非常乏味、耗时，而且容易出现人为错误。为了确保效率、准确性并遵守数据保护法规，该律师事务所寻求一种自动化解决方案来简化文档编辑流程。 
        
        <br>

        <b>解决方案:</b>
        GroupDocs.Total 使该过程自动化，在收到文档时触发编辑。此外，[灵活的选项](https://docs.groupdocs.com/redaction/java/text-redactions/)允许您设置规则、选择密文模式（例如，停电、用星号替换）并指定，从而实现自定义需要编辑的特定部分或页面。最后，[用户友好的输出](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) 生成 PDF 格式的编辑文档，以便于共享和审阅，同时增强的安全性和可审核性确保整个过程流程已记录在案，以确保合规性和问责制。 
        <br><br>
        这一全面的解决方案使法律专业人士和其他组织能够显着减少编辑时间和成本，最大限度地减少人为错误，并始终充满信心地处理敏感信息。        
              
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.redaction.Redaction;
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // 将包含私有数据的文档加载到编辑器中 
        Redactor redactor = new Redactor("customer-info.docx");
        
        // 设置和自定义密文选项 
        redactor.apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
        
        // 应用修订并保存结果 
        redactor.save();

        // 加载经过编辑的文件以供审阅 
        Viewer viewer = new Viewer("customer-info.docx");
        
        // 将 PDF 设置为所需的查看格式       
        PdfViewOptions viewOptions = new PdfViewOptions("redacted-info.pdf");

        // 将文档保存为 PDF      
        viewer.view(viewOptions);        
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs 产品评论"
# description: "不要只相信我们的话。看看其他开发人员如何评价我们的 API"

# items:
#   # review loop
#   - title: "GroupDocs.Total"
#     content: "优质的服务和优质的产品。他们在 GroupDocs.Viewer for .NET 实施过程中提供了极大的帮助和响应，强烈推荐他们。"
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Total"
#     content: "在项目中实现并使用 GroupDocs.Viewer for Java 后，它看起来运行得很好。我已经用很多文档进行了测试，到目前为止一切顺利。我扔给它的所有内容都可以很好地呈现，并且看起来与在 PDF 查看器或 MS Word 中一样好。"
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---