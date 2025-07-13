---
title: 'Synthesizing time-varying BRDFs via latent space'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Takuto Narumoto
  - Hiroaki Santo
  - admin

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

abstract: "This paper introduces a method for synthesizing time-varying bidirectional reflectance distribution functions (BRDFs) by applying learned temporal changes to static BRDFs. Achieving realistic and natural changes in material appearance over time is crucial in computer graphics and virtual reality. Existing methods employ a parametric BRDF model, and the temporal changes in BRDFs are modeled by polynomial functions that represent the transitions of the BRDF parameters. However, the limited representational capabilities of both the parametric BRDF model and the polynomial temporal model restrict the fidelity of the appearance reproduction. In this paper, to overcome this limitation, we introduce a neural embedding for BRDFs and propose a neural temporal model that represents the temporal changes of BRDFs in the latent space, which allows flexible representations of BRDFs and temporal changes. The experiments using synthetic and real-world datasets demonstrate that the flexibility of the proposed approach achieves a faithful synthesis of temporal changes in material appearance."


# Summary. An optional shortened abstract.
summary: We synthisize time-varying BRDFs by applying learned temporal changes to static BRDFs.

tags:
  - ECCV 2024
  - ECCV
  - Computer vision
  - Computer graphics

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eccv.ecva.net/virtual/2024/poster/1289'
url_code: 'https://github.com/naru-19/eccv2024-synthesizing-time-varying-BRDFs-via-latent-space'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Synthesizing time-varying BRDFs'
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
