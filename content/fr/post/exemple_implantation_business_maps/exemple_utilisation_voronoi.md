---
date: "2023-03-13T00:00:00Z"
# external_link: false
image:
  filename: map_voronoi_superettes_parisiennes.jpg
  caption: 
  focal_point: Smart
summary: Comment déterminer une zone d'implantation idéale en fonction des emplacements et des zones d'influences d'autres commerces et services.
tags:
- Cartes
- Geomarketing
- Calculs d'implantation
categories: 
- Cartes et analyses geospatiales
title: Identifier une zone d'implantation idéale d'après les zones d'influences des concurrents
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


 <strong> 🎯 Cet article présente comment déterminer une zone d'implantation idéale pour un service, en fonction des emplacements et des zones d'influences d'autres commerces et services. Nous allons notamment identifier les zones les moins denses en concurrents. </strong>



 <img src="/logos/emage-rotating-earth-optimized.gif" style= "float: left" width="140px" >

Une manière d'apprécier les zones d'influences consiste à "enfermer" chaque entité dans son propre espace avec un *diagramme de Voronoï* - d'après le calcul formalisé par G. Voronoï en 1908. Les figures ci-dessous présentent la localisation des cliniques et d'autres types d'enseignes parisiennes (vente de matériaux, supérettes et restaurants).

<figure>  <figcaption> ↓ A. Cliniques et hopitaux parisiens <i class="fa-solid fa-user-doctor"></i>; <br>↓  B. Points de vente de 9 enseignes de vente de matériaux <i class="fa-solid fa-helmet-safety"></i>; <br>↓ C. Supérettes et supermarchés parisiens de 9 groupes concurrents <i class="fa-solid fa-cart-shopping"></i>; <br>D. Restaurants à Paris <i class="fa-solid fa-utensils"></i>

{{< gallery album="voroinoi_business_paris" >}}

   <figcaption> Les "zones d'influences" (A, B et C) sont calculées en Voronoï. Data ODbL (CC-BY-SA 2.0)</figcaption> </figcaption>
</figure>

 

 <img src="/graphiques/map_voronoi_boucheries_Tours.png" style= "float: right; margin-top: 1px; margin-left: 15px" width="260px" >

✨ Le calcul des zones d'influences des concurrents concerne également la vente itinérante (p. ex. un camion de restaurateurs ou de coiffeurs ambulants) et les artisans-commerçants (p. ex. ci-contre les emplacements et zones d'influences des boucheries tourangelles).


{{< spoiler text="Il faut généralement exploiter d'autres indicateurs en complément de la localisation des concurrents, pour déterminer une zone d'implantation idéale (cliquez pour voir des exemples)." >}} 


- Il faut parfois estimer les menaces que représentent les différents concurrents (p. ex. réputation et prix pratiqués), et prendre en compte les caractéristiques des zones et des cibles : prix des locaux au m², densité de population, revenus moyens dans la zone, flux de voyageurs à proximité d'une gare <i class="fa-solid fa-person-walking-luggage"></i>, présence de transports en commun et de parkings, etc. 

- Le système de coordonnées conduisant à calculer le diagramme de Voronoï peut également être ajusté ou remplacé par d'autres référentiels. Par exemple, il faut parfois exploiter les temps de trajets comme référentiel de distances spatiales, notamment en cas d'implantation en dehors des centres urbains.

{{< /spoiler >}}

<br> 

{{% callout note %}}

La localisation des concurrents permet de calculer la zone d'influence de chacun et, *in fine*, d'identifier un lieu d'implantation optimal pour un point de vente, un service ou un service public.

<i class="fa fa-info-circle"></i> Les calculs d'implantation nécessitent généralement de s'intéresser à d'autres services, en synergie avec l'activité à implanter (e.g., les arrêts de bus à proximité).

<i class="fa fa-info-circle"></i> Ce calcul des "zones d'influences" est complémentaire d'autres sources de données, relatives aux concurrents, aux populations et aux zones concernées (p. ex. les prix pratiqués par les concurrents à proximité, le revenu moyen dans la zone d'influence, la présence de transports en commun et de parkings).

{{% /callout %}}


<strong> <i class='fa fa-magic' aria-hidden='true'></i>🌟 Nous pouvons vous aider à identifier un lieu d'implantation idéal. </strong>

<div> <a href= '/page_contacts/page_contact/' title= "Vers la page de contacts">  <button class= "button button-rond"> <i class="fa fa-paper-plane"> </i> CONTACTEZ E-MAGE </button> </a> </div> <br> <br>


