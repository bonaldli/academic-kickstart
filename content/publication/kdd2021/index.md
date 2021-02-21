---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Individualized Passenger Travel Pattern Multi-Clustering based on Tensor Latent Dirichlet Allocation"
authors: ["admin","Hao-Yan", "Chen-Zhang", "Fugee-Tsung"]
date: 2021-02-08T19:18:44+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-02-08T19:18:44+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 27th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD ’21), Applied Data Science Track" #"The 37th IEEE International Conference on Data Engineering (ICDE 2021), Research Track"
publication_short: "Submitted to 27th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD ’21)" #"The 37th IEEE International Conference on Data Engineering (ICDE 2021) "

abstract: " To be released once published"

# Summary. An optional shortened abstract.
summary: ""
tags: ["individualized analysis", "topic model", "tensor", "spatiotemporal data", "graph structure", "online algorithm"]
categories: ["Conference"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
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
<i class="fas fa-medal"></i> Award:

> This paper is awarded with **Best Student Paper Finalist Award** in INFORMS 2020 Data Mining Section.

After the previous two works in station-wise traffic flow prediction, we realized this mass traffic analysis at a macro level neglects the research value and abundant information of individual passenger travel data. Individualized travel pattern (passenger $u$ travels from origin $o$ to destination $d$  at time $t$) is believed to have higher research value. 
## Challenge
But this task is rather challenging since it is high-dimensional multi-mode Spatiotemporal big data with more 7 million passengers; Also there is multi-clustering structure along each dimension of $o, d, t$; passenger behaviors are also affected by the external environment, such as the locations and surroundings of stations. 
## Methodology
So we proposed a novel Graph-Regularized Tensor LDA model: firstly it represents each trip from one passenger as a 3-dimensional word $\boldsymbol{w} = (w^O, w^D, w^T)$; A passenger with several trips is perceived as a 3-dimensional document $\boldsymbol{\mathcal{W}}^{O \times D \times T}$; Generative processes in the passenger-level and trip-level will be defined along each dimension and the latent topic will be also formulated as a tensor $\boldsymbol{z} = (z^O, z^D, z^T)$; Same as last work we also observed that passengers will have similar patterns both in geographically close stations or functionally similar stations. We further propose to incorporate the graph regularizations into the tensor LDA generative process for origin and destination. We also propose the tensorised variational  expectation-maximization (EM) algorithm to estimate parameters. 
## Results
Eventually, the topics along each dimension of $o, d, t$ are much more interpretable and meaningful than benchmark methods.