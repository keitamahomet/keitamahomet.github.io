---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  spacing: '5rem'

sections:
  - block: collection
    content:
      title: Selected Projects
      text: I enjoy building data-driven solutions. Here is a selection of projects in descriptive, predictive, prescriptive analytics and databases.

      filters:
        folders:
          - projects

      # Affiche une sélection sur la page Projects
      count: 9

      # Tri : les plus récents en premier
      sort_by: date
      sort_ascending: false

      # ✅ Affiche tout contenu (pas seulement "featured")
      featured_only: false

      #Bouton vers la liste complète
      archive:
        enable: true
        text: See all
        link: /projects/

    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
---
