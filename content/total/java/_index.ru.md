---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ru
product: "Total"
product_tag: "total"
platform: "Java"
platform_tag: "java"

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
head_title: "Многофункциональный набор для автоматизации документов для приложений на Java"
head_description: "GroupDocs.Total для Java - это комплексная библиотека автоматизации документов, созданная специально для разработчиков Java, предоставляющая широкий спектр функциональных возможностей для работы с различными форматами документов, такими как PDF, Word, Excel, изображения, HTML, диаграммы и многое другое."

############################# Header ############################
title: "Упростите автоматизацию документов<br> в ваших проектах Java"
description: "Улучшите возможности автоматизации документов: легко конвертируйте, просматривайте, сравнивайте, редактируйте и подписывайте более 200 форматов файлов с легкостью."
words:
  for: "for"

actions:
  main: "Бесплатная загрузка через Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-total/"
  alt: "Лицензирование"
  alt_link: "https://purchase.groupdocs.com/pricing/total/java"
  title: "Готовы начать?"
  description: "Попробуйте функции GroupDocs.Total бесплатно или запросите лицензию"

release:
  title: "Версия {0}&nbsp;выпущена"
  notes: "Смотрите, что нового"
  downloads: "Загрузки"
  link: "https://releases.groupdocs.com/total/java/release-notes/latest/"

