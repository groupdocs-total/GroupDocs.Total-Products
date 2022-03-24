---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Total"
product_tag: "total"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "API C# .NET para ver, convertir, anotar, firmar, automatizar, marcar con marca de agua, redactar y buscar formatos de archivo"
head_description: "API y bibliotecas de manipulación de documentos GroupDocs .NET. Consuma cualquier API en una aplicación .NET para generar, manipular o convertir más de 50 documentos."

############################# Header ############################
title: ".NET API de automatización de documentos"
description: "API para ver, exportar, anotar, comparar, firmar, automatizar y buscar documentos en sus aplicaciones .NET."
button:
    enable: true

############################# SubMenu ############################
submenu:
  enable: true
  
  left:
      img_alt: "GroupDocs.Total for .NET"
      image: "/border/groupdocs-total-net.svg"
      product: "GroupDocs.Total"
      platform: ".NET"

  middle:
      button:
          # button loop
          - link: "#overview"
            text: "Visión de conjunto"

          # button loop
          - link: "#products"
            text: "productos"

          # button loop
          - link: "#features"
            text: "Características"

          # button loop
          - link: "#support"
            text: "Support"

          # button loop
          - link: "https://purchase.groupdocs.com/pricing/total/net"
            text: "Precios"

  right:
      link_download: "https://downloads.groupdocs.com/total"
      link_learn: "https://docs.groupdocs.com/total/net/"
      link_buy: "https://purchase.groupdocs.com"

############################# Visión de conjunto ############################
overview:
    enable: true
    content: "GroupDocs.Total para .NET es una compilación de todas las API de .NET que ofrece GroupDocs. Lo compilamos a diario para asegurarnos de que contenga las versiones más actualizadas de cada una de nuestras API de manipulación de documentos .NET.
    
    Con GroupDocs.Total para .NET, los desarrolladores pueden usar todas nuestras API con una sola licencia. Sin embargo, también puede solicitar cualquier API individual. "

