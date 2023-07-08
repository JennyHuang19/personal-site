---
title: "Detecting Changes in the Transmission Rate of a Stochastic Epidemic Model"
authors: Jenny Huang, Raphaël Morsomme, David Dunson, Jason Xu
- admin
date: "2022-11-22T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Throughout the course of an epidemic, the rate at which disease spreads varies with behavioral changes, the emergence of new disease variants, and the introduction of mitigation policies. Estimating such changes in transmission rates can help us better model and predict the dynamics of an epidemic, and provide insight into the efficacy of control and intervention strategies. We present a method for likelihood-based estimation of parameters in the stochastic SIR model under a time-inhomogeneous transmission rate comprised of piecewise constant components. In doing so, our method simultaneously learns change points in the transmission rate via a Markov chain Monte Carlo algorithm. The method targets the exact model posterior in a difficult missing data setting given only partially observed case counts over time. We validate performance on simulated data before applying our approach to data from an Ebola outbreak in Western Africa and COVID-19 outbreak on a university campus.


tags:
- Source Themes
featured: false

links:
- name: Custom Link
  url: [https://arxiv.org/abs/2211.14691](https://arxiv.org/abs/2211.14691)
url_pdf: [https://arxiv.org/pdf/2211.14691.pdf](https://arxiv.org/pdf/2211.14691.pdf)
url_code: '[https://github.com/JennyHuang19/damcmc_timevarying_beta](https://github.com/JennyHuang19/damcmc_timevarying_beta)'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
