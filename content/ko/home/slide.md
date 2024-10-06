---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:
  - block: features
    content:
      title: 
      text: <br><span style="font-size:125%">앞으로 공부 하고 관심 있는 분야들</span>

  - block: slider
    content:
      slides:
        - title: 
          content: <span style="font-size:90%">자바<span style="font-size:90%">
          align: center
          background:
            image:
              filename: java1.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: 
          content: <span style="font-size:90%">Spring</span>
          align: center
          background:
            image:
              filename: spring1.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: 
          content: <span style="font-size:90%">AI</span>
          align: center
          background:
            image:
              filename: 1.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: 
          content: <span style="font-size:90%">개발</span>
          align: center
          background:
            image:
              filename: dev.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      is_fullscreen: true
      loop: true
      interval: 3000
---
