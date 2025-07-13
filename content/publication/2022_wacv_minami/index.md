---
title: 'Symmetric-light photometric stereo'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Kazuma Minami
  - Hiroaki Santo
  - admin
  - Yasuyuki Matsushita

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-01-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CVF Winter Conference on Applications of Computer Vision (WACV 2022)*
publication_short: In *WACV 2022*

abstract: "This paper presents symmetric-light photometric stereo for surface normal estimation, in which directional lights are distributed symmetrically with respect to the optic center. Unlike previous studies of ring-light settings that required the information of ring radius, we show that even without the knowledge of the exact light source locations or their distances from the optic center, the symmetric configuration provides us sufficient information for recovering unique surface normals without ambiguity. Specifically, under the symmetric lights, measurements of a pair of scene points having distinct surface normals but the same albedo yield a system of constrained quadratic equations about the surface normal, which has a unique solution. Experiments demonstrate that the proposed method alleviates the need for geometric light source calibration while maintaining the accuracy of calibrated photometric stereo."


# Summary. An optional shortened abstract.
# summary: We develop TreeFormer, accurately estimating plant skeletal structure from a single image.

tags:
  - WACV 2022
  - WACV
  - Computer vision
  - Photometric stereo

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openaccess.thecvf.com/content/WACV2022/html/Minami_Symmetric-Light_Photometric_Stereo_WACV_2022_paper.html'
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
