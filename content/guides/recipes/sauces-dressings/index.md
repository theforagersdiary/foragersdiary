---
title: Sauces & Dressings
url: /recipes/sauces-dressings
layout: listrecipes
weight: 2
sections:

  - block: collection
    id: sauce
    content:
      title: Sauces and Dressings Recipes
      subtitle:
      text: 'Everything tastes better with a good sauce!'
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
        author: ""
        category: ""
        tag: "condiment"
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'title'
      sort_ascending: true
    design:
      view: article-grid
      columns:
      spacing:
        padding: ['0rem', 0, '6rem', 0]
---