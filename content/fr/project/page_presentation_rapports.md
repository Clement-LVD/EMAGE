---
# Page type pourrait être a Widget Page 
# Homepage is headless, other widget pages are not.
# headless: true
# Site header

header:
  navbar:
    enable: true
content: 
  page_type: landing
active: true
date: 2023-03-13
title: null
type: landing
sections:


- block: markdown
  id: rapports-types
  design: 
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["85px", "0", "10px", "0"] 
    background:
      gradient_end: "#202020"
      gradient_start: black
      gradient_angle: -180
      text_color_light: true
  content:
      title:   Rapports-types
      subtitle: 👷 👷 Pages en construction 👷 👷 
      text: |- 
        <body>
          <div class="container-cards"> 
          <a href="/rapports-types/analyse-de-textes/" class="card-classe disabled"> 
              <strong> <center> <img src="/svg/bookshelf.svg" width="40px"  class="inverted-image">
              <br>   Analyses supervisées et non-supervisées </center> </strong>
            </a> 
          <a href="/rapports-types/fb-influence/" class="card-classe disabled"> 
              <strong> <center> <i class="fa fa-newspaper fa-2x"></i>
              <br> Analyses de presse et de littérature </center> </strong>
            </a> <div> </div>
            <a href="/rapports-types/fb-influence/" class="card-classe disabled"> 
              <strong> <center> <i class="fa fa-users fa-2x"></i>
              <br> Influence des messages </center> </strong>
            </a> 
         <a href="/rapports-types/analyses-de-communications/" class="card-classe disabled"> 
              <strong> <center>  <i class="fa fa-commenting fa-2x"></i>
              <br> Efficacité des préventions et sensibilisations </center> </strong>
            </a>  
          <a href="/rapports-types/analyse-de-textes/" class="card-classe disabled"> 
              <strong> <center> <i class="fa fa-fire-extinguisher fa-2x"></i>
              <br> Pertinence des communications de crise </center> </strong>
            </a> 
          </div>
        </body> 
        <br> 
        <br>
        <body>
          <div class="container-cards"> 
          <a href="/rapports-types/analyse-de-textes/" class="card-classe disabled"> 
              <strong> <center> <i class="fa fa-users fa-2x"></i>
              <br>  Questionnaires & expérimentations en ligne </center> </strong>
            </a> 
          <a href="/rapports-types/fb-influence/" class="card-classe disabled"> 
              <strong> <center> <img src="/svg/survey_text_writed.svg" width="40px"  >
              <br> Enquêtes et sondages de terrain </center> </strong>
            </a> 
          <a href="/rapports-types/geomarketing/" class="card-classe disabled"> 
              <strong> <center> <img src="/media/icons/globe-bw.svg" width="40px" class="inverted-image">
              <br> Géomarketing </center> </strong>
            </a> 
          <a href="/rapports-types/fb-influence/" class="card-classe disabled"> 
              <strong> <center> <i class="fa-brands fa-facebook fa-2x"></i>
              <br> Influences sur Facebook </center> </strong>
            </a> 
         <a href="/rapports-types/analyses-de-communications/" class="card-classe disabled"> 
              <strong> <center>  <i class="fa fa-brain fa-2x"></i>
              <br> Insights Facebook </center> </strong>
            </a>  
          <a href="/rapports-types/analyse-de-textes/" class="card-classe disabled"> 
              <strong> <center>  <i class="fa-brands fa-twitter fa-2x"></i>
              <br> Autres réseaux sociaux (e.g., Twitter) </center> </strong>
            </a> 
          </div>
        </body> <br> <hr> <hr>

        

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
    title: <hr> Thèmes des articles du site
    subtitle:         
        

           
---