---
title: "Machine Unlearning by Suppressing Sample Contribution"
authors:
- Xinwen Cheng 
- admin
- Xiaolin Huang

date: "2024-02-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-23T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv*
publication_short: In *arXiv*

abstract: Machine Unlearning (MU) is to forget data from a well-trained model, which is practically important due to the "right to be forgotten". In this paper, we start from the fundamental distinction between training data and unseen data on their contribution to the model the training data contributes to the final model while the unseen data does not. We theoretically discover that the input sensitivity can approximately measure the contribution and practically design an algorithm, called MU-Mis (machine unlearning via minimizing input sensitivity), to suppress the contribution of the forgetting data. Experimental results demonstrate that MU-Mis outperforms state-of-the-art MU methods significantly. Additionally, MU-Mis aligns more closely with the application of MU as it does not require the use of remaining data.

# Summary. An optional shortened abstract.
summary: This paper theoretically discover that the input sensitivity can approximately measure the contribution of the forgetting data and practically design an algorithm, called MU-Mis (machine unlearning via minimizing input sensitivity), to suppress the contribution of the forgetting data.

tags:
- Machine Unlearning

featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2402.15109
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
  caption: 'MU-Mis Algorithm'
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
