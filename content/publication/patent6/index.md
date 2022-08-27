---
title: 'Automatic Monitoring Method, System, and Equipment for Relay Protection Hard Pressure Plate'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Fan He
  - admin
  - Qingqin Fu
  - Jie Ren
  - Yingchun Fu
  - Menjuan Chen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-08-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['8']

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

abstract: 本发明属于计算机视觉与数字图像处理领域,具体涉及一种继电保护硬压板的自动化监测方法、系统、设备,旨在解决传统继电保护硬压板监测方案费时费力,现有自动化监测方案又无法实现完全自动化监测的问题。本方法包括：获取待监测硬压板的阵列图像；对图像进行硬压板识别检测；将硬压板的坐标转换到参数空间并滤波处理,获取局部峰值点；对各局部峰值点的纵坐标聚类并排序；对各组聚类结果内的坐标逐项做差并计算均值；获取坐标数为第一数量的聚类结果并计算纵坐标的平均值；计算其余各组聚类结果的纵坐标的平均值；组成各硬压板的新的检测结果,完成自动化监测。本发明解决了传统监测方式费时费力,现有自动化监测无法完全自动化监测的问题。

# Summary. An optional shortened abstract.
summary: 本发明属于计算机视觉与数字图像处理领域,具体涉及一种继电保护硬压板的自动化监测方法、系统、设备,旨在解决传统继电保护硬压板监测方案费时费力,现有自动化监测方案又无法实现完全自动化监测的问题。

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
