---
# Leave the homepage title empty to use the site title
title: "Huiyin Ouyang"
date: 2025-08-04
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
    design:
      css_class: ""
      background:
        color: ""

  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      view: citation

  - block: collection
    id: wip
    content:
      title: Working Papers
      filters:
        folders:
          - wip
    design:
      view: citation

  - block: collection
    id: projects2
    content:
      title: Research Grants
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 2

  - block: collection
    id: courses
    content:
      title: Teaching
      filters:
        folders:
          - teaching
    design:
      view: article-grid
      columns: 2

  - block: markdown
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: |
        - **Email:** [oyhy@hku.hk](mailto:oyhy@hku.hk)
        - **HKU Profile:** [https://www.hkubs.hku.hk/people/huiyin-ouyang/](https://www.hkubs.hku.hk/people/huiyin-ouyang/)
        - **Location:** Room 1321, KKL Building, HKU, Hong Kong
    design:
      columns: '1'
---
