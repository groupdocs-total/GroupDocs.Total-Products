---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Total"
product_tag: "total"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "API-интерфейсы Java для просмотра, преобразования, аннотирования, подписи, автоматизации и поиска форматов файлов"
head_description: "Используйте Java-версии API для работы с документами GroupDocs, чтобы интегрировать их с вашими собственными платформами и Java-приложениями."

############################# Header ############################
title: "Библиотеки автоматизации документов Java"
description: "API для просмотра, экспорта, аннотирования, сравнения, подписи, автоматизации и поиска документов из любого приложения Java.."
button:
    enable: true

############################# SubMenu ############################
submenu:
  enable: true
  
  left:
      img_alt: "GroupDocs.Total for Java"
      image: "/border/groupdocs-total-java.svg"
      product: "GroupDocs.Total"
      platform: "Java"

  middle:
      button:
          # button loop
          - link: "#overview"
            text: "Обзор"

          # button loop
          - link: "#products"
            text: "Продукты"

          # button loop
          - link: "#features"
            text: "Функции"

          # button loop
          - link: "#support"
            text: "Support"

          # button loop
          - link: "https://purchase.groupdocs.com/pricing/total/java"
            text: "Pricing"

  right:
      link_download: "https://releases.groupdocs.com/total"
      link_learn: "https://docs.groupdocs.com/total/java/"
      link_buy: "https://purchase.groupdocs.com"

############################# Обзор ############################
overview:
    enable: true
    content: |
      GroupDocs.Total для Java представляет собой компиляцию всех Java API, предлагаемых GroupDocs. Мы ежедневно компилируем его, чтобы гарантировать, что он содержит самые последние версии каждого из наших API Java.
        
      With GroupDocs.Total for Java developers can use all our APIs with a single license. However, you can order any individual API as well. APIs we offer include

