---
############################# Static ############################
layout: "auto-gen"
date: 2021-06-29T14:22:14+03:00
draft: false

############################# Head ############################
head_title: "Add PNG Image Watermark to PPTX File in C# .NET"
head_description: "C# .NET API to add PNG image watermark into PowerPoint presentation (PPTX) and 100+ other file formats using GroupDocs.Total suite of documents automation APIs."

############################# Header ############################
title: "Add PNG Image Watermark to PPTX in .NET"
description: "Insert PNG or any other image watermark into PowerPoint presentation (PPTX) formats quite easily and accurately using GroupDocs.Total suite of documents automation APIs for C# .NET applications."
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
    title_left: "Adding image watermark to PPTX file in .NET"
    content_left: |
        [GroupDocs.Total](https://products.groupdocs.com/total/net/) makes it easy for developers to integrate PNG image watermark into PowerPoint presentation file formats using a few lines of C# .NET code.

        *   Instantiate Watermarker with input document
        *   Use watermark image path as constructor parameter
        *   Set the watermark horizontal and vertical alignments
        *   Add watermark to the watermarker and generate output document
        *   Instantiate viewer with output document
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
        // Add watermark to the input file using GroupDocs.Watermark API
        // Instantiate Watermarker with input document
        using (Watermarker watermarker = new Watermarker("input.pptx"))
          {
            // Use watermark image path as constructor parameter of ImageWatermark class
            using (ImageWatermark watermark = new ImageWatermark("watermark.png"))
            {
              // Set watermark size and alignment
              watermark.Width = 150;
              watermark.Height = 150;
              watermark.HorizontalAlignment = HorizontalAlignment.Right;
              watermark.VerticalAlignment = VerticalAlignment.Top;

              //Add watermark to the watermarker and generate output document
              watermarker.Add(watermark);
              watermarker.Save("output.pptx");
            }
          }
        
        // View watermarked file using GroupDocs.Viewer API
        // Instantiate Viewer with output document
        using (Viewer viewer = new Viewer("output.pptx"))
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
        - icon: "far fa-file-powerpoint-o"
          title: " About PowerPoint PPTX File Format"
          content: |
            Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings.

          link: "https://docs.fileformat.com/presentation/pptx/"
    
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