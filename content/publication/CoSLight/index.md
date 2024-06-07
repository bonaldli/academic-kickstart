---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "CoSLight: Co-optimizing Collaborator Selection and Decision-making to Enhance Traffic Signal Control"
authors: [Jingqing Ruan, Ziyue Li, Hua Wei, Haoyuan Jiang, Jiaming Lu, Xuantang Xiong, Hangyu Mao, Rui Zhao]
date: 2024-08-25T15:01:26+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-07T15:01:26+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Effective multi-intersection collaboration is pivotal for reinforcement-learning-based traffic signal control to alleviate congestion. Existing work mainly chooses neighboring intersections as collaborators. However, quite an amount of congestion, even some wide-range congestion, is caused by non-neighbors failing to collaborate. To address these issues, we propose to separate the collaborator selection as a second policy to be learned, concurrently being updated with the original signal-controlling policy. Specifically, the selection policy in real-time adaptively selects the best teammates according to phase- and intersection-level features. Empirical results on both synthetic and real-world datasets provide robust validation for the superiority of our approach, offering significant improvements over existing state-of-the-art methods. "

# Summary. An optional shortened abstract.
summary: ""

tags: ["Reinforcement Learning", "Traffic Signal Control", "Traffic Management", "Spatiotemporal Decision Intelligence", "Spatiotemporal Analysis", "Smart Mobility"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2405.17152
url_code: https://github.com/AnonymousAccountss/CoSLight
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

What life mottos have we learned from traffic signal control? Wait! What?
Yes, we learned that **“you are your biggest collaborator”** and **“Collaboration should be mutually reciprocal”** from the traffic light!

Every driver would have realized that the traffic patterns in different regions (residential v.s. downtown) at different hours (midday v.s. evening peak) are quite different. The same should have been true of the traffic signal coordination! In our CoSLight, we co-optimize the collaborating policy ρ (choosing which traffic light as a collaborator) and the decision-making policy π (delivering which traffic control phase for the next timeslot). It turns out to be working very, Very, VERY well: our CoSLight can choose different sets of traffic lights for collaboration at different times!

And we also learned life philosophies from the traffic light agents, very (ironically) deep:
(1) When we drop the traffic light itself from being its own collaborator, the performance drops 2%: “You are your biggest collaborator”.
(2) When you collaborate with me, but I don't collaborate with you, a.k.a, not being mutually reciprocal (mathematically not being symmetric), the performance drops 300%!!!: “Collaboration should be mutually reciprocal”.

All right, “collaboration should be mutually reciprocal”: we learned the important lesson the hard way...

