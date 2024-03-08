---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Total"
product_tag: "total"

############################# Head ############################
head_title: "Document Automation APIs | On Premise APIs and online services"
head_description: "Automate your document manipulation easily and free"

############################# Header ##########################
title: "Master document automation with all-in-one suite"
description: |
  Simplify repetitive document tasks and streamline your workflows with just a few lines of code. Powerful APIs make integration effortless, empowering you to focus on innovation, not infrastructure.

  Convert, sign, view, annotate - conquer any document task with minimal code. From Word to PDF, Excel to images, handle everything seamlessly. Less code, bigger impact.

  Automate document tasks, boost efficiency, and move fast with lightning-speed integration. Save time and resources, focusing on what truly matters to your business.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Choose your platform"
  title: "Supported platforms"
  description: "GroupDocs.Total library supports the following operating systems and frameworks"
  details_link_title: "Learn more"
  items:
    # supported_platforms loop
    - title: ".NET"
      description: "GroupDocs.Total for .NET"
      color: "blue"
      tag: "net"
      link: "/total/net/"
      features_link: "https://docs.groupdocs.com/total/net/system-requirements/"
      features:
        # features loop
        - content: ".NET Framework 4.6.2+  <br>  .NET Core 3.1  <br>  .NET 6+"
          rows: "3"
        # features loop
        - content: "Windows, Linux"
          rows: "1"
        # features loop
        - content: "200+ file formats"
          rows: "1"
        # features loop
        - content: "Visual Studio <br> VS Code <br> Rider"
          rows: "15"
    
    # supported_platforms loop
    - title: "Java"
      description: "GroupDocs.Total for Java"
      color: "red"
      tag: "java"
      link: "/total/java/"
      features_link: "https://docs.groupdocs.com/total/java/system-requirements/"
      features:
        # features loop
        - content: "J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"       
        # features loop
        - content: "200+ file formats"
          rows: "1"
        # features loop
        - content:  "Eclipse <br> NetBeans <br> IntelliJ Idea"
          rows: "3"

############################# Features ############################

features:
  enable: true
  title: "GroupDocs.Total's feature set"
  description: "Single solution that unifies the functionality of all individual GroupDocs products under one roof and manages any document task without third-party software."

  items:
    # feature loop
    - icon: "view"
      title: "View documents and images"
      content: "Render files to view them in HTML, PDF, PNG, and JPEG formats."

    # feature loop
    - icon: "convert"
      title: "Convert between formats"
      content: "Transform files from different source to various target formats."

    # feature loop
    - icon: "merge"
      title: "Merge multiple files into one"
      content: "Seamlessly combine multiple PDF, Office and other into a single document."
    
    # feature loop
    - icon: "settings"
      title: "More products and features"
      content: "Explore all set of GroupDocs document automation APIs: compare, e-sing, search, watermark and more!"


############################# Code samples ############################
# code_samples:
#   enable: true
#   title: "GroupDocs.Total code samples"
#   description: "Some use cases of typical GroupDocs.Total operations in C#, Java, TypeScript"
#   items:
#     # code sample loop
#     - title: "How to render DOCX files to PDF"
#       content: |
#         Render DOCX documents to PDF without Microsoft Word or other software installed. Easily load and view DOCX files within your application, whether it is a web or desktop application. Here is an example of how to render a DOCX file to PDF:
#       samples:
#         - language: "C#"
#           color: "blue"
#           content: |
#             ```csharp {style=abap}   
#             // Load DOCX file to render
#             using (Viewer viewer = new Viewer("sample.docx"))
#             {
#               // Render DOCX to a PDF file
#               PdfViewOptions viewOptions = new PdfViewOptions();
#               viewer.View(viewOptions);
#             }
#             ```
#         - language: "Java"
#           color: "red"
#           content: |
#             ```java {style=abap}   
#             import com.groupdocs.viewer.Viewer;
#             import com.groupdocs.viewer.options.PdfViewOptions;
#             // ...
#             // Load DOCX file to render
#             try (Viewer viewer = new Viewer("sample.docx")) {
#                 // Render DOCX to a PDF file
#                 PdfViewOptions viewOptions = new PdfViewOptions();
#                 viewer.view(viewOptions);
#             }
#             ```
#         - language: "TypeScript"
#           color: "green"
#           content: |
#             ```javascript {style=abap}  
#             // Load DOCX file to render
#             const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
#             // Render DOCX to a PDF file
#             const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
#             viewer.view(viewOptions)
#             ```


############################# Formats ############################
formats:
  enable: true
  title:  "200+ file formats supported"
  description: "GroupDocs.Total supports operations with the most popular [file formats](https://docs.groupdocs.com/total/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "In-depth metrics and statistical insights"
  description: "Dive into a detailed breakdown of our key figures, providing comprehensive metrics and statistical insights into our achievements, impact, and growth."

  items:
    # metrics loop
    - number: "200+"
      title: "Supported formats"
      content: "Easily view over 200 file formats including documents, images, and CAD drawings hassle-free. Break compatibility barriers and access diverse files effortlessly with our comprehensive viewing solution."
    # metrics loop
    - number: "550K"
      title: "NuGet downloads"
      content: "Our NuGet package solution has become a trusted and widely adopted resource in the developer community, providing seamless integration and valuable functionality for countless projects."

    # metrics loop
    - number: "10+"
      title: "Libraries"
      content: "Our product includes 10+ libraries, offering advanced features to optimize performance. These libraries are designed to fulfill different development needs with unparalleled capabilities."
    
    # metrics loop
    - number: "100+"
      title: "Happy customers"
      content: "Serving the most iconic brands around the globe. Discover why hundreds love GroupDocs.Total! Explore seamless navigation, convenient collaboration, and unparalleled ease of use. Join now!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Our happy customers"
  description: "GroupDocs libraries are employed by globally renowned and distinguished brands across the world."

  items:
    # customers loop
    - title: "BenQ Corporation"
      logo: "benq"
    # customers loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
    # customers loop
    - title: "AT&T Inc."
      logo: "att"
    # customers loop
    - title: "AstraZeneca"
      logo: "astrazeneca"
    # customers loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
    # customers loop
    - title: "Roche Holding AG"
      logo: "roche"
    # customers loop
    - title: "Capita"
      logo: "capita"
    # customers loop
    - title: "Axa S.A."
      logo: "axa"
    # customers loop
    - title: "Instructure Inc."
      logo: "instructure"
     # customers loop
    - title: "Wipro"
      logo: "wipro"



