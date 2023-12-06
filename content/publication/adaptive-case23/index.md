---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Adaptive Case23"
authors: [Yirong Chen, "admin", Wanli Ouyang, Michael Lepech]
date: 2023-09-28T00:27:02+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-06T00:27:02+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2023 IEEE 19th International Conference on Automation Science and Engineering (CASE)"
publication_short: "IEEE CASE 2023"

abstract: "Accurate traffic forecasting is vital to intelligent transportation systems, which are widely adopted to solve urban traffic issues. Existing traffic forecasting studies focus on modeling spatial-temporal dynamics in traffic data, among which the graph convolution network (GCN) is at the center for exploiting the spatial dependency embedded in the road network graphs. However, these GCN-based methods operate intrinsically on the node level (e.g., road and intersection) only whereas overlooking the spatial hierarchy of the whole city. Nodes such as intersections and road segments can form clusters (e.g., regions), which could also have interactions with each other and share similarities at a higher level. In this work, we propose an Adaptive Hierarchical SpatioTemporal Network (AHSTN) to promote traffic forecasting by exploiting the spatial hierarchy and modeling multi-scale spatial correlations. Apart from the node-level spatiotemporal blocks, AHSTN introduces the adaptive spatiotemporal downsampling module to infer the spatial hierarchy for spatiotemporal modeling at the cluster level. Then, an adaptive spatiotemporal upsampling module is proposed to upsample the cluster-level representations to the node-level and obtain the multi-scale representations for generating predictions. Experiments on two real-world datasets show that AHSTN achieves better performance over several strong baselines."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Spatial Time Series", "Graph Neural Network", "Graph Machine Learning", "Spatiotemporal Analysis"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2306.09386
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
