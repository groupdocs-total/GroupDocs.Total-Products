---
############################# Static ############################
layout: "auto-gen"
date: 2021-06-29T14:22:14+03:00
draft: false

############################# Head ############################
head_title: "Add Metadata Signatures to OTT Viewer in Java"
head_description: "Add digital metadata signatures to an OpenDocument template file (OTT) in Java applications. View the signed file in HTML, Image or PDF viewer using GroupDocs.Total for Java APIs."

############################# Header ############################
title: "Add Metadata Signatures to Java OTT Viewer"
description: "Add digital metadata signatures to an OpenDocument template file (OTT). View the signed file in HTML, Image or PDF viewer using GroupDocs.Total APIs for Java applications."
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
    title_left: "Adding metadata signatures to OTT in Java"
    content_left: |
        [GroupDocs.Total](https://products.groupdocs.com/total/java/) makes it easy for developers to digitally sign an OpenDocument template file (OTT) with metadata signatures using a few lines of Java code.

        *   Instantiate <mark>**Signature**</mark> with input document.
        *   Instantiate the <mark>**MetadataSignOptions**</mark> object as per your needs.
        *   Instantiate one or more <mark>**WordProcessingMetadataSignature**</mark> objects and add them into <mark>**MetadataSignOptions**</mark> to metadata signatures collection (<mark>**getSignatures**</mark>) via <mark>**Add**</mark> or <mark>**AddRange**</mark> method.
        *   Call <mark>**Sign**</mark> method and pass <mark>**MetadataSignOptions**</mark> to it.
        *   Set options to view signed document as HTML.
        
    title_right: "System Requirements"
    content_right: |
        The below code example requires you to install [GroupDocs.Viewer for Java](https://products.groupdocs.com/viewer/java/) and [GroupDocs.Signature for Java](https://products.groupdocs.com/signature/java/) libraries. Also, make sure that you have the following prerequisites ready on your system before executing the code below:

        *   Operating Systems: Microsoft Windows, Linux, MacOS
        *   Development Environments: NetBeans, IntelliJ IDEA, Eclipse
        *   Frameworks: Java 7 (1.7) and above
        *   Download the latest version of GroupDocs.Total for Java from [Maven](https://repository.groupdocs.com/webapp/#/artifacts/browse/tree/General/repo/com/groupdocs/groupdocs-total)
        
    code: |
        ```cs
        // Add metadata signatures to Word document using GroupDocs.Signature API
        // Instantiate Signature with input OTT document
        Signature signature = new Signature("input.ott");
          {
            // Instantiate the MetadataSignOptions object
            MetadataSignOptions options = new MetadataSignOptions();
          
            // Create few WordProcessing Metadata signatures
            WordProcessingMetadataSignature[] signatures = new WordProcessingMetadataSignature[]
            {
              new WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
              new WordProcessingMetadataSignature("DateCreated", new Date()),
              new WordProcessingMetadataSignature("DocumentId", 123456),
              new WordProcessingMetadataSignature("SignatureId", 123.456)
            };

            // Add these signatures to options
            options.getSignatures().addRange(signatures);
            signature.Sign("output.ott", options);
          }

            // Set options to view signed document as HTML
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("output{0}.html");
            try (Viewer viewer = new Viewer("output.ott")) {
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
        - icon: "far fa-file-word-o"
          title: " About OTT File Format"
          content: |
            Files with OTT extension represent template documents generated by applications in compliance with the OASIS' OpenDocument standard format. These are created with word processor applications such as free OpenOffice Writer and can hold settings that can be used to generate new documents from these template files. These settings include page margins, borders, headers, footers, and other page settings. Such templates are used in official documents such as company letterheads and standardized forms.

          link: "https://docs.fileformat.com/word-processing/ott/"
    
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