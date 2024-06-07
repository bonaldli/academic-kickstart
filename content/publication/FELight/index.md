---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "FELight: Fairness-Aware Traffic Signal Control Via Sample-Efficient Reinforcement Learning"
authors: [Xinqi Du, Ziyue Li, Cheng Long, Yongheng Xing, Philip S. Yu, Hechang Chen]
date: 2024-03-18T14:59:50+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-07T14:59:50+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Knowledge and Data Engineering"
publication_short: "IEEE T-KDE"

abstract: "Traffic congestion is becoming an increasingly prominent problem, and intelligent traffic signal control methods can effectively alleviate it. Recently, there has been a growing trend of applying reinforcement learning to traffic signal control for adaptive signal scheduling. However, most existing methods focus on improving traffic performance while neglecting the issue of scheduling fairness, resulting in long waiting time for some vehicles. Some works attempt to address fairness issues but often sacrifice transport performance. Furthermore, existing methods overlook the challenge of sample efficiency, especially when dealing with diversity-limited traffic data. Therefore, we propose a F airness-aware and sample- E fficient traffic signal control method called FELight. Specifically, we first design a novel fairness metric and integrate it into decision process to penalize cases with high latency by setting a threshold for activating the fairness mechanism. Theoretical comparison with other fairness works proves why and when our fairness could bring advantages. Moreover, counterfactual data augmentation is employed to enrich interaction data, enhancing the sample efficiency of FELight. Self-supervised state representation is introduced to extract informative features from raw states, further improving sample efficiency. Experiments on real traffic datasets demonstrate that FELight provides relatively fairer traffic signal control without compromising performance compared to state-of-the-art approaches. "

# Summary. An optional shortened abstract.
summary: ""

tags: ["Reinforcement Learning", "Smart Mobility", "Traffic Signal Control", "Traffic Management", "Model Fairness", "Spatiotemporal Decision Intelligence", "Spatiotemporal Analysis"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ieeexplore.ieee.org/abstract/document/10471901
url_code: https://github.com/dxnbbsw/FELight
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
