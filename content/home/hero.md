+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

title = ""

# Hero image (optional). Enter filename of an image in the `static/img/` folder.
hero_media = "biojulia-logo-light-svgomg.svg"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = ""
  
  # Background gradient.
  gradient_start = "#4bb4e3"
  gradient_end = "#2b94c3"
  
  # Background image.
  image = "bubble-helix-omg.png"  # Name of image in `static/img/`.
  image_darken = 0.8  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "contain"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "left"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = true

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
[cta]
  url = "getting-started/"
  label = "Get Started"
  icon_pack = "fas"
  icon = "download"
  
#[cta_alt]
#  url = "https://sourcethemes.com/academic/"
#  label = "View Documentation"

# Note. An optional note to show underneath the links.
#[cta_note]
#  label = '<a class="js-github-release" href="https://sourcethemes.com/academic/updates" data-repo="gcushen/hugo-academic">Latest release<!-- V --></a>'
+++

**Fast, open, easy, software for biology**

The bioinformatics infrastructure for the julia language.
