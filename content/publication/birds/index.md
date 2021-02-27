---
title: "Privileged Pooling: Better Sample Efficiency Through Supervised Attention / in review"
authors:
- admin
- Stefano D'Aronco
- Konrad Schindler
- Jan D. Wegner
date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: We propose a scheme for supervised image classification that uses privileged information, in the form of keypoint annotations for the training data, to learn strong models from small and/or biased training sets. Our main motivation is the recognition of animal species for ecological applications such as biodiversity modelling, which is challenging because of long-tailed species distributions due to rare species, and strong dataset biases such as repetitive scene background in camera traps. To counteract these challenges, we propose a visual attention mechanism that is supervised via keypoint annotations that highlight important object parts. This privileged information, implemented as a novel privileged pooling operation, is only required during training and helps the model to focus on regions that are discriminative. In experiments with three different animal species datasets, we show that deep networks with privileged pooling can use small training sets more efficiently and generalize better.

# Summary. An optional shortened abstract.
summary: 
tags:
- Source Themes
featured: false

links:
# - name: Custom Link
  # url: http://example.org
url_pdf: https://arxiv.org/abs/2003.09168
url_code: '#'
url_dataset: '#'
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
