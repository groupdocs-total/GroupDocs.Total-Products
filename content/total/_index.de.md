---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Total"
product_tag: "total"

############################# Head ############################
head_title: "Dokumentautomatisierungs-APIs | On-Premise-APIs und Online-Dienste"
head_description: "Automatisieren Sie Ihre Dokumentenbearbeitung einfach und kostenlos"

############################# Header ##########################
title: "Automatisierung von Masterdokumenten mit der All-in-One-Suite"
description: |
  Vereinfachen Sie wiederkehrende Dokumentaufgaben und optimieren Sie Ihre Arbeitsabläufe mit nur wenigen Codezeilen. Leistungsstarke APIs machen die Integration mühelos und ermöglichen Ihnen, sich auf Innovation und nicht auf die Infrastruktur zu konzentrieren.

  Konvertieren, signieren, anzeigen, kommentieren – meistern Sie jede Dokumentaufgabe mit minimalem Code. Von Word bis PDF, von Excel bis hin zu Bildern – erledigen Sie alles nahtlos. Weniger Code, größere Wirkung.

  Automatisieren Sie Dokumentenaufgaben, steigern Sie die Effizienz und arbeiten Sie schnell mit der blitzschnellen Integration. Sparen Sie Zeit und Ressourcen und konzentrieren Sie sich auf das, was für Ihr Unternehmen wirklich wichtig ist.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Wählen Sie Ihre Plattform"
  title: "Unterstützte Plattformen"
  description: "Die GroupDocs.Total-Bibliothek unterstützt die folgenden Betriebssysteme und Frameworks"
  details_link_title: "Erfahren Sie mehr"
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
        - content: "Über 200 Dateiformate"
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
        - content: "Über 200 Dateiformate"
          rows: "1"
        # features loop
        - content:  "Eclipse <br> NetBeans <br> IntelliJ Idea"
          rows: "3"

############################# Features ############################

features:
  enable: true
  title: "Der Funktionsumfang von GroupDocs.Total"
  description: "Eine einzige Lösung, die die Funktionalität aller einzelnen GroupDocs-Produkte unter einem Dach vereint und jede Dokumentaufgabe ohne Software von Drittanbietern verwaltet."

  items:
    # feature loop
    - icon: "view"
      title: "Dokumente und Bilder ansehen"
      content: "Rendern Sie Dateien, um sie in den Formaten HTML, PDF, PNG und JPEG anzuzeigen."

    # feature loop
    - icon: "convert"
      title: "Konvertieren Sie zwischen Formaten"
      content: "Transformieren Sie Dateien aus verschiedenen Quellen in verschiedene Zielformate."

    # feature loop
    - icon: "merge"
      title: "Mehrere Dateien zu einer zusammenführen"
      content: "Kombinieren Sie mehrere PDF-, Office- und andere Dokumente nahtlos in einem einzigen Dokument."
    
    # feature loop
    - icon: "settings"
      title: "Weitere Produkte und Funktionen"
      content: "Entdecken Sie alle GroupDocs-APIs zur Dokumentautomatisierung: Vergleichen, E-Singen, Suchen, Wasserzeichen und mehr!"


############################# Code samples ############################
# code_samples:
#   enable: true
#   title: "GroupDocs.Total-Codebeispiele"
#   description: "Einige Anwendungsfälle typischer GroupDocs.Total-Operationen in C#, Java, TypeScript"
#   items:
#     # code sample loop
#     - title: "So rendern Sie DOCX-Dateien in PDF"
#       content: |
#        Rendern Sie DOCX-Dokumente in PDF, ohne dass Microsoft Word oder andere Software installiert ist. Laden Sie einfach DOCX-Dateien in Ihre Java-Anwendung und zeigen Sie sie an, unabhängig davon, ob es sich um eine Web- oder Desktop-Anwendung handelt. Hier ist ein Beispiel für das Rendern einer DOCX-Datei in PDF:
#       samples:
#         - language: "C#"
#           color: "blue"
#           content: |
#             ```csharp {style=abap}   
#             // Laden Sie die DOCX-Datei zum Rendern
#             using (Viewer viewer = new Viewer("sample.docx"))
#             {
#               // Rendern Sie DOCX in eine PDF-Datei
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
#             // Laden Sie die DOCX-Datei zum Rendern
#             try (Viewer viewer = new Viewer("sample.docx")) {
#                 // Rendern Sie DOCX in eine PDF-Datei
#                 PdfViewOptions viewOptions = new PdfViewOptions();
#                 viewer.view(viewOptions);
#             }
#             ```
#         - language: "TypeScript"
#           color: "green"
#           content: |
#             ```javascript {style=abap}  
#             // Laden Sie die DOCX-Datei zum Rendern
#             const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
#             // Rendern Sie DOCX in eine PDF-Datei
#             const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
#             viewer.view(viewOptions)
#             ```


