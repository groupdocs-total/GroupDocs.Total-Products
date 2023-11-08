---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Total"
product_tag: "total"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "用于查看、转换、注释、签名、自动化、水印、编辑和搜索文件格式的 C# .NET API"
head_description: "GroupDocs .NET 文档操作库和 API。在 .NET 应用程序中使用任何 API 以生成、操作或转换 50 多个文档."

############################# Header ############################
title: ".NET 文档自动化 API"
description: "在 .NET 应用程序中查看、导出、注释、比较、签名、自动化和搜索文档的 API."
button:
    enable: true

############################# SubMenu ############################
submenu:
  enable: true
  
  left:
      img_alt: "GroupDocs.Total for .NET"
      image: "/border/groupdocs-total-net.svg"
      product: "GroupDocs.Total"
      platform: ".NET"

  middle:
      button:
          # button loop
          - link: "#overview"
            text: "概述"

          # button loop
          - link: "#products"
            text: "产品"

          # button loop
          - link: "#features"
            text: "特征"

          # button loop
          - link: "#support"
            text: "Support"

          # button loop
          - link: "https://purchase.groupdocs.com/pricing/total/net"
            text: "价钱"

  right:
      link_download: "https://releases.groupdocs.com/total"
      link_learn: "https://docs.groupdocs.com/total/net/"
      link_buy: "https://purchase.groupdocs.com"

############################# 概述 ############################
overview:
    enable: true
    content: "GroupDocs.Total for .NET 是 GroupDocs 提供的每个 .NET API 的汇编。我们每天对其进行编译，以确保它包含我们每个 .NET 文档操作 API 的最新版本.
    <br><br>借助适用于 .NET 的 GroupDocs.Total，开发人员可以通过单一许可证使用我们所有的 API。但是，您也可以订购任何单独的 API。 "

############################# product ############################

