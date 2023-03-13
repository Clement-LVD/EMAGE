---
date: 2023-03-13
title: ENQUÊTES & ANALYSES
subtitle:  BIENVENUE SUR LE SITE D'EMAGE DIAG, consulting & analyses
type: landing
# va voir =>
# https://connorrothschild.github.io/v2/post/animate-hugo-academic/
sections:

# Your landing page sections - add as many different content blocks as you like
- block: markdown
  id: home
  content:
    title: <h1> BIENVENUE SUR LE SITE D'<strong>E-MAGE</strong> </h1>
    subtitle:   <h2> <strong> CONSULTING, ENQUÊTES & ANALYSES </strong> </h2>
      
        <br> <a href="{{< ref "#contact" >}}" class="btn btn-cligno"><h3-little><i class="fa fa-paper-plane"></i> Contacts</h3-little> </a>  <br>
        <br><a href="#services">
        ╭─<i class="fa fa-circle-down"></i>─╮</a>
  # text: 
    columns: '1'     
  design:
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["95px", "0", "0px", "0"]
    background:
      text_color_light: true 
    #   gradient_end: '#000000'
    #   gradient_start: black
      # The gradient angle from 0-360 degrees
      # gradient_angle: 10


- block: features_avec_tooltip 
  id: services
  design:
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["5px", "0", "0px", "0"]
    background:
      gradient_end: '#000000'
      gradient_start: '#000000'
      text_color_light: true
  content:
    title: <strong> SERVICES </strong>
    items:
    # ICI TU A TRAFFIQUé cette fonction pour réagir à certaines variables et les envoyer en tooltipbox
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
      description: "- Conseils & bilans en communication"
      # tooltip_titre: '<a href="theses.hal.science/tel-03457426">Voir ma thèse sur la communication de crise et le maintien de réputation</a>'
    - icon: scirate
      icon_pack: ai
      name: Enquêtes et recherches 
      # tooltip_titre: ↓<br>↓<br>↓<br>↓<br>↓<br>↓<br>↓<br>↓<br>↓<br>↓<br>→ 
      description: "       - Psychosociologue   <i class='fa fa-user-secret fa-1x'></i> <br> - Docteur en psychologie <i class='fa fa-graduation-cap'></i>"
    - icon: envelopes-bulk
      icon_pack: fa
      name: Bilans
      description: "Analyses et rapports programmés : <br>
             <i class='fa fa-check-square'></i> Vérifiables              <i class='fa fa-file' ></i>🔍→💾<br>
             <i class='fa fa-check-square'></i> Actualisables           💾⃕◌⃕◌⃕<i class='fa fa-refresh'></i> <br>
             <i class='fa fa-check-square'></i> Réutilisables        🌰⃕🌰⃕🌰⃕<i class='fa fa-server'></i>"
    - icon: signs-post
      icon_pack: fa
      name:   Aide à la décision
      description: "
            - Rapports et analyses <br>
            - Conception et organisation d'enquêtes<br> 
             (p. ex. mesure de l'efficacité d'une campagne)"


- block: features_avec_tooltip_v_avancee
  id: methodes
  design:
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["5px", "0", "0px", "0"]
    background:
      gradient_end: '#000000'
      gradient_start: '#000000'
      text_color_light: true 
  content:
    title: <hr/>Méthodes
    items:
    - icon: "book_stylised.svg"
      icon_pack: custom
      icon_class: "inverted-image"
      name: <a href="/category/analyse-de-textes/" title="Vers des explications plus détaillées"> Analyses de textes </a>
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
      <i class="fa fa-leaf" aria-hidden="true" fa-1x></i> Leaflet.js 
      <br> <i class="fa fa-database" aria-hidden="true" fa-1x></i>  OpenStreetMap Data (API)
      <br> <i class="fa fa-map" aria-hidden="true" fa-1x></i>     Cartes topographiques'
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
     
 
 
