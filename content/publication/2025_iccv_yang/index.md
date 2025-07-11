---
title: 'NeuraLeaf: Neural parametric leaf models with shape and deformation disentanglement'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yang Yang
  - Dongni Mao
  - Hiroaki Santo
  - Yasuyuki Matsushita
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-10-19T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CVF International Conference on Computer Vision (ICCV 2025)*
publication_short: In *ICCV 2025*

abstract: We develop a neural parametric model for 3D leaves for plant modeling and reconstruction that are essential for agriculture and computer graphics. While neural parametric models are actively studied for humans and animals, plant leaves present unique challenges due to their diverse shapes and flexible deformation. To this problem, we introduce a neural parametric model for leaves, NeuraLeaf. Capitalizing on the fact that flattened leaf shapes can be approximated as a 2D plane, NeuraLeaf disentangles the leaves' geometry into their 2D base shapes and 3D deformations. This representation allows learning from rich sources of 2D leaf image datasets for the base shapes, and also has the advantage of simultaneously learning textures aligned with the geometry. To model the 3D deformation, we propose a novel skeleton-free skinning model and create a newly captured 3D leaf dataset called DeformLeaf. We show that NeuraLeaf successfully generates a wide range of leaf shapes with deformation, resulting in accurate model fitting to 3D observations like depth maps and point clouds.


# Summary. An optional shortened abstract.
summary: We develop NeuraLeaf, the first neural parametric model for 3D leaves for plant modeling and reconstruction. 

tags:
  - ICCV 2025
  - Computer vision
  - Plant phenomics

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://neuraleaf-yang.github.io/'
url_dataset: 'https://neuraleaf-yang.github.io/'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: '[**NeuraLeaf**](https://neuraleaf-yang.github.io/)'
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
