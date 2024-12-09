---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Here to build your web desires to life
      color: text-dark
      type: TitleBlock
    subtitle: Web development
    text: >+

      We turn your website ideas into reality. Our team of skilled designers and
      developers will bring your vision to life, creating a stunning and
      functional online presence.

    actions:
      - label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
    media:
      url: /images/main-hero.svg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: "Logaxis\_ Designs"
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - type: FeaturedItemsSection
    title:
      text: Service's
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Static Websites
        subtitle: Basic informative site
        text: >
          A static website is like a digital brochure. It has fixed pages that
          don't change automatically. Perfect for simple, informational sites.


          **Benefits:**


          *   **Speed:** Loads quickly.


          *   **Security:** Fewer vulnerabilities.


          *   **Cost-Effective:** Affordable.


          **Starting Price:**


          A basic static website starts at R300.


          **Ready to get started?** Let's discuss your project.
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - title: Web Applications
        subtitle: Website where you can perform actions on
        text: >+
          A web application is like a dynamic online tool. It can change and
          update itself, providing interactive features like user accounts,
          databases, and real-time content.


          **Why Choose a Web Application?**


          *   **Flexibility:** Highly customizable.


          *   **Interactivity:** Engage users with dynamic features.


          *   **Scalability:** Grow with your business needs.


          **Pricing**


          The cost of a web application depends on its specific functionality
          and complexity. Let's discuss your project to get a tailored quote.


          **Ready to build your web application?** Contact us today.



        image:
          url: /images/icon2.svg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Mobile Apps
        subtitle: The world is yours
        text: >+
          A mobile app is a software application designed to run on smartphones
          and tablets. It offers a personalized user experience, tailored to
          mobile devices.


          **Why Choose a Mobile App?**


          *   **Portability:** Accessible anytime, anywhere.


          *   **Engagement:** Direct connection with your audience.


          *   **Brand Awareness:** Enhance brand visibility and recognition.


          **Pricing**


          The cost of a mobile app depends on factors like platform (iOS,
          Android, or both), complexity, features, and design. Let's discuss
          your project to get a tailored quote.


          **Ready to take your business mobile?** Contact us today.



        image:
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions:
      - label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    badge:
      label: our Offering
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Google Search Optimizations
      color: text-dark
      type: TitleBlock
    subtitle: Be the top search in your field
    text: >+
      SEO, or Search Engine Optimization, is the process of improving your
      website's visibility on search engines like Google. By optimizing your
      website's content<sup> 1 </sup> and structure, you can attract more
      organic traffic

    actions: []
    media:
      url: /images/hero3.svg
      altText: Dope design preview
      type: ImageBlock
    badge:
      label: service
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
    type: GenericSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Consultation on our services
      color: text-dark
      type: TitleBlock
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
