---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://wowchemy.com/docs/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Datasets
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: Story Generation
      tag: SG
    - name: Question Generation
      tag: QG
    - name: Title Generation
      tag: TG
    - name: Text Summarization
      tag: Summ

design:
  columns: '2'
  view: masonry
  flip_alt_rows: false
  background: {}
  spacing: {padding: [0, 0, 0, 0]}
---
