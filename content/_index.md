---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2023-05-03
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
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
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true
      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: 'What I work on'
      subtitle: ''
      text: |-
        I help research and data-sharing programs run well. That means turning
        complex, multi-stakeholder initiatives into documented, metrics-driven
        operations, and translating fluently between scientists, engineers,
        policy staff, and leadership.

        My focus areas are antimicrobial resistance (AMR) surveillance data,
        FAIR and responsible data governance, and the ethical use of AI and
        machine learning in public health. I care about inclusive research
        design and building the trust that makes data reuse possible.
    design:
      columns: '1'
  - block: collection
    id: publications
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
