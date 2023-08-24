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
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Honors'
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
          date_end: ''
          date_start: '2023-06-01'
          description: ''
          organization: School of Applied Economics of Renmin University of China
          organization_url: http://ae.ruc.edu.cn/home/index.htm
          title: Second prize of Undergraduate dissertation
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2022-09-01'
          description:  ''
          organization: School of Applied Economics of Renmin University of China
          organization_url: http://ae.ruc.edu.cn/home/index.htm
          title: First Prize of the "Jingshi Cup" Academic Writing Competition
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2021-12-01'
          description:  ''
          organization: Renmin University of China
          organization_url: https://www.ruc.edu.cn/en
          title: Scholarship for Social Work and Voluntary Service
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2020-12-01'
          description:  ''
          organization: Renmin University of China
          organization_url: ''
          title: Runner-up of Debate Contest at Renmin University of China
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2020-12-01'
          description:  ''
          organization: Renmin University of China
          organization_url: https://www.ruc.edu.cn/en
          title: Outstanding School Cadre
          url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
 - block: features
      content:
      title: Skills
      items:
        - name: R
          description: 80%
          icon: r-project
          icon_pack: fab
        - name: STATA
          description: 90%
          icon: house
          icon_pack: fas
        - name: Statistics
          description: 85%
          icon: chart-line
          icon_pack: fas
        - name: Volleyball
          description: 80%
          icon: volleyball
          icon_pack: fas
        - name: Tiktok
          description: 90%
          icon: tiktok
          icon_pack: fab
        - name: Bilibili
          description: 95%
          icon: bilibili
          icon_pack: fab
      design:
      columns: '3'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        If you have any questions, please don't hesitate to contact me.
      # Contact (add or remove contact options as necessary)
      email: yu.xiaokun@outlook.com
      phone: +86 136 9508 0017
      # appointment_url: 'https://calendly.com'
      address:
        street: Avenida da Universidade
        city: Taipa
        region: Macau
        postcode: ''
        country: China
        country_code: CN
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Wednesday 20:00 to 23:00'
      # Automatically link email and phone or display as text?
      autolink: false
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
