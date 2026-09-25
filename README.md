# NextHikes Retail EDA

## Exploratory Data Analysis of Large-Scale Retail Transaction Data

This project performs Exploratory Data Analysis (EDA) on a retail transaction dataset containing 100,000 records and 18 variables.

### Objectives

- Understand numerical and categorical variable distributions
- Perform univariate analysis
- Analyze relationships using bivariate analysis
- Perform multivariate analysis
- Detect outliers using the IQR method
- Study correlations between numerical variables
- Analyze skewness and kurtosis
- Perform statistical validation
- Identify meaningful business insights

### Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Jupyter Notebook

### Project Files

- `NextHikes_Retail_EDA.ipynb` — Complete EDA notebook
- `NextHikes_Retail_EDA_Presentation.pptx` — Project presentation
- `retail_large_dataset.csv` — Dataset

### Key Findings

- Dataset contains 100,000 transactions and 18 variables.
- No missing values or duplicate rows were identified.
- `product_price` and `quantity` have the strongest positive associations with `final_price`.
- IQR outliers were identified only in `final_price`.
- Customer segment and product category did not show statistically significant differences in mean final price.
- Return rates remained within a narrow range across categories and shipping conditions.

## Author

Jineshri Mehta
