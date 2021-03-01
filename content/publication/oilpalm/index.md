---
title: "Mapping Oil Palm Density at Country Scale: an Active Learning Approach / in review"
authors:
- admin
- Stefano D'Aronco
- Konrad Schindler
- Jan D. Wegner
date: ""
doi: ""


# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Oil palm is one of the major oil crops in the world. Accurate mapping is fundamental for understanding its past and future impact on the environment. Beyond traditional land cover classification, we propose to use tree densities per pixel for large scale oil palm analysis. This allows for a much finer-grained analysis, for instance regarding different planting patterns. To that end, we propose a new, active deep learning method to estimate oil palm density at scale of from Sentinel-2 satellite images, and apply it to generate complete maps for Malaysia and Indonesia. What makes the regression of oil palm density challenging is the need for representative reference data that covers all relevant geographical conditions across a large territory. Specifically for density estimation, generating reference data involves counting individual trees. To keep the associated labelling effort low we propose an active learning (AL) approach that automatically chooses the most relevant samples to be labelled. Our method relies on estimates of the epistemic model uncertainty and of the diversity among samples, making it possible to retrieve an entire batch of relevant samples in a single iteration. Moreover, our algorithm has linear computational complexity and is easily parallelisable to cover large areas. We use our method to compute the first oil palm density map with $10\,$m Ground Sampling Distance (GSD) , for all of Indonesia and Malaysia and for two different years, 2017 and 2019. The maps have a mean absolute error of $\pm$7.3 trees/$ha$, estimated from an independent validation set. We also analyse density variations between different states within a country and compare them to official estimates. According to our estimates there are, in total, \textgreater1.2 billion oil palms in Indonesia covering \textgreater15 million $ha$, and \textgreater0.5 billion oil palms in Malaysia covering \textgreater6 million $ha$.

# Summary. An optional shortened abstract.
summary: We propose a new, active deep learning method to estimate oil palm density at scale of from Sentinel-2 satellite images, and apply it to generate complete maps for Malaysia and Indonesia.
tags:
- Deep Learning
- Remote Sensing
featured: false

links:
# - name: Custom Link
  # url: http://example.org
# url_pdf: '#'
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
  caption: 'Oil palm density map from 2017. We estimate a total of 1.7 billion oil palms Indonesia and Malaysia.'
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
