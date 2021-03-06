---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Robotics and AR Learning Experience"
summary: "Learning experience using Humanoid Robot and Multimedia AR, for solar system learning materials"
authors: ["admin"]
tags: ["Augmented Reality", "Computer Vision"]
categories: []
date: 2020-08-18T14:39:13+07:00

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
#### **Introduction**
The rationalization of the change in the education unit curriculum in Indonesia to K-13 was carried out due to various challenges faced including future challenges, competencies needed in the future, community perceptions, development of knowledge and pedagogy, as well as various negative phenomena that emerged. Education in accordance with future needs will only be realized if there is a shift or change in mindset in the learning process, with several points including: from one direction to interactive and from a single tool to multimedia tools. Thus, the authors conducted research on design of multimedia learning with the help of robot assistants. Multimedia learning contains material about the solar system, designed on the basis of marker based augmented reality using the Vuforia SDK in the form of Universal Windows Platform applications that are built on personal computer devices. The robot assistant is designed on a humanoid robot, with embedded intelligence that has the ability to detect and recognize text, using EAST Text Detector and Tesseract OCR, on the multimedia screen in the form of a planet name and the ability to find the fastest path to the destination planet to press buttons on the multimedia screen to change the augmented display reality planet. The entire design was tested and implemented at CoppeliaSim and managed to get a 100% accuracy and success rate.

#### **Scope of Problem**
1. Multimedia AR designed based on marker based tracking, in desktop application form, build on Microsoft Surface Pro 4; 
2. Robot Assistant implemented on Humanoid Robot, planted embedded intelligence/artificial intelligence;
3. Testing is carried out on CoppeliaSim Simulator.

#### **Scope of Embedded Intelligence**
1. Able to detect (EAST Text Detector) and recognize (Tesseract OCR) text on multimedia screen (planet name);
2. Able to find the shortest path to the destination planet (Shortest Path Algorithm in CDLL Data Structure).

#### **Block Diagram**

{{< figure src="fig1.PNG" title="Fig 1. Block Diagram System" >}}

#### **Multimedia AR (Mercury)**

{{< figure src="fig2.jpg" title="Fig 2. Planet Mercury" >}}

#### **Program Output on Console**

{{< figure src="fig3.PNG" title="Fig 3. Output on Current Planet Mercury" >}}


