---
title: "ACM Gordon Bell Special Prize Finalist - Running ahead of evolution—AI-based simulation for predicting future high-risk
  SARS-CoV-2 variants"
authors:
- Jie Chen
- Zhiwei Nie
- Yu Wang
- Kai Wang
- Fan Xu
- Zhiheng Hu
- Bing Zheng
- Zhennan Wang
- Guoli Song
- Jingyi Zhang 
- ' others'

date: "2023-07-01"
#doi: "https://doi.org/10.1177/109434202311880"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-06T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*The International Journal of High Performance Computing Applications*"
#publication_short: "IJHPCA"

abstract: The never-ending emergence of SARS-CoV-2 variations of concern (VOCs) has challenged the whole world for pandemic control. In order to develop effective drugs and vaccines, one needs to efficiently simulate SARS-CoV-2 spike receptor-binding domain (RBD) mutations and identify high-risk variants. We pretrain a large protein language model with approximately 408 million protein sequences and construct a high-throughput screening for the prediction of binding affinity and antibody escape. As the first work on SARS-CoV-2 RBD mutation simulation, we successfully identify mutations in the RBD regions of 5 VOCs and can screen millions of potential variants in seconds. Our workflow scales to 4096 NPUs with 96.5% scalability and 493.9× speedup in mixed-precision computing, while achieving a peak performance of 366.8 PFLOPS (reaching 34.9% theoretical peak) on Pengcheng Cloudbrain-II. Our method paves the way for simulating coronavirus evolution in order to prepare for a future pandemic that will inevitably take place.

# Summary. An optional shortened abstract.
summary: Running ahead of evolution

tags:
- AI for Science
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://github.com/ZhiweiNiepku/SARS-CoV-2_mutation_simulation/blob/main/IJHPCA_online.pdf'
url_code: 'https://github.com/ZhiweiNiepku/SARS-CoV-2_mutation_simulation'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/lOLynZp07AM'

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
projects:
  - content/project/Evolution_Simulation/index.md

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

