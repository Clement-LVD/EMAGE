a l'origine il y avait un dossier "post" dans le répertoire "fr/content" de hugo (un des trucs essentiels de hugo donc)
et tu la envoyé là (il y a des super exemples pour faire un blog tout simple, des explications sur la mise en place d'un site hugo, etc.

DE PLUS, DANS LE DOCUMENT GLOBAL QUI CALCUL LA PAGE !! IL FAUT EGALEMENT INDIQUER DANS LE YAML CE CONTENU, avec un block !


- block: collection
  content:
    count: 2
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Publications Linkedin
  design:
    columns: "2"
    view: compact
  id: posts