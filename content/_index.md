---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Education and Socholarships'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_start: '2021-03-01'
          date_end: '2021-07-01'
          description: 
          organization: Endomapper
          organization_url: https://cordis.europa.eu/project/id/863146
          title: Endomapper's Research Scholarship
          url: ''
        - certificate_url: ''
          date_end: '2027-12-01'
          date_start: '2023-12-01'
          description: 
          organization: Gobierno de Aragon 
          organization_url: https://www.aragon.es/
          title: PhD Scholarship
          url: ''
        - certificate_url: ''
          date_end: '2021-07-18'
          date_start: '2017-09-10'
          description: ''
          organization: Universidad de Zaragoza
          organization_url: https://unizar.es/
          title: BSc in Computer Science
          url: ''
        - certificate_url: ''
          date_end: '2021-06-07'
          date_start: '2021-09-01'
          description: 
          organization: Universidad Politecnica de Valencia
          organization_url: https://www.investmat.webs.upv.es/
          title: MSc in Applied and Theorical Mathematics
          url: ''

    design:
      columns: '2'
  - block: features
    content:
      title: Skills
      items:
        - name: C++
          description: Advance
          icon: code
          icon_pack: fa
        - name: Python
          description: Advance
          icon: python
          icon_pack: fab
        - name: Statistics
          description: Advance
          icon: chart-line
          icon_pack: fas
        - name: LaTex
          description: Advance
          icon: file-alt
          icon_pack: fas
        - name: Bash
          description: Intermediate
          icon: terminal
          icon_pack: fas
        - name: Deep Learning
          description: Advance
          icon: brain
          icon_pack: fas   
  - block: collection
    id: publications
    content:
      #title: Recent Publications
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  #- block: collection
  #  id: featured
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    columns: '2'
  #    view: card
  #- block: collection
  #  id: posts
  #  content:
  #    title: Recent Posts
  #    subtitle: ''
  #    text: ''
      # Choose how many pages you would like to display (0 = all pages)
  #    count: 5
      # Filter on criteria
  #    filters:
  #      folders:
  #        - post
  #      author: ""
  #      category: ""
  #      tag: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
      # Choose how many pages you would like to offset by
  #    offset: 0
      # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
      # Choose a layout view
  #    view: compact
  #    columns: '2'    
  - block: experience
    id: research_experience
    content:
      title: Research Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD Student
          company: Graphics and Iamging Lab
          company_url: 'https://graphics.unizar.es/'
          company_logo: LOGO_G_IL3
          location: Zaragoza, Spain
          date_start: '2022-12-01'
          date_end:
          description: 
          
        - title: Researcher Assistant
          company: Graphics and Iamging Lab
          company_url: 'https://graphics.unizar.es/'
          company_logo: LOGO_G_IL3
          location: Zaragoza
          date_start: '2022-09-01'
          date_end: '2022-12-01'
          description: I was researching intuitive visual appearance editing from real-world datasets using deep learning techniques.
          #    Responsibilities include:

          #    * Analysing
          #    * Modelling
          #    * Deploying
        - title: Researcher Assistant
          company: Endomapper
          company_url: 'https://cordis.europa.eu/project/id/863146'
          company_logo: em
          location: Zaragoza, Spain
          date_start: '2021-03-01'
          date_end: '2021-07-01'
          description: As end-degree project, I received a grant to research on
                       Structure from Motion (SfM) and Multi-view Stereo using colonoscopy
                       videos under Professor José María Martínez Montiel.
        - title: Software Engineering
          company: Bitbrain
          company_url: 'https://www.bitbrain.com/'
          company_logo: bitbrain
          location: Zaragoza, Spain
          date_start: '2020-07-01'
          date_end: '2020-08-01'
          description: During my internship at Bitbrain (supervised by Juan Domingo Tardos from Universidad de Zaragoza) I developed an accurate binary
                       classifier to automate this workflow.
    design:
      columns: '2'

  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Computer Graphics
          tag: Computer Graphics
        - name: Computer Vision
          tag: Computer Vision
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  #- block: markdown
  #  content:
  #    title: Gallery
  #    subtitle: ''
  #    text: |-
  #      {{< gallery album="demo" >}}
  #  design:
  #    columns: '1'
  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    columns: '2'
  #    view: compact
  #- block: tag_cloud
  #  content:
  #    title: Popular Topics
  #  design:
  #    columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Contact me by e-mail 😁
      # Contact (add or remove contact options as necessary)
      email: dsubias@unizar.es
      phone: +34 636752979
      #appointment_url: 'https://calendly.com'
      #address:
      #  street: 450 Serra Mall
      #  city: Stanford
      #  region: CA
      #  postcode: '94305'
      #  country: United States
      #  country_code: US
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
      #  - icon: skype
      #    icon_pack: fab
      #    name: Skype Me
      #    link: 'skype:echo123?call'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
