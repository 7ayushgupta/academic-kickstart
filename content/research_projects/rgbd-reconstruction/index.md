---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Realtime Onboard Dense RGB-D Mapping on UAVs"
summary: "Implemented and evaluated the realtime RGB-D mapping of unstructured environments, using open-source packages"
authors: [Ayush Gupta]
tags: [research]
categories: [UAV, Computer Vision]
date: 2019-05-02T18:51:50+05:30

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
url_pdf: "files/realtime-dense-mapping-draft.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Dense RGB-D map of environments have applications in aerial drone navigation, robotic manipulation, reconnaissance operations and semantic mapping. This mapping process is quite computationally expensive, with the main bottleneck being the generation of point clouds from the visual inputs. We have made use of both Monocular Cameras and RGB-D cameras for evaluating the feasibility and accuracy of the systems, while noting the processing speed of the entire system, accounting for the less computational power present on an aerial drone due to its scarce size and energy resources.