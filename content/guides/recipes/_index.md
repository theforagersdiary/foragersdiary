---
title: Recipes
url: 
type: guides
layout: listrecipes
weight: 4
sections:

  - block: collection
    id: recipes
    content:
      title: Recipes
      subtitle:
      text:
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
        
        author: ""
        category: ""
        tag: "recipe"
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
        padding: ['0rem', 4rem, '0rem', 4rem]
---