---
title: "FD-Net with Auxiliary Time Steps: Fast Prediction of PDEs using Hessian-Free Trust-Region Methods"
authors:
- Sila Gulgec
- admin
- Neil Deshmukh
- Shamim N Pakzad
- Martin Takáč
author_notes:
- Thornton Tomasetti
- 
- 
- Lehigh University
- MBZUAI
date: "2019-10-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*NeurIPS 2019 Workshop (Beyond First Order Methods in ML)*"
publication_short: "*NeurIPS Workshop Beyond First Order Methods in ML*"

abstract:  Discovering the underlying physical behavior of complex systems is a crucial, but less well-understood topic in many engineering disciplines. This study proposes a finite-difference inspired convolutional neural network framework to learn hidden partial differential equations from given data and iteratively estimate future dynamical behavior. The methodology designs the filter sizes such that they mimic the finite difference between the neighboring points. By learning the governing equation, the network predicts the future evolution of the solution by using only a few trainable parameters. In this paper, we provide numerical results to compare the efficiency of the second-order Trust-Region Conjugate Gradient (TRCG) method with the first-order ADAM optimizer.

# Summary. An optional shortened abstract.
summary: ""

tags:
- Machine Learning
- Deep Learning
- Optimization Methods
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/1910.12680.pdf
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
