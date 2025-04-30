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
        Wir sind eine internationale Capoeira-Gruppe, deren Ziel es ist, die Fundamente von Capoeira zu studieren und zu implementieren, mit Fokus auf Technik und Grundprinzipien.
  
  - block: contact
    content:
      title: Trainingsorte (MELO, KSG, TAM)
      text: |-
        Kommt zu unserem Training, Gäste sind immer willkommen! Zur Zeit bieten wir je zwei Trainingseinheiten für Erwachsene und für Kinder/Jugendliche in die:
          <br>**MELO**: Gymnastikhalle (oben) der **M**arie-**E**lisabeth-**L**üders-**O**berschule
          <br>**KSG**: oberen Sporthalle der **K**urt-**S**chumacher-**G**rundschule
          <br>**TAM**: Sporthalle des Interkulturellen Familienzentrums **tam**
      # BELOW commented stuff could be an option for multicontact (following: https://discourse.gohugo.io/t/variables-in-shortcodes/20637/7)
      # locations:
      #   - name: "MELO"
      #     params:
      #       latitude: '52.499238779432005'
      #       longitude: '13.36469710838366'
      #       address: Steinmetzstraße 79, 10783 Berlin
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
        - '**Kinder**: '
        - 'Dienstag(MELO) und Donnerstag(MELO) 17:00-18:30'
        - 'Freitag(TAM) 16:30-18:00'
        - '**Erwachsene**:'
        - 'Dienstag(KSG) 18:00-19:30, Freitag(MELO) 20:00-21:30'
      autolink: true
    design:
      columns: '2'

  - block: collection
    content:
      title: Veranstaltungen 
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
      title: Neuigkeiten 
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
