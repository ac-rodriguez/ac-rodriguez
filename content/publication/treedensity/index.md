---
title: "Counting the uncountable: deep semantic density estimation from space"
authors:
- admin
- Jan D. Wegner
date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: We propose a new method to count objects of specific categories that are significantly smaller than the ground sampling distance of a satellite image. This task is hard due to the cluttered nature of scenes where different object categories occur. Target objects can be partially occluded, vary in appearance within the same class and look alike to different categories. Since traditional object detection is infeasible due to the small size of objects with respect to the pixel size, we cast object counting as a density estimation problem. To distinguish objects of different classes, our approach combines density estimation with semantic segmentation in an end-to-end learnable convolutional neural network (CNN). Experiments show that deep semantic density estimation can robustly count objects of various classes in cluttered scenes. Experiments also suggest that we need specific CNN architectures in remote sensing instead of blindly applying existing ones from computer vision.

# Summary. An optional shortened abstract.
summary: 
tags:
- Source Themes
featured: false

links:
- name: Arxiv
  url: https://arxiv.org/abs/1809.07091
url_pdf: https://link.springer.com/chapter/10.1007/978-3-030-12939-2_24
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  []
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
slides: ""
---
<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
