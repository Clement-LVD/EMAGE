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

> <strong> ✨Dans cet article, nous allons voir comment calculer une zone d'implantation pour un service, en fonction de la densité de  la conccurence. </strong>

La densité des concurrents aide à déterminer une zone d'implantation, avec la prise en compte des services du même type (point de vente, service ou service public) 🎯. La densité des concurrents est complémentaire d'autres données (e.g., prix des locaux, densité de population et revenus moyens, flux de voyageurs à proximité d'une gare <i class="fa-solid fa-person-walking-luggage"></i>).

Les figures ci-dessous présentent la densité des cliniques et de plusieurs enseignes parisiennes (vente de matériaux; supérettes et restaurants).


<figure>  <figcaption> ↓ A. Cliniques et hopitaux parisiens <i class="fa-solid fa-user-doctor"></i>; <br>↓  B. Points de vente de 9 enseignes de vente de matériaux <i class="fa-solid fa-helmet-safety"></i>; <br>↓ C. Supérettes et supermarchés parisiens de 9 groupes concurrents <i class="fa-solid fa-cart-shopping"></i>; <br>D. Restaurants à Paris <i class="fa-solid fa-utensils"></i>{{< gallery album="voroinoi_business_paris" >}}
   <figcaption> Les "zones d'influences" (A, B et C) sont calculées en Voronoï. Data ODbL (CC-BY-SA 2.0)</figcaption> </figcaption>
</figure>

De même pour planifier le démarrage de l'activité de certains vendeurs itinérants, comme un camion de restaurateurs ou de coiffeurs ambulants. 

- <i class="fa-solid fa-hat-wizard"></i> 🔮 Lister les commerces comparables et identifier les zones les moins denses

-  <i class='fa fa-magic' aria-hidden='true'></i>🌟 Produire une liste des meilleurs emplacements et d'autres rendus (e.g., une carte dynamique)