- block: markdown
  id: autres-methodes
  design:
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["20px", "0px", "5px", "0"]
    background:
      gradient_end: black
      gradient_start: black
      text_color_light: true
  content:
    title: 
    subtitle:
    text:  </div></div> <center> <br> 
            <div class="waviy">
          <span style="--i:1"> <i class="fa fa-plus-square" ></i></span>
          <span style="--i:2"><i class="fa fa-plus-circle"></i></span>
          <span style="--i:3"><i class="fa fa-plus-square" ></i></i></span>
          <span style="--i:4"><i class="fa fa-plus-circle" ></i></span>
          <span style="--i:5"><i class="fa fa-plus-square" ></i></span> </center>
          <h3> <div id=flip> 
          <div><div> <i class="fa fa-check-square"></i>     QUESTIONNAIRES</div></div>
          <div><div> <i class="fa fa-comments"></i>     ENTRETIENS</div></div> 
           
           <div><div> <i class="fa fa-search"></i>     OBSERVATIONS</div></div>
           
           <div><div> <i class="fa fa-gears"></i>     DONNÉES DE CAPTEURS</div></div>
           
           <div><div> <i class="fa fa-users"></i>     EXPÉRIMENTATIONS</div></div>
           
           <div><div> <i class="fa fa-search"></i>     MESURES DE LA PERTINENCE DES COMMUNICATIONS</div></div>
           
            <div><div> <i class="fa fa-database"></i>     BASES DE DONNÉES</div></div></h3>
           
            
           <h3><br> ET D'AUTRES MÉTHODES...</h3></div></div>  </div>


 # <hr>
    # - name: Analyses supervisées (textes & meta-analysis)
    #   tag: Analyse thématique supervisée
    # - name: Analyses non-supervisées (textes & meta-analysis) 
    #   tag: Analyse thématique non-supervisée
      
- block: portfolio
  id: projects
  content:
    title: Quelques cas d'études
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
      padding: ["10px", "0", "10px", "0"] 
    background:
      gradient_end: black
      gradient_start: black
      text_color_light: true
    columns: "1"
    # flip_alt_rows: true
    # view: project #ou masonry est très bien
    view: masonry
    show_project_dates: false

- block: markdown
  id: contact
  design: 
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["10px", "0", "10px", "0"] 
    background:
      gradient_end: #ededed
      gradient_start: white
      text_color_light: false
  content:
      title: Contactez E-MAGE consulting 
      text:    '<h1>  <div> 📧 {{< global_param "email" >}}</div>
      
      <br><i class="fa fa-paper-plane" ></i>   Formulaire de contact </h1>
      
                 
                 <h3-little> <form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Votre prénom et nom : <input type="text" name="name" /></label>
  </p>
  <p>
    <label>Votre email : <input type="email" name="email" /></label>
  </p> 
    <label>  <div> Vos besoins (vous pouvez indiquer plusieurs réponses<br> en maintenant "ctrl") : </div> <select name="role[]" multiple>
      <option value="analyse">   Analyse de données   </option>
      <option value="conseil">   Conseils</option>
      <option value="autre">   Autre</option>
    </select> </label> 
  <p>
    <label>Message : <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Envoi</button>
  </p> </h3-little>
</form> <br>
                  '
              
- block: markdown
  id: about
  content:
    title: <strong> L'ÉQUIPE E-MAGE </strong>
    subtitle: 
    text: <img src="clem_himself.jpg" alt="Clément" class="avatar-square" id = "myself_picture"> <h1>**Clément L.**<br>
          <div class="waviy"><span style="--i:1"> Ph.</span><span style="--i:2">D.</span></div>   
          <a href="{{< ref "/academic_resume/description_clement.md" >}}" class="btn btn-cligno"><i class="fa fa-graduation-cap"></i> Voir le profil universitaire</a>
        <a href="https://www.linkedin.com/in/cl%C3%A9ment-laverdet-503879188/"><i class="fab fa-linkedin"></i></a></h1>
    
  contact_links:
    - icon: "graduation-cap"
      icon_pack: fas
      link: 'academic_resume/description_clement/'
    - icon: linkedin
      icon_pack: fab
      label: Profil Linkedin
      link: "https://www.linkedin.com/in/cl%C3%A9ment-laverdet-503879188/"
    - icon: cv
      icon_pack: ai
      link: uploads/resume.pdf
    - icon: researchgate
      icon_pack: ai
      link: https://www.researchgate.net/profile/Clement-Laverdet
      name: Mon profil researchgate
    - icon: linkedin
      icon_pack: fab
      name: Mon profil Linkedin
      link: "https://www.linkedin.com/in/cl%C3%A9ment-laverdet-503879188/"
  design:
    columns: '1'  
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["15px", "0", "0px", "0"] 
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
     
 
  
- block: category_cloud
  content:
    subtitle: 
  id: categories-cloud
  design:
    columns: "1" 
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["55px", "0", "30px", "0"]
    background:
      gradient_end: '#000000'
      gradient_start: '#000000'
      text_color_light: false

- block: tag_cloud
  id: tag_cloud
  design:
    columns: "2"     
  content:
    title: Sous-thématiques ("tags") du site
    subtitle: 
                
          
---
<!-- Inclure Bootstrap JS   -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script> 
              <script>
              $(function () {
                  $([data-toggle="tooltip"]).tooltip()  
              }) 
              </script> 
