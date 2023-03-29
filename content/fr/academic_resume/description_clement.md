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
    title: CV
  design:
    columns: "2"
---
