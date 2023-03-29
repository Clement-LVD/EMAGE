---
# Page type pourrait être a Widget Page 
# Homepage is headless, other widget pages are not.
# headless: true
# Site header

header:
  navbar:
    enable: true
sidebar_left: true
content: 
  page_type: landing
active: true
date: 2023-03-13
title: null
type: landing
sections:

           
- block: markdown
  id: about
  content:
    title: Profil universitaire
    subtitle:  (page inachevée ++ tout est à faire)
    text: <h1><img src="/svg/clem_himself.jpg" width= "320px" alt="" class="float-left" id = "myself_picture">  Clément L. <br>
          <div class="waviy"><span style="--i:1"> Ph.</span><span style="--i:2">D.</span></div>   
           <a href="{{< ref "/" >}}" class="btn btn-cligno"> <span class='gray-emoji'>🧙</span> Voir la page pro E-MAGE consulting</a></h1> <br>
        <span> <a href="https://www.linkedin.com/in/cl%C3%A9ment-laverdet-503879188/"><i class="fab fa-linkedin fa-2x"></i></a> </span>
        <span> <a href="https://www.researchgate.net/profile/Clement-Laverdet/"> <i class="ai inverted-image ai-researchgate ai-2x"></i></a> </span> 
        <span> <a href="mailto:clementlvd@gmail.com"> <i class="fa fa-paper-plane fa-2x"></i></a> </span>   clementlvd@gmail.com
        <span> <a href="/cv_clement/cv.pdf"> <i class="ai ai-cv ai-2x"></i></a> </span> 
  design:
    columns: '1'  
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["75px", "0", "0px", "0"] 
    background:
      gradient_end: '#000000'
      gradient_start: '#000000'
      text_color_light: true
      


- block: features_avec_tooltip 
  id: caracteristiques-myself
  design:
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["25px", "0", "25px", "0"]
    background:
      gradient_end: '#000000'
      gradient_start: '#000000'
      text_color_light: true
  content:
    title:
    items:
    - icon: code
      icon_pack: fa
      name: PROGRAMMATION
      description: '
      <i class="fa-brands fa-r-project fa-1x"></i> <i class="fa-brands fa-python fa-1x"></i>   R & Python
      <br><i class="fa fa-asterisk fa-1x"></i>     RegEx      
      <br> [_+_] APIs, SQL, html, etc. </h5> </span> '
    - icon: scirate
      icon_pack: ai
      name: PSYCHO-SOCIOLOGUE
      tooltip_titre: "Titre de psychologue social"
      description: '
      <i class="fa fa-user-secret fa-1x"></i>   Secret pro     
      <br><i class="fa fa-user-md" aria-hidden="true"></i>  Déontologie'
    - icon: graduation-cap
      icon_pack: fa
      name: Ph.D. en Ψ
      tooltip_titre: "Thèse ：Bilans de l'influence sur Facebook et des rôles des communications et de Facebook pendant les crises <br> <a href='theses.hal.science/tel-03457426'> Voir cette thèse en ligne </a>"  
      description: "Travaux de recherches sur :<br>- La communication préventive<br>- La communication de crise<br>-Les accidents de la route<br>- Les crises politiques, catastrophes naturelles, accidents majeurs et conflits"
    - icon: layer-group
      icon_pack: fa
      name: ANALYSES DE DONNÉES
      description: '<div><a href="/category/analyse-de-textes/" title="Vers des exemples"> Textes <i class="fa fa-file-text" fa-1x></i></a></div>
                      <div><a href="/category/enquetes/" title="Vers des exemples"> Enquêtes & questionnaires <i class="fa fa-check" fa-1x></i></a></div>
                      <div><a href="/category/cartes-et-analyses-geospatiales/" title="Vers des exemples"> Cartes <i class="fa fa-map" fa-1x></i></a></div>
                      <div><a href="/category/reseaux-de-relations/" title="Vers des exemples"> Réseaux <img src="/media/icons/network.png" width="15px" height="15" class="inverted-image"> </a></div>
                      <div><a href="/category/strategies-analyses-de-communications/" title="Vers des exemples"> Analyse des communications <i class="fa fa-commenting" fa-1x></i></a></div> '
      
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company:  **E-Mage**
      location: France
      title: CEO & data analyst
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
    - company: Université Gustave Eiffel
      location: Versailles, France
      title: Chargé d'un projet de recherche (Post-doctorat)
      company_logo: logo_UGE
      company_url: "https://www.univ-gustave-eiffel.fr/"
      date_start: "2021-10-01"
      date_end: "2023-02-01"
      description: |2-

          * Recherches sur l'accidentalité routière
          * Text-mining, analyses géoégraphiques et d'enquêtes
          * Participation à des conférences en sécurité routière
          * Rédaction d'articles scientifiques et de rapports a l'intention du ministère de l'Intérieur
    - company: Université de Nîmes
      location: Nîmes, France
      title: Chargé d'enseignement et chercheur doctorant (Contrat doctoral)
      company_logo: logo_unimes
      company_url: "https://www.unimes.fr"
      date_end: "2021-05-01"
      date_start: "2016-12-15"
      description: |2-

          * Recherches sur la communication de crise et les rôles des réseaux sociaux numériques pendant les crises
          * Analyses de stratégies de communcations de crise et bilan des rôles du discours journalistique (300 sources sur les 10 dernières années)
          * Conception d'enseignements, d'ateliers et de conférences
    - company: Mairie d'Igny
      location: Igny, France
      title: Chargé de recherches (Stage de recherche)
      company_logo: logo_igny
      company_url: "https://www.igny.fr/"
      date_end: "2015-07-01"
      date_start: "2015-01-01" 
      description: |2-

          * Conception de recherches autour de l'influence intergénérationnelle (enseignants en primaire → enfants → parents)
          * Bilan de l'efficacité d'un programme municipal de préventions en milieu scolaire
          * Réalisation de notes de services sur divers thèmes (e.g., conséquences psychologiques de l'extinction de l'éclairage public)
    - company: Direction des ressources humaines de l'Armée de terre (DRHAT)
      location: Vincennes, France
      title: Chargé d'études statistiques (CDD)
      company_logo: logo_drhat
      company_url: "https://rh-terre.defense.gouv.fr/la-drhat/organisation"
      date_start: "2014-03-01"
      date_end: "2014-07-30" 
      description: |2-

          * Évaluation de la qualité des tests de recrutements
          * Recherches autour de la performance des soldats, de la rupture de contrat, etc.
          * Rapports à la "cellule psychologie" et présentations à la cours des comptes
    title: CV
  design:
    columns: "2"
    
