# SAYOOJ K P — PORTFOLIO WEBSITE

## Portfolio Overview

This portfolio presents Sayooj K P's hybrid profile across:

- Mechanical Engineering
- Industrial / Refinery Maintenance
- Manufacturing
- AI / LLM Evaluation
- Prompt Engineering
- Technical QA & Documentation
- Machine Learning and Engineering Analytics

The website is designed for recruiter-friendly scanning, with engineering case studies, visual workflows, skills, experience, projects, and evidence-based career positioning.

## Featured AI / Machine Learning Project

### AI-Powered Predictive Maintenance & Failure Risk Analysis

An engineering-focused machine-learning project using the UCI AI4I 2020 Predictive Maintenance Dataset.

The project covers:

- Dataset understanding and engineering EDA
- Machine-failure distribution analysis
- Failure-mode consistency checks
- Engineering feature engineering
- Temperature difference calculation
- Angular-speed conversion
- Mechanical-power calculation
- Operating-regime analysis
- Imbalanced classification
- Logistic Regression baseline
- Random Forest modeling
- ROC-AUC and PR-AUC evaluation
- Confusion-matrix analysis
- Predictive feature importance
- Machine-failure risk segmentation

### Key Results

- 10,000 machine observations
- 14 original dataset columns
- 339 observed machine failures
- Observed failure rate: 3.39%
- Random Forest ROC-AUC: 0.963
- Random Forest PR-AUC: 0.856
- Failure precision: 0.909
- Failure recall: 0.735
- Failure F1-score: 0.813

### Engineering Features

The project created engineering-derived variables including:

- Temperature Difference = Process Temperature − Air Temperature
- Angular Speed = 2π × RPM / 60
- Mechanical Power = Torque × Angular Speed / 1000

The analysis found an observed association between higher mechanical power / high tool-wear operating regimes and increased failure rates. These relationships are treated as dataset associations rather than proof of causation.

### Modeling Considerations

Identifier fields were excluded from prediction. Failure-mode indicator columns were also excluded because they may represent information available during or after a failure event and could introduce target leakage.

## Technology Stack

Python · Pandas · NumPy · Scikit-learn · Matplotlib · Machine Learning · Predictive Maintenance · Feature Engineering · Imbalanced Classification · Risk Scoring

## Project Links

- GitHub: https://github.com/sayooj-kp/AI-Powered-Predictive-Maintenance
- Kaggle Notebook: https://www.kaggle.com/code/sayoojkp741/ai-powered-predictive-maintenance-data-eda

## Existing Portfolio Content

The website also presents:

- AI / LLM response evaluation
- Manufacturing-domain AI validation
- Concentric tube heat exchanger work
- Rice-bran alternative-fuel experimentation
- BPCL refinery maintenance experience
- Technical content and accessibility QA
- Recruiter-focused skills and experience mapping

## Files

- `index.html` — main portfolio website
- `assets/` — profile image and website assets
- `Sayooj_KP_Resume.pdf` — resume

## Usage

Open `index.html` in a browser to view the portfolio.
