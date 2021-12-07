---
title: Nous contacter
img_path: images/contact-b3bee6cd.png
form_id: contactForm
form_action: /success
form_fields:
  - input_type: text
    name: name
    label: Nom
    default_value: Votre nom
    is_required: true
  - input_type: email
    name: email
    label: Email
    default_value: Votre adresse email
    is_required: true
  - input_type: select
    name: Sujet
    label: Sujet
    default_value: Please select
    options:
      - Error on the site
      - Sponsorship
      - Other
  - input_type: textarea
    name: message
    label: Message
    default_value: Votre message
  - input_type: checkbox
    name: consent
    label: >-
      En cochant cette case et en remplissant ce formulaire, vous acceptez
      d'être contacté.
submit_label: Envoyer
seo:
  title: Get in Touch
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Get in Touch
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'og:image'
      value: images/contact.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Get in Touch
    - name: 'twitter:description'
      value: This is the contact page
    - name: 'twitter:image'
      value: images/contact.jpg
      relativeUrl: true
layout: contact
---
Pour nous contacter, veuillez remplir le formulaire ci-dessous.
