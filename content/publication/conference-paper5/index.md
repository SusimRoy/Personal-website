---
title: "TAIGen: Training-Free Adversarial Image Generation via Diffusion Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Susim Roy
  - Anubhooti Jain
  - Mayank Vatsa
  - Richa Singh

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-07-14'
# doi: '10.1109/AVSS61716.2024.10672595'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of IEEE/CVF International Conference on Computer Vision, Workshop on Biometrics, Identity and Behaviour Science(ICCVw'25)(Oral)*
summary: ICCVw'2025

abstract: Adversarial perturbations generated using GANs or diffusion models often suffer from issues such as poor quality, long generation runtime, and high computational costs. Additionally, diffusion models are known to have been trained on large sets of training data, which makes it hard to control the generated data. Thus, we explore the plethora of feature variations in the diffusion model backbone to select the right properties for unintended perturbations. To this end, we propose TAIGen, a novel black-box, training-free adversarial attack method. TAIGen utilizes unconditional diffusion models to generate perturbations efficiently in just a few sampling steps. Our approach introduces a selective channel-based mechanism that integrates attention maps and GradCAM that are both robust and imperceptible. These perturbations are also transferable to unseen classifiers, increasing their overall impact. The effectiveness of TAIGen is validated across the ImageNet, CIFAR-10, and CelebA-HQ datasets. In the challenging black-box setting on ImageNet using VGGNet as the source model, TAIGen achieves attack success rates of 70.6% on ResNet, 80.8% on MNASNet, and 97.81% on ShuffleNet.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'conference-paper5'
url_code: 'https://github.com/SusimRoy/TAIGen'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: 'https://docs.google.com/presentation/d/1pOFGNx_oPBpEVAse6PstWjDb3vOCitlG3lD0cOpUO14/edit?usp=sharing'
# url_project: ''
# url_slides: 'https://docs.google.com/presentation/d/1hXfuwqmE1WiB-SW3Gxw1UXfzuJ73GsUHZgV701n1JyY/edit?usp=sharing'
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
