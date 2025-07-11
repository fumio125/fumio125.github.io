---
title: 'Accuracy evaluation and prediction of single-image camera calibration'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Susumu Kikkawa
  - admin
  - Daigo Muramatsu
  - Yasushi Yagi
  - Hideo Saito

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-02-13T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# c.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access, 11*:19312-19323"
publication_short: 

abstract: "This paper proposes an application to statistically predict the accuracy of single-image geometric camera calibration that uses given 2D-3D correspondences. Deriving both camera intrinsics and extrinsics from correspondences between a single image and a 3D shape, is important for the scene analysis when the optical system of the camera is lost, such as in the analyses of traffic accidents. It is unclear whether the single-image calibration will be successful in practice, particularly when the number of 2D-3D correspondences is small, even if we could assign accurate correspondences by manual labor. To this end, we perform a systematic evaluation of the camera parameter accuracy using synthetic environments. Based on the statistics observed during the experiments, our application predicts the calibration accuracy from simple variables (e.g., the area that correspondences could be given). Since the prediction process does not rely on 3D shapes, it provides an estimate of the success of the calibration before time-consuming processes, i.e., 3D scanning and 2D-3D correspondence mapping."


# Summary. An optional shortened abstract.
# summary: We develop NeuraLeaf, the first neural parametric model for 3D leaves for plant modeling and reconstruction. 

tags:
  - Computer vision
  - Forensics

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1109/ACCESS.2023.3244212'
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