############################# Actions ############################

actions:
  enable: true
  title: "Ready to get started?"
  description: "Try GroupDocs.Total features for free or request a license"

  items:
    #  loop
    - title: ".NET"
      link: "/total/net/"
      color: "blue"
        #  loop
    - title: "Java"
      link: "/total/java/"
      color: "red"


############################# Faq ############################

faq:
  enable: true
  title: "Common questions and concerns"
  description: "Find answers to common inquiries in our FAQ section to quickly address your queries and concerns."

  items:
    #  loop
    - question: "What is GroupDocs.Total, and how is it different from other GroupDocs products?"
      answer: |
        GroupDocs.Total is a comprehensive suite that combines the functionalities of all individual GroupDocs products into a single package. This offers several advantages: <br><br>
        <ul>
          <li>
            <b>Unified features:</b> You have access to all document processing capabilities, including viewing, conversion, merging, annotation, signing, and more, within a single API. <br><br>
          </li>
          <li>
            <b>Enhanced compatibility:</b> GroupDocs.Total ensures consistent and reliable performance across all supported file formats and platforms, eliminating compatibility issues that might arise when using separate products. <br><br>
          </li>
          <li>
            <b>Optimized package sizes:</b> The suite comes as a single, compact package, reducing resource consumption and simplifying integration into your applications compared to using individual products with separate installations.
          </li>
        <ul>

    #  loop
    - question: "Why to prefer GroupDocs.Total instead of buying individual GroupDocs products?"
      answer: |
        Purchasing a single GroupDocs.Total license typically costs less than buying licenses for two or more individual GroupDocs products. <br>
        This translates to several key benefits for you: <br><br>
        <b>Cost savings:</b> GroupDocs.Total offers a significant discount compared to purchasing individual products, allowing you to stretch your budget further. <br><br>
        <b>Simplified management:</b> With GroupDocs.Total, you manage everything under one license, eliminating the need to track and maintain multiple licenses for different products. This simplifies your administrative tasks and reduces overall costs. <br><br>
        If you're looking for a cost-effective and feature-rich solution for your document management needs, GroupDocs.Total is the perfect choice.

    #  loop
    - question: "How do I get started with GroupDocs.Total?"
      answer: |
        You can start with a free trial to explore the features and see if it meets your needs. GroupDocs also offers various [documentation](https://docs.groupdocs.com/total/) resources and [tutorials](https://groupdocs.github.io) to help you get started with integration and development.
        
    #  loop
    - question: "Does GroupDocs.Total offer any technical support?"
      answer: |
        Yes, GroupDocs offers comprehensive technical support to ensure your success with GroupDocs.Total. They have two options: <br><br>
        <b>[Free Support Forum](https://forum.groupdocs.com):</b> This forum allows you to connect with GroupDocs staff, who can answer your questions and offer solutions based on their experience. It's a great resource for common issues and general inquiries. <br><br>
        <b>[Paid Support Helpdesk](https://helpdesk.groupdocs.com):</b> This option provides support on a priority basis. If you encounter complex issues or require faster resolutions, paid support offers personalized assistance and quicker response times. <br><br>
        By providing both free and paid options, GroupDocs caters to different needs and budgets, ensuring you have the support you need to thrive with GroupDocs.Total.

    #  loop
    - question: "Does GroupDocs.Total require additional software for document manipulation?"
      answer: |
        GroupDocs.Total is a self-contained suite and does not require any additional third-party software for basic document manipulation tasks like viewing, converting, annotating, or signing. However, depending on specific features you use (e.g., OCR for scanned documents), external libraries might be needed.

############################# Cloud and Apps ############################

cloud_links:
  enable: true
  title: "GroupDocs.Total solutions"
  description: "Supercharge document processing in your applications with our cloud REST API and free online apps"

  items:
    #  loop
    - icon: "groupdocs_total-cloud"
      title: "GroupDocs.Total Cloud"
      link: "https://products.groupdocs.cloud/total"
      content: "Robust cloud solutions to efficiently automate processing of Microsoft Office, PDF document in your applications."

    #  loop
    - icon: "groupdocs_total-apps"
      title: "GroupDocs.Total Online Apps"
      link: "https://products.groupdocs.app"
      content: "Free online web apps to view and edit document content, compare and merge different Microsoft Office, OpenOffice, images & other popular file formats."    

    #  loop
    - icon: "groupdocs_total-windows"
      title: "GroupDocs.Total Windows"
      link: "https://products.groupdocs.app/total/windows"
      content: "Offline apps to convert, annotate, compare, sign, assemble, parse, classify, redact and search documents on any operating system."   

---