---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: cat.kim@qut.edu.au
  #phone: 888 888 88 88
  address:
    street: Gardens Point Campus, R Block Room 204
    city: Brisbane City
    region: Queensland
    postcode: '4000'
    country: Australia
    country_code: AUS
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: ''
  # office_hours:
  #   - 'Monday 10:00 to 13:00'
  #   - 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  contact_links:
    - icon: mastodon
      icon_pack: fab
      name: Mastodon
      link: 'https://scicomm.xyz/@seaCatKim'
    - icon: linkedin
      icon_pack: fab
      name: LinkedIn
      link: 'https://www.linkedin.com/in/seacatkim/'
    # - icon: video
    #   icon_pack: fas
    #   name: Zoom Me
    #   link: 'https://zoom.com'

design:
  columns: '2'
  background:
    image: tablecoral_fish.jpg  # in assets/media
    image_darken: 0.5  # range 0-1, close to 0 is darker
    text_color_light: true
---
