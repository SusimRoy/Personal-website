---
title: A Sequential Memory Preserving Approach for Few-Shot Image Classification
summary: Course Project for Advanced Machine Learning(CSL7340)
tags:
  - Coursework
  - CV
date: '2023-11-25'

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
url_code: 'https://github.com/SusimRoy/Breakxit'
url_pdf: 'https://github.com/SusimRoy/Breakxit/blob/main/report.pdf'
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
- we model the meta-training set as the combination of all the individual task specific training sets instead of a multi-task setting.
- We understand the cross-domain connection stored in the feature extractor using our Memory Augmented Propagation network which stores the information from the previous layers of our backbone.
- We apply self-attention on each output feature map of the layers of our backbone in a hierarchical manner to find co-dependency.
- We test on the popular CIFAR-FS and miniImageNet datasets and find that our results are at par and sometimes even better than convolutional based SOTA approaches like MetaOptNet.