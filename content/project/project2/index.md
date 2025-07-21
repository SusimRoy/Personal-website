---
title: MagFormer:- Parameter-Efficient Modular Approach for Person Re-Identification
authors: 
- Susim Roy
- Dr. Kaiyi Ji

summary: Deep Learning Course Project, University at Buffalo
author_notes:
- "University at Buffalo"
- "University at Buffalo"

tags:
  - Coursework
  - CV
date: '2025-05-01'

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
url_code: 'https://github.com/SusimRoy/MagFormer'
url_pdf: 'https://github.com/SusimRoy/MagFormer/blob/main/DL_project_report.pdf'
url_slides: 'https://docs.google.com/presentation/d/1c1Mets20T8icZa9hldEwbijQ01gRTdKA6-7R_uuExrE/edit?usp=sharing'
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

## Summary 
- MagFormer, a modular transformer model, improves person re-identification by integrating image-to-image interactions during training to reduce noisy or unstable representations.
- It introduces three components(1)MALAA: Approximates dense relations using magnitude-aware landmarks.
(2)RNS: Focuses attention on contextually relevant samples by sparsifying it.
(3)DiffAttn: Cancels residual noise to boost identity consistency.
- MagFormer is scalable, interpretable, and consistently outperforms baselines.