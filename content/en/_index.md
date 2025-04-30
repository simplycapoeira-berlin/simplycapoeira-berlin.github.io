---
# Leave the homepage title empty to use the site title

title:
date: 2022-10-24
type: landing

sections:

  - block: hero
    content:
      title: |
        Simplesmente 
        Capoeira Berlin e.V.
      image:
        filename: sharing.jpg
      text: |
        <br>
        
        We are an international group of capoeira, whose purpose is to implement the fundamentals of capoeira, focusing on the evolution of technique and basic principles.

  
  - block: contact
    content:
      title: Training Locations (MELO, KSG, TAM) 
      text: |-
        Join us at the training, guests are always welcome! Currently we have two adult training session and two kids training sessions at:
          <br>**MELO**: upper gym at **M**arie-**E**lisabeth-**L**üders-**O**berschule
          <br>**KSG**: upper gym at **K**urt-**S**chumacher-**G**rundschule
          <br>**TAM**: gym of Interkulturellen Familienzentrums **tam**
      address:
        street: 'MELO:Steinmetzstr. 79 (10783), KSG:Puttkamerstr. 19 (10969), TAM:Wilhelmstr. 116 – 117 (10963)'
        # city: Berlin 
        # postcode: '10783'
        country: Germany
        country_code: DE
      # coordinates:
      #   latitude: '52.499238779432005'
      #   longitude: '13.36469710838366'
      # directions: small gym on the upper floor
      office_hours:
        - '**Kids**: '
        - 'Tuesday(MELO) and Thursday(MELO) 17:00-18:30'
        - 'Friday(TAM) 16:30-18:00'
        - '**Adults**:'
        - Tuesday(KSG) 18:00-19:30, Friday(MELO) 20:00-21:30'
      autolink: true
    design:
      columns: '2'

  - block: collection
    content:
      title: Events 
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
      title: News
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
