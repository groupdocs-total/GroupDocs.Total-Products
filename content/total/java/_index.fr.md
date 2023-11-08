---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Total"
product_tag: "total"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "API Java pour afficher, convertir, annoter, signer, automatiser et rechercher des formats de fichiers"
head_description: "Utilisez les versions Java des API de manipulation de documents GroupDocs pour les intégrer à vos propres plateformes et applications Java"

############################# Header ############################
title: "Bibliothèques d'automatisation de documents Java"
description: "API pour afficher, exporter, annoter, comparer, signer, automatiser et rechercher des documents à partir de n'importe quelle application Java."
button:
    enable: true

############################# SubMenu ############################
submenu:
  enable: true
  
  left:
      img_alt: "GroupDocs.Total for Java"
      image: "/border/groupdocs-total-java.svg"
      product: "GroupDocs.Total"
      platform: "Java"

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
          - link: "https://purchase.groupdocs.com/pricing/total/java"
            text: "Pricing"

  right:
      link_download: "https://releases.groupdocs.com/total"
      link_learn: "https://docs.groupdocs.com/total/java/"
      link_buy: "https://purchase.groupdocs.com"

############################# Aperçu ############################
overview:
    enable: true
    content: |
      GroupDocs.Total pour Java est une compilation de toutes les API Java proposées par GroupDocs. Nous le compilons quotidiennement pour nous assurer qu'il contient les versions les plus récentes de chacune de nos API Java.
        
      Avec GroupDocs.Total pour Java, les développeurs peuvent utiliser toutes nos API avec une seule licence. Cependant, vous pouvez également commander n'importe quelle API individuelle. Les API que nous proposons incluent

