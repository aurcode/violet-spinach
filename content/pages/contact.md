---
title: Contacto
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      ¿Tiene alguna pregunta, comentario o sugerencia? Rellene este formulario
      de contacto y me pondré en contacto con usted en breve.




      aurelio3927@gmail.com
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre *
        is_required: true
      - input_type: email
        name: email
        is_required: true
        label: Correo electrónico *
      - input_type: textarea
        name: message
        label: Mensaje *
        is_required: true
    submit_label: Enviar
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
