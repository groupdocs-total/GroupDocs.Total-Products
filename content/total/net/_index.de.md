---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: de
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
head_title: "All-in-One-Dokumentautomatisierungsbibliothek für .NET-Anwendungen"
head_description: "GroupDocs.Total für .NET ist eine All-in-One-API-Suite zur Dokumentautomatisierung für .NET-Entwickler und bietet einen umfassenden Satz an Tools für die Arbeit mit verschiedenen Dokumentformaten, darunter PDF, Word, Excel, Bild, HTML, Diagramm und mehr ."

############################# Header ##########################
title: "Optimieren Sie die Dokumentenautomatisierung<br>in Ihren .NET-Apps"
description: "Schalten Sie die Automatisierung von Dokumenten frei: Konvertieren, Anzeigen und Vergleichen, Bearbeiten und Signieren von mehr als 200 Formaten ganz einfach."
words:
  for: "for"

actions:
  main: "Kostenloser NuGet-Download"
  main_link: "https://www.nuget.org/packages/GroupDocs.Total"
  alt: "Lizenzierung"
  alt_link: "https://purchase.groupdocs.com/pricing/total/net"
  title: "Bereit anzufangen?"
  description: "Testen Sie die Funktionen von GroupDocs.Total kostenlos oder fordern Sie eine Lizenz an"

release:
  title: "Version {0} veröffentlicht"
  notes: "Schau was neu ist"
  downloads: "Downloads"
  link: "https://releases.groupdocs.com/total/net/release-notes/latest/"

