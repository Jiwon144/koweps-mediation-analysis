# [Project 04] Macro-Panel Data Mediation Analysis Pipeline
# koweps-mediation-analysis

Python replication of a published mediation analysis using KOWEPS macro-panel data. Transitioning from SPSS to programmatic statistical modeling.

### About This Project

This project rebuilds the core analytical pipeline of a published empirical study (which I participated in as a 2nd author) to validate the methodology and showcase my programmatic data literacy. 

Crucially, while the original research relied on traditional GUI-based statistical software (SPSS), this repository completely replicates and automates the **mediation analysis using Python**. This transition demonstrates reproducibility, advanced data manipulation, and modern statistical modeling capabilities.

The analysis examines a multi-generational sociological model:
* **Hypothesis:** Parents' childhood economic adversity ($X$) decreases perceived positive parenting ($M$), which ultimately mediates and leads to lower academic achievement of the child ($Y$).

### Methodological Note: Computational Replication & Data Simulation

Please note that the dataset utilized in this repository is **synthetically generated** to mirror the statistical properties, sample distribution, and noise patterns of the **Korea Welfare Panel Study (KOWEPS)**. 

Due to data privacy and access restrictions regarding national longitudinal panel raw data, a priori generative modeling was implemented. The primary objectives of this computational simulation are:
1. **Methodological Transition:** To successfully migrate and replicate the original empirical mediation analysis into an automated, open-source Python pipeline.
2. **Robustness Testing:** To demonstrate programmatic data literacy by implementing OLS regression models and bootstrapping mediation verification on a large-scale, noise-injected dataset ($N=5,000$) prior to institutional data access.

**Data Source & Reference:**
* **Dataset:** Korea Welfare Panel Study (KOWEPS), Korea Institute for Health and Social Affairs & Seoul National University.
* **Original Study:** Young-Jae Cha, Jiwon Kim, Dayk Jang, 2017, The Effect of Harsh Early Childhood Environments of Parents on Academic Achievement of Children: The Mediating Role of Perceived Positive Parenting, Paper presented at the 10th Korea Welfare Panel Study (KOWEPS) Conference
