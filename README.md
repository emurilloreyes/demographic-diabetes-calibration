# Demographic-Wise Calibration of Diabetes Risk Predictions

## Overview
The aim of this project is to investigate whether machine learning models trained to predict diabetes risk are equally well-calibrated across different demographic groups. For example, a predicted risk of 0.20 should ideally mean that approximately 20% of individuals receiving that prediction have diabetes, regardless of their demographic characteristics. We will investigate whether a globally calibrated model remains miscalibrated across specific groups and whether group-specific calibration methods can reduce these differences. 

## Research Questions
- Are globally calibrated models miscalibrated across demographic groups?
- Does global calibration close these gaps, or do group-specific calibrators perform better?
- Does improving calibration within individual groups come at the expense of overall performance?

## Dataset
**CDC Diabetes Health Indicators** dataset, obtained from the [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/).


## Methods
- Binary classifications w/ probability estimation
- Global and group-specific model comparisons
- Platt scaling
- Isotonic regression
- Calibration and performance evaluations

## Repository Structure

```text
├── data/          # Dataset documentation and data files
├── notebooks/     # Exploratory analysis and experiments
├── src/           # Reusable project code
├── results/       # Evaluation metrics and visualizations
├── reports/       # Final project report
└── docs/          # Project documentation
```

## Setup
1. Clone the repository
2. Install dependencies:
  ```text
  pip install -r requirements.txt
  ```
3. Download the dataset
4. Run notebooks in numerical order

## Team
- Eduardo Murillo Reyes
- Zaid Khan
- Raymond Yu

