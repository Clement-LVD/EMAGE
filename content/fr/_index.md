---
date: 2023-03-13
title: ANALYSES & ENQUÊTES
subtitle:  BIENVENUE SUR LE SITE D'EMAGE DIAG, consulting & analyses
type: landing
# si tu te sens un peu perdu, va voir : https://connorrothschild.github.io/v2/post/animate-hugo-academic/
sections:
             
- block: markdown_pleine_page
  id: home
  content:
    title: 
    subtitle: 
    text:  |- 
        <div class="gallery-container">
          <div class="gallery-item"> 
            <a href= '/categories/' title= "Voir les principales thématiques du site">  
               <div class="item-text">
            <gros-titre style= "border-style: solid; padding: 5px 12px 10px 12px"> Diagnostics <br> Analyses & Conseils </gros-titre>
            </div></a>
          </div>
            <div class="gallery-item">  
            <a href= '/page_contacts/page_contact/' title= "Vers la page de contacts">  
            <div class="item-text">
             <button class= "button button-rond">📞 📧  <br> CONTACTS <i class="fa fa-paper-plane fa-2x"> </i>   </button>
            </div></a>
          </div>
            <a href= '#methodes' title= "Voir les principales méthodes">  
            <div class="gallery-item">
            <div class="item-text">
             <button class= "button button-rond"> <center> <i class="fa fa-line-chart" ></i> ANALYSES :
             <br>   RÉVÉLEZ VOS DONNÉES   </center></button>
            </div>  </a>
          </div>
            <a href= '/category/analyse-de-textes/' title= "Voir les principales méthodes d'analyses de textes">  
            <div class="gallery-item">
            <div class="item-text">
             <button class= "button"> <center><i class="fa fa-comments"></i> <i class="fa fa-book"></i> 
             <br>  VALORISEZ VOS TEXTES <br> À LEURS JUSTES VALEURS  </center></button>
            </div>
            <div class="item-image">
             <img src='/logos/animation_logo_voronoi_optimise.gif' alt= "Logo animé" style="height: 145px;">
            </div> </a>
          </div>
          
          <div class="gallery-item">
            <a href= '/tag/communication/' title= "Voir des exemples"> 
                 <div class="item-image"> 
             </div>
            <div class="item-text">
               <button> <i class="fa fa-comment"></i> CONSEILS :
               <br> CHOISISSEZ ET OPTIMISEZ VOS MESSAGES </button> </h3-little>
              </div> </a>
          </div>
          
          <div class="gallery-item">
            <a href= "/category/enquetes/" title= "Voir des exemples"> 
                 <div class="item-image"> 
             </div>
            <div class="item-text">
               <button><i class="fa fa-search-plus" ></i> DIAGNOSTICS :
               <br> BÉNÉFICIEZ D'UNE ENQUÊTE SUR MESURE </button> </h3-little>
              </div> </a>
          </div>
            
          <div class="gallery-item">
          <a href= "/category/strategies-analyses-de-communications/">
                 <div class="item-image">
                 </div>
            <div class="item-text">
              <button> <center> <i class="fa fa-braille" ></i> MESUREZ : </center> ➾  VOTRE INFLUENCE <br>➾ ET CELLE DE VOS CONCURRENTS </button>
              </div> </a>
          </div> 
          
          <div class="gallery-item">
            <a href= '/post/exemple_implantation_business_maps/exemple_utilisation_voronoi/'> 
            <div class="item-image">
              <img src='banieres/baniere_map_voronoi_superettes_parisiennes.jpg' style="height: 175px; display: table; " alt= "Supérettes et supermarchés parisiens et zones d'influences (Voronoï)" >
              </div>
              <div class="item-text">
              <h3-little> <center> <i class="fa fa-map-pin" ></i> IDENTIFIEZ : </center> ➾ L'EMPLACEMENT IDÉAL POUR VOTRE IMPLANTATION  <br> ➾ et les zones d'influences des concurrents </h3-little> 
            </div> </a> </div> 
          </div>
  design:
    columns: '1'  
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["0px", "0", "0px", "0"] 
    background:
      # gradient_end: black
      # gradient_start: black
      # gradient_angle: -180
      text_color_light: true
      

