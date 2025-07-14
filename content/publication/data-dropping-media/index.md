---
title: "Approximations to Worst-Case Data-dropping: Unmasking Failure Modes"
authors: 
- Jenny Y. Huang, David R. Burt, Tin D. Nguyen, Yunyi Shen, Tamara Broderick

date: "2025-01-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Transactions on Machine Learning Research"
publication_short: "TMLR"

abstract: A data analyst might worry about generalization if dropping a very small fraction of data points from a study could change its substantive conclusions. Checking this non-robustness directly poses a combinatorial optimization problem and is intractable even for simple models and moderate data sizes. Recently various authors have proposed a diverse set of approximations to detect this non-robustness. In the present work, we show that, even in a setting as simple as ordinary least squares (OLS) linear regression, many of these approximations can fail to detect (true) non-robustness in realistic data arrangements. We focus on OLS in the present work due its widespread use and since some approximations work only for OLS. Of the approximations that do not fail our tests, we find not only that a simple recursive greedy algorithm is the most conceptually straightforward but also that it can be orders of magnitude faster to run than the others.

tags:
- Source Themes
featured: false

links:
# - name: "[https://arxiv.org/abs/2211.14691](https://doi.org/10.1002/sim.9907)"
#   url: "[https://arxiv.org/abs/2211.14691](https://doi.org/10.1002/sim.9907)"
url_pdf: "https://openreview.net/pdf?id=m6EQ6YdPXV"

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
