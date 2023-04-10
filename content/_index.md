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
  - block: features
    content:
      title: Skills
      items:
        - name: python
          icon: python
          icon_pack: fab
        - name: R
          icon: r-project
          icon_pack: fab
        - name: Latex
          icon: code
          icon_pack: fas
        - name: Building daylight simulation
          icon: bug
          icon_pack: fas
        - name: Building energy simulation
          icon: forumbee
          icon_pack: fab
        - name: Parametric Modeling
          icon: mendeley
          icon_pack: fab
  - block: collection
    id: publications
    content:
      title: Recent Publications
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
        - name: VRF
          tag: VRF
        - name: Other
          tag: Other
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: uploads/Huawei.pdf
          date_end: '2023-01-01'
          date_start: '2022-09-01'
          description: ''
          organization: Huawei
          organization_url: https://www.huawei.com/en/
          title: "'Optics Valley Of China. Huawei Cup' The 19th China Post-Graduate Mathematical Contest in Modeling."
          url: ''
        - certificate_url: uploads/Catifications-Mingchen Li_页面_14.jpg
          date_end: '2022-01-01'
          date_start: '2022-09-01'
          description: ''
          organization: WUHAN DESIGN
          organization_url: http://www.wuhancityofdesign.com/en/
          title: The best work of the first domestic BIM application 100 universities invitations (Leader).
          url: ''
        - certificate_url: uploads/Catifications-Mingchen Li_页面_12.jpg
          date_end: '2022-01-01'
          date_start: '2021-06-01'
          description: ''
          organization: PKPM
          organization_url: https://www.pkpm.cn/
          title: 2021 BIM Technology Application Innovation Labor Competition Domestic Software Group (Leader)
          url: ''
    design:
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Free to contact me.
      # Contact (add or remove contact options as necessary)
      email: limingchen@tju.edu.cn

      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: formspree
        formspree:
          id: xbjepolq
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
