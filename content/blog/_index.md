---
title: Blog
type: landing
summary: 

# reading_time: false  # Show estimated reading time?
# share: false  # Show social sharing links?
# profile: false  # Show author profile?
# comments: false  # Show comments?
# cms_exclude: true

# View.
#   1 = List
#   2 = Compact
#   3 = Card
# view: 2

# Optional header image (relative to `static/media/` folder).
# header:
#   caption: ''
#   image: ''

sections:
- block: portfolio
    id: 
    content:
      title: 
      filters:
        folders:
          # - blog
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Data Science
          tag: Data Science
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---