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
                  text: '**NEW FEATURE**'
              - _bookshop_name: cloudcannon/simple/headline
                style:
                  heading_level: h3
                  text_color: Primary
                content:
                  text: Edit your Hugo content with Shortcodes
              - _bookshop_name: cloudcannon/simple/paragraph
                content:
                  text: >-
                    CloudCannon is the first CMS with full support and full
                    integration for built-in and custom Hugo shortcodes — across
                    our Visual, Content, and Source Editors.
              - _bookshop_name: cloudcannon/simple/button
                style:
                  type: Primary
                  size: Responsive
                  disabled: false
                content:
                  text: Read the article
                  url: >-
                    https://cloudcannon.com/blog/editing-content-with-hugo-shortcodes/
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
      path: /uploads/hugo-shortcodes-cloudcannon.svg
      alt: Hugo shortcodes in CloudCannon
    style:
      content_width: Large
      content_alignment: Center
---
