---
title: Home
sections:
  - type: hero_section
    title: 'Hi, we''re the Northern Beaches Yowies.'
    subtitle: >-
      We provide friendly, local bicycle services and repairs in our Northern
      Beaches workshop. We do build and upgrades and work on all types of bikes.
      Drop by and say hi.
    actions:
      - label: Contact the Yowie
        url: /contact
        style: primary
        has_icon: false
    image: /images/241206879_112137201241683_1366130517113754361_n.jpg
    image_alt: A smiling woman
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
  - type: features_section
    title: We fix bikes
    subtitle: What we do
    features:
      - title: Builds and upgrades
        subtitle: 'You want it, we build it'
        content: "We're top blokes who build top bikes. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus facilisis leo tincidunt venenatis interdum. Phasellus vel lobortis lectus. Curabitur aliquet augue id consectetur ultricies.\_\n\n"
        actions:
          - label: See our handiwork
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: /images/251831158_125451323243604_601207657078724594_n.jpg
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
      - title: High performance services
        subtitle: 'Fast turnaround, competitive prices'
        content: "Local pickup available. Now serving organic lager. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus facilisis leo tincidunt venenatis interdum. Phasellus vel lobortis lectus. Curabitur aliquet augue id consectetur ultricies.\_\n"
        actions:
          - label: Learn about our philosophy
            url: /about
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: /images/244746601_118055210649882_5584727393420042978_n.jpg
        image_alt: Feature 2 illustration
        media_position: right
        media_width: sixty
    feature_padding_vert: large
    align: center
    background_color: none
  - type: grid_section
    title: Testimonials
    subtitle: Yowie's happy customers
    grid_items:
      - content: >
          Just got my bike back from a service by Yowie Bikes. They did a great
          job on my mountain bike which feels much improved. Nice blokes too!


          **Ian Sharples**
        image: images/hanson-deck.png
        image_position: left
        image_width: twenty-five
      - content: >
          Yowie fixed my MTB drivetrain problems & upgraded my rear cassette to
          a massive granny gear. They did a great job.


          **Andrew Pollard**
        image: images/miles-tone.png
        image_position: left
        image_width: twenty-five
      - content: >
          Just got my bike back from a service by Yowie Bikes. They did a great
          job on my mountain bike which feels much improved. Nice blokes too!


          **Ian Sharples**
        image: images/eleanor-carr.png
        image_position: left
        image_width: twenty-five
      - content: >
          Yowie fixed my MTB drivetrain problems & upgraded my rear cassette to
          a massive granny gear. They did a great job.


          **Andrew Pollard**
        image: images/gordon-norman.png
        image_position: left
        image_width: twenty-five
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: large
    align: center
    background_color: secondary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 12
  - type: form_section
    content: |
      ## Let's talk

      If you would like more information about our services, get in touch!
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
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Message
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
      value: /images/yowie-logo.jpg
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
