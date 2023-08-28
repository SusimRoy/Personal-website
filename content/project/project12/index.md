---
title: UAV Guided UGV Movement
summary: DRDO, InterIIT'22.
tags:
  - Robotics
date: '2022-02-20'

# Optional external URL for project (replaces project detail page).
external_link: ''

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: 'https://github.com/SusimRoy/DRDO-UAV-UGV'
url_pdf: 'https://github.com/SusimRoy/DRDO-UAV-UGV/blob/main/MP_DR_T13_REPORT.pdf'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

<h2>Summary</h2> 
- An autonomous drone had to navigate in hilly environment and store it's path while moving towards the goal point following which a UGV would follow the path made by the UAV and reach the endpoint. <br/>
- Used OpenCV and segmentation techniques along with ROS to segment out road from surroundings using depth images.<br/>
- Analyzed the drone movement using Gazebo and RVIZ in order to accurately find an optimal path for the UGV. <br/>
- Sent messages to the UGV using ROSBags for it's movement post UAV arrival at goal. 