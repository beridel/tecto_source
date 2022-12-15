+++
# A "Meet the Team" section created with the People widget.
# This section displays people from `content/authors/` which belong to the `user_groups` below.

widget = "pages"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 3  # Order that this section will appear.

title = "Recent News"
subtitle = ""

[content]
  page_type = "post"
  count = 10
  offset = 0
  order = "desc"
  [content.filters]
    tag = ""
    category = ""
    publication_type = ""
    author = ""
    exclude_featured = false

[design]
  # Show user's social networking links? (true/false)
  show_social = true

  # Show user's interests? (true/false)
  show_interests = true

[design.background]
  # 1 = list
  # 2 = compact
  # 3 = card
  # 4 = citation (publications only)
  view = 1
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++
