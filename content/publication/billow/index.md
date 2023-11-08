---
title: "Recognition of Unseen Bird Species by Learning from Field Guides"
authors:
- admin
- Stefano D'Aronco
- Rodrigo Caye Daudt
- Jan D. Wegner
- Konrad Schindler

date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "We exploit field guides to learn bird species recognition, in particular zero-shot recognition of unseen species. The illustrations contained in field guides deliberately focus on discriminative properties of a species, and can serve as side information to transfer knowledge from seen to unseen classes. We study two approaches: (1) a contrastive encoding of illustrations that can be fed into zero-shot learning schemes; and (2) a novel method that leverages the fact that illustrations are also images and as such structurally more similar to photographs than other kinds of side information. Our results show that illustrations from field guides, which are readily available for a wide range of species, are indeed a competitive source of side information. On the iNaturalist2021 subset, we obtain a harmonic mean from 749 seen and 739 unseen classes greater than 45% (@top-10) and 15% (@top-1). Which shows that field guides are a valuable option for challenging real-world scenarios with many species."

# Summary. An optional shortened abstract.
summary: We exploit existing field guides to learn bird species recognition in large scale datasets for zero-shot recognition of unseen species
tags:
- Deep Learning
- Fine-Grained
- Zero-shot Learning
- Field Guides
featured: true

links:
# - name: Custom Link
  # url: http://example.org
url_pdf: https://arxiv.org/abs/2003.09168
url_code: 'https://github.com/ac-rodriguez/zsl_billow'
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
  caption: "We use the field guides to create class prototypes that are used at inference time to make a prediction."
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