- block: features_avec_tooltip 
  id: services
  design:
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["21px", "0", "0px", "0"]
    background:
      gradient_end: '#000000'
      gradient_start: '#05050F'
      gradient_angle: 180
      text_color_light: true
  content:
    title: <h4> Nos services </h4>
    items:
    - icon: layer-group
      icon_pack: fa
      name: Analyses de données
      description: '<div><a href="/category/analyse-de-textes/" title="Vers des exemples"> Textes <i class="fa fa-file-text" fa-1x></i></a></div>
                      <div><a href="/category/enquetes/" title="Vers des exemples"> Enquêtes & questionnaires <i class="fa fa-check" fa-1x></i></a></div>
                      <div><a href="/category/cartes-et-analyses-geospatiales/" title="Vers des exemples"> Cartes <i class="fa fa-map" fa-1x></i></a></div>
                      <div><a href="/category/reseaux-de-relations/" title="Vers des exemples"> Réseaux <img src="/media/icons/network.png" width="15px" height="15" class="inverted-image"> </a></div>
                      <div><a href="/category/strategies-analyses-de-communications/" title="Vers des exemples"> Analyse des communications <i class="fa fa-commenting" fa-1x></i></a></div> '
                      
    - icon: open-data #description: 85%
      icon_pack: ai
      name: Présentation des résultats
      description: 'Rendus programmés et vérifiés : <br>- Figures & tables   <i class="fa fa-file-image" fa-2x></i> <i class="fa fa-table" aria-hidden="true"></i>
      <br> - Cartes                  <img src="/media/icons/globe-bw.svg" width="33px" height="55"  > 
      <br>- Réseaux & diagrammes <img src="/media/icons/network.png" width="25px" height="30" class="inverted-image"> 
      <br> - Analyses statistiques <i class="fa fa-bar-chart" fa-2x></i> <i class="fa fa-pie-chart" ></i>'
    - icon: handshake-angle
      icon_pack: fa 
      name: Conseils
      description: "<b>- Calculs d'implantation et géomarketing<br>- Conseils théoriques pour améliorer l'efficacité de préventions <br> - Mesures d'influences en ligne <br> - Identification des stratégies éditoriales et des types de commentaires  <br>  ... </b>"
      # tooltip_titre: '<a href="theses.hal.science/tel-03457426">Voir ma thèse sur la communication de crise et le maintien de réputation</a>'
    - icon: scirate
      icon_pack: ai
      name: Enquêtes et recherches 
      # tooltip_titre: ↓<br>↓<br>↓<br>↓<br>↓<br>↓<br>↓<br>↓<br>↓<br>↓<br>→ 
      description: "Reprise ou conception d'enquêtes : <br>✅<b>Programmation <br>&<br>✅ Méthodes de sciences sociales <br>       - Psychosociologue   <i class='fa fa-user-secret fa-1x'></i> <br> - Docteur en psychologie <i class='fa fa-graduation-cap'></i> </b>"
    - icon: envelopes-bulk
      icon_pack: fa
      name: Bilans
      description: "<b> Analyses et rapports programmés : <br>
             <i class='fa fa-check-square'></i> Vérifiables              <i class='fa fa-file' ></i>🔍→💾<br>
             <i class='fa fa-check-square'></i> Actualisables           💾⃕◌⃕◌⃕<i class='fa fa-refresh'></i> <br>
             <i class='fa fa-check-square'></i> Réutilisables        🌰⃕🌰⃕🌰⃕<i class='fa fa-server'></i> </b>"
    - icon: signs-post
      icon_pack: fa
      name:   Aide à la décision
      description: "<b>
            - Conception et organisation d'enquêtes </b> <br> 
             (p. ex. mesure de l'efficacité d'une campagne) <br> <b>
            - Rapports et analyses </b> <br> (p. ex. calculs d'implantation / géomarketing, <br> bilan de l'influence sur Facebook)"

