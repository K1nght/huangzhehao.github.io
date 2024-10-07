---
title: 'Trainable Weight Averaging: Efficient Training by Optimizing Historical Solutions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tao Li
  - admin
  - Qinghua Tao
  - Yingwen Wu
  - Xiaolin Huang

date: '2023-02-26T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-02-26T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Learning Representations 2023*
publication_short: In *ICLR 2023*

abstract: Stochastic gradient descent (SGD) and its variants are considered as the de-facto methods to train deep neural networks (DNNs). While recent improvements to SGD mainly focus on the descent algorithm itself, few works pay attention to utilizing the historical solutions---as an iterative method, SGD has gone through substantial explorations before convergence. Recently, an interesting attempt is stochastic weight averaging (SWA), which significantly improves the generalization by simply averaging the solutions at the tail stage of training. In this paper, we realize that the averaging coefficients could be determined in a trainable manner and propose Trainable Weight Averaging (TWA), a novel optimization method in the reduced subspace spanned by historical solutions. TWA has much greater flexibility and can be applied to the head stage of training to achieve training efficiency while preserving good generalization capability. Further, we propose a distributed training scheme to resolve the memory burden of large-scale training with efficient parallel computation. In the extensive numerical experiments, (i) TWA achieves consistent improvements over SWA with less sensitivity to learning rate; (ii) applying TWA in the head stage of training largely speeds up the convergence, resulting in over 40% time saving on CIFAR and 30% on ImageNet with improved generalization compared with regular training.

# Summary. An optional shortened abstract.
summary: A parallel framework for large-scale training with efﬁciency in memory and computation is designed for TWA or EMA and manifests better adaptation to different stages of training.

tags:
- Efficient Training
- Weight Averaging

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://openreview.net/pdf?id=8wbnpOJY-f
url_code: 'https://github.com/nblt/TWA'
url_dataset: ''
url_poster: 'https://iclr.cc/media/PosterPDFs/ICLR%202023/11905.png?t=1680768391.872985'
url_project: ''
url_slides: ''
url_source: 'https://iclr.cc/virtual/2023/poster/11905'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'TWA intuition'
  focal_point: ''
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

This work is driven by the results in [previous paper](/publication/Low_Dimensional_Trajectory_Hypothesis_is_True_DNNs_Can_Be_Trained_in_Tiny_Subspaces) on DNNs.