# - block: diplomes
#   subtitle: lequel
#   title:  gg
#   design:
#     columns: "2"
#   content:
#     date_format: Jan 2006
#     items:
#     - certificate_url: https://courses.edx.org/certificates/07dd917be3654e058599574b3a1fa40e
#       date_end: ""
#       date_start: "2021-10-10"
#       description: "Certificat en ligne délivré par Stanford Online"
#       organization: Stanford Online
#       orga_logo: "stanford_online"
#       organization_url: https://learn.stanford.edu/
#       title: Relational Databases and SQL
#       url: https://www.edx.org/course/databases-5-sql
#     - certificate_url: https://www.theses.fr/2021NIME0002
#       date_end: ""
#       date_start: "2021-05-25"
#       description: "Relations publiques et exploitation des réseaux sociaux numériques en gestion des crises : quels rôles de Facebook pour les gestionnaires français et comment exploiter ce canal de façon pertinente ?"
#       organization: ED583 (IMT Alès & UNÎMES)
#       organization_url: https://ed583.unimes.fr/
#       orga_logo: "logo ED 2022"
#       title: Docteur en psychologie
#       url: ""
#     - certificate_url: 
#       date_end: "2015-12-21"
#       date_start: "2013-07-01"
#       description: ""
#       organization: Univ. Paris Cité (ex-Paris 5)
#       orga_logo: "Logo univ Paris5"
#       organization_url: https://u-paris.fr/societes-humanites/
#       title: Titre de psycho-sociologue / Master 2
#       url: ""
# - block: collection
#   content:
#     count: 2
#     filters:
#       author: ""
#       category: ""
#       exclude_featured: false
#       exclude_future: false
#       exclude_past: false
#       folders:
#       - post
#       publication_type: ""
#       tag: ""
#     offset: 0
#     order: desc
#     subtitle: ""
#     text: ""
#     title: Quelques précisions méthodologiques
#   design:
#     columns: "2"
#     view: compact
#     background:
#       gradient_end: lightgrey 
#       gradient_start: white
#       gradient_angle: -180
#       text_color_light: false
#   id: posts
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
# - block: contact
#   content:
#     address:
#       city: 
#       country: France
#       country_code: FR
#       postcode: ""
#       # region: Île-de-France
#       street: 
#     <!--appointment_url: https://calendly.com -->
#     autolink: true
#     contact_links:
#     - icon: researchgate
#       icon_pack: ai
#       link: https://www.researchgate.net/profile/Clement-Laverdet
#       name: Mon profil researchgate
#     - icon: linkedin
#       icon_pack: fab
#       name: Mon profil Linkedin
#       link: "https://www.linkedin.com/in/cl%C3%A9ment-laverdet-503879188/"
#     directions: France et Île-de-France
#     email: clementlvd@gmail.com
#     phone: 
#     title: Contacts
#   design:
#     columns: "2"
#   id: contact
---
