# Natural-gas-price-estimation

Project Overview

This project was developed as part of the J.P. Morgan Quantitative Research Job Simulation. The objective is to build a prototype model that estimates natural gas prices for specific dates using historical data and forecasts prices for the next 12 months.

The project demonstrates how Python can be used to analyze historical commodity prices and support preliminary pricing decisions for natural gas storage contracts.

Objectives

Analyze historical monthly natural gas prices.

Estimate prices for specific dates using historical observations.

Forecast natural gas prices for the next 12 months.

Visualize historical prices and forecast trends.

Develop a basic pricing model for further testing and validation.

Dataset

The dataset contains monthly natural gas price observations from October 2020 to September 2024.

The main columns are:

Dates: Date of the monthly observation.

Prices: Recorded natural gas price.

Technologies Used

Python – Model development and analysis.

Pandas – Data loading and manipulation.

NumPy – Numerical calculations and linear trend fitting.

Matplotlib – Data visualization.

Jupyter Notebook / Python – Data analysis and model experimentation.

Methodology

Data Preparation: Load the dataset, convert dates into the correct format, handle invalid records, and sort observations chronologically.

Price Estimation: Use linear interpolation to estimate prices between available historical observations.

Price Forecasting: Fit a simple linear trend to recent observations and extrapolate prices for the next 12 months.

Visualization: Plot historical price movements and compare them with forecast estimates.

Output Generation: Export the forecast results to a CSV file and save charts for further analysis.
