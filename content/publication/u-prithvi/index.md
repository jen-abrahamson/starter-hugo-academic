---
title: "U-Prithvi: Integrating a Foundation Model and U-Net for Enhanced Flood Inundation Mapping"
authors:
  - Vit Kostejn
  - Yamil Essus
  - Jenna Abrahamson
  - Ranga Raju Vatsavai

date: '2025-08-15T00:00:00Z'
doi: '10.4230/LIPIcs.GIScience.2025.18'

# Schedule page publish date (NOT publication's date).
publishDate: "2025-08-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*13th International Conference on Geographic Information Science (GIScience 2025), Leibniz International Proceedings in Informatics (LIPIcs)*"
publication_short: "GIScience 2025"

abstract: In recent years, large pre-trained models, commonly referred to as foundation models, have become increasingly popular, and sustainable land management.Remote sensing has been widely used to map and monitor land use and land cover change over very large areas. Many change detection algorithms (CDAs) have been developed with promising accuracy. However, accuracy of detecting specific types of change using these algorithms is often not satisfactory owing to errors of commission. We present a novel pixel-based broad area search (BAS) approach that detects and classifies heavy construction, which is an important indicator of human development and of interest to the intelligence community. The BAS system combines an online CDA, roboBayes, with a supervised tree based classifier that removes the CDA’s errors of commission. To assess the performance of the classifier, we examined three tree-based algorithms, including decision on roboBayes model parameters, tuning the models using a leave-one-region-out cross-validation strategy. We compared the performance of the tree-based classifiers against a baseline of filters created by the authors. Performance was evaluated at the pixel-level using precision, recall, and F1-score, which are analogues of commission error, omission error, and accuracy, respectively. The BAS system with optimized tree-based filters performed nearly 80% better than the BAS system without any filters and more than 50% better than the authors’ filters.

summary: A novel architecture combining the Prithvi transformer foundation model with U-Net for improved flood inundation mapping from remote sensing imagery.

tags:
- GeoAI
- Flood mapping
- Foundation models
- Deep learning
- Remote sensing
featured: true

links:
- name: DOI
  url: 'https://doi.org/10.4230/LIPIcs.GIScience.2025.18'
- name: Paper
  url: 'https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.GIScience.2025.18'
url_pdf: 'https://drops.dagstuhl.de/storage/00lipics/lipics-vol346-giscience2025/LIPIcs.GIScience.2025.18/LIPIcs.GIScience.2025.18.pdf'
url_code: 'https://github.com/kostejnv/prithvi_segmentation'
url_dataset: ''
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
projects: [GIS791Proj]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
