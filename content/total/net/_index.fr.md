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
head_title: "API C# .NET pour afficher, convertir, annoter, signer, automatiser, filigraner, rédiger et rechercher des formats de fichiers"
head_description: "Bibliothèques et API de manipulation de documents GroupDocs .NET. Utilisez n'importe quelle API dans l'application .NET pour la génération, la manipulation ou la conversion de plus de 50 documents."

############################# Header ############################
title: ".API d'automatisation de documents NET"
description: "API pour afficher, exporter, annoter, comparer, signer, automatiser et rechercher des documents dans vos applications .NET."
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
            text: "Aperçu"

          # button loop
          - link: "#products"
            text: "Des produits"

          # button loop
          - link: "#features"
            text: "Caractéristiques"

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

############################# Aperçu ############################
overview:
    enable: true
    content: "GroupDocs.Total pour .NET est une compilation de toutes les API .NET proposées par GroupDocs. Nous le compilons quotidiennement pour nous assurer qu'il contient les versions les plus récentes de chacune de nos API de manipulation de documents .NET.
    <br><br>Avec GroupDocs.Total pour les développeurs .NET, vous pouvez utiliser toutes nos API avec une seule licence. Cependant, vous pouvez également commander n'importe quelle API individuelle. "

############################# Des produits ############################
products:
    enable: true
    title: "Des produits"
    description: "GroupDocs.Total pour .NET inclut les API de manipulation de documents suivantes pour .NET :"

    product:
        # product loop
        - image: "/border/groupdocs-viewer-net.svg"
          img_alt: "GroupDocs.Viewer for .NET"
          name: "GroupDocs.Viewer for .NET"
          content: "Puissante API de visionneuse de documents pour rendre, visualiser et afficher des documents de plus de 50 formats de fichiers. Rendu complet du document entier, rendu efficace d'un document partiel ou rendu spécifique d'une plage de pages/cellules. Rendre une couche de document individuelle, avec ou sans annotations et commentaires pour les formats de fichiers pris en charge."
          link: "/viewer/net/"

        # product loop
        - image: "/border/groupdocs-annotation-net.svg"
          img_alt: "GroupDocs.Annotation for .NET"
          name: "GroupDocs.Annotation for .NET"
          content: "API de gestion des annotations pour créer et manipuler différents types d'annotations, telles que la zone, le texte, la polyligne, le point, le soulignement, etc.. Il vous présente un ensemble complet d'outils de balisage pour surligner, barrer, baliser et commenter du texte et des images.. Imprimez les documents annotés ou exportez-les au format PDF avec les annotations."
          link: "/annotation/net/"

          # product loop
        - image: "/border/groupdocs-conversion-net.svg"
          img_alt: "GroupDocs.Conversion for .NET"
          name: "GroupDocs.Conversion for .NET"
          content: "API complète de conversion de documents pour configurer et convertir des documents parmi plus de 50 formats de fichiers. Avec des fonctionnalités telles que le rendu de l'en-tête d'e-mail lors de la conversion à partir d'un e-mail, la définition de répertoires de polices personnalisées, la configuration et le placement d'un filigrane et une méthode de conversion avancée, etc.. cette API est bien plus qu'un simple outil de conversion de fichiers."
          link: "/conversion/net/"

          # product loop
        - image: "/border/groupdocs-comparison-net.svg"
          img_alt: "GroupDocs.Comparison for .NET"
          name: "GroupDocs.Comparison for .NET"
          content: "API de vérification des différences de documents pour comparer à la fois le contenu et les styles de texte. Choisissez le niveau de détail pour le processus de comparaison. Appliquer ou rejeter les modifications après l'analyse des différences. Récupérer des documents via un fichier ou un flux. Spécifiez le séparateur de mots et la couleur de la police pour styliser le texte comparé. Comparer les fichiers protégés par mot de passe."
          link: "/comparison/net/"

          # product loop
        - image: "/border/groupdocs-signature-net.svg"
          img_alt: "GroupDocs.Signature for .NET"
          name: "GroupDocs.Signature for .NET"
          content: "API de manipulation de signature électronique pour signer des documents numériques de différents formats. Récupérer tous les certificats enregistrés présents dans le système. Appliquez une signature de nombreux types, tels que texte, code-barres, image, code QR, etc.. Effectuez une recherche simple et avancée pour localiser les signatures souhaitées. Configurez les propriétés de la signature, telles que l'ombre, l'alignement, les dimensions et bien plus encore."
          link: "/signature/net/"

          # product loop
        - image: "/border/groupdocs-assembly-net.svg"
          img_alt: "GroupDocs.Assembly for .NET"
          name: "GroupDocs.Assembly for .NET"
          content: "API d'automatisation de documents et de génération de rapports en créant et en personnalisant des modèles pour les formats pris en charge. Manipulez les données à l'aide de formules et d'opérations de données séquentielles, formatez les chaînes dans la syntaxe du modèle, définissez le formatage ordinal, cardinal, alphabétique et numérique. Définir les variables ; insérer dynamiquement du contenu dans des rapports avec une mise en forme conditionnelle, etc."
          link: "/assembly/net/"

          # product loop
        - image: "/border/groupdocs-metadata-net.svg"
          img_alt: "GroupDocs.Metadata for .NET"
          name: "GroupDocs.Metadata for .NET"
          content: "API d'accès et de manipulation des métadonnées pour lire, modifier, remplacer et supprimer les métadonnées de divers types de documents. Comparez les propriétés des métadonnées de deux fichiers pour identifier leurs similitudes et leurs différences. Exporter les métadonnées vers Excel, CSV ou DataSet. Détecter le type MIME d'un fichier ou d'un flux de fichiers spécifique. Supprimer les informations de localisation des photos. Réduisez la consommation de mémoire des fichiers."
          link: "/metadata/net/"

          # product loop
        - image: "/border/groupdocs-search-net.svg"
          img_alt: "GroupDocs.Search for .NET"
          name: "GroupDocs.Search for .NET"
          content: "API de recherche de documents et de texte qui offre des fonctionnalités de recherche de base à avancées, telles que la création et la fusion de plusieurs index, la recherche via Simple, Boolean, Fuzzy, Expression régulière (Regex) et d'autres types de requêtes. Appliquez une recherche rapide, fiable et intelligente aux fichiers, documents et e-mails. Recherche basée sur les termes homophoniques, les synonymes, la plage de dates, les jokers et la sensibilité à la casse."
          link: "/search/net/"

          # product loop
        - image: "/border/groupdocs-parser-net.svg"
          img_alt: "GroupDocs.Parser for .NET"
          name: "GroupDocs.Parser for .NET"
          content: "API d'extraction de texte qui prend en charge l'extraction de texte et de métadonnées bruts, formatés et structurés à partir de formats de fichiers pris en charge. Analyser les documents protégés par mot de passe. Choisissez entre une extraction de texte rapide ou standard. Le formateur Markdown & HTML prend en charge le formatage de la police, des hyperliens, des en-têtes, des listes et des tableaux. Obtenez les données du conteneur de messagerie (Exchange Web Server, POP3, IMAP)."
          link: "/parser/net/"

          # product loop
        - image: "/border/groupdocs-watermark-net.svg"
          img_alt: "GroupDocs.Watermark for .NET"
          name: "GroupDocs.Watermark for .NET"
          content: "Application de filigrane numérique et API de manipulation pour appliquer de nouveaux filigranes, rechercher et supprimer les filigranes existants des documents aux formats pris en charge. Verrouiller les filigranes pour restreindre l'édition. Remplacer les filigranes existants. Protéger le filigrane de texte en utilisant des caractères illisibles dans les présentations. Modifier les propriétés de la forme telles que le texte alternatif, l'angle de rotation, etc.. en présentation."
          link: "/watermark/net/"

          # product loop
        - image: "/border/groupdocs-editor-net.svg"
          img_alt: "GroupDocs.Editor for .NET"
          name: "GroupDocs.Editor for .NET"
          content: "API de l'éditeur de documents pour charger un document au format de fichier pris en charge, le convertir en HTML, pousser le HTML vers un éditeur HTML externe, enregistrer le HTML dans son format de fichier d'origine. Récupérer séparément les ressources jointes à n'importe quel document. Obtenir le contenu CSS du document HTML. Récupérer le DOM HTML à partir du contenu de la chaîne et convertir en document. Appliquer la sécurité au document résultant."
          link: "/editor/net/"

          # product loop
        - image: "/border/groupdocs-merger-net.svg"
          img_alt: "GroupDocs.Merger for .NET"
          name: "GroupDocs.Merger for .NET"
          content: "API de fusion et de séparation de documents pour combiner, diviser, réorganiser, échanger, rogner et supprimer une seule page ou une collection de pages, de diapositives ou de diagrammes. Définir ou supprimer la protection par mot de passe pour les formats de fichiers connus et inconnus. Assemblage ou fractionnement d'un seul ou d'un lot de documents. Découpez le document en supprimant des pages, des diapositives ou des diagrammes spécifiques."
          link: "/merger/net/"

          # product loop
        - image: "/border/groupdocs-redaction-net.svg"
          img_alt: "GroupDocs.Redaction for .NET"
          name: "GroupDocs.Redaction for .NET"
          content: "API de rédaction et de nettoyage de documents pour rédiger, supprimer ou masquer les informations classifiées, le contenu et les métadonnées des documents, des feuilles de calcul, des fichiers PDF et des diapositives."
          link: "/redaction/net/"

          # product loop
        - image: "/border/groupdocs-classification-net.svg"
          img_alt: "GroupDocs.Classification for .NET"
          name: "GroupDocs.Classification for .NET"
          content: "API de classification de texte et de documents bruts pour les applications .NET. Classez les formats de contenu et de document tels que Microsoft Office Word, PDF, OpenDocument, RTF et Text à l'aide de plusieurs taxonomies, notamment les documents et IAB-2. Personnalisez facilement les résultats classifiés à l'aide d'un ensemble de fonctionnalités avancées selon vos besoins."
          link: "/classification/net/"

