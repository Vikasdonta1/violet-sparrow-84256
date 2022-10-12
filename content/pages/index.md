---
title: Home
layout: PageLayout
sections:
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-0
          - pb-6
          - pl-0
          - pr-0
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: HeroSection
    colors: colors-d
    elementId: ''
    backgroundSize: full
    title: Welcome to My Portfolio Website.
    subtitle: Software Engineer. Creative. Learner.
    text: ''
    actions:
      - type: Button
        label: Connect
        showIcon: true
        icon: arrowRight
        style: secondary
        url: /contact-me
      - type: Link
        altText: ''
        url: ' https://wa.me/+918554846522'
        showIcon: true
        icon: send
        iconPosition: right
        elementId: ''
      - type: Link
        altText: ''
        url: 'https://www.linkedin.com/in/vikas-donta/'
        showIcon: true
        icon: linkedin
        iconPosition: right
        elementId: ''
      - type: Link
        altText: ''
        url: 'https://github.com/Vikasdonta1'
        showIcon: true
        icon: github
        iconPosition: right
        elementId: ''
      - type: Link
        altText: ''
        url: vikas.donta@gmail.com
        showIcon: true
        icon: mail
        iconPosition: right
        elementId: ''
    media:
      type: ImageBlock
      url: /images/ezgif.com-gif-maker (1).png
      altText: Hero image
    backgroundImage: null
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
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
  - type: QuoteSection
    colors: colors-c
    quote: >+
      ### I'm a Software Engineer, Full-Stack Developer, Programmer, Graphics
      Designer and also a Freelancer.

    name: >-
      I leaned lot of Python, SQL, R Code, Data Science and ML, AI, DL.      Now
      I am looking for Full-Stack Carrier for creative and efficient works.
    title: '                    I have worked on a range of different projects from Data Science, Games, Backend, Graphics to Web Design and many more.'
    styles:
      self:
        height: auto
        width: full
        padding:
          - pt-20
          - pb-20
          - pr-10
          - pl-10
        justifyContent: center
        margin:
          - mt-4
          - ml-0
          - mb-0
          - mr-0
      quote:
        textAlign: center
      name:
        textAlign: center
      title:
        textAlign: center
  - type: FeaturedItemsSection
    colors: colors-d
    elementId: ''
    title: Internship
    subtitle: ''
    items:
      - type: FeaturedItem
        title: RESEARCH
        text: >+
          The Project that Interns work mainly focus upon Software Defined
          Network 

          (SDN), Internet of Things (IoT), and Blockchain Technology. All of
          these are 

          cutting edge and have attracted both Industry and Academia.

        actions:
          - type: Button
            label: Learn more
            showIcon: true
            icon: arrowRight
            url: /internship/research
            style: secondary
        styles:
          self:
            textAlign: left
            borderColor: border-secondary
            borderStyle: double
        subtitle: 'Research Teaser Internship – CYBERSECURITY | RESEARCHER '
      - type: FeaturedItem
        title: FOSSEE-Summer-Fellowship-2022
        text: "In this internship I made Python Django Project. I built this project from scratch.\_ In the project I have use Django as Backend for user and manager authentication and Python as Frontend to design the awesome website.\n"
        actions:
          - type: Button
            label: Learn more
            showIcon: true
            icon: arrowRight
            url: /internship/internship
            style: secondary
        styles:
          self:
            textAlign: left
            borderColor: border-secondary
            borderStyle: solid
        subtitle: SOFTWARE INTERNSHIP
    actions: []
    columns: 2
    spacingX: 16
    spacingY: 16
    enableHover: true
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
        borderColor: border-secondary
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
  - elementId: ''
    colors: colors-c
    variant: variant-a
    title: Recent Projects
    actions:
      - type: Link
        label: See all Projects
        url: /blog
        showIcon: true
        icon: arrowRight
    posts:
      - content/pages/blog/post-five.md
      - content/pages/blog/post-four.md
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
          - pt-11
          - pb-11
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: FeaturedPostsSection
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    readMoreLinkLabel: Read More
    showAuthor: false
  - type: HeroSection
    colors: colors-d
    elementId: ''
    backgroundSize: full
    title: Certifications
    subtitle: View All My Couse Certificate Accomplisments
    text: ''
    actions:
      - type: Button
        label: Click Me
        showIcon: true
        icon: arrowRightCircle
        style: primary
        url: /certificate
    media:
      type: ImageBlock
      url: /images/Blank-Retirement-Certificate-Template.png
      altText: Hero image
    backgroundImage: null
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-20
          - pb-20
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
  - type: FeaturedItemsSection
    colors: colors-c
    elementId: ''
    title: Education
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Indala College Mumbai University
        text: |+
          Currently Pursuing B.E. in Computer Engineering ( Third Year)

        actions:
          - type: Button
            label: More About
            showIcon: true
            icon: arrowRight
            url: /edu/Indala
            style: secondary
        styles:
          self:
            textAlign: left
        subtitle: B.E.IN COMPUTER ENGINEERING
      - type: FeaturedItem
        title: DR. D. Y. Patil  Pune University
        text: |
          Completed Three Years Of Diploma in Computer Engineering
        actions:
          - type: Button
            label: More About
            showIcon: true
            icon: arrowRight
            url: /edu/diploma
            style: secondary
        styles:
          self:
            textAlign: left
        subtitle: DIPLOMA IN COMPUTER ENGINEERING
    actions: []
    columns: 1
    spacingX: 16
    spacingY: 16
    enableHover: false
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-11
          - pb-11
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: ContactSection
    colors: colors-d
    elementId: ''
    backgroundSize: full
    title: Get in Touch
    text: We look forward to hearing from you.
    form:
      fields:
        - name: name
          label: Name
          placeholder: Your name
          isRequired: 'true'
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          placeholder: Your email
          isRequired: 'true'
          width: 1/2
          type: EmailFormControl
        - name: address
          placeholder: Your Message
          isRequired: 'false'
          width: full
          type: TextFormControl
      submitLabel: Send Message
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: ''
      type: FormBlock
    media:
      url: /images/1565584986HelpDesk Services.jpg
      altText: Contact form image
      type: ImageBlock
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-9
          - pb-9
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-4
          - pb-4
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
addTitleSuffix: true
metaTags: []
metaTitle: Vikas
socialImage: /images/1565584986HelpDesk Services.jpg
---
