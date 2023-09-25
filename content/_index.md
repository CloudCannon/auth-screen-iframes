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
                style:
                  heading_level: h3
                  text_color: Secondary
                content:
                  text: A new way to configure your CloudCannon sites
              - _bookshop_name: cloudcannon/simple/paragraph
                content:
                  text: >-
                    With our new visual interface for your site’s configuration,
                    you can see everything at a glance — and learn more about
                    the config and input options that are available.
              - _bookshop_name: cloudcannon/simple/button
                style:
                  type: Secondary
                  size: Responsive
                  disabled: false
                content:
                  text: Read the article
                  url: >-
                    https://cloudcannon.com/blog/a-new-way-to-configure-your-cloudcannon-sites/?utm_campaign=Config%20GUI%20PM&utm_source=authscreen
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
      path: /uploads/config-screen-image.png
      alt: Client Sharing in CloudCannon
    style:
      content_width: Small
      content_alignment: Center
---
