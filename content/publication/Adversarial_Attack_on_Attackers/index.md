---
title: 'Adversarial Attack on Attackers: Post-Process to Mitigate Black-Box Score-Based Query Attacks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Sizhe Chen
- admin
- Qinghua Tao
- Yingwen Wu
- Cihang Xie
- Xiaolin Huang

date: '2022-11-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Advances in Neural Information Processing Systems 2022*
publication_short: In *NeurIPS 2022*

abstract: The score-based query attacks (SQAs) pose practical threats to deep neural networks by crafting adversarial perturbations within dozens of queries, only using the model's output scores. Nonetheless, we note that if the loss trend of the outputs is slightly perturbed, SQAs could be easily misled and thereby become much less effective. Following this idea, we propose a novel defense, namely Adversarial Attack on Attackers (AAA), to confound SQAs towards incorrect attack directions by slightly modifying the output logits. In this way, (1) SQAs are prevented regardless of the model's worst-case robustness; (2) the original model predictions are hardly changed, i.e., no degradation on clean accuracy; (3) the calibration of confidence scores can be improved simultaneously. Extensive experiments are provided to verify the above advantages. For example, by setting on CIFAR-10, our proposed AAA helps WideResNet-28 secure 80.59% accuracy under Square attack (2500 queries), while the best prior defense (i.e., adversarial training) only attains 67.44%. Since AAA attacks SQA's general greedy strategy, such advantages of AAA over 8 defenses can be consistently observed on 8 CIFAR-10/ImageNet models under 6 SQAs, using different attack targets, bounds, norms, losses, and strategies. Moreover, AAA calibrates better without hurting the accuracy. 

# Summary. An optional shortened abstract.
summary: We propose a novel defense against score-based query attacks, which post-processes model outputs to effectively confound attackers without hurting accuracy and calibration.

tags:
  - Adversarial Defense
  - Black-box Attack 
  - Score-based Query Attack

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://proceedings.neurips.cc/paper_files/paper/2022/file/5fa29a2f163ce2020769eca8956e2d77-Paper-Conference.pdf
url_code: 'https://github.com/Sizhe-Chen/AAA'
url_dataset: ''
url_poster: 'https://neurips.cc/media/PosterPDFs/NeurIPS%202022/f804d21145597e42851fa736e221da3f.png?t=1665965691.5208557'
url_project: ''
url_slides: 'https://neurips.cc/media/neurips-2022/Slides/54907.pdf'
url_source: 'https://neurips.cc/virtual/2022/poster/54907'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'AAA post-processes to avoid score-based query attacks.'
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

