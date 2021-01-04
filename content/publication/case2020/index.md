---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Long-Short Term Spatiotemporal Tensor Prediction for Passenger Flow Profile"
authors: ["admin", "Hao Yan", "Chen Zhang", "Fugee Tsung"]
date: 2020-08-22T12:01:43+08:00
doi: "10.1109/LRA.2020.3004785"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-22T12:01:43+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Robotics and Automation Letters"
publication_short: "IEEE Robotics and Automation Letters"

abstract: "Spatiotemporal data is very common in many applications, such as manufacturing systems and transportation systems. It is typically difficult to be accurately predicted given intrinsic complex spatial and temporal correlations. Most of the existing methods based on various statistical models and regularization terms, fail to preserve innate features in data alongside their complex correlations. In this paper, we focus on a tensor-based prediction and propose several practical techniques to improve prediction. For long-term prediction specifically, we propose the ”Tensor Decomposition + 2-Dimensional Auto-Regressive Moving Average (2D-ARMA)” model, and an effective way to update prediction real-time; For shortterm prediction, we propose to conduct tensor completion based on tensor clustering to avoid oversimplifying and ensure accuracy. A case study based on the metro passenger flow data is conducted to demonstrate the improved performance. "

# Summary. An optional shortened abstract.
summary: "This paper is awarded with IEEE CASE 2020 Best Conference Paper Award"

tags: ["Spatiotemporal Analysis", "Tensor Decomposition", "Tensor Completion", "Prediction"]
categories: ["Conference"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ieeexplore.ieee.org/document/9126133
url_code:
url_dataset:
url_poster:
url_project:
url_slides: https://drive.google.com/file/d/1-KEi-SkFNqpu66XMGFZmFzruLDL5esqw/view?usp=sharing
url_source:
url_video: https://drive.google.com/file/d/1Ap6K1qq1pNwtzq1eGDBAwrrIa_SGSbmt/view?usp=sharing

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
<i class="fas fa-medal"></i> Award:

> This paper is awarded with **Best Conference Paper Award** in 2020 IEEE 16th International Conference on Automation Science and Engineering (CASE).


Traffic flow prediction is undoubtedly an essential task for both operational team and citizens. With the collaboration the Hong Kong Metro, we realize  the task to provide the citywide prediction covering all 100 stations simultaneously is quite essential yet rather challenging, especially when the data has strong spatiotemporal correlation. 
## Challenge
We observed two types of spatial correlations and two types of temporal correlations in the data. We have spot that, for spatial correlations: (S1) Geographical correlation: the passenger flow of a station is usually affected by its spatially adjacent neighbors; (S2) Contextual correlations: two stations sharing similar functionalities (business center, residential area or school, etc.) are more likely to have similar passenger flows. For temporal correlations: (T1) Daily correlation: the profile is correlated with previous days of the same week; (T2)  Weekly correlation: the profile is correlated with the same day of previous weeks.

For the metro operational team, to provide long-term (several days ahead) prediction and short-term (several hours ahead) prediction are both important. And there are little work to both consider spatiotemporal correlation and offer citywide long- and short-term prediction. 
## Methodology
To tackle this challenge, we first formulate data as a three-dimensional tensor $\boldsymbol{\mathcal{X}}^{station \times  point \times day}$ with dimension station, day, time point, to preserve the spatiotemporal nature of the data. (1.1) For long-term prediction, we proposed a "2-step 2D-ARMA" tensor prediction model, which firstly uses tensor decomposition to get day-feature matrix $\mathbf{U}^{day}$, and then conducts 2D-ARMA prediction model on this $\mathbf{U}^{day}$, capturing the daily and weekly correlations in a better way. (1.2) Another challenge for long-term prediction is how to update prediction real-time when new data keep arriving. To tackle this, we also propose a recursive dynamic updating method. (2) For short-term prediction,  we first directly used Low Rank Tensor Completion (LRTC) method to treat the prediction horizon as missing part and to complete it. But we found an interesting phenomenon: in homogeneous stations LRTC works well, however, LRTC malfunctions in heterogeneous stations. we proposed a temporary solution for it: a "Tensor Clustering + Tensor Completion" prediction model which first clusters stations and then conducts tensor completion within each station cluster for prediction. 
## Results
Our method improved the prediction results significantly: for long-term prediction, 30\% higher accuracy is achieved; Recursive dynamic updating method could improve the following 3 hours prediction by around 20\%. For short-term prediction, with the homogeneity of stations guaranteed, and the tensor completion within one cluster can improve the prediction by 30\%