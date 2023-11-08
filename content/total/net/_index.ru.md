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
head_title: "C# .NET API для просмотра, преобразования, аннотирования, подписи, автоматизации, водяных знаков, редактирования и поиска форматов файлов"
head_description: "Библиотеки и API для работы с документами GroupDocs .NET. Используйте любой API в приложении .NET для создания, обработки или преобразования более 50 документов.."

############################# Header ############################
title: ".NET API автоматизации документов"
description: "API для просмотра, экспорта, аннотирования, сравнения, подписи, автоматизации и поиска документов в ваших приложениях .NET."
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
          - link: "https://purchase.groupdocs.com/pricing/total/net"
            text: "Pricing"

  right:
      link_download: "https://releases.groupdocs.com/total"
      link_learn: "https://docs.groupdocs.com/total/net/"
      link_buy: "https://purchase.groupdocs.com"

############################# Обзор ############################
overview:
    enable: true
    content: "GroupDocs.Total для .NET представляет собой компиляцию всех .NET API, предлагаемых GroupDocs. Мы ежедневно компилируем его, чтобы гарантировать, что он содержит самые последние версии каждого из наших API для работы с документами .NET..
    <br><br>С помощью GroupDocs.Total для .NET разработчики могут использовать все наши API с одной лицензией. Однако вы также можете заказать любой отдельный API. "

