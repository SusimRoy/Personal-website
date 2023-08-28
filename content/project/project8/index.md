---
title: Deep Q Learning
summary: Course project for Advanced Aritifical Intelligence(CSL7030)
tags:
  - course
date: '2023-04-25'

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
url_code: 'https://github.com/SusimRoy/Deep-Q-Learning'
url_pdf: 'https://github.com/SusimRoy/Deep-Q-Learning/blob/main/simple-DQN-custom-game-report.pdf'
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
- The objective was to train a RL agent to play the world's hardest game which is essentially to reach a goal point among arbitratrily moving obstacles. 
- Created a simple MLP which projects from a n-dimensional state space to a m-dimensional action state which the RL agent should take.
- Created a custom reward function which penalizes the agent for being idle or getting stuck by an obstacle and rewards it for reaching the goal.