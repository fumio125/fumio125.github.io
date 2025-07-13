---
title: 'Learn to synthesize photorealistic dual-pixel images from RGBD frames'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Feiran Li
  - Heng Guo
  - Hiroaki Santo
  - admin
  - Yasuyuki Matsushita

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-07-28T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Computational Photography (ICCP 2023)*
publication_short: In *ICCP 2023*

abstract: "As a special sensor that implicitly provides ordinal depth information, dual-pixel (DP) appears to be beneficial for various tasks such as defocus deblurring and monocular depth estimation. Recent advances in data-driven dual-pixel (DP) research are bottlenecked by the difficulties in reaching large-scale DP datasets, and a photorealistic image synthesis approach appears to be a credible solution. To benchmark the accuracy of various existing DP image simulators and facilitate data-driven DP image synthesis, this work presents a real-world DP dataset consisting of approximately 5000 high-quality pairs of sharp images, DP defocus blur images, detailed imaging parameters, and accurate depth maps. Based on this large-scale dataset, we also propose a holistic data-driven framework to synthesize photorealistic DP images, where a neural network replaces conventional handcrafted imaging models. Experiments show that our neural DP simulator can generate more photorealistic DP images than existing state-of-the-art methods and effectively benefit data-driven DP-related tasks. Our code and dataset are released at https://github.com/SILI1994/Dual-Pixel-Simulator."


# Summary. An optional shortened abstract.
# summary: We resolve the scale ambiguity in multi-view 3D reconstruction with dual-pixel imaging. 

tags:
  - ICCP 2023
  - ICCP
  - Computer vision
  - Computational photography

# Display this page in the Featured widget?
featured: false 

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/10233839'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://github.com/feiran-l/Neural-Dual-Pixel-Simulator'
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
