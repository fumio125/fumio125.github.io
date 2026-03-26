---
title: 'High-fidelity multi-view normal integration with scale-encoded neural surface representation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tongyu Yang
  - Heng Guo
  - Yasuyuki Matsushita
  - admin
  - Yu Luo
  - Xin Fan

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# c.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: "*Computer Graphics Forum*"
publication_short: 

abstract: Previous multi-view normal integration methods typically sample a single ray per pixel, without considering the spatial area covered by each pixel, which varies with camera intrinsics and the camera-to-object distance. Consequently, when the target object is captured at different distances, the normals at corresponding pixels may differ across views. This multi-view surface normal inconsistency results in the blurring of high-frequency details in the reconstructed surface. To address this issue, we propose a scale-encoded neural surface representation that incorporates the pixel coverage area into the neural representation. By associating each 3D point with a spatial scale and calculating its normal from a hybrid grid-based encoding, our method effectively represents multi-scale surface normals captured at varying distances. Furthermore, to enable scale-aware surface reconstruction, we introduce a mesh extraction module that assigns an optimal local scale to each vertex based on the training observations. Experimental results demonstrate that our approach consistently yields high-fidelity surface reconstruction from normals observed at varying distances, outperforming existing multi-view normal integration methods.

# Summary. An optional shortened abstract.
summary: We propose a scale-encoded neural surface representation that incorporates the pixel coverage area into the neural representation.

tags:
  - Computer Graphics Forum
  - Computer vision
  - Computer graphics
  - Normal integration

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2603.20337'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: ''
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
