---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "DuaLight: Enhancing Traffic Signal Control by Leveraging Scenario-Specific and Scenario-Shared Knowledge"
authors: [Jiaming Lu, Jingqing Ruan, Haoyuan Jiang, "admin", Hangyu Mao, Rui Zhao]
date: 2024-05-06T18:30:13+02:00
doi: "10.5555/3635637.3662986"

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

abstract: "Reinforcement learning has been revolutionizing the traditional traffic signal control task, showing promising power to relieve congestion and improve efficiency. However, the existing methods lack effective learning mechanisms capable of absorbing dynamic information inherent to a specific scenario and universally applicable dynamic information across various scenarios. Moreover, within each specific scenario, they fail to fully capture the essential empirical experiences about how to coordinate between neighboring and target intersections, leading to sub-optimal system-wide outcomes. Viewing these issues, we propose DuaLight, which aims to leverage both the experiential information within a single scenario and the generalizable information across various scenarios for enhanced decision-making. Specifically, DuaLight introduces a scenario-specific experiential weight module with two learnable parts: Intersection-wise and Feature-wise, guiding how to adaptively utilize neighbors and input features for each scenario, thus providing a more fine-grained understanding of different intersections. Furthermore, we implement a scenario-shared Co-Train module to facilitate the learning of generalizable dynamics information across different scenarios. Empirical results on both real-world and synthetic scenarios show DuaLight achieves competitive performance across various metrics, offering a promising solution to alleviate traffic congestion, with 3-7% improvements. The code is available under: https://github.com/lujiaming-12138/DuaLight."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Reinforcement Learning", "Traffic Signal Control", "Spatiotemporal Decision Intelligence", "Spatiotemporal Analysis", "Smart Mobility", "Generalist Agent"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://dl.acm.org/doi/10.5555/3635637.3662986
url_code: https://github.com/lujiaming-12138/DuaLight
url_dataset: https://github.com/lujiaming-12138/DuaLight
url_poster:
url_project:
url_slides:
url_source: https://github.com/lujiaming-12138/DuaLight
url_video: https://github.com/lujiaming-12138/DuaLight

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "A Generalist Agent of Global and Local Knowledge"
  focal_point: "Smart"
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
