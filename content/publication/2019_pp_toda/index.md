---
title: 'How convolutional neural networks diagnose plant disease'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yosuke Toda
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2019-03-26T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# c.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: "*Plant Phenomics, 2019*:9237136 (**Top 1% article**)"
publication_short: 

abstract: "Deep learning with convolutional neural networks (CNNs) has achieved great success in the classification of various plant diseases. However, a limited number of studies have elucidated the process of inference, leaving it as an untouchable black box. Revealing the CNN to extract the learned feature as an interpretable form not only ensures its reliability but also enables the validation of the model authenticity and the training dataset by human intervention. In this study, a variety of neuron-wise and layer-wise visualization methods were applied using a CNN, trained with a publicly available plant disease image dataset. We showed that neural networks can capture the colors and textures of lesions specific to respective diseases upon diagnosis, which resembles human decision-making. While several visualization methods were used as they are, others had to be optimized to target a specific layer that fully captures the features to generate consequential outputs. Moreover, by interpreting the generated attention maps, we identified several layers that were not contributing to inference and removed such layers inside the network, decreasing the number of parameters by 75% without affecting the classification accuracy. The results provide an impetus for the CNN black box users in the field of plant science to better understand the diagnosis process and lead to further efficient use of deep learning for plant disease diagnosis."


# Summary. An optional shortened abstract.
# summary: We develop NeuraLeaf, the first neural parametric model for 3D leaves for plant modeling and reconstruction. 

tags:
  - Plant phenomics
  - Computer vision

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.34133/2019/9237136'
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
