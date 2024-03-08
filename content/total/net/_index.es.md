---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: es
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
head_title: "Biblioteca de automatización de documentos todo en uno para aplicaciones .NET"
head_description: "GroupDocs.Total para .NET es un conjunto de API de automatización de documentos todo en uno para desarrolladores de .NET, que proporciona un conjunto completo de herramientas para trabajar con varios formatos de documentos, incluidos PDF, Word, Excel, imágenes, HTML, diagramas y más. ."

############################# Header ##########################
title: "Optimice la automatización de documentos<br> en sus aplicaciones .NET"
description: "Desbloquee la automatización de documentos: convierta, vea y compare, edite y firme entre más de 200 formatos fácilmente."
words:
  for: "for"

actions:
  main: "Descarga gratuita de NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Total"
  alt: "Licencia"
  alt_link: "https://purchase.groupdocs.com/pricing/total/net"
  title: "¿Listo para comenzar?"
  description: "Pruebe GroupDocs.Total funciones gratis o solicite una licencia"

release:
  title: "Versión {0} lanzada"
  notes: "Ver qué hay de nuevo"
  downloads: "Descargas"
  link: "https://releases.groupdocs.com/total/net/release-notes/latest/"

code:
  title: "Fusionar y ver archivos de Word en C#"
  more: "Más ejemplos"
  more_link: "https://github.com/groupdocs-total/GroupDocs.Total-for-.NET"
  install: "dotnet add package GroupDocs.Total"
  content: |
    ```csharp {style=abap} 
    // Cargue el archivo DOCX de origen
    using (Merger merger = new Merger("sample1.docx"))
    {
        // Agregue otro archivo DOCX para fusionar
        merger.Join("sample2.docx");

        // Fusionar archivos DOCX y guardar el resultado
        merger.Save("merged.docx");
    }

    // Cargue el archivo DOCX combinado en el visor
    using (var viewer = new Viewer("merged.docx"))
    {
        // Establecer opciones HTML de salida, un archivo por página
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // Renderice DOCX a HTML con recursos integrados        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Total de un vistazo"
  description: "Automatice la visualización de archivos, convierta, edite, compare, busque, agregue marcas de agua y otros flujos de trabajo en aplicaciones .NET"
  features:
    # feature loop
    - title: "Combine el poder de múltiples productos GroupDocs en una solución única e integral"
      content: | 
        Puede utilizar funciones de diferentes productos GroupDocs para crear un enfoque personalizado que satisfaga sus necesidades específicas.
        <br><br>
        Por ejemplo, puede convertir un archivo de Word a PDF y luego agregar una firma digital. O complete los datos de una plantilla de documento desde una base de datos, o extraiga texto de una imagen y luego tradúzcalo a otro idioma.
        <br><br>
        ¡Las posibilidades son infinitas!
          
    # feature loop
    - title: "Domina la diversidad de formatos de archivos"
      content: "GroupDocs.Total para .NET desbloquea la compatibilidad con más de 200 formatos de archivos, lo que le permite procesar documentos de todos los tipos populares. Desde formatos de Office como Word y Excel hasta imágenes, códigos y archivos cifrados, lo tenemos cubierto."

    # feature loop
    - title: "Soporte multiplataforma"
      content: "Libérate de las limitaciones de la plataforma. GroupDocs.Total proporciona compatibilidad multiplataforma, lo que le permite ofrecer un rendimiento óptimo y disponibilidad de la solución a los usuarios en cualquier sistema donde se pueda instalar .NET."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independencia de plataforma"
  description: "GroupDocs.Total para .NET admite los siguientes sistemas operativos, marcos y administradores de paquetes"
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
  title: "Formatos de archivo admitidos"
  description: |
    GroupDocs.Total para .NET admite operaciones con los siguientes [formatos de archivo](https://docs.groupdocs.com/total/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument y formatos de texto
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
        ### Imágenes, gráficos y diagramas
        * **Imágenes rasterizadas:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Otro        
        * **Web:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Archivo:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Otro:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Total funciones"
  description: "Administre, renderice y convierta de manera integral archivos PDF y documentos de Office"

  items:
    # feature loop
    - icon: "viewer"
      title: "Amplia visualización de archivos"
      content: "Visualización completa de documentos para más de 180 formatos, incluidos HTML, imágenes y PDF."

    # feature loop
    - icon: "conversion"
      title: "Conversión de formato"
      content: "Conversión perfecta entre varios formatos de documentos sin herramientas externas."

    # feature loop
    - icon: "annotation"
      title: "Anotación interactiva"
      content: "Capacidades avanzadas de anotación para elementos de texto e imagen dentro de documentos."

    # feature loop
    - icon: "comparison"
      title: "Comparación de contenido"
      content: "Comparación precisa de documentos, destacando diferencias en contenido y estilo."

    # feature loop
    - icon: "signature"
      title: "Flexibilidad de firma"
      content: "Opciones de firma versátiles, que incluyen texto, imagen y firmas digitales."

    # feature loop
    - icon: "assembly"
      title: "Creación de documentos basada en plantillas"
      content: "Generación automatizada de documentos a partir de plantillas y fuentes de datos externas."

    # feature loop
    - icon: "metadata"
      title: "Gestión de metadatos"
      content: "Sólido acceso y manipulación de metadatos para un mejor control de documentos."

    # feature loop
    - icon: "search"
      title: "Búsqueda Avanzada"
      content: "Potente funcionalidad de búsqueda con soporte para algoritmos difusos y sinónimos."

    # feature loop
    - icon: "watermark"
      title: "Control de marca de agua"
      content: "Gestión sencilla de marcas de agua de documentos, que ofrece funciones de personalización y extracción."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Ejemplos de código"
  description: "Algunos escenarios del mundo real de GroupDocs.Total para uso de .NET"
  items:
    # code sample loop
    - title: "Proteja y organice contratos: aplique marcas de agua y administre metadatos en archivos DOCX"
      content: |
        Proteja y organice eficientemente sus documentos de Word con este ejemplo de código completo. El siguiente ejemplo le permite implementar una gestión sólida de marcas de agua y metadatos dentro del flujo de trabajo de su contrato para mejorar la seguridad y la gestión de la información. Demuestra cómo: <br><br>
        <b>Aplicar una marca de agua personalizada:</b> Agregue una marca de agua destacada de 'Borrador de contrato' al documento para mayor claridad y protección visual. [Personalice la marca de agua](https://docs.groupdocs.com/watermark/net/basic-usage/customize/) con opciones de fuente, color, opacidad y alineación. <br><br>
        <b>Mejorar metadatos:</b> [Modifique los metadatos del documento](https://docs.groupdocs.com/metadata/net/working-with-metadata-in-wordprocessing-documents/) fácilmente para incluir detalles esenciales como autor, hora de creación, empresa, categoría y palabras clave para una mejor organización y capacidad de búsqueda.
       
        {{< landing/code title="C#">}}
        ```csharp {style=abap}  
        using GroupDocs.Metadata;
        using GroupDocs.Watermark;
        using GroupDocs.Watermark.Common;
        using GroupDocs.Watermark.Watermarks;
        
        // Cargue su documento en un marcador de agua
        using (Watermarker watermarker = new Watermarker("contract.docx"))
        {
            // Establezca el texto y la fuente deseados para la marca de agua.
            TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 60, FontStyle.Bold));
            
            // Elija el color de fuente y la opacidad, rotación y alineaciones del texto.
            watermark.ForegroundColor = Color.DarkGreen;
            watermark.Opacity = 0.5;
            watermark.HorizontalAlignment = HorizontalAlignment.Center;
            watermark.VerticalAlignment = VerticalAlignment.Center;
            
            // Aplicar la marca de agua
            watermarker.Add(watermark);
            
            // Guarde el documento resultante.
            watermarker.Save("watermarked-contract.docx");
        }

        using (Metadata metadata = new Metadata("watermarked-contract.docx"))
        {
          var root = metadata.GetRootPackage<WordProcessingRootPackage>();

          // Actualizar las propiedades de los metadatos del documento
          root.DocumentProperties.Author = "Name Surname";
          root.DocumentProperties.CreatedTime = DateTime.Now;
          root.DocumentProperties.Company = "Company Name";
          root.DocumentProperties.Category = "Work materials";
          root.DocumentProperties.Keywords = "contract, watermarked";

          // Guardar documento con metadatos actualizados
          metadata.Save("contract-final.docx");
        }        
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Redacción de documentos simplificada"
      content: |
        <b>Guión:</b> Una gran firma legal a menudo procesa diversos documentos que contienen información confidencial del cliente que debe redactarse antes de compartirla con terceros o para su divulgación pública. Redactar manualmente esta información confidencial puede resultar tedioso, llevar mucho tiempo y estar propenso a errores humanos. Para garantizar la eficiencia, la precisión y el cumplimiento de las normas de protección de datos, la firma legal busca una solución automatizada para agilizar el proceso de redacción de documentos. 
        
        <br>

        <b>Solución:</b>
        GroupDocs.Total automatiza el proceso, activando la redacción al recibir un documento. Además, las [opciones flexibles](https://docs.groupdocs.com/redaction/net/text-redactions/) permiten la personalización al permitirle establecer reglas, elegir modos de redacción (por ejemplo, oscurecer, reemplazar con asteriscos) y especificar secciones o páginas específicas para su redacción. Finalmente, [resultado fácil de usar](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) genera documentos redactados en formato PDF para compartirlos y revisarlos fácilmente, mientras que la seguridad y la auditabilidad mejoradas garantizan toda la información. El proceso está documentado para garantizar el cumplimiento y la rendición de cuentas. 
        <br><br>
        Esta solución integral permite a los profesionales legales y otras organizaciones reducir significativamente el tiempo y los costos de redacción, minimizar el error humano y manejar constantemente información confidencial con confianza.        
              
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Redaction;
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;

        // Cargar documento con datos privados en el redactor 
        using (Redactor redactor = new Redactor("customer-info.docx"))
        {
          // Configurar y personalizar las opciones de redacción 
          redactor.Apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
          // Aplicar redacciones y guardar el resultado. 
          redactor.Save();
        }

        // Cargar archivo redactado para revisión 
        using (var viewer = new Viewer("customer-info.docx"))
        {
          // Configure PDF como formato de visualización deseado       
          var viewOptions = new PdfViewOptions("redacted-info.pdf");

          // Guardar documento en PDF      
          viewer.View(viewOptions);
        }
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Reseñas de productos GroupDocs"
# description: "No confíe sólo en nuestra palabra. Vea lo que otros desarrolladores dicen sobre nuestras API"

# items:
#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Excelente servicio y excelentes productos. Fueron extremadamente útiles y receptivos durante el proceso de implementación de GroupDocs.Viewer para .NET, no puedo recomendarlos lo suficiente."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Después de implementar y utilizar GroupDocs.Viewer para Java en el proyecto, parece estar funcionando muy bien. He probado con muchos documentos y hasta ahora todo bien. Todo lo que le he añadido se reproduce muy bien y se ve tan bien como en un visor de PDF o MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---