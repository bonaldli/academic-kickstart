---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Critical Perceptual Pre-trained Model for Complex Trajectory Recovery"
authors: [Dedong Li, "admin", Zhishuai Li, Lei Bai, Qingyuan Gong, Lijun Sun, Wolfgang Ketter, Rui Zhao]
date: 2023-11-05T16:08:37+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-04T16:08:37+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "31st ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems"
publication_short: "SIGSPATIAL 2023"

abstract: "The trajectory on the road traffic is commonly collected at a low sampling rate, and trajectory recovery aims to recover a complete and continuous trajectory from the sparse and discrete inputs. Recently, sequential language models have been innovatively adopted for trajectory recovery in a pre-trained manner: it learns road segment representation vectors, which will be used in the downstream tasks. However, existing methods are incapable of handling complex trajectories: when the trajectory crosses remote road segments or makes several turns, which we call critical nodes, the quality of learned representations deteriorates, and the recovered trajectories skip the critical nodes. This work is dedicated to offering a more robust trajectory recovery for complex trajectories. Firstly, we define the trajectory complexity based on the detour score and entropy score and construct the complexity-aware semantic graphs correspondingly. Then, we propose a Multi-view Graph and Complexity Aware Transformer (MGCAT) model to encode these semantics in trajectory pre-training from two aspects: 1) adaptively aggregate the multi-view graph features considering trajectory pattern, and 2) higher attention to critical nodes in a complex trajectory. Such that, our MGCAT is perceptual when handling the critical scenario of complex trajectories. Extensive experiments are conducted on large-scale datasets. The results prove that our method learns better representations for trajectory recovery, with 5.22% higher F1-score overall and 8.16% higher F1-score for complex trajectories particularly."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Transformer", "Graph Machine Learning", "Attention", "Pre-trained Model", "Smart Transportation", "Trajectory", "Spatiotemporal Analysis", "Graph Neural Network"]
categories: ["Conference"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2311.02631
url_code: https://github.com/bonaldli/ComplexTraj
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