############################# Formats ############################
formats:
  enable: true
  title:  "Über 200 Dateiformate werden unterstützt"
  description: "GroupDocs.Total unterstützt Vorgänge mit den gängigsten [Dateiformaten](https://docs.groupdocs.com/total/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "Detaillierte Kennzahlen und statistische Erkenntnisse"
  description: "Tauchen Sie ein in eine detaillierte Aufschlüsselung unserer Schlüsselzahlen und bieten Sie umfassende Kennzahlen und statistische Einblicke in unsere Erfolge, Auswirkungen und unser Wachstum."

  items:
    # metrics loop
    - number: "200+"
      title: "Unterstützte Formate"
      content: "Sehen Sie sich problemlos über 200 Dateiformate an, darunter Dokumente, Bilder und CAD-Zeichnungen. Überwinden Sie Kompatibilitätsbarrieren und greifen Sie mit unserer umfassenden Anzeigelösung mühelos auf verschiedene Dateien zu."
    # metrics loop
    - number: "550K"
      title: "NuGet-Downloads"
      content: "Unsere NuGet-Paketlösung hat sich zu einer vertrauenswürdigen und weit verbreiteten Ressource in der Entwicklergemeinschaft entwickelt und bietet nahtlose Integration und wertvolle Funktionalität für unzählige Projekte."

    # metrics loop
    - number: "10+"
      title: "Bibliotheken"
      content: "Unser Produkt umfasst mehr als 10 Bibliotheken und bietet erweiterte Funktionen zur Optimierung der Leistung. Diese Bibliotheken sind darauf ausgelegt, unterschiedliche Entwicklungsanforderungen mit beispiellosen Fähigkeiten zu erfüllen."
    
    # metrics loop
    - number: "100+"
      title: "Zufriedene Kunden"
      content: "Wir beliefern die bekanntesten Marken rund um den Globus. Entdecken Sie, warum Hunderte GroupDocs.Total lieben! Entdecken Sie nahtlose Navigation, bequeme Zusammenarbeit und beispiellose Benutzerfreundlichkeit. Jetzt beitreten!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Unsere zufriedenen Kunden"
  description: "GroupDocs-Bibliotheken werden von weltweit bekannten und angesehenen Marken auf der ganzen Welt eingesetzt."

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
  title: "Bereit anzufangen?"
  description: "Testen Sie die Funktionen von GroupDocs.Total kostenlos oder fordern Sie eine Lizenz an"

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
  title: "Häufige Fragen und Bedenken"
  description: "In unserem FAQ-Bereich finden Sie Antworten auf häufig gestellte Fragen, um schnell auf Ihre Fragen und Bedenken einzugehen."

  items:
    #  loop
    - question: "Was ist GroupDocs.Total und wie unterscheidet es sich von anderen GroupDocs-Produkten?"
      answer: |
        GroupDocs.Total ist eine umfassende Suite, die die Funktionalitäten aller einzelnen GroupDocs-Produkte in einem einzigen Paket vereint. Dies bietet mehrere Vorteile: <br><br>
        <ul>
          <li>
            <b>Einheitliche Funktionen:</b> Sie haben Zugriff auf alle Funktionen zur Dokumentenverarbeitung, einschließlich Anzeigen, Konvertieren, Zusammenführen, Kommentieren, Signieren und mehr, innerhalb einer einzigen API. <br><br>
          </li>
          <li>
            <b>Verbesserte Kompatibilität:</b> GroupDocs.Total gewährleistet eine konsistente und zuverlässige Leistung über alle unterstützten Dateiformate und Plattformen hinweg und eliminiert Kompatibilitätsprobleme, die bei der Verwendung separater Produkte auftreten können. <br><br>
          </li>
          <li>
            <b>Optimierte Packungsgrößen:</b> Die Suite wird als einzelnes, kompaktes Paket geliefert, was den Ressourcenverbrauch reduziert und die Integration in Ihre Anwendungen im Vergleich zur Verwendung einzelner Produkte mit separaten Installationen vereinfacht.
          </li>
        <ul>

    #  loop
    - question: "Warum sollte man GroupDocs.Total bevorzugen, anstatt einzelne GroupDocs-Produkte zu kaufen?"
      answer: |
        Der Kauf einer einzelnen GroupDocs.Total-Lizenz kostet in der Regel weniger als der Kauf von Lizenzen für zwei oder mehr einzelne GroupDocs-Produkte. <br>
        Daraus ergeben sich mehrere entscheidende Vorteile für Sie: <br><br>
        <b>Einsparmaßnahmen:</b> GroupDocs.Total bietet einen erheblichen Rabatt im Vergleich zum Kauf einzelner Produkte, sodass Sie Ihr Budget noch weiter ausschöpfen können. <br><br>
        <b>Vereinfachte Verwaltung:</b> Mit GroupDocs.Total verwalten Sie alles unter einer Lizenz, sodass Sie nicht mehr mehrere Lizenzen für verschiedene Produkte verfolgen und verwalten müssen. Dies vereinfacht Ihre Verwaltungsaufgaben und reduziert die Gesamtkosten. <br><br>
        Wenn Sie nach einer kostengünstigen und funktionsreichen Lösung für Ihre Dokumentenverwaltungsanforderungen suchen, ist GroupDocs.Total die perfekte Wahl.

    #  loop
    - question: "Wie fange ich mit GroupDocs.Total an?"
      answer: |
        Sie können mit einer kostenlosen Testversion beginnen, um die Funktionen zu erkunden und zu sehen, ob sie Ihren Anforderungen entspricht. GroupDocs bietet außerdem verschiedene [Dokumentation](https://docs.groupdocs.com/total/)-Ressourcen und [Tutorials](https://groupdocs.github.io), um Ihnen den Einstieg in die Integration und Entwicklung zu erleichtern.
        
    #  loop
    - question: "Bietet GroupDocs.Total technischen Support?"
      answer: |
        Ja, GroupDocs bietet umfassenden technischen Support, um Ihren Erfolg mit GroupDocs.Total sicherzustellen. Sie haben zwei Möglichkeiten: <br><br>
        <b>[Kostenloses Support-Forum](https://forum.groupdocs.com):</b> In diesem Forum können Sie mit GroupDocs-Mitarbeitern in Kontakt treten, die Ihre Fragen beantworten und auf der Grundlage ihrer Erfahrung Lösungen anbieten können. Es ist eine großartige Ressource für häufige Probleme und allgemeine Anfragen. <br><br>
        <b>[Kostenpflichtiger Support-Helpdesk](https://helpdesk.groupdocs.com):</b> Diese Option bietet Support auf Prioritätsbasis. Wenn Sie auf komplexe Probleme stoßen oder schnellere Lösungen benötigen, bietet der kostenpflichtige Support personalisierte Unterstützung und schnellere Reaktionszeiten. <br><br>
        Durch die Bereitstellung sowohl kostenloser als auch kostenpflichtiger Optionen geht GroupDocs auf unterschiedliche Bedürfnisse und Budgets ein und stellt sicher, dass Sie die Unterstützung erhalten, die Sie benötigen, um mit GroupDocs.Total erfolgreich zu sein.

    #  loop
    - question: "Benötigt GroupDocs.Total zusätzliche Software zur Dokumentenbearbeitung?"
      answer: |
        GroupDocs.Total ist eine eigenständige Suite und erfordert keine zusätzliche Software von Drittanbietern für grundlegende Dokumentenbearbeitungsaufgaben wie Anzeigen, Konvertieren, Kommentieren oder Signieren. Abhängig von den spezifischen Funktionen, die Sie verwenden (z. B. OCR für gescannte Dokumente), sind jedoch möglicherweise externe Bibliotheken erforderlich.

############################# Cloud and Apps ############################

cloud_links:
  enable: true
  title: "GroupDocs.Gesamtlösungen"
  description: "Beschleunigen Sie die Dokumentenverarbeitung in Ihren Anwendungen mit unserer Cloud-REST-API und kostenlosen Online-Apps"

  items:
    #  loop
    - icon: "groupdocs_total-cloud"
      title: "GroupDocs.Total Cloud"
      link: "https://products.groupdocs.cloud/total"
      content: "Robuste Cloud-Lösungen zur effizienten Automatisierung der Verarbeitung von Microsoft Office- und PDF-Dokumenten in Ihren Anwendungen."

    #  loop
    - icon: "groupdocs_total-apps"
      title: "GroupDocs.Total Online Apps"
      link: "https://products.groupdocs.app"
      content: "Kostenlose Online-Web-Apps zum Anzeigen und Bearbeiten von Dokumentinhalten sowie zum Vergleichen und Zusammenführen verschiedener Microsoft Office-, OpenOffice-, Bilder- und anderer gängiger Dateiformate."    

    #  loop
    - icon: "groupdocs_total-windows"
      title: "GroupDocs.Total Windows"
      link: "https://products.groupdocs.app/total/windows"
      content: "Offline-Apps zum Konvertieren, Kommentieren, Vergleichen, Signieren, Zusammenstellen, Analysieren, Klassifizieren, Schwärzen und Durchsuchen von Dokumenten auf jedem Betriebssystem."   

---