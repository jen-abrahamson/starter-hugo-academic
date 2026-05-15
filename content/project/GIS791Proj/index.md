---
title: Flood Mapping with Prithvi
summary: Class project focused on using U-Net, IBM-NASA's Prithvi Foundation Model, and a novel fused version we term U-Prithvi to conduct flood mapping using Sentinel-2 imagery.
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart



---

**Flood Mapping with Prithvi**

I was part of a group that developed U-Prithvi, a novel hybrid architecture that combines the strengths of transformer-based foundation models with convolutional neural networks for flood inundation mapping. While the Prithvi foundation model excels at generalization tasks, we identified limitations in capturing fine-grained spatial details. By integrating Prithvi with U-Net's architecture and introducing a RandomHalfMaskLayer for balanced learning, we achieved superior performance on flood detection tasks. Our testing on the Sen1Floods11 dataset demonstrates that U-Prithvi outperforms both individual models, particularly on out-of-sample data, while remaining adaptable to other foundation models. This project was started as part of North Carolina State University's Geospatial Artificial Intelligence course.

