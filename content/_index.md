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
              - _bookshop_name: cloudcannon/simple/headline
                content:
                  text: Join the CloudCannon Community!
                style:
                  heading_level: h1
                  text_color: Secondary
              - _bookshop_name: cloudcannon/simple/headline
                content:
                  text: Share, learn, and connect with other CloudCannon users.
                style:
                  heading_level: h3
                  text_color: Primary
              - _bookshop_name: cloudcannon/simple/button
                content:
                  text: Browse the Community
                  url: https://hubs.la/Q03bFt1l0
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
  - _bookshop_name: cloudcannon/sections/hero-image
    content:
      path: /uploads/community-launch-login.png
      alt: Wireframe image with CC staff photos
    style:
      content_width: Medium
      content_alignment: Center
---
