---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A General Scenario-agnostic Reinforcement Learning for Traffic Signal Control"
authors: [Haoyuan Jiang, "admin", Lei Bai, Rui Zhao]
date: 2023-02-13T00:29:16+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-02-16T00:29:16+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Intelligent Transportation Systems"
publication_short: "IEEE Transactions on Intelligent Transportation Systems"

abstract: "Reinforcement learning has been recently adopted to revolutionize and optimize traditional traffic signal control systems. Existing methods are either based on a single scenario or multiple independent scenarios, where each scenario has a separate simulation environment with predefined road network topology and traffic signal settings. These models implement training and testing in the same scenario, thus being strictly tied up with the specific setting and sacrificing model generalization heavily. While a few recent models could be trained by multiple scenarios, they require a huge amount of manual labor to label the intersection structure, hindering the model’s generalization. In this work, we aim at a general framework that could eliminate heavy labeling and model a variety of scenarios simultaneously. To this end, we propose a GEneral Scenario-Agnostic (GESA) reinforcement learning framework for traffic signal control with: (1) A general plug-in module to map all different intersections into a unified structure, freeing us from the heavy manual labor to specify the structure of intersections; (2) A unified state and action space to keep the model input and output consistently structured; (3) A large-scale co-training with multiple scenarios, leading to a generic traffic signal control algorithm. In experiments, we demonstrate our algorithm as the first one that can be co-trained with seven different scenarios without manual annotation, and get 17.20% higher rewards than benchmarks. When dealing with a new scenario, our model can still achieve 10.36% higher rewards."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Reinforcement Learning", "Multi-task Learning", "Generalist Agent", "Traffic Signal Control", "Traffic Management", "Spatiotemporal Decision Intelligence", "Model Efficiency"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://openreview.net/forum?id=RKMbC8Tslx
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
