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
                  text: We're partnering with Astro 🚀
                style:
                  heading_level: h1
                  text_color: Secondary
              - _bookshop_name: cloudcannon/simple/headline
                content:
                  text: >-
                    Get a headstart with our new Astro Component Starter,
                    Jetstream template, and join the Astro + Cloudcannon
                    challenge!
                style:
                  heading_level: h3
                  text_color: Primary
              - _bookshop_name: cloudcannon/simple/button
                content:
                  text: Find out more
                  url: https://hubs.la/Q046jn960
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
      path: /uploads/cc-astro-logo-1.svg
      alt: Astro X CloudCannon logos
    style:
      content_width: Medium
      content_alignment: Center
---
