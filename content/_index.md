---
# Leave the homepage title empty to use the site title
title: "Woosung (Reiss) Koh"
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
    design:
      css_class: dark
      background:
        color: black
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
      title: 📚 Publications
      text: "*First Author(s), ^Advisor(s)"
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    content:
      title: '🤺 Mentees'
      subtitle: ''
      text: |-
          <small> I have been fortunate to mentor individuals listed below, just as I have benefited from the guidance of numerous mentors and advisors throughout my own journey.
          - MinHyung Lee ⟶ Research Intern, DAVIAN Lab, KAIST AI</small>
          - Hyeongjin Kim ⟶ Intern (Advanced Research), Hyundai Mobis</small>

    design:
      columns: '1'
---