############################# Des produits ############################
products:
    enable: true
    title: "Des produits"
    description: "GroupDocs.Total pour Java inclut les API de manipulation de documents suivantes pour Java :"

    product:
        # product loop
        - image: "/border/groupdocs-viewer-java.svg"
          img_alt: "GroupDocs.Viewer for Java"
          name: "GroupDocs.Viewer for Java"
          content: |
            Une puissante API de visionneuse de documents qui vous permet d'afficher plus de 50 formats de documents dans vos applications Java. Le visualiseur peut fonctionner de deux manières : en rastérisant les documents ou en les convertissant en une combinaison de SVG, HTML et CSS. Les deux méthodes offrent un rendu haute fidélité.
              
            Les formats de fichiers pris en charge incluent les documents Microsoft Office, Visio, Project et Outlook, les fichiers PDF, AutoCAD, les fichiers image (TIFF, JPG, BMP, GIF, TIFF, etc.) et plus encore.
          link: "/viewer/java/"

        # product loop
        - image: "/border/groupdocs-annotation-java.svg"
          img_alt: "GroupDocs.Annotation for Java"
          name: "GroupDocs.Annotation for Java"
          content: |
            Une API flexible qui permet aux utilisateurs finaux d'annoter des documents Microsoft Office, PDF et autres dans vos applications Java. L'API est livrée avec un ensemble complet d'outils de balisage, qui permettent aux utilisateurs finaux de surligner, de barrer et de commenter du texte et des images.
          link: "/annotation/java/"

          # product loop
        - image: "/border/groupdocs-conversion-java.svg"
          img_alt: "GroupDocs.Conversion for Java"
          name: "GroupDocs.Conversion for Java"
          content: |
            Une API de classe avancée qui vous permet de convertir dans les deux sens entre plus de 50 formats de documents à partir de vos applications Java. L'API prend en charge tous les formats de documents Microsoft Office ainsi que les formats PDF, HTML et les formats de fichiers image courants (TIFF, JPEG, GIF, PNG, BMP). Les documents peuvent être convertis un par un à la volée ou ajoutés à une file d'attente de conversion.
          link: "/conversion/java/"

          # product loop
        - image: "/border/groupdocs-comparison-java.svg"
          img_alt: "GroupDocs.Comparison for Java"
          name: "GroupDocs.Comparison for Java"
          content: |
            Cette API permet aux utilisateurs finaux de trouver rapidement et facilement les différences entre deux révisions d'un document. Il compare les documents téléchargés et affiche les différences entre eux via une interface utilisateur de vue diff. Les différences sont mises en évidence à l'aide de la vue redline - similaire à la fonction de suivi des modifications de Microsoft Word.
          link: "/comparison/java/"

          # product loop
        - image: "/border/groupdocs-signature-java.svg"
          img_alt: "GroupDocs.Signature for Java"
          name: "GroupDocs.Signature for Java"
          content: |
            Avec cette API, vous pouvez améliorer de manière transparente vos applications avec la capacité de signature électronique. Vos utilisateurs peuvent alors faire signer électroniquement des documents en utilisant uniquement un navigateur Web. Des pistes d'audit détaillées, un cryptage SSL 256 bits et d'autres fonctionnalités de sécurité avancées garantissent que les documents signés restent confidentiels et sécurisés, tandis qu'une interface utilisateur de type assistant rend le processus de signature rapide et facile.
          link: "/signature/java/"

          # product loop
        - image: "/border/groupdocs-assembly-java.svg"
          img_alt: "GroupDocs.Assembly for Java"
          name: "GroupDocs.Assembly for Java"
          content: |
            Le moteur GroupDocs.Assembly pour Java est un ensemble d'API d'automatisation de documents et de génération de rapports conçus pour créer des documents personnalisés à partir de modèles. Le moteur de génération de rapports Java assemble intelligemment les données fournies avec le document modèle défini et génère un document de sortie basé sur la source de données dans le même format que le format du document modèle.
          link: "/assembly/java/"

          # product loop
        - image: "/border/groupdocs-metadata-java.svg"
          img_alt: "GroupDocs.Metadata for Java"
          name: "GroupDocs.Metadata for Java"
          content: |
            GroupDocs.Metadata for Java est une API de gestion des métadonnées de document conçue pour toutes les opérations de métadonnées de base telles que l'affichage, l'ajout, la modification et la suppression de métadonnées. Les API de métadonnées prennent en charge un certain nombre de formats de fichiers. Vous pouvez charger le document d'entrée et rendre ses métadonnées accessibles à l'utilisateur pour les opérations de métadonnées.
          link: "/metadata/java/"

          # product loop
        - image: "/border/groupdocs-search-java.svg"
          img_alt: "GroupDocs.Search for Java"
          name: "GroupDocs.Search for Java"
          content: |
            GroupDocs.Search pour Java - API de recherche de documents pour des requêtes avancées avec des fonctionnalités d'indexation. Utilisez l'API dans les applications Java pour les documents, y compris Word Excel PowerPoint et PDF pour la récupération de texte intégral et bien plus encore.
          link: "/search/java/"

          # product loop
        - image: "/border/groupdocs-parser-java.svg"
          img_alt: "GroupDocs.Parser for Java"
          name: "GroupDocs.Parser for Java"
          content: |
            GroupDocs.Parser pour Java - Un extracteur de texte extensible et une API d'analyse pour lire ou analyser le contenu du document et les propriétés des métadonnées à partir de différents formats de fichiers. Cela fonctionne simplement en obtenant le fichier en entrée, puis en récupérant le texte brut ou formaté du fichier d'entrée avec les propriétés des métadonnées.
          link: "/parser/java/"

          # product loop
        - image: "/border/groupdocs-watermark-java.svg"
          img_alt: "GroupDocs.Watermark for Java"
          name: "GroupDocs.Watermark for Java"
          content: |
            GroupDocs.Watermark pour Java est une API de filigrane de document pour ajouter, rechercher et supprimer le filigrane de plusieurs formats de fichiers. L'API prend en charge les types de filigrane texte et image. Le filigrane ajouté par n'importe quel logiciel tiers peut facilement être recherché et supprimé par cette API alors qu'il est difficile de supprimer le filigrane ajouté à l'aide de cette API par des outils tiers.
          link: "/watermark/java/"

          # product loop
        - image: "/border/groupdocs-editor-java.svg"
          img_alt: "GroupDocs.Editor for Java"
          name: "GroupDocs.Editor for Java"
          content: |
            GroupDocs.Editor pour Java est une API légère pour éditer plusieurs formats de documents sous forme de HTML. L'API de l'éditeur peut à la fois traduire le document source en HTML et enregistrer le code HTML modifié au format du document source.
          link: "/editor/java/"

          # product loop
        - image: "/border/groupdocs-merger-java.svg"
          img_alt: "GroupDocs.Merger for Java"
          name: "GroupDocs.Merger for Java"
          content: |
            GroupDocs.Merger pour Java est une API de fusion et de jonction de documents permettant de combiner et d'organiser plusieurs fichiers en un seul, ainsi que de diviser, supprimer ou réorganiser des pages dans un document au format pris en charge.
          link: "/merger/java/"

          # product loop
        - image: "/border/groupdocs-redaction-java.svg"
          img_alt: "GroupDocs.Redaction for Java"
          name: "GroupDocs.Redaction for Java"
          content: |
            API de rédaction de documents Java pour protéger ou supprimer toute information confidentielle des documents Word, Excel, PowerPoint, Images et PDF à l'aide de types de rédaction de texte, de métadonnées et d'annotations.
          link: "/redaction/java/"

