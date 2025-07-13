---
title: 'Realtime novel view synthesis with eigen-texture regression'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yuta Nakashima
  - admin
  - Norihiko Kawai
  - Ryosuke Kimura
  - Hiroshi Kawasaki
  - Katsushi Ikeuchi
  - Ambrosio Blanco

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2020-11-30T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *British Machine Vision Conference (BMVC 2017)*
publication_short: In *BMVC 2017*

abstract: "Realtime novel view synthesis, which generates a novel view of a real object or scene in realtime, enjoys a wide range of applications including augmented reality, telepresence, and immersive telecommunication. Image-based rendering (IBR) with rough geometry can be done using only an off-the-shelf camera and thus can be used by many users. However, IBR from images in the wild (e.g., lighting condition changes or the scene contains objects with specular surfaces) has been a tough problem due to color discontinuity; IBR with rough geometry picks up appropriate images for a given viewpoint, but the image used for a rendering unit (a face or pixel) switches when the viewpoint moves, which may cause noticeable changes in color. We use the eigen-texture technique, which represents images for a certain face using a point in the eigenspace. We propose to regress a new point in this space, which moves smoothly, given a viewpoint so that we can generate an image whose color smoothly changes according to the point. Our regressor is based on a neural network with a single hidden layer and hyperbolic tangent nonlinearity. We demonstrate the advantages of our IBR approach using our own datasets as well as publicly available datasets for comparison."


# Summary. An optional shortened abstract.
# summary: We resolve the scale ambiguity in multi-view 3D reconstruction with dual-pixel imaging. 

tags:
  - BMVC 2017
  - BMVC
  - Computer vision
  - image-based rendering

# Display this page in the Featured widget?
featured: false 

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://cvl.ist.osaka-u.ac.jp/user/okura/paper/BMVC2017.pdf'
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
