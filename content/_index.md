---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: R 
          description:
          icon: r-project
          icon_pack: fat
        - name: vector-
          description:
          icon: spider
          icon_pack: fat
        - name: ecological
          description:
          icon: tree
          icon_pack: fat

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
        - title: Senior Medical Entomologist
          company: UK Health Security Agency
          company_url: ''
          company_logo: 
          location: Porton Down, UK
          date_start: '2023-03-03'
          date_end: ''
          description: |2-
              As a Senior Medical Entomologist, I lead a range of ecological research projects, including the National Tick Survey and various projects investigating the impacts of land management and host presence on tick-borne disease hazard. My responsibilities include:

              * Managing ecological research projects
              * Coordinating with Stakeholders
              * Management of data entry
              * Data analysis (data visualisation, statistical modeling, spatial modeling)
              * Writing peer-reviewed articles
        - title: Medical Entomologist
          company: UK Health Security Agency
          company_url: ''
          company_logo: 
          location: Porton Down, UK
          date_start: '2020-03-08'
          date_end: '2023-03-01'
          description: |2-
              As a Medical Entomologist, I am involved in  a range of ecological research projects focusing on tick-borne diseases in the UK. My responsibilities include:

              * Coordinating field work logistics
              * Coordinating with Stakeholders
              * Data entry
              * Data analysis (data visualisation, statistical modeling, spatial modeling)
              * Writing peer-reviewed articles
        - title: PhD Candidate
          company: University of Glasgow
          company_url: ''
          company_logo: 
          location: Glasgow, UK
          date_start: '2016-10-03'
          date_end: '2020-09-10'
          description: My PhD focusses on the impacts of host community composition on Lyme disease hazard in Scottish woodlands.
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: sara.gandy@ukhsa.gov.uk
      phone: +44(0) 7929 853811
      address:
        street: Manor Farm Road, Porton Down
        city: Salisbury
        region: Wiltshire
        postcode: 'SP4 0JG'
        country: United Kingdom
        country_code: UK
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/SaraGandy38'
           # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
