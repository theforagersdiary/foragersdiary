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
      title: The Foragers Diary
      text: Foraging Resources | Foraging Guides | Foraging Diary
      primary_action:
        text: Guides
        url: /docs/
        icon:
      secondary_action:
        text: Diary
        url: /blog/
      announcement:
        text: "Nothing to announce right now"
        link:
          text: "Read more"
          url: "/blog/"
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
      title: Recent Posts
      count: 3
      filters: 
        folders:
        - blog
    design:
      columns: 3
      view: article-grid

  - block: cta-card
    content:
      title: "Why forage?"
      text: Foraging is a gateway to a wider set of connections we have all but lost. Foraging calls us to be active participants within our world and reconnects us to the roots we've lost
      button:
        text: Get Started
        url: /blog/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      background:
        image:
          filename: plant.jpg
          size: cover
          parallax: false
        
---
