---
title: 'Multispectral photometric stereo for spatially-varying spectral reflectances: A well posed problem?'

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

date: '2021-06-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2021)*
publication_short: In *CVPR 2021*

abstract: "Multispectral photometric stereo (MPS) aims at recovering the surface normal of a scene from a single-shot multi-spectral image, which is known as an ill-posed problem. To make the problem well-posed, existing MPS methods rely on restrictive assumptions, such as shape prior, surfaces having a monochromatic with uniform albedo. This paper alleviates the restrictive assumptions in existing methods. We show that the problem becomes well-posed for a surface with a uniform chromaticity but spatially-varying albedos based on our new formulation. Specifically, if at least three (or two) scene points share the same chromaticity, the proposed method uniquely recovers their surface normals and spectral reflectance with the illumination of more than or equal to four (or five) spectral lights. Besides, our method can be made robust by having many (i.e., 4 or more) spectral bands using robust estimation techniques for conventional photometric stereo. Experiments on both synthetic and real-world scenes demonstrate the effectiveness of our method. Our data and result can be found at https://github.com/GH-HOME/MultispectralPS.git."


# Summary. An optional shortened abstract.
# summary: We resolve the scale ambiguity in multi-view 3D reconstruction with dual-pixel imaging. 

tags:
  - CVPR 2021
  - CVPR
  - Computer vision
  - Photometric stereo

# Display this page in the Featured widget?
featured: false 

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openaccess.thecvf.com/content/CVPR2021/html/Guo_Multispectral_Photometric_Stereo_for_Spatially-Varying_Spectral_Reflectances_A_Well_Posed_CVPR_2021_paper.html'
url_code: 'https://github.com/GH-HOME/MultispectralPS'
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
