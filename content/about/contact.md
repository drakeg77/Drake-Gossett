---
widget: contact
headless: true
weight: 50

title: Get in touch
subtitle: Fill out the form below and I'll get back to you soon.

content:
  autolink: true

  form:
    provider: formspree
    formspree:
      id: "https://formspree.io/f/xpwpwepk"
      method: "POST"  # Ensure the form submits via POST

    fields:
      - name: "name"
        label: "Your Name"
        type: "text"
        required: true

      - name: "email"
        label: "Your Email"
        type: "email"
        required: true

      - name: "message"
        label: "Your Message"
        type: "textarea"
        required: true

    submit_label: "Send Message"

design:
  columns: "1"
---
