---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: " No Free Charge Theorem 2.0: How to Steal Private Information from a Mobile Device Using a Powerbank"
event: "BlackHat Europe 2018"
event_url: "https://www.blackhat.com/eu-18/briefings/schedule/#no-free-charge-theorem-20-how-to-steal-private-information-from-a-mobile-device-using-a-powerbank-12630"
location: "London"
address:
  street:
  city:
  region:
  postcode:
  country: "United Kingdom"
summary:
abstract: "Thanks to their omnipresence and multi-purposeness, users rely on smartphones to execute in few touches a wide range of privacy-related operation, such as accessing bank accounts, checking emails, or transferring money. While not long time ago users were seeking constant Internet connection (e.g., via free Wi-Fi hotspot), now they also look for energy sources to recharge their smartphones' battery, due to the use of more energy-draining apps (e.g., Pokémon Go).

This phenomenon has led to the diffusion of free charging stations in public places and the marketing of portable batteries a.k.a. powerbanks. Despite the preventive measures implemented by Android's developers in order to prevent data transfer via USB cable (i.e., 'Charging only' mode), we are able to exploit a hidden communication channel which leverages only the electrical current provided for charging the smartphone.

On one side, a malicious app (which can be disguised as a legitimate, clean app) installed on the victim's phone, which only requires wakelock permission (i.e., to wake up the phone when it is idle), remains silent until the device is plugged to a USB port and left unattended. Then, such app begins transmitting sensitive data coded in energy consumption peaks. On the other side, the energy provider (e.g., powerbank) is able to measure such peaks and then reconstruct the transmitted information. All this happens without the malicious app's access to Internet or other permissions, except for the information that it wants to exfiltrate."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2018-12-05T10:47:42+08:00
date_end: 2018-12-05T10:47:42+08:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2018-12-04T10:47:42+08:00

authors: [Riccardo Spolaor, Riccardo Bonafede, Veelasha Moonsamy, Mauro Conti]
tags: [Applied Security, Mobile ]

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides: http://i.blackhat.com/eu-18/Wed-Dec-5/eu-18-Spolaor-No-Free-Charge-Theorem-2-How-To-Steal-Private-Information-From-A-Mobile-Device-Using-A-Powerbank.pdf

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
