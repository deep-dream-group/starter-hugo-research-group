---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    id: heroo
    content:
      title: |
        Deep Dream Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Welcome to the official site of Deep Dream Group. This research group focuses on constructing state-of-the-art machine learning models for Natural Language Processing, Computer Vision, and Time-Series analysis.
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: 
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: people
    id: people
    content:
      title: Meet the Group
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
          - Researchers
          - Grad Students
          - Administration
          - Visitors
          - Alumni
      sort_by: Params.first_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # text: |-
      #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: fahimsikder01@gmail.com
      # address:
      #   street: Room - 2F:488, Building - E Huset, Linköping University
      #   city: Linköping
      #   region: 
      #   postcode: '58183'
      #   country: Sweden
      #   country_code: SE
      # coordinates:
      #   latitude: '58.397965'
      #   longitude: '15.575253'
      # contact_links:
      #   - icon: skype
      #     icon_pack: fab
      #     name: fahim-sikder
      #     link: ''
      #   - icon: twitter
      #     icon_pack: fab
      #     name: fahimsikder01
      #     link: 'https://twitter.com/fahimsikder01'
      # phone: 888 888 88 88
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---