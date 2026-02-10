# Smart Action — Predictive Modelling (R) | Master’s Thesis Deliverable

A historical (educational) predictive modelling project in **R**, preserved for portfolio transparency.  
This repository includes a curated landing page, the upgraded HTML report, and the original Master’s thesis PDF deliverable.

## Quick links
- **Live page (GitHub Pages):** https://valescabravo.github.io/Smart_Action-Predictive-Model/
- **Full report (HTML):** https://valescabravo.github.io/Smart_Action-Predictive-Model/SmartAction_Thesis_Upgraded.html
- **Thesis deliverable (PDF, Spanish):** https://valescabravo.github.io/Smart_Action-Predictive-Model/docs/smart-action-sustainable-tourism-thesis.pdf
- **Repository:** https://github.com/ValescaBravo/Smart_Action-Predictive-Model

> Note: This is an educational portfolio artefact (Master’s thesis). Results are dataset-specific and are not presented as business impact claims.

## Context (high level)
The thesis focuses on sustainable tourism and the **European Ecolabel (EEE)** for tourist accommodations. It combines:
- descriptive analysis of tourism supply/demand (Basque Country context)
- identification of EEE-certified accommodations
- a supervised learning approach to model the likelihood of achieving EEE based on available features

## Technical highlights (as documented)
- Compared **Random Forest**, **XGBoost**, and **Logistic Regression**
- Selected **regularised Logistic Regression** based on ROC performance
- Addressed class imbalance (minority class) using **SMOTE**
- Tuned hyperparameters via grid search (alpha/lambda) with cross-validation using `glmnet`

## Repository contents
- `index.html` — curated landing page for GitHub Pages
- `SmartAction_Thesis_Upgraded.html` — upgraded HTML report (full output)
- `docs/smart-action-sustainable-tourism-thesis.pdf` — Master’s thesis deliverable (PDF, Spanish)

## How to view
### Option 1 — Recommended (no setup)
Open the live page:
- https://valescabravo.github.io/Smart_Action-Predictive-Model/

### Option 2 — Open locally
Download the repo and open:
- `SmartAction_Thesis_Upgraded.html`

## Credits
Educational project maintained by **Valesca Bravo** (Master in Big Data & Business Intelligence). Co-authors are credited in the thesis PDF.
