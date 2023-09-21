## Researching Recession Proof Retail Trades

Description:
This GitHub repository contains the code and data for an analysis of spending patterns during recessions in the United States. We aimed to investigate whether certain categories of spending, as a percentage of total spending, statistically increase or decrease during economic recessions.

Dataset:
We combined two datasets for this analysis: "Dates of US Recessions (Monthly)" and "Retail and Food Services Sales." The datasets were cleaned and matched based on recession dates. Missing values in the Retail and Food Sales dataset were updated, and the data was transformed to include the percentage of total spending for each category. Two categories, Jewelry and Men's clothing retail, were excluded due to extensive missing data.

Hypothesis Testing:
We formulated our hypotheses as follows:

Null Hypothesis (H0): The mean spending, as a percent of total spending, in a particular category during a recession is equal to the mean percent of total spending in the same category outside of a recession.
Alternate Hypothesis (H1): The mean spending in a particular category, as a percent of total spending, during a recession is different from the mean percent of total spending in the same category outside of a recession.
We performed Welch’s two-sample t-tests to compare mean percent spending in each category during and outside of a recession. The test results, including test statistics and p-values, were used to determine if we could reject the null hypothesis. We used a significance level of 0.05 for hypothesis testing.

Repository Contents:
Data: Contains the cleaned and merged datasets used for the analysis.
Code: The code for data preprocessing, hypothesis testing, and generating visualizations is located here.
