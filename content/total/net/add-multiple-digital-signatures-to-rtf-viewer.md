---
############################# Static ############################
layout: "auto-gen"
date: 2021-06-29T14:22:14+03:00
draft: false

############################# Head ############################
head_title: "Add Multiple Digital Signatures to RTF Viewer in .NET"
head_description: "Sign Rich Text Format (RTF) documents file with multiple digital signature types (Barcode, Image, Metadata, QR-Code, Stamp, Text, Form Field) in C# .NET applications."

############################# Header ############################
title: "Add Multiple Signatures to RTF Viewer"
description: "Sign Rich Text Format (RTF) files with different digital signature types (Barcode, Image, Metadata, QR-Code, Stamp, Text, Form Field). View the signed file in HTML, Image or PDF viewer in .NET (C#, ASP.NET, VB.NET, .NET Core) applications."
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
    title_left: "Put multiple signatures to RTF files in .NET"
    content_left: |
        [GroupDocs.Total](https://products.groupdocs.com/total/net/) makes it easy for developers to insert multiple digital signatures to Rich Text Format (RTF) documents by adding a few lines of C# .NET code.

        *   Instantiate Signature with input document
        *   Instantiate required sign options objects depending on the signature type.
        *   Use **BarcodeSignOptions** to add Barcode signatures.
        *   Use **DigitalSignOptions** to add Digital signatures.
        *   Use **FormFieldSignOptions** to add Form-field signatures.
        *   Use **ImageSignOptions** to add Image signatures.
        *   Use **MetadataSignOptions** to add Metadata signatures.
        *   Use **QrCodeSignOptions** to add QR-code signatures.
        *   Use **StampSIgnOptions** to add Stamp signatures.
        *   Use **TextSignOptions** to add Text signatures.
        *   Fill collection with sign options from previous step.
        *   Call **Sign** method of **Signature** class  and pass sign options to it.
        
    title_right: "System Requirements"
    content_right: |
        The below code example requires you to install [GroupDocs.Viewer for .NET](https://products.groupdocs.com/viewer/net/) and [GroupDocs.Signature for .NET](https://products.groupdocs.com/signature/net/) libraries. Also, make sure that you have the following prerequisites ready on your system before executing the code below:

        *   Operating Systems: Microsoft Windows, Linux, MacOS
        *   Development Environments: Microsoft Visual Studio, Xamarin, MonoDevelop
        *   Frameworks: .NET Framework, .NET Standard, .NET Core, Mono
        *   Get the latest version of GroupDocs.Total for .NET downloaded from [Nuget](https://www.nuget.org/packages/groupdocs.total)
        
    code: |
        ```cs
        // Digitally sign RTF file with multiple signatures in .NET
        // Instantiate Signature with input RTF document
        using (Signature signature = new Signature("input.rtf"))
          {
            // Define several signature options of different types and settings
            TextSignOptions textOptions = new TextSignOptions("Add text signature here")
            {
              VerticalAlignment = VerticalAlignment.Top,
              HorizontalAlignment = HorizontalAlignment.Left
            };

            BarcodeSignOptions barcodeOptions = new BarcodeSignOptions("123456")
            {
              EncodeType = BarcodeTypes.Code128,
              Left = 100,
              Top = 100
            };

            QrCodeSignOptions qrcodeOptions = new QrCodeSignOptions("JohnSmith")
            {
              EncodeType = QrCodeTypes.QR,
              Left = 100,
              Top = 200
            };

            DigitalSignOptions digitalOptions = new DigitalSignOptions("certificate.pfx")
            {
              ImageFilePath = Constants.ImageHandwrite,
              VerticalAlignment = VerticalAlignment.Center,
              HorizontalAlignment = HorizontalAlignment.Center,
              Password = "1234567890"
            };

            // define list of signature options
            List<SignOptions> listOptions = new List<SignOptions>();
            listOptions.Add(textOptions);
            listOptions.Add(barcodeOptions);
            listOptions.Add(qrcodeOptions);
            listOptions.Add(digitalOptions);

            // sign document to file
            signature.Sign("signed.rtf", options);

        // View watermarked file using GroupDocs.Viewer API
        // Instantiate Viewer with output document
        using (Viewer viewer = new Viewer("output.rtf"))
          {
            // Set options to view signed document as HTML
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("output{0}.html");
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
        - icon: "far fa-file-text"
          title: " About RTF File Format"
          content: |
            Introduced and documented by Microsoft, the Rich Text Format (RTF) represents a method of encoding formatted text and graphics for use within applications. The format facilitates cross-platform document exchange with other Microsoft Products, thus serving the purpose of interoperability. This capability makes it a standard of data transfer between word processing software and, hence, contents can be transferred from one operating system to another without losing document formatting. The file format specifications are available by Microsoft for public download and can be referred to from developer’s perspective.

          link: "https://docs.fileformat.com/word-processing/rtf/"
    
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