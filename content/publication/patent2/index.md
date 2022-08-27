---
title: 'Method and System for Removing Strong Noise from Point Cloud of Complex Curved Surface'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xiling Liu
  - admin
  - Qinyi Gu
  - Menjuan Chen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2019-11-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-04-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['8']

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

abstract: 本发明涉及一种复杂曲面点云强噪音去除方法及系统,所述去除方法包括：获取待处理点云Ω,所述待处理点云Ω由N+1个原始空间点组成；对各所述原始空间点进行平移变换,得到平移点云Ω’；对所述平移点云Ω’进行旋转变换,得到旋转点云Φ；对所述旋转点云Φ进行坐标变更变换,得到系数点云Я；对所述系数点云Я进行旋转平移变换,得到去噪结果点云F。本发明通过对处理点云依次进行平移变换、旋转变换、坐标变更变换及旋转平移变换,即可得到去噪结果点云,整个过程可不依赖人工设定参数,排除人为的干扰,提高去噪精度,从而实现在较大的范围内有效去除复杂连续曲面点云中强噪音。

# Summary. An optional shortened abstract.
summary: 本发明涉及一种复杂曲面点云强噪音去除方法及系统，通过对处理点云依次进行平移变换、旋转变换、坐标变更变换及旋转平移变换,即可得到去噪结果点云,整个过程可不依赖人工设定参数,排除人为的干扰,提高去噪精度,从而实现在较大的范围内有效去除复杂连续曲面点云中强噪音。

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
