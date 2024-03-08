---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: de
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
head_title: "All-in-one-Dokumentautomatisierungssuite für Java-Anwendungen"
head_description: "GroupDocs.Total für Java ist eine umfassende Dokumentautomatisierungsbibliothek, die auf Java-Entwickler zugeschnitten ist und eine breite Palette an Funktionen für die Verarbeitung verschiedener Dokumentformate wie PDF, Word, Excel, Bild, HTML, Diagramm und mehr bietet."

############################# Header ############################
title: "Vereinfachen Sie die Dokumentenautomatisierung<br>in Ihren Java-Projekten"
description: "Erweitern Sie die Funktionen zur Dokumentenautomatisierung: Konvertieren, Anzeigen, Vergleichen, Bearbeiten und Signieren von über 200 Dateiformaten mühelos."
words:
  for: "for"

actions:
  main: "Kostenloser Maven-Download"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-total/"
  alt: "Lizenzierung"
  alt_link: "https://purchase.groupdocs.com/pricing/total/java"
  title: "Bereit anzufangen?"
  description: "Testen Sie die Funktionen von GroupDocs.Total kostenlos oder fordern Sie eine Lizenz an"

release:
  title: "Version {0} veröffentlicht"
  notes: "Schau was neu ist"
  downloads: "Downloads"
  link: "https://releases.groupdocs.com/total/java/release-notes/latest/"

