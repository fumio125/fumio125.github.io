---
title: 'Multispectral photometric stereo for spatially-varying spectral reflectances'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Heng Guo
  - admin
  - Boxin Shi
  - Takuya Funatomi
  - Yasuhiro Mukaigawa
  - Yasuyuki Matsushita

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-07-06T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# c.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: "*International Journal of Computer Vision, 130*:2166-2183"
publication_short: 

abstract: "Multispectral photometric stereo (MPS) aims at recovering the surface normal of a scene measured under multiple light sources with different wavelengths. While it opens up a capability of a single-shot measurement of surface normal, the problem has been known ill-posed. To make the problem well-posed, existing MPS methods rely on restrictive assumptions, such as shape prior, surfaces having a monochromatic with uniform albedo. This paper alleviates these restrictive assumptions in existing methods. We show that the problem becomes well-posed for surfaces with uniform chromaticity but spatially-varying albedos based on our new formulation. Specifically, if at least three (or two) scene points share the same chromaticity, the proposed method uniquely recovers their surface normals with the illumination of no less than four (or five) spectral lights in a closed-form. In addition, we show that a more general setting of spatially-varying both chromaticities and albedos can become well-posed if the light spectra and camera spectral sensitivity are calibrated. For this general setting, we derive a unique and closed-form solution for MPS using the linear bases extracted from a spectral reflectance database. Experiments on both synthetic and real captured data with spatially-varying reflectance demonstrate the effectiveness of our method and show the potential applicability for multispectral heritage preservation."


# Summary. An optional shortened abstract.
# summary: We develop NeuraLeaf, the first neural parametric model for 3D leaves for plant modeling and reconstruction. 

tags:
  - IJCV
  - Computer vision
  - Photometric stereo

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1007/s11263-022-01634-4'
url_code: ''
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
projects:
  - []

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
