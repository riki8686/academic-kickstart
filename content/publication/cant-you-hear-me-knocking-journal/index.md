---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Analyzing Android Encrypted Network Traffic to Identify User Actions"
authors: [Mauro Conti, Luigi Vincenzo Mancini, Riccardo Spolaor, Nino Vincenzo Verde ]
date: 2015-09-14T14:43:53+08:00
doi: "10.1109/TIFS.2015.2478741"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-28T14:43:53+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Information Forensics and Security"
publication_short: "IEEE TIFS"

abstract: "Mobile devices can be maliciously exploited to violate the privacy of people. In most attack scenarios, the adversary takes the local or remote control of the mobile device, by leveraging a vulnerability of the system, hence sending back the collected information to some remote web service. In this paper, we consider a different adversary, who does not interact actively with the mobile device, but he is able to eavesdrop the network traffic of the device from the network side (e.g., controlling a Wi-Fi access point). The fact that the network traffic is often encrypted makes the attack even more challenging. In this paper, we investigate to what extent such an external attacker can identify the specific actions that a user is performing on her mobile apps. We design a system that achieves this goal using advanced machine learning techniques. We built a complete implementation of this system, and we also run a thorough set of experiments, which show that our attack can achieve accuracy and precision higher than 95%, for most of the considered actions. We compared our solution with the three state-of-the-art algorithms, and confirming that our system outperforms all these direct competitors."

# Summary. An optional shortened abstract.
summary: ""

tags: [Network traffic analysis, Android, Mobile device, User actions, Machine Learning, Clustering, Classification]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: files/android2015.pdf
url_code: https://spritz.math.unipd.it/projects/analyzinguseractionsandroid/
url_dataset: https://spritz.math.unipd.it/projects/analyzinguseractionsandroid/
url_poster:
url_project: https://spritz.math.unipd.it/projects/analyzinguseractionsandroid/
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