code:
  title: "Объединение и просмотр файлов Word в Java"
  more: "Больше примеров"
  more_link: "https://github.com/groupdocs-total/GroupDocs.Total-for-Java"
  install: |
    <dependencies>
      <dependency>
        <groupId>com.groupdocs</groupId>
        <artifactId>groupdocs-total</artifactId>
        <version>{0}</version>
      </dependency>
    </dependencies>

    <repositories>
      <repository>
        <id>repository.groupdocs.com</id>
        <name>GroupDocs Repository</name>
        <url>https://repository.groupdocs.com/repo/</url>
      </repository>
    </repositories>
  content: |
    ```java {style=abap}
    // Загрузите исходный файл DOCX 
    Merger merger = new Merger("sample1.docx");
    
    // Добавьте еще один файл DOCX для объединения
    merger.join("sample2.docx");

    // Объедините файлы DOCX и сохраните результат
    merger.save("merged.docx");
    
    // Загрузите объединенный файл DOCX в просмотрщик
    try (Viewer viewer = new Viewer("merged.docx"))
    {
      // Установите параметры вывода HTML, один файл на страницу
      HtmlViewOptions viewOptions =   
      HtmlViewOptions.forEmbeddedResources("page{0}.html");
          
      // Отобразите DOCX в HTML с встроенными ресурсами        
      viewer.view(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "Обзор GroupDocs.Total"
  description: "Автоматизация просмотра, конвертации, редактирования, сравнения, поиска, нанесения водяных знаков и других рабочих процессов в приложениях Java"
  features:
    # feature loop
    - title: "Объединение возможностей нескольких продуктов GroupDocs в единое комплексное решение"
      content: | 
        Вы можете использовать функции различных продуктов GroupDocs для создания настраиваемого подхода, отвечающего вашим конкретным потребностям.
        <br><br>
        Например, вы можете преобразовать файл Word в PDF, а затем добавить цифровую подпись. Или заполнить шаблон документа данными из базы данных или извлечь текст из изображения и затем перевести его на другой язык.
        <br><br>
        Возможности бесконечны!
          
    # feature loop
    - title: "Овладейте разнообразием форматов файлов"
      content: "GroupDocs.Total для Java разблокирует совместимость с более чем 200 форматами файлов, позволяя вам обрабатывать документы всех популярных типов. От офисных форматов, таких как Word и Excel, до изображений, кода и зашифрованных файлов - у нас есть все, что вам нужно."

    # feature loop
    - title: "Поддержка кросс-платформенности"
      content: "Избавьтесь от ограничений платформы. GroupDocs.Total обеспечивает совместимость с различными платформами, позволяя вам обеспечить оптимальную производительность и доступность решения для пользователей на любой системе, где можно установить Java."

############################# Platforms ############################
platforms:
  enable: true
  title: "Независимость от платформы"
  description: "GroupDocs.Total для Java поддерживает следующие операционные системы, фреймворки и менеджеры пакетов"
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
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "Maven"
      image: "maven"


############################# File formats ############################
formats:
  enable: true
  title: "Поддерживаемые форматы файлов"
  description: |
    GroupDocs.Total для Java поддерживает операции со следующими [форматами файлов](https://docs.groupdocs.com/total/java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Форматы Microsoft Office, OpenDocument и текстовые форматы
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
        ### Изображения, графика и диаграммы
        * **Растровые изображения:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Прочие        
        * **Веб:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Архивы:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Прочие:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Возможности GroupDocs.Total"
  description: "Комплексное управление, отображение и преобразование PDF-файлов и документов Office"

  items:
    # feature loop
    - icon: "viewer"
      title: "Обширный просмотр файлов"
      content: "Комплексный просмотр документов более чем в 180 форматах, включая HTML, изображения и PDF."

    # feature loop
    - icon: "conversion"
      title: "Преобразование форматов"
      content: "Беспроблемное преобразование между различными форматами документов без использования внешних инструментов."

    # feature loop
    - icon: "annotation"
      title: "Интерактивная аннотация"
      content: "Расширенные возможности аннотации для текстовых и изображенческих элементов внутри документов."

    # feature loop
    - icon: "comparison"
      title: "Сравнение содержимого"
      content: "Точное сравнение документов, выявляющее различия в содержании и стиле."

    # feature loop
    - icon: "signature"
      title: "Гибкость подписи"
      content: "Разнообразные варианты подписи, включая текстовую, изображенческую и цифровую подпись."

    # feature loop
    - icon: "assembly"
      title: "Создание документов на основе шаблонов"
      content: "Автоматизированное создание документов на основе шаблонов и внешних источников данных."

    # feature loop
    - icon: "metadata"
      title: "Управление метаданными"
      content: "Надежный доступ к метаданным и их изменение для улучшенного контроля документов."

    # feature loop
    - icon: "search"
      title: "Расширенный поиск"
      content: "Мощная функциональность поиска с поддержкой размытых и синонимичных алгоритмов."

    # feature loop
    - icon: "watermark"
      title: "Управление водяными знаками"
      content: "Безусиленное управление водяными знаками документов с возможностью настройки и извлечения функций."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Примеры кода"
  description: "Некоторые реальные сценарии использования GroupDocs.Total для Java"
  items:
    # code sample loop
    - title: "Безопасное и простое управление договорами: Нанесение водяных знаков и управление метаданными в файле DOCX"
      content: |
        Эффективно защищайте и организовывайте ваши документы Word с помощью этого комплексного примера кода. Приведенный ниже образец позволяет вам реализовать надежное нанесение водяных знаков и управление метаданными в рамках вашего рабочего процесса с контрактами для повышения безопасности и управления информацией. Он демонстрирует, как: <br><br>
        <b>Применить настраиваемый водяной знак:</b> Добавить важный водяной знак 'Черновик контракта' на документ для визуальной ясности и защиты. [Настройте водяной знак](https://docs.groupdocs.com/watermark/java/adding-text-watermarks/) с параметрами шрифта, цвета, непрозрачности и выравнивания. <br><br>
        <b>Улучшить метаданные:</b> Легко [измените метаданные документа](https://docs.groupdocs.com/metadata/java/working-with-metadata-in-word-processing-documents/), чтобы включить важные сведения, такие как автор, время создания, компания, категория и ключевые слова для улучшенной организации и поиска.
       
        {{< landing/code title="Java">}}
        ```java {style=abap}  
        import com.groupdocs.metadata.Metadata;
        import com.groupdocs.watermark.Watermark;
        import com.groupdocs.watermark.Watermark.Common;
        import com.groupdocs.watermark.Options.HtmlViewOptions;
        
        // Загрузите ваш документ в водяной знак
        Watermarker watermarker = new Watermarker("contract.docx");
        
        // Задайте нужный текст и шрифт для водяного знака
        TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 36));
          
        // Выберите цвет шрифта и непрозрачность текста, вращение и выравнивание
        watermark.setForegroundColor(Color.getRed());                                                            
        watermark.setHorizontalAlignment(HorizontalAlignment.Center);                                            
        watermark.setVerticalAlignment(VerticalAlignment.Center);                               

        // Примените водяной знак
        watermarker.add(watermark);
        
        // Сохраните полученный документ
        watermarker.save("watermarked-contract.docx");
        
        Metadata metadata = new Metadata("watermarked-contract.docx");        
        WordProcessingRootPackage root = metadata.getRootPackageGeneric();

        // Обновите свойства метаданных документа
        root.getDocumentProperties().setAuthor("Name Surname");
        root.getDocumentProperties().setCreatedTime(new Date());
        root.getDocumentProperties().setCompany("Company Name");
        root.getDocumentProperties().setCategory("Work materials");
        root.getDocumentProperties().setKeywords("contract, watermarked");

        // Сохраните документ с обновленными метаданными
        metadata.save("contract-final.docx");                
        ```
        {{< /landing/code >}}

    # code sample loop
    - title: "Оптимизированная редакция документов"
      content: |
        <b>Сценарий:</b> Крупная юридическая фирма часто обрабатывает разнообразные документы, содержащие конфиденциальную информацию клиентов, которую необходимо редактировать перед предоставлением третьим лицам или для публичного раскрытия. Ручная редакция этой чувствительной информации может быть утомительной, затратной по времени и подверженной человеческим ошибкам. Для обеспечения эффективности, точности и соответствия правилам защиты данных юридическая фирма ищет автоматизированное решение для оптимизации процесса редакции документов. 
        
        <br>

        <b>Решение:</b>
        GroupDocs.Total автоматизирует процесс, запуская редакцию при получении документа. Более того, [гибкие опции](https://docs.groupdocs.com/redaction/java/text-redactions/) позволяют настраивать правила, выбирать режимы редакции (например, закраска, замена звездочками) и указывать конкретные разделы или страницы для редакции. Наконец, [удобный формат вывода](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) генерирует отредактированные документы в формате PDF для удобного обмена и рецензии, а улучшенная безопасность и возможность проведения аудита гарантируют, что весь процесс будет задокументирован для соответствия и ответственности. 
        <br><br>
        Это комплексное решение позволяет юридическим профессионалам и другим организациям значительно сократить время и затраты на редакцию, минимизировать человеческие ошибки и последовательно обрабатывать чувствительную информацию с уверенностью.        
              
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.redaction.Redaction;
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // {index-content-java.code_samples.sample2_comment_1} 
        Redactor redactor = new Redactor("customer-info.docx");
        
        // {index-content-java.code_samples.sample2_comment_2} 
        redactor.apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
        
        // {index-content-java.code_samples.sample2_comment_3} 
        redactor.save();

        // {index-content-java.code_samples.sample2_comment_4} 
        Viewer viewer = new Viewer("customer-info.docx");
        
        // {index-content-java.code_samples.sample2_comment_5}       
        PdfViewOptions viewOptions = new PdfViewOptions("redacted-info.pdf");

        // {index-content-java.code_samples.sample2_comment_6}      
        viewer.view(viewOptions);        
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Отзывы о продуктах GroupDocs"
# description: "Не просто верьте на слово. Посмотрите, что говорят другие разработчики о наших API"

# items:
#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Отличный сервис и отличные продукты. Они были крайне полезны и отзывчивы во время процесса реализации GroupDocs.Viewer для .NET, не могу рекомендовать их достаточно высоко."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Total"
#     content: "После внедрения и использования GroupDocs.Viewer для Java в проекте, он выглядит очень хорошо. Я тестировал множество документов, и пока все хорошо. Все, что я ему дал, рендерится красиво и выглядит так же хорошо, как это было бы в PDF-просмотрщике или MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---