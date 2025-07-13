---
title: 'Normal integration via inverse plane fitting with minimum point-to-plane distance'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xu Cao
  - Boxin Shi
  - admin
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

abstract: "This paper presents a surface normal integration method that solves an inverse problem of local plane fitting. Surface reconstruction from normal maps is essential in photometric shape reconstruction. To this end, we formulate normal integration in the camera coordinates and jointly solve for 3D point positions and local plane displacements. Unlike existing methods that consider the vertical distances between 3D points, we minimize the sum of squared point-to-plane distances. Our method can deal with both orthographic or perspective normal maps with arbitrary boundaries. Compared to existing normal integration methods, our method avoids the checkerboard artifact and performs more robustly against natural boundaries, sharp features, and outliers. We further provide a geometric analysis of the source of artifacts that appear in previous methods based on our plane fitting formulation. Experimental results on analytically computed, synthetic, and real-world surfaces show that our method yields accurate and stable reconstruction for both orthographic and perspective normal maps."


# Summary. An optional shortened abstract.
# summary: We resolve the scale ambiguity in multi-view 3D reconstruction with dual-pixel imaging. 

tags:
  - CVPR 2021
  - CVPR
  - Computer vision
  - Normal integration

# Display this page in the Featured widget?
featured: false 

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openaccess.thecvf.com/content/CVPR2021/html/Cao_Normal_Integration_via_Inverse_Plane_Fitting_With_Minimum_Point-to-Plane_Distance_CVPR_2021_paper.html'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://github.com/xucao-42/NormalIntegration'
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
