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
        - date_start: '2023-06-01'
          description: 'Started an internship at Pacific Northwest National Lab'
          organization: 'Pacific Northwest National Lab'
          organization_url: https://www.pnnl.gov/
          title: 'PhD Intern @ PNNL'
        - date_start: '2023-04-03'
          description: 'Coauthor on a conference paper accepted for presentation and publication at IEEE International Geoscience and Remote Sensing Symposium'
          organization: 'IEEE IGARSS'
          organization_url: https://2023.ieeeigarss.org/
          title: 'Paper Accepted to IEEE IGARSS'
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - date_start: '2023-03-01'
          description: 'Awarded the NSF GRFP, an award that recognizes and supports outstanding graduate students who are pursuing full-time research-based master's and doctoral degrees in science, technology, engineering, and mathematics (STEM) or in STEM education.'
          organization: 'National Science Foundation'
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
        - name: Inundation/Biogeochemistry
          tag: Inundation/Biogeochemistry
        - name: Change Detection
          tag: Change Detection
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
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
        {{< gallery album="demo" >}}
    design:
      columns: '1'
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
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
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
