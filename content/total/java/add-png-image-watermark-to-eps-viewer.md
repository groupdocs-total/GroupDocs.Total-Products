---
############################# Static ############################
layout: "auto-gen"
date: 2021-06-29T14:22:14+03:00
draft: false

############################# Head ############################
head_title: "Add PNG Image Watermark to EPS Viewer in Java"
head_description: "Java API to add PNG image watermark into an encapsulated PostScript (EPS) file and 100+ other file formats using GroupDocs.Total suite of documents automation APIs."

############################# Header ############################
title: "Add PNG Image Watermark to EPS Viewer"
description: "Add PNG or other types of image watermarks into an encapsulated PostScript (EPS) file on any position with adjustable size and orientation using GroupDocs.Total suite of documents automation APIs for java applications."
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
        img_alt: "GroupDocs.Total for Java"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-total-java.png"
        product: "GroupDocs.Total"
        platform: "Java"

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
        link_learn: "https://docs.groupdocs.com/total/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "About GroupDocs.Total for Java"
    content: |
        GroupDocs.Total for Java is a suite of document manipulation APIs to perform powerful documents manipulation & automation features within your desktop solutions and web apps without requiring any other commercial application. It enables developers to seamlessly add the documents management and editing features (view, edit, annotate, convert, compare, e-sign, assemble, search, parse, merge, redact and classify) within PDF, Microsoft Office Word, Excel, PowerPoint, OneNote, Visio, Outlook, HTML, images, graphics, diagrams and 100+ other popular file formats.

        GroupDocs.Total APIs are well supported on all major operating systems and Java frameworks.

############################# Steps ############################
steps:
    enable: true
    title_left: "Adding image watermark to EPS file in Java"
    content_left: |
        [GroupDocs.Total](https://products.groupdocs.com/total/java/) makes it easy for developers to integrate PNG image watermark into an encapsulated PostScript (EPS) file using a few lines of Java code.

        *   Instantiate FileInputStream Object with input file
        *   Instantiate Watermarker object using the stream object created above
        *   Use watermark image path as constructor parameter of ImageWatermark class
        *   Set image watermark alignment
        *   Add watermark to the watermarker and generate output file
        *   Set options to view document as HTML
        *   Instantiate Viewer with output file
        
    title_right: "System Requirements"
    content_right: |
        The below code example requires you to install [GroupDocs.Viewer for Java](https://products.groupdocs.com/viewer/java/) and [GroupDocs.Watermark for Java](https://products.groupdocs.com/watermark/java/) libraries. Also, make sure that you have the following prerequisites ready on your system before executing the code below:

        *   Operating Systems: Microsoft Windows, Linux, MacOS
        *   Development Environments: NetBeans, IntelliJ IDEA, Eclipse
        *   Frameworks: Java 7 (1.7) and above
        *   Download the latest version of GroupDocs.Total for Java from [Maven](https://repository.groupdocs.com/webapp/#/artifacts/browse/tree/General/repo/com/groupdocs/groupdocs-total)
        
    code: |
        ```cs
        // Add watermark to (EPS) file using GroupDocs.Watermark API
        // Instantiate FileInputStream Object with input file
        FileInputStream stream = new FileInputStream("input.eps");

        // Instantiate Watermarker object using the stream object created above
        Watermarker watermarker = new Watermarker(stream);
        
        // Use PNG watermark image path as constructor parameter of ImageWatermark class
        ImageWatermark watermark = new ImageWatermark("watermark.png");
        
        // Set image watermark alignment 
        watermark.setHorizontalAlignment(HorizontalAlignment.Center);
        watermark.setVerticalAlignment(VerticalAlignment.Center);

        //Add watermark to the watermarker and generate output file
        watermarker.add(watermark);
        watermarker.save("output.eps");
        
        // Close Watermark, Watermarker and FileInputStream objects
        watermark.close();
        watermarker.close();
        stream.close();

        // View watermarked EPS file using GroupDocs.Viewer API
        // View watermarked file using GroupDocs.Viewer API
        // Set options to view document as HTML
        HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("output{0}.html");

        // Instantiate Viewer with output file
        try (Viewer viewer = new Viewer("output.eps")) {
          viewer.view(options);
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
          title: " About EPS File Format"
          content: |
            Files with EPS extension essentially describe an Encapsulated PostScript language program that describes the appearance of a single page. The name “Encapsulated” because it can be included or encapsulated in another PostScript language page description. This script based file format may contain any combination of text, graphics and images. EPS files may include a bitmap preview image encapsulated inside for display by applications that can open such files. EPS files can be converted to standard image formats such as JPG, PNG, TIFF and PDF using different applications e.g. Adobe Illustrator, Photoshop and PaintShop Pro. Because of a security vulnerability in EPS files, Office 2016, Office 2013, Office 2010, and Office 365 have turned off the ability to Add EPS files into Office documents.

          link: "https://docs.fileformat.com/page-description-language/eps/"
    
############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Total for Java offers individual solutions for"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/net/"
        
        # solution loop
        - img_alt: "GroupDocs.Annotation for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-annotation-net.png"
          product: "GroupDocs.Annotation"
          platform: "Java"
          link: "/annotation/net/"

        # solution loop
        - img_alt: "GroupDocs.Conversion for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-conversion-net.png"
          product: "GroupDocs.Conversion"
          platform: "Java"
          link: "/conversion/net/"

        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-comparison-net.png"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/net/"

        # solution loop
        - img_alt: "GroupDocs.Signature for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-signature-net.png"
          product: "GroupDocs.Signature"
          platform: "Java"
          link: "/signature/net/"

        # solution loop
        - img_alt: "GroupDocs.Assembly for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-assembly-net.png"
          product: "GroupDocs.Assembly"
          platform: "Java"
          link: "/assembly/net/"

        # solution loop
        - img_alt: "GroupDocs.Metadata for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-metadata-net.png"
          product: "GroupDocs.Metadata"
          platform: "Java"
          link: "/metadata/net/"

        # solution loop
        - img_alt: "GroupDocs.Search for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-search-net.png"
          product: "GroupDocs.Search"
          platform: "Java"
          link: "/search/net/"

        # solution loop
        - img_alt: "GroupDocs.Parser for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-parser-net.png"
          product: "GroupDocs.Parser"
          platform: "Java"
          link: "/parser/net/"

        # solution loop
        - img_alt: "GroupDocs.Watermark for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-watermark-net.png"
          product: "GroupDocs.Watermark"
          platform: "Java"
          link: "/watermark/net/"

        # solution loop
        - img_alt: "GroupDocs.Editor for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-editor-net.png"
          product: "GroupDocs.Editor"
          platform: "Java"
          link: "/editor/net/"

        # solution loop
        - img_alt: "GroupDocs.Merger for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-merger-net.png"
          product: "GroupDocs.Merger"
          platform: "Java"
          link: "/merger/net/"

        # solution loop
        - img_alt: "GroupDocs.Redaction for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs_redaction-net.png"
          product: "GroupDocs.Redaction"
          platform: "Java"
          link: "/redaction/net/"

        # solution loop
        - img_alt: "GroupDocs.Classification for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-classification-net.png"
          product: "GroupDocs.Classification"
          platform: "Java"
          link: "/classification/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---