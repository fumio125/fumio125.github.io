---
title: 'Masks-to-Skeleton: Multi-view mask-based tree skeleton extraction with 3D Gaussian splatting'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xinpeng Liu
  - Kanyu Xu
  - Risa Shinoda
  - Hiroaki Santo
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-07-11T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# c.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: "*Sensors, 25*(14):4354"
publication_short: 

abstract: Accurately reconstructing tree skeletons from multi-view images is challenging. While most existing works use skeletonization from 3D point clouds, thin branches with low-texture contrast often involve multi-view stereo (MVS) to produce noisy and fragmented point clouds, which break branch connectivity. Leveraging the recent development in accurate mask extraction from images, we introduce a mask-guided graph optimization framework that estimates a 3D skeleton directly from multi-view segmentation masks, bypassing the reliance on point cloud quality. In our method, a skeleton is modeled as a graph whose nodes store positions and radii while its adjacency matrix encodes branch connectivity. We use 3D Gaussian splatting (3DGS) to render silhouettes of the graph and directly optimize the nodes and the adjacency matrix to fit given multi-view silhouettes in a differentiable manner. Furthermore, we use a minimum spanning tree (MST) algorithm during the optimization loop to regularize the graph to a tree structure. Experiments on synthetic and real-world plants show consistent improvements in completeness and structural accuracy over existing point-cloud-based and heuristic baseline methods.


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

url_pdf: 'https://doi.org/10.3390/s25144354'
url_code: 'https://github.com/huntorochi/Masks-to-Skeleton'
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
