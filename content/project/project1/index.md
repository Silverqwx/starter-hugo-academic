---
title: Research, Development and Optimization of Structured Light 3D Camera
summary: 3D Camera for scanning object to get 3D model based on structured light
tags:
  - 3D Reconstruction
date: '2018-06-03T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  # caption: Photo by rawpixel on Unsplash
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

A camera and a projector are used to compose a projector-camera system. Gray-Phase code is used in this system to help achieve high-speed 3D reconstruction of the object surface. High-precision calibration algorithm and de-distortion algorithm are completed to ensure the accurary, and at last, accuracy of 0.01mm is achieved.

使用相机和投影仪，基于结构光编解码和多视图立体几何技术，实现物体表面高速三维重建，点云重建速度达到 30 副/秒，基于高精度标定和去畸变技术，消除畸变对重建结果的影响，利用 C++ 将软件部分模块化封装，已应用于多个项目和中科院自动化所苏州研究院的 3D 相机产品
