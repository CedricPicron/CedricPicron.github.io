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
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: experience
    id: education
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD candidate
          company: KU Leuven, ESAT-PSI
          company_url: 'https://www.esat.kuleuven.be/english/overview'
          company_logo: esat
          location: Leuven, Belgium
          date_start: '2019-09-01'
          date_end: ''
          description: PhD candidate under supervision of Prof. Tinne Tuytelaars.
        - title: MSc of Mathematical Engineering
          company: KU Leuven
          company_url: 'https://www.kuleuven.be/english/kuleuven/index.html'
          company_logo: kul
          location: Leuven, Belgium
          date_start: '2017-09-01'
          date_end: '2019-06-01'
          description: Graduated with magna cum laude.
        - title: BSc of Electrical Engineering
          company: Vrije Universiteit Brussel
          company_url: 'https://www.vub.be/en'
          company_logo: vub
          location: Brussels, Belgium
          date_start: '2014-09-01'
          date_end: '2017-06-01'
          description: Graduated with summa cum laude.
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: cedric.picron@outlook.com
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
