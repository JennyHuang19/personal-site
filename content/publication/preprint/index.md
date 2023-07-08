---
title: "Detecting Changes in the Transmission Rate of a Stochastic Epidemic Model"
authors: 
- admin
- Jenny Huang, Raphaël Morsomme, David Dunson, Jason Xu
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
# - name: ""
#   url: "https://arxiv.org/abs/2211.14691"
url_pdf: "https://arxiv.org/pdf/2211.14691.pdf"
url_code: 'https://github.com/JennyHuang19/damcmc_timevarying_beta'
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

---
title: "Fitting a Stochastic Model of Intensive Care Occupancy to Noisy COVID-19 Hospitalization Time Series"
authors: 
- admin
- Achal Aswathi, Vladimir Minin, Jenny Huang, Daniel Chow, and Jason Xu

date: "2022-03-012T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Intensive care occupancy is an important indicator of health care stress that has been used to guide policy decisions during the COVID-19 pandemic. Toward reliable decision-making as a pandemic progresses, estimating the rates at which patients are admitted to and discharged from hospitals and intensive care units (ICUs) is crucial. Since individual-level hospital data are rarely available to modelers in each geographic locality of interest, it is important to develop tools for inferring these rates from publicly available daily numbers of hospital and ICU beds occupied. We develop such an estimation approach based on an immigration-death process that models fluctuations of ICU occupancy. Our flexible framework allows for immigration and death rates to depend on covariates, such as hospital bed occupancy and daily SARS-CoV-2 test positivity rate, which may drive changes in hospital ICU operations. We demonstrate via simulation studies that the proposed method performs well on noisy time series data and apply our statistical framework to hospitalization data from the University of California, Irvine (UCI) Health and Orange County, California. By introducing a likelihood-based framework where immigration and death rates can vary with covariates, we find, through rigorous model selection, that hospitalization and positivity rates are crucial covariates for modeling ICU stay dynamics and validate our per-patient ICU stay estimates using anonymized patient-level UCI hospital data.


tags:
- Source Themes
featured: false

links:
# - name: ""
#   url: "arXiv:2203.00229"
url_pdf: "https://arxiv.org/pdf/2203.00229.pdf"
url_code: ''
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

---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
