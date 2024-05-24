---
title: 'RefMOS: A Robust Referred Moving Object Segmentation framework based on text query'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Prafulla Saxena
  - Susim M Roy
  - Santosh K Vipparthi
  - Dinesh K Tyagi
  - Subrahmanyam Murala
  - R. Balasubramanian

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-07-15'
doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Advanced Video and Signal-Based Surveillance(AVSS)*
publication_short: In *IEEE AVSS*

abstract: Referred Moving object segmentation is a very challenging task in automated video surveillance applications as it requires additional information to learn about object representation referred by natural language expression. In segmenting specific moving objects targeted by a text, suppressing other moving as well as stationary objects is a crucial task. A better context needs to be learned where linguistic, spatial, and temporal features need to be taken into account. In this work, we have proposed a robust referred moving object segmentation (RefMOS) framework to capture moving objects referred by text query. Most of the earlier state-of-the-art methods exploit a different type of supervision by treating video frames as images but lack temporal information during processing. In this work, we have proposed an inter-frame movement detector (IFCD) module, which extracts the movement information between the consecutive frames and helps integrate temporal information with spatial visual features. Language embedding is utilized to capture the information of referred moving objects in the text by extracting linguistic features from a pre-trained language model, i.e., BERT. Furthermore, the cross-entropy loss and SGD optimizer are used to train the network. Our RefMOS framework competes with the state-of-the-art approaches and achieves 48.6 mean IOU on the ref-DAVIS 17 dataset.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- # {{% callout note %}}
# Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the _Slides_ button to check out the example.
# {{% /callout %}}

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
