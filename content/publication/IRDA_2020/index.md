---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "IRDA: Incremental Reinforcement Learning for Dynamic Resource Allocation."
authors: [Jia Wang, Jiannong Cao, Senzhang Wang, Zhongyu Yao, and Wengen Li (2020).]
date: 2020-06-25T16:22:18+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-25T16:22:18+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Big Data, 2020"
publication_short: "IEEE Trans. Big Data"

abstract: ""

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true #false

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
  caption: "The overview of the proposed incremental reinforcement learning method"
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["Big-data-driven Airport Resource Management Engine"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
We mine the task patterns from the large volume of historical allocation data and propose a
reinforcement learning model termed IRDA to learn the allocation strategy in an incremental way. We observe that historical allocation
data is usually generated from the daily repeated operations, which is not independent and identically distributed. Training with partial of
this dataset can make the allocation strategy converged already, thereby wasting a lot of remaining data. To improve the learning
efficiency, we partition the whole historical allocation big dataset into multi-batch datasets, which forces the agent to continuously
“explore” and learn on the distinct state spaces. IRDA reuses the strategy learned from the previous batch dataset and adapts it to the
learning on the next batch dataset, so as to incrementally learn from multi-batch datasets and improve the allocation strategy. We apply
the proposed method to handle baggage carousel allocation at Hong Kong International Airport (HKIA). The experimental results show
that IRDA is capable of incrementally learning from multi-batch datasets, and improves the baggage carousel resource utilization by
around 51:86% compared to the current baggage carousel allocation system at HKIA.