---
url: /resources/bookshelf
linkTitle: Bookshelf
title: Bookshelf
weight: 50
layout: listrecipes
reading_time: false
hide_date: true
sections:

  - block: collection
    id: books
    content:
      title: The Bookshelf
      subtitle:
      text: Thoughts, reviews and recommendations 
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
        
        author: ""
        category: ""
        tag: "books"
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
      columns: 3
      spacing:
        padding: ['0rem', 3rem, '0rem', 3rem]
---

