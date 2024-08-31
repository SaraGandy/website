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
      text-align: left
      items:
        - name: R & Statistics
          description: Statistical modelling (GLMs, GLMMs, GAMs, SEMs) in R, qGIS (spatial analyses), DNAstar for bioinformatics
          icon: r-project
          icon_pack: fab
        - name: Field work
          description: Live capture of ungulate & rodents, trdio-telemetry, camera trapping, distance sampling,  blood/skin biopsy sampling, collection of ticks/mosquitoes
          icon: tree
          icon_pack: fas
        - name: Laboratory
          description: Tick/mosquito morphological ID, DNA extraction, PCR (real time & nested), Sanger sequencing
          icon: flask
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
        - title: Research Associate
          company: University of Glasgow
          company_url: ''
          company_logo: 
          location: Glasgow, UK
          date_start: '2024-03-04'
          date_end: ''
          description: I am currently a research associate at the University of Glasgow, working on the MEaSURE project, an interdisciplinary project in collaboration with the University of Manchester and the University of Salford. The project aims to explore the ecological services and disservices associated with urban green spaces. My research specifically focuses on assessing the risk of tick-borne diseases in urban green spaces by understanding how disease risk varies with landscape connectivity, land cover and host presence. Additionally, I will create exposure risk maps using mobility data to track park usage patterns.

        - title: Senior Medical Entomologist
          company: UK Health Security Agency
          company_url: ''
          company_logo: 
          location: Porton Down, UK
          date_start: '2023-03-03'
          date_end: '2024-02-06'
          description: |2-
              As a Senior Medical Entomologist, I am leading a range of ecological research projects, including the National Tick Survey as well as various field base ecological project investigating the impacts of land management and host presence on tick-borne disease hazard. I also analyse large government dataset to, for instance, understand spatiotemporal changes in tick distribution. Some of my responsibilities include: 

              * Managing field base ecological research projects
              * Coordinating with stakeholders and project partners
              * Management of data entry
              * Data analysis (data visualisation, statistical modelling, spatial modelling)
              * Writing peer-reviewed articles
              * Training vector control officers overseas (UKOTS)
        - title: Medical Entomologist
          company: UK Health Security Agency
          company_url: ''
          company_logo: 
          location: Porton Down, UK
          date_start: '2020-03-08'
          date_end: '2023-03-01'
          description: |2-
              As a Medical Entomologist, I am involved in  a range of ecological research projects focusing on better understanding tick-borne disease risk in the UK. Some of my responsibilities include:

              * Coordinating field work logistics, leading a team of 5 people
              * Coordinating with stakeholders and project partners
              * Data entry
              * Data analysis (data visualisation, statistical modeling, spatial modelling)
              * Writing peer-reviewed articles
        - title: Graduate teaching assistant
          company: University of Glasgow
          company_url: ''
          company_logo: 
          location: Glasgow, UK
          date_start: '2016-11-01'
          date_end: '2020-05-30'
          description: As a graduate teaching assistant, I am teaching undergraduate and MSc students during practicals and tutorial sessions on general biology (labs & marking), introduction to GIS, statistics (GLMs, GLMMs, dplyr & ggplot2 in R), marine biologgy (field course) and molecular biology (labs).
        - title: PhD Candidate
          company: University of Glasgow
          company_url: ''
          company_logo: 
          location: Glasgow, UK
          date_start: '2016-10-03'
          date_end: '2020-09-10'
          description: My PhD focuses on the impacts of host community composition on Lyme disease hazard in Scottish woodlands.
        - title: Field technician
          company: Grimsö research station
          company_url: ''
          company_logo: 
          location: Grimsö, Sweden
          date_start: '2016-05-01'
          date_end: '2016-07-31'
          description: As a field technician, my duties include mammal capture (roe deer, rodents), blood sampling, radio-telemetry, animal survey, tick collection, tick identification and distance sampling.
        - title: MSc research project
          company: Grimsö research station
          company_url: ''
          company_logo: 
          location: Grimsö, Sweden
          date_start: '2015-01-01'
          date_end: '2015-08-30'
          description: My research project focuses on understanding the influence of time, temperature and humidity on *Ixodes ricinus* density in Sweden using a long term dataset.
    design:
      columns: '2'
  - block: experience
    content:
      title: Scolarships & awards
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      items:
        - title: Training award
          company: University of Glasgow
          company_url: ''
          company_logo: 
          location: Glasgow, UK
          date_start: '2019-09-01'
          date_end: '2019-09-07'
          description: I received a sclolarship of £540 granted by the University of Glasgow to attend a workshop on Bayesian Statistics
        - title: Travel grant
          company: VectorBite
          company_url: ''
          company_logo: 
          location:
          date_start: '2019-06-01'
          date_end: '2019-06-07'
          description: Travel grant of £200 granted by VectorBite to attend a meeting/workshop in Trento, Italy
        - title: Travel grant
          company: VectorBite
          company_url: ''
          company_logo: 
          location:
          date_start: '2018-06-01'
          date_end: '2018-06-07'
          description: Travel grant of 1200USD granted by VectorBite to attend a meeting/workshop in Pacific Grove, US
        - title: PhD funding
          company: University of Glasgow/Macaulay fund
          company_url: ''
          company_logo: 
          location:
          date_start: '2016-10-01'
          date_end: '2016-10-02'
          description: Competitive PhD studenship of ~£90,000 obtained
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
      email: sara.gandy@glasgow.ac.uk
      phone: 
      address:
        street: School of Biodiversity, One Health & Veterinary Medicine, University of Glasgow
        city: Glasgow
        region: 
        postcode: 'G12 8QQ'
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

##  {style="text-align: left"}
