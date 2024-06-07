---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SQL-to-Schema Enhances Schema Linking in Text-to-SQL"
authors: [Sun Yang, Qiong Su, Zhishuai Li, Ziyue Li, Hangyu Mao, Chenxi Liu, Rui Zhao]
date: 2024-05-15T15:01:16+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-07T15:01:16+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 35th Database and Expert Systems Applications Conferences and Workshops"
publication_short: "DEXA 2024"

abstract: "In sophisticated existing Text-to-SQL methods exhibit errors in various proportions, including schema-linking errors (incorrect columns, tables, or extra columns), join errors, nested errors, and group-by errors. Consequently, there is a critical need to filter out unnecessary tables and columns, directing the language models attention to relevant tables and columns with schema-linking, to reduce errors during SQL generation. Previous approaches have involved sorting tables and columns based on their relevance to the question, selecting the top-ranked ones for sorting, or directly identifying the necessary tables and columns for SQL generation. However, these methods face challenges such as lengthy model training times, high consumption of expensive GPT-4 tokens in few-shot prompts, or suboptimal performance in schema linking. Therefore, we propose an inventive schema linking method in two steps: Firstly, generate an initial SQL query by utilizing the complete database schema. Subsequently, extract tables and columns from the initial SQL query to create a concise schema. Using CodeLlama-34B, when comparing the schemas obtained by mainstream methods with ours for SQL generation, our schema performs optimally. Leveraging GPT4, our SQL generation method achieved results that are comparable to mainstream Text-to-SQL methods on the Spider dataset."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Large Language Model", "LLMs for Coding", "Text-to-SQL", "Natural Language Understanding"]
tags: []
categories: []
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
