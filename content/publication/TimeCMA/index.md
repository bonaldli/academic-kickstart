---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "TimeCMA: Towards LLM-Empowered Time Series Forecasting via Cross-Modality Alignment"
authors: [Chenxi Liu, Qianxiong Xu, Hao Miao, Sun Yang, Lingzheng Zhang, Cheng Long, "admin", Rui Zhao]
date: 2024-06-03T15:01:39+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-07T15:01:39+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "under review of VLDB"
publication_short: "under review of VLDB"

abstract: "The widespread adoption of scalable mobile sensing has led to large amounts of time series data for real-world applications. A fundamental application is multivariate time series forecasting (MTSF), which aims to predict future time series values based on historical observations. Existing MTSF methods suffer from limited parameterization and small-scale training data. Recently, Large language models (LLMs) have been introduced in time series, which achieve promising forecasting performance but incur heavy computational costs. To solve these challenges, we propose TimeCMA, an LLM-empowered framework for time series forecasting with cross-modality alignment. We design a dual-modality encoding module with two branches, where the time series encoding branch extracts relatively low-quality yet pure embeddings of time series through an inverted Transformer. In addition, the LLM-empowered encoding branch wraps the same time series as prompts to obtain high-quality yet entangled prompt embeddings via a Pre-trained LLM. Then, we design a cross-modality alignment module to retrieve high-quality and pure time series embeddings from the prompt embeddings. Moreover, we develop a time series forecasting module to decode the aligned embeddings while capturing dependencies among multiple variables for forecasting. Notably, we tailor the prompt to encode sufficient temporal information into a last token and design the last token embedding storage to reduce computational costs. Extensive experiments on real data offer insight into the accuracy and efficiency of the proposed framework."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Large Language Model", "LLMs for Forcasting", "Prediction", "Time Series", "Natural Language Understanding"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2406.01638
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
