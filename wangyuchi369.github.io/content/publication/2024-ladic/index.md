---
title: '[NAACL 2024] LaDiC: Are Diffusion Models Really Inferior to Autoregressive
Counterparts for Image-to-Text Generation?'


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Shuhuai Ren
- Rundong Gao
- Linli Yao
- Qingyan Guo
- Kaikai An
- Jianhong Bai
- Xu Sun

date: '2024-03-26T00:00:00Z'
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['Conference paper']

# Publication name and optional abbreviated publication name.
publication: 2024 Annual Conference of the North American Chapter of the Association for Computational Linguistics
publication_short: NAACL 2024

abstract: 'Diffusion models have exhibited remarkable capabilities in text-to-image generation. However, their performance in image-to-text generation, specifically image captioning, has lagged behind Auto-Regressive (AR) models, casting doubt on their applicability for such tasks. In this work, we revisit diffusion models, highlighting their capacity for holistic context modeling and parallel decoding. With these benefits, diffusion models can alleviate the inherent limitations of AR methods, including their slow inference speed, error propagation, and unidirectional constraints. Furthermore, we identify the prior underperformance of diffusion models stemming from the absence of an effective latent space for image-text alignment, and the discrepancy between continuous diffusion processes and discrete textual data. In response, we introduce a novel architecture, LaDiC, which utilizes a split BERT to create a dedicated latent space for captions and integrates a regularization module to manage varying text lengths. Our framework also includes a diffuser for semantic image-to-text conversion and a Back\&Refine technique to enhance token interactivity during inference. LaDiC achieves state-of-the-art performance for diffusion-based methods on the MS COCO dataset with 38.2 BLEU@4 and 126.2 CIDEr, demonstrating exceptional performance without pre-training or ancillary modules. This indicates strong competitiveness with AR models, revealing the previously untapped potential of diffusion models in image-to-text generation.'

# Summary. An optional shortened abstract.
summary: 'We explore the previously untapped advantages of diffusion models over autoregressive (AR) methods in image-to-text generation. Through meticulous design of a latent-based diffusion model tailored for captioning, we achieve comparable performance with some strong AR baselines.'

tags: []

# Display this page in the Featured widget?
featured: true

# # Custom links (uncomment lines below)
# links:
# - name: Demo Page
#   url: https://microsoft.github.io/GAIA

url_pdf: 'https://arxiv.org/pdf/2404.10763.pdf'
url_code: 'https://github.com/wangyuchi369/LaDiC'
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
  focal_point: 'Middle'
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

award: ''
---

