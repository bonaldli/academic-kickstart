---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Profile Decomposition based Hybrid Transfer Learning for Cold-start Data Anomaly Detection"
authors: ["admin", "Ke-Zhang","Hao-Yan", "Fugee-Tsung"]
date: 2021-01-04T18:32:48+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-01-04T18:32:48+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "The ACM Transactions in Knowledge Discovery from Data (TKDD)"
publication_short: "Under revision in The ACM Transactions in Knowledge Discovery from Data (TKDD)"

abstract: "Anomaly detection is an essential task for quality management in smart manufacturing. An accurate data-driven detection method usually needs enough data and labels. However, in practice, there commonly exist newly set-up processes in manufacturing, and they only have quite limited data available for analysis. Borrowing the name from the recommender system, we call this process a cold-start process. The sparsity of anomaly, the deviation of the profile, and noise aggravate the detection difficulty.

Transfer learning could help to detect anomalies for cold-start processes by transferring the knowledge from more experienced processes to the new processes. However, the existing transfer learning and multi-task learning frameworks are established on task- or domain-level relatedness. We observe instead, within a domain, some components (background and anomaly) share more commonality, others (profile deviation and noise) not. To this end, we propose a more delicate component-level transfer learning scheme, i.e., decomposition-based hybrid transfer learning (DHTL): It first decomposes a domain (e.g., a data source containing profiles) into different components (smooth background, profile deviation, anomaly, and noise); then, each component’s transferability is analyzed by expert knowledge; Lastly, different transfer learning techniques could be tailored accordingly. We adopted the Bayesian probabilistic hierarchical model to formulate parameter transfer for the background, and “L2,1+L1”-norm to formulate low dimension feature-representation transfer for the anomaly. An efficient algorithm based on Block Coordinate Descend is proposed to learn the parameters. A case study based on glass coating pressure profiles demonstrates the improved accuracy and completeness of detected anomaly, and a simulation demonstrates the fidelity of the decomposition results."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Profile Monitoring", "Functional Data", "Transfer Learning", "Anomaly Detection", "Model Efficiency"]
categories: ["Journal"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
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
