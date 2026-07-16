---
title: "Don't mask out the background! Natural-light photometric stereo via illumination reconstruction"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Taiga Hashida
  - Hiroaki Santo
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-09-09T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Computer Vision (ECCV 2026)*
publication_short: In *ECCV 2026*

abstract: "This paper introduces an inverse-rendering framework for natural-light, uncalibrated photometric stereo (PS) that leverages background cues captured alongside the target object. Natural-light PS (NaPS) acquires shading variations by moving or rotating the camera and object under fixed, uncontrolled illumination, such as indoor lighting, while maintaining their relative geometry. However, uncalibrated NaPS, in which the lighting conditions are unknown, remains inherently ill-posed. To tackle this challenge, we propose explicitly reconstructing the lighting environment from the image background, which is typically masked out in prior work, thereby converting uncalibrated NaPS into a tractable inverse-rendering problem. Specifically, we move and rotate the camera-object pair while keeping their relative pose fixed, and reconstruct the surrounding illumination directly from the observed background using a 3D Gaussian Splatting (3DGS) representation. We then optimize the target object's shape and reflectance via inverse rendering under the reconstructed illumination. Experimental results demonstrate that our inverse-rendering-based approach yields more accurate estimates of both geometry and reflectance than existing learning-based PS methods, especially under realistic near-field indoor conditions."


# Summary. An optional shortened abstract.
summary: We introduces an inverse-rendering framework for natural-light, uncalibrated photometric stereo (PS).

tags:
  - ECCV 2026
  - ECCV
  - Computer vision
  - Photometric stereo

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  caption: '[**Hashida+, ECCV2026**]()'
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
