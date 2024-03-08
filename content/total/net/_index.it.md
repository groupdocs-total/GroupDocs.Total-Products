---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: it
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
head_title: "Libreria di automazione dei documenti all-in-one per applicazioni .NET"
head_description: "GroupDocs.Total per .NET è una suite API all-in-one per l'automazione dei documenti per sviluppatori .NET, che fornisce un set completo di strumenti per lavorare con vari formati di documenti, tra cui PDF, Word, Excel, Immagine, HTML, Diagramma e altro ancora ."

############################# Header ##########################
title: "Semplifica l'automazione dei documenti<br> nelle tue app .NET"
description: "Sblocca l'automazione dei documenti: converti, visualizza e confronta, modifica e firma facilmente tra più di 200 formati."
words:
  for: "for"

actions:
  main: "Download gratuito di NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Total"
  alt: "Licenza"
  alt_link: "https://purchase.groupdocs.com/pricing/total/net"
  title: "Pronti per iniziare?"
  description: "Prova gratuitamente le funzionalità di GroupDocs.Total o richiedi una licenza"

release:
  title: "Versione {0} rilasciata"
  notes: "Scopri le novità"
  downloads: "Download"
  link: "https://releases.groupdocs.com/total/net/release-notes/latest/"

code:
  title: "Unisci e visualizza file Word in C#"
  more: "Altri esempi"
  more_link: "https://github.com/groupdocs-total/GroupDocs.Total-for-.NET"
  install: "dotnet add package GroupDocs.Total"
  content: |
    ```csharp {style=abap} 
    // Carica il file DOCX di origine
    using (Merger merger = new Merger("sample1.docx"))
    {
        // Aggiungi un altro file DOCX da unire
        merger.Join("sample2.docx");

        // Unisci file DOCX e salva il risultato
        merger.Save("merged.docx");
    }

    // Carica il file DOCX unito nel visualizzatore
    using (var viewer = new Viewer("merged.docx"))
    {
        // Imposta le opzioni HTML di output, un file per pagina
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // Renderizza DOCX in HTML con risorse incorporate        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Total in breve"
  description: "Automatizza la visualizzazione di file, la conversione, la modifica, il confronto, la ricerca, l'applicazione di filigrane e altri flussi di lavoro nelle applicazioni .NET"
  features:
    # feature loop
    - title: "Combina la potenza di più prodotti GroupDocs in un'unica soluzione completa"
      content: | 
        Puoi utilizzare le funzionalità di diversi prodotti GroupDocs per creare un approccio personalizzato che soddisfi le tue esigenze specifiche.
        <br><br>
        Ad esempio, puoi convertire un file Word in PDF e quindi aggiungere una firma digitale. Oppure compila i dati di un modello di documento da un database o estrai il testo da un'immagine e poi traducilo in un'altra lingua.
        <br><br>
        Le possibilità sono infinite!
          
    # feature loop
    - title: "Padroneggia la diversità dei formati di file"
      content: "GroupDocs.Total per .NET sblocca la compatibilità con oltre 200 formati di file, consentendoti di elaborare documenti di tutti i tipi più diffusi. Dai formati per ufficio come Word ed Excel alle immagini, al codice e ai file crittografati, ti offriamo la soluzione."

    # feature loop
    - title: "Supporto multipiattaforma"
      content: "Liberati dalle limitazioni della piattaforma. GroupDocs.Total fornisce compatibilità multipiattaforma, consentendoti di offrire prestazioni ottimali e disponibilità della soluzione agli utenti su qualsiasi sistema in cui è possibile installare .NET."

############################# Platforms ############################
platforms:
  enable: true
  title: "Indipendenza dalla piattaforma"
  description: "GroupDocs.Total per .NET supporta i seguenti sistemi operativi, framework e gestori di pacchetti"
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
  title: "Formati di file supportati"
  description: |
    GroupDocs.Total per .NET supporta operazioni con i seguenti [formati di file](https://docs.groupdocs.com/total/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument e formati di testo
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
        ### Immagini, grafica e diagrammi
        * **Immagini raster:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Altro        
        * **ragnatela:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Archivi:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Altro:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Funzionalità di GroupDocs.Total"
  description: "Gestisci, esegui il rendering e converti in modo completo PDF e documenti Office"

  items:
    # feature loop
    - icon: "viewer"
      title: "Visualizzazione estesa dei file"
      content: "Visualizzazione completa di documenti per oltre 180 formati, inclusi HTML, immagini e PDF."

    # feature loop
    - icon: "conversion"
      title: "Conversione del formato"
      content: "Conversione perfetta tra vari formati di documenti senza strumenti esterni."

    # feature loop
    - icon: "annotation"
      title: "Annotazione interattiva"
      content: "Funzionalità di annotazione avanzate per elementi di testo e immagine all'interno dei documenti."

    # feature loop
    - icon: "comparison"
      title: "Confronto dei contenuti"
      content: "Confronto preciso dei documenti, evidenziando le differenze di contenuto e stile."

    # feature loop
    - icon: "signature"
      title: "Flessibilità della firma"
      content: "Opzioni di firma versatili, tra cui testo, immagine e firme digitali."

    # feature loop
    - icon: "assembly"
      title: "Creazione di documenti basata su modelli"
      content: "Generazione automatizzata di documenti da modelli e origini dati esterne."

    # feature loop
    - icon: "metadata"
      title: "Gestione dei metadati"
      content: "Robusto accesso e manipolazione dei metadati per un migliore controllo dei documenti."

    # feature loop
    - icon: "search"
      title: "Ricerca Avanzata"
      content: "Potente funzionalità di ricerca con supporto per algoritmi fuzzy e sinonimi."

    # feature loop
    - icon: "watermark"
      title: "Controllo filigrana"
      content: "Gestione semplice della filigrana dei documenti, che offre funzionalità di personalizzazione ed estrazione."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Esempi di codici"
  description: "Alcuni scenari reali di GroupDocs.Total per l'utilizzo di .NET"
  items:
    # code sample loop
    - title: "Proteggi e organizza i contratti: applica filigrane e gestisci i metadati nel file DOCX"
      content: |
        Proteggi e organizza in modo efficiente i tuoi documenti Word con questo esempio di codice completo. L'esempio seguente ti consente di implementare una solida gestione della filigrana e dei metadati all'interno del flusso di lavoro del contratto per una maggiore sicurezza e gestione delle informazioni. Dimostra come: <br><br>
        <b>Applica una filigrana personalizzata:</b> Aggiungi una filigrana prominente "Bozza di contratto" al documento per chiarezza visiva e protezione. [Personalizza la filigrana](https://docs.groupdocs.com/watermark/net/basic-usage/customize/) con opzioni di carattere, colore, opacità e allineamento. <br><br>
        <b>Migliora i metadati:</b> [modifica facilmente i metadati del documento](https://docs.groupdocs.com/metadata/net/working-with-metadata-in-wordprocessing-documents/) per includere dettagli essenziali come autore, ora di creazione, azienda, categoria e parole chiave per una migliore organizzazione e ricercabilità.
       
        {{< landing/code title="C#">}}
        ```csharp {style=abap}  
        using GroupDocs.Metadata;
        using GroupDocs.Watermark;
        using GroupDocs.Watermark.Common;
        using GroupDocs.Watermark.Watermarks;
        
        // Carica il tuo documento nella filigrana
        using (Watermarker watermarker = new Watermarker("contract.docx"))
        {
            // Imposta il testo e il carattere desiderati per la filigrana
            TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 60, FontStyle.Bold));
            
            // Scegli il colore del carattere e l'opacità, la rotazione e gli allineamenti del testo
            watermark.ForegroundColor = Color.DarkGreen;
            watermark.Opacity = 0.5;
            watermark.HorizontalAlignment = HorizontalAlignment.Center;
            watermark.VerticalAlignment = VerticalAlignment.Center;
            
            // Applicare la filigrana
            watermarker.Add(watermark);
            
            // Salva il documento risultante
            watermarker.Save("watermarked-contract.docx");
        }

        using (Metadata metadata = new Metadata("watermarked-contract.docx"))
        {
          var root = metadata.GetRootPackage<WordProcessingRootPackage>();

          // Aggiorna le proprietà dei metadati del documento
          root.DocumentProperties.Author = "Name Surname";
          root.DocumentProperties.CreatedTime = DateTime.Now;
          root.DocumentProperties.Company = "Company Name";
          root.DocumentProperties.Category = "Work materials";
          root.DocumentProperties.Keywords = "contract, watermarked";

          // Salva il documento con i metadati aggiornati
          metadata.Save("contract-final.docx");
        }        
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Redazione semplificata dei documenti"
      content: |
        <b>Scenario:</b> Un grande studio legale elabora spesso diversi documenti contenenti informazioni riservate sui clienti che devono essere oscurate prima di condividerle con terze parti o per la divulgazione pubblica. L'oscuramento manuale di queste informazioni sensibili può essere noioso, dispendioso in termini di tempo e soggetto a errori umani. Per garantire efficienza, accuratezza e conformità alle normative sulla protezione dei dati, lo studio legale cerca una soluzione automatizzata per semplificare il processo di redazione dei documenti. 
        
        <br>

        <b>Soluzione:</b>
        GroupDocs.Total automatizza il processo, attivando la redazione alla ricezione di un documento. Inoltre, le [opzioni flessibili](https://docs.groupdocs.com/redaction/net/text-redactions/) potenziano la personalizzazione consentendo di impostare regole, scegliere le modalità di oscuramento (ad esempio oscuramento, sostituzione con asterischi) e specificare sezioni o pagine specifiche per la redazione. Infine, [output intuitivo](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) genera documenti oscurati in formato PDF per una facile condivisione e revisione, mentre una maggiore sicurezza e verificabilità garantiscono l'intero il processo è documentato in termini di conformità e responsabilità. 
        <br><br>
        Questa soluzione completa consente ai professionisti legali e ad altre organizzazioni di ridurre in modo significativo i tempi e i costi di redazione, ridurre al minimo l'errore umano e gestire in modo coerente le informazioni sensibili con sicurezza.        
              
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Redaction;
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;

        // Carica il documento con dati privati ​​nel redattore 
        using (Redactor redactor = new Redactor("customer-info.docx"))
        {
          // Configura e personalizza le opzioni di redazione 
          redactor.Apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
          // Applica le revisioni e salva il risultato 
          redactor.Save();
        }

        // Carica il file oscurato per la revisione 
        using (var viewer = new Viewer("customer-info.docx"))
        {
          // Imposta il PDF come formato di visualizzazione desiderato       
          var viewOptions = new PdfViewOptions("redacted-info.pdf");

          // Salva il documento in PDF      
          viewer.View(viewOptions);
        }
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Recensioni dei prodotti GroupDocs"
# description: "Non limitarti a crederci sulla parola. Scopri cosa dicono gli altri sviluppatori sulle nostre API"

# items:
#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Servizio eccellente e prodotti eccellenti. Si sono rivelati estremamente utili e reattivi durante il processo di implementazione di GroupDocs.Viewer per .NET, non posso che consigliarli vivamente."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Dopo aver implementato e utilizzato GroupDocs.Viewer per Java nel progetto sembra funzionare molto bene. Ho testato con molti documenti e finora tutto bene. Tutto ciò che ho inserito viene visualizzato bene e ha lo stesso aspetto di un visualizzatore PDF o MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---