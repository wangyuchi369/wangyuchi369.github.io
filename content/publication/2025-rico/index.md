---
title: '[Arxiv]  RICO: Improving Accuracy and Completeness in Image Recaptioning via Visual Reconstruction'


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yishuo Cai
- Shuhuai Ren
- Sihan Yang
- Linli Yao
- Yuanxin Liu
- Yuanxing Zhang
- Pengfei Wan
- Xu Sun

date: '2025-05-30T00:00:00Z'
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['Preprint']

# Publication name and optional abbreviated publication name.
publication: Arxiv Preprint
publication_short: Arxiv

abstract: 'Image recaptioning is widely used to generate training datasets with enhanced quality for various multimodal tasks. Existing recaptioning methods typically rely on powerful multimodal large language models (MLLMs) to enhance textual descriptions, but often suffer from inaccuracies due to hallucinations and incompleteness caused by missing fine-grained details. To address these limitations, we propose RICO, a novel framework that refines captions through visual reconstruction. Specifically, we leverage a text-to-image model to reconstruct a caption into a reference image, and prompt an MLLM to identify discrepancies between the original and reconstructed images to refine the caption. This process is performed iteratively, further progressively promoting the generation of more faithful and comprehensive descriptions. To mitigate the additional computational cost induced by the iterative process, we introduce RICO-Flash, which learns to generate captions like RICO using DPO. Extensive experiments demonstrate that our approach significantly improves caption accuracy and completeness, outperforms most baselines by approximately 10% on both CapsBench and CompreCap.'

# Summary. An optional shortened abstract.
summary: 'We propose RICO, a novel framework that refines captions through visual reconstruction. Extensive experiments demonstrate that our approach significantly improves caption accuracy and completeness.'

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
# - name: Demo Page
#   url: https://wangyuchi369.github.io/VidTwin/

url_pdf: 'https://arxiv.org/pdf/2505.22613'
url_code: 'https://github.com/wangyuchi369/RICO'
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