products:
    enable: true
    title: "产品"
    description: "GroupDocs.Total for .NET 包括以下 .NET 文档操作 API："

    product:
        # product loop
        - image: "/border/groupdocs-viewer-net.svg"
          img_alt: "GroupDocs.Viewer for .NET"
          name: "GroupDocs.Viewer for .NET"
          content: "强大的文档查看器 API，用于渲染、查看和显示 50 多种文件格式的文档。全面渲染整个文档，高效渲染部分文档，或渲染特定的页面/单元格范围。渲染单个文档层，带有或不带有支持的文件格式的注释和注释。"
          link: "/viewer/net/"

        # product loop
        - image: "/border/groupdocs-annotation-net.svg"
          img_alt: "GroupDocs.Annotation for .NET"
          name: "GroupDocs.Annotation for .NET"
          content: "注释管理 API 用于创建和操作各种类型的注释，例如区域、文本、折线、点、下划线等。它为您提供了一套全面的标记工具来突出显示、删除线、标记和评论文本和图像.打印带注释的文档或连同注释一起导出为 PDF。"
          link: "/annotation/net/"

          # product loop
        - image: "/border/groupdocs-conversion-net.svg"
          img_alt: "GroupDocs.Conversion for .NET"
          name: "GroupDocs.Conversion for .NET"
          content: "全面的文档转换 API，用于在 50 多种文件格式之间配置和转换文档。具有在从电子邮件转换过程中呈现电子邮件标题、设置自定义字体目录、配置和放置水印以及高级转换方法等功能。这个 API 不仅仅是一个简单的文件转换工具."
          link: "/conversion/net/"

          # product loop
        - image: "/border/groupdocs-comparison-net.svg"
          img_alt: "GroupDocs.Comparison for .NET"
          name: "GroupDocs.Comparison for .NET"
          content: "文档差异检查器 API 用于比较内容和文本样式。选择比较过程的详细程度。差异分析后应用或拒绝更改。通过文件或流获取文档。指定单词分隔符和字体颜色以对比较文本进行样式化。比较密码保护文件."
          link: "/comparison/net/"

          # product loop
        - image: "/border/groupdocs-signature-net.svg"
          img_alt: "GroupDocs.Signature for .NET"
          name: "GroupDocs.Signature for .NET"
          content: "电子签名操作 API，用于签署各种格式的数字文档。获取系统中存在的所有已注册证书。应用多种类型的签名，例如文本、条形码、图像、二维码等。执行简单和高级搜索以找到所需的签名。配置签名的属性，例如阴影、对齐方式、尺寸等等。"
          link: "/signature/net/"

          # product loop
        - image: "/border/groupdocs-assembly-net.svg"
          img_alt: "GroupDocs.Assembly for .NET"
          name: "GroupDocs.Assembly for .NET"
          content: "通过为支持的格式构建和自定义模板，实现文档自动化和报告生成 API。使用公式和顺序数据操作、在模板语法中格式化字符串、设置序数、基数、字母和数字格式来处理数据。定义变量；使用条件格式等动态地将内容插入到报告中。"
          link: "/assembly/net/"

          # product loop
        - image: "/border/groupdocs-metadata-net.svg"
          img_alt: "GroupDocs.Metadata for .NET"
          name: "GroupDocs.Metadata for .NET"
          content: "元数据访问和操作 API，用于读取、编辑、替换和删除各种文档类型的元数据。比较两个文件的元数据属性以确定它们的相似之处和不同之处。将元数据导出到 Excel、CSV 或 DataSet。检测特定文件或文件流的 MIME 类型。从照片中删除位置信息。减少文件的内存消耗。"
          link: "/metadata/net/"

          # product loop
        - image: "/border/groupdocs-search-net.svg"
          img_alt: "GroupDocs.Search for .NET"
          name: "GroupDocs.Search for .NET"
          content: "提供基本到高级搜索功能的文档和文本搜索 API，例如构建和合并多个索引，通过简单的、布尔型、模糊型、正则表达式 (Regex) 和其他查询类型进行搜索。对文件、文档和电子邮件应用快速、可靠和智能的搜索。根据谐音词、同义词、日期范围、通配符和区分大小写进行搜索。"
          link: "/search/net/"

          # product loop
        - image: "/border/groupdocs-parser-net.svg"
          img_alt: "GroupDocs.Parser for .NET"
          name: "GroupDocs.Parser for .NET"
          content: "文本提取器 API，支持从支持的文件格式中提取原始、格式化和结构化文本和元数据。解析受密码保护的文档。在快速或标准文本提取之间进行选择。 Markdown 和 HTML 格式化程序支持字体、超链接、标题、列表和表格的格式化。从电子邮件容器（Exchange Web 服务器、POP3、IMAP）获取数据。"
          link: "/parser/net/"

          # product loop
        - image: "/border/groupdocs-watermark-net.svg"
          img_alt: "GroupDocs.Watermark for .NET"
          name: "GroupDocs.Watermark for .NET"
          content: "数字水印应用和操作 API，用于应用新水印、搜索和删除支持格式的文档中的现有水印。锁定水印以限制编辑。替换现有水印。在演示文稿中使用不可读的字符保护文本水印。在演示文稿中修改形状属性，例如替代文本、旋转角度等."
          link: "/watermark/net/"

          # product loop
        - image: "/border/groupdocs-editor-net.svg"
          img_alt: "GroupDocs.Editor for .NET"
          name: "GroupDocs.Editor for .NET"
          content: "Document Editor API 用于加载支持的文件格式的文档，将其转换为 HTML，将 HTML 推送到外部 HTML 编辑器，将 HTML 保存为其原始文件格式。单独获取随任何文档附加的资源。获取 HTML 文档的 CSS 内容。从字符串内容中获取 HTML DOM 并转换为文档。对结果文档应用安全性。"
          link: "/editor/net/"

          # product loop
        - image: "/border/groupdocs-merger-net.svg"
          img_alt: "GroupDocs.Merger for .NET"
          name: "GroupDocs.Merger for .NET"
          content: "文档合并和拆分器 API，用于合并、拆分、重新排列、交换、修剪和删除单个页面或 页面、幻灯片或图表的集合。设置或删除已知和未知文件格式的密码保护。缝合或拆分单个或一批文档。通过删除特定页面、幻灯片或图表来修剪文档。"
          link: "/merger/net/"

          # product loop
        - image: "/border/groupdocs-redaction-net.svg"
          img_alt: "GroupDocs.Redaction for .NET"
          name: "GroupDocs.Redaction for .NET"
          content: "文档编辑和清理 API，用于编辑、删除或隐藏文档、工作表、PDF 文件和幻灯片中的分类信息、内容和元数据."
          link: "/redaction/net/"

          # product loop
        - image: "/border/groupdocs-classification-net.svg"
          img_alt: "GroupDocs.Classification for .NET"
          name: "GroupDocs.Classification for .NET"
          content: ".NET 应用程序的原始文本和文档分类 API。使用包括文档和 IAB-2 在内的多种分类法对内容和文档格式进行分类，例如微软办公软件 Word、PDF、OpenDocument、RTF 和文本。根据您的要求，使用一系列高级功能轻松自定义分类结果。"
          link: "/classification/net/"

