---
date: "2023-03-27T00:00:00Z"
# external_link: false
image:
  filename: mountain.png
  caption: 
  focal_point: Smart
summary: Un petit résumé.
tags:
- Cartes
- Geomarketing
- Calculs d'implantation
categories: 
- Cartes et analyses geospatiales
title: Implantation et calculs de zones d'influences des concurrents
gallery_item:
- album: voroinoi_business_paris
  image: A_cliniques_et_hopitaux_a_paris.jpg
  caption: Cliniques et hopitaux parisiens (Data ODbL - CC-BY-SA 2.0)
- album: voroinoi_business_paris
  image: B_enseignes_bricolage_et_materiaux.jpg
  caption: Points de vente parisiens de 9 enseignes de vente de matériaux (Data ODbL - CC-BY-SA 2.0)
- album: voroinoi_business_paris
  image: C_map_voronoi_superettes_parisiennes.jpg
  caption: Supérettes et supermarchés parisiens de 9 groupes concurrents (Data ODbL - CC-BY-SA 2.0)
- album: voroinoi_business_paris
  image: D_restaurants_a_paris.jpg
  caption: Carte des restaurants parisiens (Data ODbL - CC-BY-SA 2.0)
---
<h3>
            <maxilarge-tooltip data-toggle="tooltip" data-trigger= "hover click" data-html=true title="
            - Rapports actualisables et capitalisables <br>
            - Conception d'enquêtes<br> 
            - Conseils en communication de crise et en communication persuasive (prévention, etc.)"><i class="fa fa-map-signs" aria-hidden="true" fa-3x></i><br>  <a href="/category/analyse-de-textes/" title="Vers des exemples"> Aide à la décision </a> </maxilarge-tooltip>  </h3> 

<span data-toggle="tooltip" title="Ma tooltip">Mon texte</span>
<span data-toggle="tooltip" title="Ma deuxième tooltip">Mon second texte</span>

<!-- Inclure Bootstrap JS à la fin de la page -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

<!-- Activer les tooltips -->
<script>
$(function () {
  $('[data-toggle="tooltip"]').tooltip()
})
</script>


<span class="tooltip-content" data-tippy-content="Contenu de la tooltip ici">Aide à la décision</span> 

<script src="https://unpkg.com/@popperjs/core@2.9.3"></script>
<script src="https://unpkg.com/tippy.js@6.3.2/dist/tippy-bundle.umd.min.js"></script>   
<script>
  tippy(".tooltip-content", {
    allowHTML: true,
    arrow: true,
    delay: [0, 600], // ms
  });
</script>

<button id="my-button">Cliquez ici</button>

<!-- JavaScript -->
<script src="https://unpkg.com/@popperjs/core@2.9.3"></script>
<script src="https://unpkg.com/tippy.js@6.3.2/dist/tippy-bundle.umd.min.js"></script>

<!-- La projection de données géographiques permet de calculer plusieurs statistiques descriptives, plus ou moins évoluées. Par exemple, il est possible de calculer des "zones d'influences" autour des commerces de proximité, et de calculer la densité d'occupation associée à divers territoires. Cela concerne en premier lieu les entrepreneursqui visent à atteindre les clients situés autour d'eux, comme les restaurateurs - itinérants ou non, les salons de coiffure et les enseignes de grandes distributions ou de bricolage par exemple. Prenons le cas de l'implantation d'un restaurant, d'un magasin de bricolage ou d'une supérette dans Paris, En général, les différents secteurs accessibles à l'entrepreneur sont déjà plus ou moins saturés géographiquement.

