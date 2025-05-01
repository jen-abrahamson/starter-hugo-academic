---
title: AGU 2024 Annual Meeting

event: AGU 2024 Annual Meeting
event_url: https://agu.confex.com/agu/agu24/meetingapp.cgi

location: Washington, D.C.

summary: Gave an Oral Presentation on mapping variable inundation using data fusion and how it comapres to current, operational remote sensing-based inundation products.
abstract: 'Variable inundation strongly influences wetland biogeochemistry, especially in coastal plains where inundated areas can change on monthly to weekly time scales. Shifts in hydrologic states (i.e. dry to inundated) can transform wetlands from carbon sinks to carbon sources as methane (CH4) is released when oxygen becomes limited and triggers the process of methanogenesis. Small, short-term changes in inundated areas contribute to CH4 production. Still, our ability to estimate the impact of these changes on total CH4 emissions is limited by the spatial and temporal resolutions of available inundation data. Due to limited in-situ data, satellites are increasingly used to monitor inundation at scale; however, the resulting inundation maps and CH4 estimates can vary based on the spatial and temporal resolutions of the satellites used. Fortunately, advancements in data fusion and computing have enabled new ways of leveraging massive amounts of satellite data to address these differences. To explore this, we compared inundation data from individual satellites with those produced by a data fusion method integrating multiple satellites. First, we predicted inundation using 10 m Sentinel-1 (S1), 10 m Sentinel-2 (S2), and 3 m PlanetScope (PS) satellites at their native resolutions from 2017-2022 in a 5,778 km2 wetland-dominated area of eastern North Carolina. We mapped inundation by classifying pixels as open water, inundated vegetation, or dry land using the best-performing machine learning model—either Random Forest or Extreme Gradient Boosting—for each sensor. All models had overall accuracies > 93%, with S1 predicting the least inundation, S2 the most, and PS producing the highest variability. Next, these maps were fused using a spatiotemporal random effects model to produce daily inundation maps at 5 m, which resulted in 2.8x more observations than S2 alone. This approach can also be integrated with process-based models to improve predictions, particularly in canopy-covered areas where optical satellites are less effective. Limitations in inundation data hinder our understanding of CH4 dynamics. By developing a method to create consistent, accurate maps of inundation at high spatial and temporal resolutions, this work advances our ability to quantify CH4 dynamics caused by small-scale, variable inundation.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-12-09T13:00:00Z'
date_end: '2024-12-09T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-12-31T00:00:00Z'

authors: [Jenna Abrahamson]
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Oral Presentation'
  focal_point: Right

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/JennaAbrahamson
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["example"]
---
