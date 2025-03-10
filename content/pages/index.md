---
type: PageLayout
title: Home
colors: colors-e
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-b
    backgroundSize: full
    title: 'Jivesh Dahiya | Digital Creator, Designer & Entrepreneur'
    subtitle: "I am a multi-skilled digital creator with expertise in graphic design, video editing, SEO, and social media management. A national-level karate champion, state-level chess player, and academic topper, I bring the same dedication and discipline to my creative work. Passionate about building brands, optimizing digital presence, and creating impactful designs, I aim to grow businesses through innovative content strategies. With a strong technical background in cybersecurity, branding, and project management, I am continuously evolving and pushing boundaries. Currently, I am on a journey to establish my own brand, YouTube channel, and freelancing business, with the ultimate goal of achieving financial freedom and making my mother proud. \U0001F680Let’s connect and build something extraordinary! \U0001F4A1"
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: center
        textDecoration: underline
        fontWeight: 400
      subtitle:
        textAlign: left
        fontWeight: 400
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: wide
        padding:
          - pt-1
          - pb-1
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 4
        borderStyle: solid
  - type: LabelsSection
    title: Skills
    subtitle: 'Skills I have :'
    items:
      - type: Label
        label: Social Media Marketing
        url: ''
      - type: Label
        label: Graphic Designing
        url: ''
      - type: Label
        label: Video Editing
        url: ''
      - type: Label
        label: You Tube Growth
        url: ''
      - type: Label
        label: SEO Professional
        url: ''
      - type: Label
        label: Team Building
        url: ''
      - type: Label
        label: Advanced Computer Skills
        url: ''
      - type: Label
        label: Digital Marketing
        url: ''
      - type: Label
        label: Many More...
        url: ''
    colors: colors-d
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: narrow
        padding:
          - pt-1
          - pb-1
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-b
    variant: variant-a
    subtitle: Work Samples
    showFeaturedImage: false
    actions:
      - type: Button
        label: Logo Samples
        altText: ''
        url: >-
          https://drive.google.com/drive/folders/1NiOWIa7EtPf_mLzA2RHA2N0Oy6R5IEAI?usp=drive_link
        showIcon: true
        icon: arrowRight
        iconPosition: left
        style: primary
        elementId: ''
      - type: Button
        label: Thumbnails Designs
        altText: ''
        url: /Thumbnail Designs
        showIcon: false
        icon: arrowRight
        iconPosition: left
        style: primary
        elementId: ''
      - type: Button
        label: Banner Samples
        altText: ''
        url: >-
          https://drive.google.com/drive/folders/1HGwHb3TjCDQIJzUIWk8zJlHEDjqJoBzi?usp=drive_link
        showIcon: false
        icon: arrowRight
        iconPosition: left
        style: primary
        elementId: ''
      - type: Button
        label: Join us for FREE!
        altText: ''
        url: /Join us
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    posts: []
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
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
          - pt-28
          - pb-48
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
        justifyContent: flex-end
    title: Work Samples
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: narrow
        padding:
          - pt-1
          - pb-1
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
  - colors: colors-b
    type: FeaturedProjectsSection
    elementId: ''
    actions: []
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: More Information..
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: narrow
        padding:
          - pt-1
          - pb-1
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
  - type: ContactSection
    title: Contact Me
    text: I'm look forward to hearing from you.
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: false
          placeholder: Your name
          width: 1/2
          isRequired: true
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: false
          placeholder: Your email
          width: 1/2
          isRequired: true
        - type: TextareaFormControl
          name: message
          label: Tell me about your project
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
          isRequired: 'false'
      submitLabel: Send Message
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    media:
      type: ImageBlock
      url: /images/contact.jpg
      altText: Contact form image
      caption: Caption of the image
      elementId: ''
    colors: colors-d
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
