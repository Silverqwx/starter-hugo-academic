---
title: 'A Method, System and Equipment for Accelerating 3D Reconstruction without Relying on Mechanical Placement'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xilong Liu
  - admin
  - Qinyi Gu
  - Menjuan Chen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-04-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-06-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['8']

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

abstract: The present invention belongs to the field of three-dimensional reconstruction, and specifically relates to a method, system and apparatus for accelerating three-dimensional reconstruction that does not depend on mechanical placement, said method comprising, obtaining a projection pattern of a surface of a measured object taken by a camera at any angle; determining the first coordinate data of the object point corresponding to each pixel point in said projection pattern in the camera image coordinate system and the second coordinate data in the projector image coordinate system, respectively; calculating a depth value of the object point corresponding to each pixel point in the camera image coordinate system based on the second coordinate data, the positional matrix parameters and the preset recording form parameters to calculate the depth value of the object point corresponding to each pixel point in the camera coordinate system; according to said depth value, the first coordinate data to calculate the three-dimensional coordinate data of the object point corresponding to each pixel point in the camera coordinate system, called spatial point coordinate data; using the three-dimensional point cloud data formed by each spatial point coordinate data for three-dimensional reconstruction. The present invention ensures the reconstruction accuracy in the process of achieving accelerated three-dimensional reconstruction.                   本发明属于三维重建领域,具体涉及了一种不依赖于机械摆放的三维重建加速方法、系统及设备,所述方法包括：获取相机任意角度拍摄的被测物体表面的投影图案；确定所述投影图案中每个像素点对应的物点分别在相机图像坐标系中的第一坐标数据和投影仪图像坐标系中的第二坐标数据；根据第二坐标数据、位姿矩阵参数和预设记录表单参数计算每个像素点对应的物点在相机坐标系中的深度值；根据所述深度值、第一坐标数据计算得到每个像素点对应的物点在相机坐标系中的三维坐标数据,称作空间点坐标数据；利用各个空间点坐标数据形成的三维点云数据进行三维重建。本发明在实现加速三维重建的过程中保证了重建精度。

# Summary. An optional shortened abstract.
summary: 本发明属于三维重建领域,具体涉及了一种不依赖于机械摆放的三维重建加速方法、系统及设备,在实现加速三维重建的过程中保证了重建精度。

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
