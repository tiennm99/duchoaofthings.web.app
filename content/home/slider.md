+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = ""

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Xin chào!"
  content = "Rất vui vì bạn đã đến với site của chúng mình"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "hexagon.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Liên hệ chúng mình tại đây nhé!"
  cta_url = "https://www.facebook.com/bkfcduchoalongan/"
  cta_icon_pack = "fab"
  cta_icon = "facebook"

[[item]]
  title = "Bạn là học sinh cấp 3?"
  content = "Xem hướng dẫn của bạn tại link sau nhé!"
  align = "left"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "sphere.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  cta_label = "Hướng dẫn tại đây"
  cta_url = "/post/2020-05-30-huong-dan-hoc-sinh/"
  cta_icon_pack = "fas"
  cta_icon = "link"

[[item]]
  title = "Bạn là thành viên nhóm?"
  content = "Xem hướng dẫn của bạn tại link sau nhé!"
  align = "right"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "triangle.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  cta_label = "Hướng dẫn tại đây"
  cta_url = "/courses/huong-dan-thanh-vien"
  cta_icon_pack = "fas"
  cta_icon = "link"
+++
