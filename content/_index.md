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
                  text: '**FEATURE: CLIENT SHARING**'
              - _bookshop_name: cloudcannon/simple/headline
                style:
                  heading_level: h3
                  text_color: Primary
                content:
                  text: Let anyone, anywhere, edit your CloudCannon sites
              - _bookshop_name: cloudcannon/simple/paragraph
                content:
                  text: >-
                    It’s easy to share your static site with anyone, and allow
                    them to edit it — without new users having to create a
                    CloudCannon account.
              - _bookshop_name: cloudcannon/simple/button
                style:
                  type: Primary
                  size: Responsive
                  disabled: false
                content:
                  text: Learn more
                  url: >-
                    https://cloudcannon.com/blog/let-anyone-anywhere-edit-your-cloudcannon-sites/?utm_campaign=Client%20Sharing%20PM&utm_source=internal&utm_medium=auth-screen
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
      path: /uploads/client-sharing-image-final.svg
      alt: Client Sharing in CloudCannon
    style:
      content_width: Medium
      content_alignment: Center
---
