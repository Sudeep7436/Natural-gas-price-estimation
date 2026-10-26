# Natural-gas-price-estimation-- J.P. Morgan Quantitative Research Job Simulation

Overview

This repository contains the projects I completed as part of the J.P. Morgan Quantitative Research Job Simulation. The projects focus on credit risk analysis, FICO score bucketing, natural gas price analysis, and commodity storage contract pricing using Python and quantitative techniques.

The objective was to explore financial data, build analytical models, and understand how quantitative methods can support risk assessment and commodity pricing.

Projects Included

1. Credit Risk Analysis
File: Credit risk analysis.ipynb
* Analyzed loan-related data to understand credit risk.
* Explored loan default prediction using machine learning.
* Worked with logistic regression and probability of default concepts.
* Examined how quantitative analysis can support lending decisions.

2. Bucket FICO Scores
File: Bucket FICO Scores.ipynb
* Worked with FICO credit scores for credit risk assessment.
* Explored score bucketing to group borrowers into risk categories.
* Used log-likelihood calculations and dynamic programming to determine score buckets.
* Examined how credit score groups can help distinguish different levels of default risk.

3. Natural Gas Price Data Analysis
File: Investigate and analyze price data natural_gas.ipynb
* Explored historical natural gas prices.
* Analyzed price movements and trends over time.
* Investigated monthly seasonality in natural gas prices.
* Developed a forecasting approach to estimate prices for the following 12 months.

4. Commodity Storage Contract Pricing
File: Price a commodity storage contract.ipynb
* Developed a prototype for estimating natural gas prices on specific dates.
* Used historical price observations to estimate prices between available dates.
* Explored price extrapolation for dates outside the observed period.
* Applied the estimated prices to a commodity storage contract pricing problem.

Dataset
File: Nat_Gas.csv
The dataset contains monthly natural gas price observations from October 2020 to September 2024.

Column
Description
* Dates: Date of the observation
* Prices: Observed natural gas price
The dataset is used for natural gas price analysis and commodity storage contract pricing.
The credit risk and FICO score notebooks require a separate loan dataset that is not included in this repository.

Technologies Used
* Python – Data analysis and model development
* Pandas – Data cleaning and manipulation
* NumPy – Numerical computations
* Matplotlib – Data visualization
* Scikit-learn – Machine learning
* SciPy – Scientific and statistical computations
* Jupyter Notebook – Interactive coding and analysis

JP-Morgan-Quantitative-Research/
│
├── Credit risk analysis.ipynb
├── Bucket FICO Scores.ipynb
├── Investigate and analyze price data natural_gas.ipynb
├── Price a commodity storage contract.ipynb
├── Nat_Gas.csv
├── requirements.txt
├── .gitignore
└── README.md

Key Learnings
* Financial data analysis and exploratory data analysis.
* Credit risk assessment and probability of default.
* FICO score bucketing using dynamic programming.
* Natural gas price trend and seasonality analysis.
* Price estimation and forecasting techniques.
* Applying Python to quantitative research problems.

Limitations
* Credit risk notebooks require the separate loan dataset to run completely.
* Forecasting methods are prototypes and may not capture all market conditions.
* Models require additional testing, backtesting, and validation before practical financial use.
