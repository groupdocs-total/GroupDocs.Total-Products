---
############################# Static ############################
layout: "auto-gen"
date: 2021-06-29T14:22:14+03:00
draft: false

############################# Head ############################
head_title: "Add BMP Image Watermark to OXPS Viewer in C# .NET"
head_description: "C# .NET API to add BMP image watermark into an Open XML Paper Specification file (OXPS) and 100+ other file formats using GroupDocs.Total suite of documents automation APIs."

############################# Header ############################
title: "Add BMP Image Watermark to OXPS Viewer"
description: "Insert BMP or any other image watermark into an Open XML Paper Specification file (OXPS) quite easily and accurately using GroupDocs.Total suite of documents automation APIs for C# .NET applications."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/total"

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Total for .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-total-net.png"
        product: "GroupDocs.Total"
        platform: ".NET"

    middle:
        button:

            # button loop
            - link: "https://apireference.groupdocs.com"
              text: "API Reference"

            # button loop
            - link: "https://github.com/groupdocs-total"
              text: "Code Examples"

            # button loop
            - link: "https://products.groupdocs.app/total"
              text: "Live Demos"

            # button loop
            - link: "https://purchase.groupdocs.com/buy"
              text: "Pricing"

    right:
        link_download: "https://downloads.groupdocs.com"
        link_learn: "https://docs.groupdocs.com/total/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "About GroupDocs.Total for .NET"
    content: |
        GroupDocs.Total for .NET is a suite of document manipulation APIs to perform powerful documents manipulation & automation features within your desktop solutions and web apps without requiring any other commercial application. It enables developers to add the functionalities (view, edit, annotate, convert, compare, e-sign, assemble, search, parse, merge, redact and classify) within PDF, Microsoft Office Word, Excel, PowerPoint, OneNote, Visio, Outlook, HTML, images, graphics, diagrams and 90+ other popular document formats.

        GroupDocs.Total APIs are well supported on all major operating systems and platforms including .NET Framework, .NET Standard, .NET Core, Mono and Xamarin.

