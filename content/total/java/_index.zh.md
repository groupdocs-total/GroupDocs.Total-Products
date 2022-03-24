---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Total"
product_tag: "total"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "用于查看、转换、注释、签名、自动化和搜索文件格式的 Java API"
head_description: "使用 Java 版本的 GroupDocs 文档操作 API 将它们与您自己的平台和 Java 应用程序集成"

############################# Header ############################
title: "Java 文档自动化库"
description: "从任何 Java 应用程序中查看、导出、注释、比较、签名、自动化和搜索文档的 API."
button:
    enable: true

############################# SubMenu ############################
submenu:
  enable: true
  
  left:
      img_alt: "GroupDocs.Total for Java"
      image: "/border/groupdocs-total-java.svg"
      product: "GroupDocs.Total"
      platform: "Java"

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
          - link: "https://purchase.groupdocs.com/pricing/total/java"
            text: "价钱"

  right:
      link_download: "https://downloads.groupdocs.com/total"
      link_learn: "https://docs.groupdocs.com/total/java/"
      link_buy: "https://purchase.groupdocs.com"

############################# 概述 ############################
overview:
    enable: true
    content: |
      GroupDocs.Total for Java 是 GroupDocs 提供的每个 Java API 的编译。我们每天都会对其进行编译，以确保它包含我们每个 Java API 的最新版本。
        
      使用 GroupDocs.Total for Java 开发人员可以通过一个许可证使用我们所有的 API。但是，您也可以订购任何单独的 API。我们提供的 API 包括

