---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: Website_SC_row.png 
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['0', '0', '0', '0']
      css_class: fullscreen

  - block: hero
    content:
      title: |
        Simplesmente 
        Capoeira Berlin e.V.
      image:
        filename: SC_example_horda.jpeg
      text: |
        <br>
        
        **Capoeira** .

  
  - block: contact
    content:
      title: Training Location at MELO 
      text: |-
        Join us at the training, guests are always welcome! Currently we have one adult training session and two kids training sessions at the small gym of MELO (Marie-Elisabeth-Lüders-Oberschule).
      address:
        street: Steinmetzstraße 79, 10783 Berlin
        # city: Berlin 
        # postcode: '10783'
        country: Germany
        country_code: DE
      coordinates:
        latitude: '52.499238779432005'
        longitude: '13.36469710838366'
      directions: small gym on the upper floor
      office_hours:
        - 'Kids: Tuesday and Thursday 17:00 to 18:30'
        - 'Adults: Friday 20:00 to 21:30'
      autolink: true
    design:
      columns: '2'

  - block: collection
    content:
      title: Latest Events 
      subtitle:
      text:
      count: 2
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: event 
    design:
      view: card
      columns: '2'

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 2
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '2'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the trainer →" %}}
    design:
      columns: '1'
---
