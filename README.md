# JPMorgan-Quantitative-Research-Simulation
Completed JPMorgan Chase &amp; Co. Quantitative Research Simulation covering natural gas price analysis, predictive modeling, and credit risk assessment. Developed functions for commodity storage contract pricing, PD estimation using logistic regression and decision trees, and FICO score bucketing.


Project Overview: JPMorgan Chase & Co. Quantitative Research Simulation
This project encompasses a series of tasks designed to enhance skills in quantitative research, data analysis, and predictive modeling within the context of financial commodities and credit risk assessment.
Task 1: Investigate and Analyze Price Data
In this task, I focused on analyzing natural gas price data. The key steps included:
Data Acquisition: Downloaded monthly natural gas price data from a market data provider, covering prices from October 2020 to September 2024.
Data Analysis: Developed code to analyze historical price data and estimate prices for any given date in the past.
Extrapolation: Created a model to predict future prices for an additional year based on existing trends.
Visualization: Implemented visualizations to identify seasonal trends and patterns in natural gas pricing.
Task 2: Price a Commodity Storage Contract
This task involved creating a prototype pricing model for commodity storage contracts. The main components included:
Function Development: Wrote a function that calculates the value of a storage contract based on various parameters such as injection and withdrawal dates, prices, storage costs, and maximum volume.
Cash Flow Consideration: Analyzed all cash flows involved in the contract pricing to ensure accurate valuation.
Testing: Conducted tests with sample inputs to validate the pricing model's functionality.
Task 3: Credit Risk Analysis
In this task, I built a model to estimate the probability of default (PD) for borrowers using loan data. The key steps included:
Data Preparation: Loaded and explored borrower datasets to identify relevant features.
Model Development: Implemented logistic regression and decision tree models to predict default probabilities.
Expected Loss Calculation: Developed functions to calculate expected losses based on predicted default probabilities.
Task 4: Bucket FICO Scores
This task involved categorizing borrowers based on their FICO scores to analyze default probabilities. The main components included:
Bucketing Implementation: Created a method for categorizing FICO scores into discrete buckets using equal-width binning.
Probability of Default Calculation: Developed a method to calculate the probability of default for each bucket based on historical data.
Log-Likelihood Optimization: Implemented a log-likelihood function to evaluate the effectiveness of the bucketing strategy.
Conclusion
Through these tasks, I gained valuable experience in data manipulation, statistical analysis, predictive modeling, and financial analysis. 
