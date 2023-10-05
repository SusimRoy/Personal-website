---
title: Feedback Approach to Foster Motion Information in FPAR
summary: Course Project for Deep Learning(CSL7050), IIT Jodhpur
tags:
  - Coursework
  - CV
date: '2023-04-02'

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
url_code: ''
url_pdf: 'https://github.com/SusimRoy/Feedback-is-All-we-need/blob/main/B20AI061_B20AI043_DLOPS_PROJECT_REPORT.pdf'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

## Summary 
- Improved the existing SparNet architecture by encorporating a feedback mechanism which basically embeds the finer information from the later layers of Resnet in it's earlier layers.
- The Motion Prediction Block used the knowledge from the Action Recognition Block to incorporate it back into that in it's first layer while taking care of the dimensions. 
- Deployed the model on a webpage using flask framework where an user can input a video or an image and gets returned a heat map indicating the location of the action.