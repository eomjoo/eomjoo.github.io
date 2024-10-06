---
# This file represents a page section for the slider.
widget: blank  # Use the 'blank' widget to allow custom content.

# Order that this section appears on the page.
headless: true
weight: 50

sections:
  - block: slider
    content:
      slides:
        - title: "<span style='font-size:90%'>Slide 1</span>"
          content: "<span style='font-size:90%'>This is the content from about1 folder slide 1.</span>"
          align: center
          background:
            image:
              filename: slide1.jpg  # Replace with the appropriate image path in your project
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: "<span style='font-size:90%'>Slide 2</span>"
          content: "<span style='font-size:90%'>This is the content from about1 folder slide 2.</span>"
          align: center
          background:
            image:
              filename: slide2.jpg  # Replace with the appropriate image path in your project
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
