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
│  └─ Inference_on_Battery.Rmd
│  └─ DirtSlurper3100.csv
│  └─ Inference_on_ImpactSensor.Rmd
│  └─ KM_vs_Weibull.pdf
│  └─ KMcurve.pdf
│  └─ Battery_UsageGroups.pdf
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
- **analysis/Inference_on_Battery.Rmd**: Inference on battery capacity and usage (The battery manufacturer guarantees that the battery will retain at least 80% capacity
after 2400 hours of continuous use. Excluding extreme use cases (i.e., 2400 hours or
more of continuous use) the manufacturer guarantees L10 ≥ 1000 days. For repair
purposes, a battery with less than 80% capacity needs to be replaced.).
- **analysis/Inference_on_ImpactSensor.Rmd": Inference on ImpactSensor (The Impact sensor is built by IButler and an integral part of the design of the Dirt-
Slurper3100. No specifications concerning reliability have been provided to you. However,
IButler is considering selling this sensor through a satellite company. Help IButler
in providing lifetime specifications concerning this sensor).
- **report/Report_SA.pdf**: report divided in: Introduction, Exploration Data Analysis (EDA), Methodology, Results, Conclusions and Extra parts.
