---
title: "Assessment of Performance of Tree-Based Algorithms to Reduce Errors of Omission and Commission in Change Detection"
authors:
  - Peter Rasmussen
  - Jenna Abrahamson
  - Xiaojing Tang
  - Owen Smith
  - Josh Gray
  - Curtis Woodcock
  - Marc Bosch Ruiz

date: '2023-07-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*International Geoscience and Remote Sensing Symposium*"
publication_short: "IGARSS"

abstract: The ability to detect land use and land cover change quickly and accurately is crucial for earth system modeling, policy making, and sustainable land management.Remote sensing has been widely used to map and monitor land use and land cover change over very large areas. Many change detection algorithms (CDAs) have been developed with promising accuracy. However, accuracy of detecting specific types of change using these algorithms is often not satisfactory owing to errors of commission. We present a novel pixel-based broad area search (BAS) approach that detects and classifies heavy construction, which is an important indicator of human development and of interest to the intelligence community. The BAS system combines an online CDA, roboBayes, with a supervised tree based classifier that removes the CDA’s errors of commission. To assess the performance of the classifier, we examined three tree-based algorithms – decision tree, random forest, and LightGBM – trained on roboBayes model parameters, tuning the models using a leave-one-region-out cross-validation strategy. We compared the performance of the tree-based classifiers against a baseline of filters created by the authors. Performance was evaluated at the pixel-level using precision, recall, and F1-score, which are analogues of commission error, omission error, and accuracy, respectively. The BAS system with optimized tree-based filters performed nearly 80% better than the BAS system without any filters and more than 50% better than the authors’ filters.

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: false

# links:
# - name: ""
url: "https://2023.ieeeigarss.org/view_session.php?SessionID=1087"
url_pdf: "IGARSS_2023.pdf"
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Overview of methodology including the broad area search pipeline and machine learning module.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [IARPA SMART]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
