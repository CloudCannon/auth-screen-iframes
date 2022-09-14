---
title: Home
sections:
  - _bookshop_name: cloudcannon/sections/one-column
    content:
      blocks:
        - _bookshop_name: cloudcannon/structural/content_blocks
          content:
            blocks:
              - _bookshop_name: custom/dynamic-spacer
                style:
                  min: 0
                  max: 60
                  viewport_lower_limit: 600
                  viewport_upper_limit: 800
              - _bookshop_name: cloudcannon/simple/paragraph
                content:
                  text: '**NEW INTEGRATION**'
              - _bookshop_name: cloudcannon/simple/headline
                style:
                  heading_level: h3
                  text_color: Primary
                content:
                  text: Enjoy greater control over your GitHub connection.
              - _bookshop_name: cloudcannon/simple/paragraph
                content:
                  text: >-
                    Manage your GitHub OAuth and repository access separately,
                    cut back on permissions, and only share the required
                    repositories.
              - _bookshop_name: cloudcannon/simple/button
                style:
                  type: Primary
                  size: Responsive
                  disabled: false
                content:
                  text: Read the migration docs
                  url: >-
                    https://cloudcannon.com/documentation/articles/connecting-a-github-repository-as-your-source/#migrating-to-github-app
          style:
            flow: Vertical
            vertical_alignment: Middle
            custom_background_color: false
            background_color: '#ffffff'
    style:
      custom_background_color: false
      background_color: '#f5f5f5'
      content_alignment: Center
      content_width: Medium
  - _bookshop_name: cloudcannon/sections/hero-image
    content:
      path: /uploads/github-access-control.png
      alt: GitHub Repository Access Control
    style:
      content_width: Large
      content_alignment: Center
---
