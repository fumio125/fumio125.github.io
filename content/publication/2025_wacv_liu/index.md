---
title: 'TreeFormer: Single-view plant skeleton estimation via tree-constrained graph generation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xinpeng Liu
  - Hiroaki Santo
  - Yosuke Toda
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-02-28T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CVF Winter Conference on Applications of Computer Vision (WACV 2025)*
publication_short: In *WACV 2025*

abstract: "Accurate estimation of plant skeletal structure (e.g., branching structure) from images is essential for smart agriculture and plant science. Unlike human skeletons with fixed topology, plant skeleton estimation presents a unique challenge, i.e., estimating arbitrary tree graphs from images. While recent graph generation methods successfully infer thin structures from images, it is challenging to constrain the output graph strictly to a tree structure. To this problem, we present TreeFormer, a plant skeleton estimator via tree-constrained graph generation. Our approach combines learning-based graph generation with traditional graph algorithms to impose the constraints during the training loop. Specifically, our method projects an unconstrained graph onto a minimum spanning tree (MST) during the training loop and incorporates this prior knowledge into the gradient descent optimization by suppressing unwanted feature values. Experiments show that our method accurately estimates target plant skeletal structures for multiple domains: Synthetic tree patterns, real botanical roots, and grapevine branches."


# Summary. An optional shortened abstract.
summary: We develop TreeFormer, accurately estimating plant skeletal structure from a single image.

tags:
  - WACV 2025
  - WACV
  - Computer vision
  - Plant phenotyping

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2411.16132'
url_code: 'https://github.com/huntorochi/TreeFormer/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: '[**TreeFormer**](https://github.com/huntorochi/TreeFormer/)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - planttwin

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