############################# Продукты ############################
products:
    enable: true
    title: "Продукты"
    description: "GroupDocs.Total для Java включает следующие API для работы с документами для Java:"

    product:
        # product loop
        - image: "/border/groupdocs-viewer-java.svg"
          img_alt: "GroupDocs.Viewer for Java"
          name: "GroupDocs.Viewer for Java"
          content: |
            Мощный API для просмотра документов, который позволяет отображать более 50 форматов документов в ваших Java-приложениях. Средство просмотра может работать двумя способами: растрировать документы или преобразовывать их в комбинацию SVG, HTML и CSS. Оба метода обеспечивают высокую точность рендеринга.
              
            Поддерживаемые форматы файлов включают документы Microsoft Office, Visio, Project и Outlook, PDF-файлы, AutoCAD, файлы изображений (TIFF, JPG, BMP, GIF, TIFF и т. д.) и другие.
          link: "/viewer/java/"

        # product loop
        - image: "/border/groupdocs-annotation-java.svg"
          img_alt: "GroupDocs.Annotation for Java"
          name: "GroupDocs.Annotation for Java"
          content: |
            Гибкий API, который позволяет конечным пользователям комментировать документы Microsoft Office, PDF и другие документы в ваших приложениях Java. API поставляется с полным набором инструментов разметки, которые позволяют конечным пользователям выделять, зачеркивать и комментировать текст и изображения.
          link: "/annotation/java/"

          # product loop
        - image: "/border/groupdocs-conversion-java.svg"
          img_alt: "GroupDocs.Conversion for Java"
          name: "GroupDocs.Conversion for Java"
          content: |
            Расширенный API класса, который позволяет вам конвертировать туда и обратно между более чем 50 форматами документов из ваших приложений Java. API поддерживает все форматы документов Microsoft Office, а также PDF, HTML и распространенные форматы файлов изображений (TIFF, JPEG, GIF, PNG, BMP). Документы можно конвертировать один за другим на лету или добавлять в очередь конвертации.
          link: "/conversion/java/"

          # product loop
        - image: "/border/groupdocs-comparison-java.svg"
          img_alt: "GroupDocs.Comparison for Java"
          name: "GroupDocs.Comparison for Java"
          content: |
            Этот API позволяет конечным пользователям быстро и легко находить различия между двумя версиями документа. Он сравнивает загруженные документы и отображает различия между ними через пользовательский интерфейс просмотра различий. Различия выделяются с помощью красной линии — аналогично функции отслеживания изменений Microsoft Word.
          link: "/comparison/java/"

          # product loop
        - image: "/border/groupdocs-signature-java.svg"
          img_alt: "GroupDocs.Signature for Java"
          name: "GroupDocs.Signature for Java"
          content: |
            С помощью этого API вы можете легко улучшить свои приложения с помощью возможности электронной подписи. После этого ваши пользователи смогут подписывать документы в электронном виде, используя только веб-браузер. Подробные журналы аудита, 256-битное шифрование SSL и другие расширенные функции безопасности обеспечивают конфиденциальность и безопасность подписанных документов, а пользовательский интерфейс, похожий на мастер, делает процесс подписания быстрым и простым.
          link: "/signature/java/"

          # product loop
        - image: "/border/groupdocs-assembly-java.svg"
          img_alt: "GroupDocs.Assembly for Java"
          name: "GroupDocs.Assembly for Java"
          content: |
            Движок GroupDocs.Assembly для Java представляет собой набор API-интерфейсов для автоматизации документов и генерации отчетов, предназначенных для создания пользовательских документов из шаблонов. Механизм отчетов Java интеллектуально собирает данные с определенным шаблоном документа и генерирует выходной документ на основе источника данных в том же формате, что и формат шаблона документа.
          link: "/assembly/java/"

          # product loop
        - image: "/border/groupdocs-metadata-java.svg"
          img_alt: "GroupDocs.Metadata for Java"
          name: "GroupDocs.Metadata for Java"
          content: |
            GroupDocs.Metadata for Java — это API управления метаданными документа, предназначенный для всех основных операций с метаданными, таких как просмотр, добавление, изменение и удаление метаданных. API метаданных поддерживают несколько форматов файлов. Вы можете загрузить входной документ и сделать его метаданные доступными для пользователя для операций с метаданными.
          link: "/metadata/java/"

          # product loop
        - image: "/border/groupdocs-search-java.svg"
          img_alt: "GroupDocs.Search for Java"
          name: "GroupDocs.Search for Java"
          content: |
            GroupDocs.Search для Java — API поиска документов для расширенных запросов с функциями индексирования. Используйте API в приложениях Java для документов, включая Word Excel PowerPoint и PDF для полнотекстового поиска и многого другого.
          link: "/search/java/"

          # product loop
        - image: "/border/groupdocs-parser-java.svg"
          img_alt: "GroupDocs.Parser for Java"
          name: "GroupDocs.Parser for Java"
          content: |
            GroupDocs.Parser для Java — расширяемый API для извлечения текста и синтаксического анализа для чтения или анализа содержимого документа и свойств метаданных из файлов различных форматов. Он работает просто, получая файл в качестве входных данных, а затем извлекает необработанный или форматированный текст входного файла вместе со свойствами метаданных.
          link: "/parser/java/"

          # product loop
        - image: "/border/groupdocs-watermark-java.svg"
          img_alt: "GroupDocs.Watermark for Java"
          name: "GroupDocs.Watermark for Java"
          content: |
            GroupDocs.Watermark для Java — это API-интерфейс водяных знаков для документов, позволяющий добавлять, искать и удалять водяные знаки из файлов различных форматов. API поддерживает текстовые и графические типы водяных знаков. Водяной знак, добавленный любым сторонним программным обеспечением, можно легко найти и удалить с помощью этого API, в то время как удалить водяной знак, добавленный с помощью этого API, любыми сторонними инструментами сложно.
          link: "/watermark/java/"

          # product loop
        - image: "/border/groupdocs-editor-java.svg"
          img_alt: "GroupDocs.Editor for Java"
          name: "GroupDocs.Editor for Java"
          content: |
            GroupDocs.Editor для Java — это облегченный API для редактирования нескольких форматов документов в форме HTML. API редактора может как преобразовывать исходный документ в HTML, так и сохранять отредактированный HTML в формате исходного документа.
          link: "/editor/java/"

          # product loop
        - image: "/border/groupdocs-merger-java.svg"
          img_alt: "GroupDocs.Merger for Java"
          name: "GroupDocs.Merger for Java"
          content: |
            GroupDocs.Merger для Java — это API для слияния и соединения документов, позволяющий объединять и упорядочивать несколько файлов в один, а также разделять, удалять или изменять порядок страниц в документе поддерживаемого формата.
          link: "/merger/java/"

          # product loop
        - image: "/border/groupdocs-redaction-java.svg"
          img_alt: "GroupDocs.Redaction for Java"
          name: "GroupDocs.Redaction for Java"
          content: |
            API редактирования документов Java для защиты или удаления любой конфиденциальной информации из документов Word, Excel, PowerPoint, изображений и PDF с использованием типов редактирования текста, метаданных и аннотаций.
          link: "/redaction/java/"

