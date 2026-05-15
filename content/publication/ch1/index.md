---
title: "Multi-Sensor Monitoring of Wetland Inundation Using a Machine Learning and Data Fusion Framework"
authors:
  - Jenna Abrahamson
  - Josh Gray
  - Mirela Tulbure
  - Erin Schliep

date: '2026-04-04T00:00:00Z'
doi: '10.31223/X51F4Q'

# Schedule page publish date (NOT publication's date).
publishDate: "2025-08-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*Earth ArXiv*"
publication_short: "Earth ArXiv"

abstract: Continuous, high-resolution inundation data are needed to understand how small-scale, short-term wetland flooding influences global methane emissions and carbon cycling. Small (less than 1,000 m²), variably inundated wetlands are significant methane sources, yet coarse satellite products often miss their dynamics. Integrating optical and radar imagery with resolutions less than 30 m offers a solution over single sensor approaches, but two needs remain: (1) understanding the relative strengths and limitations of different sensors for detecting inundation in vegetated wetlands, and (2) developing methods that leverage these sensor characteristics to transform sparse, irregular classification maps with different resolutions into complete, consistent coverage. To address this, we first evaluated sensors by classifying inundation from 2017 to 2022 across a wetland area in eastern North Carolina using Sentinel-1, Sentinel-2, and PlanetScope imagery. We used tree-based machine learning models to classify pixels as Dry Land, Inundated Vegetation, or Open Water, and compared maps of inundation frequency produced by each model. Sentinel-2 random forest achieved the highest accuracy (94.9%), followed by PlanetScope (92.6%) and Sentinel-1 (85.9%) models. Next, we introduce a fusion framework based on Fixed-Rank Kriging, a spatiotemporal statistical model, to fuse binary classification maps into daily inundation probabilities at 6 m resolution. The fused approach balanced individual sensor variability and detected short-term inundation fluctuations missed by the Landsat Dynamic Surface Water Extent, a widely used satellite-derived data product. By characterizing sensor performance and translating that information into a multi-sensor fusion approach, this work enables high-resolution, continuous monitoring of inundation dynamics vital to predicting wetland methane emissions.

summary: A multi-sensor approach to monitoring high resolution inundation changes in wetlands

tags:
- Inundation Mapping
- Data Fusion
- Machine Learning
- Wetlands
- Commercial Imagery
- Remote sensing
featured: true

links:
- name: Paper
  url: 'https://eartharxiv.org/repository/view/12485/'
url_pdf: 
url_code: 
url_dataset: 'https://github.com/jen-abrahamson/wetland_hydro_ml'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [example]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
