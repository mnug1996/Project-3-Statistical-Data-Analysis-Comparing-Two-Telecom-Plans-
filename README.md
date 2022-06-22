# Project 3 Statistical Data Analysis Comparing Two Telecom Plans

## Introduction for the project:

The goal for this project is to perform statistical data analysis for the telecom operator Megaline and determine which plan, Surf or Ultimate, brings in the most revenue so the company may adjust the marketing budget.

## Outline summary:
* Load and view the data.
* Prepare the data:
  * Created necessary columns, such as call counts, month, call duration totals.
  * Deleted any unnecessary columns.
* Analyze the data:
  * Merged the tables on customer ids.
  * Created boxplots to analyze the initial distribution and removed any outliers.
* Calculate monthly revenue:
  * Merged the revenue table with the main table
  * Formulated new features for messages, minutes, mb used
  * Used the new features to calculated the revenue based on the provided plan rates
* Re-analyze the data with revenue:
  * New histograms were created in relation with monthly revenue.
* Test Hypothesis:
  * Formulated null and alt hypothesis.
  * Ran a t-test for two populations of equal variance (surf and ultimate).
  * Compared alpha (0.05) with the resulting p-value from the t-test.
