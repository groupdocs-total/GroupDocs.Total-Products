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
head_title: "C# .NET-APIs zum Anzeigen, Konvertieren, Kommentieren, Signieren, Automatisieren, Wasserzeichen, Schwärzen und Suchen von Dateiformaten"
head_description: "GroupDocs .NET-Dokumentbearbeitungsbibliotheken und -APIs. Verwenden Sie eine beliebige API in einer .NET-Anwendung zum Generieren, Bearbeiten oder Konvertieren von über 50 Dokumenten."

############################# Header ############################
title: ".NET-Dokumentautomatisierungs-APIs"
description: "APIs zum Anzeigen, Exportieren, Kommentieren, Vergleichen, Signieren, Automatisieren und Suchen von Dokumenten in Ihren .NET-Anwendungen."
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
            text: "Überblick"

          # button loop
          - link: "#products"
            text: "Produkte"

          # button loop
          - link: "#features"
            text: "Merkmale"

          # button loop
          - link: "#support"
            text: "Support"

          # button loop
          - link: "https://purchase.groupdocs.com/pricing/total/net"
            text: "Preisgestaltung"

  right:
      link_download: "https://downloads.groupdocs.com/total"
      link_learn: "https://docs.groupdocs.com/total/net/"
      link_buy: "https://purchase.groupdocs.com"

############################# Überblick ############################
overview:
    enable: true
    content: "GroupDocs.Total für .NET ist eine Zusammenstellung aller von GroupDocs angebotenen .NET-APIs. Wir kompilieren es täglich, um sicherzustellen, dass es die aktuellsten Versionen jeder unserer APIs zur Bearbeitung von .NET-Dokumenten enthält.
    <br><br>Mit GroupDocs.Total für .NET können Entwickler alle unsere APIs mit einer einzigen Lizenz nutzen. Sie können jedoch auch jede einzelne API bestellen. "

