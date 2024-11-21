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
          date_start: '2024-04-19'
          description: 'Coauthor on review manuscript with collaborators at PNNL accepted for preprint and public peer review.'
          organization: EGU Biogeosciences
          organization_url: https://egusphere.copernicus.org/preprints/2024/egusphere-2024-98/
          title: Paper Posted for Public Peer Review
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
          description: 'Proposal on mapping daily inundation with satellites to capture methane emissions was funded.'
          organization: NASA
          organization_url: https://www.nasa.gov/
          title: Received NASA FINESST Grant
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
    id: publication
    content:
      title: Publications
      text:
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
