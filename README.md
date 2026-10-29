# Statistical Investigation of Factors Associated with Student Stress

## Project Overview

This project investigates statistical associations between recorded student stress categories and selected psychological, physiological, environmental, academic, and social variables.

Using descriptive statistics, exploratory data analysis (EDA), Spearman's rank correlation, hypothesis testing, and a correlation heatmap, the analysis examines patterns in student stress data.

## Dataset

- **Source:** [Kaggle: StressLevelDataset.csv](https://www.kaggle.com/datasets/izedikeanita/stressleveldataset-csv)
- **Observations:** 1,100
- **Columns:** 21, comprising 20 explanatory variables and the `stress_level` outcome.

## Methods

- Data loading and quality checks
- Variable range and coding inspection
- Descriptive statistics and exploratory visualisations
- Spearman's rank correlation analysis
- Hypothesis testing with Benjamini–Hochberg adjustment
- Cross-tabulation of blood-pressure codes and stress categories
- Correlation heatmap analysis

## Key Findings

- All ten variables included in the hypothesis tests showed statistically significant associations with `stress_level` after Benjamini–Hochberg adjustment at the 0.05 significance level.
- `self_esteem` and `sleep_quality` showed strong negative associations with recorded stress categories.
- `bullying`, `future_career_concerns`, and `anxiety_level` showed strong positive associations.
- The heatmap revealed relationships among explanatory variables, including a strong positive correlation between `basic_needs` and `academic_performance`.
- The cross-tabulation revealed an unusual pattern between recorded blood-pressure codes and stress categories, warranting further investigation.

## Limitations

The analysis identifies associations, not causal relationships. The meanings of the recorded stress categories and the coding procedures require further verification. The unusual blood-pressure pattern also warrants investigation before substantive conclusions are drawn.

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn, SciPy, and Jupyter Notebook.

## Reproducibility

Download the dataset from the Kaggle link above and update the notebook's data-loading path to match your local environment before running the analysis.
