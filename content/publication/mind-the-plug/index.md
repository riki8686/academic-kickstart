---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Mind the plug! Laptop-user recognition through power consumption"
authors: [Mauro Conti, Michele Nati, Enrico Rotundo, Riccardo Spolaor]
date: 2016-05-30T14:45:33+08:00
doi: "https://doi.org/10.1145/2899007.2899009"

# Schedule page publish date (NOT publication's date).
publishDate: 2016-05-30T14:45:33+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM International Workshop on IoT Privacy, Trust, and Security"
publication_short: "IoTPTS @ ASIACCS"

abstract: "

The Internet of Things (IoT) paradigm, in conjunction with the one of smart cities, is pursuing toward the concept of smart buildings, i.e., 'intelligent' buildings able to receive data from a network of sensors and thus to adapt the environment. IoT sensors can monitor a wide range of environmental features such as the energy consumption inside a building at fine-grained level (e.g., for a specific wall-socket). Some smart buildings already deploy energy monitoring in order to optimize the energy use for good purposes (e.g., to save money, to reduce pollution). Unfortunately, such measurements raise a significant amount of privacy concerns.
In this paper, we investigate the feasibility of recognizing the pair laptop-user (i.e., a user using her own laptop) from the energy traces produced by her laptop. We design MTPlug, a framework that achieves this goal relying on supervised machine learning techniques as pattern recognition in multivariate time series. We present a comprehensive implementation of this system and run a thorough set of experiments. In particular, we collected data by monitoring the energy consumption of two groups of laptop users, some office employees and some intruders, for a total of 27 people. We show that our system is able to build an energy profile for a laptop user with accuracy above 80%, in less than 3.5 hours of laptop usage. To the best of our knowledge, this is the first research that assesses the feasibility of laptop users profiling relying uniquely on fine-grained energy traces collected using wall-socket smart meters.
"

# Summary. An optional shortened abstract.
summary: ""

tags: [Laptop, Energy consumption, Energy, Side-channel, Intrusion detection, Machine Learning, Classification]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://dl.acm.org/citation.cfm?id=2899009
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