############################# Продукты ############################
products:
    enable: true
    title: "Продукты"
    description: "GroupDocs.Total для .NET включает следующие API для работы с документами для .NET:"

    product:
        # product loop
        - image: "/border/groupdocs-viewer-net.svg"
          img_alt: "GroupDocs.Viewer for .NET"
          name: "GroupDocs.Viewer for .NET"
          content: "Мощный API для просмотра документов для рендеринга, просмотра и отображения документов более чем 50 форматов файлов. Всесторонняя визуализация всего документа, эффективная визуализация части документа или визуализация определенной страницы/диапазона ячеек. Рендеринг отдельного слоя документа с аннотациями и комментариями или без них для поддерживаемых форматов файлов."
          link: "/viewer/net/"

        # product loop
        - image: "/border/groupdocs-annotation-net.svg"
          img_alt: "GroupDocs.Annotation for .NET"
          name: "GroupDocs.Annotation for .NET"
          content: "API управления аннотациями для создания и управления различными типами аннотаций, таких как область, текст, полилиния, точка, подчеркивание и т. д. Он предоставляет вам полный набор инструментов разметки для выделения, зачеркивания, тегов и комментариев к тексту и изображениям. . Распечатайте аннотированные документы или экспортируйте в PDF вместе с аннотациями."
          link: "/annotation/net/"

          # product loop
        - image: "/border/groupdocs-conversion-net.svg"
          img_alt: "GroupDocs.Conversion for .NET"
          name: "GroupDocs.Conversion for .NET"
          content: "Комплексный API преобразования документов для настройки и преобразования документов из более чем 50 форматов файлов. Благодаря таким функциям, как рендеринг заголовка электронной почты во время преобразования из электронной почты, установка пользовательских каталогов шрифтов, настройка и размещение водяных знаков, а также расширенный метод преобразования и т. д., этот API представляет собой гораздо больше, чем простой инструмент преобразования файлов.."
          link: "/conversion/net/"

          # product loop
        - image: "/border/groupdocs-comparison-net.svg"
          img_alt: "GroupDocs.Comparison for .NET"
          name: "GroupDocs.Comparison for .NET"
          content: "API проверки различий документов для сравнения содержимого и стилей текста. Выберите уровень детализации процесса сравнения. Применить или отклонить изменения после анализа различий. Получение документов через файл или поток. Укажите разделитель слов и цвет шрифта для стилизации сравниваемого текста. Сравните файлы, защищенные паролем."
          link: "/comparison/net/"

          # product loop
        - image: "/border/groupdocs-signature-net.svg"
          img_alt: "GroupDocs.Signature for .NET"
          name: "GroupDocs.Signature for .NET"
          content: "API манипулирования электронной подписью для подписи цифровых документов различных форматов. Получить все зарегистрированные сертификаты, присутствующие в системе. Применяйте подпись многих типов, например текст, штрих-код, изображение, QR-код и т. д. Выполняйте простой и расширенный поиск, чтобы найти нужные подписи. Настройте свойства подписи, такие как тень, выравнивание, размеры и многое другое."
          link: "/signature/net/"

          # product loop
        - image: "/border/groupdocs-assembly-net.svg"
          img_alt: "GroupDocs.Assembly for .NET"
          name: "GroupDocs.Assembly for .NET"
          content: "API для автоматизации документов и создания отчетов путем создания и настройки шаблонов для поддерживаемых форматов. Управляйте данными, используя формулы и последовательные операции с данными, форматируйте строки в синтаксисе шаблона, задавайте порядковое, кардинальное, буквенное и числовое форматирование. определить переменные; динамически вставлять содержимое в отчеты с условным форматированием и т. д."
          link: "/assembly/net/"

          # product loop
        - image: "/border/groupdocs-metadata-net.svg"
          img_alt: "GroupDocs.Metadata for .NET"
          name: "GroupDocs.Metadata for .NET"
          content: "API доступа к метаданным и управления ими для чтения, редактирования, замены и удаления метаданных различных типов документов. Сравните свойства метаданных двух файлов, чтобы выявить их сходства и различия. Экспорт метаданных в Excel, CSV или DataSet. Определить MIME-тип определенного файла или файлового потока. Удалить информацию о местоположении с фотографий. Уменьшите потребление памяти файлами."
          link: "/metadata/net/"

          # product loop
        - image: "/border/groupdocs-search-net.svg"
          img_alt: "GroupDocs.Search for .NET"
          name: "GroupDocs.Search for .NET"
          content: "API поиска документов и текста, предлагающий базовые и расширенные функции поиска, такие как построение и объединение нескольких индексов, поиск с помощью простого, логического, нечеткого, регулярное выражение (регулярное выражение) и другие типы запросов. Применяйте быстрый, надежный и интеллектуальный поиск к файлам, документам и электронным письмам. Поиск на основе омофонических терминов, синонимов, диапазона дат, подстановочных знаков и учета регистра."
          link: "/search/net/"

          # product loop
        - image: "/border/groupdocs-parser-net.svg"
          img_alt: "GroupDocs.Parser for .NET"
          name: "GroupDocs.Parser for .NET"
          content: "API для извлечения текста, который поддерживает извлечение необработанного, форматированного и структурированного текста и метаданных из файлов поддерживаемых форматов. Парсинг защищенных паролем документов. Выберите между быстрым или стандартным извлечением текста. Средство форматирования Markdown и HTML поддерживает форматирование шрифта, гиперссылок, заголовков, списков и таблиц. Получить данные из контейнера электронной почты (Exchange Web Server, POP3, IMAP)."
          link: "/parser/net/"

          # product loop
        - image: "/border/groupdocs-watermark-net.svg"
          img_alt: "GroupDocs.Watermark for .NET"
          name: "GroupDocs.Watermark for .NET"
          content: "Применение цифровых водяных знаков и API манипулирования для применения новых водяных знаков, поиска и удаления существующих водяных знаков из документов поддерживаемых форматов. Заблокируйте водяные знаки, чтобы ограничить редактирование. Заменить существующие водяные знаки. Защитите текстовый водяной знак, используя нечитаемые символы в презентациях. Изменять свойства фигуры, такие как альтернативный текст, угол поворота и т. д., в презентации."
          link: "/watermark/net/"

          # product loop
        - image: "/border/groupdocs-editor-net.svg"
          img_alt: "GroupDocs.Editor for .NET"
          name: "GroupDocs.Editor for .NET"
          content: "API редактора документов для загрузки документа поддерживаемого формата файла, преобразования его в HTML, передачи HTML во внешний редактор HTML, сохранения HTML в исходном формате файла. Отдельно извлекайте ресурсы, прикрепленные к любому документу. Получить CSS-контент HTML-документа. Получить HTML DOM из строкового содержимого и преобразовать в документ. Применить безопасность к результирующему документу."
          link: "/editor/net/"

          # product loop
        - image: "/border/groupdocs-merger-net.svg"
          img_alt: "GroupDocs.Merger for .NET"
          name: "GroupDocs.Merger for .NET"
          content: "API слияния и разделения документов для объединения, разделения, перестановки, замены, обрезки и удаления отдельных страниц или набора страниц, слайдов или диаграмм. Установите или снимите защиту паролем для известных и неизвестных форматов файлов. Сшивайте или разделяйте один или несколько документов. Обрежьте документ, удалив определенные страницы, слайды или диаграммы."
          link: "/merger/net/"

          # product loop
        - image: "/border/groupdocs-redaction-net.svg"
          img_alt: "GroupDocs.Redaction for .NET"
          name: "GroupDocs.Redaction for .NET"
          content: "API редактирования и очистки документов для редактирования, удаления или скрытия секретной информации, контента и метаданных из документов, рабочих листов, PDF-файлов и слайдов.."
          link: "/redaction/net/"

          # product loop
        - image: "/border/groupdocs-classification-net.svg"
          img_alt: "GroupDocs.Classification for .NET"
          name: "GroupDocs.Classification for .NET"
          content: "API классификации необработанного текста и документов для приложений .NET. Классифицируйте содержимое и форматы документов, такие как Microsoft Office Word, PDF, OpenDocument, RTF и Text, используя несколько таксономий, включая документы и IAB-2. Легко настраивайте классифицированные результаты, используя множество расширенных функций в соответствии с вашими требованиями.."
          link: "/classification/net/"

