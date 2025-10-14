# DirtSlurper3100 – Survival Analysis

This repo contains our survival/reliability analysis for the DirtSlurper3100 robot vacuum. It includes EDA, Kaplan–Meier curves and model-based inference. The assignment emphasizes clear assumptions, model descriptions, and well-justified tests and estimates.

## Repository layout

<pre>
repo-root/
├─ data/
│  └─ DirtSlurper3100.csv
├─ docs/
│  └─ DirtSlurper_2025.pdf
├─ analysis/
│  ├─ Survival_Analysis_Project.Rmd
│  └─ KM_curve.Rmd
├─ report/
│  └─ Report.pdf
└─ outputs/
   ├─ figures/
   └─ tables/
</pre>



## What’s inside

- **docs/DirtSlurper_2025.pdf**: official brief, scope, and requirements (EDA -> Modeling -> Inference).
- **data/raw/DirtSlurper3100.csv**: warranty dataset with registrations (2015–2019) and repair/censoring info (right-censored at 2019-12-31).
- **analysis/Survival_Analysis_Project.Rmd**: EDA + first Kaplan–Meier on the dataset.
- **analysis/KM_curve.Rmd**: KM curve on component-level.
- **report/Report.pdf**: report divided in: Intro, Methodology, Results and Conclusions.
