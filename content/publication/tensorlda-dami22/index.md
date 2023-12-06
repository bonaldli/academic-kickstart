---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Individualized Passenger Travel Pattern Multi-Clustering based on Graph Regularized Tensor Latent Dirichlet Allocation"
authors: ["admin","Hao-Yan", "Chen-Zhang", "Fugee-Tsung"]
date: 2022-06-18T19:18:44+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-02-08T19:18:44+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Data Mining and Knowledge Discovery" #"The 37th IEEE International Conference on Data Engineering (ICDE 2021), Research Track"
publication_short: "Data Mining and Knowledge Discovery" #"The 37th IEEE International Conference on Data Engineering (ICDE 2021) "

abstract: " Individual passenger travel patterns have significant value in understanding passenger’s behavior, such as learning the hidden clusters of locations, time, and passengers. The learned clusters further enable commercially beneficial actions such as customized services, promotions, data-driven urban-use planning, peak hour discovery, and so on. However, the individualized passenger modeling is very challenging for the following reasons: 1) The individual passenger travel data are multi-dimensional spatiotemporal big data, including at least the origin, destination, and time dimensions; 2) Moreover, individualized passenger travel patterns usually depend on the external environment, such as the distances and functions of locations, which are ignored in most current works. This work proposes a multi-clustering model to learn the latent clusters along the multiple dimensions of Origin, Destination, Time, and eventually, Passenger (ODT-P). We develop a graph-regularized tensor Latent Dirichlet Allocation (LDA) model by first extending the traditional LDA model into a tensor version and then applies to individual travel data. Then, the external information of stations is formulated as semantic graphs and incorporated as the Laplacian regularizations; Furthermore, to improve the model scalability when dealing with massive data, an online stochastic learning method based on tensorized variational Expectation-Maximization algorithm is developed. Finally, a case study based on passengers in the Hong Kong metro system is conducted and demonstrates that a better clustering performance is achieved compared to state-of-the-arts with the improvement in point-wise mutual information index and algorithm convergence speed by a factor of two."

# Summary. An optional shortened abstract.
summary: ""
tags: ["Tensor Topic Model", "Tensor", "Spatiotemporal Analysis", "Graph Machine Learning", "Trajectory", "Smart Mobility", "Data Efficiency"]
categories: ["Conference"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://link.springer.com/article/10.1007/s10618-022-00842-3
url_code: https://github.com/bonaldli/GR-TensorLDA
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