---
layout: PostFeedLayout
title: My Work
numOfPostsPerPage: 10
postFeed:
  showDate: true
  showAuthor: true
  showExcerpt: true
  showReadMoreLink: true
  readMoreLinkLabel: Learn More
  variant: variant-c
  colors: colors-d
  styles:
    self:
      width: narrow
      padding:
        - pt-0
        - pl-4
        - pr-4
        - pb-12
styles:
  title:
    textAlign: center
bottomSections:
  - colors: colors-d
    elementId: ''
    images:
      - type: ImageBlock
        url: /images/gallery-1.jpg
        altText: Image one
        caption: Image one caption
      - type: ImageBlock
        url: /images/gallery-2.jpg
        altText: Image two
        caption: Image two caption
      - type: ImageBlock
        url: /images/gallery-3.jpg
        altText: Image three
        caption: Image three caption
      - type: ImageBlock
        url: /images/gallery-4.jpg
        altText: Image four
        caption: Image four caption
    spacing: 16
    columns: 4
    aspectRatio: '4:3'
    showCaption: false
    enableHover: false
    styles:
      self:
        height: auto
        width: full
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-4
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
    type: MediaGallerySection
  - type: ContactSection
    colors: colors-d
    elementId: null
    backgroundSize: null
    title: Contact With Me
    text: |+
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
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: Submit
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
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
addTitleSuffix: true
---
