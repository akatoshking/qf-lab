+++
# Tag Cloud widget.
widget = "tag_cloud"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 120  # Order that this section will appear.

title = "Popular Topics"
subtitle = ""

[content]
  # Choose the taxonomy from `config.toml` to display (e.g. tags, categories)
  taxonomy = "tags"
  tags = ["partial differential equations(PDEs)", "Tensor methods", 
"deep learning for PDEs", 
"Bayesian inverse problems", 
"random numerical linear algebra", 
"numerical optimization", 
"uncertainty quantification"]
  
  # Choose how many tags you would like to display (0 = all tags)
  count = 20

[design]
  # Minimum and maximum font sizes (1.0 = 100%).
  font_size_min = 0.7
  font_size_max = 2.0
+++
