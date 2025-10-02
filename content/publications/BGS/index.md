---
title: 'Better Gradient Steps for Deep On-Policy Reinforcement Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Thibault Lahire

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-08-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['Workshop Paper']

# Publication name and optional abbreviated publication name.
publication: In *Aligning Reinforcement Learning Experimentalists and Theorists Workshop at International Conference on Machine Learning*
publication_short: In *ARLET workshop at ICML*

abstract: In deep on-policy reinforcement learning, algorithms collect transitions by executing the current policy in the environment. These transitions are then used during a gradient ascent step, aiming at updating the neural network(s) parameter. This article studies how the collected transitions can be prioritized to speed up the gradient ascent process toward a favorable policy. To do so, we weigh the transitions in the update gradient ascent equation with their per-sample gradient norms, which is a measure of the margin of change which can occur in the neural network.

# Summary. An optional shortened abstract.
summary: This paper studies how the collected transitions can be prioritized to speed up the gradient ascent process toward a favorable policy. To do so, we weigh the transitions in the update gradient ascent equation with their per-sample gradient norms, which is a measure of the margin of change which can occur in the neural network.

tags:
  - Reinforcement Learning
  - Sample Efficiency for RL

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
# hugoblox:
#   ids:
#     doi: 10.5555/123456

# Custom links
links:
  - type: pdf
    url: "https://drive.google.com/file/d/1tnvVJ_gDVDgdMymbpaT7ClvtTT5tu4bL/view?usp=sharing"
  # - type: code
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: dataset
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: video
  #   url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---

<!-- > [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
