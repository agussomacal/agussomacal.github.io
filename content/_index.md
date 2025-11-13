---
# Leave the homepage title empty to use the site title
title: 'Title'
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  # ============= Research ============= #
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My research currently focuses on developing accelerated version of Natural Gradient Descent specially in the context of Scientific Machine Learning and Non-linear Reduced Order Modelling.
    design:
      columns: '1'
  
  # ============= Featured Publications ============= #
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  
  # ============= Publications ============= #
  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publication
        exclude_featured: false
      count: 5  # Means all
    design:
      view: citation

  # ============= Talks ============= #
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: article-grid
---
