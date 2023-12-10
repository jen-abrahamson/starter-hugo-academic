---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Recent News'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Recent News.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: ''
          date_start: '2023-11-02'
          description: 'Passed both my written and oral preliminary exams.'
          organization: Center for Geospatial Analytics, NCSU
          organization_url: https://cnr.ncsu.edu/geospatial/)
          title: Became a Ph.D. Candidate!
        - certificate_url: ''
          date_end: ''
          date_start: '2023-08-02'
          description: 'Received NASA FINESST Research Grant'
          organization: NASA
          organization_url: https://www.nasa.gov/
          title: Proposal focused on mapping daily inundation with satellites to capture short-term methane emissions was funded.
        - certificate_url: ''
          date_end: ''
          date_start: '2023-06-02'
          description: 'Started an internship at Pacific Northwest National Lab'
          organization: Pacific Northwest National Lab
          organization_url: https://www.pnnl.gov/
          title: PhD Intern @ PNNL
          url: 'https://www.pnnl.gov/'
        - certificate_url: ''
          date_end: ''
          date_start: '2021-04-01'
          description: Coauthor on a paper accepted for the IEEE International Geoscience & Remote Sensing Symposium.
          organization: Institute of Electrical and Electronics Engineers
          organization_url: https://2023.ieeeigarss.org/
          title: Paper Accepted to IEEE IGARSS
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2023-05-01'
          description: 'Received news of NSF GRFP award, set to start August 1st'
          organization: National Science Foundation
          organization_url: https://www.nsfgrfp.org/
          title: 'Awarded NSF GRFP'
          url: ''
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
        design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    content:
      title: Publications
      text:
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Presentations
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: features
    content:
      title: Skills
      items:
        - name: R
          icon: r-project
          icon_pack: fab
        - name: Python
          icon: python
          icon_pack: fab
        - name: Remote Sensing
          icon: satellite
          icon_pack: fas
  - block: markdown
    content:
      title: Visualization Gallery
      subtitle: ''
      text: |-
        {{< gallery album="gallery" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: jnabraha@ncsu.edu
      address:
        city: Raleigh
        region: NC
        country: United States
        country_code: US
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Twitter
          link: 'https://twitter.com/JennaAbrahamson'
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
