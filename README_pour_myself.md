# EMAGE
E-MAGE: Diagnostics et analyses

en gros le thème c'est "academic-starter" mais tu n'a pas vraiment besoin du thème en lui même comme tu bricole tout le site à la mano !

voici les classes du thème de base => 
name = "Academic"
license = "MIT"
licenselink = "https://github.com/wowchemy/starter-hugo-academic/blob/master/LICENSE.md"
description = "Use the website builder to easily build your site with 50+ widgets and deploy with one click! Fully customize your site with themes, plugins, and language packs."
homepage = "https://github.com/wowchemy/starter-hugo-academic/"
demosite = "https://wowchemy.com/hugo-themes/"
tags = ["widgets",
        "resume",
        "portfolio",
        "responsive",
        "clean",
        "personal",
        "company",
        "blog",
        "minimal",
        "light",
        "dark",
        "multilingual",
        "documentation",
        "landing page",
        "projects",
        "single page",
        "contact form",
        "mobile",
        "gallery",
        "search",
        "presentation",
        "simple",
        "minimalist",
        "starter",
        "modern",
        "one page",
        "customizable",
        "technical",
        "product",
        "slide"
        ]
features = ["page builder", "widgets", "themes", "search", "research publication system", "filterable portfolio",
            "blog", "create courses", "talks", "events", "slides", "gallery", "contact form"]

et voici la météhode qu'il comptait employer  dans le netlify.toml =>

[build]
  command = "hugo --gc --minify -b $URL"
  publish = "public"

[build.environment]
  HUGO_VERSION = "0.111.0"
  HUGO_ENABLEGITINFO = "true"

[context.production.environment]
  HUGO_ENV = "production"

[context.deploy-preview]
  command = "hugo --gc --minify --buildFuture -b $DEPLOY_PRIME_URL"

[context.branch-deploy]
  command = "hugo --gc --minify -b $DEPLOY_PRIME_URL"

[[plugins]]
  package = "netlify-plugin-hugo-cache-resources"
  [plugins.inputs]
    debug = true


[//]: # (Site créé en suivant les lignes directrices de ==> https://shilaan.rbind.io/post/building-your-website-using-r-blogdown/ 

)
blogdown::check_site()

blogdown::serve_site()

POUR LA MISE EN LIGNE INITIAL SUR GITHUB, il faut déposer les fichiers directement pour ensuite pouvoir 'commit' les changements
https://kinsta.com/blog/hugo-static-site/

On passe par git ==> netlify => le site web

Tu peux spécifier une liste de documents à ne pas intégrer à git dans gitignore, pour ne pas mettre à jour. Ces répertoires inutiles sont: 
  
  - "public" (celui que va générer le site hugo au final une fois compilé)
  - R , tant que tu n'utilise pas le compilateur de R pour produire le site (on va passer par netlify pour build donc jamais besoin de build le site depuis R) !
  - BROUILLONS_WEBSITE, bien évidemment celui la va rester en local...
  - des fichiers comme le Rprofile spécifique à R (qui permet de régler le 'knitonsave' par exemple)
  - resources

le projet Hugo academic s'organise en plein de folders
Les styles sont dans layouts/partials
voir ici pour gérer les styles => https://nickballou.com/blog/custom-wowchemy/

Il y a des shortcodes qui créent plein d'éléments que tu appelle en yaml => ils sont dans layouts/partials/blocks par exemple
le fichier custom.css est très important pour définir plein de styles
tu a aussi des dossiers d'images trop chaotique ++ (3 au total + la possibilité d'avoir une image dans un sous-dossier)
un shortcode tag_clouds
tu essaye de modifier le shortcode features.html en créant un features_avec_tooltip et une version avancée (pour injecter autre chose que du svg)

1) LE CONTENU SE TROUVE DANS LE DOSSIER "content" => c'est là qu'il y a tout ce qui deviendra des pages 
(même s'il n'y a pas de lien pointant vers ces pages). Ce  contenu va littéralement devenir le site !
par exemple content/assets/media etc. va devenir www.lesite.com/assets/media !

Dans le dossier "content", il y a:

A) la page principale sous forme du index.md qui est à la racine du répertoire "/content/"  
B) des sous-dossiers et des éventuels sous-sous dossiers. Les fichiers .md dans ces dossiers correspondent à des 
    B.1) pages qui sont créées et vers lesquelles on redirige parfois le visiteur comme la partie "academic_resume" de clément, les différents articles placés dans "posts" ou dans "projects", etc.
    B.2) autant de pages qui sont crées ou d'ensembles de pages 
C) quelques détails qui sont à la racine du content/, comme les termes et conditions d'utilisation, des images ou encore la déclaration "privacy".

Il y a plein de choses importantes (bon courage pour reprendre un tel projet)
Déjà, Hugo propose des fonctions de taxonomies: tu peux ajouter des classes comme des "tags" ou des "categories" (tu peux régler des pronoms au pluriels dans les paramètres); et ensuite il faut faire un système de dossiers et de fichiers pour indiquer les noms corrects de ces taxonomies... Le dossier c'est "content/categories/[un dossier dont le nom est le même que celui de la catégorie que tu veux trafiquer l'affichage - typiquement l'affichage de son nom"