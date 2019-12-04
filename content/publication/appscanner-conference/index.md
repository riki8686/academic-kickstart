---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Appscanner: Automatic fingerprinting of smartphone apps from encrypted network traffic"
authors: [Vincent F Taylor, Riccardo Spolaor, Mauro Conti, Ivan Martinovic]
date: 2016-03-21T14:45:07+08:00
doi: "10.1109/EuroSP.2016.40"


# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-28T14:45:07+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE European Symposium on Security and Privacy"
publication_short: "IEEE EuroS&P"

abstract: "Automatic fingerprinting and identification of smartphone apps is becoming a very attractive data gathering technique for adversaries, network administrators, investigators and marketing agencies. In fact, the list of apps installed on a device can be used to identify vulnerable apps for an attacker to exploit, uncover a victim’s use of sensitive apps, assist network planning, and aid marketing. However, app fingerprinting is complicated by the vast number of apps available for download, the wide range of devices they may be installed on, and the use of payload encryption protocols such as HTTPS/TLS.
In this paper, we present a novel methodology and a framework implementing it, called AppScanner, for the automatic fingerprinting and real-time identification of Android apps from their encrypted network traffic. To build app fingerprints, we run apps automatically on a physical device to collect their network traces. We apply various processing strategies to these network traces before extracting the features that are used to train our supervised learning algorithms. Our fingerprint generation methodology is highly scalable and does not rely on inspecting packet payloads; thus our framework works even when HTTPS/TLS is employed. We built and deployed this lightweight framework and ran a thorough set of experiments to assess its performance. We automatically profiled 110 of the most popular apps in the Google Play Store and were later able to re-identify them with more than 99% accuracy."

# Summary. An optional shortened abstract.
summary: ""

tags: [Network traffic analysis, Security, Privacy, Android, Mobile device, Classification]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: files/appscanner2016.pdf
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
projects: [Appscanner]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
