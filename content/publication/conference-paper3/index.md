---
title: "Efficient Convolutions using Box-Filters for Low-Latency Image Processing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Susim M Roy
  - Bharat Yalavarthi
  - Nalini Ratha

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-11-08'
doi: 'https://doi.org/10.1109/WNYISPW63690.2024.10786496'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Western New York Image and Signal Processing Workshop(2024)(Oral)*
summary: IEEE WNYISPW'2024

abstract: The convolution operator in Convolutional Neural Networks (CNNs) has been a crucial aspect of success in various computer vision tasks. There has been a recent surge in the use of CNNs for generative modeling. However, such techniques usually have a long inference time which is mainly due to the costly convolution operation. Thus, we bring our attention to reducing the total number of mathematical operations during convolution using the Summed Area Table (SAT) and box filters. In this work, we find the redundant box filters that are being repeated across the filter dimension and prune them to save computation. Additionally, we also show that this does not take a toll on the accuracy and instead increases it after finetuning the remaining architecture. Thus, our proposed method computes convolution output with lower latency as compared to using all the box filters, increases classification accuracy, and can be applied with arbitrarily shaped kernels.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10786496'
# url_code: 'https://github.com/SusimRoy/CIAI'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: 'https://docs.google.com/presentation/d/1LMW1V5vwbR9ixUdmVMMolAxUJ7xAYPVVGJGF2Xmb0Nc/edit?usp=sharing'
# url_project: ''
url_slides: 'https://docs.google.com/presentation/d/1eyS7lXhDffbyDXrEmwhGO16L7hvCldZpjrSTE21nsac/edit?usp=sharing'
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