############################# 特征 ############################
features:
    enable: true
    title: "Advanced API 特征"

    feature:
      # feature loop
      - icon: "fas fa-eye"
        content: "以原始格式或 HTML、图像或 PDF 格式查看任何格式的文档"

      # feature loop
      - icon: "fas fa-file"
        content: "注释任何 PDF、DOCX、XLSX 和 PPTX 文档"

      # feature loop
      - icon: "fas fa-save"
        content: "在 JSON 文件、数据库等不同对象中保存注释或与原始文件合并"
      
      # feature loop
      - icon: "fas fa-file-export"
        content: "将注释导出到单独的 PDF 或 Word 文件"

      # feature loop
      - icon: "fas fa-bolt"
        content: "最快的即时转换 API"

      # feature loop
      - icon: "fas fa-clone"
        content: "批量转换多个文件"

      # feature loop
      - icon: "fas fa-file-code"
        content: "比较内容的单词和段落差异"

      # feature loop
      - icon: "fas fa-file-contract"
        content: "使用比较 API 时单独的差异摘要"

      # feature loop
      - icon: "fas fa-signature"
        content: "多个签名属性"

      # feature loop
      - icon: "fas fa-file-signature"
        content: "在任意页面上设置签名，如第一、最后、偶数、奇数等"

      # feature loop
      - icon: "fas fa-server"
        content: "从多个数据源生成多格式文档"

      # feature loop
      - icon: "fas fa-key"
        content: "键/值对形式的内置和自定义元数据操作"

      # feature loop
      - icon: "fas fa-file-download"
        content: "导出附有支持的文件格式的元数据"

      # feature loop
      - icon: "fab fa-searchengin"
        content: "多种基本和高级搜索方法"

      # feature loop
      - icon: "fas fa-search"
        content: "Fuzzy and 同义词搜索"

      # feature loop
      - icon: "fas fa-search-minus"
        content: "搜索和删除文本/图像水印"

      # feature loop
      - icon: "fas fa-file-image"
        content: "向文档内的图像添加水印"

      # feature loop
      - icon: "fas fa-file-alt"
        content: "提取结构化和突出显示的文本"
      
      # feature loop
      - icon: "fas fa-file-archive"
        content: "从包含其他文件（例如 zip 档案）的容器中获取文本"

      # feature loop
      - icon: "fas fa-file-invoice"
        content: "直接和逆向文档转换"

      # feature loop
      - icon: "fas fa-edit"
        content: "编辑多种文档格式"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: false
    title: "GroupDocs.Total for .NET 为"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for .NET"
          image: "/border/groupdocs-viewer-net.svg"
          product: "GroupDocs.Viewer"
          platform: ".NET"
          link: "/viewer/net/"
        
        # solution loop
        - img_alt: "GroupDocs.Annotation for .NET"
          image: "/border/groupdocs-annotation-net.svg"
          product: "GroupDocs.Annotation"
          platform: ".NET"
          link: "/annotation/net/"

        # solution loop
        - img_alt: "GroupDocs.Conversion for .NET"
          image: "/border/groupdocs-comparison-net.svg"
          product: "GroupDocs.Conversion"
          platform: ".NET"
          link: "/conversion/net/"

        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET"
          image: "/border/groupdocs-comparison-net.svg"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/"

        # solution loop
        - img_alt: "GroupDocs.Signature for .NET"
          image: "/border/groupdocs-signature-net.svg"
          product: "GroupDocs.Signature"
          platform: ".NET"
          link: "/signature/net/"

        # solution loop
        - img_alt: "GroupDocs.Assembly for .NET"
          image: "/border/groupdocs-assembly-net.svg"
          product: "GroupDocs.Assembly"
          platform: ".NET"
          link: "/assembly/net/"

        # solution loop
        - img_alt: "GroupDocs.Metadata for .NET"
          image: "/border/groupdocs-metadata-net.svg"
          product: "GroupDocs.Metadata"
          platform: ".NET"
          link: "/metadata/net/"

        # solution loop
        - img_alt: "GroupDocs.Search for .NET"
          image: "/border/groupdocs-search-net.svg"
          product: "GroupDocs.Search"
          platform: ".NET"
          link: "/search/net/"

        # solution loop
        - img_alt: "GroupDocs.Parser for .NET"
          image: "/border/groupdocs-parser-net.svg"
          product: "GroupDocs.Parser"
          platform: ".NET"
          link: "/parser/net/"

        # solution loop
        - img_alt: "GroupDocs.Watermark for .NET"
          image: "/border/groupdocs-watermark-net.svg"
          product: "GroupDocs.Watermark"
          platform: ".NET"
          link: "/watermark/net/"

        # solution loop
        - img_alt: "GroupDocs.Editor for .NET"
          image: "/border/groupdocs-editor-net.svg"
          product: "GroupDocs.Editor"
          platform: ".NET"
          link: "/editor/net/"

        # solution loop
        - img_alt: "GroupDocs.Merger for .NET"
          image: "/border/groupdocs-merger-net.svg"
          product: "GroupDocs.Merger"
          platform: ".NET"
          link: "/merger/net/"

        # solution loop
        - img_alt: "GroupDocs.Redaction for .NET"
          image: "/border/groupdocs-redaction-net.svg"
          product: "GroupDocs.Redaction"
          platform: ".NET"
          link: "/redaction/net/"

        # solution loop
        - img_alt: "GroupDocs.Classification for .NET"
          image: "/border/groupdocs-classification-net.svg"
          product: "GroupDocs.Classification"
          platform: ".NET"
          link: "/classification/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
