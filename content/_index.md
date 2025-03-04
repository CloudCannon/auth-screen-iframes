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
                  text: New Headless Mode, and live data and config editing
                style:
                  heading_level: h1
                  text_color: Secondary
              - _bookshop_name: cloudcannon/simple/paragraph
                content:
                  text: >-
                    Available now for all users! Edit your site config and data
                    without rebuilding — and choose to add dynamic site
                    components, simplify your builds, or create richer card
                    previews.
              - _bookshop_name: cloudcannon/simple/button
                content:
                  text: Learn more
                  url: >-
                    https://cloudcannon.com/blog/streamlined-headless-mode-unified-configuration-and-live-data-editing/?utm_campaign=Unified%Config&utm_source=auth-screen
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
      height: 40
  - _bookshop_name: cloudcannon/sections/hero-image
    content:
      path: /uploads/auth-screen-hype-community-1.png
      alt: Read and write access groups for CloudCannon's Custom Permissions
    style:
      content_width: Small
      content_alignment: Center
---
