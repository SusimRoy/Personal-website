---
title: "Discerning the Chaos: Detecting Adversarial Perturbations while Disentangling
Intentional from Unintentional Noises"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Anubhooti Jain
  - Susim M Roy
  - Kwanit Gupta
  - Mayank Vatsa
  - Richa Singh

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-09-17'
doi: '10.1109/IJCB62174.2024.10744526'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Joint Conference on Biometrics(IJCB), 2024(Oral)*
publication_short: In *IEEE IJCB*

abstract: Deep learning models, such as those used for face recognition and attribute prediction, are susceptible to manipulations like adversarial noise and unintentional noise, including Gaussian and impulse noise. This paper introduces CIAI, a class-independent detection network built on a modified vision transformer with detection layers. CIAI employs a novel loss function that combines Maximum Mean Discrepancy and Center Loss to detect both intentional (adversarial attacks) and unintentional noise, regardless of the image class. We illustrate the impact of noise on gender prediction accuracy and evaluate CIAI’s detection performance using the CelebA and LFW datasets. Our findings show that CIAI achieves detection accuracy that is comparable to or better than existing methods, even against previously unseen attacks. Attention maps and t-SNE plots reveal the features that assist in gender prediction and noise detection. Additionally, we present detection results on the AgeDB and CIFAR-10 datasets, further demonstrating the robustness of our approach.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2409.19619'
url_code: 'https://github.com/SusimRoy/CIAI'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_poster: 'https://docs.google.com/presentation/d/1LMW1V5vwbR9ixUdmVMMolAxUJ7xAYPVVGJGF2Xmb0Nc/edit?usp=sharing'
# url_project: ''
url_slides: 'https://docs.google.com/presentation/d/1tjDkIvcwm7S0eS7vDD9Aoq2pFbcayKJbj_EXOXG3_6Q/edit?usp=sharing'
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