code:
  title: "Word-Dateien in Java zusammenführen und anzeigen"
  more: "Mehr Beispiele"
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
    // Laden Sie die DOCX-Quelldatei 
    Merger merger = new Merger("sample1.docx");
    
    // Fügen Sie eine weitere DOCX-Datei zum Zusammenführen hinzu
    merger.join("sample2.docx");

    // DOCX-Dateien zusammenführen und Ergebnis speichern
    merger.save("merged.docx");
    
    // Laden Sie die zusammengeführte DOCX-Datei in den Viewer
    try (Viewer viewer = new Viewer("merged.docx"))
    {
      // Legen Sie Ausgabe-HTML-Optionen fest, eine Datei pro Seite
      HtmlViewOptions viewOptions =   
      HtmlViewOptions.forEmbeddedResources("page{0}.html");
          
      // Rendern Sie DOCX mit eingebetteten Ressourcen in HTML        
      viewer.view(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Total auf einen Blick"
  description: "Automatisieren Sie Dateiansicht, Konvertierung, Bearbeitung, Vergleich, Suche, Wasserzeichen und andere Arbeitsabläufe in Java-Anwendungen"
  features:
    # feature loop
    - title: "Kombinieren Sie die Leistungsfähigkeit mehrerer GroupDocs-Produkte zu einer einzigen, umfassenden Lösung"
      content: | 
        Sie können Funktionen verschiedener GroupDocs-Produkte nutzen, um einen maßgeschneiderten Ansatz zu erstellen, der Ihren spezifischen Anforderungen entspricht.
        <br><br>
        Sie können beispielsweise eine Word-Datei in eine PDF-Datei konvertieren und anschließend eine digitale Signatur hinzufügen. Oder füllen Sie eine Dokumentvorlage mit Daten aus einer Datenbank oder extrahieren Sie Text aus einem Bild und übersetzen Sie ihn dann in eine andere Sprache.
        <br><br>
        Die Möglichkeiten sind endlos!
          
    # feature loop
    - title: "Beherrschen Sie die Vielfalt der Dateiformate"
      content: "GroupDocs.Total für Java ermöglicht die Kompatibilität mit über 200 Dateiformaten und ermöglicht Ihnen die Verarbeitung von Dokumenten aller gängigen Typen. Von Office-Formaten wie Word und Excel bis hin zu Bildern, Code und verschlüsselten Dateien sind Sie bei uns genau richtig."

    # feature loop
    - title: "Plattformübergreifende Unterstützung"
      content: "Befreien Sie sich von Plattformbeschränkungen. GroupDocs.Total bietet plattformübergreifende Kompatibilität und ermöglicht es Ihnen, Benutzern auf jedem System, auf dem Java installiert werden kann, optimale Leistung und Lösungsverfügbarkeit zu bieten."

############################# Platforms ############################
platforms:
  enable: true
  title: "Plattformunabhängigkeit"
  description: "GroupDocs.Total für Java unterstützt die folgenden Betriebssysteme, Frameworks und Paketmanager"
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
  title: "Unterstützte Dateiformate"
  description: |
    GroupDocs.Total für Java unterstützt Vorgänge mit den folgenden [Dateiformaten](https://docs.groupdocs.com/total/java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument und Textformate
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
        ### Bilder, Grafiken und Diagramme
        * **Rasterbilder:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Andere        
        * **Netz:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Archiv:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Andere:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Total-Funktionen"
  description: "Umfassende Verwaltung, Darstellung und Konvertierung von PDFs und Office-Dokumenten"

  items:
    # feature loop
    - icon: "viewer"
      title: "Umfangreiche Dateiansicht"
      content: "Umfassende Dokumentenanzeige für über 180 Formate, einschließlich HTML, Bilder und PDF."

    # feature loop
    - icon: "conversion"
      title: "Formatkonvertierung"
      content: "Nahtlose Konvertierung zwischen verschiedenen Dokumentformaten ohne externe Tools."

    # feature loop
    - icon: "annotation"
      title: "Interaktive Anmerkung"
      content: "Erweiterte Anmerkungsfunktionen für Text- und Bildelemente in Dokumenten."

    # feature loop
    - icon: "comparison"
      title: "Inhaltsvergleich"
      content: "Präziser Dokumentenvergleich, der Unterschiede in Inhalt und Stil hervorhebt."

    # feature loop
    - icon: "signature"
      title: "Signature-Flexibilität"
      content: "Vielseitige Signaturoptionen, einschließlich Text-, Bild- und digitale Signaturen."

    # feature loop
    - icon: "assembly"
      title: "Vorlagenbasierte Dokumentenerstellung"
      content: "Automatisierte Dokumentengenerierung aus Vorlagen und externen Datenquellen."

    # feature loop
    - icon: "metadata"
      title: "Metadatenverwaltung"
      content: "Robuster Metadatenzugriff und -bearbeitung für eine verbesserte Dokumentenkontrolle."

    # feature loop
    - icon: "search"
      title: "Erweiterte Suche"
      content: "Leistungsstarke Suchfunktion mit Unterstützung für Fuzzy- und Synonymalgorithmen."

    # feature loop
    - icon: "watermark"
      title: "Wasserzeichenkontrolle"
      content: "Mühelose Dokumentenwasserzeichenverwaltung mit Anpassungs- und Extraktionsfunktionen."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Codebeispiele"
  description: "Einige reale Szenarien von GroupDocs.Total für die Java-Nutzung"
  items:
    # code sample loop
    - title: "Verträge sichern und organisieren: Anbringen von Wasserzeichen und Verwalten von Metadaten in der DOCX-Datei"
      content: |
        Schützen und organisieren Sie Ihre Word-Dokumente effizient mit diesem umfassenden Codebeispiel. Das folgende Beispiel ermöglicht Ihnen die Implementierung einer robusten Wasserzeichen- und Metadatenverwaltung in Ihren Vertragsworkflow für mehr Sicherheit und Informationsmanagement. Es zeigt, wie man: <br><br>
        <b>Wenden Sie ein benutzerdefiniertes Wasserzeichen an:</b> Fügen Sie dem Dokument für visuelle Klarheit und Schutz ein auffälliges „Vertragsentwurf“-Wasserzeichen hinzu. [Passen Sie das Wasserzeichen an](https://docs.groupdocs.com/watermark/java/adding-text-watermarks/) mit Optionen für Schriftart, Farbe, Deckkraft und Ausrichtung. <br><br>
        <b>Metadaten verbessern:</b> [Dokumentmetadaten einfach ändern](https://docs.groupdocs.com/metadata/java/working-with-metadata-in-word-processing-documents/), um wichtige Details wie Autor, Erstellungszeit, Unternehmen, Kategorie, und Schlüsselwörter für eine bessere Organisation und Durchsuchbarkeit.
       
        {{< landing/code title="Java">}}
        ```java {style=abap}  
        import com.groupdocs.metadata.Metadata;
        import com.groupdocs.watermark.Watermark;
        import com.groupdocs.watermark.Watermark.Common;
        import com.groupdocs.watermark.Options.HtmlViewOptions;
        
        // Laden Sie Ihr Dokument in den Wasserzeichendrucker
        Watermarker watermarker = new Watermarker("contract.docx");
        
        // Legen Sie den gewünschten Text und die gewünschte Schriftart für das Wasserzeichen fest
        TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 36));
          
        // Wählen Sie Schriftfarbe und Textopazität, Drehung und Ausrichtung
        watermark.setForegroundColor(Color.getRed());                                                            
        watermark.setHorizontalAlignment(HorizontalAlignment.Center);                                            
        watermark.setVerticalAlignment(VerticalAlignment.Center);                               

        // Bringen Sie das Wasserzeichen an
        watermarker.add(watermark);
        
        // Speichern Sie das resultierende Dokument
        watermarker.save("watermarked-contract.docx");
        
        Metadata metadata = new Metadata("watermarked-contract.docx");        
        WordProcessingRootPackage root = metadata.getRootPackageGeneric();

        // Aktualisieren Sie die Metadateneigenschaften des Dokuments
        root.getDocumentProperties().setAuthor("Name Surname");
        root.getDocumentProperties().setCreatedTime(new Date());
        root.getDocumentProperties().setCompany("Company Name");
        root.getDocumentProperties().setCategory("Work materials");
        root.getDocumentProperties().setKeywords("contract, watermarked");

        // Dokument mit aktualisierten Metadaten speichern
        metadata.save("contract-final.docx");                
        ```
        {{< /landing/code >}}

    # code sample loop
    - title: "Optimierte Schwärzung von Dokumenten"
      content: |
        <b>Szenario:</b> Eine große Anwaltskanzlei verarbeitet häufig verschiedene Dokumente mit vertraulichen Mandanteninformationen, die vor der Weitergabe an Dritte oder zur öffentlichen Offenlegung redigiert werden müssen. Das manuelle Bearbeiten dieser sensiblen Informationen kann mühsam, zeitaufwändig und anfällig für menschliches Versagen sein. Um Effizienz, Genauigkeit und Einhaltung der Datenschutzbestimmungen sicherzustellen, sucht die Anwaltskanzlei nach einer automatisierten Lösung zur Optimierung des Schwärzungsprozesses von Dokumenten. 
        
        <br>

        <b>Lösung:</b>
        GroupDocs.Total automatisiert den Prozess und löst beim Empfang eines Dokuments eine Schwärzung aus. Darüber hinaus ermöglichen [flexible Optionen](https://docs.groupdocs.com/redaction/java/text-redactions/) die Anpassung, indem Sie Regeln festlegen, Schwärzungsmodi auswählen (z. B. schwärzen, durch Sternchen ersetzen) und angeben bestimmte Abschnitte oder Seiten zur Redaktion. Schließlich generiert [benutzerfreundliche Ausgabe](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) redigierte Dokumente im PDF-Format zur einfachen Weitergabe und Überprüfung, während verbesserte Sicherheit und Überprüfbarkeit das Ganze gewährleisten Der Prozess wird im Hinblick auf Compliance und Verantwortlichkeit dokumentiert. 
        <br><br>
        Mit dieser umfassenden Lösung können Rechtsexperten und andere Organisationen die Redaktionszeit und -kosten erheblich reduzieren, menschliche Fehler minimieren und vertrauliche Informationen stets vertrauensvoll behandeln.        
              
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.redaction.Redaction;
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // Dokument mit privaten Daten in Redactor laden 
        Redactor redactor = new Redactor("customer-info.docx");
        
        // Schwärzungsoptionen einrichten und anpassen 
        redactor.apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
        
        // Schwärzungen anwenden und Ergebnis speichern 
        redactor.save();

        // Laden Sie die redigierte Datei zur Überprüfung 
        Viewer viewer = new Viewer("customer-info.docx");
        
        // Richten Sie PDF als gewünschtes Anzeigeformat ein       
        PdfViewOptions viewOptions = new PdfViewOptions("redacted-info.pdf");

        // Dokument als PDF speichern      
        viewer.view(viewOptions);        
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs-Produktbewertungen"
# description: "Verlassen Sie sich nicht nur auf unser Wort. Sehen Sie, was andere Entwickler über unsere APIs sagen"

# items:
#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Exzellenter Service und hervorragende Produkte. Sie waren während des GroupDocs.Viewer für .NET-Implementierungsprozesses äußerst hilfsbereit und reaktionsschnell und können sie nur wärmstens empfehlen."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Nach der Implementierung und Verwendung von GroupDocs.Viewer für Java im Projekt scheint es sehr gut zu funktionieren. Ich habe es mit vielen Dokumenten getestet und bisher so gut. Alles, was ich darauf geworfen habe, wird gut gerendert und sieht genauso gut aus wie in einem PDF-Viewer oder MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---