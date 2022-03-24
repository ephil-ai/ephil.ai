---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: info@ephil.ai
  #phone: 888 888 88 88
  address:
    street: Atlas 9.328, De Zaale
    city:  PO Box 513
    region: 5600 MB Eindhoven
    country: The Netherlands
    country_code: NL
  #coordinates:
   # latitude: '37.4275'
    #longitude: '-122.1697'
  #directions: Atlas 9.328
  #office_hours:
   # - 'Monday 10:00 to 13:00'
   # - 'Wednesday 09:00 to 10:00'
 # appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Follow us on Twitter
      link: 'https://twitter.com/ephil_ai'
  #contact_links:
   # - icon: twitter
    #  icon_pack: fas
     # name: Follow us on Twitter
      #link: 'https://twitter.com/ephil_ai'

  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: 
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

design:
  columns: '2'
---

