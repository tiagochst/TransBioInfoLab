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

  email: steven.chen@med.miami.edu
  address:
    street: 1120 NW 14th St
    city: Miami
    region: FL
    postcode: '33136'
    country: United States
    country_code: US
  coordinates:
    latitude: '25.787783848513527'
    longitude: ' -80.21283006931746'

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
---
