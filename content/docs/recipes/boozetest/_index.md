---
title: boozetets
url: /recipes/boozetets
layout: listrecipes

sections:

  - block: collection
    id: recipes
    content:
      title: Recipes
      subtitle:
      text: 'Recipes from the kitchen. Many of these recipes are from...'
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
        author: ""
        category: ""
        tag: "boozetest"
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
      columns: 4
      spacing:
        padding: ['0rem', 0, '6rem', 0]
---