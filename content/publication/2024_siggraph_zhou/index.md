---
title: 'Path-space differentiable rendering of implicit surfaces'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Siwei Zhou
  - Youngha Chang
  - Nobuhiko Mukai
  - Hiroaki Santo
  - admin
  - Yasuyuki Matsushita
  - Shuang Zhao

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-09-29T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *SIGGRAPH 2024 Conference Papers*
publication_short: In *SIGGRAPH 2024*

abstract: "Physics-based differentiable rendering is a key ingredient for integrating forward rendering into probabilistic inference and machine learning pipelines. As a state-of-the-art formulation for differentiable rendering, differential path integrals have enabled the development of efficient Monte Carlo estimators for both interior and boundary integrals. Unfortunately, this formulation has been designed mostly for explicit geometries like polygonal meshes. In this paper, we generalize the theory of differential path integrals to support implicit geometries like level sets and signed-distance functions (SDFs). In addition, we introduce new Monte Carlo estimators for efficiently sampling discontinuity boundaries that are also implicitly specified. We demonstrate the effectiveness of our theory and algorithms using several differentiable-rendering and inverse-rendering examples."


# Summary. An optional shortened abstract.
summary: We develop differentiable rendering for implicit surfaces. 

tags:
  - SIGGRAPH 2024
  - SIGGRAPH
  - Computer graphics

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://shuangz.com/projects/psdr-sdf-sg24/psdr-sdf-sg24.pdf'
url_code: 'https://github.com/uguuuuuu/PSDR-SDF'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Path-space differentiable rendering of implicit surfaces'
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
