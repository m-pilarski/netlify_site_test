---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
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
    provider: formspree
    formspree:
      id: test
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true

design:
  columns: '2'
---

<form
  name="contact"
  method="POST"
  data-netlify-recaptcha="true"
  data-netlify="true"
>
  <!-- input fields and custom reCAPTCHA snippet -->
</form>

<!-- <head>
<script type="module" src="https://unpkg.com/friendly-challenge@0.9.0/widget.module.min.js" async defer></script>
<script nomodule src="https://unpkg.com/friendly-challenge@0.9.0/widget.min.js" async defer></script>
</head>

Hier noch <div class="frc-captcha" data-sitekey="<FCMHHISNQ5KGGETR>"></div> -->
