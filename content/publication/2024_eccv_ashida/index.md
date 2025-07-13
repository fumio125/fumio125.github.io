---
title: 'Resolving scale ambiguity in multi-view 3D reconstruction using dual-pixel sensors'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Kohei Ashida
  - Hiroaki Santo
  - admin
  - Yasuyuki Matsushita

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
publication: In *European Conference on Computer Vision (ECCV 2024)*
publication_short: In *ECCV 2024*

abstract: "Multi-view 3D reconstruction, namely structure-from-motion and multi-view stereo, is an essential component in 3D computer vision. In general, multi-view 3D reconstruction suffers from unknown scale ambiguity unless a reference object of known size is recorded together with the scene, or the camera poses are pre-calibrated. In this paper, we show that multi-view images recorded by a dual-pixel (DP) sensor allow us to automatically resolve the scale ambiguity without requiring a reference object or pre-calibration. Specifically, the observed defocus blurs in DP images provide sufficient information for determining the scale when paired together with the depth maps (up to scale) recovered from the multi-view 3D reconstruction. Based on this observation, we develop a simple yet effective linear solution method to determine the absolute scale in multi-view 3D reconstruction. Experiments demonstrate the effectiveness of the proposed method with diverse scenes recorded with different cameras/lenses."


# Summary. An optional shortened abstract.
summary: We resolve the scale ambiguity in multi-view 3D reconstruction with dual-pixel imaging. 

tags:
  - ECCV 2024
  - ECCV
  - Computer vision
  - Computational photography

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eccv.ecva.net/virtual/2024/poster/1345'
url_code: 'https://github.com/kohei-ashida/dp-sfm'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Resolving scale ambiguity in multi-view 3D reconstruction using dual-pixel sensors'
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
