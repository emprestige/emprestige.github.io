---
title: "Estimating social contact rates for the COVID-19 pandemic using Google mobility and pre-pandemic contact surveys"
authors:
- Em Prestige
- Peitro Coletti
- Jantien Backer
- Nicholas G Davies
- W. John Edmunds
- Christopher I. Jarvis

date: "2024-09-30T00:00:00Z"
#doi: "pre-print"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: In *The Lancet Public Health*
# publication_short: In *Lancet Public Health*

abstract: |
  During the COVID-19 pandemic, aggregated mobility data was frequently used to estimate changing social contact rates. By taking pre-pandemic contact matrices, and transforming these using pandemic-era mobility data, infectious disease modellers attempted to predict the effect of large-scale behavioural changes on contact rates. This study explores the most accurate method for this transformation, using pandemic-era contact surveys as ground truth. We compared four methods for scaling synthetic contact matrices: two using fitted regression models and two using “naïve” mobility or mobility squared models. The regression models were fitted using the CoMix contact survey and Google mobility data from the UK over March 2020 – March 2021. The four models were then used to scale synthetic contact matrices—a representation of pre-pandemic behaviour—using mobility data from the UK, Belgium and the Netherlands to predict the number of contacts expected in “work” and “other” settings for a given mobility level. We then compared partial reproduction numbers estimated from the four models with those calculated directly from CoMix contact matrices across the three countries. The accuracy of each model was assessed using root mean squared error. The fitted regression models had substantially more accurate predictions than the naïve models, even when models were applied to out-of-sample data from the UK, Belgium and the Netherlands. Across all countries investigated, the linear fitted regression model was the most accurate and the naïve model using mobility alone was the least accurate. When attempting to estimate social contact rates during a pandemic without the resources available to conduct contact surveys, using a model fitted to data from another pandemic context is likely to be an improvement over using a “naïve” model based on mobility data alone. If a naïve model is to be used, mobility squared may be a better predictor of contact rates than mobility per se.

  Funding: National Institute for Health and Care Research

# Summary. An optional shortened abstract.
summary: 
  This study compares the predictive ability of Google mobility data to pandemic-era contacts surveys

tags:
- COVID-19
- Social Mobility Data
- Social Contact Rates
- Modelling
- Prediction Methods
featured: true

links:
- name: Pre-Print
  url: "https://www.medrxiv.org/content/10.1101/2023.12.19.23300209v3"
url_code: "https://github.com/cmmid/comix_mobility"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: "Figure 4 from the publication"
#  focal_point: Smart
#  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
 - mobility

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
