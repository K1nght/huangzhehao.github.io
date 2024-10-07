---
title: "Query Attack by Multi-Identity Surrogates"
authors:
- Sizhe Chen
- admin
- Qinghua Tao
- Xiaolin Huang

date: "2023-03-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-12T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Artificial Intelligence 2023*
publication_short: In *TAI 2023*

abstract: Deep Neural Networks (DNNs) are acknowledged as vulnerable to adversarial attacks, while the existing black-box attacks require extensive queries on the victim DNN to achieve high success rates. For query-efﬁciency, surrogate models of the victim are used to generate transferable Adversarial Examples (AEs) because of their Gradient Similarity (GS) , i.e., surrogates’ attack gradients are similar to the victim’s ones. However, it is generally neglected to exploit their similarity on outputs, namely the Prediction Similarity (PS) , to ﬁlter out inefﬁcient queries by surrogates without querying the victim. To jointly utilize and also optimize surrogates’ GS and PS, we develop QueryNet, a uniﬁed attack framework that can signiﬁcantly reduce queries. QueryNet creatively attacks by multi-identity surrogates, i.e., crafts several AEs for one sample by different surrogates, and also uses surrogates to decide on the most promising AE for the query. After that, the victim’s query feedback is accumulated to optimize not only surrogates’ parameters but also their architectures, enhancing both the GS and the PS. Although QueryNet has no access to pre-trained surrogates’ prior, it reduces queries by averagely about an order of magnitude compared to alternatives within an acceptable time, according to our comprehensive experiments 11 victims (including two commercial models) on MNIST/CIFAR10/ImageNet, allowing only 8-bit image queries, and no access to the victim’s training data.

# Summary. An optional shortened abstract.
summary: QueryNet is a attack framework that reduces queries by averagely about an order of magnitude compared to alternatives within an acceptable time, according to comprehensive experiments 11 victims on MNIST/CIFAR10/ImageNet, allowing only 8-bit image queries, and no access to the victim’s training data.

tags:
- Adversarial Learning
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2105.15010
url_code: 'https://github.com/Sizhe-Chen/QueryNet'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'QueryNet'
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

