---
# Page type pourrait être a Widget Page 
# Homepage is headless, other widget pages are not.
# headless: true
# Site header

header:
  navbar:
    enable: false
content: 
  page_type: widget_page
active: true
date: "2023-03-15"
title: null
type: landing
sections:
- block: hero
  content:
     # on ajoutera plus tard des bouttons en pur html
    # cta:
    #   label: → **Visiter le site d'E-MAGE (page pro)**
    #   url: '#about'
    #   
    # cta_alt:
    #   label: "**@→ Écrire un mail à Clément**"
    #   url: mailto:clementlvd@gmail.com
    #   

    # image:
    #   filename: skills_diagram.svg
    text: |-
      
      <br><h1>
      <a href="{{< ref "/" >}}" class="btn btn-shine2">Voir la page pro : E-MAGE Consulting</a> </h1>
      <!--Custom spacing-->
      <div class="mb-3"></div>
     
      
      <!--GitHub Button JS-->
      <!-- <script async defer src="https://buttons.github.io/buttons.js"></script> -->
      
      <!-- ICI LE TITRE DE LA PAGE !! -->
    title: <br>Clément L.<br><br>Résumé académique
      <!-- voir les couleurs sur => https://www.html.am/html-codes/color/color-code-chart.cfm -->
      <!-- toujours 4 espaces pour les commentaires 
      et ils peuvent faire deux lignes !  -->
      <!-- a l'origine eux ils proposent le gradient_end à '#1976d2' et le start a '#004ba0' comme couleurs -->  

  
           <!--
      ci-dessous le username !
      BREF => le "username" ne renvoie en fait PAS au dossier qui s'apelle "admin" 
      (lequel dossier admin spécifie des thèmes pour le serveur)
      non, en réalité il renvoie à une putain de page / dossier dans le repertoire content "authors", 
      dans laquelle il y a un dossier "admin"
      
      -->
  
              <!-- ICI ON EST EN TRAIN DE CR2ER UNE CLASSE "features" 
              on utilise deux packs d'icones => fa et ai (https://jpswalsh.github.io/academicons/)-->
- block: features
  design:
    background:
      gradient_end: '#000000'
      gradient_start: '#000000'
      text_color_light: true
  content:
    title: Skills
    items:
    - icon: r-project #description: 85%
      icon_pack: fab
      name: R
    - icon: python #description: 70%
      icon_pack: fab
      name: Python
    - icon: asterisk #description: 80%
      icon_pack: fab
      name: RegEx
    - icon: dataverse #description: 25%
      icon_pack: ai
      name: SQL
    - icon: code #description: 25%
      icon_pack: fa
      name: html
    - icon: plus #description: 25%
      icon_pack: fab
      name: and more
      
- block: features
  design:
    background:
      gradient_end: '#000000'
      gradient_start: '#000000'
      text_color_light: true
  content:
    title: Skills
    items:      
    - icon: pubpeer #description: 80%
      icon_pack: ai
      name: Relationships network
    - icon: chart-line #description: 100%
      icon_pack: fa
      name: Statistics
    - icon: file-text #description: 90%
      icon_pack: fa
      name: Text-analysis
    - icon: scirate #description: 100%
      icon_pack: ai
      name: Psychosociology
    - icon: th-list #description: 85%
      icon_pack: fa
      name: Survey design & analysis
    - icon: open-data
      icon_pack: ai
      name: Présenter les résultats
      
