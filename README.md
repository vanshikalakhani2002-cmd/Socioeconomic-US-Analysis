# A Socioeconomic Analysis of U.S. States

How education, household income, and industry employment connect across U.S. states, using 2020–2021 U.S. Census data. I took three messy, separate datasets, cleaned and merged them into one reliable source, then built Tableau dashboards aimed at a non-technical audience like policymakers and economic planners.

## What's in here

| File | What it is |
|------|-----------|
| `Socioeconomic_Analysis.ipynb` | The full Python workflow — profiling, cleaning, transformation. Charts render in the notebook. |
| `Report.pdf` | The written report with the Tableau dashboards and interpretation. |
| `data/Inconsistent_US_dataset.csv` | The merged dataset (917 rows, 60 columns). |

## The work

Starting from three public Census files (education, finance, industry) covering 437 districts, I merged them into a single state-level table, then cleaned it in Python — handling missing values, capping outliers with IQR, removing duplicates, and standardising formats. From there I built four Tableau dashboards: gender-wise employment by industry, education vs high income, a state-wise income heatmap, and a population treemap by education level.

Kaggle source: [https://www.kaggle.com/datasets/mittvin/u-s-census-dataset-educationfinanceindustry/data](https://www.kaggle.com/datasets/mittvin/u-s-census-dataset-education-finance-industry)

## What I found

- Higher education tracks strongly with a larger high-income population — though a few states hit high incomes without it, pointing to other drivers like tech, oil, or manufacturing.
- Industry employment is consistently gender-segregated: women concentrate in education and arts, men in manufacturing and retail.
- Middle-income households cluster in California, Texas, and Florida, while states like Alaska and Wyoming sit far lower.

## Tools

Python (pandas, NumPy, seaborn, matplotlib) · Tableau · Excel