############################# 产品 ############################
products:
    enable: true
    title: "产品"
    description: "GroupDocs.Total for Java 包括以下 Java 文档操作 API："

    product:
        # product loop
        - image: "/border/groupdocs-viewer-java.svg"
          img_alt: "GroupDocs.Viewer for Java"
          name: "GroupDocs.Viewer for Java"
          content: |
            一个强大的文档查看器 API，允许您在 Java 应用程序中显示 50 多种文档格式。查看器可以通过两种方式工作：光栅化文档或将它们转换为 SVG、HTML 和 CSS 的组合。两种方法都提供高保真渲染。
              
            支持的文件格式包括微软办公软件、Visio、Project 和 Outlook 文档、PDF、AutoCAD、图像文件（TIFF、JPG、BMP、GIF、TIFF 等）等。
          link: "/viewer/java/"

        # product loop
        - image: "/border/groupdocs-annotation-java.svg"
          img_alt: "GroupDocs.Annotation for Java"
          name: "GroupDocs.Annotation for Java"
          content: |
            一个灵活的 API，允许最终用户在您的 Java 应用程序中注释微软办公软件、PDF 和其他文档。 API 带有一套全面的标记工具，允许最终用户突出显示、删除和评论文本和图像。
          link: "/annotation/java/"

          # product loop
        - image: "/border/groupdocs-conversion-java.svg"
          img_alt: "GroupDocs.Conversion for Java"
          name: "GroupDocs.Conversion for Java"
          content: |
            一个高级类 API，允许您在 Java 应用程序中在 50 多种文档格式之间来回转换。 API 支持所有微软办公软件文档格式以及 PDF、HTML 和常见的图像文件格式（TIFF、JPEG、GIF、PNG、BMP）。文档可以在运行中一个一个地转换或添加到转换队列中。
          link: "/conversion/java/"

          # product loop
        - image: "/border/groupdocs-comparison-java.svg"
          img_alt: "GroupDocs.Comparison for Java"
          name: "GroupDocs.Comparison for Java"
          content: |
            此 API 允许最终用户快速轻松地找到文档的两个修订版之间的差异。它比较上传的文档并通过差异视图 UI 显示它们之间的差异。使用红线视图突出显示差异 - 类似于 Microsoft Word 更改跟踪功能。
          link: "/comparison/java/"

          # product loop
        - image: "/border/groupdocs-signature-java.svg"
          img_alt: "GroupDocs.Signature for Java"
          name: "GroupDocs.Signature for Java"
          content: |
            使用此 API，您可以使用电子签名功能无缝增强您的应用程序。然后，您的用户可以仅使用 Web 浏览器以电子方式签署文档。详细的审计跟踪、256 位 SSL 加密和其他高级安全功能可确保签名文档的私密性和安全性，而类似向导的 UI 使签名过程变得快速而简单。
          link: "/signature/java/"

          # product loop
        - image: "/border/groupdocs-assembly-java.svg"
          img_alt: "GroupDocs.Assembly for Java"
          name: "GroupDocs.Assembly for Java"
          content: |
            GroupDocs.Assembly for Java 引擎是一组文档自动化和报告生成 API，旨在从模板创建自定义文档。 Java 报表引擎智能地将给定的数据与定义的模板文档组合在一起，并根据数据源生成与模板文档格式相同格式的输出文档。
          link: "/assembly/java/"

          # product loop
        - image: "/border/groupdocs-metadata-java.svg"
          img_alt: "GroupDocs.Metadata for Java"
          name: "GroupDocs.Metadata for Java"
          content: |
            GroupDocs.Metadata for Java 是一个文档元数据管理 API，设计用于所有基本元数据操作，如查看、添加、修改和删除元数据。元数据 API 支持多种文件格式。您可以加载输入文档并使其元数据可供用户访问以进行元数据操作。
          link: "/metadata/java/"

          # product loop
        - image: "/border/groupdocs-search-java.svg"
          img_alt: "GroupDocs.Search for Java"
          name: "GroupDocs.Search for Java"
          content: |
            GroupDocs.Search for Java - 用于具有索引功能的高级查询的文档搜索 API。在 Java 应用程序中使用 API 处理文档，包括 Word Excel PowerPoint 和 PDF 以进行全文检索等等。
          link: "/search/java/"

          # product loop
        - image: "/border/groupdocs-parser-java.svg"
          img_alt: "GroupDocs.Parser for Java"
          name: "GroupDocs.Parser for Java"
          content: |
            GroupDocs.Parser for Java - 一个可扩展的文本提取器和解析 API，用于读取或分析来自不同文件格式的文档内容和元数据属性。它只需将文件作为输入，然后获取输入文件的原始或格式化文本以及元数据属性即可。
          link: "/parser/java/"

          # product loop
        - image: "/border/groupdocs-watermark-java.svg"
          img_alt: "GroupDocs.Watermark for Java"
          name: "GroupDocs.Watermark for Java"
          content: |
            GroupDocs.Watermark for Java 是一个文档水印 API，用于从多种文件格式中添加、搜索和删除水印。 API 支持文本和图像水印类型。任何第三方软件添加的水印都可以通过此API轻松搜索和删除，而任何第三方工具很难删除使用此API添加的水印。
          link: "/watermark/java/"

          # product loop
        - image: "/border/groupdocs-editor-java.svg"
          img_alt: "GroupDocs.Editor for Java"
          name: "GroupDocs.Editor for Java"
          content: |
            GroupDocs.Editor for Java 是一个轻量级的 API，用于以 HTML 的形式编辑多种文档格式。编辑器 API 既可以将源文档翻译成 HTML，也可以将编辑后的 HTML 保存为源文档格式。
          link: "/editor/java/"

          # product loop
        - image: "/border/groupdocs-merger-java.svg"
          img_alt: "GroupDocs.Merger for Java"
          name: "GroupDocs.Merger for Java"
          content: |
            GroupDocs.Merger for Java 是一个文档合并和连接 API，用于将多个文件组合和排列成一个文件，以及在支持格式的文档中拆分、删除或重新排序页面。
          link: "/merger/java/"

          # product loop
        - image: "/border/groupdocs-redaction-java.svg"
          img_alt: "GroupDocs.Redaction for Java"
          name: "GroupDocs.Redaction for Java"
          content: |
            Java 文档编校 API，用于使用文本、元数据和注释编校类型保护或删除 Word、Excel、PowerPoint、图像和 PDF 文档中的任何机密信息。
          link: "/redaction/java/"

