---
title: "Grad-PU: Arbitrary-Scale Point Cloud Upsampling via Gradient Descent with Learned Distance Functions (CVPR 2023)"
summary: "**Yun He**, Danhang Tang, Yinda Zhang, Xiangyang Xue, Yanwei Fu"
# A new framework for accurate point cloud upsampling that supports arbitrary upsampling rates. **Accepted by CVPR 2023. 

# tags:
#   - Deep Learning
date: '2023-06-21T00:00:00Z'

authors:
  - "**admin**"
  - Danhang Tang
  - Yinda Zhang
  - Xiangyang Xue
  - Yanwei Fu

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Overview
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
links:
- name: Paper
  url: https://arxiv.org/abs/2304.11846
- name: Project Page
  url: https://yunhe20.github.io/Grad-PU/
- name: Code
  url: https://github.com/yunhe20/Grad-PU
- name: Video
  url: https://www.youtube.com/watch?v=VIDgUohCakc
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

Most existing point cloud upsampling methods have roughly three steps: feature extraction, feature expansion and 3D coordinate prediction. However, they usually suffer from two critical issues: (1) fixed upsampling rate after one-time training, since the feature expansion unit is customized for each upsampling rate; (2) outliers or shrinkage artifact caused by the difficulty of precisely predicting 3D coordinates or residuals of upsampled points. To address them, we propose a new framework for accurate point cloud upsampling that supports arbitrary upsampling rates. Our method first interpolates the low-res point cloud according to a given upsampling rate. And then refine the positions of the interpolated points with an iterative optimization process, guided by a trained model estimating the difference between the current point cloud and the high-res target. Extensive quantitative and qualitative results on benchmarks and downstream tasks demonstrate that our method achieves the state-of-the-art accuracy and efficiency.

### **Publication** 
The IEEE/CVF Computer Vision and Pattern Recognition Conference (CVPR), 2023.
