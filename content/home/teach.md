---
# This file represents a page section to display teaching content in a card format.
widget: portfolio

# This file is part of a larger page (e.g., landing page).
headless: true

# Order that this section appears on the page.
weight: 20

title: "Teaching"
subtitle: "Explore the Courses and Tutorials"

content:
  # Page type to display. In this case, we use 'teaching' to match the folder name.
  page_type: teaching

  # Default filter index (optional).
  filter_default: 0

  # Filter toolbar (optional).
  filter_button:
    - name: All
      tag: '*'

design:
  columns: '2'  # Number of cards per row
  view: card     # Display style: card format
  flip_alt_rows: true
  background: {}
  spacing: {padding: [0, 0, 0, 0]}
---
