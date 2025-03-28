---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  - block: experience
    id : experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Graduate Student Assistant
          company: University of Buffalo
          company_url: ''
          company_logo: ''
          location: Buffalo, NY, USA
          date_start: '2024-08-20'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Working on improving training and inference time  of CNNs and generative models in general under Prof. [Nalini K Ratha](https://nalini-ratha.github.io/).

        - title: MITACS Research Intern
          company: University of Alberta/SuperGeo AI
          company_url: 'https://sga.ai/'
          company_logo: 'University-of-Alberta'
          location: Edmonton, Canada
          date_start: '2023-05-18'
          date_end: '2023-08-10'
          description: |2-
              Responsibilities include:

              * Wheat and Canola plants data Collection and Annotation.
              * Developing Object Detection models such as Efficient-Det and Yolov8 for accurate detection. Mentors: [Prof. Li Cheng](https://vision-and-learning-lab-ualberta.github.io/author/li-cheng/) and [Dr. Weiping Zeng](https://www.linkedin.com/in/weiping-zeng-3747a738/?originalSubdomain=ca)
              * Deploying on company's demo website for real-time usage.

        - title: Research Intern
          company: Indian Institute of Technology, Guwahati
          company_url: ''
          company_logo: ''
          location: Guwahati, India
          date_start: '2022-05-01'
          date_end: '2023-01-31'
          description: |2-
            Responsibilites include:
            * Creating an extensive literature survey on work done in MOS like analyzing SOTA models like Referformer, MTTR etc.
            * Incorporating temporal information between relatively important frames into RefVos along with encoder-decoder structures for feature retrieval. Mentors: [Dr. Santosh K Vipparthi](https://visionintelligence.github.io/People.html) and [Dr. R. Balasubramanian](https://faculty.iitr.ac.in/cs/bala/)

        # - title: ABU-Robocon'22
        #   company: Indian Institute of Technology, Jodhpur
        #   company_url: ''
        #   company_logo: ''
        #   location: Jodhpur, India
        #   date_start: '2021-11-01'
        #   date_end: '2022-04-30'
        #   description: |2-
        #     Responsibilites include:
            
        #     * Developing the software using ROS for autonomous control of robots.
        #     * Integrating Object Detection AI models like DETR with ROS.
    design:
      columns: '2'

  - block: collection
    id: featured
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: compact

  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Machine/Deep Learning
          tag: Research Projects
        - name: Robotics
          tag: Robotics
        - name: Computer Vision
          tag: CV
        - name: Course Project
          tag: Coursework
        - name: Web-Development
          tag: WebDev

    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: compact
      # For Showcase view, flip alternate rows?
      # flip_alt_rows: false
  - block: accomplishments
    id: accomplishment
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: '2023-08-10'
          date_start: '2023-05-18'
          description: 'Awarded the MITACS scholarship for onsite research internship at University of Alberta'
          organization: MITACS
          organization_url: https://www.mitacs.ca/en
          title: AI Research Internship
          url: ''
        - certificate_url: 
          date_start: '2024-09-18'
          description: 'Received the Rising Star in Diversity, Equity and Inclusion(DEI) Advocacy travel grant for 8th IEEE International Joint Conference on Biometrics(IJCB) conference'
          organization: IEEE Biometrics Council
          organization_url: https://ieee-biometrics.org/
          title: DEI Travel Grant
          url: ''
        - certificate_url: 
          date_start: '2024-11-08'
          description: 'Received the Best Student Paper Award at the 2024 IEEE Western New York Image Processing Workshop(WNYISPW)'
          organization: IEEE Rochester Section
          organization_url: https://ieee-biometrics.org/
          title: Best Student Paper
          url: ''
    design:
      columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
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
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact Me
      # subtitle:
      # text: |-
      #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # # Contact (add or remove contact options as necessary)
      email: susimmuk@buffalo.edu
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: linkedin-in
          icon_pack: fab
          name: Linkedin
          link: 'https://www.linkedin.com/in/susim-mukul-roy/'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # # Automatically link email and phone or display as text?
      # autolink: true
      # # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
