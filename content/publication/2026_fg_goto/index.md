---
title: 'Unsupervised 3D human pose estimation via conditional multi-view ancestral sampling'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ryohei Goto
  - Takuya Fujihashi
  - Shunsuke Saruwatari
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-05-25T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Automatic Face and Gesture Recognition (FG 2026)*
publication_short: In *FG 2026*

abstract: "We propose a method of estimating a 3D human pose from a single view without 3D supervision. The key to our method is to leverage the 2D diffusion priors of motion diffusion models (MDMs) pre-trained on large 2D human pose datasets. Specifically, we extend multi-view ancestral sampling of diffusion models to the task of 2D-3D lifting of human pose. To this end, we newly propose a conditional multi-view ancestral sampling (cMAS) that optimizes the 3D pose such that its multi-view projections follow the manifold in 2D MDM noise space, while conditioning the 3D pose to match the given 2D poses and anatomical constraints of humans. Experiments on the Yoga dataset demonstrate that our method achieves better cross-domain performance compared to state-of-the-art supervised and unsupervised 3D pose estimation methods, including extreme human poses where 3D supervision is unavailable."


# Summary. An optional shortened abstract.
summary: We propose conditional multi-view ancestral sampling (cMAS) for single view 3D human pose estimation without 3D supervision.
tags:
  - FG 2026
  - FG
  - Computer vision
  - Computer graphics

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://arxiv.org/abs/2605.15583'
url_code: 'https://github.com/asaa0001/c-MAS'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: '[**ZeroPlantSeg**](https://github.com/JunhaoXing/ZeroPlantSeg/)'
#   focal_point: ''
#   preview_only: false

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
