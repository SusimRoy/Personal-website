---
title: Playlist Converter
summary: Self-Project
tags:
  - webd
date: '2021-08-20'

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
url_code: 'https://github.com/devlup-labs/apple2spotify-playlist'
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
- Created a website with VueJS and tailwindcss where an user can input an Apple playlist and a Spotify playlist will be created in their account which can be private/public as per their choice.
- Used an Apple token to get songs from the user's playlist and thereby sent GET requests to Spotify to fetch the songs and finally sending a POST request to make the playlist.
- The algorithm we used to get the songs from Spotify is to add the first song which appears on searching with the corresponding name in the Apple playlist.