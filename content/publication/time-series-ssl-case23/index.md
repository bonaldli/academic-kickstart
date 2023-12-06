---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Correlated Time Series Self-Supervised Representation Learning via Spatiotemporal Bootstrapping"
authors: [Luxuan Wang, Lei Bai, "admin", Rui Zhao, Fugee Tsung]
date: 2023-09-28T00:27:42+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-06T00:27:42+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2023 IEEE 19th International Conference on Automation Science and Engineering (CASE)"
publication_short: "IEEE CASE 2023"

abstract: "Correlated time series analysis plays an important role in many real-world industries. Learning an efficient representation of this large-scale data for further downstream tasks is necessary but challenging. In this paper, we propose a time-step-level representation learning framework for individual instances via bootstrapped spatiotemporal representation prediction. We evaluated the effectiveness and flexibility of our representation learning framework on correlated time series forecasting and cold-start transferring the forecasting model to new instances with limited data. A linear regression model trained on top of the learned representations demonstrates our model performs best in most cases. Especially compared to representation learning models, we reduce the RMSE, MAE, and MAPE by 37%, 49%, and 48% on the PeMS-BAY dataset, respectively. Furthermore, in real-world metro passenger flow data, our framework demonstrates the ability to transfer to infer future information of new cold-start instances, with gains of 15%, 19%, and 18%. "

# Summary. An optional shortened abstract.
summary: ""

tags: ["Self-Supervised Learning", "Contrastive Learning", "Spatial Time Series", "Spatiotemporal Analysis", "Smart Mobility", "Model Efficiency"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2306.06994
url_code: https://github.com/bonaldli/Spatiotemporal-TS-Representation-Learning
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
