---
layout: PageLayout
metaTitle: null
metaDescription: null
addTitleSuffix: true
socialImage: null
metaTags: []
title: Contact Me
sections:
  - type: QuoteSection
    colors: colors-b
    elementId: ''
    quote: |
      Contact
    backgroundImage:
      url: /images/istockphoto-1170264057-612x612.jpg
      opacity: 70
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-12
          - pb-52
          - pl-10
          - pr-10
        justifyContent: center
        margin:
          - mb-0
          - mt-0
          - ml-0
          - mr-0
      quote:
        textAlign: center
      name:
        fontWeight: 500
        textAlign: left
      title:
        fontWeight: 400
        textAlign: left
  - type: HeroSection
    colors: colors-d
    elementId: ''
    backgroundSize: full
    title: Contact Me
    subtitle: This is how you can reach me...
    text: ''
    actions:
      - type: Button
        label: '+918554846522'
        showIcon: true
        icon: arrowRightCircle
        style: primary
        url: ' https://wa.me/+918554846522'
      - type: Button
        altText: ''
        url: 'https://mail.google.com/mail/'
        showIcon: true
        icon: mail
        iconPosition: right
        style: primary
        elementId: ''
        label: vikas.donta@gmail.com
      - type: Button
        label: 'Omkar Apartment, Bhiwandi, Thane, MH'
        altText: ''
        url: 'https://goo.gl/maps/CbaFtU5bpxNzxoQK8'
        showIcon: true
        icon: chevronRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/1565584986HelpDesk Services.jpg
      altText: Hero image
    backgroundImage: null
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-20
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: ContactSection
    colors: colors-d
    elementId: null
    title: Get in Touch
    text: |
      We look forward to hearing from you.

      Start A Project or Schedule a Talk
    form:
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: Phone Number
          hideLabel: false
          placeholder: Phone Number
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: Company Or Organisation
          hideLabel: false
          placeholder: Company Or Organisation
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: full
          type: TextFormControl
        - name: Message
          hideLabel: false
          placeholder: Please describe
          isRequired: true
          width: full
          type: TextareaFormControl
      submitLabel: Send Message
      elementId: sign-up-form
      action: /.netlify/functions/submission_created
      destination: vikas.donta@gmail.com
      styles:
        submitLabel:
          textAlign: center
      type: FormBlock
    media: null
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-0
          - pb-5
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
---
