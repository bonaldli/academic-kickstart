---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Tensor Completion for Weakly-dependent Data on Graph for Metro Passenger Flow Prediction"
authors: ["admin","Nurettin Dorukhan Sergin","Hao-Yan", "Chen-Zhang", "Fugee-Tsung"]
date: 2020-04-03T16:32:57+08:00
doi: "https://doi.org/10.1609/aaai.v34i04.5915"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-04-03T16:32:57+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the AAAI Conference on Artificial Intelligence"
publication_short: "Proceedings of the AAAI Conference on Artificial Intelligence, 34(04), 4804-4810."

abstract: "Low-rank tensor decomposition and completion have attracted significant interest from academia given the ubiquity of tensor data. However, the low-rank structure is a global property, which will not be fulfilled when the data presents complex and weak dependencies given specific graph structures. One particular application that motivates this study is the spatiotemporal data analysis. As shown in the preliminary study, weakly dependencies can worsen the low-rank tensor completion performance. In this paper, we propose a novel low-rank CANDECOMP/PARAFAC (CP) tensor decomposition and completion framework by introducing the L1-norm penalty and Graph Laplacian penalty to model the weakly dependency on graph. We further propose an efficient optimization algorithm based on the Block Coordinate Descent for efficient estimation. A case study based on the metro passenger flow data in Hong Kong is conducted to demonstrate improved performance over the regular tensor completion methods."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Tensor Decompositoin", "Tensor Completion", "Graph Structure", "Prediction", "Spatiotemporal Analysis"]
categories: ["AAAI","Conference"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://aaai.org/ojs/index.php/AAAI/article/view/5915
url_code: https://github.com/bonaldli/WDG_TC.git
url_dataset:
url_poster: https://drive.google.com/open?id=19Ysg2IhvoTogM_F9x1j2G9too6BazofL
url_project:
url_slides: https://drive.google.com/open?id=1CY2W_RMOMfHE9xZp0gj-f9SRLtCicZPp
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

> This paper is awarded with **Best Student Paper Finalist Award** in INFORMS 2020 Quality, Statistics, and Reliability (QSR) Section.

## Challenge
From our last paper, we found out low-rank tensor completion tends to ill-perform in heterogeneous stations. This is because LRTC assume a low rank structure in data, i.e. low-rank property implies that data in all stations are strongly and linearly dependent. However, two spatial correlations in station dimension are observed: only stations that are geographically close or functionally similar are more likely to have same passenger flow patterns. We offered a temporary solution by conducting LRTC within each station cluster to guarantee low-rank structure. But we would also like to look for a better solution, a low-rank tensor completion method that could directly handle the data with local spatial correlations. 
## Methodology
Therefore we proposed a tensor completion method for Weakly-dependent Data on Graph (WDG). We formulate the geographical correlation and functional similarity as two graphs, and introduce them as two Laplacian regularizations into LRTC, namely, into station-feature matrix $\mathbf{U}^{station}$, such that if two stations are close on the two graphs, they have similar parameters on $\mathbf{U}^{station}$. Besides, since there are those two graphs on station dimension, if any 2 stations are randomly picked, they’re less likely to be highly-dependent if they’re not connected in either of two graphs. We formulate this weak dependency as a sparse coding via $l_1$-norm, such that a station is represented with only a small amount of highly-related stations as “basis”. 
## Results
We are the first work to provide a Low Rank Tensor Completion solution to weakly-dependent pattern on graphs. And the completion result could achieve 40\% higher accuracy. 