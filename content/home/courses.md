---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

active: true

# Order that this section appears on the page.
weight: 40

title: Teaching
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: courses

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  filter_button:
  - name: All
    tag: '*'
  - name: Undergraduate
    tag: "undergraduate"
  - name: TPG
    tag: "tpg"
  - name: MBA
    tag: "mba"

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 3

  order: desc

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