- block: features
  design:
    background:
      gradient_end: '#000000'
      gradient_start: '#000000'
      text_color_light: true
  content: 
    items:
    - icon: grav
      icon_pack: fab
      name: Automie & rigueur
      
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: . **E-Mage**
        <!-- et le logo il faut aller le chercher dans "asset/media/icons/brands" (wtf)
        et il ne prends que du svg -->
      company_logo: wizard_hat
      company_url: ""
      date_end: ""
      date_start: "2023-03-01"
      description: |2-

          * Gérer la société, estimer les besoins des clients
          * Conception d'enquêtes et de recherches
          * Analyses de données (e.g., text-mining, *insights* Facebook)
          * Rédaction de bilans et de rapports à partir des données
      location: France
      title: CEO & data analyst
    - company: Gustave Eiffel University
      company_logo: logo_UGE
      company_url: ""
      date_end: "2021-10-01"
      date_start: "2023-02-01"
      description: |2-

          * Recherches sur l'accidentalité routière
          * Text-mining, analyses géoégraphiques et d'enquêtes
          * Participation à des conférences et des articles en sécurité routière, à la rédaction e rapports au ministère de l'Intérieur, etc.
      location: Versailles, France
      title: Chargé d'un projet de recherche (Post-doctorat)
    title: Experience
  design:
    columns: "2"
- block: diplomes
  content:
    date_format: Jan 2006
    items:
    - certificate_url: www.theses.fr/2021NIME0002
      date_end: ""
      date_start: "2021-05-25"
      description: "Relations publiques et exploitation des réseaux sociaux numériques en gestion des crises : quels rôles de Facebook pour les gestionnaires français et comment exploiter ce canal de façon pertinente ?"
      organization: ED583 (IMT Alès & UNÎMES)
      organization_url: https://ed583.unimes.fr/
      orga_logo: "logo_ED_2022"
      title: Docteur en psychologie
      url: ""
    - certificate_url: https://courses.edx.org/certificates/07dd917be3654e058599574b3a1fa40e
      date_end: ""
      date_start: "2021-10-10"
      description: "Certificat en ligne délivré par Stanford Online"
      organization: Stanford Online
      orga_logo: "stanford_online"
      organization_url: https://learn.stanford.edu/
      title: Relational Databases and SQL
      url: https://www.edx.org/course/databases-5-sql
    - certificate_url: 
      date_end: "2020-12-21"
      date_start: "2020-07-01"
      description: ""
      organization: Univ. Paris Cité (ex-Paris 5)
      orga_logo: "Logo_univ_Paris5"
      organization_url: https://u-paris.fr/societes-humanites/
      title: Titre de psycho-sociologue / Master 2
      url: ""
    subtitle: null
    title: Accomplish&shy;ments
  design:
    columns: "2"
- block: collection
  content:
    count: 2
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Publications
  design:
    columns: "2"
    view: compact
  id: posts
# - block: markdown
#   content:
#     subtitle: ""
#     text: '{{< gallery album="demo" >}}'
#     title: Gallery
#   design:
#     columns: "1"
# - block: collection
#   content:
#     filters:
#       featured_only: true
#       folders:
#       - publication
#     title: Featured Publications
#   design:
#     columns: "2"
#     view: card
#   id: featured
# - block: collection
#   content:
#     filters:
#       exclude_featured: true
#       folders:
#       - publication
#     text: |-
#       {{% callout note %}}
#       Quickly discover relevant content by [filtering publications](./publication/).
#       {{% /callout %}}
#     title: Recent Publications
#   design:
#     columns: "2"
#     view: citation
# - block: collection
#   content:
#     filters:
#       folders:
#       - event
#     title: Recent & Upcoming Talks
#   design:
#     columns: "2"
#     view: compact
#   id: talks
- block: contact
  content:
    address:
      city: 
      country: France
      country_code: FR
      postcode: ""
      # region: Île-de-France
      street: 
    <!--appointment_url: https://calendly.com -->
    autolink: true
    contact_links:
    - icon: researchgate
      icon_pack: ai
      link: https://www.researchgate.net/profile/Clement-Laverdet
      name: Mon profil researchgate
    - icon: linkedin
      icon_pack: fab
      name: Mon profil Linkedin
      link: "https://www.linkedin.com/in/cl%C3%A9ment-laverdet-503879188/"
    directions: France et Île-de-France
    email: clementlvd@gmail.com
    phone: 
    title: Contacts
  design:
    columns: "2"
  id: contact
---
