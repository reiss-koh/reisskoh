---
# Leave the homepage title empty to use the site title
title: "Woosung (Reiss) Koh"
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
    design:
      css_class: ""
      background:
        color: ""
        image:
          # Add your image background to `assets/media/`.
          filename: 
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    content:
      title: Publications
#      text: "*Equal contribution"
      # Add this line below to show ALL papers:
      count: 0
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      spacing: "1rem"
---
