---
widget: slider
weight: 20
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '512px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: '[🔎Research Areas](/project/)'
      content: Take a look at what we're working on
      align: left
      background:
        position: right
        color: '#666'
        brightness: 0.5
        media: 347479055_concept_art_of_people_doing_philosophical_research_.png
        fit: cover
    - title: '[Meet the Team!](/people/)'
      content: ''
      align: center
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: meet_the_team.png
        fit: cover
    - title: 'Get in touch! ⬇️'
      content: ''
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.7
        media: 1112809040_A_homing_pigeon__by_Rosa_Bonheur_and_Edward_Hopper__trending_on_art_station.png
        fit: cover
      link:
        icon: envelope
        icon_pack: fas
        text: Contact us
        url: /#contact
---