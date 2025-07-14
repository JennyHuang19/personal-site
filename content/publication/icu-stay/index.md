---
title: "Dropping Just a Handful of Preferences Can Change Top Large Language Model Rankings"
authors: 
- Jenny Y. Huang*, Yunyi Shen*, Dennis Wei, Tamara Broderick

date: "2025-07-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ICML 2025 Workshop on Models of Human Feedback for AI Alignment"
publication_short: "ICML 2025 Workshop on Models of Human Feedback for AI Alignment"

abstract: 'We propose a method for evaluating the robustness of a widely used LLM ranking system---the Bradley--Terry ranking system---to dropping a worst-case very small fraction of evaluation data. Our approach is computationally fast and easy to adopt. When we apply our method to matchups from two popular human-preference platforms, Chatbot Arena and MT-Bench, we find that the Bradley--Terry rankings of top-performing models are remarkably sensitive to the removal of a small fraction of evaluations. Our framework also identifies the specific evaluations most responsible for such ranking flips, allowing for inspections of these influential preferences. We observe that the rankings derived from MT-Bench preferences are notably more robust than those from Chatbot Arena, likely due to MT-bench’s use of expert annotators and carefully constructed prompts. Finally, we find that rankings based on crowdsourced human-evaluated systems are just as sensitive as those based on LLM-as-a-judge evaluations, where in both, dropping as little as 0.02% of the total evaluations in the dataset can change the top-ranked model.'

# Summary. An optional shortened abstract.
summary: We present a method for auditing the robustness of LLM ranking systems to worst-case data-dropping; we find that dropping just 0.02% of human (and AI) preferences can change the top-ranked models on Chatbot Arena.

tags:
- Source Themes
featured: false

# links:
# - name: Custom Link
#   url: https://openreview.net/forum?id=ZNUcipRpUck
url_pdf: "https://openreview.net/pdf?id=b9r1snfxIH"
url_code: 'https://github.com/JennyHuang19/IsRankingRobust'


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
