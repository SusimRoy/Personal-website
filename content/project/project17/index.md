---
title: Visual Motion Analysis from Images and Videos
summary: Course Project for Dependable AI(CSL4050)
tags:
  - Course Project
date: '2023-08-01'

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
url_code: 'https://github.com/Soumik-Roy/Robustness-of-Bayesian-Neural-Networks-against-White-Box-Attacks'
url_pdf: 'https://github.com/Soumik-Roy/Robustness-of-Bayesian-Neural-Networks-against-White-Box-Attacks/blob/main/B20AI042_B20AI043_Report.pdf'
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
- An experimental work where we tested whether BNN posteriors are more robust to gradient based adversarial attacks when compared to the general learning based neural networks in SOTA architectures.
- Implemented BNN posterior in Alexnet,LeNet, Resnet34 and a custom made CNN to test the validity of the theoretical result. Each of these 4 models were attacked with FGSM and PGD variants.
- Implemented two bayesian estimation methods namely the conventional variational inference and one of it's modified version called local reparametrisation trick into the three above models.
- Results indicate that Resnet34 takes a much longer time to train and has relatively poorer classification accuracy as compared to the other three models. A hypothesis supporting this fact is that Resnet34 has a more complex structure which doesn't model the data distribution properly through the priors at each block.