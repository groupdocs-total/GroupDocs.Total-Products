---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Total"
product_tag: "total"

############################# Head ############################
head_title: "API de automatización de documentos | API locales y servicios en línea"
head_description: "Automatiza la manipulación de tus documentos de forma fácil y gratuita"

############################# Header ##########################
title: "Domine la automatización de documentos con una suite todo en uno"
description: |
  Simplifique las tareas documentales repetitivas y optimice sus flujos de trabajo con solo unas pocas líneas de código. Las potentes API facilitan la integración y le permiten centrarse en la innovación, no en la infraestructura.

  Convierta, firme, vea, anote: conquiste cualquier tarea de documento con un código mínimo. Desde Word hasta PDF, desde Excel hasta imágenes, maneje todo sin problemas. Menos código, mayor impacto.

  Automatice las tareas de documentos, aumente la eficiencia y avance rápido con una integración ultrarrápida. Ahorra tiempo y recursos, centrándote en lo que realmente importa para tu negocio.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Elige tu plataforma"
  title: "Plataformas compatibles"
  description: "La biblioteca GroupDocs.Total admite los siguientes sistemas operativos y marcos"
  details_link_title: "Aprende más"
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
        - content: "Más de 200 formatos de archivo"
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
        - content: "Más de 200 formatos de archivo"
          rows: "1"
        # features loop
        - content:  "Eclipse <br> NetBeans <br> IntelliJ Idea"
          rows: "3"

############################# Features ############################

features:
  enable: true
  title: "Conjunto de características de GroupDocs.Total"
  description: "Solución única que unifica la funcionalidad de todos los productos individuales de GroupDocs bajo un mismo techo y gestiona cualquier tarea documental sin software de terceros."

  items:
    # feature loop
    - icon: "view"
      title: "Ver documentos e imágenes."
      content: "Renderice archivos para verlos en formatos HTML, PDF, PNG y JPEG."

    # feature loop
    - icon: "convert"
      title: "Convertir entre formatos"
      content: "Transforme archivos de diferentes fuentes a varios formatos de destino."

    # feature loop
    - icon: "merge"
      title: "Fusionar varios archivos en uno"
      content: "Combine sin problemas varios PDF, Office y otros en un solo documento."
    
    # feature loop
    - icon: "settings"
      title: "Más productos y características"
      content: "Explore todo el conjunto de API de automatización de documentos de GroupDocs: comparación, canto electrónico, búsqueda, marca de agua y más."


############################# Code samples ############################
# code_samples:
#   enable: true
#   title: "GroupDocs.Total de ejemplos de código"
#   description: "Algunos casos de uso de operaciones típicas de GroupDocs.Total en C#, Java, TypeScript"
#   items:
#     # code sample loop
#     - title: "Cómo renderizar archivos DOCX a PDF"
#       content: |
#        Renderice documentos DOCX a PDF sin Microsoft Word u otro software instalado. Cargue y vea fácilmente archivos DOCX dentro de su aplicación, ya sea una aplicación web o de escritorio. A continuación se muestra un ejemplo de cómo convertir un archivo DOCX a PDF:
#       samples:
#         - language: "C#"
#           color: "blue"
#           content: |
#             ```csharp {style=abap}   
#             // Cargue el archivo DOCX para renderizar
#             using (Viewer viewer = new Viewer("sample.docx"))
#             {
#               // Renderizar DOCX a un archivo PDF
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
#             // Cargue el archivo DOCX para renderizar
#             try (Viewer viewer = new Viewer("sample.docx")) {
#                 // Renderizar DOCX a un archivo PDF
#                 PdfViewOptions viewOptions = new PdfViewOptions();
#                 viewer.view(viewOptions);
#             }
#             ```
#         - language: "TypeScript"
#           color: "green"
#           content: |
#             ```javascript {style=abap}  
#             // Cargue el archivo DOCX para renderizar
#             const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
#             // Renderizar DOCX a un archivo PDF
#             const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
#             viewer.view(viewOptions)
#             ```


