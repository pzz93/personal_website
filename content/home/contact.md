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
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: zhuozhen001@e.ntu.edu.sg
  # phone: +65 89410891 | +86 13982229267 -->
  address:
    street: 50 Nanyang Avenue, S3-B2C-117
    city: Singapore
    region: CA
    postcode: '639798'
    country: Singapore
    country_code: SG
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Finance Department, Nanyang Business School
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
