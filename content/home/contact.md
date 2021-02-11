---
# Contact widget.
widget : "contact"  # See https://sourcethemes.com/academic/docs/page-builder/
headless : true  # This file represents a page section.
active : true  # Activate this widget? true/false
weight : 130  # Order that this section will appear.

title : Keep in touch
subtitle : I'm best reached via email. I'm always open to interesting conversations and collaboration.

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: formspree
    formspree:
      id: contact
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true

design:
  columns: '2'
---

