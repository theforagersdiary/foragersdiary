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
        icon: rocket-launch
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
      css_class: "min-h-screen"
      background:
        color: ""
        image:
          # Add your image background to `assets/media/`.
          filename: ""
          size: cover
          parallax: false
          text_color_light: true
          filters:
            brightness: 0.8


  - block: collection
    content:
      title: Somefing
      filters: 
        folders:
        - blog

    design:
      columns: 3
      view: article-grid

  - block: cta-card
    content:
      title: "Something heere possibly as a CTA?"
      text: Lots of text i ehre khuewf kww wkuwfh  whfkjwbf wkefhwek wkfuwehgfkwef biwuehfwe wiuehfuwehf wkeufhwiuehfbkiwhef.
      button:
        text: Get Started
        url: /blog/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