############################# Функции ############################
features:
    enable: true
    title: "Advanced API Функции"

    feature:
      # feature loop
      - icon: "fas fa-eye"
        content: "Просмотр документа любого формата в его исходном формате или в формате HTML, изображений или PDF"

      # feature loop
      - icon: "fas fa-file"
        content: "Аннотируйте любые документы PDF, DOCX, XLSX и PPTX"
      
      # feature loop
      - icon: "fas fa-file-export"
        content: "Экспорт аннотаций в отдельный файл PDF или Word"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Самый быстрый API конвертации «на лету»"

      # feature loop
      - icon: "fas fa-clone"
        content: "Пакетное преобразование нескольких файлов"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Сравнивает контент на наличие различий в словах и абзацах"

      # feature loop
      - icon: "fas fa-file-contract"
        content: "Сводка отдельных различий при использовании API сравнения"

      # feature loop
      - icon: "fas fa-signature"
        content: "Несколько свойств подписи"

      # feature loop
      - icon: "fas fa-file-signature"
        content: "Установите подпись на произвольных страницах, таких как первая, последняя, четная, нечетная и т. д."

      # feature loop
      - icon: "fas fa-server"
        content: "Создание многоформатных документов из более чем одного источника данных"

      # feature loop
      - icon: "fas fa-key"
        content: "Встроенные и настраиваемые операции с метаданными в виде пар ключ/значение"

      # feature loop
      - icon: "fas fa-file-download"
        content: "Экспорт метаданных, прикрепленных к поддерживаемым форматам файлов"

      # feature loop
      - icon: "fab fa-searchengin"
        content: "Несколько основных и расширенных методов поиска"

      # feature loop
      - icon: "fas fa-search"
        content: "Fuzzy and Поиск синонимов"

      # feature loop
      - icon: "fas fa-search-minus"
        content: "Поиск и удаление текстового/изображения водяного знака"

      # feature loop
      - icon: "fas fa-file-image"
        content: "Добавление водяного знака к изображениям внутри документа"

      # feature loop
      - icon: "fas fa-file-alt"
        content: "Извлечение структурированного и выделенного текста"
      
      # feature loop
      - icon: "fas fa-file-archive"
        content: "Извлекает текст из контейнеров, содержащих другие файлы, такие как zip-архивы."

      # feature loop
      - icon: "fas fa-file-invoice"
        content: "Прямое и обратное преобразование документа"

      # feature loop
      - icon: "fas fa-edit"
        content: "Редактировать несколько форматов документов"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: false
    title: "GroupDocs.Total для .NET предлагает индивидуальные решения для"

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
