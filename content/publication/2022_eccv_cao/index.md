---
title: 'Bilateral normal integration'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xu Cao
  - Hiroaki Santo
  - Boxin Shi
  - admin
  - Yasuyuki Matsushita

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-10-23T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Computer Vision (ECCV v)*
publication_short: In *ECCV 2022*

abstract: "This paper studies the discontinuity preservation problem in recovering a surface from its surface normal map. To model discontinuities, we introduce the assumption that the surface to be recovered is semi-smooth, i.e., the surface is one-sided differentiable (hence one-sided continuous) everywhere in the horizontal and vertical directions. Under the semi-smooth surface assumption, we propose a bilaterally weighted functional for discontinuity preserving normal integration. The key idea is to relatively weight the one-sided differentiability at each point’s two sides based on the definition of one-sided depth discontinuity. As a result, our method effectively preserves discontinuities and alleviates the under- or over-segmentation artifacts in the recovered surfaces compared to existing methods. Further, we unify the normal integration problem in the orthographic and perspective cases in a new way and show effective discontinuity preservation results in both cases (Source code is available at https://github.com/hoshino042/bilateral_normal_integration.)."


# Summary. An optional shortened abstract.
# summary: We resolve the scale ambiguity in multi-view 3D reconstruction with dual-pixel imaging. 

tags:
  - ECCV 2022
  - ECCV
  - Computer vision
  - Normal integration

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136610545.pdf'
url_code: 'https://github.com/xucao-42/bilateral_normal_integration'
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
