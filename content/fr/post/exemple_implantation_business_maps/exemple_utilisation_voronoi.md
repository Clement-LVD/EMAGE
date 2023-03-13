---
date: "2023-03-13T00:00:00Z"
# external_link: false
image:
  filename: map_voronoi_superettes_parisiennes.jpg
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

<!-- La projection de données géographiques permet de calculer plusieurs statistiques descriptives, plus ou moins évoluées. Par exemple, il est possible de calculer des "zones d'influences" autour des commerces de proximité, et de calculer la densité d'occupation associée à divers territoires. Cela concerne en premier lieu les entrepreneursqui visent à atteindre les clients situés autour d'eux, comme les restaurateurs - itinérants ou non, les salons de coiffure et les enseignes de grandes distributions ou de bricolage par exemple. Prenons le cas de l'implantation d'un restaurant, d'un magasin de bricolage ou d'une supérette dans Paris, En général, les différents secteurs accessibles à l'entrepreneur sont déjà plus ou moins saturés géographiquement.

voir les [cartes ci-dessous](#figure-superette-paris)

<figure>  {{< figure src="map_voronoi_superettes_parisiennes.jpg" id="superette-paris" >}}
  <figcaption> Cartes des supérettes et supermarchés parisiens de 9 groupes concurrents, et "zones d'influences" en Voronoï (data ODbL, CC-BY-SA 2.0).</figcaption>
</figure>
-->
<!-- un bouton : on utilise une librairie javascript pour le produire ^^ 
il faut aller voir la doc de  https://atomiks.github.io/tippyjs/v6/getting-started/-->
<!-- HTML button -->


Les statistiques spatiales servent par exemple à *monitorer* la concurrence dans différentes zones, et à définir une zone d'implantation idéale pour un commerce ou un service:

- pour un service public en fonction de la position des autres services publics;
- pour une enseigne de vente de matériaux;
- une supérette;
- un restaurant, etc.

<figure>  <figcaption> ↓ A. Cliniques et hopitaux parisiens ; <br>↓  B. Points de vente de 9 enseignes de vente de matériaux ; <br>↓ C. Supérettes et supermarchés parisiens de 9 groupes concurrents ; <br>D. Restaurants à Paris (Data ODbL - CC-BY-SA 2.0)</figcaption> {{< gallery album="voroinoi_business_paris" >}}
   <figcaption> Les "zones d'influences" (A, B et C) sont calculées en Voronoï</figcaption>
</figure>

Pour un entrepreneur qui voudrait implanter un salon de coiffure, cela peut être intéressant d'identifier les zones les moins "densément" fournies. De même pour le coiffeur itinérant, qui voudrait identifier des zones propices à l'installation de son camion.

