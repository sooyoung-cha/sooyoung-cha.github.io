---
# Leave the homepage title empty to use the site title
title:
date: 2025-12-19
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: experience
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: "2006"
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Integrated Master and Ph.D
          company: Steineggerlab @ Seoul National University
          company_url: 'https://steineggerlab.com'
          location: Seoul, Korea
          date_start: '2024-09-01'
          date_end: ''
        - title: B.E. in Electrical and Computer Engineering
          company: Seoul National University
          company_url: 'https://snu.ac.kr'
          location: Seoul, Korea
          date_start: '2019-03-01'
          date_end: '2024-02-26'
    design:
      columns: '2'
  - block: collection
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      email: ellen2g@snu.ac.kr
      address:
        street: 1 Gwanak-ro, Gwanak-gu
        city: Seoul
        # region: CA
        postcode: '08826'
        country: Korea
        country_code: KR
      directions: 502-407
      contact_links:
      autolink: true
    design:
      columns: '2'
---