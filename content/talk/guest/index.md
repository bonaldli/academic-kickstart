---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Advanced Machine Learning for Smart Transportation"
event: "Guest lecture on ISYE 7204 Informatics in Production and Service System at Georgia Tech"
event_url:
location: Zoom
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "Intelligent Transport Systems (ITS) have been an essential chapter in smart city blueprint. There are numbers of real practical applications of ITS: For instance, when you are driving on the road, the ITS could predict how crowded the traffic will be in 15 minutes. It can also give you some personalized recommendations about your route planning etc. When the traffic becomes packed, an ITS may intelligently control the traffic signal adaptively. And if a congestion happens, the ITS could also help to detect the potential cause and predict how the congestion spread. 
Overall, the universal goal of an ITS is to improve the traffic condition via machine learning and artificial intelligent. But the questions are: what kind of data are we expected from the ITS? What kind of tasks are under the stage spotlight? And what kind of techniques under the umbrella of “machine learning” could offer efficient and accurate solutions? In the series of these two lectures, we will voyage the journey and find the answer together. Throughout the journey, you will see this term “spatiotemporal” or “spatial-temporal” a lot. Spot on! The traffic data is one of the most typical spatiotemporal data. And the core to make our algorithm work well is to capture these spatiotemporal correlations. If we categorize the ITS problem more detailed, we will find out there are three types of domains in ITS, and they are: (1) Static Data Analysis (e.g., flow, speed, demand), (2) Dynamic Data Analysis (e.g., trajectory), and (3) Traffic Management (e.g., traffic signal control, congestion management). We will cover all these three domains in our lectures. Last but not the least, we will offer abundant resources including famous research papers, public datasets, open source codes, and so on if you are interested in this research area."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2023-01-30T15:30:00+01:00
date_end: 2023-01-30T16:45:00+01:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2023-01-02T16:15:13+01:00

authors: [admin]
tags: [Intelligent Transport Systems, Smart Mobility, Spatiotemporal Analysis, Tensor, Topic Model, Causal Inference, Contrastive Learning]

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides: 

url_code:
url_pdf: https://drive.google.com/open?id=10flGnmEzIsPo6YFUhUAdim5VYlW_TyNB&authuser=bobbyli1994%40gmail.com&usp=drive_fs
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
---------------
## **Details:** 

#### 0. Syllabus:  
The syllabus is available [here](https://drive.google.com/open?id=10flGnmEzIsPo6YFUhUAdim5VYlW_TyNB&authuser=bobbyli1994%40gmail.com&usp=drive_fs)

#### 1. Lecture One: High-dimensional Data (Tensor) in Smart Transportation 
  - **Time**: 3:30PM-4:45PM, 30 Jan 2023 (65-70min Lecture, 5-10min Q&A) 
  - **Location**: Zoom (https://gatech.zoom.us/j/97394420485, Meeting ID: 973 9442 0485) 
  - **Description**: In the first lecture, we will discuss how the high-dimensional data analytics, i.e., tensor methods, could well formulate the traffic data both spatially and temporally, and we will look at the most popular tasks in ITS: demand prediction, and travel pattern clustering. Specifically, we will discuss Tensor Decomposition, Tensor Completion for demand prediction, and Tensor Topic Models for travel pattern clustering.

![Tensor in ITS](tensor.png "caption")


#### 2. Lecture Two: Deep Learning in Smart Transportation  
  - **Time**: 3:30PM-4:45PM, 01 Feb 2023 (65-70min Lecture, 5-10min Q&A) 
  - **Location**: Zoom (https://gatech.zoom.us/j/97394420485, Meeting ID: 973 9442 0485) 
  - **Description**: In the second lecture, more deep learning related methods will be introduced. Specifically, we will discuss how Self-Supervised Learning can be leveraged to deal with static time-series data such as traffic flow. We will also discuss how Contrastive Learning could learn more robust representation for dynamic trajectory. Last but not the least, we will also leverage Deep Reinforcement Learning into traffic signal control and Deep Causal Inference into traffic congestion reasoning.

![DL in ITS](dl.png "caption")