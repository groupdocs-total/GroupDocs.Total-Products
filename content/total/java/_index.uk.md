---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: uk
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
head_title: "Все-в-одному бібліотека для автоматизації документів у Java-застосунках"
head_description: "GroupDocs.Total для Java - це комплексна бібліотека для автоматизації документів, розроблена для Java-розробників, яка пропонує широкий набір функцій для роботи з різноманітними форматами документів, такими як PDF, Word, Excel, зображення, HTML, діаграми та багато іншого."

############################# Header ############################
title: "Спростіть автоматизацію документів<br> у ваших проектах Java"
description: "Покращте можливості автоматизації документів: без зусиль конвертуйте, переглядайте, порівнюйте, редагуйте та підписуйте понад 200 форматів файлів з легкістю."
words:
  for: "for"

actions:
  main: "Завантажити безкоштовно через Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-total/"
  alt: "Ліцензування"
  alt_link: "https://purchase.groupdocs.com/pricing/total/java"
  title: "Готові розпочати?"
  description: "Спробуйте функції GroupDocs.Total безкоштовно або запросіть ліцензію"

release:
  title: "Версія {0}&nbsp;випущена"
  notes: "Дивіться, що нового"
  downloads: "Завантаження"
  link: "https://releases.groupdocs.com/total/java/release-notes/latest/"

