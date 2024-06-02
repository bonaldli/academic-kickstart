---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "VisionTraj: A Noise-Robust Trajectory Recovery Framework based on Large-scale Camera Network"
authors: [Zhishuai Li, "admin", Xiaoru Hu, Guoqing Du, Yunhao Nie, Feng Zhu, Lei Bai, Rui Zhao]
date: 2024-06-02T18:23:55+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-11T18:23:55+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "under review: IEEE Transactions on Intelligent Vehicles"
publication_short: "IEEE T-IV"

abstract: "Trajectory recovery based on the snapshots from the city-wide multi-camera network facilitates urban mobility sensing and driveway optimization. The state-of-the-art solutions devoted to such a vision-based scheme typically incorporate predefined rules or unsupervised iterative feedback, struggling with multi-fold challenges such as lack of open-source datasets for training the whole pipeline, and the vulnerability to the noises from visual inputs. In response to the dilemma, this paper proposes VisionTraj, the first learning-based model that reconstructs vehicle trajectories from snapshots recorded by road network cameras. Coupled with it, we elaborate on two rational vision-trajectory datasets, which produce extensive trajectory data along with corresponding visual snapshots, enabling supervised vision-trajectory interplay extraction. Following the data creation, based on the results from the off-the-shelf multi-modal vehicle clustering, we first re-formulate the trajectory recovery problem as a generative task and introduce the canonical Transformer as the autoregressive backbone. Then, to identify clustering noises (e.g., false positives) with the bound on the snapshots' spatiotemporal dependencies, a GCN-based soft-denoising module is conducted based on the fine- and coarse-grained Re-ID clusters. Additionally, we harness strong semantic information extracted from the tracklet to provide detailed insights into the vehicle's entry and exit actions during trajectory recovery. The denoising and tracklet components can also act as plug-and-play modules to boost baselines. Experimental results on the two hand-crafted datasets show that the proposed VisionTraj achieves a maximum +11.5% improvement against the sub-best model."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Spatiotemporal Analysis", "Trajectory", "Graph Neural Network", "Graph Machine Learning", "Trajectory", "Computer Vision"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2312.06428
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