############################# productos ############################
products:
    enable: true
    title: "productos"
    description: "GroupDocs.Total para .NET incluye las siguientes API de manipulación de documentos para .NET:"

    product:
        # product loop
        - image: "/border/groupdocs-viewer-net.svg"
          img_alt: "GroupDocs.Viewer for .NET"
          name: "GroupDocs.Viewer for .NET"
          content: "Potente API de visor de documentos para renderizar, ver y mostrar documentos de más de 50 formatos de archivo. Procesa de forma integral todo el documento, eficientemente un documento parcial o un rango específico de páginas/celdas. Renderice capas de documentos individuales, con o sin anotaciones y comentarios para los formatos de archivo admitidos."
          link: "/viewer/net/"

        # product loop
        - image: "/border/groupdocs-annotation-net.svg"
          img_alt: "GroupDocs.Annotation for .NET"
          name: "GroupDocs.Annotation for .NET"
          content: "API de administración de anotaciones para crear y manipular varios tipos de anotaciones, como área, texto, polilínea, punto, subrayado, etc. Le presenta un conjunto completo de herramientas de marcado para resaltar, tachar, etiquetar y comentar texto e imágenes. . Imprima los documentos anotados o expórtelos a PDF junto con las anotaciones."
          link: "/annotation/net/"

          # product loop
        - image: "/border/groupdocs-conversion-net.svg"
          img_alt: "GroupDocs.Conversion for .NET"
          name: "GroupDocs.Conversion for .NET"
          content: "API integral de conversión de documentos para configurar y convertir documentos entre más de 50 formatos de archivo. Con funciones como renderizar el encabezado del correo electrónico durante la conversión desde el correo electrónico, establecer directorios de fuentes personalizadas, configurar y colocar marcas de agua y métodos de conversión avanzados, etc. esta API es mucho más que una simple herramienta de conversión de archivos.."
          link: "/conversion/net/"

          # product loop
        - image: "/border/groupdocs-comparison-net.svg"
          img_alt: "GroupDocs.Comparison for .NET"
          name: "GroupDocs.Comparison for .NET"
          content: "API de verificación de diferencias de documentos para comparar tanto el contenido como los estilos de texto. Elija el nivel de detalle para el proceso de comparación. Aplicar o rechazar cambios después del análisis de diferencias. Obtenga documentos a través de un archivo o transmisión. Especifique el separador de palabras y el color de fuente para estilizar el texto comparado. Comparar archivos protegidos con contraseña."
          link: "/comparison/net/"

          # product loop
        - image: "/border/groupdocs-signature-net.svg"
          img_alt: "GroupDocs.Signature for .NET"
          name: "GroupDocs.Signature for .NET"
          content: "API de manipulación de firma electrónica para firmar documentos digitales de varios formatos. Obtener todos los certificados registrados presentes en el sistema. Aplique firmas de muchos tipos, como texto, código de barras, imagen, código QR, etc. Realice búsquedas simples y avanzadas para localizar las firmas deseadas. Configure las propiedades de la firma, como sombra, alineación, dimensiones y mucho más."
          link: "/signature/net/"

          # product loop
        - image: "/border/groupdocs-assembly-net.svg"
          img_alt: "GroupDocs.Assembly for .NET"
          name: "GroupDocs.Assembly for .NET"
          content: "Automatización de documentos y API de generación de informes mediante la creación y personalización de plantillas para formatos admitidos. Manipule datos utilizando fórmulas y operaciones de datos secuenciales, formatee cadenas en la sintaxis de plantilla, establezca formato ordinal, cardinal, alfabético y numérico. Definir variables; inserte contenido de forma dinámica en informes con formato condicional, etc."
          link: "/assembly/net/"

          # product loop
        - image: "/border/groupdocs-metadata-net.svg"
          img_alt: "GroupDocs.Metadata for .NET"
          name: "GroupDocs.Metadata for .NET"
          content: "API de acceso y manipulación de metadatos para leer, editar, reemplazar y eliminar metadatos de varios tipos de documentos. Compare las propiedades de los metadatos de dos archivos para identificar sus similitudes y diferencias. Exporte metadatos a Excel, CSV o DataSet. Detecte el tipo MIME de un archivo específico o secuencia de archivos. Elimina la información de ubicación de las fotos. Reduce el consumo de memoria de los archivos."
          link: "/metadata/net/"

          # product loop
        - image: "/border/groupdocs-search-net.svg"
          img_alt: "GroupDocs.Search for .NET"
          name: "GroupDocs.Search for .NET"
          content: "API de búsqueda de documentos y texto que ofrece funciones de búsqueda básicas a avanzadas, como la creación y combinación de múltiples índices, la búsqueda a través de Sencillo, Boolean, Fuzzy, Expresión regular (regex) y otros tipos de consulta. Aplique una búsqueda rápida, confiable e inteligente a archivos, documentos y correos electrónicos. Búsqueda basada en términos homofónicos, sinónimos, rango de fechas, comodines y distinción entre mayúsculas y minúsculas."
          link: "/search/net/"

          # product loop
        - image: "/border/groupdocs-parser-net.svg"
          img_alt: "GroupDocs.Parser for .NET"
          name: "GroupDocs.Parser for .NET"
          content: "API de extractor de texto que admite la extracción de metadatos y texto sin procesar, formateado y estructurado de formatos de archivo compatibles. Analizar documentos protegidos por contraseña. Elija entre extracción de texto rápida o estándar. El formateador Markdown y HTML admite el formateo de fuentes, hipervínculos, encabezados, listas y tablas. Obtenga datos del contenedor de correo electrónico (Exchange Web Server, POP3, IMAP)."
          link: "/parser/net/"

          # product loop
        - image: "/border/groupdocs-watermark-net.svg"
          img_alt: "GroupDocs.Watermark for .NET"
          name: "GroupDocs.Watermark for .NET"
          content: "Aplicación de marca de agua digital y API de manipulación para aplicar nuevas marcas de agua, buscar y eliminar marcas de agua existentes de documentos de formatos compatibles. Bloquee las marcas de agua para restringir la edición. Reemplace las marcas de agua existentes. Proteja la marca de agua de texto usando caracteres ilegibles en las presentaciones. Modifique las propiedades de la forma, como texto alternativo, ángulo de rotación, etc. en la presentación."
          link: "/watermark/net/"

          # product loop
        - image: "/border/groupdocs-editor-net.svg"
          img_alt: "GroupDocs.Editor for .NET"
          name: "GroupDocs.Editor for .NET"
          content: "API del editor de documentos para cargar documentos de formato de archivo compatible, convertirlo a HTML, enviar HTML a un editor de HTML externo, guardar el HTML en su formato de archivo original. Obtenga por separado los recursos adjuntos con cualquier documento. Obtenga contenido CSS del documento HTML. Obtenga HTML DOM del contenido de la cadena y conviértalo en documento. Aplicar seguridad al documento resultante."
          link: "/editor/net/"

          # product loop
        - image: "/border/groupdocs-merger-net.svg"
          img_alt: "GroupDocs.Merger for .NET"
          name: "GroupDocs.Merger for .NET"
          content: "API de fusión y división de documentos para combinar, dividir, reorganizar, intercambiar, recortar y eliminar una sola página o una colección de páginas, diapositivas o diagramas. Configure o elimine la protección con contraseña para formatos de archivo conocidos y desconocidos. Unir o dividir documentos individuales o por lotes. Recorte el documento eliminando páginas, diapositivas o diagramas específicos."
          link: "/merger/net/"

          # product loop
        - image: "/border/groupdocs-redaction-net.svg"
          img_alt: "GroupDocs.Redaction for .NET"
          name: "GroupDocs.Redaction for .NET"
          content: "API de redacción y saneamiento de documentos para redactar, eliminar u ocultar información clasificada, contenido y metadatos de documentos, hojas de trabajo, archivos PDF y diapositivas."
          link: "/redaction/net/"

          # product loop
        - image: "/border/groupdocs-classification-net.svg"
          img_alt: "GroupDocs.Classification for .NET"
          name: "GroupDocs.Classification for .NET"
          content: "API de clasificación de documentos y texto sin procesar para aplicaciones .NET. Clasifique contenido y formatos de documentos como Microsoft Office Word, PDF, OpenDocument, RTF y Text utilizando varias taxonomías, incluidos documentos e IAB-2. Personalice fácilmente los resultados clasificados utilizando un montón de funciones avanzadas según sus requisitos."
          link: "/classification/net/"

