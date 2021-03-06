---
title: Kontaktaufnahme
sections:
  - type: hero_section
    title: Kontakt
    subtitle: Bitte untenstehendes Formular ausfüllen. Ich melde mich!
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >
      ## Preise


      After a short onboarding call I will be able to provide you with ballpark
      pricing, followed by a detailed proposal once we discuss the details.


      ### Vorschläge


      Your proposal will include several choices in terms of pricing structure
      and deliverable timeline.


      ### Rahmenbedingungen


      If at any point you'd like to cancel our project, you are required to
      provide a 30-day written notice, after which I will transfer all of your
      assets to you so you can use them anytime.
    content_align: left
    form_position: left
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - type: form_field
        input_type: text
        name: name
        label: Name
        is_required: true
        default_value: Ihr Vor- & Nachname
      - type: form_field
        input_type: email
        name: email
        label: E-Mail
        default_value: Ihre E-Mail Adresse
        is_required: true
      - type: form_field
        input_type: textarea
        name: message
        label: Nachricht
        default_value: Ihre Nachricht an mich
      - type: form_field
        input_type: checkbox
        name: consent
        label: >-
          Ich verstehe, dass dieses Formular meine übermittelten Informationen
          speichert, damit ich kontaktiert werden kann.
        is_required: true
    submit_label: Senden
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_opacity: 8
    background_image_size: contain
    background_image_repeat: repeat
seo:
  type: stackbit_page_meta
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
template: advanced
---
