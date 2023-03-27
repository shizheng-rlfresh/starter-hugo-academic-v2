---
title: "Improved Training of Graph-Embedding Based Neural Network Energy Functions for Catalysis"
authors:
- admin
- Srinivas Rangarajan
- Martin Takáč
author_notes:
- 
- Lehigh University
- MBZUAI
date: "2020-11-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication: "*2020 Virtual AIChE Annual Meeting*"
publication_short: "*AIChEL*"

abstract:  Complex reaction networks comprising of thousands of intermediates and reactions are ubiquitous in heterogeneous catalysis; developing mechanistic models of such systems is computationally intractable primarily due to the cost of computing the energies of reactions and species using an ab initio method such as density functional theory (DFT). Developing machine learned energy potentials trained on DFT energies offer a tractable way of building mechanistic models for these systems. To this end, the contribution of this talk is two-fold. First, we develop a novel deep neural network model to learn and predict the potential energy surface (PES) for periodic systems. The novel architecture integrates graph embedding of individual atoms, atomic interactions and periodic boundary conditions with physics-aware feature engineering, residual learning, and attention mechanism. Second, we train the model with an efficiently distributed Hessian-free optimization method and deliver a prediction within chemical accuracy, which demonstrates the potential of second order methods in the joint field of deep learning and quantum chemistry. We will use examples from the field of heterogeneous catalysis, including (i) alkane conversion on molybdenum sulfide and (ii) adsorption of hydrocarbons in zeolites.

# Summary. An optional shortened abstract.
summary: ""

tags:
- Machine Learning
- Deep Learning
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://aiche.confex.com/aiche/2020/meetingapp.cgi/Paper/607537'
url_video: 'https://www.youtube.com/watch?v=nYoJZNUwxdU'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**AIChE**](https://www.aiche.org/conferences/aiche-annual-meeting/2020)'
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
