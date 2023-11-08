---
############################# Static ############################
layout: "auto-gen"
date: 2021-06-29T14:22:14+03:00
draft: false

############################# Head ############################
head_title: "Add Barcode Signatures to VSS Viewer in C# .NET"
head_description: "Add 60+ digital barcode signatures to Microsoft Visio Stencil (VSS) and 100+ other file formats. View the signed file in HTML using GroupDocs.Total for .NET APIs."

############################# Header ############################
title: "Add Barcode Signatures to VSS Viewer"
description: "Digitally sign and secure Microsoft Visio Stencil (VSS) files by adding 60+ barcode signature types in your C#, .NET or VB.NET applications using GroupDocs.Total APIs."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://releases.groupdocs.com/total"

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
        link_download: "https://releases.groupdocs.com"
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
    title_left: "Adding barcode signatures to VSS file in .NET"
    content_left: |
        [GroupDocs.Total](https://products.groupdocs.com/total/net/) makes it easy for developers to digitally sign Microsoft Visio Stencil (VSS) documents with barcode signatures using a few lines of C# .NET code.

        *   Instantiate Signature with input document
        *   Create barcode option with predefined barcode text
        *   Setup barcode encoding type
        *   Set the barcode signature position
        *   Add signature and generate output document
        *   Set options to view signed document as HTML
        
    title_right: "System Requirements"
    content_right: |
        The below code example requires you to install [GroupDocs.Viewer for .NET](https://products.groupdocs.com/viewer/net/) and [GroupDocs.Signature for .NET](https://products.groupdocs.com/signature/net/) libraries. Also, make sure that you have the following prerequisites ready on your system before executing the code below:

        *   Operating Systems: Microsoft Windows, Linux, MacOS
        *   Development Environments: Microsoft Visual Studio, Xamarin, MonoDevelop
        *   Frameworks: .NET Framework, .NET Standard, .NET Core, Mono
        *   Get the latest version of GroupDocs.Total for .NET downloaded from [Nuget](https://www.nuget.org/packages/groupdocs.total)
        
    code: |
        ```cs
        // Add barcode signature to VSS file using GroupDocs.Signature API
        // Instantiate Signature with input VSS document
        using (Signature signature = new Signature("input.vss"))
          {
            // Create barcode option with predefined barcode text using BarcodeSignOptions class
            BarcodeSignOptions options = new BarcodeSignOptions("JohnSmith")
            {
              // Setup Barcode encoding type
              EncodeType = BarcodeTypes.Code128,

              // Set signature position
              Left = 50,
              Top = 150,
              Width = 200,
              Height = 50
            };

          // Sign document to file
          SignResult result = signature.Sign("output.vss", options);

          // Set options to view signed document as HTML
          HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("output{0}.html");
          try (Viewer viewer = new Viewer("output.vss")) {
          viewer.view(viewOptions);
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
        - icon: "far fa-file-image-o"
          title: " About VSS File Format"
          content: |
            VSS are stencil files created with Microsoft Visio 2007 and earlier. A relatively new file format is .VSSX that was introduced with Microsoft Visio 2013. Stencil files provide drawing objects that can be included in a .VSD Visio drawing. Microsoft Visio itself is known for creating drawing elements such as collection of shapes, connectors, flowcharts, network layout, UML diagrams, software diagrams, database models, objects mapping and other similar information. It also has rich conversion features of Visio documents to other file formats such as PNG, BMP, PDF and others. Visio is available for both Windows and Mac OS.

          link: "https://docs.fileformat.com/image/vss/"
    
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
          link: "/viewer/net/"
        
        # solution loop
        - img_alt: "GroupDocs.Annotation for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-annotation-net.png"
          product: "GroupDocs.Annotation"
          platform: ".NET"
          link: "/annotation/net/"

        # solution loop
        - img_alt: "GroupDocs.Conversion for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-conversion-net.png"
          product: "GroupDocs.Conversion"
          platform: ".NET"
          link: "/conversion/net/"

        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/"

        # solution loop
        - img_alt: "GroupDocs.Signature for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-signature-net.png"
          product: "GroupDocs.Signature"
          platform: ".NET"
          link: "/signature/net/"

        # solution loop
        - img_alt: "GroupDocs.Assembly for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-assembly-net.png"
          product: "GroupDocs.Assembly"
          platform: ".NET"
          link: "/assembly/net/"

        # solution loop
        - img_alt: "GroupDocs.Metadata for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-metadata-net.png"
          product: "GroupDocs.Metadata"
          platform: ".NET"
          link: "/metadata/net/"

        # solution loop
        - img_alt: "GroupDocs.Search for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-search-net.png"
          product: "GroupDocs.Search"
          platform: ".NET"
          link: "/search/net/"

        # solution loop
        - img_alt: "GroupDocs.Parser for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-parser-net.png"
          product: "GroupDocs.Parser"
          platform: ".NET"
          link: "/parser/net/"

        # solution loop
        - img_alt: "GroupDocs.Watermark for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-watermark-net.png"
          product: "GroupDocs.Watermark"
          platform: ".NET"
          link: "/watermark/net/"

        # solution loop
        - img_alt: "GroupDocs.Editor for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-editor-net.png"
          product: "GroupDocs.Editor"
          platform: ".NET"
          link: "/editor/net/"

        # solution loop
        - img_alt: "GroupDocs.Merger for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-merger-net.png"
          product: "GroupDocs.Merger"
          platform: ".NET"
          link: "/merger/net/"

        # solution loop
        - img_alt: "GroupDocs.Redaction for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs_redaction-net.png"
          product: "GroupDocs.Redaction"
          platform: ".NET"
          link: "/redaction/net/"

        # solution loop
        - img_alt: "GroupDocs.Classification for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-classification-net.png"
          product: "GroupDocs.Classification"
          platform: ".NET"
          link: "/classification/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---