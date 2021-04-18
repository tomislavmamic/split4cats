---
title: Home
sections:
  - type: hero_section
    title: Gradske mačke žive naglavačke
    subtitle: >-
      Prosječna ulična mačka u Splitu živi kraće od godinu dana i cijeli život
      pati od strašnih bolesti.
    actions:
      - label: Uključi se
        url: /contact
        style: primary
    image: images/hero2.png
    image_alt: sterilizacija je važnija
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: secondary
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
  - type: features_section
    title: Problemi uličnih mačaka
    subtitle: Što mi radimo
    features:
      - title: Bolesti
        subtitle: 30% splitskih mačaka ima mačju sidu
        content: >
          Veliki broj mačaka omogućava lako širenje bolesti. Zbog toga velik
          broj mačaka boluje od različitih bolesti i pate tijekom cijelog svog
          života.
        actions:
          - label: See Writing Samples
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/hero.jpg
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
      - title: Glad i trovanje
        subtitle: Svaka mačka prolazi kroz glad i trovanje
        content: >
          Mačke u gradu jedu ljudske otpatke. Za razliku od divljih mačaka, nisu
          navikle loviti svoju hranu i zbog toga biraju između rizika od
          trovanja ili konstantne gladi.
        actions:
          - label: Learn More
            url: /about
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/problem1.jpg
        image_alt: Feature 2 illustration
        media_position: right
        media_width: sixty
      - title: Kratak i težak život
        subtitle: Godišnje se promijeni >50% populacije
        content: >
          Grad je opasno mjesto za život. Mačka koja se okoti u Splitu
          najvjerojatnije neće preživjeti prvu godinu života. Svoj kratki život
          će većinu vremena biti bolesna, gladna ili ozlijeđena, a umrijet će
          strašnom smrću.
        actions:
          - label: See Past Work
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/problem2.jpg
        image_alt: Feature 3 illustration
        media_position: right
        media_width: sixty
    feature_padding_vert: large
    align: center
    background_color: none
  - type: form_section
    content: |+
      ## Kontaktiraj nas

    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Ime
        default_value: Tvoje ime i prezime
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Tvoja email adresa
        is_required: true
      - input_type: textarea
        name: message
        label: akuroP
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Stackbit Personal Theme
  description: The preview of the Personal theme
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
layout: advanced
---
