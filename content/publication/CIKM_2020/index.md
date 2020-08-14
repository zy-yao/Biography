---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Recursive Balanced k-Subset Sum Partition for Rule-constrained Resource Allocation."
authors: [Zhuo Li，Jiannong Cao，Zhongyu Yao (2020).]
date: 2020-07-25T16:22:18+08:00
# doi: "-"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-25T16:22:18+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "29th ACM International Conference On Information and Knowledge Management (CIKM 2020)"
publication_short: "CIKM 2020"

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
Rule-constrained resource allocation aims to evenly distribute tasks to different processors under the constraints of a set of allocation rules. Conventional heuristic approach fails to achieve optimal solution while simple brute force method has the defects of extremely high computational complexity.
To address these limitations, we propose “recursive balanced k-subset sum partition (RBkSP)”, in which iterative “cut-oneout” policy is employed that in each round, only one subset is partitioned whose weights of tasks sum up to 1/𝑘 of the
total weight of all tasks in the set. In a single partition, we
first create a dynamic programming table with its elements
recursively computed, then use “zig-zag search” method to
explore the table and find out elements with optimal subset
partition, finally assign them to different places. Afterwards,
to resolve conflicts during allocation, we use heuristic method
which is simple but effective to adjust the allocation of tasks
that are contradicted to specific rules. Testing results show
RBkSP can achieve more balanced allocation with lower
computational complexity over classical benchmarks.