############################# Produkte ############################
products:
    enable: true
    title: "Produkte"
    description: "GroupDocs.Total für .NET enthält die folgenden Dokumentbearbeitungs-APIs für .NET:"

    product:
        # product loop
        - image: "/border/groupdocs-viewer-net.svg"
          img_alt: "GroupDocs.Viewer for .NET"
          name: "GroupDocs.Viewer for .NET"
          content: "Leistungsstarke Dokumentenbetrachter-API zum Rendern, Anzeigen und Anzeigen von Dokumenten in mehr als 50 Dateiformaten. Vollständiges Rendern des gesamten Dokuments, effizientes Rendern von Teildokumenten oder Rendern bestimmter Seiten/Zellbereiche. Rendern Sie einzelne Dokumentebenen mit oder ohne Anmerkungen und Kommentare für die unterstützten Dateiformate."
          link: "/viewer/net/"

        # product loop
        - image: "/border/groupdocs-annotation-net.svg"
          img_alt: "GroupDocs.Annotation for .NET"
          name: "GroupDocs.Annotation for .NET"
          content: "Anmerkungsverwaltungs-API zum Erstellen und Bearbeiten verschiedener Arten von Anmerkungen, z. B. Fläche, Text, Polylinie, Punkt, Unterstreichung usw. Sie bietet Ihnen eine umfassende Reihe von Markierungswerkzeugen zum Hervorheben, Durchstreichen, Markieren und Kommentieren von Text und Bildern . Drucken Sie die kommentierten Dokumente oder exportieren Sie sie zusammen mit den Anmerkungen in das PDF-Format."
          link: "/annotation/net/"

          # product loop
        - image: "/border/groupdocs-conversion-net.svg"
          img_alt: "GroupDocs.Conversion for .NET"
          name: "GroupDocs.Conversion for .NET"
          content: "Umfassende Dokumentenkonvertierungs-API zum Konfigurieren und Konvertieren von Dokumenten in mehr als 50 Dateiformaten. Mit Funktionen wie dem Rendern von E-Mail-Headern während der Konvertierung aus E-Mails, dem Festlegen benutzerdefinierter Schriftartverzeichnisse, dem Konfigurieren und Platzieren von Wasserzeichen und einer erweiterten Konvertierungsmethode usw. ist diese API viel mehr als ein einfaches Dateikonvertierungstool."
          link: "/conversion/net/"

          # product loop
        - image: "/border/groupdocs-comparison-net.svg"
          img_alt: "GroupDocs.Comparison for .NET"
          name: "GroupDocs.Comparison for .NET"
          content: "API zum Prüfen von Dokumentenunterschieden zum Vergleichen von Inhalten und Textstilen. Wählen Sie den Detaillierungsgrad für den Vergleichsprozess. Änderungen nach der Differenzanalyse anwenden oder ablehnen. Dokumente per Datei oder Stream abrufen. Geben Sie Worttrennzeichen und Schriftfarbe an, um verglichenen Text zu stilisieren. Vergleichen Sie passwortgeschützte Dateien."
          link: "/comparison/net/"

          # product loop
        - image: "/border/groupdocs-signature-net.svg"
          img_alt: "GroupDocs.Signature for .NET"
          name: "GroupDocs.Signature for .NET"
          content: "eSignatur-Manipulations-API zum Signieren digitaler Dokumente in verschiedenen Formaten. Rufen Sie alle im System vorhandenen registrierten Zertifikate ab. Wenden Sie Signaturen vieler Arten an, z. B. Text, Barcode, Bild, QR-Code usw. Führen Sie eine einfache und erweiterte Suche durch, um die gewünschten Signaturen zu finden. Konfigurieren Sie Signatureigenschaften wie Schatten, Ausrichtung, Abmessungen und vieles mehr."
          link: "/signature/net/"

          # product loop
        - image: "/border/groupdocs-assembly-net.svg"
          img_alt: "GroupDocs.Assembly for .NET"
          name: "GroupDocs.Assembly for .NET"
          content: "Dokumentenautomatisierung und API zur Berichterstellung durch Erstellen und Anpassen von Vorlagen für unterstützte Formate. Bearbeiten Sie Daten mithilfe von Formeln und sequentiellen Datenoperationen, formatieren Sie Zeichenfolgen in der Vorlagensyntax, legen Sie ordinale, kardinale, alphabetische und numerische Formatierungen fest. Variablen definieren; fügen Sie dynamisch Inhalte in Berichte mit bedingter Formatierung usw. ein."
          link: "/assembly/net/"

          # product loop
        - image: "/border/groupdocs-metadata-net.svg"
          img_alt: "GroupDocs.Metadata for .NET"
          name: "GroupDocs.Metadata for .NET"
          content: "Metadatenzugriffs- und Manipulations-API zum Lesen, Bearbeiten, Ersetzen und Entfernen von Metadaten verschiedener Dokumenttypen. Vergleichen Sie die Metadateneigenschaften zweier Dateien, um ihre Ähnlichkeiten und Unterschiede zu identifizieren. Metadaten nach Excel, CSV oder DataSet exportieren. Erkennen Sie den MIME-Typ einer bestimmten Datei oder eines Dateistreams. Standortinformationen aus Fotos entfernen. Reduzieren Sie den Speicherverbrauch von Dateien."
          link: "/metadata/net/"

          # product loop
        - image: "/border/groupdocs-search-net.svg"
          img_alt: "GroupDocs.Search for .NET"
          name: "GroupDocs.Search for .NET"
          content: "Dokument- und Textsuch-API, die grundlegende bis erweiterte Suchfunktionen bietet, z. B. Erstellen und Zusammenführen mehrerer Indizes, Suchen über Einfach, Boolean, Fuzzy, Regulärer Ausdruck (Regex) und andere Abfragetypen. Wenden Sie eine schnelle, zuverlässige und intelligente Suche auf Dateien, Dokumente und E-Mails an. Suche basierend auf homophonen Begriffen, Synonymen, Datumsbereich, Platzhaltern und Groß-/Kleinschreibung."
          link: "/search/net/"

          # product loop
        - image: "/border/groupdocs-parser-net.svg"
          img_alt: "GroupDocs.Parser for .NET"
          name: "GroupDocs.Parser for .NET"
          content: "Textextraktor-API, die die Extraktion von rohem, formatiertem und strukturiertem Text und Metadaten aus unterstützten Dateiformaten unterstützt. Passwortgeschützte Dokumente parsen. Wählen Sie zwischen schneller oder standardmäßiger Textextraktion. Der Markdown- und HTML-Formatierer unterstützt die Formatierung von Schriftarten, Hyperlinks, Überschriften, Listen und Tabellen. Abrufen von Daten aus dem E-Mail-Container (Exchange-Webserver, POP3, IMAP)."
          link: "/parser/net/"

          # product loop
        - image: "/border/groupdocs-watermark-net.svg"
          img_alt: "GroupDocs.Watermark for .NET"
          name: "GroupDocs.Watermark for .NET"
          content: "Digitale Wasserzeichenanwendung und Bearbeitungs-API zum Anwenden neuer Wasserzeichen, Suchen und Entfernen vorhandener Wasserzeichen aus Dokumenten mit unterstützten Formaten. Sperren Sie Wasserzeichen, um die Bearbeitung einzuschränken. Vorhandene Wasserzeichen ersetzen. Schützen Sie Textwasserzeichen mit unlesbaren Zeichen in Präsentationen. Ändern Sie Formeigenschaften wie Alternativtext, Drehwinkel usw. in der Präsentation."
          link: "/watermark/net/"

          # product loop
        - image: "/border/groupdocs-editor-net.svg"
          img_alt: "GroupDocs.Editor for .NET"
          name: "GroupDocs.Editor for .NET"
          content: "Dokumenteditor-API zum Laden eines Dokuments im unterstützten Dateiformat, zum Konvertieren in HTML, zum Übertragen von HTML in einen externen HTML-Editor und zum Speichern des HTML-Codes im ursprünglichen Dateiformat. Rufen Sie Ressourcen, die jedem Dokument beigefügt sind, separat ab. Holen Sie sich den CSS-Inhalt des HTML-Dokuments. HTML-DOM aus String-Inhalt abrufen und in Dokument konvertieren. Wenden Sie die Sicherheit auf das Ergebnisdokument an."
          link: "/editor/net/"

          # product loop
        - image: "/border/groupdocs-merger-net.svg"
          img_alt: "GroupDocs.Merger for .NET"
          name: "GroupDocs.Merger for .NET"
          content: "API zum Zusammenführen und Teilen von Dokumenten zum Kombinieren, Teilen, Neuanordnen, Austauschen, Trimmen und Entfernen einzelner Seiten oder einer Sammlung von Seiten, Folien oder Diagrammen. Setzen oder entfernen Sie den Passwortschutz für bekannte und unbekannte Dateiformate. Heften oder teilen Sie einzelne Dokumente oder Stapel von Dokumenten. Kürzen Sie das Dokument, indem Sie bestimmte Seiten, Folien oder Diagramme entfernen."
          link: "/merger/net/"

          # product loop
        - image: "/border/groupdocs-redaction-net.svg"
          img_alt: "GroupDocs.Redaction for .NET"
          name: "GroupDocs.Redaction for .NET"
          content: "API zur Schwärzung und Bereinigung von Dokumenten zum Schwärzen, Entfernen oder Ausblenden klassifizierter Informationen, Inhalte und Metadaten aus Dokumenten, Arbeitsblättern, PDF-Dateien und Folien."
          link: "/redaction/net/"

          # product loop
        - image: "/border/groupdocs-classification-net.svg"
          img_alt: "GroupDocs.Classification for .NET"
          name: "GroupDocs.Classification for .NET"
          content: "Klassifizierungs-API für Rohtext und Dokumente für .NET-Anwendungen. Klassifizieren Sie Inhalte und Dokumentformate wie Microsoft Office Word, PDF, OpenDocument, RTF und Text mithilfe mehrerer Taxonomien, darunter Dokumente und IAB-2. Passen Sie die klassifizierten Ergebnisse mit einer Reihe erweiterter Funktionen ganz einfach an Ihre Anforderungen an."
          link: "/classification/net/"

