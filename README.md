
# Demographic-Wise Calibration of Diabetes Risk Predictions

## Overview

The aim of this project is to investigate whether machine learning models trained to predict diabetes risk are equally well-calibrated across different demographic groups. For example, a predicted risk of 0.20 should ideally mean that approximately 20% of individuals receiving that prediction have diabetes, regardless of their demographic characteristics.

We will investigate whether a globally trained and calibrated model remains miscalibrated across specific groups and whether group-specific calibration models can reduce these differences.

## Research Questions

- Are global models miscalibrated across demographic groups?
- Does calibrating global models close these gaps, or do group-specific calibrated models perform better?
- Does improving calibration within individual group models come at the expense of overall performance?
- Does demographic-specific training improve probability calibration across demographic groups, and does this improvement justify the reduction in training data?

## Dataset

**CDC Diabetes Health Indicators** dataset, obtained from the [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators).

## Methods

- Binary classification with probability estimation
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

## Getting Started

### Prerequisites

- Python 3.10
- Git

### Installation

1. Clone the repository

2. Create a virtual environment:

```bash
python3.10 -m venv .venv
```

3. Activate the virtual environment:

   **macOS/Linux:**

```bash
source .venv/bin/activate
```

   **Windows (PowerShell):**

```bash
.venv\Scripts\Activate.ps1
```

4. Install the dependencies:

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

## Team

- Eduardo Murillo Reyes
- Zaid Khan
- Raymond Yu
