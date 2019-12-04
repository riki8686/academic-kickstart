---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "BOTection: Bot Detection by Building Markov Chain Models of Bots Network Behavior"
authors: [ Bushra Alahmadi, Enrico Mariconti, Riccardo Spolaor, Gianluca Stringhini,
Ivan Martinovic]
date: 2020-06-05T14:52:01+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-28T14:52:01+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM ASIA Conference on Computer and Communications Security"
publication_short: "ACM ASIACCS"

abstract: "Botnets continue to be a threat to organizations, thus various machine learning-based botnet detectors have been proposed. However, the capability of such systems in detecting new or unseen
botnets is crucial to ensure its robustness against the rapid evolution of botnets. Moreover, it prolongs the effectiveness of the
system in detecting bots, avoiding frequent and time-consuming
classifier re-training. We present BOTection, a privacy-preserving
bot detection system that models the bot network flow behavior
as a Markov Chain. Using the state transitions extracted from the
Markov chains, we train a classifier to first detect network flows
produced by bots, and then identify their bot families. BOTection is
content-agnostic and resilient to encryption, relying on high-level
network features to model bots’ network behavior. We evaluate
our system on a dataset of over 7M malicious flows from 12 botnet
families, showing its capability of detecting bots’ network traffic
with 99.78% F-measure. Notably, due to the modeling of general bot
network behavior, BOTection can detect traffic belonging to unseen
bot families that launch similar attacks to those previously known
with an F-measure of 93.03%. We also assess BOTection robustness
in classifying a bot family with a 99.09% F-measure score, which is
essential in understanding their behavior for effective detection."

# Summary. An optional shortened abstract.
summary: ""

tags: [Network traffic analysis, Sequence analysis, Markov chain, Botnet, Malware, Detection]
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
