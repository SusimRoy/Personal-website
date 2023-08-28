---
title: Referring Moving Object Segmentation
summary: Research Internship
tags:
  - Research_Project
date: '2022-07-20'

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
- Conducted an extensive literature survey to understand the working of the SOTA models like Referformer, MTTR etc.
- Improved RefVos by including the temporal information from the frames by taking their difference and sending it as input along with the 2nd frame among every 3 consecutive frame.
- To capture the new variety of features, made a new convolutional decoder to interpret the spatial and temporal information into accurately segmenting the object.
- Researched into joining the language and visual features using modules introduced by different papers such as a Multi-Scale Cross-Modal Feature Mining technique among others.
- Extended the training and testing dataset to JHMDB and DAVIS-17 along with the standard A2D dataset. 