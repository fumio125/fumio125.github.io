---
title: 'Close-contact detection using a single camera for sports considering occlusion'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ryosuke Hasegawa
  - Akira Uchiyama
  - admin
  - Daigo Muramatsu
  - Issei Ogasawara
  - Hiromi Takahata
  - Ken Nakata
  - Teruo Higashino

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-02-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# c.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access, 10*:15457-15468"
publication_short: 

abstract: "The Coronavirus disease 2019 (COVID-19) is still prevalent in the world. Exercise is important to maintain our health while dealing with infectious diseases. Social distancing is more important during exercise because we may not be able to wear masks to avoid breathing problems, heatstroke, etc. To maintain social distancing during exercise, we develop a close-contact detection system using a single camera especially for sports in schools and gyms. We rely on a single camera because of the deployment cost. The system recognizes people from a video and estimates the interpersonal distance for close-contact detection. The challenge is the occlusion of people, which leads to false negatives in close-contact detection. To solve the problem, we leverage the observation that most false negatives in human detection are caused by occlusion owing to other people. This is because there are few obstacles in sports facilities. Based on the above observation, we assume that a person still exists near the last detected position even when s/he disappears in the proximity of other people. For evaluation, we recorded 834 videos that were 112 min long in total including various scenarios with 2724 close-contacts. The results show that the F1-score of close-contact detection and tracking are 83.6% and 67.3%, respectively. We also confirmed that the start and end time errors are within 1 s for more than 80% of the close-contacts."


# Summary. An optional shortened abstract.
# summary: We develop NeuraLeaf, the first neural parametric model for 3D leaves for plant modeling and reconstruction. 

tags:
  - Computer vision
  - Sports

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1109/ACCESS.2022.3146538'
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