############################# Merkmale ############################
features:
    enable: true
    title: "Advanced API Merkmale"

    feature:
      # feature loop
      - icon: "fas fa-eye"
        content: "Zeigen Sie jedes Dokument in seinem Originalformat oder im HTML-, Bild- oder PDF-Format an"

      # feature loop
      - icon: "fas fa-file"
        content: "Kommentieren Sie alle PDF-, DOCX-, XLSX- und PPTX-Dokumente"
      
      # feature loop
      - icon: "fas fa-file-export"
        content: "Exportieren Sie Anmerkungen in eine separate PDF- oder Word-Datei"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Schnellste On-the-Fly-Konvertierungs-API"

      # feature loop
      - icon: "fas fa-clone"
        content: "Stapelkonvertierung mehrerer Dateien"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Vergleicht Inhalt auf Unterschiede in Wörtern und Absätzen"

      # feature loop
      - icon: "fas fa-file-contract"
        content: "Separate Zusammenfassung der Unterschiede bei Verwendung der Vergleichs-API"

      # feature loop
      - icon: "fas fa-signature"
        content: "Mehrere Signatureigenschaften"

      # feature loop
      - icon: "fas fa-file-signature"
        content: "Signatur auf beliebigen Seiten einrichten, wie erste, letzte, gerade, ungerade usw"

      # feature loop
      - icon: "fas fa-server"
        content: "Generieren Sie Multiformat-Dokumente aus mehr als einer Datenquelle"

      # feature loop
      - icon: "fas fa-key"
        content: "Integrierte und benutzerdefinierte Metadatenoperationen in Form von Schlüssel/Wert-Paaren"

      # feature loop
      - icon: "fas fa-file-download"
        content: "Exportieren Sie Metadaten, die mit unterstützten Dateiformaten angehängt sind"

      # feature loop
      - icon: "fab fa-searchengin"
        content: "Mehrere grundlegende und erweiterte Suchmethoden"

      # feature loop
      - icon: "fas fa-search"
        content: "Fuzzy and Synonymsuche"

      # feature loop
      - icon: "fas fa-search-minus"
        content: "Suchen und entfernen Sie das Text-/Bild-Wasserzeichen"

      # feature loop
      - icon: "fas fa-file-image"
        content: "Hinzufügen von Wasserzeichen zu Bildern in einem Dokument"

      # feature loop
      - icon: "fas fa-file-alt"
        content: "Extrahieren Sie strukturierten und hervorgehobenen Text"
      
      # feature loop
      - icon: "fas fa-file-archive"
        content: "Ruft Text aus Containern ab, die andere Dateien wie ZIP-Archive enthalten"

      # feature loop
      - icon: "fas fa-file-invoice"
        content: "Direkte und inverse Dokumententransformation"

      # feature loop
      - icon: "fas fa-edit"
        content: "Bearbeiten Sie mehrere Dokumentformate"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: false
    title: "GroupDocs.Total für .NET bietet individuelle Lösungen für"

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
