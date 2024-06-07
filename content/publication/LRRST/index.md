---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Low-Rank Robust Subspace Tensor Clustering for Metro Passenger Flow Modeling"
authors: [Dorukhan Sergin Nurretin, Jiuyun Hu, Ziyue Li, Chen Zhang, Fugee Tsung, Hao Yan]
date: 2024-04-05T15:00:16+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-07T15:00:16+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "INFORMS Journal on Data Science"
publication_short: "INFORMS Journal on Data Science"

abstract: "Tensor clustering has become an important topic, specifically in spatio-temporal modeling, due to its ability to cluster spatial modes (e.g., stations or road segments) and temporal modes (e.g., time of the day or day of the week). Our motivating example is from subway passenger flow modeling, where similarities between stations are commonly found. However, the challenges lie in the innate high-dimensionality of tensors and also the potential existence of anomalies. This is because the three tasks, i.e., dimension reduction, clustering, and anomaly decomposition, are inter-correlated to each other, and treating them in a separate manner will render a suboptimal performance. Thus, in this work, we design a tensor-based subspace clustering and anomaly decomposition technique for simultaneously outlier-robust dimension reduction and clustering for high-dimensional tensors. To achieve this, a novel low-rank robust subspace clustering decomposition model is proposed by combining Tucker decomposition, sparse anomaly decomposition, and subspace clustering. An effective algorithm based on Block Coordinate Descent is proposed to update the parameters. Prudent experiments prove the effectiveness of the proposed framework via the simulation study, with a gain of +25% clustering accuracy than benchmark methods in a hard case. The interrelations of the three tasks are also analyzed via ablation studies, validating the interrelation assumption. Moreover, a case study in the station clustering based on real passenger flow data is conducted, with quite valuable insights discovered.
"

# Summary. An optional shortened abstract.
summary: ""

tags: ["Tensor", "Tensor Decomposition", "Anomaly Detection", "Spatiotemporal Analysis", "Spatial Time Series", "Smart Mobility"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2404.04403
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
