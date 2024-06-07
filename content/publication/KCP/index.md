---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Non-Neighbors Also Matter to Kriging: A New Contrastive-Prototypical Learning"
authors: [Zhishuai Li, Yunhao Nie, "admin", Lei Bai, Yisheng Lv, Rui Zhao]
date: 2024-01-24T14:59:01+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-07T14:59:01+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of The 27th International Conference on Artificial Intelligence and Statistics"
publication_short: "AISTATS 2024"

abstract: "Kriging aims at estimating the attributes of unsampled geo-locations from observations in the spatial vicinity or physical connections, which helps mitigate skewed monitoring caused by under-deployed sensors. Existing works assume that neighbors' information offers the basis for estimating the attributes of the unobserved target while ignoring non-neighbors. However, non-neighbors could also offer constructive information, and neighbors could also be misleading. To this end, we propose ``Contrastive-Prototypical'' self-supervised learning for Kriging (KCP) to refine valuable information from neighbors and recycle the one from non-neighbors. As a pre-trained paradigm, we conduct the Kriging task from a new perspective of representation: we aim to first learn robust and general representations and then recover attributes from representations. A neighboring contrastive module is designed that coarsely learns the representations by narrowing the representation distance between the target and its neighbors while pushing away the non-neighbors. In parallel, a prototypical module is introduced to identify similar representations via exchanged prediction, thus refining the misleading neighbors and recycling the useful non-neighbors from the neighboring contrast component. As a result, not all the neighbors and some of the non-neighbors will be used to infer the target. To encourage the two modules above to learn general and robust representations, we design an adaptive augmentation module that incorporates data-driven attribute augmentation and centrality-based topology augmentation over the spatiotemporal Kriging graph data. Extensive experiments on real-world datasets demonstrate the superior performance of KCP compared to its peers with 6% improvements and exceptional transferability and robustness. "

# Summary. An optional shortened abstract.
summary: ""

tags: ["Spatiotemporal Analysis", "Spatial Time Series", "Smart Mobility", "Kriging", "Contrastive Learning", "Self-Supervised Learning"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://proceedings.mlr.press/v238/li24b.html
url_code: https://github.com/bonaldli/KCP
url_dataset:
url_poster: https://virtual.aistats.org/media/PosterPDFs/AISTATS%202024/6553.png?t=1714216633.7656586
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
