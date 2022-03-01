---
title: sign-up2
sections:
  - type: hero_section
    subtitle: THANK YOU FOR JOINING US ON THIS JOURNEY
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
    title: WE'RE BOOTING UP
    background_image: images/Artboard 2-bc16d447.png
    background_image_opacity: 20
    background_image_position: left bottom
  - type: form_section
    content: >
      ## Hello!


      We're extremely glad to have your interest in the platform. Before we give
      you full access to our "Level Up" Mental Health Literacy Training
      Programme" and invite you into the community of other early adopters, we'd
      like to know a little more about you.


      Please complete the adjacent form with details of your favourite games,
      hobbies, and age. **You will then be directed to our training platform and
      asked to create an account with your username and password of choice**.
      This is so you can complete the course at your own pace.


      Due to this being a beta test and not the full roll out, the platform will
      remain live for 30 days before being closed for further development.


      If you have more questions before joining, please visit our [FAQ](/faq)
      page or [email](mailto:team@awfullygood.org) the team.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: sign-up2
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
      - input_type: text
        name: GenderID
        label: What gender do you identify as?
        default_value: lorem-ipsum
        options: []
        is_required: false
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
      - input_type: text
        name: How did you hear about us?
        label: How did you hear about us?
        default_value: 'Google, Word of Mouth etc...'
        options: []
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
    background_image: images/bg-518a39ac.png
seo:
  title: Sign Up for Gamers vs. Depression
  description: >-
    We're stoked that you want to sign up for our mental health literacy
    programme. Please complete the form and you will be redirected to the
    course. 
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Sign Up for Gamers vs. Depression
      keyName: property
    - name: 'og:description'
      value: >-
        We're stoked that you want to sign up for our mental health literacy
        programme. Please complete the form and you will be redirected to the
        course. 
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Sign Up for Gamers vs. Depression
    - name: 'twitter:description'
      value: >-
        We're stoked that you want to sign up for our mental health literacy
        programme. Please complete the form and you will be redirected to the
        course. 
    - name: 'og:image'
      value: images/large_1.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:image'
      value: images/large_1.png
      keyName: property
      relativeUrl: true
layout: advanced
---
