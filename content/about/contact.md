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
      id: "xpwpwepk"  # Keep only the ID

    action: "https://formspree.io/f/xpwpwepk"  # Explicitly define action
    method: "POST"  # Explicitly define method

    fields:
      - name: "email"
        label: "Your Email"
        type: "email"
        required: true

      - name: "message"
        label: "Your Message"
        type: "textarea"
        required: true

    submit_label: "Send"

design:
  columns: "1"
---
