---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-04-11
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
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: protists.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: collection
    id: research
    content:
      title: Research
      filters:
        folders:
          - research
      sort_by: 'none'
      sort_ascending: false
    design:
      view: card

  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        Publication list click [here](/publication/). 
    design:
      columns: '1'

---