############################# Функции ############################
features:
    enable: true
    title: "Advanced API Функции"

    feature:
      # feature loop
      - icon: "fas fa-file"
        content: "Представление документов в HTML, изображениях и PDF"

      # feature loop
      - icon: "fas fa-water"
        content: "Водяной знак: добавьте текст в качестве водяного знака на все страницы и изображения вывода."

      # feature loop
      - icon: "fas fa-pen"
        content: "Собственные аннотации Word и PDF"
      
      # feature loop
      - icon: "fas fa-tools"
        content: "Полный набор инструментов для аннотаций"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Добавляйте аннотации к электронной почте, HTML и графическим документам"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Быстрое и точное преобразование документов"

      # feature loop
      - icon: "fas fa-key"
        content: "Сравнивает содержимое документов, файлы, защищенные паролем, стили шрифтов и водяные знаки."

      # feature loop
      - icon: "fas fa-save"
        content: "Сохранить сводку различий в формате DOC или DOCX"

      # feature loop
      - icon: "fas fa-upload"
        content: "Загружайте, печатайте или рисуйте подписи"

      # feature loop
      - icon: "fas fa-file-signature"
        content: "Проверка цифровой подписи для всех типов"

      # feature loop
      - icon: "fas fa-server"
        content: "Создание документов из более чем одного источника данных"

      # feature loop
      - icon: "fas fa-eraser"
        content: "Анализируйте и удаляйте скрытые метаданные в различных форматах документов"

      # feature loop
      - icon: "fas fa-search-plus"
        content: "Поиск и сравнение метаданных"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Экспорт метаданных в Excel/CSV"

      # feature loop
      - icon: "fas fa-lock"
        content: "Извлечение текста из защищенных паролем файлов"

      # feature loop
      - icon: "fas fa-search-minus"
        content: "Поиск и удаление текстового/изображения водяного знака"

      # feature loop
      - icon: "fas fa-file-image"
        content: "Редактировать несколько форматов документов"

      # feature loop
      - icon: "fas fa-file-alt"
        content: "Объединение нескольких файлов в один"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: false
    title: "GroupDocs.Total для Java предлагает индивидуальные решения для"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for Java"
          image: "/border/groupdocs-viewer-java.svg"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"
        
        # solution loop
        - img_alt: "GroupDocs.Annotation for Java"
          image: "/border/groupdocs-annotation-java.svg"
          product: "GroupDocs.Annotation"
          platform: "Java"
          link: "/annotation/java/"

        # solution loop
        - img_alt: "GroupDocs.Conversion for Java"
          image: "/border/groupdocs-conversion-java.svg"
          product: "GroupDocs.Conversion"
          platform: "Java"
          link: "/conversion/java/"

        # solution loop
        - img_alt: "GroupDocs.Comparison for Java"
          image: "/border/groupdocs-comparison-java.svg"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/"

        # solution loop
        - img_alt: "GroupDocs.Signature for Java"
          image: "/border/groupdocs-signature-java.svg"
          product: "GroupDocs.Signature"
          platform: "Java"
          link: "/signature/java/"

        # solution loop
        - img_alt: "GroupDocs.Assembly for Java"
          image: "/border/groupdocs-assembly-java.svg"
          product: "GroupDocs.Assembly"
          platform: "Java"
          link: "/assembly/java/"

        # solution loop
        - img_alt: "GroupDocs.Metadata for Java"
          image: "/border/groupdocs-metadata-java.svg"
          product: "GroupDocs.Metadata"
          platform: "Java"
          link: "/metadata/java/"

        # solution loop
        - img_alt: "GroupDocs.Search for Java"
          image: "/border/groupdocs-search-java.svg"
          product: "GroupDocs.Search"
          platform: "Java"
          link: "/search/java/"

        # solution loop
        - img_alt: "GroupDocs.Parser for Java"
          image: "/border/groupdocs-parser-java.svg"
          product: "GroupDocs.Parser"
          platform: "Java"
          link: "/parser/java/"

        # solution loop
        - img_alt: "GroupDocs.Watermark for Java"
          image: "/border/groupdocs-watermark-java.svg"
          product: "GroupDocs.Watermark"
          platform: "Java"
          link: "/watermark/java/"

        # solution loop
        - img_alt: "GroupDocs.Editor for Java"
          image: "/border/groupdocs-editor-java.svg"
          product: "GroupDocs.Editor"
          platform: "Java"
          link: "/editor/java/"

        # solution loop
        - img_alt: "GroupDocs.Merger for Java"
          image: "/border/groupdocs-merger-java.svg"
          product: "GroupDocs.Merger"
          platform: "Java"
          link: "/merger/java/"

        # solution loop
        - img_alt: "GroupDocs.Redaction for Java"
          image: "/border/groupdocs-redaction-java.svg"
          product: "GroupDocs.Redaction"
          platform: "Java"
          link: "/redaction/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---