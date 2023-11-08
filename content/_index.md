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
                  text: ''
              - _bookshop_name: cloudcannon/simple/headline
                content:
                  text: A new way to configure your CloudCannon sites
                style:
                  heading_level: h3
                  text_color: Secondary
              - _bookshop_name: cloudcannon/simple/paragraph
                content:
                  text: >-
                    With our new visual interface for your site’s configuration,
                    you can see everything at a glance — and learn more about
                    the config and input options that are available.
              - _bookshop_name: cloudcannon/simple/button
                content:
                  text: Read the article
                  url: >-
                    https://cloudcannon.com/blog/a-new-way-to-configure-your-cloudcannon-sites/?utm_campaign=Config%20GUI%20PM&utm_source=authscreen
                style:
                  type: Secondary
                  size: Responsive
                  disabled: false
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
      path: /uploads/site-mounting-log-in-hero.png
      alt: Site Mounting in CloudCannon diagram
    style:
      content_width: Medium
      content_alignment: Center
---
