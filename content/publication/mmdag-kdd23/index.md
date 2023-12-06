---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "MM-DAG: Multi-task DAG Learning for Multi-modal Data--with Application for Traffic Congestion Analysis"
authors: [Tian Lan, "admin", Zhishuai Li, Lei Bai, Man Li, Fugee Tsung, Wolfgang Ketter, Rui Zhao, Chen Zhang]
date: 2023-08-04T00:28:34+01:00
doi: "https://doi.org/10.1145/3580305.3599436"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-06T00:28:34+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining"
publication_short: "SIGKDD 2023"

abstract: "This paper proposes to learn Multi-task, Multi-modal Direct Acyclic Graphs (MM-DAGs), which are commonly observed in complex systems, e.g., traffic, manufacturing, and weather systems, whose variables are multi-modal with scalars, vectors, and functions. This paper takes the traffic congestion analysis as a concrete case, where a traffic intersection is usually regarded as a DAG. In a road network of multiple intersections, different intersections can only have some overlapping and distinct variables observed. For example, a signalized intersection has traffic light-related variables, whereas unsignalized ones do not. This encourages the multi-task design: with each DAG as a task, the MM-DAG tries to learn the multiple DAGs jointly so that their consensus and consistency are maximized. To this end, we innovatively propose a multi-modal regression for linear causal relationship description of different variables. Then we develop a novel Causality Difference (CD) measure and its differentiable approximator. Compared with existing SOTA measures, CD can penalize the causal structural difference among DAGs with distinct nodes and can better consider the uncertainty of causal orders. We rigidly prove our design's topological interpretation and consistency properties. We conduct thorough simulations and one case study to show the effectiveness of our MM-DAG."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Causal Inference", "Traffic Management", "Spatiotemporal Analysis", "Multi-task Learning"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://dl.acm.org/doi/10.1145/3580305.3599436
url_code: https://github.com/Lantian72/MM-DAG
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
