---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ETC: An Ensemble Transformer Framework for Fetal
Health Classification."
authors: [Zhongyu Yao, Tianhang Chen, Ka-Chun Wong (2024)]
date: 2024-11-29T16:22:18+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-11-29T16:22:18+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2024 6th International Conference on Information Technology and Computer Application"
publication_short: "ITCA 2024"

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

url_code:
url_dataset:
url_video: 
url_poster: 
url_project: #https://carousel.comp.polyu.edu.hk/
url_slides: 
url_source: 
url_pdf: #https://www.zhongyu.site/publication/itca_2024/ETC%20An%20Ensemble%20Transformer%20Framework%20for%20Fetal.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Allocation of the system"
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#projects: ["Big-data-driven Airport Resource Management Engine"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
Fetal health monitoring and assessment play a crucial role in reducing perinatal mortality and ensuring safe childbirth outcomes. While traditional machine learning approaches to fetal health classification have shown promise, they often struggle with capturing complex temporal dependencies and subtle feature interactions in Cardiotocography (CTG) data. To address these limitations, we propose an Ensemble Transformer Classification (ETC) framework that leverages the power of multiple specialized Transformer encoders for enhanced fetal health assessment. Our framework incorporates three key innovations: (1) a dual encoding mechanism combining positional and semantic encoding to better represent CTG features, (2) a multi-head attention mechanism with dynamic weighting for adaptive feature interaction modeling, and (3) a Bagging-based ensemble strategy to improve model robustness and reduce prediction variance. Experimental results on CTG data demonstrate that our ETC framework achieves 94.37% overall accuracy, with particularly strong performance in identifying pathological cases (96% Precision, 93% Recall), significantly outperforming traditional machine learning methods and standard deep learning approaches. The framework shows substantial practical value for clinical diagnostic assistance, telemedicine applications, and medical education. Furthermore, its attention mechanism visualization provides interpretable insights into feature importance, making it particularly suitable for real-world medical applications.