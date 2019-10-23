+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 2  # Order that this section will appear.

title = "Research"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  #[[content.filter_button]]
  #  name = "All"
  #  tag = "*"
  
  [[content.filter_button]]
    name = "Publications"
    tag = "pubs"

  [[content.filter_button]]
    name = "R Packages"
    tag = "rpkg"


[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 2

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
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

My dissertation research was titled "Scalable Methods for Big Time-to-Event Data". Specifically, I developed  new surrogate $\ell_0$-penalization method for both right-censored and competing risks data. I showed that our method, Broken adaptive ridge (BAR), attains the oracle property for a diverging number of covariates. In addition, I showed that parameter estimation for the Fine-Gray proportional sub-distribution hazards model can be performed in $O(n)$ time, as opposed to $O(n^2)$, which allows for scalable analyses of both high-dimensional and massive sample size competing risks data.

My postdoctoral research pertains to developing integrative methods for the analysis of genetic data. 

Below is a selected list of R packages and papers that I have published.
