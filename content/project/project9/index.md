---
title: Deep Video Summarization
summary: Course project for the Deep Learning course(CSL7050), IIT Jodhpur
tags:
  - Coursework
date: '2023-05-20'

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
url_code: 'https://github.com/SusimRoy/Deep-Video-Summarization'
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
- Given an input video data, we find the most informative slides and summarize the content in the video in the form of natural language.
- We first encode the images using the CLIP model and then pass it through a U-Net inspired transformer encoder-decoder architecture with skip connections in order to score each frame.
- Finally, the frame-level scores to shot-level scores and finally use dynamic programming (0/1 knapsack) to decide which shots to pick as keyshots.