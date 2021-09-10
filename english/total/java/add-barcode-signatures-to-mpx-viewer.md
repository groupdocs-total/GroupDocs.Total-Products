---
############################# Static ############################
layout: "auto-gen"
date: 2021-06-29T14:22:14+03:00
draft: false

############################# Head ############################
head_title: "Add Barcode Signatures to MPX Viewer in Java"
head_description: "Add 60+ digital barcode signatures to Microsoft Project Exchange (MPX) and 100+ other file formats. View the signed file in HTML using GroupDocs.Total for Java APIs."

############################# Header ############################
title: "Add Barcode Signatures to MPX Viewer"
description: "Digitally sign and secure Microsoft Project Exchange files (MPX) by adding 60+ barcode signature types in your Java applications using GroupDocs.Total APIs."
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
        img_alt: "GroupDocs.Total for Java"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-total-java.png"
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
        link_learn: "https://docs.groupdocs.com/total/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "About GroupDocs.Total for Java"
    content: |
        GroupDocs.Total for Java is a suite of document manipulation APIs to perform powerful documents manipulation & automation features within your desktop solutions and web apps without requiring any other commercial application. It enables developers to add the functionalities (view, edit, annotate, convert, compare, e-sign, assemble, search, parse, merge, redact and classify) within PDF, Microsoft Office Word, Excel, PowerPoint, OneNote, Visio, Outlook, HTML, images, graphics, diagrams and 90+ other popular document formats.

        GroupDocs.Total APIs are well supported on all major operating systems and Java versions including J2SE 7.0 (1.7), J2SE 8.0 (1.8) and Java 10.

############################# Steps ############################
steps:
    enable: true
    title_left: "Adding barcode signatures to MPX in Java"
    content_left: |
        [GroupDocs.Total](https://products.groupdocs.com/total/java/) makes it easy for developers to digitally sign Microsoft Project Exchange documents (MPX) with barcode signatures using a few lines of Java code.

        *   Instantiate <mark>**Signature**</mark> class with input document
        *   Create barcode option with predefined barcode text
        *   Setup barcode encoding type
        *   Set the barcode signature position
        *   Add signature and generate signed output document
        *   Set options to view signed document as HTML
        
    title_right: "System Requirements"
    content_right: |
        The below code example requires you to install [GroupDocs.Viewer for Java](https://products.groupdocs.com/viewer/java/) and [GroupDocs.Signature for Java](https://products.groupdocs.com/signature/java/) libraries. Also, make sure that you have the following prerequisites ready on your system before executing the code below:

        *   Operating Systems: Microsoft Windows, Linux, MacOS
        *   Development Environments: NetBeans, IntelliJ IDEA, Eclipse
        *   Frameworks: Java 7 (1.7) and above
        *   Download the latest version of GroupDocs.Total for Java from [Maven](https://repository.groupdocs.com/webapp/#/artifacts/browse/tree/General/repo/com/groupdocs/groupdocs-total)
        
    code: |
        ```cs
        // Add barcode signature to MPX file using GroupDocs.Signature API
        // Instantiate Signature with input MPX document
        Signature signature = new Signature("input.mpx");
        try 
          {
            // setup barcode options with text of signature using BarcodeSignOptions class
            BarcodeSignOptions signOptions = new BarcodeSignOptions("12345678");

            // setup Barcode encoding type
            signOptions.setEncodeType(BarcodeTypes.Code128);

            // set signature position
            signOptions.setLeft(100);
            signOptions.setTop(100);

            // sign the document
            signature.sign("output.mpx", signOptions);

          }

            // Set options to view signed document as HTML
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("output{0}.html);
            try (Viewer viewer = new Viewer("output.mpx")) {
              viewer.view(Options);
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
        - icon: "far fa-file-o"
          title: " About MPX File Format"
          content: |
            A file with extension .mpx is a Microsoft Exchange File Format. An MPX file format was developed by Microsoft Project (MSP) to facilitate project information exchange between MSP and other applications supporting the MPX file format, including Primavera Project Planner, Sciforma, and Timerline Precision Estimating. Using the MPX files, you can transfer all kinds of information from a project to a different system, such as detailed resource assignment information, calendar information, or info from the Project Info dialog box. Microsoft Project 4.0 introduced support for creating and reading MPX file formats that continued to be used through Microsoft Project 98. However, support for creating MPX files has discontinued the release of Microsoft Project 2000, and the versions till Microsoft Project 2010 support only MPX reading. MPX file format is not supported in versions later than MSP 2010.

          link: "https://docs.fileformat.com/project-management/mpx/"
    
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