voir les [cartes ci-dessous](#figure-superette-paris)

<figure>  {{< figure src="map_voronoi_superettes_parisiennes.jpg" id="superette-paris" >}}
  <figcaption> Cartes des supérettes et supermarchés parisiens de 9 groupes concurrents, et "zones d'influences" en Voronoï (data ODbL, CC-BY-SA 2.0).</figcaption>
</figure>
-->
<!-- un bouton : on utilise une librairie javascript pour le produire ^^ 
il faut aller voir la doc de  https://atomiks.github.io/tippyjs/v6/getting-started/-->
<!-- HTML button -->



<script>
  tippy('#my-button', {
    content: ' CONTENT  !!',
    allowHTML: false, arrow: true,
    delay: [0, 600] // ms
  });
</script>


<div id="my-text2">Cliquez ici</div> 

<script>
  tippy('#my-text2', {
    content: '<strong>Bolded <span style="background: aqua;">CONTENT EN BLEU !</span></strong>',
    allowHTML: true, arrow: false,
    delay: [0, 600] // ms
  });
</script>
Les statistiques spatiales servent par exemple à *monitorer* la concurrence dans différentes zones, et à définir une zone d'implantation idéale pour un commerce ou un service:

- pour un service public en fonction de la position des autres services publics;
- pour une enseigne de vente de matériaux;
- une supérette;
- un restaurant, etc.

<figure>  <figcaption> ↓ A. Cliniques et hopitaux parisiens ; <br>↓  B. Points de vente de 9 enseignes de vente de matériaux ; <br>↓ C. Supérettes et supermarchés parisiens de 9 groupes concurrents ; <br>D. Restaurants à Paris (Data ODbL - CC-BY-SA 2.0)</figcaption> {{< gallery album="voroinoi_business_paris" >}}
   <figcaption> Les "zones d'influences" (A, B et C) sont calculées en Voronoï</figcaption>
</figure>

Pour un entrepreneur qui voudrait implanter un salon de coiffure, cela peut être intéressant d'identifier les zones les moins "densément" fournies. De même pour le coiffeur itinérant, qui voudrait identifier des zones propices à l'installation de son camion.


DES TESTS ENSuITE

 <h-changetext > test </h-changetext >

ON VA VOIR 5 MANIERES DIFFERENTES D'AFFICHER UN SVG

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
fill="{{ .fill }}" width="90px" height="50px" viewBox="0 0 32 32" aria-label="External Link">
<path d="M8 3C7.449219 3 7 3.449219 7 4L7 30C7 30.554688 7.449219 31 8 31L13 31C13.554688 31 14 30.554688 14 30L14 4C14 3.449219 13.554688 3 13 3 Z M 17 3C16.449219 3 16 3.449219 16 4L16 30C16 30.554688 16.449219 31 17 31L22 31C22.554688 31 23 30.554688 23 30L23 4C23 3.449219 22.554688 3 22 3 Z M 9.5 7L11.5 7C12.054688 7 12.5 7.449219 12.5 8C12.5 8.550781 12.054688 9 11.5 9L9.5 9C8.945313 9 8.5 8.550781 8.5 8C8.5 7.449219 8.945313 7 9.5 7 Z M 18.5 7L20.5 7C21.054688 7 21.5 7.449219 21.5 8C21.5 8.550781 21.054688 9 20.5 9L18.5 9C17.945313 9 17.5 8.550781 17.5 8C17.5 7.449219 17.945313 7 18.5 7 Z M 37.59375 8.4375L32.75 9.59375C32.492188 9.65625 32.265625 9.804688 32.125 10.03125C32.066406 10.125 32.023438 10.238281 32 10.34375L32 10C32 9.449219 31.554688 9 31 9L26 9C25.449219 9 25 9.449219 25 10L25 30C25 30.554688 25.449219 31 26 31L31 31C31.554688 31 32 30.554688 32 30L32 10.78125L36.8125 30.25C36.921875 30.710938 37.328125 31.03125 37.78125 31.03125C37.855469 31.03125 37.921875 31.015625 38 31L42.875 29.84375C43.132813 29.78125 43.359375 29.632813 43.5 29.40625C43.640625 29.179688 43.6875 28.914063 43.625 28.65625L38.8125 9.1875C38.683594 8.648438 38.128906 8.308594 37.59375 8.4375 Z M 36.96875 12.78125C37.351563 12.847656 37.6875 13.128906 37.78125 13.53125C37.90625 14.070313 37.566406 14.625 37.03125 14.75L36.0625 14.96875C35.984375 14.988281 35.917969 15 35.84375 15C35.390625 15 34.953125 14.679688 34.84375 14.21875C34.71875 13.679688 35.058594 13.15625 35.59375 13.03125L36.5625 12.8125C36.695313 12.78125 36.839844 12.757813 36.96875 12.78125 Z M 28 13L29 13C29.554688 13 30 13.449219 30 14C30 14.550781 29.554688 15 29 15L28 15C27.445313 15 27 14.550781 27 14C27 13.449219 27.445313 13 28 13 Z M 39.53125 24.46875C40.066406 24.347656 40.621094 24.679688 40.75 25.21875C40.875 25.753906 40.539063 26.28125 40 26.40625L39.03125 26.65625C38.953125 26.675781 38.855469 26.6875 38.78125 26.6875C38.328125 26.6875 37.921875 26.367188 37.8125 25.90625C37.6875 25.371094 38.023438 24.8125 38.5625 24.6875 Z M 9.5 25L11.5 25C12.054688 25 12.5 25.449219 12.5 26C12.5 26.550781 12.054688 27 11.5 27L9.5 27C8.945313 27 8.5 26.550781 8.5 26C8.5 25.449219 8.945313 25 9.5 25 Z M 18.5 25L20.5 25C21.054688 25 21.5 25.449219 21.5 26C21.5 26.550781 21.054688 27 20.5 27L18.5 27C17.945313 27 17.5 26.550781 17.5 26C17.5 25.449219 17.945313 25 18.5 25 Z M 28 25L29 25C29.554688 25 30 25.445313 30 26C30 26.554688 29.554688 27 29 27L28 27C27.445313 27 27 26.554688 27 26C27 25.445313 27.445313 25 28 25 Z M 3 32C2.449219 32 2 32.445313 2 33L2 36C2 36.554688 2.449219 37 3 37L47 37C47.554688 37 48 36.554688 48 36L48 33C48 32.445313 47.554688 32 47 32 Z M 6 39L6 44.5C6 45.878906 7.121094 47 8.5 47C9.878906 47 11 45.878906 11 44.5L11 39 Z M 39 39L39 44.5C39 45.878906 40.121094 47 41.5 47C42.878906 47 44 45.878906 44 44.5L44 39Z"></path>
</svg>


  <img src="/svg/network.png" width="32px" height="32px"  >
  
   <img src="/svg/bookshelf.svg" width="32px" height="32px"  >
  
{{< svg  file="/svg/survey_icon.svg" width="50px" height="50px" >}} 

0 =  {{< svg  file="static/svg/book-with-marker.svg" width="50px" height="50px" >}} //

1 = {{< svg  file="static/svg/book_stylised.svg" width="50px" height="50px" >}} //

A = <img src="/svg/book-with-marker.svg" width="32px" height="55px" >

B=  <img src="/svg/book_stylised.svg" width="32px" height="32px" > 

C = <embed type="image" src="/svg/network.png" width="32" height="32" /> 


2.
<embed type="image/svg+xml" src="/svg/book_stylised.svg" width="32" height="32" />

3.
<span class="fa-stack fa-lg">  
    <img src="/svg/book_stylised.svg" width="32px" height="32px" alt="Book icon"> 
</span>

4.
<object type="image/svg+xml" data="/svg/book_stylised.svg" width="32px" height="32px">
      <img src="/fallback-image.png" alt="Image non disponible">
    </object> 

  <img src="/svg/book_stylised.svg" width="32px" height="32px"  >

5.
<span>
   <svg xmlns="http://www.w3.org/2000/svg" fill="#000000" width="800px" height="100px" viewBox="0 0 32 32" version="1.1">
<title>book</title>
<path d="M30.728 18.612l-2.112-0.697 0.050 0.052-11.683 4.24-11.184-11.823-2.745-0.906c-1.386 0.981-1.541 3.774-0.61 4.746l13.805 14.19 14.602-5.228c-1.33-0.727-2.409-2.796-0.123-4.573zM15.474 22.441l-11.504-11.928h0.344l11.453 11.693-0.294 0.235zM16.353 27.987c0 0-1.592-1.86 0.471-4.334l12.501-4.527c0 0-1.438 2.469 0.245 3.927l-13.217 4.935zM5.799 10.384l-0.382-0.404 11.654-4.138 11.544 12.073 2.112 0.697c-0.010 0.008-0.020 0.016-0.030 0.024l0.246-0.088-13.623-14.125-14.212 5.072 2.69 0.888z"/>
</svg>
  </span>
  
  
    <br> <h-changetext > Conseils </h-changetext > <br> <h-changetext > Analyse de données </h-changetext > <br>  <h-changetext > Enquêtes et recherches </h-changetext > 
  
  <div id=flip>
    <div><div><i class="fa fa-check-square"></i>    CONSEILS</div></div>
    <div><div><i class="fa fa-users"></i> <i class="fa fa-search"></i>    ENQUÊTES ET RECHERCHES</div></div>
    <div><div> <i class="fa fa-line-chart"></i>    ANALYSES STATISTIQUES </div></div>
  </div><hr class="rounded"></div>'
  
<!--

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/sLtQ0J1kzOg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

-->

