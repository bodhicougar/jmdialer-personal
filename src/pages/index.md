---
title: Start
sections:
  - media_position: right
    image_alt: Mein Kepfl
    align: left
    padding_top: large
    background_image: /images/Logo.jpg
    media_width: sixty
    background_image_repeat: repeat
    background_color: primary
    video_embed_html: >-
      <iframe width="560" height="315"
      src="https://www.youtube-nocookie.com/embed/s6pNswIMOak" title="YouTube
      video player" frameborder="0" allow="accelerometer; autoplay;
      clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen></iframe>
    background_image_size: contain
    background_image_opacity: 8
    subtitle: Hier stelle ich meinen Schaffenszyklus vor.
    title: 'Griaß enk, I bin''s, euer Naggi!'
    content: |
      Kontaktaufnahme: Kontakt Schalter klicken

      Panorama meines Ateliers: Panorama Schalter klicken
    padding_bottom: large
    type: hero_section
    image: /images/Kepfl.jpg
    actions:
      - type: action
        url: /contact
        style: primary
        label: Kontakt
      - label: Panorama
        url: 'https://atelier.blackboxmd.fyi/'
        style: primary
        has_icon: false
        icon: arrow-left
        icon_position: center
        new_window: true
        no_follow: false
        type: action
  - type: grid_section
    title: Mit einem Klick zum Panorama meines Ateliers.
    subtitle: Panorama
    grid_items:
      - type: grid_item
        image: images/logo-1.svg
        image_alt: Logo 1
        image_align: center
      - type: grid_item
        image: images/logo-2.svg
        image_alt: Logo 2
        image_align: center
      - type: grid_item
        image: images/logo-3.svg
        image_alt: Logo 3
        image_align: center
      - type: grid_item
        image: images/logo-4.svg
        image_alt: Logo 4
        image_align: center
      - type: grid_item
        image: images/logo-5.svg
        image_alt: Logo 5
        image_align: center
      - type: grid_item
        image: images/logo-6.svg
        image_alt: Logo 6
        image_align: center
      - type: grid_item
        image: images/logo-7.svg
        image_alt: Logo 7
        image_align: center
      - type: grid_item
        image: images/logo-8.svg
        image_alt: Logo 8
        image_align: center
    grid_cols: four
    grid_gap_vert: medium
    grid_gap_horiz: medium
    align: center
    actions: []
  - type: features_section
    title: Mein Schaffenszyklus
    subtitle: Was ich mache
    features:
      - media_position: right
        image_alt: Feature 1 illustration
        media_width: sixty
        subtitle: 'Website, blog, social media and more.'
        title: Content Creation
        content: >-
          I will handle content writing for your digital assets, from
          newsletters and emails, to Facebook and Google campaigns, whitepapers,
          case studies and product descriptions. No job is too big or small!
        type: feature
        image: images/feature-1.svg
        actions:
          - type: action
            label: See Writing Samples
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
      - media_position: right
        image_alt: Feature 2 illustration
        media_width: sixty
        subtitle: 'Product updates, inventory and pricing.'
        title: Online Store Management
        content: >-
          Managing an online business is a full-time job. I will make sure your
          products look great, sound great, and sell more on your choice of
          ecommerce platform.
        type: feature
        image: images/feature-2.svg
        actions:
          - type: action
            label: Learn More
            url: /about
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
      - media_position: right
        image_alt: Feature 3 illustration
        media_width: sixty
        subtitle: 'Your products and services, at scale.'
        title: Technical Content
        content: >-
          I will dive into the ins and outs of your product or service and make
          sure the right information is communicated throughout your
          documentation, pamphlets, manuals and technical documents.
        type: feature
        image: images/feature-3.svg
        actions:
          - type: action
            label: See Past Work
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
    feature_padding_vert: large
    align: center
    background_color: none
  - align: center
    grid_items:
      - type: grid_item
        content: >-
          Alyvia is an amazing content writer. She helped us produce microcopy
          for our apps in all levels of user touchpoints.


          **Hanson Deck,** *App Developer, Studio*
        image: images/hanson-deck.png
        image_position: left
        image_width: twenty-five
      - type: grid_item
        content: >-
          Alyvia really understands who our customers are and what tone of voice
          to use when communicating with them.


          **Miles Tone,** *CEO, Studio*
        image: images/miles-tone.png
        image_position: left
        image_width: twenty-five
      - type: grid_item
        content: >-
          Working with Alyvia was great because she was well versed in all of
          our tools and applications, and was able to manage our store and
          campaigns without any technical glitches.


          **Eleanor Carr,** *CTO, eCommerce Business*
        image: images/eleanor-carr.png
        image_position: left
        image_width: twenty-five
      - type: grid_item
        content: >-
          I love it when a content writer can really wordsmith and create copy
          that suits the design intention and style!


          **Gordon Norman,** *Web Designer, Local Business*
        image: images/gordon-norman.png
        image_position: left
        image_width: twenty-five
    background_image: images/watercolor.png
    grid_cols: two
    background_image_repeat: repeat
    background_color: secondary
    grid_gap_vert: large
    background_image_size: contain
    background_image_opacity: 12
    subtitle: What My Clients Say
    title: Testimonials
    grid_gap_horiz: medium
    type: grid_section
  - form_position: left
    form_layout: stacked
    padding_top: medium
    background_image: images/watercolor.png
    align_vert: top
    form_width: fifty
    enable_card: true
    submit_label: Senden
    background_image_repeat: repeat
    form_action: /thank-you
    background_color: primary
    form_fields:
      - type: form_field
        input_type: text
        name: name
        label: Name
        default_value: Ihr Vor- & Nachname
        is_required: true
      - type: form_field
        input_type: email
        name: E-Mail
        label: E-Mail
        default_value: Ihre E-Mail Adresse
        is_required: true
      - type: form_field
        input_type: textarea
        name: Nachricht
        label: Nachricht
        default_value: Ihre Nachricht an mich
      - type: form_field
        input_type: checkbox
        name: consent
        label: >-
          Ich verstehe, dass dieses Formular meine übermittelten Informationen
          speichert, damit ich kontaktiert werden kann.
        is_required: true
    background_image_size: contain
    form_id: contact-form
    background_image_opacity: 8
    content: >
      ## Kommunikation mit mir


      If you would like more information about my services and pricing, please
      contact me using the form below.
    padding_bottom: medium
    type: form_section
    content_align: left
seo:
  type: stackbit_page_meta
  title: Jörg M. Dialer - Diplom Malermeister
  description: Der gute Geist von Büchsenhausen stellt sich vor.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Personal Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Personal theme
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Personal Theme
    - name: 'twitter:description'
      value: The preview of the Personal theme
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
template: advanced
---