code:
  title: "Об'єднання та перегляд файлів Word у Java"
  more: "Ще більше прикладів"
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
    // Завантажте вихідний файл DOCX 
    Merger merger = new Merger("sample1.docx");
    
    // Додайте ще один файл DOCX для об'єднання
    merger.join("sample2.docx");

    // Об'єднайте файли DOCX та збережіть результат
    merger.save("merged.docx");
    
    // Завантажте об'єднаний файл DOCX у переглядач
    try (Viewer viewer = new Viewer("merged.docx"))
    {
      // Встановіть опції виведення HTML, по одному файлу на сторінцю
      HtmlViewOptions viewOptions =   
      HtmlViewOptions.forEmbeddedResources("page{0}.html");
          
      // Перетворіть DOCX у HTML із вбудованими ресурсами        
      viewer.view(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Total в кількох словах"
  description: "Автоматизуйте перегляд, конвертацію, редагування, порівняння, пошук, водяні знаки та інші робочі процеси файлів у Java-застосунках"
  features:
    # feature loop
    - title: "Поєднайте потужність кількох продуктів GroupDocs у єдине, комплексне рішення"
      content: | 
        Ви можете використовувати функції різних продуктів GroupDocs, щоб створити індивідуальний підхід, який відповідає вашим конкретним потребам.
        <br><br>
        Наприклад, ви можете конвертувати файл Word у PDF, а потім додати цифровий підпис. Або заповнити шаблон документа даними з бази даних, або витягнути текст з зображення, а потім перекласти його на іншу мову.
        <br><br>
        Можливості безмежні!
          
    # feature loop
    - title: "Оволодійте різноманітністю форматів файлів"
      content: "GroupDocs.Total для Java відкриває сумісність з понад 200 форматами файлів, дозволяючи вам обробляти документи всіх популярних типів. Від офісних форматів, таких як Word і Excel, до зображень, коду та зашифрованих файлів, ми покрили вас."

    # feature loop
    - title: "Підтримка крос-платформенності"
      content: "Звільніть себе від обмежень платформи. GroupDocs.Total забезпечує сумісність крос-платформенності, дозволяючи вам забезпечити оптимальну продуктивність та доступність рішення для користувачів на будь-якій системі, де може бути встановлений Java."

############################# Platforms ############################
platforms:
  enable: true
  title: "Незалежність від платформи"
  description: "GroupDocs.Total для Java підтримує такі операційні системи, фреймворки та менеджери пакетів"
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
  title: "Підтримувані формати файлів"
  description: |
    GroupDocs.Total для Java підтримує операції з наступними [форматами файлів](https://docs.groupdocs.com/total/java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Формати Microsoft Office, OpenDocument та текстові
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
        ### Зображення, графіка та діаграми
        * **Растрові зображення:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Інші        
        * **Web:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Архіви:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Інші:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Функції GroupDocs.Total"
  description: "Комплексне керування, відображення та конвертація PDF-файлів та документів Office"

  items:
    # feature loop
    - icon: "viewer"
      title: "Широкі можливості перегляду файлів"
      content: "Комплексний перегляд документів більш ніж у 180 форматах, включаючи HTML, зображення та PDF."

    # feature loop
    - icon: "conversion"
      title: "Конвертація формату"
      content: "Безперервна конвертація між різними форматами документів без зовнішніх інструментів."

    # feature loop
    - icon: "annotation"
      title: "Інтерактивні анотації"
      content: "Розширені можливості анотації текстових та зображеннєвих елементів у документах."

    # feature loop
    - icon: "comparison"
      title: "Порівняння вмісту"
      content: "Точне порівняння документів, виділяючи відмінності в змісті та стилі."

    # feature loop
    - icon: "signature"
      title: "Гнучкість підпису"
      content: "Різноманітні опції підпису, включаючи текстовий, зображеннєвий та цифровий підписи."

    # feature loop
    - icon: "assembly"
      title: "Створення документів на основі шаблонів"
      content: "Автоматизоване створення документів за допомогою шаблонів та зовнішніх джерел даних."

    # feature loop
    - icon: "metadata"
      title: "Керування метаданими"
      content: "Надійний доступ до метаданих та їх маніпулювання для покращеного контролю над документами."

    # feature loop
    - icon: "search"
      title: "Розширений пошук"
      content: "Потужна функціональність пошуку з підтримкою нечіткості та синонімів."

    # feature loop
    - icon: "watermark"
      title: "Керування водяним знаком"
      content: "Легке керування водяним знаком у документах з можливістю налаштування та екстракції."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Приклади коду"
  description: "Деякі реальні сценарії використання GroupDocs.Total для Java"
  items:
    # code sample loop
    - title: "Захист і організація договорів: Застосування водяних знаків та керування метаданими у файлі DOCX"
      content: |
        Ефективно захистіть і організуйте свої документи Word за допомогою цього комплексного прикладу коду. Наведений нижче зразок дозволяє вам реалізувати надійні водяні знаки та керування метаданими у вашому робочому процесі з договорами для підвищення безпеки та управління інформацією. Він демонструє, як: <br><br>
        <b>Застосування власного водяного знаку:</b> Додайте помітний водяний знак 'Draft Contract' до документа для візуальної чіткості та захисту. [Налаштуйте водяний знак](https://docs.groupdocs.com/watermark/java/adding-text-watermarks/) із опціями шрифту, кольору, прозорості та вирівнювання. <br><br>
        <b>Покращення метаданих:</b> Легко [змінюйте метадані документа](https://docs.groupdocs.com/metadata/java/working-with-metadata-in-word-processing-documents/), включаючи важливі деталі, такі як автор, час створення, компанія, категорія та ключові слова для поліпшення організації та пошуку.
       
        {{< landing/code title="Java">}}
        ```java {style=abap}  
        import com.groupdocs.metadata.Metadata;
        import com.groupdocs.watermark.Watermark;
        import com.groupdocs.watermark.Watermark.Common;
        import com.groupdocs.watermark.Options.HtmlViewOptions;
        
        // Завантажте ваш документ до водяного знаку
        Watermarker watermarker = new Watermarker("contract.docx");
        
        // Встановіть бажаний текст та шрифт для водяного знаку
        TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 36));
          
        // Виберіть колір шрифту та прозорість тексту, обертання та вирівнювання
        watermark.setForegroundColor(Color.getRed());                                                            
        watermark.setHorizontalAlignment(HorizontalAlignment.Center);                                            
        watermark.setVerticalAlignment(VerticalAlignment.Center);                               

        // Застосуйте водяний знак
        watermarker.add(watermark);
        
        // Збережіть отриманий документ
        watermarker.save("watermarked-contract.docx");
        
        Metadata metadata = new Metadata("watermarked-contract.docx");        
        WordProcessingRootPackage root = metadata.getRootPackageGeneric();

        // Оновіть властивості метаданих документа
        root.getDocumentProperties().setAuthor("Name Surname");
        root.getDocumentProperties().setCreatedTime(new Date());
        root.getDocumentProperties().setCompany("Company Name");
        root.getDocumentProperties().setCategory("Work materials");
        root.getDocumentProperties().setKeywords("contract, watermarked");

        // Збережіть документ із оновленими метаданими
        metadata.save("contract-final.docx");                
        ```
        {{< /landing/code >}}

    # code sample loop
    - title: "Оптимізована редакція документів"
      content: |
        <b>Сценарій:</b> Велика юридична фірма часто обробляє різноманітні документи, що містять конфіденційну інформацію клієнтів, яку необхідно редагувати перед наданням третім сторонам або для публічного розголошення. Ручна редакція цієї конфіденційної інформації може бути нудною, часом затратною та схильною до людських помилок. Для забезпечення ефективності, точності та відповідності регламентуючим документам про захист даних юридична фірма шукає автоматизоване рішення для оптимізації процесу редакції документів. 
        
        <br>

        <b>Рішення:</b>
        GroupDocs.Total автоматизує процес, спрацьовуючи редакцію при отриманні документа. Крім того, [гнучкі опції](https://docs.groupdocs.com/redaction/java/text-redactions/) дозволяють налаштовувати редакцію, вибирати режими редакції (наприклад, чорніти, заміняти зірочками), вказувати конкретні розділи або сторінки для редакції. Нарешті, [користувацький вихід](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) генерує редаговані документи у форматі PDF для легкого обміну та перегляду, тоді як підвищена безпека та перевірка забезпечують документацію всього процесу для відповідності та відповідальності. 
        <br><br>
        Це комплексне рішення дозволяє юридичним професіоналам та іншим організаціям значно скоротити час та витрати на редакцію, мінімізувати людські помилки та послідовно обробляти конфіденційну інформацію з впевненістю.        
              
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
# title: "Відгуки про продукти GroupDocs"
# description: "Не просто вірте на слово. Подивіться, що кажуть інші розробники про наші API"

# items:
#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Чудовий сервіс і відмінні продукти. Вони були дуже корисні та оперативні під час процесу впровадження GroupDocs.Viewer для .NET, не можу висловити їм достатньо високої оцінки."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Після впровадження та використання GroupDocs.Viewer для Java у проекті виглядає, що все працює дуже добре. Я протестував з багатьма документами, і досі все працює гарно. Все, що я випробував, відображається красиво та виглядає так само добре, як і в переглядачі PDF або MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---