---
title: About
layout: PageLayout
sections:
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-0
          - pb-4
          - pl-0
          - pr-0
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    colors: colors-d
    variant: variant-a
    title: About Me
    text: >+
      Hello and welcome to my online portfolio. I'm a Software Engineer,
      Full-Stack Developer, Programmer, Graphics Designer and also a freelancer.
      I leaned lot of Python, SQL, R Code, Data Science and ML, AI, DL.


      I have worked on a range of different projects from Data Science, Games,
      Backend, Graphics to Web Design and many more.



      A passionate coder who loves to code and create programs for fun. I
      strongly believes in open data and open source softwares.



      A Software Engineer who is motivated by the belief that
      softwares/applications can make the live easier for people.




      Now I am looking for Full-Stack Carrier for creative and efficient works.

    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-32
          - pb-28
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
    subtitle: Career Objectives
  - type: FeaturedItemsSection
    colors: colors-c
    elementId: ''
    title: Internships
    subtitle: ''
    items:
      - type: FeaturedItem
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
        subtitle: 'Research Teaser Internship – CYBERSECURITY | RESEARCHER '
        title: Research Intern
      - type: FeaturedItem
        title: FOSSEE-Summer-Fellowship-2022
        text: "In this internship I made Python Django Project. I built this project from scratch.\_ In the project I have use Django as Backend for user and manager authentication and Python as Frontend to design the awesome website.\n\n"
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
        subtitle: SOFTWARE INTERN
    actions: []
    columns: 2
    spacingX: 16
    spacingY: 16
    enableHover: false
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
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: ContactSection
    colors: colors-d
    title: Contact Me
    text: |+
      Start A Project or Schedule a Talk

    form:
      type: FormBlock
      elementId: sign-up-form
      destination: vikas.donta@gmail.com
      action: /.netlify/functions/submission_created
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
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: full
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: Submit Form
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
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
---
