---
title: Contact
date: 2022-10-24

type: landing

sections: 
  - block: contact
    content:
      title: Contact
      text: |-
            If you are interested in Prince of Peace please contact us using the form.
      email: test@example.org
      phone: 888 888 88 88
      address:
        street: 1100 Somewhere Rd
        city: Anytown
        region: MD
        postcode: '12345'
        country: United States
        country_code: US
      coordinates:
        latitude: '39.1149'
        longitude: '-77.2457'
        directions: ''  
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
