---
title: Detecting Adversarial Perturbations While Determining Intentional and Unintentional Noises
summary: Undergraduate Research Project, IIT Jodhpur
tags:
  - Research Projects
  - CV
date: '2022-08-30'
authors: 
- "Dr. Richa Singh"
- "Dr. Mayank Vatsa"
- Susim Mukul Roy
- Anubhooti Jain
- Kwanit Gupta
author_notes:
- "Indian Institute of Technology, Jodhpur"
- "Indian Institute of Technology, Jodhpur"
- "Indian Institute of Technology, Jodhpur"
- "Indian Institute of Technology, Jodhpur"
- "Indian Institute of Technology, Jodhpur"
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
- We proposed a class-independent detection method, CIAI, using Maximum Mean Discrepancy which classifies the intended(adversarial attacks) and unintended(for e.g. Gaussian) noise separately.
- The algorithm is multistage indicating that in the first stage, we use an MMD-based loss to train a Vision
Transformer initialized with trained classifier weights and in the second stage we use the trained detector for classification by freezing all the layers and adding three trainable layers for training.
- We show the detection accuracy which is comparable and at times exceeds the previous state-of-the-art detection methods, including performance on unseen attacks.