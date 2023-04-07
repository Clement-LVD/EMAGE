---
date: 2023-03-13
title: E-MAGE DIAGNOSTICS, ANALYSES & CONSEILS
subtitle:  BIENVENUE SUR LE SITE D'EMAGE DIAG, consulting & analyses
type: landing
# si tu te sens un peu perdu, va voir : https://connorrothschild.github.io/v2/post/animate-hugo-academic/
sections:
            
- block: markdown
  id: about
  content:
    title: <hr>
    subtitle: 
    text: <img src="/svg/clem_himself.jpg" alt="Clément" class="avatar-custom-crop" id = "myself_picture"> <h1> <strong> L'ÉQUIPE E-MAGE </strong>
          <br><br>**Clément L.**<br> 
          <div class="waviy"><span style="--i:1"> Ph.</span><span style="--i:2">D.</span></div>   
           <a href="{{< ref "/academic_resume/description_clement" >}}" class="btn btn-cligno"><i class="fa fa-graduation-cap"></i> Voir le profil universitaire</a></h1>
            <span> <a href="https://www.linkedin.com/in/cl%C3%A9ment-laverdet-503879188/"><i class="fab fa-linkedin fa-2x"></i></a> </span>
        <span> <a href="/cv_clement/cv_LVD_2023_compressed.pdf"> <i class="ai ai-cv ai-2x"></i></a> </span>
  design:
    columns: '1'  
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["25px", "0", "0px", "0"] 
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
      name: Ph.D. ❪Ψ❫
      tooltip_titre: "Thèse ：Bilans de l'influence sur Facebook et des rôles des communications et de Facebook pendant les crises <br> <a href='theses.hal.science/tel-03457426'> Voir cette thèse en ligne </a>"  
      description: "Travaux de recherches sur :<br>- La communication préventive<br>- La communication de crise<br>-Les accidents de la route<br>- Les crises politiques, catastrophes naturelles, accidents majeurs et conflits"
     

---