############################# Caractéristiques ############################
features:
    enable: true
    title: "Advanced API Caractéristiques"

    feature:
      # feature loop
      - icon: "fas fa-eye"
        content: "Visualisez n'importe quel format de document dans son format d'origine ou au format HTML, Images ou PDF"

      # feature loop
      - icon: "fas fa-file"
        content: "Annotez tous les documents PDF, DOCX, XLSX et PPTX"

      # feature loop
      - icon: "fas fa-save"
        content: "Enregistrez des annotations dans différents objets tels que des fichiers JSON, des bases de données ou fusionnez avec le fichier d'origine"
      
      # feature loop
      - icon: "fas fa-file-export"
        content: "Exporter les annotations vers un fichier PDF ou Word séparé"

      # feature loop
      - icon: "fas fa-bolt"
        content: "API de conversion à la volée la plus rapide"

      # feature loop
      - icon: "fas fa-clone"
        content: "Conversion par lots de plusieurs fichiers"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Compare le contenu pour les différences de mots et de paragraphes"

      # feature loop
      - icon: "fas fa-file-contract"
        content: "Résumé des différences séparées lors de l'utilisation de l'API de comparaison"

      # feature loop
      - icon: "fas fa-signature"
        content: "Propriétés de signature multiples"

      # feature loop
      - icon: "fas fa-file-signature"
        content: "Configuration de la signature sur des pages arbitraires telles que premier, dernier, pair, impair, etc."

      # feature loop
      - icon: "fas fa-server"
        content: "Générer des documents multiformats à partir de plusieurs sources de données"

      # feature loop
      - icon: "fas fa-key"
        content: "Opérations de métadonnées intégrées et personnalisées sous la forme de paires clé/valeur"

      # feature loop
      - icon: "fas fa-file-download"
        content: "Exporter les métadonnées jointes avec les formats de fichiers pris en charge"

      # feature loop
      - icon: "fab fa-searchengin"
        content: "Plusieurs méthodes de recherche de base et avancées"

      # feature loop
      - icon: "fas fa-search"
        content: "Recherche floue et synonyme"

      # feature loop
      - icon: "fas fa-search-minus"
        content: "Rechercher et supprimer le filigrane texte/image"

      # feature loop
      - icon: "fas fa-file-image"
        content: "Ajouter un filigrane aux images dans un document"

      # feature loop
      - icon: "fas fa-file-alt"
        content: "Extraire du texte structuré et surligné"
      
      # feature loop
      - icon: "fas fa-file-archive"
        content: "Récupère du texte à partir de conteneurs contenant d'autres fichiers tels que des archives zip"

      # feature loop
      - icon: "fas fa-file-invoice"
        content: "Transformation directe et inverse de documents"

      # feature loop
      - icon: "fas fa-edit"
        content: "Modifier plusieurs formats de documents"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: false
    title: "GroupDocs.Total pour .NET propose des solutions individuelles pour"

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
