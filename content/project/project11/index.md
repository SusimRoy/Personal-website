---
title: Multimodal Art Database
summary: Course Project for Data Engineering(CSL4030)
tags:
  - Coursework
date: '2022-10-30'

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
url_code: 'https://github.com/SusimRoy/Multimodal-Art-Database'
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

<h2>Summary</h2> 
- A user had to input an artistic image and our software would detect the top k artists who could have possibly made the painting and store them in a local MariaDB database. <br/>
- To find the similarity between input painting and the database, we used the CLIP model to first finetune on our art database and then using the cosine similarity between the stored embeddings and our input feature embedding. <br/>
- The most likely images got stored in a normalized SQL tables with foreign keys linking between the image id table and the artist id table.
