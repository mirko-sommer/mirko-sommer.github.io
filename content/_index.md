---
# Leave the homepage title empty to use the site title
title: "About"
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
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: '#4682B4'
        image:
          # Add your image background to `assets/media/`.
          # filename: background.png
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    content:
      title: Selected Projects
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 1
---
