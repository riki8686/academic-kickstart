---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "MalAlert: Detecting Malware in Large-Scale Network Traffic Using Statistical Features"
authors: [Michal Piskozub, Riccardo Spolaor, Ivan Martinovic]
date: 2019-01-25T14:50:57+08:00
doi: "https://doi.org/10.1145/3308897.3308961"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-01-25T14:50:57+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM SIGMETRICS Performance Evaluation Review"
publication_short: "WAIN @ Performance"

abstract: "In recent years, we witness the spreading of a significant variety of malware, which operate and propagate relying on network communications. Due to the staggering growth of traffic in the last years, detecting malicious software has become infeasible on a packet-by-packet basis. In this paper, we address this challenge by investigating malware behaviors and designing a method to detect them relying only on network flow-level data. In our analysis we identify malware types with regards to their impact on a network and the way they achieve their malicious purposes. Leveraging this knowledge, we propose a machine learning-based and privacy-preserving method to detect malware. We evaluate our results on two malware datasets (MalRec and CTU-13) containing traffic of over 65,000 malware samples, as well as one month of network traffic from the University of Oxford containing over 23 billion flows. We show that despite the coarse-grained information provided by network flows and the imbalance between legitimate and malicious traffic, MalAlert can distinguish between different types of malware with the F1 score of 90%."

# Summary. An optional shortened abstract.
summary: ""

tags: [Malware detection, Network traffic analysis, Network flows, Machine learning, Classification, Large networks, Big data]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://dl.acm.org/citation.cfm?id=3308961
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