code:
  title: "Word-Dateien in C# zusammenführen und anzeigen"
  more: "Mehr Beispiele"
  more_link: "https://github.com/groupdocs-total/GroupDocs.Total-for-.NET"
  install: "dotnet add package GroupDocs.Total"
  content: |
    ```csharp {style=abap} 
    // Laden Sie die DOCX-Quelldatei
    using (Merger merger = new Merger("sample1.docx"))
    {
        // Fügen Sie eine weitere DOCX-Datei zum Zusammenführen hinzu
        merger.Join("sample2.docx");

        // DOCX-Dateien zusammenführen und Ergebnis speichern
        merger.Save("merged.docx");
    }

    // Laden Sie die zusammengeführte DOCX-Datei in den Viewer
    using (var viewer = new Viewer("merged.docx"))
    {
        // Legen Sie Ausgabe-HTML-Optionen fest, eine Datei pro Seite
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // Rendern Sie DOCX mit eingebetteten Ressourcen in HTML        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Total auf einen Blick"
  description: "Automatisieren Sie Dateiansicht, Konvertierung, Bearbeitung, Vergleich, Suche, Wasserzeichen und andere Arbeitsabläufe in .NET-Anwendungen"
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
      content: "GroupDocs.Total für .NET ermöglicht die Kompatibilität mit über 200 Dateiformaten und ermöglicht Ihnen die Verarbeitung von Dokumenten aller gängigen Typen. Von Office-Formaten wie Word und Excel bis hin zu Bildern, Code und verschlüsselten Dateien sind Sie bei uns genau richtig."

    # feature loop
    - title: "Plattformübergreifende Unterstützung"
      content: "Befreien Sie sich von Plattformbeschränkungen. GroupDocs.Total bietet plattformübergreifende Kompatibilität und ermöglicht es Ihnen, Benutzern auf jedem System, auf dem .NET installiert werden kann, optimale Leistung und Lösungsverfügbarkeit zu bieten."

############################# Platforms ############################
platforms:
  enable: true
  title: "Plattformunabhängigkeit"
  description: "GroupDocs.Total für .NET unterstützt die folgenden Betriebssysteme, Frameworks und Paketmanager"
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
  title: "Unterstützte Dateiformate"
  description: |
    GroupDocs.Total für .NET unterstützt Vorgänge mit den folgenden [Dateiformaten](https://docs.groupdocs.com/total/net/supported-document-formats/).
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
  description: "Einige reale Szenarien von GroupDocs.Total für die .NET-Nutzung"
  items:
    # code sample loop
    - title: "Verträge sichern und organisieren: Anbringen von Wasserzeichen und Verwalten von Metadaten in der DOCX-Datei"
      content: |
        Schützen und organisieren Sie Ihre Word-Dokumente effizient mit diesem umfassenden Codebeispiel. Das folgende Beispiel ermöglicht Ihnen die Implementierung einer robusten Wasserzeichen- und Metadatenverwaltung in Ihren Vertragsworkflow für mehr Sicherheit und Informationsmanagement. Es zeigt, wie man: <br><br>
        <b>Wenden Sie ein benutzerdefiniertes Wasserzeichen an:</b> Fügen Sie dem Dokument für visuelle Klarheit und Schutz ein auffälliges „Vertragsentwurf“-Wasserzeichen hinzu. [Passen Sie das Wasserzeichen an](https://docs.groupdocs.com/watermark/net/basic-usage/customize/) mit Optionen für Schriftart, Farbe, Deckkraft und Ausrichtung. <br><br>
        <b>Metadaten verbessern:</b> [Ändern Sie ganz einfach die Metadaten von Dokumenten](https://docs.groupdocs.com/metadata/net/working-with-metadata-in-wordprocessing-documents/), um wichtige Details wie Autor, Erstellungszeit, Unternehmen, Kategorie und Schlüsselwörter einzuschließen für eine verbesserte Organisation und Durchsuchbarkeit.
       
        {{< landing/code title="C#">}}
        ```csharp {style=abap}  
        using GroupDocs.Metadata;
        using GroupDocs.Watermark;
        using GroupDocs.Watermark.Common;
        using GroupDocs.Watermark.Watermarks;
        
        // Laden Sie Ihr Dokument in den Wasserzeichendrucker
        using (Watermarker watermarker = new Watermarker("contract.docx"))
        {
            // Legen Sie den gewünschten Text und die gewünschte Schriftart für das Wasserzeichen fest
            TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 60, FontStyle.Bold));
            
            // Wählen Sie Schriftfarbe und Textopazität, Drehung und Ausrichtung
            watermark.ForegroundColor = Color.DarkGreen;
            watermark.Opacity = 0.5;
            watermark.HorizontalAlignment = HorizontalAlignment.Center;
            watermark.VerticalAlignment = VerticalAlignment.Center;
            
            // Bringen Sie das Wasserzeichen an
            watermarker.Add(watermark);
            
            // Speichern Sie das resultierende Dokument
            watermarker.Save("watermarked-contract.docx");
        }

        using (Metadata metadata = new Metadata("watermarked-contract.docx"))
        {
          var root = metadata.GetRootPackage<WordProcessingRootPackage>();

          // Aktualisieren Sie die Metadateneigenschaften des Dokuments
          root.DocumentProperties.Author = "Name Surname";
          root.DocumentProperties.CreatedTime = DateTime.Now;
          root.DocumentProperties.Company = "Company Name";
          root.DocumentProperties.Category = "Work materials";
          root.DocumentProperties.Keywords = "contract, watermarked";

          // Dokument mit aktualisierten Metadaten speichern
          metadata.Save("contract-final.docx");
        }        
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Optimierte Schwärzung von Dokumenten"
      content: |
        <b>Szenario:</b> Eine große Anwaltskanzlei verarbeitet häufig verschiedene Dokumente mit vertraulichen Mandanteninformationen, die vor der Weitergabe an Dritte oder zur öffentlichen Offenlegung redigiert werden müssen. Das manuelle Bearbeiten dieser sensiblen Informationen kann mühsam, zeitaufwändig und anfällig für menschliches Versagen sein. Um Effizienz, Genauigkeit und Einhaltung der Datenschutzbestimmungen sicherzustellen, sucht die Anwaltskanzlei nach einer automatisierten Lösung zur Optimierung des Schwärzungsprozesses von Dokumenten. 
        
        <br>

        <b>Lösung:</b>
        GroupDocs.Total automatisiert den Prozess und löst beim Empfang eines Dokuments eine Schwärzung aus. Darüber hinaus ermöglichen [flexible Optionen](https://docs.groupdocs.com/redaction/net/text-redactions/) die Anpassung, indem Sie Regeln festlegen, Schwärzungsmodi auswählen (z. B. schwärzen, durch Sternchen ersetzen) und angeben bestimmte Abschnitte oder Seiten zur Redaktion. Schließlich generiert [benutzerfreundliche Ausgabe](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) redigierte Dokumente im PDF-Format zur einfachen Weitergabe und Überprüfung, während verbesserte Sicherheit und Überprüfbarkeit das Ganze gewährleisten Der Prozess wird im Hinblick auf Compliance und Verantwortlichkeit dokumentiert. 
        <br><br>
        Mit dieser umfassenden Lösung können Rechtsexperten und andere Organisationen die Redaktionszeit und -kosten erheblich reduzieren, menschliche Fehler minimieren und vertrauliche Informationen stets vertrauensvoll behandeln.        
              
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Redaction;
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;

        // Dokument mit privaten Daten in Redactor laden 
        using (Redactor redactor = new Redactor("customer-info.docx"))
        {
          // Schwärzungsoptionen einrichten und anpassen 
          redactor.Apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
          // Schwärzungen anwenden und Ergebnis speichern 
          redactor.Save();
        }

        // Laden Sie die redigierte Datei zur Überprüfung 
        using (var viewer = new Viewer("customer-info.docx"))
        {
          // Richten Sie PDF als gewünschtes Anzeigeformat ein       
          var viewOptions = new PdfViewOptions("redacted-info.pdf");

          // Dokument als PDF speichern      
          viewer.View(viewOptions);
        }
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