---
title: sign-up
sections:
  - type: hero_section
    subtitle: THANK YOU FOR JOINING OUR PRIVATE BETA WAITING LIST
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
    title: WE'RE BOOTING UP
    background_image: images/304.jpg
    background_image_opacity: 20
    background_image_position: right top
  - type: form_section
    content: >
      ## Hello!


      We're extremely glad to have your interest in the platform. Before we give
      you full access to our "Level Up: Mental Health Literacy Training
      Programme" and invite you into the community of other early adopters, we'd
      like to know a little more about you. Please complete the adjacent form
      with details of your favourite games, hobbies, and age. **We hope to
      release the first round of invites in January 2022.**


      ## Requirements to join


      Please note, Gamers vs. Depression is for young men aged 16 to 24.


      ## Why just young men?


      It's not that we don't want to work with those of your from other
      demographics, but in order for members to feel comfortable in discussing
      personal topics, we feel it is important that they are able to communicate
      with peers. We hope to roll out similarly focused communities for other
      demographics in the future once we establish a proof of concept. Please
      sign up to our newsletter for our latest posts and advice.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: number
        name: age
        label: Age
        default_value: Add your age here
        options: []
        is_required: true
      - input_type: textarea
        name: Games
        label: Top Three Games of All Time
        default_value: Add your games here
      - input_type: select
        name: MH
        label: Experience of Mental Health Disorders
        default_value: Select from the drop down menu
        options:
          - 'Yes, me.'
          - 'Yes, other.'
          - I'm just here to support a friend.
          - Other
        is_required: false
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Sign Me Up
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: none
    background_image_opacity: 20
seo:
  title: General Enquiries
  description: This is the general enquiries page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: General Enquiries
      keyName: property
    - name: 'og:description'
      value: This is the general enquiries page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: General Enquiries
    - name: 'twitter:description'
      value: This is the general enquiries page
layout: advanced
---
