---
date: "2023-03-10T00:00:00Z"
image:
  filename: wordcloud_analyse_non_supervisée.png
  caption: Principaux thèmes du site, d'après la [section "tags"](/#tag_cloud)
  focal_point: Smart
summary: [article à faire]
tags:
- Web-analysis
- Text-analysis
- Analyse thématique non-supervisée
categories:
- Analyse de textes
title: "Analyses non-supervisées"
summary: Les méthodes d'analyses non-supervisées ou 'naïves' ne s'appuient **pas** sur un modèle identifiant la présence de certains termes ou de certaines formulations. Ainsi, elles s'appliquent à des ensembles de textes qui ne sont pas l'objet de modèlisations préalables. 
---


Les méthodes d'analyses non-supervisées ne s'appuient pas sur un lexique ou un modèle dépendant de certaines formulations. Ainsi, ces méthodes sont exploitables "immédiatement", pour n'importe quel ensemble de textes (théoriquement cela implique également l'analyse de textes dans des langues inconnues de l'analyste). 


# Quelques exemples de méthodes non-supervisées

{{< toc >}}

## Modèle GLOVE (Google)

## Dirichlet LDA
*[... à faire]*

# Modifications ou extractions supervisées du texte suivies d'analyses non-supervisées
Parfois, l'analyste constitue un sous-échantillon de textes d'après un critère précis, pour déployer ensuite des analyses non-supervisées sur ce sous-ensemble de textes identifiés de façon supervisées (p. ex. textes qui contiennent un terme précis ou un ensemble de termes exprimant l'insatisfaction d'un client, d'après un lexique exhaustif et validé des formulations exprimant l'insatisfaction). 

*[À compléter]*

## Les analyses sans modèles sous-jacents 
Certaines formes d'analyses non-supervisées servent à prendre contact rapidement avec le corpus de données, de façon exploratoire : termes les plus fréquents, ou qui occasionnent le plus de réactions sur Facebook, qui apparaîssent dans les rapports au sujet des catastrophes les plus importantes mais pas dans les rapports au sujet des accidents de moindre importance, etc. 

Éventuellement, il faut étudier un nombre restreint de termes identifiés comme pertinents, mais ne constituant pas des phrases : il n'est alors pas possible de recourir aux modèles qui reposent sur des formes de cooccurences au sein d'une phrase entière ou d'un paragraphe (p. ex. les modèles GLOVE ou LDA). Dans ce cas, on peut généralement étudier les termes les plus fréquents, voire ceux qui sont en coexistence. Ce cas de figuree concerne typiquement les "*tags*" ou les "catégories" associés à des articles de presse en ligne ou des billets de blogs, les hashtags, les ingrédients sur les sites de recettes de cuisine, etc.


{{< spoiler text="Cliquez ici pour des précisions sur l'analyse de tags et leurs utilités pour le fonctionnement du site-web lui-même.">}}

Certains sites proposent des balises html spécifiques à l'affichage d'un système de mots-clés (selon le site-web, ils sont présentés comme des "tags", "catégories", "mots-clés", etc.). En général, ces mots-clés sont renseignés manuellement par l'administrateur du site-web ou celui qui publie l'article, au même titre que d'autres champs associés à un article en ligne ou un billet de blog (p. ex. le titre, un éventuel résumé ou une date de publication). Quand ils sont affichés dans le cadre d'un article en ligne, d'un post Facebook ou d'un tweet, chacun de ces mots-clés constitue généralement une vignette cliquable, qui redirige l'utilisateur vers une page qui regroupe le contenu associé à ce mot-clé. On retrouve ces mots-clés à la fin de la plupart des articles de presse en ligne ou sur certains billets de blogs Ces tags servent généralement de redirection vers, que ce soit les quelques  Par ailleurs, ces mêmes 'tags' sont parfois exploités pour déterminer le contenu à présenter à l'utilisateur, typiquement pour proposer du contenu à la fin de la lecture d'un article (p. ex. pour proposer d'autres articles en lien avec l'analyse de textes à la fin de cet article). Éventuellement, tous les "tags" ou une sélection des tags les plus fréquents sont affichés sur une page (p. ex. les nuages de mots de "tags", comme sur la page d'acceuil du site d'E-MAGE Diag').

{{< /spoiler >}}

Par exemple, les "tags" des différentes pages du site d'E-MAGE consulting sont présentés dans la table ci-dessous.

<div class="table-responsive">
  {{< tags_table >}}  
</div>

 Cette table permet notamment d'identifier les tags qui n'apparaîssent jamais ensemble ou, au contraire, apparaissent systématiquement ensemble (p. ex. les *tags* "analyses tématiques supervisées" et "lexiques"). Ce type d'analyses permet généralement d'identifier plusieurs optimisations pour un site-web, y compris pour des sites dont je ne suis pas l'administrateur (p. ex. la majeure partie des sites-web journalistiques ou de partis politiques qui utilisent un système de *tags*). Un exemple d'optimisation repose sur l'identification des "chemins" de navigation qu'un utilisateur peut emprunter, s'il clique sur toutes les redirections qui sont proposées sous les articles du site. Ainsi, l'administrateur d'un site-web avec un système de recommandation d'articles doit s'intéresser aux mots-clés associés aux articles conduisant à la plus forte rétention des utilisateurs, que ce soit en s'assurant que les articles les plus visionnés ont des tags en communs avec d'autres thématiques occasionnant une forte rétention des utilisateurs - pour que ces derniers soient suggérés aux utilisateurs, en modifiant légèrement sa ligne éditoriale pour publier des articles impliquant plusieurs thématiques jusqu'alors peu ou pas coexistantes - mais occasionnant une forte rétention des utilisateurs, etc.
 
<!-- 
CI DESSOUS TU UTILISE UNE TABLE PRODUITE PARR UN MIX DE CODES HTML ET DE HUGO SHORTCODE renseignés dans layouts/shortcodes/tags_table.html
-->


<!-- CI DESSOUS UN GRAPH DE RELATION UN PEU NAZBROQUE MAIS QUI A LE MERITE D'ETRE FONCTIONNEL -->
 
 