---
title: Real Time Face Mask Detection
summary: Self-Project, IIT Jodhpur
tags:
  - CV
date: '2021-04-20'

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
url_code: 'https://github.com/SusimRoy/Real-Time-Mask-Detection'
url_pdf: ''
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
- Used VGG-19 to train on a publicly available kaggle dataset on masked/non-masked faces and obtained an accuracy of 99.8%.
- Used the haarCascades to detect the face in a real-time video and then apply our model to check whether the user has worn a mask or not.