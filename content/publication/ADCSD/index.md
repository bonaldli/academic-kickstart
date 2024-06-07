---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Online Test-Time Adaptation of Spatial-Temporal Traffic Flow Forecasting"
authors: [Pengxin Guo, Pengrong Jin, "admin", Lei Bai, Yu Zhang]
date: 2024-01-08T14:58:27+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-08T14:58:27+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "under review: IEEE Transaction on Intelligent Transport Systems"
publication_short: "under review: IEEE T-ITS"

abstract: "Accurate spatial-temporal traffic flow forecasting is crucial in aiding traffic managers in implementing control measures and assisting drivers in selecting optimal travel routes. Traditional deep-learning based methods for traffic flow forecasting typically rely on historical data to train their models, which are then used to make predictions on future data. However, the performance of the trained model usually degrades due to the temporal drift between the historical and future data. To make the model trained on historical data better adapt to future data in a fully online manner, this paper conducts the first study of the online test-time adaptation techniques for spatial-temporal traffic flow forecasting problems. To this end, we propose an Adaptive Double Correction by Series Decomposition (ADCSD) method, which first decomposes the output of the trained model into seasonal and trend-cyclical parts and then corrects them by two separate modules during the testing phase using the latest observed data entry by entry. In the proposed ADCSD method, instead of fine-tuning the whole trained model during the testing phase, a lite network is attached after the trained model, and only the lite network is fine-tuned in the testing process each time a data entry is observed. Moreover, to satisfy that different time series variables may have different levels of temporal drift, two adaptive vectors are adopted to provide different weights for different time series variables. Extensive experiments on four real-world traffic flow forecasting datasets demonstrate the effectiveness of the proposed ADCSD method. The code is available at https://github.com/Pengxin-Guo/ADCSD."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Spatiotemporal Analysis", "Spatial Time Series", "Smart Mobility", "Domain Adaptation", "Prediction"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2401.04148
url_code: https://github.com/Pengxin-Guo/ADCSD
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