############################# Características ############################
features:
    enable: true
    title: "Advanced API Características"

    feature:
      # feature loop
      - icon: "fas fa-eye"
        content: "Ver cualquier documento de formato en su formato original o en formato HTML, imágenes o PDF"

      # feature loop
      - icon: "fas fa-file"
        content: "Anote cualquier documento PDF, DOCX, XLSX y PPTX"
      
      # feature loop
      - icon: "fas fa-file-export"
        content: "Exportar anotaciones a un archivo PDF o Word separado"

      # feature loop
      - icon: "fas fa-bolt"
        content: "La API de conversión sobre la marcha más rápida"

      # feature loop
      - icon: "fas fa-clone"
        content: "Conversión por lotes de varios archivos"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Compara el contenido de las diferencias en palabras y párrafos"

      # feature loop
      - icon: "fas fa-file-contract"
        content: "Resumen de diferencias separadas al usar la API de comparación"

      # feature loop
      - icon: "fas fa-signature"
        content: "Múltiples propiedades de firma"

      # feature loop
      - icon: "fas fa-file-signature"
        content: "Configure la firma en páginas arbitrarias como primera, última, par, impar, etc."

      # feature loop
      - icon: "fas fa-server"
        content: "Genere documentos multiformato a partir de más de una fuente de datos"

      # feature loop
      - icon: "fas fa-key"
        content: "Operaciones de metadatos integradas y personalizadas en forma de pares clave/valor"

      # feature loop
      - icon: "fas fa-file-download"
        content: "Exportar metadatos adjuntos con formatos de archivo compatibles"

      # feature loop
      - icon: "fab fa-searchengin"
        content: "Múltiples métodos de búsqueda básicos y avanzados"

      # feature loop
      - icon: "fas fa-search"
        content: "Fuzzy and Búsqueda de sinónimos"

      # feature loop
      - icon: "fas fa-search-minus"
        content: "Buscar y eliminar marca de agua de texto/imagen"

      # feature loop
      - icon: "fas fa-file-image"
        content: "Agregar marca de agua a las imágenes dentro de un documento"

      # feature loop
      - icon: "fas fa-file-alt"
        content: "Extraer texto estructurado y resaltado"
      
      # feature loop
      - icon: "fas fa-file-archive"
        content: "Obtiene texto de contenedores que contienen otros archivos, como archivos zip"

      # feature loop
      - icon: "fas fa-file-invoice"
        content: "Transformación directa e inversa de documentos"

      # feature loop
      - icon: "fas fa-edit"
        content: "Editar múltiples formatos de documentos"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: false
    title: "GroupDocs.Total para .NET ofrece soluciones individuales para"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for .NET"
          image: "/border/groupdocs-viewer-net.svg"
          product: "GroupDocs.Viewer"
          platform: ".NET"
          link: "/viewer/net/"
        
        # solution loop
        - img_alt: "GroupDocs.Annotation for .NET"
          image: "/border/groupdocs-annotation-net.svg"
          product: "GroupDocs.Annotation"
          platform: ".NET"
          link: "/annotation/net/"

        # solution loop
        - img_alt: "GroupDocs.Conversion for .NET"
          image: "/border/groupdocs-comparison-net.svg"
          product: "GroupDocs.Conversion"
          platform: ".NET"
          link: "/conversion/net/"

        # solution loop
        - img_alt: "GroupDocs.Comparison for .NET"
          image: "/border/groupdocs-comparison-net.svg"
          product: "GroupDocs.Comparison"
          platform: ".NET"
          link: "/comparison/net/"

        # solution loop
        - img_alt: "GroupDocs.Signature for .NET"
          image: "/border/groupdocs-signature-net.svg"
          product: "GroupDocs.Signature"
          platform: ".NET"
          link: "/signature/net/"

        # solution loop
        - img_alt: "GroupDocs.Assembly for .NET"
          image: "/border/groupdocs-assembly-net.svg"
          product: "GroupDocs.Assembly"
          platform: ".NET"
          link: "/assembly/net/"

        # solution loop
        - img_alt: "GroupDocs.Metadata for .NET"
          image: "/border/groupdocs-metadata-net.svg"
          product: "GroupDocs.Metadata"
          platform: ".NET"
          link: "/metadata/net/"

        # solution loop
        - img_alt: "GroupDocs.Search for .NET"
          image: "/border/groupdocs-search-net.svg"
          product: "GroupDocs.Search"
          platform: ".NET"
          link: "/search/net/"

        # solution loop
        - img_alt: "GroupDocs.Parser for .NET"
          image: "/border/groupdocs-parser-net.svg"
          product: "GroupDocs.Parser"
          platform: ".NET"
          link: "/parser/net/"

        # solution loop
        - img_alt: "GroupDocs.Watermark for .NET"
          image: "/border/groupdocs-watermark-net.svg"
          product: "GroupDocs.Watermark"
          platform: ".NET"
          link: "/watermark/net/"

        # solution loop
        - img_alt: "GroupDocs.Editor for .NET"
          image: "/border/groupdocs-editor-net.svg"
          product: "GroupDocs.Editor"
          platform: ".NET"
          link: "/editor/net/"

        # solution loop
        - img_alt: "GroupDocs.Merger for .NET"
          image: "/border/groupdocs-merger-net.svg"
          product: "GroupDocs.Merger"
          platform: ".NET"
          link: "/merger/net/"

        # solution loop
        - img_alt: "GroupDocs.Redaction for .NET"
          image: "/border/groupdocs-redaction-net.svg"
          product: "GroupDocs.Redaction"
          platform: ".NET"
          link: "/redaction/net/"

        # solution loop
        - img_alt: "GroupDocs.Classification for .NET"
          image: "/border/groupdocs-classification-net.svg"
          product: "GroupDocs.Classification"
          platform: ".NET"
          link: "/classification/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
