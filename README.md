
#Teclov Investment Strategy Analysis

This repository contains an analysis for Teclov, an asset management company, aimed at identifying the best investment opportunities across sectors, countries, and investment types. The project is driven by data from Crunchbase and focuses on optimizing investment decisions based on real-world trends.

About the Project

About the Project
Teclov, an asset management company, seeks to invest in sectors and countries where most investors are placing their bets, especially focusing on early-stage startups. This project aims to support the CEO in making informed decisions by:

Analyzing investment data from Crunchbase.
Narrowing down the best countries, sectors, and funding types for investments.
Recommending strategies based on past trends and investor behaviors.
The analysis adheres to the following constraints:

Investments must be between 5 to 15 million USD.
Investments must be made only in English-speaking countries.
Business Objective:
Teclov’s investment strategy revolves around:

Identifying the most promising sectors and investment types.
Choosing English-speaking countries with the highest investment potential.
Investing where other investors are placing significant bets.
Business Understanding
Teclov is particularly interested in:

Investment Type Analysis: Identifying the most suitable funding type (venture, seed, angel, private equity) based on typical investment amounts.
Country Analysis: Finding the top countries where most investors are putting their money.
Sector Analysis: Understanding investment patterns across the main sectors.
Dataset Overview
The data consists of three main components:

Rounds2: Contains funding rounds data.
Companies: Information about companies that have received investments.
Mapping File: Maps each sub-sector to one of eight main sectors for simplified analysis.
Data Cleaning Steps:
Remove duplicates and handle missing values.
Merge Rounds2 and Companies datasets into a single master frame for analysis.
Constraints:
Analyze only English-speaking countries.
Focus on investments between 5-15 million USD.
Features and Analysis
This project involves the following major analyses:

Funding Type Analysis: Evaluate which investment types (seed, venture, angel, or private equity) best fit Teclov’s investment strategy based on the target investment range.
Country Analysis: Identify the top nine countries receiving the highest total investments and narrow it down to the top three English-speaking countries.
Sector Analysis: Map companies to one of the eight main sectors and analyze which sectors are receiving the most investment.

Usage
Once the project is set up, run the Jupyter notebook to perform the following tasks:

Load Data: Load and clean the datasets.
Merge Data: Combine the rounds and companies datasets into a master data frame.
Investment Analysis: Analyze the most promising investment types, countries, and sectors based on Teclov’s strategy.
Generate Visualizations: Visualize the investment trends through plots.
Key Findings
Best Investment Type: Based on the funding amount range of 5 to 15 million USD, the most suitable investment type for Teclov is identified. Typically, venture or private equity funding types meet this criterion.
Top Countries: The top three English-speaking countries receiving the most investments are identified.
Best Sectors: The sectors attracting the highest number of investments across the top three countries are analyzed.
Visualizations
The following visualizations are included:

Funding Type Distribution: A plot showing the distribution of investments across seed, venture, angel, and private equity funding types.
Country-wise Investment: A plot showing the top 9 countries receiving the most funding.
Sector-wise Investment: A visualization of the top sectors receiving the most investments in each of the top three English-speaking countries.
Future Work
Expand the analysis by incorporating more recent and comprehensive data.
Perform time-series analysis to capture seasonality and investment trends over time.
Integrate machine learning models to predict future investment trends.
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







