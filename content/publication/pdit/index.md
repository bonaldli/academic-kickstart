---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "PDiT: Interleaving Perception and Decision-making Transformers for Deep Reinforcement Learning"
authors: [Hangyu Mao, Rui Zhao, "admin", Zhiwei Xu, Hao Chen, Yiqun Chen, Bin Zhang, Zhen Xiao, Junge Zhang, Jiangjin Yin]
date: 2024-06-02T23:58:01+02:00
doi: "10.5555/3635637.3662995"

# Schedule page publish date (NOT publication's date).
publishDate: 2024-05-06T23:58:01+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 23rd International Conference on Autonomous Agents and Multiagent Systems"
publication_short: "AAMAS 2024"

abstract: "Designing better deep networks and better reinforcement learning (RL) algorithms are both important for deep RL. This work studies the former. Specifically, the Perception and Decision-making Interleaving Transformer (PDiT) network is proposed, which cascades two Transformers in a very natural way: the perceiving one focuses on the environmental perception by processing the observation at the patch level, whereas the deciding one pays attention to the decision-making by conditioning on the history of the desired returns, the perceiver's outputs, and the actions. Such a network design is generally applicable to a lot of deep RL settings, e.g., both the online and offline RL algorithms under environments with either image observations, proprioception observations, or hybrid image-language observations. Extensive experiments show that PDiT can not only achieve superior performance than strong baselines in different settings but also extract explainable feature representations. Our code is available at https://github.com/maohangyu/PDiT."

# Summary. An optional shortened abstract.
summary: 

tags: ["Reinforcement Learning", "Multi-Modality", "Transformer"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2312.15863
url_code: https://github.com/maohangyu/PDiT
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
**TL;DR**: In PDiT, we proposed a Transformer-interleaving-Transformer architecture for specialized environment perception and decision-making: it is a multi-modal generalist agent for vision, language, and numerics!