---
title: 'Density-preserving Deep Point Cloud Compression (CVPR 2022)'


summary: |2-
  **Yun He***, Xinlin Ren*, Danhang Tang, Yinda Zhang, Xiangyang Xue, Yanwei Fu

# A novel deep point cloud compression method that preserves local density information. **Accepted by CVPR 2022.**

# tags:
#   - Deep Learning
date: '2022-06-29T00:00:00Z'

authors:
  - Yun He*
  - Xinlin Ren*
  - Danhang Tang
  - Yinda Zhang
  - Xiangyang Xue
  - Yanwei Fu

# Author notes (optional)
# author_notes:
#   - '*'
#   - '*'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Overview
  focal_point: 

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
links:
- name: Paper
  url: https://arxiv.org/abs/2204.12684
- name: Project Page
  url: https://yunhe20.github.io/D-PCC/
- name: Code
  url: https://github.com/yunhe20/D-PCC
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

### **Abstract**
Local density of point clouds is crucial for representing local details, but has been overlooked by existing point cloud compression methods. To address this, we propose a novel deep point cloud compression method that preserves local density information. Our method works in an auto-encoder fashion: the encoder downsamples the points and learns point-wise features, while the decoder upsamples the points using these features. Specifically, we propose to encode local geometry and density with three embeddings: density embedding, local position embedding and ancestor embedding. During the decoding, we explicitly predict the upsampling factor for each point, and the directions and scales of the upsampled points. To mitigate the clustered points issue in existing methods, we design a novel sub-point convolution layer, and an upsampling block with adaptive scale. Furthermore, our method can also compress point-wise attributes, such as normal. Extensive qualitative and quantitative results on SemanticKITTI and ShapeNet demonstrate that our method achieves the state-of-the-art rate-distortion trade-off.

### **Publication** 
The IEEE/CVF Computer Vision and Pattern Recognition Conference (CVPR), 2022.
