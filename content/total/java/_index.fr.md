---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: fr
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
head_title: "Suite d'automatisation de documents tout-en-un pour les applications Java"
head_description: "GroupDocs.Total pour Java est une bibliothèque complète d'automatisation de documents conçue pour les développeurs Java, offrant un large éventail de fonctionnalités pour gérer divers formats de documents tels que PDF, Word, Excel, Image, HTML, Diagramme, etc."

############################# Header ############################
title: "Simplifiez l'automatisation des documents<br> dans vos projets Java"
description: "Améliorez les capacités d'automatisation des documents : convertissez, affichez, comparez, modifiez et signez facilement plus de 200 formats de fichiers."
words:
  for: "for"

actions:
  main: "Téléchargement gratuit de Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-total/"
  alt: "Licence"
  alt_link: "https://purchase.groupdocs.com/pricing/total/java"
  title: "Prêt à commencer?"
  description: "Essayez les fonctionnalités de GroupDocs.Total gratuitement ou demandez une licence"

release:
  title: "Version {0} publiée"
  notes: "Regardez ce qu'il y a de nouveau"
  downloads: "Téléchargements"
  link: "https://releases.groupdocs.com/total/java/release-notes/latest/"

code:
  title: "Fusionner et afficher des fichiers Word en Java"
  more: "Plus d'exemples"
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
    // Charger le fichier DOCX source 
    Merger merger = new Merger("sample1.docx");
    
    // Ajouter un autre fichier DOCX à fusionner
    merger.join("sample2.docx");

    // Fusionner les fichiers DOCX et enregistrer le résultat
    merger.save("merged.docx");
    
    // Charger le fichier DOCX fusionné dans la visionneuse
    try (Viewer viewer = new Viewer("merged.docx"))
    {
      // Définir les options HTML de sortie, un fichier par page
      HtmlViewOptions viewOptions =   
      HtmlViewOptions.forEmbeddedResources("page{0}.html");
          
      // Rendre DOCX en HTML avec des ressources intégrées        
      viewer.view(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Total en un coup d'œil"
  description: "Automatisez l'affichage, la conversion, la modification, la comparaison, la recherche, le filigrane et d'autres flux de travail dans les applications Java des fichiers."
  features:
    # feature loop
    - title: "Combinez la puissance de plusieurs produits GroupDocs en une solution unique et complète"
      content: | 
        Vous pouvez utiliser les fonctionnalités de différents produits GroupDocs pour créer une approche personnalisée répondant à vos besoins spécifiques.
        <br><br>
        Par exemple, vous pouvez convertir un fichier Word en PDF, puis ajouter une signature numérique. Ou remplissez les données d'un modèle de document à partir d'une base de données, ou extrayez le texte d'une image, puis traduisez-le dans une autre langue.
        <br><br>
        Les possibilités sont infinies!
          
    # feature loop
    - title: "Maîtriser la diversité des formats de fichiers"
      content: "GroupDocs.Total pour Java offre la compatibilité avec plus de 200 formats de fichiers, vous permettant ainsi de traiter des documents de tous types courants. Des formats bureautiques comme Word et Excel aux images, codes et fichiers cryptés, nous avons ce qu'il vous faut."

    # feature loop
    - title: "Prise en charge multiplateforme"
      content: "Libérez-vous des limitations de la plateforme. GroupDocs.Total offre une compatibilité multiplateforme, vous permettant de fournir des performances optimales et une disponibilité de la solution aux utilisateurs sur n'importe quel système sur lequel Java peut être installé."

############################# Platforms ############################
platforms:
  enable: true
  title: "Indépendance de la plateforme"
  description: "GroupDocs.Total pour Java prend en charge les systèmes d'exploitation, frameworks et gestionnaires de packages suivants"
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
  title: "Formats de fichiers pris en charge"
  description: |
    GroupDocs.Total pour Java prend en charge les opérations avec les [formats de fichiers](https://docs.groupdocs.com/total/java/supported-document-formats/) suivants.
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument et formats texte
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
        ### Images, graphiques et diagrammes
        * **Images rastées:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Autre        
        * **la toile:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Les archives:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Autre:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Fonctionnalités GroupDocs.Total"
  description: "Gérez, restituez et convertissez de manière complète les PDF et les documents Office."

  items:
    # feature loop
    - icon: "viewer"
      title: "Visualisation étendue des fichiers"
      content: "Visualisation complète de documents dans plus de 180 formats, notamment HTML, images et PDF."

    # feature loop
    - icon: "conversion"
      title: "Conversion de formats"
      content: "Conversion transparente entre différents formats de documents sans outils externes."

    # feature loop
    - icon: "annotation"
      title: "Annotations interactives"
      content: "Capacités d'annotation avancées pour les éléments de texte et d'image dans les documents."

    # feature loop
    - icon: "comparison"
      title: "Comparaison de contenu"
      content: "Comparaison précise des documents, mettant en évidence les différences de contenu et de style."

    # feature loop
    - icon: "signature"
      title: "Flexibilité exclusive"
      content: "Options de signature polyvalentes, notamment du texte, des images et des signatures numériques."

    # feature loop
    - icon: "assembly"
      title: "Création de documents basée sur un modèle"
      content: "Génération automatisée de documents à partir de modèles et de sources de données externes."

    # feature loop
    - icon: "metadata"
      title: "Gestion des métadonnées"
      content: "Accès et manipulation robustes des métadonnées pour un contrôle amélioré des documents."

    # feature loop
    - icon: "search"
      title: "Recherche Avancée"
      content: "Fonctionnalité de recherche puissante avec prise en charge des algorithmes flous et synonymes."

    # feature loop
    - icon: "watermark"
      title: "Contrôle du filigrane"
      content: "Gestion sans effort des filigranes de documents, offrant des fonctionnalités de personnalisation et d'extraction."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Exemples de codes"
  description: "Quelques scénarios réels d'utilisation de GroupDocs.Total pour Java"
  items:
    # code sample loop
    - title: "Sécurisez et organisez les contrats : appliquez des filigranes et gérez les métadonnées dans un fichier DOCX"
      content: |
        Protégez et organisez efficacement vos documents Word avec cet exemple de code complet. L'exemple ci-dessous vous permet de mettre en œuvre une gestion robuste du filigrane et des métadonnées dans votre flux de travail contractuel pour une sécurité et une gestion des informations améliorées. Il montre comment : <br><br>
        <b>Appliquer un filigrane personnalisé:</b> Ajoutez un filigrane « Brouillon de contrat » bien visible au document pour plus de clarté visuelle et de protection. [Personnalisez le filigrane](https://docs.groupdocs.com/watermark/java/adding-text-watermarks/) avec les options de police, de couleur, d'opacité et d'alignement. <br><br>
        <b>Améliorer les métadonnées:</b> [Modifiez facilement les métadonnées du document](https://docs.groupdocs.com/metadata/java/working-with-metadata-in-word-processing-documents/) pour inclure des détails essentiels tels que l'auteur, l'heure de création, l'entreprise, la catégorie, et des mots-clés pour une organisation et une recherche améliorées.
       
        {{< landing/code title="Java">}}
        ```java {style=abap}  
        import com.groupdocs.metadata.Metadata;
        import com.groupdocs.watermark.Watermark;
        import com.groupdocs.watermark.Watermark.Common;
        import com.groupdocs.watermark.Options.HtmlViewOptions;
        
        // Chargez votre document dans un filigrane
        Watermarker watermarker = new Watermarker("contract.docx");
        
        // Définissez le texte et la police souhaités pour le filigrane
        TextWatermark watermark = new TextWatermark("Contract Draft", new Font("Arial", 36));
          
        // Choisissez la couleur de la police et l'opacité, la rotation et les alignements du texte
        watermark.setForegroundColor(Color.getRed());                                                            
        watermark.setHorizontalAlignment(HorizontalAlignment.Center);                                            
        watermark.setVerticalAlignment(VerticalAlignment.Center);                               

        // Appliquer le filigrane
        watermarker.add(watermark);
        
        // Enregistrez le document résultant
        watermarker.save("watermarked-contract.docx");
        
        Metadata metadata = new Metadata("watermarked-contract.docx");        
        WordProcessingRootPackage root = metadata.getRootPackageGeneric();

        // Mettre à jour les propriétés des métadonnées du document
        root.getDocumentProperties().setAuthor("Name Surname");
        root.getDocumentProperties().setCreatedTime(new Date());
        root.getDocumentProperties().setCompany("Company Name");
        root.getDocumentProperties().setCategory("Work materials");
        root.getDocumentProperties().setKeywords("contract, watermarked");

        // Enregistrer le document avec les métadonnées mises à jour
        metadata.save("contract-final.docx");                
        ```
        {{< /landing/code >}}

    # code sample loop
    - title: "Rédaction rationalisée de documents"
      content: |
        <b>Scénario:</b> Un grand cabinet juridique traite fréquemment divers documents contenant des informations confidentielles sur les clients qui doivent être expurgées avant de les partager avec des tiers ou pour les rendre publiques. La suppression manuelle de ces informations sensibles peut être fastidieuse, prendre du temps et être sujette à des erreurs humaines. Pour garantir l'efficacité, l'exactitude et le respect des réglementations en matière de protection des données, le cabinet juridique recherche une solution automatisée pour rationaliser le processus de rédaction des documents. 
        
        <br>

        <b>Solution:</b>
        GroupDocs.Total automatise le processus, déclenchant la rédaction dès réception d'un document. De plus, [options flexibles](https://docs.groupdocs.com/redaction/java/text-redactions/) permettent la personnalisation en vous permettant de définir des règles, de choisir les modes de rédaction (par exemple, interdiction, remplacement par des astérisques) et de spécifier sections ou pages spécifiques à rédiger. Enfin, [sortie conviviale](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) génère des documents rédigés au format PDF pour un partage et une révision faciles, tandis qu'une sécurité et une auditabilité améliorées garantissent l'intégralité le processus est documenté aux fins de conformité et de responsabilité. 
        <br><br>
        Cette solution complète permet aux professionnels du droit et à d’autres organisations de réduire considérablement le temps et les coûts de rédaction, de minimiser les erreurs humaines et de gérer systématiquement les informations sensibles en toute confiance.        
              
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.redaction.Redaction;
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // Charger un document avec des données privées dans le rédacteur 
        Redactor redactor = new Redactor("customer-info.docx");
        
        // Configurer et personnaliser les options de rédaction 
        redactor.apply(new ExactPhraseRedaction("John Smith", new ReplacementOptions("[personal]")));
        
        // Appliquer les expurgations et enregistrer le résultat 
        redactor.save();

        // Charger le fichier rédigé pour examen 
        Viewer viewer = new Viewer("customer-info.docx");
        
        // Configurer le PDF selon le format d'affichage souhaité       
        PdfViewOptions viewOptions = new PdfViewOptions("redacted-info.pdf");

        // Enregistrer le document au format PDF      
        viewer.view(viewOptions);        
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Avis sur les produits GroupDocs"
# description: "Ne vous contentez pas de nous croire sur parole. Découvrez ce que d'autres développeurs disent de nos API"

# items:
#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Excellent service et excellents produits. Ils ont été extrêmement utiles et réactifs pendant le processus de mise en œuvre de GroupDocs.Viewer pour .NET, et ne sauraient les recommander assez."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Total"
#     content: "Après avoir implémenté et utilisé GroupDocs.Viewer pour Java dans le projet, cela semble très bien fonctionner. J'ai testé avec beaucoup de documents et jusqu'ici tout va bien. Tout ce que j'ai lancé s'affiche bien et est aussi beau que dans une visionneuse PDF ou MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---