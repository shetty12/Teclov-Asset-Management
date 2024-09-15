
# Aerofit Treadmill Purchase Prediction and Customer Profiling

This project leverages Aerofit customer data to identify characteristics that influence the purchase of one of three treadmill models: KP281, KP481, and KP781. The aim is to provide data-driven recommendations for treadmill purchases based on customer profiles

About the Project

Problem Statement
Aerofit collects customer data on variables such as gender, age, income, weekly usage, fitness, marital status, and miles run on the treadmill. The goal is to identify patterns that drive the purchase of one of three treadmill models:

KP281: Entry-level treadmill.
KP481: Mid-tier treadmill.
KP781: High-end treadmill.
The objective is to recommend the most suitable treadmill to future customers based on their profiles.

Dataset Overview
The dataset consists of 180 rows and 9 columns representing customer attributes and treadmill product:

Product: KP281, KP481, KP781
Age: Age of the customer
Gender: Male or Female
Education: Years of education
MaritalStatus: Single or Partnered
Usage: Weekly treadmill usage (days)
Fitness: Self-reported fitness level (1-5)
Income: Annual income in USD
Miles: Miles run per week on the treadmill
Analysis and Modeling

1. Data Preprocessing
Categorical Encoding: Gender, MaritalStatus, and Product columns were encoded for analysis.
Binning: Continuous variables like Age, Income, and Miles were binned for better interpretability.
Outlier Detection: Outliers in Age, Income, and Miles were identified, but instead of removing them, they were clipped due to the small dataset size.

2. Correlation Analysis
The product choice highly correlates with factors such as Education, Income, Usage, Fitness, and Miles run.
Usage and Miles are strongly correlated with higher-end products (KP781), while lower-end products (KP281) are preferred by those with lower Income and Fitness.

3. Visualization
Scatterplots and factorplots were used to identify patterns in customer preferences based on Income, Age, Usage, and Miles run.
Correlation heatmaps were created to visualize relationships between variables.

4. Conditional and Marginal Probabilities
The likelihood of a customer buying a particular treadmill model was calculated using conditional and marginal probabilities based on factors like Income, Fitness, and Usage.
Key Insights
KP281:

Preferred by customers with lower income (below $50,000), older age, and moderate fitness levels.
Women over 40 with incomes below 70k are frequent buyers.
KP481:

Favored by middle-aged customers with moderate income ($50,000 - $70,000) and fitness levels.
Men with incomes between 60k-70k who run 100-150 miles are likely to buy KP481.
KP781:



Usage
Load the dataset and preprocess it by encoding categorical variables and binning continuous variables.
Perform correlation analysis and visualizations using seaborn and matplotlib.
Apply conditional and marginal probability analysis to identify customer preferences.
Use the provided customer profiles to recommend treadmill models based on new customer data.

## Badges



[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)
![Python](https://img.shields.io/badge/python-3.8-blue.svg)
![Pandas](https://img.shields.io/badge/pandas-1.2.4-blue.svg)
![NumPy](https://img.shields.io/badge/numpy-1.19.2-orange.svg)
![Matplotlib](https://img.shields.io/badge/matplotlib-3.3.4-orange.svg)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-0.24.2-yellow.svg)
![Scipy](https://img.shields.io/badge/scipy-1.6.0-lightgrey.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)


## Deployment

To deploy this project run

```bash
  npm run deploy
```
Navigate to the directory and install the required libraries:
```bash
cd Teclov_Investment_Analysis
pip install -r requirements.txt
```
Launch the Jupyter Notebook:
```bash
 jupyter notebook Teclov_Investment_Analysis.ipynb







