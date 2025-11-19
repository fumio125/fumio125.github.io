---
title: 'CattleAct: Cattle interaction detection with joint learning of action-interaction latent space'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ren Nakagawa
  - Yang Yang
  - Risa Shinoda
  - Hiroaki Santo
  - Kenji Oyama
  - admin
  - Takenao Ohkawa

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-03-06T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CVF Winter Conference on Applications of Computer Vision (WACV 2026)*
publication_short: In *WACV 2026*

abstract: "This paper introduces a method and application for automatic detection of behavioral interaction between grazing cattle from a single image, which is essential for smart livestock management in the cattle industry, such as for detecting estrus. Although the interaction detection for humans has been actively studied, a non-trivial challenge lies in cattle interaction detection, i.e., the lack of a comprehensive behavioral dataset including interaction, since the interactions of grazing cattle are rare events. We, therefore, propose CattleAct, a data-efficient method for interaction detection by decomposing interactions into the combinations of actions by individual cattle. Specifically, we first learn an action latent space from a large-scale cattle action dataset, then embed rare interactions via the fine-tuning of the pre-trained latent space using contrastive learning, constructing a unified latent space of action and interactions. On top of the proposed method, we develop a practical working system integrating video and GPS inputs. Experiments in a commercial-scale pasture show the accurate interaction detection by our method compared to the baselines."


# Summary. An optional shortened abstract.
summary: We develop CattleAct, cattle interaction detection method via action recognition.

tags:
  - WACV 2026
  - WACV
  - Computer vision
  - Agriculture

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
  caption: '[**CattleAct**]()'
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