############################# Steps ############################
steps:
    enable: true
    title_left: "Adding image watermark to OXPS file in .NET"
    content_left: |
        [GroupDocs.Total](https://products.groupdocs.com/total/net/) makes it easy for developers to integrate BMP image watermark into an Open XML Paper Specification file (OXPS) using a few lines of C# .NET code.

        *   Instantiate Watermarker with input OXPS file
        *   Use BMP watermark image path as constructor parameter of ImageWatermark class
        *   Set the watermark size and alignment
        *   Add watermark to the watermarker and generate output document
        *   Instantiate Viewer with output document
        *   Set options to view document as HTML
        
    title_right: "System Requirements"
    content_right: |
        The below code example requires you to install GroupDocs.Viewer for .NET and GroupDocs.Watermark for .NET libraries. Also, make sure that you have the following prerequisites ready on your system before executing the code below:

        *   Operating Systems: Microsoft Windows, Linux, MacOS
        *   Development Environments: Microsoft Visual Studio, Xamarin, MonoDevelop
        *   Frameworks: .NET Framework, .NET Standard, .NET Core, Mono
        *   Get the latest version of GroupDocs.Total for .NET downloaded from [Nuget](https://www.nuget.org/packages/groupdocs.total)
        
    code: |
        ```cs
        // Add watermark to OXPS file using GroupDocs.Watermark API
        // Instantiate Watermarker with input OXPS document
        using (Watermarker watermarker = new Watermarker("input.oxps"))
          {
            // Use BMP watermark image path as constructor parameter of ImageWatermark class
            using (ImageWatermark watermark = new ImageWatermark("watermark.bmp"))
            {
              // Set watermark size and alignment
              watermark.Width = 150;
              watermark.Height = 150;
              watermark.HorizontalAlignment = HorizontalAlignment.Right;
              watermark.VerticalAlignment = VerticalAlignment.Top;

              //Add watermark to the watermarker and generate output document
              watermarker.Add(watermark);
              watermarker.Save("output.oxps");
            }
          }
        
        // View watermarked OXPS file using GroupDocs.Viewer API
        // View watermarked file using GroupDocs.Viewer API
        // Instantiate Viewer with output document
        using (Viewer viewer = new Viewer("output.oxps"))
          {
            // Set options to view document as HTML
            HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources("output{0}.html");
            viewer.View(options);
          }
        ```
        
############################# Demos ############################
demos:
    enable: true
    title: "Free Document Automation Apps"
    content: |
        Offline [GroupDocs.Total Apps](https://products.groupdocs.app/total) to view, convert, annotate, compare, sign, assemble, parse, classify, redact and search documents.  
        The live demo has the following benefits
        
############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-code-o"
          title: " About OXPS File Format"
          content: |
            The file format OXPS is known as Open XML Paper Specification. It’s a page description language and document format. Microsoft is the developer of this format. OXPS file format is very much familiar to these PDF files. The setup of the OXPS file is the same as an XPS format. The only difference is the description of OXPS as an open format. The .oxps file extension is the most current version of the XPS file format originated by Microsoft and Ecma International. If we talk about the specification, the OXPS and XPS files are used to publish, share, and allocate fixed-layout documents. As a substitute to PDFs, the OXPS file format can store text and multimedia data, with arranging features and printing layout characteristics.

          link: "https://docs.fileformat.com/page-description-language/oxps/"
    
############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Total for .NET offers individual solutions for"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
          product: "GroupDocs.Viewer"
          platform: ".NET"
          link: "/viewer/net"
        
        # solution loop
        - img_alt: "GroupDocs.Annotation for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-annotation-net.png"
          product: "GroupDocs.Annotation"
          platform: ".NET"
          link: "/annotation/net"

        # solution loop
        - img_alt: "GroupDocs.Conversion for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-conversion-net.png"
          product: "GroupDocs.Conversion"
          platform: ".NET"
          link: "/conversion/net"

        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net"

        # solution loop
        - img_alt: "GroupDocs.Signature for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-signature-net.png"
          product: "GroupDocs.Signature"
          platform: ".NET"
          link: "/signature/net"

        # solution loop
        - img_alt: "GroupDocs.Assembly for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-assembly-net.png"
          product: "GroupDocs.Assembly"
          platform: ".NET"
          link: "/assembly/net"

        # solution loop
        - img_alt: "GroupDocs.Metadata for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-metadata-net.png"
          product: "GroupDocs.Metadata"
          platform: ".NET"
          link: "/metadata/net"

        # solution loop
        - img_alt: "GroupDocs.Search for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-search-net.png"
          product: "GroupDocs.Search"
          platform: ".NET"
          link: "/search/net"

        # solution loop
        - img_alt: "GroupDocs.Parser for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-parser-net.png"
          product: "GroupDocs.Parser"
          platform: ".NET"
          link: "/parser/net"

        # solution loop
        - img_alt: "GroupDocs.Watermark for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-watermark-net.png"
          product: "GroupDocs.Watermark"
          platform: ".NET"
          link: "/watermark/net"

        # solution loop
        - img_alt: "GroupDocs.Editor for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-editor-net.png"
          product: "GroupDocs.Editor"
          platform: ".NET"
          link: "/editor/net"

        # solution loop
        - img_alt: "GroupDocs.Merger for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-merger-net.png"
          product: "GroupDocs.Merger"
          platform: ".NET"
          link: "/merger/net"

        # solution loop
        - img_alt: "GroupDocs.Redaction for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs_redaction-net.png"
          product: "GroupDocs.Redaction"
          platform: ".NET"
          link: "/redaction/net"

        # solution loop
        - img_alt: "GroupDocs.Classification for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-classification-net.png"
          product: "GroupDocs.Classification"
          platform: ".NET"
          link: "/classification/net"

############################# Back to top ###############################
back_to_top:
  enable: true
---