############################# Formats ############################
formats:
  enable: true
  title:  "Más de 200 formatos de archivo compatibles"
  description: "GroupDocs.Total admite operaciones con los más populares [formatos de archivo](https://docs.groupdocs.com/total/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "Métricas detalladas y conocimientos estadísticos"
  description: "Sumérgete en un desglose detallado de nuestras cifras clave, proporcionando métricas completas y conocimientos estadísticos sobre nuestros logros, impacto y crecimiento."

  items:
    # metrics loop
    - number: "200+"
      title: "Formatos soportados"
      content: "Vea fácilmente más de 200 formatos de archivos, incluidos documentos, imágenes y dibujos CAD, sin complicaciones. Rompe las barreras de compatibilidad y accede a diversos archivos sin esfuerzo con nuestra solución de visualización integral."
    # metrics loop
    - number: "550K"
      title: "Descargas NuGet"
      content: "Nuestra solución de paquete NuGet se ha convertido en un recurso confiable y ampliamente adoptado en la comunidad de desarrolladores, brindando una integración perfecta y una funcionalidad valiosa para innumerables proyectos."

    # metrics loop
    - number: "10+"
      title: "Bibliotecas"
      content: "Nuestro producto incluye más de 10 bibliotecas que ofrecen funciones avanzadas para optimizar el rendimiento. Estas bibliotecas están diseñadas para satisfacer diferentes necesidades de desarrollo con capacidades incomparables."
    
    # metrics loop
    - number: "100+"
      title: "Clientes felices"
      content: "Sirviendo a las marcas más emblemáticas de todo el mundo. ¡Descubra por qué a cientos de personas les encanta GroupDocs.Total! Explore una navegación fluida, una colaboración cómoda y una facilidad de uso incomparable. ¡Únete ahora!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Nuestros clientes felices"
  description: "Las bibliotecas de GroupDocs son utilizadas por marcas distinguidas y reconocidas a nivel mundial en todo el mundo."

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
  title: "¿Listo para comenzar?"
  description: "Pruebe GroupDocs.Total funciones gratis o solicite una licencia"

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
  title: "Preguntas e inquietudes comunes"
  description: "Encuentre respuestas a consultas comunes en nuestra sección de preguntas frecuentes para abordar rápidamente sus consultas e inquietudes."

  items:
    #  loop
    - question: "¿Qué es GroupDocs.Total y en qué se diferencia de otros productos de GroupDocs?"
      answer: |
        GroupDocs.Total es una suite integral que combina las funcionalidades de todos los productos individuales de GroupDocs en un solo paquete. Esto ofrece varias ventajas.: <br><br>
        <ul>
          <li>
            <b>Funciones unificadas:</b> Tiene acceso a todas las capacidades de procesamiento de documentos, incluida la visualización, conversión, fusión, anotación, firma y más, dentro de una única API. <br><br>
          </li>
          <li>
            <b>Compatibilidad mejorada:</b> GroupDocs.Total garantiza un rendimiento consistente y confiable en todos los formatos de archivos y plataformas compatibles, eliminando los problemas de compatibilidad que pueden surgir al usar productos separados. <br><br>
          </li>
          <li>
            <b>Tamaños de paquete optimizados:</b> La suite se presenta como un paquete único y compacto, lo que reduce el consumo de recursos y simplifica la integración en sus aplicaciones en comparación con el uso de productos individuales con instalaciones separadas.
          </li>
        <ul>

    #  loop
    - question: "¿Por qué preferir GroupDocs.Total en lugar de comprar productos GroupDocs individuales?"
      answer: |
        Comprar una única licencia de GroupDocs.Total normalmente cuesta menos que comprar licencias para dos o más productos GroupDocs individuales. <br>
        Esto se traduce en varios beneficios clave para usted.: <br><br>
        <b>Ahorro de costes:</b> GroupDocs.Total ofrece un descuento significativo en comparación con la compra de productos individuales, lo que le permite estirar aún más su presupuesto. <br><br>
        <b>Gestión simplificada:</b> Con GroupDocs.Total, usted administra todo bajo una sola licencia, eliminando la necesidad de rastrear y mantener múltiples licencias para diferentes productos. Esto simplifica sus tareas administrativas y reduce los costos generales. <br><br>
        Si está buscando una solución rentable y rica en funciones para sus necesidades de gestión de documentos, GroupDocs.Total es la elección perfecta.

    #  loop
    - question: "¿Cómo empiezo con GroupDocs.Total?"
      answer: |
        Puede comenzar con una prueba gratuita para explorar las funciones y ver si satisface sus necesidades. GroupDocs también ofrece varios recursos de [documentación](https://docs.groupdocs.com/total/) y [tutoriales](https://groupdocs.github.io) para ayudarle a comenzar con la integración y el desarrollo.
        
    #  loop
    - question: "¿GroupDocs.Total ofrece algún soporte técnico?"
      answer: |
        Sí, GroupDocs ofrece soporte técnico integral para garantizar su éxito con GroupDocs.Total. Tienen dos opciones: <br><br>
        <b>[Foro de soporte gratuito](https://forum.groupdocs.com):</b> Este foro le permite conectarse con el personal de GroupDocs, quienes pueden responder sus preguntas y ofrecer soluciones basadas en su experiencia. Es un gran recurso para problemas comunes y consultas generales. <br><br>
        <b>[Servicio de asistencia técnica de pago](https://helpdesk.groupdocs.com):</b> Esta opción proporciona soporte de forma prioritaria. Si encuentra problemas complejos o necesita resoluciones más rápidas, el soporte pago ofrece asistencia personalizada y tiempos de respuesta más rápidos. <br><br>
        Al ofrecer opciones gratuitas y de pago, GroupDocs se adapta a diferentes necesidades y presupuestos, lo que garantiza que tenga el soporte que necesita para prosperar con GroupDocs.Total.

    #  loop
    - question: "¿GroupDocs.Total requiere software adicional para la manipulación de documentos?"
      answer: |
        GroupDocs.Total es una suite independiente y no requiere ningún software adicional de terceros para tareas básicas de manipulación de documentos como ver, convertir, anotar o firmar. Sin embargo, dependiendo de las funciones específicas que utilice (por ejemplo, OCR para documentos escaneados), es posible que necesite bibliotecas externas.

############################# Cloud and Apps ############################

cloud_links:
  enable: true
  title: "GroupDocs. Soluciones totales"
  description: "Potencie el procesamiento de documentos en sus aplicaciones con nuestra API REST en la nube y aplicaciones en línea gratuitas"

  items:
    #  loop
    - icon: "groupdocs_total-cloud"
      title: "GroupDocs.Total Cloud"
      link: "https://products.groupdocs.cloud/total"
      content: "Soluciones sólidas en la nube para automatizar eficientemente el procesamiento de documentos PDF de Microsoft Office en sus aplicaciones."

    #  loop
    - icon: "groupdocs_total-apps"
      title: "GroupDocs.Total Online Apps"
      link: "https://products.groupdocs.app"
      content: "Aplicaciones web gratuitas en línea para ver y editar el contenido de los documentos, comparar y combinar diferentes Microsoft Office, OpenOffice, imágenes y otros formatos de archivos populares."    

    #  loop
    - icon: "groupdocs_total-windows"
      title: "GroupDocs.Total Windows"
      link: "https://products.groupdocs.app/total/windows"
      content: "Aplicaciones sin conexión para convertir, anotar, comparar, firmar, ensamblar, analizar, clasificar, redactar y buscar documentos en cualquier sistema operativo."   

---