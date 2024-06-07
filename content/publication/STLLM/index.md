---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Spatial-Temporal Large Language Model for Traffic Prediction"
authors: [Chenxi Liu, Sun Yang, Qianxiong Xu, Zhishuai Li, Cheng Long, "admin", Rui Zhao]
date: 2024-06-07T14:58:48+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-05T14:58:48+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 25th IEEE International Conference on Mobile Data Management"
publication_short: "IEEE MDM 2024"

abstract: "Traffic prediction, a critical component for intelligent transportation systems, endeavors to foresee future traffic at specific locations using historical data. Although existing traffic prediction models often emphasize developing complex neural network structures, their accuracy has not seen improvements accordingly. Recently, Large Language Models (LLMs) have shown outstanding capabilities in time series analysis. Differing from existing models, LLMs progress mainly through parameter expansion and extensive pre-training while maintaining their fundamental structures. In this paper, we propose a Spatial-Temporal Large Language Model (ST-LLM) for traffic prediction. Specifically, ST-LLM redefines the timesteps at each location as tokens and incorporates a spatial-temporal embedding module to learn the spatial location and global temporal representations of tokens. Then these representations are fused to provide each token with unified spatial and temporal information. Furthermore, we propose a novel partially frozen attention strategy of the LLM, which is designed to capture spatial-temporal dependencies for traffic prediction. Comprehensive experiments on real traffic datasets offer evidence that ST-LLM outperforms state-of-the-art models. Notably, the ST-LLM also exhibits robust performance in both few-shot and zero-shot prediction scenarios."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Large Language Model", "Spatiotemporal Analysis", "Spatial Time Series", "Smart Mobility", "Domain Adaptation", "Model Fine Tuning", "Prediction"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2401.10134
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
