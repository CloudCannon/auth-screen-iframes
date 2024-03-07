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
                  text: Collaborate with your team
                style:
                  heading_level: h2
                  text_color: Secondary
              - _bookshop_name: cloudcannon/simple/paragraph
                content:
                  text: >-
                    Editing in CloudCannon is now a collaborative experience,
                    enabling multiple users to create content together.
              - _bookshop_name: cloudcannon/simple/button
                content:
                  text: Read the article
                  url: >-
                    https://cloudcannon.com/blog/cloudcannons-new-editing-improvements-are-here/
                style:
                  type: Primary
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
  - _bookshop_name: cloudcannon/structural/spacer
    style:
      height: 120
  - _bookshop_name: cloudcannon/sections/hero-image
    content:
      path: /uploads/collaborative-editing-r.svg
      alt: Collaborative editing in CloudCannon diagram
    style:
      content_width: Large
      content_alignment: Center
---
