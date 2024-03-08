---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: en
product: "Total"
product_tag: "total"
platform: ".NET"
platform_tag: "net"

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
head_title: "All-in-one document automation library for .NET applications"
head_description: "GroupDocs.Total for .NET is an all-in-one document automation API suite for .NET developers, providing a comprehensive set of tools for working with various document formats, including PDF, Word, Excel, Image, HTML, Diagram, and more."

############################# Header ##########################
title: "Streamline document automation<br> in your .NET apps"
description: "Unlock document automation: convert, view and compare, edit and sign between more than 200 formats easily."
words:
  for: "for"

actions:
  main: "Free NuGet Download"
  main_link: "https://www.nuget.org/packages/GroupDocs.Total"
  alt: "Licensing"
  alt_link: "https://purchase.groupdocs.com/pricing/total/net"
  title: "Ready to get started?"
  description: "Try GroupDocs.Total features for free or request a license"

release:
  title: "Version {0}&nbsp;released"
  notes: "See what’s new"
  downloads: "Downloads"
  link: "https://releases.groupdocs.com/total/net/release-notes/latest/"

code:
  title: "Merge and view Word files in C#"
  more: "More examples"
  more_link: "https://github.com/groupdocs-total/GroupDocs.Total-for-.NET"
  install: "dotnet add package GroupDocs.Total"
  content: |
    ```csharp {style=abap} 
    // Load the source DOCX file
    using (Merger merger = new Merger("sample1.docx"))
    {
        // Add another DOCX file to merge
        merger.Join("sample2.docx");

        // Merge DOCX files and save result
        merger.Save("merged.docx");
    }

    // Load merged DOCX file into viewer
    using (var viewer = new Viewer("merged.docx"))
    {
        // Set output HTML options, one file per page
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // Render DOCX to HTML with embedded resources        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Total at a glance"
  description: "Automate file view, convert, edit, compare, search, watermarking and other workflows in .NET applications"
  features:
    # feature loop
    - title: "Combine the power of multiple GroupDocs products to a single, comprehensive solution"
      content: | 
        You can use features of different GroupDocs products to create a customized approach that meets your specific needs.
        <br><br>
        For example, you can convert a Word file to PDF and then add a digital signature. Or populate a document template data from a database, or extract text from an image and then translate it into another language.
        <br><br>
        The possibilities are endless!
          
    # feature loop
    - title: "Master the diversity of file formats"
      content: "GroupDocs.Total for .NET unlocks compatibility with over 200 file formats, empowering you to process documents of all popular types. From office formats like Word and Excel to images, code, and encrypted files, we've got you covered."

    # feature loop
    - title: "Cross-platform support"
      content: "Free yourself from platform limitations. GroupDocs.Total provides cross-platform compatibility, allowing you to deliver optimal performance and solution availability to users on any system where .NET can be installed."

############################# Platforms ############################
platforms:
  enable: true
  title: "Platform independence"
  description: "GroupDocs.Total for .NET supports the following operating systems, frameworks and package managers"
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
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "Supported file formats"
  description: |
    GroupDocs.Total for .NET supports operations with the following [file formats](https://docs.groupdocs.com/total/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument and text formats
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
        ### Images, Graphics & Diagrams
        * **Raster images:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Other        
        * **Web:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Archives:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Other:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Total features"
  description: "Comprehensively manage, render, and convert PDFs and Office Documents"

  items:
    # feature loop
    - icon: "viewer"
      title: "Extensive File Viewing"
      content: "Comprehensive document viewing for over 180 formats, including HTML, images, and PDF."

    # feature loop
    - icon: "conversion"
      title: "Format Conversion"
      content: "Seamless conversion between various document formats without external tools."

    # feature loop
    - icon: "annotation"
      title: "Interactive Annotation"
      content: "Advanced annotation capabilities for text and image elements within documents."

    # feature loop
    - icon: "comparison"
      title: "Content Comparison"
      content: "Precise document comparison, highlighting differences in content and style."

    # feature loop
    - icon: "signature"
      title: "Signature Flexibility"
      content: "Versatile signature options, including text, image, and digital signatures."

    # feature loop
    - icon: "assembly"
      title: "Template-Based Document Creation"
      content: "Automated document generation from templates and external data sources."

    # feature loop
    - icon: "metadata"
      title: "Metadata Management"
      content: "Robust metadata access and manipulation for enhanced document control."

    # feature loop
    - icon: "search"
      title: "Advanced Search"
      content: "Powerful search functionality with support for fuzzy and synonym algorithms."

    # feature loop
    - icon: "watermark"
      title: "Watermark Control"
      content: "Effortless document watermark management, offering customization and extraction features."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Code samples"
  description: "Some real-world scenarios of GroupDocs.Total for .NET usage"
  items:
    # code sample loop
    - title: "Secure and organize contracts: Apply watermarks and manage metadata in DOCX file"
      content: |
        Efficiently protect and organize your Word documents with this comprehensive code example. The sample below empowers you to implement robust watermarking and metadata management within your contract workflow for enhanced security and information management. It demonstrates how to: <br><br>
        <b>Apply a Custom Watermark:</b> Add a prominent 'Contract Draft' watermark to the document for visual clarity and protection. [Customize the watermark](https://docs.groupdocs.com/watermark/net/basic-usage/customize/) with font, color, opacity, and alignment options. <br><br>
        <b>Enhance Metadata:</b> Easily [modify document metadata](https://docs.groupdocs.com/metadata/net/working-with-metadata-in-wordprocessing-documents/) to include essential details like author, creation time, company, category, and keywords for improved organization and searchability.
       
        {{< landing/code title="C#">}}
        ```csharp {style=abap}  
        using GroupDocs.Metadata;
        using GroupDocs.Watermark;
        using GroupDocs.Watermark.Common;
        using GroupDocs.Watermark.Watermarks;
        
        // Load your document into watermarker
        using (Watermarker watermarker = new Watermarker("contract.docx"))
        {
            // Set the desired text and font for the watermark
            TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 60, FontStyle.Bold));
            
            // Choose font color and text opacity, rotation and alignments
            watermark.ForegroundColor = Color.DarkGreen;
            watermark.Opacity = 0.5;
            watermark.HorizontalAlignment = HorizontalAlignment.Center;
            watermark.VerticalAlignment = VerticalAlignment.Center;
            
            // Apply the watermark
            watermarker.Add(watermark);
            
            // Save the resulting document
            watermarker.Save("watermarked-contract.docx");
        }

        using (Metadata metadata = new Metadata("watermarked-contract.docx"))
        {
          var root = metadata.GetRootPackage<WordProcessingRootPackage>();

          // Update document metadata properties
          root.DocumentProperties.Author = "Name Surname";
          root.DocumentProperties.CreatedTime = DateTime.Now;
          root.DocumentProperties.Company = "Company Name";
          root.DocumentProperties.Category = "Work materials";
          root.DocumentProperties.Keywords = "contract, watermarked";

          // Save document with updated metadata
          metadata.Save("contract-final.docx");
        }        
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Streamlined Document Redaction"
      content: |
        <b>Scenario:</b> A large legal firm frequently processes diverse documents containing confidential client information that must be redacted before sharing with third-parties or for public disclosure. Manually redacting this sensitive information can be tedious, time-consuming, and prone to human error. To ensure efficiency, accuracy, and compliance with data protection regulations, the legal firm seeks an automated solution to streamline the document redaction process. 
        
        <br>

        <b>Solution:</b>
        GroupDocs.Total automates the process, triggering redaction upon receiving a document. Furthermore, [flexible options](https://docs.groupdocs.com/redaction/net/text-redactions/) empower customization by allowing you to set rules, choose redaction modes (e.g., blackout, replace with asterisks), and specify specific sections or pages for redaction. Finally, [user-friendly output](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) generates redacted documents in PDF format for easy sharing and review, while enhanced security and auditability ensure the entire process is documented for compliance and accountability. 
        <br><br>
        This comprehensive solution empowers legal professionals and other organizations to significantly reduce redaction time and costs, minimize human error, and consistently handle sensitive information with confidence.        
              
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Redaction;
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;

        // Load document with private data into redactor 
        using (Redactor redactor = new Redactor("customer-info.docx"))
        {
          // Setup and customize redaction options 
          redactor.Apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
          // Apply redactions and save result 
          redactor.Save();
        }

        // Load redacted file for review 
        using (var viewer = new Viewer("customer-info.docx"))
        {
          // Setup PDF as desired viewing format       
          var viewOptions = new PdfViewOptions("redacted-info.pdf");

          // Save document into PDF      
          viewer.View(viewOptions);
        }
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs products reviews"
# description: "Don't just take our word for it. See what other developers say about our APIs"

# items:
#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Excellent service and excellent products. They were extremely helpful and responsive during the GroupDocs.Viewer for .NET implementation process, can’t recommend them highly enough."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Total"
#     content: "After implementing and using GroupDocs.Viewer for Java in the project it looks to be working very well. I have tested with a lot of documents and so far so good. Everything I’ve thrown at it renders nicely and looks just as good as it would in a PDF viewer or MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---