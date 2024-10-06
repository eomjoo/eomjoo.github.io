---
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

sections:

  - block: slider
    content:
      slides:
        - title:
          content: "<span style='font-size:90%'>Java<span style='font-size:90%'>"
          align: center
          background:
            image:
              filename: java1.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title:
          content: "<span style='font-size:90%'>Spring</span>"
          align: center
          background:
            image:
              filename: spring1.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title:
          content: "<span style='font-size:90%'>AI</span>"
          align: center
          background:
            image:
              filename: 1.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title:
          content: "<span style='font-size:90%'>Development</span>"
          align: center
          background:
            image:
              filename: dev.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

    design:
      slide_height: '350px'
      is_fullscreen: true
      loop: true
      interval: 3000
---
