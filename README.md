# Sales & Customer Satisfaction — Exploratory Data Analysis

An end-to-end exploratory data analysis (EDA) project on a sales and customer satisfaction dataset, built for **CSE303: Statistics for Data Science**. The analysis compares a **Control** group against a **Treatment** group to understand how an intervention affected sales and customer satisfaction.

## What this project does

- Loads and inspects a 10,000-row sales & satisfaction dataset
- Checks class balance across categorical features using pie charts
- Automatically classifies each column as numeric (continuous/discrete) or categorical
- Computes descriptive statistics — mean, median, mode, variance, standard deviation for numeric columns; frequency and percentage for categorical columns
- Visualizes distributions with histograms, bar charts, and pie charts
- Analyzes relationships between variables with correlation coefficients, regression plots, and a correlation heatmap
- Encodes categorical variables into numeric form (label encoding / frequency encoding)
- Detects and handles missing values using mean imputation (numeric) and mode imputation (categorical)

## Key findings

- Sales increased notably from **Control** to **Treatment** (mean sales rose from ~204 to ~280)
- Customer satisfaction also improved after treatment (~70.3 → ~73.9)
- `Sales_Before` and `Sales_After` are strongly correlated (**0.89**)
- `Customer_Satisfaction_Before` and `Customer_Satisfaction_After` are strongly correlated (**0.84**)
- The dataset originally had ~9,771 missing values across all columns, fully handled through imputation

## Tech stack

- **Python**
- **Pandas** — data loading, cleaning, and transformation
- **Seaborn** & **Matplotlib** — data visualization
- **Scikit-learn** — label encoding

## How to run

1. Clone this repository
2. Make sure `sales_satisfaction.csv` is in the same folder as the notebook
3. Install dependencies:
   ```
   pip install pandas seaborn matplotlib scikit-learn
   ```
4. Open `assignment2.ipynb` in Jupyter Notebook / JupyterLab / VS Code and run all cells

## Author

Khadija — CSE, 4th Year
