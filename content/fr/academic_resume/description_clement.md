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
    subtitle:
    text: <h1><img src="/svg/clem_himself.jpg" width= "320px" alt="" class="float-left" id = "myself_picture">  Clément L. <br>
          <div class="waviy"><span style="--i:1"> Ph.</span><span style="--i:2">D.</span></div>   
           <a href="{{< ref "/" >}}" class="btn btn-cligno"> <span class='gray-emoji'>🧙</span> Voir la page pro E-MAGE consulting</a></h1> <br>
        <span> <a href="https://www.linkedin.com/in/cl%C3%A9ment-laverdet-503879188/"><i class="fab fa-linkedin fa-2x"></i></a> </span>
        <span> <a href="https://www.researchgate.net/profile/Clement-Laverdet/"> <i class="ai inverted-image ai-researchgate ai-2x"></i></a> </span> 
        <span> <a href="mailto:clementlvd@gmail.com"> <i class="fa fa-paper-plane fa-2x"></i></a> </span>   clementlvd@gmail.com
        <span> <a href="/cv_clement/cv_LVD_2023.pdf"> <i class="ai ai-cv ai-2x"></i></a> </span> 
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
  design:
    columns: "2"
  content:
    date_format: Jan 2006
    title: Parcours professionnel
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
          * Analyses de stratégies de communications de crise et bilan des rôles du discours journalistique (300 sources sur les 10 dernières années)
          * Conception d'enseignements, d'ateliers et de conférences
    - company: Mairie d'Igny
      location: Igny, France
      title: Chargé de recherches (Stage de recherche)
      company_logo: Logo_igny
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
      company_logo: Logo_drhat
      company_url: "https://rh-terre.defense.gouv.fr/la-drhat/organisation"
      date_start: "2014-03-01"
      date_end: "2014-07-30" 
      description: |2-

          * Évaluation de la qualité des tests de recrutements
          * Recherches autour de la performance des soldats, de la rupture de contrat, etc.
          * Rapports à la "cellule psychologie" et présentations à la cours des comptes
    - company: (2 associés principaux)
      location: Île-de-France
      title: Artisan associé
      company_logo: 
      company_url:
      date_start: "2008-07-11"
      date_end: "2016-11-30" 
      description: |2-

          * Planification et conduite de travaux de rénovations
          * Bati intérieur : électricité, plomberie, isolation, domotiques, saunas, tapisseries (tissu massif, papier peint, etc.), rénovations de murs (éventuellement traditionnelles), implantation d'escaliers, mises aux normes, etc.
          * Bâti extérieur : terrasses, allées, maçonneries, portails à gâchette électronique, luminaires classiques et connectés, etc.
---
