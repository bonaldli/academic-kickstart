---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Tensor Dirichlet Process Multinomial Mixture Model with Graphs for Passenger Trajectory Clustering"
authors: ["admin", Hao Yan, Chen Zhang, Wolfgang Ketter, Fugee Tsung]
date: 2023-11-05T23:58:51+01:00
doi: "https://doi.org/10.1145/3615886.3627749"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-05T23:58:51+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "31st ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems"
publication_short: "SIGSPATIAL 2023"

abstract: "Passenger clustering based on trajectory records is essential for transportation operators. However, existing methods cannot easily cluster the passengers due to the hierarchical structure of the passenger trip information, including multiple trips within each passenger and multi-dimensional information about each trip. Furthermore, existing approaches rely on an accurate specification of the clustering number to start. Finally, existing methods do not consider spatial semantic graphs such as geographical proximity and functional similarity between the locations. In this paper, we propose a novel tensor Dirichlet Process Multinomial Mixture model with graphs, which can preserve the hierarchical structure of the multi-dimensional trip information and cluster them in a unified one-step manner with the ability to determine the number of clusters automatically. The spatial graphs are utilized in community detection to link the semantic neighbors. We further propose a tensor version of Collapsed Gibbs Sampling method with a minimum cluster size requirement. A case study based on Hong Kong metro passenger data is conducted to demonstrate the automatic process of cluster amount evolution and better cluster quality measured by within-cluster compactness and cross-cluster separateness."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Tensor Topic Model", "Graph Machine Learning", "Trajectory", "Spatiotemporal Analysis", "Tensor"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://dl.acm.org/doi/abs/10.1145/3615886.3627749
url_code: https://github.com/bonaldli/TensorDPMM-G
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
