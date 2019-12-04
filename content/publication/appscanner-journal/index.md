---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Robust smartphone app identification via encrypted network traffic analysis"
authors: [Vincent F Taylor, Riccardo Spolaor, Mauro Conti, Ivan Martinovic]
date: 2017-08-09T14:45:13+08:00
doi: "10.1109/TIFS.2017.2737970"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-28T14:45:13+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Information Forensics and Security"
publication_short: "IEEE TIFS"

abstract: "The apps installed on a smartphone can revealmuch information about a user, such as their medical conditions,sexual orientation, or religious beliefs. Additionally, the presenceor absence of particular apps on a smartphone can informan adversary who is intent on attacking the device. In thispaper, we show that a passive eavesdropper can feasibly identifysmartphone apps by fingerprinting the network traffic that theysend. Although SSL/TLS hides the payload of packets, side-channel data such as packet size and direction is still leaked fromencrypted connections. We use machine learning techniques toidentify smartphone apps from this side-channel data. In additionto merely fingerprinting and identifying smartphone apps, weinvestigate how app fingerprints change over time, across devicesand across different versions of apps. Additionally, we introducestrategies that enable our app classification system to identify andmitigate the effect of ambiguous traffic, i.e., traffic in commonamong apps such as advertisement traffic. We fully implementeda framework to fingerprint apps and ran a thorough set ofexperiments to assess its performance. We fingerprinted 110 of the most popular apps in the Google Play Store and were ableto identify them six months later with up to 96% accuracy.Additionally, we show that app fingerprints persist to varyingextents across devices and app versions"

# Summary. An optional shortened abstract.
summary: ""

tags: [Network traffic analysis, Security, Privacy, Android, Mobile device, Classification, Ambiguous]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/1704.06099.pdf
url_code: https://github.com/vftaylor/appscanner 
url_dataset: https://github.com/vftaylor/appscanner 
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
projects: [Appscanner]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
