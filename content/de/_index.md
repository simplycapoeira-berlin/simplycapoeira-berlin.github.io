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
      title: Trainingsort in der MELO
      text: |-
        Kommt zu unserem Training, Gäste sind immer willkommen! Zur Zeit bieten wir eine Trainingseinheit für Erwachsene und zwei Trainingseinheiten für Kinder/Jugendliche in der Gymnastikhalle der MELO (Marie-Elisabeth-Lüders-Oberschule) an.
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
        - 'Kinder: Dienstag und Donnerstag 17:00 to 18:30'
        - 'Erwachsene: Freitag 20:00 to 21:30'
      autolink: true
    design:
      columns: '2'

  - block: collection
    content:
      title: Bevorstehende Veranstaltungen 
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
