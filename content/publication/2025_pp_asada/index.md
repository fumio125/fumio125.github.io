---
title: 'LeafGen: Structure-aware leaf image generation for annotation-free leaf instance segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Naoki Asada
  - Xinpeng Liu
  - Kanyu Xu
  - Ryohei Miyakawa
  - Yang Yang
  - Hiroaki Santo
  - Yosuke Toda 
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-09-10T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# c.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: "*Plant Phenomics*"
publication_short: 

abstract: Instance segmentation of plant leaves plays a crucial role in plant phenotyping, leveraging the rapid advancements in neural network research. A significant challenge in leaf instance segmentation lies in the preparation of training datasets, which typically require manual annotations comprising numerous pairs of ground-truth masks and corresponding plant photographs. Recently, segmentation models pre-trained on large-scale datasets, e.g., Segment Anything, have enabled training-free (i.e., zero-shot) instance segmentation accessible to the public. However, applying these models to leaf segmentation often yields unsatisfactory results, as the training datasets for these foundation models may lack sufficient plant imagery to accurately segment leaves exhibiting heavy occlusions and similar textures. To address this issue, we propose a fully automatic method for generating training datasets for leaf instance segmentation, combining an off-the-shelf zero-shot model with structure-aware image generation. Specifically, given a set of plant images and an L-system growth rule representing the structural pattern of the target plant, the proposed method automatically produces an arbitrary number of instance mask and photorealistic plant image pairs, eliminating the need for manual annotation. To maximize usability, we also provide a GUI front-end that integrates the entire pipeline of our method. Experiments on *Arabidopsis*, Komatsuna, and *Rhaphiloepsis* plants demonstrate that our method achieves more accurate segmentation compared to state-of-the-art zero-shot models, attaining AP@50 scores of 74.8, 76.0, and 88.2 for leaf instance segmentation of *Arabidopsis*, Komatsuna, and *Rhaphiloepsis*, respectively---without any manual annotation.


# Summary. An optional shortened abstract.
# summary: We develop NeuraLeaf, the first neural parametric model for 3D leaves for plant modeling and reconstruction. 

tags:
  - Computer vision
  - Plant phenomics

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/RightzZ/structure_gen'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
