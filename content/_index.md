---
# Leave the homepage title empty to use the site title
title: ""
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
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      background:
        color: zinc
        text_color_light: false

  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
         My research interests include autonomous navigation and positioning in robotics. In a broader sense, I am interested in how things see and understand the world utilizing different sensor measurements. As well as practical implementation, I hope to pursue the fundamental background of estimation, such as Bayesian estimation theory and Statistical Inference, in depth.
         
         Please visit [here](https://jaeryounglee.github.io/research-areas/) to see my research journey 😃
    design:
      columns: '1'

  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  
---
