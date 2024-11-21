---
title: EGU General Assembly 2024

event: EGU General Assembly 2024
event_url: https://www.egu24.eu/

location: Vienna, Austria

summary: Presented a lightning talk at the European Geophysical Union General Assembly on statistical data fusion of remote sensing inundation maps.
abstract: 'The biogeochemistry of wetland ecosystems is driven by the presence and absence of water. Wetlands are known hotspots of methane (CH4) emissions, particularly when inundated. Monitoring short-term, and possibly small-scale changes in inundation is therefore critical to quantifying both local and global CH4 emissions. Despite their importance, these short-term changes have historically been under-reported in efforts to monitor CH4. As sea levels rise and flood events increase, it’s imperative to account for these events to better project CH4 cycle variation in a changing climate. Remote sensing is the only method capable of monitoring these changes over time at scale; however, no current remote sensing product has the spatial and temporal resolutions required to map ephemeral changes in inundation extents accurately. To address this, we developed a method to generate high spatiotemporal resolution inundation maps combining SAR and optical data from Sentinel-1 and Sentinel-2 imagery supplemented with commercial PlanetScope imagery from 2017–2022. This method was evaluated in the Albemarle-Pamlico Peninsula, a coastal wetland region in North Carolina, United States characterized by frequent and variable inundation.

Two decision-tree-based machine learning algorithms were tested to map inundation extents: a random forest (RF) model and an extreme gradient boosted (XGBoost) model. The models were trained for each sensor based on a suite of spectral signals, terrain-derived features, and precipitation data for each image at the sensor’s native resolution. This work revealed minor differences between machine learning classifiers across the 5 years, with RF accuracies of 94.0%, 98.2%, and 98.6% and XGBoost accuracies of 89.1%, 98.3%, and 97.8% for PlanetScope, Sentinel-2, and Sentinel-1 respectively. The RF classified inundation maps from each sensor were then fused using a hierarchical spatiotemporal random effects model within a probit link function, to generate daily time series of inundation probabilities at 5 m resolution. This approach is unique in that we 1) address the differing sensor resolutions using a statistical change-of-support formulation with observations mapped to process locations, 2) fuse non-Gaussian (binary) responses from machine learning outputs, and 3) model spatial and temporal autocorrelation through spatial basis functions and a first-order autoregressive time series model. Overall, this work produced a novel 5-year inundation dataset, capturing both long-term and ephemeral changes in inundation extents that are critical for quantifying components of the water cycle and their interactions with biogeochemical cycles on Earth.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-04-19T09:00:00Z'
date_end: '2024-04-19T10:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors: [Jenna Abrahamson]
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'EGU Presentation'
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
