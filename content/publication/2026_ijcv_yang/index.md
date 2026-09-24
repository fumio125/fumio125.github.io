---
title: 'NeuraLeaf: Disentangled neural parametric modeling of leaf shape, deformation, and appearance'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yang Yang
  - Risa Shinoda
  - Hiroaki Santo
  - Yasuyuki Matsushita
  - admin
  
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-09-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# c.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: "*International Journal of Computer Vision*"
publication_short: 

abstract: We develop a neural parametric model of 3D leaves for plant modeling and reconstruction that are essential for agriculture and computer graphics. While neural parametric models are actively studied for humans and animals, plant leaves present unique challenges due to their thin surface geometry and flexible deformation. To address this problem, we introduce a neural parametric model for leaves, NeuraLeaf. Capitalizing on the fact that flattened leaf shapes can be approximated as a 2D plane, NeuraLeaf disentangles the leaves’ geometry into their 2D base shapes (i.e., flattened leaves) and 3D deformations. This representation allows learning from rich sources of 2D leaf image datasets for the base shapes, and also has the advantage of simultaneously learning textures aligned with the geometry. To obtain a disentangled and controllable appearance space, NeuraLeaf also introduces a learnable appearance space with self-supervised objectives, enabling both appearance fitting to observations and appearance-conditioned texture generation. To model the 3D deformation, we propose a novel skeleton-free skinning model and create a newly captured 3D leaf dataset called DeformLeaf. We demonstrate that NeuraLeaf successfully generates a diverse range of leaf shapes with high-fidelity appearance and deformation, resulting in accurate model fitting to RGB-D observations.


# Summary. An optional shortened abstract.
summary: We propose NeuraLeaf, a neural parametric model of 3D leaves for plant modeling and reconstruction.

tags:
  - IJCV
  - Computer vision
  - Plant phenomics

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/article/10.1007/s11263-026-03024-6'
url_code: 'https://github.com/Yrainy0615/NeuraLeaf-APP'
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
