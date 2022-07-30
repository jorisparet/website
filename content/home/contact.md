---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle: Please do not hesitate to reach out with any questions or feedback you may have about my research or my personal projects

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
      captcha: true

  # Contact details (edit or remove options as required)
  email: joris.paret@gmail.com
  #phone: 888 888 88 88
  #address:
  #  street: 450 Serra Mall
  #  city: Stanford
  #  region: CA
  #  postcode: '94305'
  #  country: United States
  #  country_code: US
  #coordinates:
  #  latitude: '37.4275'
  #  longitude: '-122.1697'
  #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: My LinkedIn Profile
      link: https://www.linkedin.com/in/joris-paret
    - icon: github
      icon_pack: fab
      name: My GitHub profile
      link: https://github.com/jorisparet

design:
  columns: '2'
---