- block: features_avec_tooltip_v_avancee
  id: methodes
  design:
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["5px", "0", "25px", "0"]
    background:
      gradient_end: '#000000'
      gradient_start: '#000000'
      text_color_light: true 
  content:
    title:  <hr><hr> <h4> Analyses de données </h4>
    items:
    - icon: "book_stylised.svg"
      icon_pack: custom
      icon_class: "inverted-image"
      name: <a href="/category/analyse-de-textes/" title="Vers des explications plus détaillées"> Text-mining </a>
      description: |-
            <i class="fa fa-code" ></i> Méthodes programmées, supervisées & non-supervisées
             <br><i class="fa fa-file" ></i> <i class="fa fa-book" ></i>  ''Petits'' et gros ensembles de textes
            <br><i class="fa fa-newspaper" ></i> <i class="fa-brands fa-facebook fa-1x"></i> Discours journalistique ou politique
            <br> <img src="/svg/book-with-marker.svg" width="17px" height="28px"  class="inverted-image"> <img src="/svg/bookshelf.svg" width="22px" height="28px"  class="inverted-image">   Analyses de littérature              
            <br><i class="fa fa-users fa-1x"></i><i class="fa fa-commenting fa-1x"></i><img src="/svg/survey_text_writed.svg" width="32px" height="55px" > Langage naturel                      
            <br> (e.g., réponses à des questionnaires ou entretiens, commentaires d'usagers, posts Facebook et tweets)<br>...
      tooltip_titre: "Cliquez pour voir des exemples"
    - icon: globe-bw.svg
      icon_pack: custom  
      name:  <a href="/category/cartes-et-analyses-geospatiales/" title="Vers des explications plus détaillées"> Cartes et analyses géospatiales</a> 
      tooltip_titre: "Cliquez pour voir des exemples"
      description: '
      <i class="fa fa-leaf"  fa-1x></i> Leaflet.js 
      <br> <i class="fa fa-database" fa-1x></i>  OpenStreetMap Data (API)
      <br> <i class="fa fa-map"  fa-1x></i>     Cartes topographiques
      <br> <i class="fa fa-sitemap" ></i>                 Géomarketing'
    - name:   <a href="/category/reseaux-de-relations/" title="Vers des explications plus détaillées"> Réseaux de relations</a>
      icon: "network.png"
      icon_pack: custom
      icon_class: "inverted-image" 
      tooltip_titre: "Cliquez pour voir des exemples"  
      description: |-
            <i class="fa fa-database fa-1x"></i> Réseaux de citations, mentions, partages
            <br><i class="fa-brands fa-facebook fa-1x"></i> <i class="fa-brands fa-twitter"></i> Réseaux sociaux numériques 
            <br><i class="ai ai-pubpeer ai-2x"></i> Réseaux de concepts (p. ex. coexistences de concepts)
            <br><i class="ai ai-dataverse ai-1x"></i> Réseaux de communications, d'agents, d'organisations, etc.  
    - name:   <a href="/category/enquetes/" title="Vers des explications plus détaillées"> Questionnaires</a>
      icon: list-alt
      icon_pack: fa
      icon_class: 
      tooltip_titre: "Cliquez pour voir des exemples"  
      description: |-
            <i class="fa fa-check-square fa-1x"></i> Enquêtes et sondages (site statique)
            <br> <i class="fa fa-desktop"></i> Expériences en ligne (site dynamique)
            <br><i class="fa fa-pen"></i> Approche qualitative = analyse de textes !
            <br><i class="fa fa-pie-chart"></i> Approche quantitative et expérimentale   
    - name:   <a href="/category/strategies-analyses-de-communications/" title="Vers des explications plus détaillées"> Analyses de communications</a>
      icon: commenting
      icon_pack: fa
      icon_class: 
      tooltip_titre: "Cliquez pour voir des exemples"  
      description: |-
            <br> <i class="fa fa-compass"></i> Confrontations (com' effectives vs. théories)
            <br><i class="fa fa-comments"></i> Récupération et analyses des messages
            <br><i class="fa fa-newspaper"></i> Revue de presse et de littérature
            <br><i class="fa fa-line-chart"></i> Analyse de l'influence sur Facebook
            <br> <i class="fa fa-info-circle" ></i> Conseils en arguments / formulations de communications 📚 : ↓
             <br>  ✅ - persuasives <i class="fa fa-compress"></i>  
             <br>  ✅ - de crise  <i class="fa fa-ambulance" ></i>
             <br>  ✅ - d'influences de l'enfant sur le parent <i class="fa fa-child fa-1x"></i>
             

    - name:  Bases de données
      icon: database
      icon_pack: fa
      icon_class: 
      tooltip_titre:
      description: |-
           -  API <i class="fa-brands fa-facebook"></i> / <i class="fa-brands fa-twitter" ></i> / <i class="fa-brands fa-google" ></i> / etc.
           <br><i class="ai ai-dataverse ai-1x"></i>  SQL, SQLite, etc.
            <br> (.*) RegEx
     

 
- block: markdown
  id: autres-methodes
  design:
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["50px", "0px", "35px", "0"]
    background:
      gradient_end: black
      gradient_start: black
      text_color_light: true
  content:
    title: 
    subtitle:
    text:     <br>   
        <div class="waviy">
          <span style='--i:1'> <i class='fa fa-plus-square' ></i></span>
          <span style="--i:2"><i class="fa fa-plus-circle"></i></span>
          <span style="--i:3"><i class="fa fa-plus-square" ></i></i></span>
          <span style="--i:4"><i class="fa fa-plus-circle" ></i></span>
          <span style="--i:5"><i class="fa fa-plus-square" ></i></span></div>    
          <br>  
              <div class='wrapper'>
                <div class='carousel'>
                  <div class='carousel__item'>
                    <div class='carousel__item-head'>
                      <i class='fa fa-search inverted-image'></i>
                    </div>
                    <div class='carousel__item-body'>
                      <p class='title'> Observations </p>
                      <p> + *reporting* spécialisé </p>
                    </div>
                  </div>
                  <div class='carousel__item'>
                    <div class='carousel__item-head'>
                      <i class='fa fa-comments inverted-image'></i> 
                    </div>
                    <div class='carousel__item-body'>
                      <p class='title'>ENTRETIENS</p>
                      <p> + traitements supervisés par lexiques</p>
                    </div>
                  </div>
                  <div class='carousel__item'>
                    <div class='carousel__item-head'>
                       <i class='fa fa-gears inverted-image'></i> 
                    </div>
                    <div class='carousel__item-body'>
                      <p class='title'>DONNÉES DE CAPTEURS HUMAINS</p>
                      <p> + Capteurs domotiques / électroniques </p>
                    </div>
                  </div>
                  <div class='carousel__item'>
                    <div class='carousel__item-head'>
                      <i class='fa fa-database inverted-image'></i> 
                    </div>
                    <div class='carousel__item-body'>
                      <p class='title'>BASES DE DONNÉES</p>
                      <p>SQL, data.table, Rdata, etc.</p>
                    </div>
                  </div>
                  <div class='carousel__item'>
                    <div class='carousel__item-head'>
                      <i class='fa fa-commenting inverted-image'></i> 
                    </div>
                    <div class='carousel__item-body'>
                      <p class='title'> ANALYSES DE COMMUNICATIONS</p>
                      <p> P. ex. pertinence de préventions ou de communications de crise</p>
                    </div>
                  </div>
                  <div class='carousel__item'>
                    <div class='carousel__item-head'>
                      🎥
                    </div>
                    <div class='carousel__item-body'>
                      <p class='title'>Analyses de photos et vidéos</p>
                      <p> P. ex. reconnaissance automatisée des visages</p>
                    </div>
                  </div>
                  <div class='carousel__item'>
                    <div class='carousel__item-head'>
                      <i class='fa fa-brain inverted-image'></i>
                    </div>
                    <div class='carousel__item-body'>
                      <p class='title'> Théories de la communication</p>
                      <p>Com' persuasive, com' de crise, etc.</p>
                    </div>
                  </div>
                  <div class='carousel__item'>
                    <div class='carousel__item-head'>
                      <i class='fa fa-diagram-project inverted-image'></i>
                    </div>
                    <div class='carousel__item-body'>
                      <p class='title'>Mesure d'influences</p>
                      <p>Sur Facebook, par questionnaires interposés, etc.</p>
                    </div>
                  </div>
                  <div class='carousel__item'>
                    <div class='carousel__item-head'>
                      <i class='ai ai-scirate ai-1x inverted-image'></i>
                    </div>
                    <div class='carousel__item-body'>
                      <p class='title'> Programmation et analyses de données</p>
                      <p> Méthodes de psycho-sociologie</p>
                    </div>
                  </div>
                </div>
              </div>  
 
        
- block: portfolio
  id: projects
  content:
    title: <hr> <hr> Quelques cas d'études
    subtitle: 
    buttons:
    - name: Tous les thèmes
      tag: '*'
    - name: Textes & meta-analysis
      tag: text-analysis
      category: Analyse de textes
    - name: Facebook
      tag: Facebook
    - name: Communication
      tag: Communication
    - name: Cartes et analyses géographiques
      tag: Cartes
    default_button_index: 0
    filters:
      folders:
      - post
  design: 
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["30px", "0", "10px", "0"] 
    background:
      gradient_end: black
      gradient_start: black
      text_color_light: true
    columns: "1"
    # flip_alt_rows: true
    # view: project #ou masonry est très bien
    view: masonry
    show_project_dates: false



- block: category_cloud
  content:
    title: '<aaa style= "color: white;"> <hr> <hr> <br> Thématique du site </aaa>'
  id: categories-cloud
  design:
    columns: "1" 
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["15px", "0", "40px", "0"]
    background:
      gradient_end: "#202020"
      gradient_start: '#000000'
      gradient_angle: -180
      text_color_light: false

- block: tag_cloud
  id: tag_cloud
  design: 
    spacing:
      padding: ["10px", "0", "1px", "0"]
    columns: "2"
    background:
      gradient_end: lightgrey 
      gradient_start: "#202020"
      gradient_angle: -180
      text_color_light: false     
  content:
    title: <hr> <br> Sous-thématiques ("tags") du site <hr>
    subtitle: 
                
          
---
<!-- Inclure Bootstrap JS   -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script> 
              <script>
              $(function () {
                  $([data-toggle="tooltip"]).tooltip()  
              }) 
              </script> 
