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
  email: 201911061110@mail.bnu.edu.cn
  office_hours:
    - '9AM to 12PM'
  appointment_url: 'https://calendly.com/di_liu'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/diliu_aurora'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://stanford.zoom.us/j/6320473761?pwd=OTNRZk1SelhoaDVJREtEbjhvWDcwUT09'

design:
  columns: '2'
---