############################# 特征 ############################
features:
    enable: true
    title: "Advanced API 特征"

    feature:
      # feature loop
      - icon: "fas fa-file"
        content: "文档的 HTML、图像和 PDF 表示"

      # feature loop
      - icon: "fas fa-water"
        content: "水印：将文本作为水印添加到输出的所有页面和图像"

      # feature loop
      - icon: "fas fa-pen"
        content: "原生 Word 和 PDF 注释"
      
      # feature loop
      - icon: "fas fa-tools"
        content: "全套注释工具"

      # feature loop
      - icon: "fas fa-envelope"
        content: "注释电子邮件、HTML 和图像文档"

      # feature loop
      - icon: "fas fa-bolt"
        content: "快速准确的文档转换"

      # feature loop
      - icon: "fas fa-key"
        content: "比较文档内容、受密码保护的文件、字体样式和水印"

      # feature loop
      - icon: "fas fa-save"
        content: "将差异摘要保存为 DOC 或 DOCX 格式"

      # feature loop
      - icon: "fas fa-upload"
        content: "上传、输入或绘制签名"

      # feature loop
      - icon: "fas fa-file-signature"
        content: "所有类型的数字签名验证"

      # feature loop
      - icon: "fas fa-server"
        content: "从多个数据源生成文档"

      # feature loop
      - icon: "fas fa-eraser"
        content: "分析和删除多种文档格式的隐藏元数据"

      # feature loop
      - icon: "fas fa-search-plus"
        content: "搜索和比较元数据"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "将元数据导出到 Excel/CSV"

      # feature loop
      - icon: "fas fa-lock"
        content: "从受密码保护的文件中提取文本"

      # feature loop
      - icon: "fas fa-search-minus"
        content: "搜索和删除文本/图像水印"

      # feature loop
      - icon: "fas fa-file-image"
        content: "编辑多种文档格式"

      # feature loop
      - icon: "fas fa-file-alt"
        content: "将多个文件合并为一个"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: false
    title: "GroupDocs.Total for Java 为"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for Java"
          image: "/border/groupdocs-viewer-java.svg"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"
        
        # solution loop
        - img_alt: "GroupDocs.Annotation for Java"
          image: "/border/groupdocs-annotation-java.svg"
          product: "GroupDocs.Annotation"
          platform: "Java"
          link: "/annotation/java/"

        # solution loop
        - img_alt: "GroupDocs.Conversion for Java"
          image: "/border/groupdocs-conversion-java.svg"
          product: "GroupDocs.Conversion"
          platform: "Java"
          link: "/conversion/java/"

        # solution loop
        - img_alt: "GroupDocs.Comparison for Java"
          image: "/border/groupdocs-comparison-java.svg"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/"

        # solution loop
        - img_alt: "GroupDocs.Signature for Java"
          image: "/border/groupdocs-signature-java.svg"
          product: "GroupDocs.Signature"
          platform: "Java"
          link: "/signature/java/"

        # solution loop
        - img_alt: "GroupDocs.Assembly for Java"
          image: "/border/groupdocs-assembly-java.svg"
          product: "GroupDocs.Assembly"
          platform: "Java"
          link: "/assembly/java/"

        # solution loop
        - img_alt: "GroupDocs.Metadata for Java"
          image: "/border/groupdocs-metadata-java.svg"
          product: "GroupDocs.Metadata"
          platform: "Java"
          link: "/metadata/java/"

        # solution loop
        - img_alt: "GroupDocs.Search for Java"
          image: "/border/groupdocs-search-java.svg"
          product: "GroupDocs.Search"
          platform: "Java"
          link: "/search/java/"

        # solution loop
        - img_alt: "GroupDocs.Parser for Java"
          image: "/border/groupdocs-parser-java.svg"
          product: "GroupDocs.Parser"
          platform: "Java"
          link: "/parser/java/"

        # solution loop
        - img_alt: "GroupDocs.Watermark for Java"
          image: "/border/groupdocs-watermark-java.svg"
          product: "GroupDocs.Watermark"
          platform: "Java"
          link: "/watermark/java/"

        # solution loop
        - img_alt: "GroupDocs.Editor for Java"
          image: "/border/groupdocs-editor-java.svg"
          product: "GroupDocs.Editor"
          platform: "Java"
          link: "/editor/java/"

        # solution loop
        - img_alt: "GroupDocs.Merger for Java"
          image: "/border/groupdocs-merger-java.svg"
          product: "GroupDocs.Merger"
          platform: "Java"
          link: "/merger/java/"

        # solution loop
        - img_alt: "GroupDocs.Redaction for Java"
          image: "/border/groupdocs-redaction-java.svg"
          product: "GroupDocs.Redaction"
          platform: "Java"
          link: "/redaction/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---