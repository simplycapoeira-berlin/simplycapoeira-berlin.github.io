---
title: Contact
date: 2024-08-06

type: landing


sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Kontaktiert uns bei Fragen rund um den Verein
        gerne **per EMail**:
      email: sc-capo-berlin@t-online.de
      # phone: 888 888 88 88
      autolink: true
      # address:
      #   name: 
      #   street: Simplesmente Capoeira Berlin e. V., z. Hd. Herrn Mert Ögüt, Gélieustraße 6a, 12203 Berlin
      #   # city: Berlin 
      #   # postcode: '10783'
      #   country: Germany
      #   country_code: DE
    
    design:
      columns: '2'

  - block: markdown 
    content:
      title: Bankverbindung / Spenden
      text: |-
        Mitgliedsbeiträge und Spenden bitte auf untenstehendes Konto überweisen.

        Wir freuen uns über jede Spende, falls ihr eine Spendenquittung benötigt, bitte kontaktiert uns.
        
        **Inhaber**: Simplesmente Capoeira Berlin e.V.

        **IBAN**: DE38 8306 5408 **0005 3604 55**

        **ODER** direkt über PayPal
        <form action="https://www.paypal.com/donate" method="post" target="_top">
        <input type="hidden" name="hosted_button_id" value="TBH2HYEQQGSH8" />
        <input type="image" src="https://www.paypalobjects.com/de_DE/DE/i/btn/btn_donate_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Spenden mit dem PayPal-Button" />
        <img alt="" border="0" src="https://www.paypal.com/de_DE/i/scr/pixel.gif" width="1" height="1" />
        </form>
    design:
      columns: '2'

  - block: contact
    content:
      title: Webdesign und Programmierung 
      text: |-
        Pascal Klamser
      email: sc-capo-berlin@t-online.de
      autolink: true
    design:
      columns: '2'

  - block: markdown 
    content:
      title: Rechtshinweis 
      text: |-
        Alle in unseren Internetseiten enthaltenen Angaben und Informationen wurden von Simplesmente Capoeira Berlin e.V. sorgfältig recherchiert und geprüft. Diese Informationen sind ein Service des Verbandes. Für Richtigkeit, Vollständigkeit und Aktualität können weder der Simplesmente Capoeira Berlin e.V. noch externe Dienstleister die Haftung übernehmen.

        Alle Informationen dienen ausschließlich zur Information der Besucher des Onlineangebotes. Im Übrigen ist die Haftung auf Vorsatz und grobe Fahrlässigkeit beschränkt. Für Internetseiten Dritter, auf die der Simplesmente Capoeira Berlin e.V. durch Hyperlink verweist, tragen die jeweiligen Anbieter die Verantwortung. Der Simplesmente Capoeira Berlin e.V. ist für den Inhalt solcher Seiten Dritter nicht verantwortlich.

        Des Weiteren kann die Web-Seite des Simplesmente Capoeira Berlin e.V. ohne dessen Wissen von einer anderen Seite mittels Hyperlink verlinkt worden sein. Der Simplesmente Capoeira Berlin e.V. übernimmt keine Verantwortung für Darstellung, Inhalt oder irgendeiner Verbindung des Simplesmente Capoeiraes Berlin e.V. in Web-Seiten Dritter.

        Außerdem behält sich der Simplesmente Capoeira Berlin e.V. das Recht vor, Änderungen oder Ergänzungen der bereitgestellten Informationen vorzunehmen.
    design:
      columns: '1'

  - block: markdown 
    content:
      title: Urheberrechtlicher Hinweis 
      text: |-
        Inhalte - ganz gleich ob eigene Inhalte des Simplesmente Capoeira Berlin e.V. oder Verweise auf Inhalte Dritter - sowie die Struktur der Internet-Seiten des Simplesmente Capoeira Berlin e.V. sind urheberrechtlich geschützt. Die Vervielfältigung von Informationen oder Daten, insbesondere die Verwendung von Texten, Textteilen, Bildmaterial oder sonstigen Inhalten bedarf grundsätzlich der vorherigen Zustimmung durch den Simplesmente Capoeira Berlin e.V. bzw. die Rechteinhaber (Dritter).

        Dies gilt nicht für solche Inhalte, die auf den Seiten des Simplesmente Capoeira Berlin e.V. frei zugänglich sind und zur kostenfreien Nutzung übernommen werden. Pressemitteilungen, News sowie Pressefotos des Simplesmente Capoeira Berlin e.V. dürfen explizit zu redaktionellen Zwecken genutzt werden. Der Nutzer hat sicherzustellen, dass die Quellen- und Urheberangaben des jeweiligen Materials vollständig und korrekt übernommen werden.

    design:
      columns: '1'

# NOTE: below I tried a video wrapping (ordering them in a grid) works nicely (module is defined in assets/scss/template.scss)
#  - block: markdown 
#    content:
#      title: videos 
#      text: |-
#        test
#        <div class="videowrapper">
#          {{< youtube id="YdjzNCgzTjU" class="video" >}}
#          {{< youtube id="6zeRtOSGpAI" class="video" >}}
#          {{< youtube id="YdjzNCgzTjU" class="video" >}}
#          {{< youtube id="YdjzNCgzTjU" class="video" >}}
#          {{< youtube id="YdjzNCgzTjU" class="video" >}}
#          {{< youtube id="YdjzNCgzTjU" class="video" >}}
#          {{< youtube id="YdjzNCgzTjU" class="video" >}}
#          {{< youtube id="YdjzNCgzTjU" class="video" >}}
#          {{< youtube id="YdjzNCgzTjU" class="video" >}}
#        </div>

  # NOTE: below is the template with a map-function
  # - block: contact
  #   content:
  #     title: Training Location at MELO 
  #     text: |-
  #       Join us at the training, guests are always welcome!
  #     address:
  #       street: Steinmetzstraße 79, 10783 Berlin
  #       # city: Berlin 
  #       # postcode: '10783'
  #       country: Germany
  #       country_code: DE
  #     coordinates:
  #       latitude: '52.499238779432005'
  #       longitude: '13.36469710838366'
  #     directions: small gym on the upper floor
  #     office_hours:
  #       - 'Kids: Tuesday and Thursday 17:00 to 18:30'
  #       - 'Adults: Friday 20:00 to 21:30'
  #     # appointment_url: 'https://calendly.com'
  #     #contact_links:
  #     #  - icon: comments
  #     #    icon_pack: fas
  #     #    name: Discuss on Forum
  #     #    link: 'https://discourse.gohugo.io'
  #   
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #   
  #     # # Email form provider
  #     # form:
  #     #   provider: netlify
  #     #   formspree:
  #     #     id:
  #     #   netlify:
  #     #     # Enable CAPTCHA challenge to reduce spam?
  #     #     captcha: false
  #   design:
  #     columns: '2'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: contact.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen
---