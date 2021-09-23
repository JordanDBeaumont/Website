---
widget: slider
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: '3000'

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 400px

# Order that this section appears on the page.
weight: 25


item:
  - title: Hello
    content: 'I am center aligned 😄'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: '#e83845'  # An HTML color value.
    overlay_img:   # Image path relative to your `assets/media/` folder
    overlay_filter: 0.5  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Download my app
    cta_url: 'https://example.org'
    cta_icon_pack: fas
    cta_icon: graduation-cap
  - title: 'Latest publication:'
    content: '*"Modulating eating behaviour with transcranial direct current stimulation (tDCS): A systematic literature review on the impact of eating behaviour traits"*'
    align: center
    overlay_color: '#e83845'
    overlay_img: ''
    overlay_filter: 0.5
    cta_label: View publication
    cta_url: '#publications'
    cta_icon_pack: fas
    cta_icon: file
  - title: 'Latest blog post:'
    content: '*"Modulating eating behaviour with transcranial direct current stimulation (tDCS): A systematic literature review on the impact of eating behaviour traits"*'
    align: center
    overlay_color: '#e83845'
    overlay_img: ''
    overlay_filter: 0.5
    cta_label: View blog
    cta_url: '#posts'
    cta_icon_pack: fas
    cta_icon: file
---