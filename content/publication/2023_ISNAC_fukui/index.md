---
title: 'Predicting molecular interactions by graph convolutional neural networks with global features'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Kaito Fukui
  - Qingwen Chen
  - Hiroaki Santo
  - admin
  - Takeshi Yamada
  - Yasuyuki Matsushita
  - Kazuhiko Nakatani

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-11-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Symposium on Nucleic Acids Chemistry (ISNAC 2023)*
publication_short: In *ISNAC 2023*

abstract: "Multi-view photometric stereo (MVPS) recovers a high-fidelity 3D shape of a scene by benefiting from both multi-view stereo and photometric stereo. While photometric stereo boosts detailed shape reconstruction it necessitates recording images under various light conditions for each viewpoint. In particular calibrating the light directions for each view significantly increases the cost of acquiring images. To make MVPS more accessible we introduce a practical and easy-to-implement setup multi-view constrained photometric stereo (MVCPS) where the light directions are unknown but constrained to move together with the camera. Unlike conventional multi-view uncalibrated photometric stereo our constrained setting reduces the ambiguities of surface normal estimates from per-view linear ambiguities to a single and global linear one thereby simplifying the disambiguation process. The proposed method integrates the ambiguous surface normal into neural surface reconstruction (NeuS) to simultaneously resolve the global ambiguity and estimate the detailed 3D shape. Experiments demonstrate that our method estimates accurate shapes under sparse viewpoints using only a few multi-view constrained light sources."


# Summary. An optional shortened abstract.
# summary: We resolve the scale ambiguity in multi-view 3D reconstruction with dual-pixel imaging. 

tags:
  - ISNAC 2023
  - Biomedical

# Display this page in the Featured widget?
featured: false 

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
