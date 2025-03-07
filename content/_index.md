---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: false # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Ukant Jadia
      image:
        filename: final.gif
      cta:
        label: '**Videos**'
        url: https://www.youtube.com/@easyunix
      cta_alt:
        label: Resume
        url: uploads/resume.pdf
      cta_note:
        # label: >-
        #   <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        During my initial college years, I developed an interest in hacking and information security, leading me to set up my own Linux environment with Kali Linux. I learned Linux commands and CLI usage primarily through YouTube and college. My experience includes using Docker for machine learning projects, hosting my website on AWS, and implementing CI/CD pipelines with GitHub Actions. I also completed a Google Cloud Career Path Certificate and an IBM course on Kubernetes and Docker Swarm.

    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true


  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: features
  #   content:
  #     title: Skills
  #     text: ''
  #     # Choose a user to display skills from (a folder name within `content/authors/`)
  #     username: admin
  #   design:
  #     columns: '2'
  - block: features
    content:
      title: Skills
      items:
      - name: Languages
        description: Bash/Shell, Python, C/C++, Dart, Java
        # percent: 75
        icon:   language
        icon_pack: custom
      - name: Frameworks/Library
        description: Flutter, Flask, Django, Regex, Requests
        # percent: 70
        icon: framework
        icon_pack: custom
      - name: Database
        description: MySQL, SQL, Firestore
        # percent: 70
        icon: database
        icon_pack: custom
      - name: Tools/Platform 
        description: Vim, Git, Linux, Docker/Kubernetes, Sed/awk, Jenkins
        # percent: 80
        icon: platform
        icon_pack: custom
      - name: Miscellaneous
        description: AWS(EC2, Lambda, SNS, CloudWatch, S3 ), GCP(Compute Engine, Cloud Functions, Cloud Pub/Sub, Cloud Logging, Cloud Storage)
        # percent: 70
        icon: miscellaneous
        icon_pack: custom

  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        # - title: CEO
        #   company: GenCoin
        #   company_url: ''
        #   company_logo: org-gc
        #   location: California
        #   date_start: '2021-01-01'
        #   date_end: ''
        #   description: |2-
        #       Responsibilities include:

        #       * Analysing
        #       * Modelling
        #       * Deploying
        - title: SWE Intern
          company: Cognus Technology
          company_url: 'https://www.cognustechnology.com/'
          company_logo: ''
          location: Udaipur
          date_start: '2023-05-22'
          date_end: '2022-08-21'
          description: |2-
            * Contributed to live project Gradding using **Flutter**, **Dart**, and **Figma**.
            * Designed intuitive onboarding with **questionnaires** and document uploads, **handling return cases** seamlessly.
            * Conducted in-depth market research on competing applications, analyzing **features** and **identifying gaps** to streamline onboarding app development by **25%**.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: uploads/gcp_cert.pdf
          date_end: '2024-05-19'
          date_start: '2024-02-29'
          description: ''
          icon: custom/ibm
          organization: Google
          organization_url: https://www.cloudskillsboost.google/
          title: 'Career Readiness - Associate Cloud Engineer Path'
          url: 'https://www.cloudskillsboost.google/paths/51'

        - certificate_url: uploads/power_bi.pdf
          date_end: '2024-03-19'
          date_start: '2024-02-29'
          description: ''
          icon: custom/ibm
          organization: _VOIS
          organization_url: https://voisfortech.com/course/
          title: ' Power BI for Data Analysis'
          url: 'https://voisfortech.com/course/index.php?categoryid=60'

        - certificate_url: uploads/automate-python.pdf
          date_end: '2024-01-15'
          date_start: '2023-12-10'
          description: A course by **Al Sweigart**(author) itself, following the pages of book Automate the Boring Stuff with Python Programming
          icon: ''
          organization: Udemy
          organization_url: https://www.udemy.com/
          title: Automate the Boring Stuff with Python Programming
          url: 'https://www.udemy.com/share/101W8U3@zbSFiHh8UbclHI5kbznawusN6OeYACMU5rsrNPOZpAxXkpyuD2yvWdZWYkBU04URpw==/'

        - certificate_url: uploads/docker.pdf
          date_end: '2024-02-19'
          date_start: '2024-01-29'
          description: ''
          icon: custom/ibm
          organization: IBM
          organization_url: https://www.ibm.com/training/
          title: 'Docker Essentials: A Developer Introduction'
          url: 'https://www.ibm.com/training/badge/docker-essentials-a-developer-introduction'

        - certificate_url: uploads/data-science.pdf
          date_end: '2023-02-10'
          date_start: '2023-01-20'
          description: Analyse and interpret the large data and apply Machine learning
          icon_pack: custom
          icon: ibm
          organization: Internshala
          organization_url: https://trainings.internshala.com/
          title: Data Science
          url: https://trainings.internshala.com/data-science-beginner-course/?tracking_source=trainings-search-dropdown
        # - certificate_url: https://www.datacamp.com
        #   date_end: '2020-12-21'
        #   date_start: '2020-07-01'
        #   description: ''
        #   icon: datacamp
        #   organization: DataCamp
        #   organization_url: https://www.datacamp.com
        #   title: 'Object-Oriented Programming in R'
        #   url: ''

    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      count: 5
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 1
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Research Project
          tag: Research Paper
        - name: MLOps
          tag: MLOps
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2' 
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Hey! let's build something together.
      # Contact (add or remove contact options as necessary)
      email: jadia.ukant@gmail.com
      # phone: +91 637 758 1234
      # appointment_url: 'https://calendly.com'
      address:
        street: 25-B Raghunathpura
        city: Udaipur
        region: Raj
        postcode: '313001'
        country: India
        country_code: IN
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '24.6098491'
        longitude: '73.7343402'  
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/ukantjadia'
        # - icon: skype
        #   icon_pack: fab
        #   name: Skype Me
        #   link: 'skype:echo123?call'
        # - icon: video
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: true
    design:
      columns: '2'
---
