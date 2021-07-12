---
title: Contacto
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      ¿Tiene alguna pregunta, comentario o sugerencia? Rellene este formulario
      de contacto y me pondré en contacto con usted en breve.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: Tu nombre
        is_required: true
      - input_type: email
        name: email
        default_value: Your email address
        is_required: true
        label: correo electrónico
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
    submit_label: Send Message
seo:
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
layout: advanced
---
