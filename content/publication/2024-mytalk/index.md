---
title: 'Make Your Actor Talk: Generalizable and High-Fidelity Lip Sync with Motion and Appearance Disentanglement'


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Runyi Yu 
- Tianyu He
- Ailing Zhang
- Yuchi Wang
- Junliang Guo
- Xu Tan
- Chang Liu
- Jie Chen
- Jiang Bian

date: '2023-02-24T00:00:00Z'
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['Preprint']

# Publication name and optional abbreviated publication name.
publication: Arxiv Preprint
publication_short: Arxiv

# abstract: 'We aim to edit the lip movements in talking video according to the given speech while preserving the personal identity and visual details. The task can be decomposed into two sub-problems: (1) speech-driven lip motion generation and (2) visual appearance synthesis. Current solutions handle the two sub-problems within a single generative model, resulting in a challenging trade-off between lip-sync quality and visual details preservation. Instead, we propose to disentangle the motion and appearance, and then generate them one by one with a speech-to-motion diffusion model and a motion-conditioned appearance generation model. However, there still remain challenges in each stage, such as motion-aware identity preservation in (1) and visual details preservation in (2). Therefore, to preserve personal identity, we adopt landmarks to represent the motion, and further employ a landmark-based identity loss. To capture motion-agnostic visual details, we use separate encoders to encode the lip, non-lip appearance and motion, and then integrate them with a learned fusion module. We train MyTalk on a large-scale and diverse dataset. Experiments show that our method generalizes well to the unknown, even out-of-domain person, in terms of both lip sync and visual detail preservation.'

# # Summary. An optional shortened abstract.
# summary: 'We present UniEdit, a tuning-free framework that supports both video motion and appearance editing by harnessing the power of a pre-trained text-to-video generator within an inversion-then-generation framework.'

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
# - name: Demo Page
#   url: https://jianhongbai.github.io/UniEdit/

url_pdf: ''
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
  caption: 'Example sentence pairs in the MultiSim dataset in English, Japanese, Urdu, and Russian'
  focal_point: ''
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
---
