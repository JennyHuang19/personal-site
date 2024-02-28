---
title: "Fitting a stochastic model of intensive care occupancy to noisy hospitalization time series during the COVID-19 pandemic"
authors: 
- Achal Aswathi, Volodymyr Minin, Jenny Huang, Daniel Chow, and Jason Xu

date: "2022-03-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Statistics in Medicine"
publication_short: "StatMed"

abstract: Intensive care occupancy is an important indicator of health care stress that has been used to guide policy decisions during the COVID-19 pandemic. Toward reliable decision-making as a pandemic progresses, estimating the rates at which patients are admitted to and discharged from hospitals and intensive care units (ICUs) is crucial. Since individual-level hospital data are rarely available to modelers in each geographic locality of interest, it is important to develop tools for inferring these rates from publicly available daily numbers of hospital and ICU beds occupied. We develop such an estimation approach based on an immigration-death process that models fluctuations of ICU occupancy. Our flexible framework allows for immigration and death rates to depend on covariates, such as hospital bed occupancy and daily SARS-CoV-2 test positivity rate, which may drive changes in hospital ICU operations. We demonstrate via simulation studies that the proposed method performs well on noisy time series data and apply our statistical framework to hospitalization data from the University of California, Irvine (UCI) Health and Orange County, California. By introducing a likelihood-based framework where immigration and death rates can vary with covariates, we find, through rigorous model selection, that hospitalization and positivity rates are crucial covariates for modeling ICU stay dynamics and validate our per-patient ICU stay estimates using anonymized patient-level UCI hospital data.


tags:
- Source Themes
featured: false

links:
# - name: "[https://arxiv.org/abs/2211.14691](https://doi.org/10.1002/sim.9907)"
#   url: "[https://arxiv.org/abs/2211.14691](https://doi.org/10.1002/sim.9907)"
url_pdf: "https://doi.org/10.1002/sim.9907"

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
