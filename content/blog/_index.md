---
title: Blog
type: landing
# summary: 

# reading_time: false  # Show estimated reading time?
# share: false  # Show social sharing links?
# profile: true  # Show author profile?
# comments: false  # Show comments?
# cms_exclude: true

# View.
#   1 = List
#   2 = Compact
#   3 = Card
# view: 3

# # Optional header image (relative to `static/media/` folder).
# header:
#   caption: ''
#   image: ''

- block: portfolio
    content:
      title: Latest Blog
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: *
        - name: Latest
          tag: Latest Blog

---