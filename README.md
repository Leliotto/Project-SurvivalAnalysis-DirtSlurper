# DirtSlurper3100 – Survival Analysis

This repo contains our survival/reliability analysis for the DirtSlurper3100 robot vacuum. It includes EDA, Kaplan–Meier curves and model-based inference. The assignment emphasizes clear assumptions, model descriptions, and well-justified tests and estimates.

## Repository layout
data/
raw/ # original inputs
DirtSlurper3100.csv
docs/
DirtSlurper_2025.pdf
analysis/
Survival_Analysis_Project.Rmd
KM_curve.Rmd
report/
Report.pdf
outputs/
figures/ # rendered plots
tables/


## What’s inside

- **docs/DirtSlurper_2025.pdf**: official brief, scope, and requirements (EDA -> Modeling -> Inference). :contentReference[oaicite:1]{index=1}
- **data/raw/DirtSlurper3100.csv**: warranty dataset with registrations (2015–2019) and repair/censoring info (right-censored at 2019-12-31). :contentReference[oaicite:2]{index=2}
- **analysis/Survival_Analysis_Project.Rmd**: EDA + first Kaplan–Meier on the dataset.
- **analysis/KM_curve.Rmd**: KM curve on component-level.
- **report/Report.pdf**: report divided in: Intro, Methodology, Results and Conclusions. :contentReference[oaicite:3]{index=3}
