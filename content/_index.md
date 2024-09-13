---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: The Forager's Diary
      text: Foraging Resources | Foraging Guides | Foraging Diary
      primary_action:
        text: Guides & Resources
        url: /guides/
        icon: hero/book-open
      secondary_action:
        text: Diary
        url: /blog/
      announcement:
        text: "New site and database build..."
        link:
          text: "Read more"
          url: "/blog/new-site"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: ""
      background:
        color: ""
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: "sitehero.jpg"
          size: cover
          parallax: false
          filters:
            brightness: 0.6
##############################################################
  - block: collection
    id: recentposts
    content:
      title: Recent Additions
      count: 6
      filters: 
        folders:
        tag:
        
    design:
      columns: 3
      view: article-grid

  - block: cta-card
    content:
      title: "Why forage?"
      text: Foraging is a gateway to a wider set of connections we have all but lost. It leads us gently to once more becoming active participants within the natural world, quietly and subtly reconnecting us to the rhythms we have become deafened too. It helps brings meaning and purpose to life by rooting us firmly back within nature. 
      button:
        text: Get Started
        url: /resources/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      background:
        image:
          filename: 
          size: 
          parallax: false
        
---
