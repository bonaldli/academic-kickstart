---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Jointly contrastive representation learning on road network and trajectory"
authors: [Zhenyu Mao, "admin", Dedong Li, Lei Bai, Rui Zhao]
date: 2022-10-17T16:08:37+08:00
doi: "https://doi.org/10.1145/3511808.3557370"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-12-28T16:08:37+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 31st ACM International Conference on Information & Knowledge Management"
publication_short: "CIKM 2022"

abstract: "Road network and trajectory representation learning are essential for traffic systems since the learned representation can be directly used in various downstream tasks (e.g., traffic speed inference, travel time estimation). However, most existing methods only contrast within the same scale, i.e., treating road network and trajectory separately, which ignores valuable inter-relations. In this paper, we aim to propose a unified framework that jointly learns the road network and trajectory representations end-to-end. We design domain-specific augmentations for road-road contrast and trajectory-trajectory contrast separately, i.e., road segment with its contextual neighbors and trajectory with its detour replaced and dropped alternatives, respectively. On top of that, we further introduce the road-trajectory cross-scale contrast to bridge the two scales by maximizing the total mutual information. Unlike the existing cross-scale contrastive learning methods on graphs that only contrast a graph and its belonging nodes, the contrast between road segment and trajectory is elaborately tailored via novel positive sampling and adaptive weighting strategies. We conduct prudent experiments based on two real-world datasets with four downstream tasks, demonstrating improved performance and effectiveness."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Contrastive Learning", "Self-Supervised Learning", "Pre-trained Model", "Smart Transportation", "Graph Neural Network", "Trajectory"]
categories: ["Conference"]
featured: yes

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://dl.acm.org/doi/abs/10.1145/3511808.3557370
url_code: https://github.com/mzy94/JCLRNT
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
