---
title: '[ICLR 2024] GAIA: Zero-shot Talking Avatar Generation'


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Tianyu He
- Junliang Guo
- Runyi Yu
- admin
- Jialiang Zhu
- Kaikai An
- Leyi Li
- Xu Tan
- Chunyu Wang
- Han Hu
- HsiangTao Wu
- Sheng Zhao
- Jiang Bian

date: '2023-11-15T00:00:00Z'
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['Conference paper']

# Publication name and optional abbreviated publication name.
publication: The Twelfth International Conference on Learning Representations
publication_short: ICLR 2024

abstract: 'Zero-shot talking avatar generation aims at synthesizing natural talking videos from speech and a single portrait image. Previous methods have relied on domain-specific heuristics such as warping-based motion representation and 3D Morphable Models, which limit the naturalness and diversity of the generated avatars. In this work, we introduce GAIA (Generative AI for Avatar), which eliminates the domain priors in talking avatar generation. In light of the observation that the speech only drives the motion of the avatar while the appearance of the avatar and the background typically remain the same throughout the entire video, we divide our approach into two stages: 1) disentangling each frame into motion and
appearance representations; 2) generating motion sequences conditioned on the
speech and reference portrait image. We collect a large-scale high-quality talking
avatar dataset and train the model on it with different scales (up to 2B parameters).
Experimental results verify the superiority, scalability, and flexibility of GAIA
as 1) the resulting model beats previous baseline models in terms of naturalness,
diversity, lip-sync quality, and visual quality; 2) the framework is scalable since
larger models yield better results; 3) it is general and enables different applications
like controllable talking avatar generation and text-instructed avatar generation.'

# Summary. An optional shortened abstract.
summary: 'A project in Microsoft. We design a codec to disentangle each frame of talking face videos into motion and appearance representations and then curated a large-scale, high-quality dataset to train our diffusion-based GAIA model. The results demonstrate remarkable naturalness and scalability.'

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Demo Page
  url: https://microsoft.github.io/GAIA

url_pdf: 'https://arxiv.org/pdf/2311.15230.pdf'
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

