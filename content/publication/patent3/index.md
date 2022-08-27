---
title: 'Method, Device, Computer Equipment and Storage Medium for Measuring Spatial Straight Line Orientation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xilong Liu
  - Qinyi Gu
  - Menjuan Chen
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2018-10-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-05-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['8']

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

abstract: 本申请涉及一种空间直线朝向测量方法、装置、计算机设备和存储介质,通过获取原始图像,提取原始图像中的直线,计算直线置信度,将各条直线进行非线性变换得到各条直线在变换图像平面中的曲线轨迹,根据直线置信度对各条曲线轨迹经过的像素点的像素值进行更新得到更新后的变换图像,对更新后的变换图像进行卷积运算得到卷积图像,从卷积图像中筛选出像素值满足交点条件的像素点的卷积图像坐标,作为目标卷积坐标,根据卷积图像坐标与原始图像的原始图像坐标的对应关系,计算得到目标卷积坐标对应的原始图像坐标,将目标卷积坐标对应的原始图像坐标作为消失点坐标,根据各个消失点坐标确定与各个消失点对应的直线的空间朝向,实现自动化计算。

# Summary. An optional shortened abstract.
summary: 本申请涉及一种空间直线朝向测量方法、装置、计算机设备和存储介质。

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
