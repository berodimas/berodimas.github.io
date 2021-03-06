---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "IoT-AR for Control and Monitoring System"
summary: "Internet of Things with Augmented Reality, implemented on greenhouse for control and monitoring"
authors: ["admin"]
tags: ["Internet of Things", "Augmented Reality"]
categories: []
date: 2020-08-17T21:36:04+07:00

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
In the process of caring for plants need to pay attention to several factors that influence the process of caring for these plants, for example factors of temperature, soil moisture, the need for radiation or intensity of light used, and other factors. To simplify these activities, an effective applicative innovation is needed that can be packaged in an informative, educative, and interactive manner. Therefore, this research was conducted which aims to create a prototype system to supervise and control the greenhouse in real-time by utilizing augmented reality as an interface, with control parameters such as lightning control and airflow control, and monitoring parameters in the form of: air and soil humidity, light intensity, and temperature. "Greenhouse Control and Monitoring System based on the Internet of Things with Augmented Reality Interface" is one of the interdisciplinary innovations between electronics, informatics, and agriculture.

#### **Scope of Problem**
1. Monitoring parameter: humidity, temperature, light intensity, moisture;
2. Control parameter: PWM Fan and RGB LED;
3. Communication protocol on Internet of Things using IEEE 802.11 (Wi-Fi).

#### **Hardware Component**

| Component           	| Description                   	 |
| ---------------------	| ------------------------------ 		|
| `NodeMCU V3 ESP8266`  | Microcontroller with IoT platform module.    |
| `DHT11 Sensor Module` | Temperature and humidity sensor.             |
| `GY-302 Sensor Module`| Light intensity sensor.            |
| `FC-28 Sensor Module` | Moisture sensor.             |
| `5V Relay Module` 	| Electric switch.             |
| `PWM Fan`		| Used to circulate air.            |
| `RGB LED` 		| Used to emit light.             |

#### **Software Component**

| Component           		| Description                    |
| ---------------------		| ------------------------------ |
| `Unity 3D`  			| Used as an engine to create Augmented Reality            |
| `Vuforia SDK` 		| Supporting SDK on Unity 3D for creating Augmented Reality            |
| `Firebase Realtime Database`	| As a cloud database on the system            |

#### **Block Diagram**

{{< figure src="fig1.PNG" title="Fig 1. Block Diagram" >}}

#### **AR App Display**

{{< figure src="fig2.jpg" title="Fig 2. Information Panel" >}}
{{< figure src="fig3.jpg" title="Fig 3. Control Panel" >}}


