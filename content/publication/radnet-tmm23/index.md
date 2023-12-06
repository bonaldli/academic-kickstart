---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Relation-Aware Distribution Representation Network for Person Clustering With Multiple Modalities"
authors: [Kaijian Liu, Shixiang Tang, "admin", Zhishuai Li, Lei Bai, Feng Zhu, Rui Zhao]
date: 2023-08-22T00:28:19+01:00
doi: "https://doi.org/10.1109/TMM.2023.3304454"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-06T00:28:19+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Multimedia"
publication_short: "IEEE Transactions on Multimedia"

abstract: "Person clustering with multi-modal clues, including faces, bodies, and voices, is critical for various tasks, such as movie parsing and identity-based movie editing. Related methods such as multi-view clustering mainly project multi-modal features into a joint feature space. However, multi-modal clue features are usually rather weakly correlated due to the semantic gap from the modality-specific uniqueness. As a result, these methods are not suitable for person clustering. In this paper, we propose a Relation- Aware Distribution representation Network (RAD-Net) to generate a distribution representation for multi-modal clues. The distribution representation of a clue is a vector consisting of the relation between this clue and all other clues from all modalities, thus being modality agnostic and good for person clustering. Accordingly, we introduce a graph-based method to construct distribution representation and employ a cyclic update policy to refine distribution representation progressively. Our method achieves substantial improvements of +6% and +8.2% in F-score on the Video Person-Clustering Dataset (VPCD) and VoxCeleb2 multi-view clustering dataset, respectively."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Multi-modality", "Computer Vision"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ieeexplore.ieee.org/abstract/document/10226251
url_code: https://github.com/bonaldli/RADNet
url_dataset: https://www.robots.ox.ac.uk/~vgg/data/Video_Person_Clustering/
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
