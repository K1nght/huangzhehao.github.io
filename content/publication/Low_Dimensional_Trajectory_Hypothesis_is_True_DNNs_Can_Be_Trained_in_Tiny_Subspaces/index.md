---
title: "Low Dimensional Trajectory Hypothesis is True: DNNs Can Be Trained in Tiny Subspaces"
authors:
- Tao Li
- Lei Tan
- admin
- Qinghua Tao
- Yipeng Liu
- Xiaolin Huang

date: "2022-05-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-05-26T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Pattern Analysis and Machine Intelligence, 45*(3)
publication_short: In *TPAMI 2023*

abstract: Deep neural networks (DNNs) usually contain massive parameters, but there is redundancy such that it is guessed that they could be trained in low-dimensional subspaces. In this paper, we propose a Dynamic Linear Dimensionality Reduction (DLDR) based on the low-dimensional properties of the training trajectory. The reduction method is efficient, supported by comprehensive experiments optimizing DNNs in 40-dimensional spaces can achieve comparable performance as regular training over thousands or even millions of parameters. Since there are only a few variables to optimize, we develop an efficient quasi-Newton-based algorithm, obtain robustness to label noise, and improve the performance of well-trained models, which are three follow-up experiments that can show the advantages of finding such low-dimensional subspaces.

# Summary. An optional shortened abstract.
summary: This paper develops an efficient quasi-Newton-based algorithm, obtains robustness to label noise, and improves the performance of well-trained models, which are three follow-up experiments that can show the advantages of finding such low-dimensional subspaces.

tags:
- Efficient Training
- Subspace Training
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2103.11154
url_code: 'https://github.com/nblt/DLDR'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

