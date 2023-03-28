---
title: "Finite difference neural networks: Fast prediction of partial differential equations"
authors:
- admin
- Sila Gulgec
- Albert S Berahas
- Shamim N Pakzad
- Martin Takáč
author_notes:
- 
- Thornton Tomasetti
- University of Michigan
- Lehigh University
- MBZUAI
date: "2021-02-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE International Conference on Machine Learning and Applications*"
publication_short: "*ICMLA*"

abstract:  Discovering the underlying behavior of complex systems is an important topic in many science and engineering disciplines. In this paper, we propose a novel neural network framework, finite difference neural networks (FD-Net), to learn partial differential equations from data. Specifically, our proposed finite difference inspired network is designed to learn the underlying governing partial differential equations from trajectory data, and to iteratively estimate the future dynamical behavior using only a few trainable parameters. We illustrate the performance (predictive power) of our framework on the heat equation, with and without noise and/or forcing, and compare our results to the Forward Euler method. Moreover, we show the advantages of using a Hessian-Free Trust Region method to train the network.

# Summary. An optional shortened abstract.
summary: ""

tags:
  - Machine Learning
  - Adaptive Algorithms
featured: false

categories:
  - Research
  - Academic Space

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/9356264
url_code: 'https://github.com/shizheng-rlfresh/FD-Net'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=btsBizwcIPw&t=6s'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: **FD-Net**'
  focal_point: ""
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
slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
