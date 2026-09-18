# Titanic Dataset — Exploratory Data Analysis

Exploratory Data Analysis (EDA) on the Titanic passenger dataset using Python, pandas, NumPy, Matplotlib, and Seaborn.

## Project Structure

DS 01/
├── Data/
│ └── Titanic-Dataset.csv
├── notebooks/
│ ├── 01_setup_and_loading.ipynb
│ ├── 02_missing_duplicates.ipynb
│ ├── 03_group_analysis.ipynb
│ └── 04_visualization.ipynb
├── requirements.txt
└── README.md


## Setup
python -m venv venv
venv\Scripts\Activate
pip install -r requirements.txt



## Key Findings
- Overall survival rate: 38.38%
- Female survival rate (74.20%) far exceeded male (18.89%)
- 1st class passengers had the highest survival rate (62.96%) vs 3rd class (24.24%)
- Age and Embarked missing values were filled (median/mode); Cabin left unchanged due to 77% missing data
- Fare was highly right-skewed with outliers among 1st-class passengers