############################# Caractéristiques ############################
features:
    enable: true
    title: "Advanced API Caractéristiques"

    feature:
      # feature loop
      - icon: "fas fa-file"
        content: "Représentation HTML, Image et PDF des documents"

      # feature loop
      - icon: "fas fa-water"
        content: "Filigrane : ajoutez du texte en filigrane à toutes les pages et images de la sortie"

      # feature loop
      - icon: "fas fa-pen"
        content: "Annotations Word et PDF natives"
      
      # feature loop
      - icon: "fas fa-tools"
        content: "Ensemble complet d'outils d'annotation"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Annotez les e-mails, les documents HTML et les images"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Conversion de documents rapide et précise"

      # feature loop
      - icon: "fas fa-key"
        content: "Compare le contenu des documents, les fichiers protégés par mot de passe, les styles de police et les filigranes"

      # feature loop
      - icon: "fas fa-save"
        content: "Enregistrer le résumé des différences au format DOC ou DOCX"

      # feature loop
      - icon: "fas fa-upload"
        content: "Télécharger, taper ou dessiner des signatures"

      # feature loop
      - icon: "fas fa-file-signature"
        content: "Vérifications de signature numérique pour tous les types"

      # feature loop
      - icon: "fas fa-server"
        content: "Générer des documents à partir de plusieurs sources de données"

      # feature loop
      - icon: "fas fa-eraser"
        content: "Analysez et supprimez les métadonnées masquées dans plusieurs formats de documents"

      # feature loop
      - icon: "fas fa-search-plus"
        content: "Rechercher et comparer les métadonnées"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Exporter les métadonnées vers Excel/CSV"

      # feature loop
      - icon: "fas fa-lock"
        content: "Extraction de texte à partir de fichiers protégés par mot de passe"

      # feature loop
      - icon: "fas fa-search-minus"
        content: "Rechercher et supprimer le filigrane texte/image"

      # feature loop
      - icon: "fas fa-file-image"
        content: "Modifier plusieurs formats de documents"

      # feature loop
      - icon: "fas fa-file-alt"
        content: "Combinez plusieurs fichiers en un seul"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: false
    title: "GroupDocs.Total pour Java propose des solutions individuelles pour"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for Java"
          image: "/border/groupdocs-viewer-java.svg"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"
        
        # solution loop
        - img_alt: "GroupDocs.Annotation for Java"
          image: "/border/groupdocs-annotation-java.svg"
          product: "GroupDocs.Annotation"
          platform: "Java"
          link: "/annotation/java/"

        # solution loop
        - img_alt: "GroupDocs.Conversion for Java"
          image: "/border/groupdocs-conversion-java.svg"
          product: "GroupDocs.Conversion"
          platform: "Java"
          link: "/conversion/java/"

        # solution loop
        - img_alt: "GroupDocs.Comparison for Java"
          image: "/border/groupdocs-comparison-java.svg"
          product: "GroupDocs.Comparison"
          platform: "Java"
          link: "/comparison/java/"

        # solution loop
        - img_alt: "GroupDocs.Signature for Java"
          image: "/border/groupdocs-signature-java.svg"
          product: "GroupDocs.Signature"
          platform: "Java"
          link: "/signature/java/"

        # solution loop
        - img_alt: "GroupDocs.Assembly for Java"
          image: "/border/groupdocs-assembly-java.svg"
          product: "GroupDocs.Assembly"
          platform: "Java"
          link: "/assembly/java/"

        # solution loop
        - img_alt: "GroupDocs.Metadata for Java"
          image: "/border/groupdocs-metadata-java.svg"
          product: "GroupDocs.Metadata"
          platform: "Java"
          link: "/metadata/java/"

        # solution loop
        - img_alt: "GroupDocs.Search for Java"
          image: "/border/groupdocs-search-java.svg"
          product: "GroupDocs.Search"
          platform: "Java"
          link: "/search/java/"

        # solution loop
        - img_alt: "GroupDocs.Parser for Java"
          image: "/border/groupdocs-parser-java.svg"
          product: "GroupDocs.Parser"
          platform: "Java"
          link: "/parser/java/"

        # solution loop
        - img_alt: "GroupDocs.Watermark for Java"
          image: "/border/groupdocs-watermark-java.svg"
          product: "GroupDocs.Watermark"
          platform: "Java"
          link: "/watermark/java/"

        # solution loop
        - img_alt: "GroupDocs.Editor for Java"
          image: "/border/groupdocs-editor-java.svg"
          product: "GroupDocs.Editor"
          platform: "Java"
          link: "/editor/java/"

        # solution loop
        - img_alt: "GroupDocs.Merger for Java"
          image: "/border/groupdocs-merger-java.svg"
          product: "GroupDocs.Merger"
          platform: "Java"
          link: "/merger/java/"

        # solution loop
        - img_alt: "GroupDocs.Redaction for Java"
          image: "/border/groupdocs-redaction-java.svg"
          product: "GroupDocs.Redaction"
          platform: "Java"
          link: "/redaction/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---