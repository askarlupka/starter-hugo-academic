---
# Leave the homepage title empty to use the site title
title: Amanda Lee Skarlupka
date: 2023-05-03
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: Data Science & Visualization
          description: R, RShiny, Biostatistics
          icon: chart-simple
          icon_pack: fas
        - name: Communication
          description: Plain language, Academic publications, Editiing
          icon: bullhorn
          icon_pack: fas
        - name: Project Management
          description: 
          icon: list-check
          icon_pack: fas
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Presidential Management Fellow
          company: National Cancer Institute 
          company_url: 'https://www.cancer.gov/'
          company_logo: org-gc
          location: Rockville, MD
          date_start: '2022-06-05'
          date_end: ''
          description:
        - title: Graduate Researcher
          company: University of Georgia - Athens
          company_url: 'www.uga.edu'
          company_logo: org-x
          location: Athens, GA
          date_start: '2016-08-11'
          date_end: '2022-05-15'
          description: 
    design:
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Please fill out the following form to contact me:

      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
