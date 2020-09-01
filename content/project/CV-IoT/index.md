---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "CV with IoT for Security System (Proposed Design)"
summary: "Computer Vision with Internet of Things, implemented on smart-lock for security system"
authors: ["admin"]
tags: ["Internet of Things", "Computer Vision"]
categories: []
date: 2020-09-01T22:39:27+07:00

# Optional external URL for project (replaces project detail page).
external_link: ""

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

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
{{% alert note %}}
This research is only limited to testing the work of the system without configuration on the embedded system and real environtment, so not implemented yet.
{{% /alert %}}

#### **Introduction**
Computer Vision can be defined as part of the field of computer science that focuses on replicating the human vision's ability to recognize an object in a digital image. The object that wants to be recognized in this study is the face of a person who wants to enter a door that has been configured with a "smart lock" system device in a building. The person who wants to enter the door can interact with the device using voice commands, such as: opening the door, repeating facial recognition, and asking permission from the access holder. This permission concept applies Internet of Things (IoT) technology, where permission requests to access holders will be sent via Bot on the Telegram application. Access can be given from anywhere as long as the access holder's cell phone is connected to the internet.

#### **Scope of Problem**
1. Voice commands that can be performed such as: opening the door, repeating facial recognition, and asking permission from the access holder;
2. The communication protocol on the Internet of Things used is the IEEE 802.11 or Wi-Fi standard;
3. Face recognition using the Support Vector Machine method.

#### **Block Diagram**
{{< figure src="fig1.PNG" title="Fig 1. Block Diagram" >}}
{{< figure src="fig2.PNG" title="Fig 2. Finite State Machine" >}}

#### **Result**
{{< figure src="fig3.PNG" title="Fig 3. Output from console" >}}
{{< figure src="fig4.PNG" title="Fig 4. Telegram message" >}}

