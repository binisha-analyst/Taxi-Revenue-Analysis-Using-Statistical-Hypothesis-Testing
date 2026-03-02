# Taxi Revenue Analysis Using Statistical Hypothesis Testing
## Project Overview
This project applies statistical hypothesis testing to determine whether the method of payment (Credit Card vs Cash) has a significant impact on taxi fare revenue.
The analysis includes data cleaning, exploratory analysis, normality checks, and an independent T-test to evaluate differences in average fare amounts between payment types.

## Objective
To test whether there is a statistically significant difference in average fare amount between customers who pay by:
- Credit Card
- Cash

## Data Cleaning
The dataset was cleaned by:
- Removing negative fare and total amounts
- Handling zero trip distance anomalies
- Validating passenger count records
- Eliminating invalid time records
- The final cleaned dataset is included as cleaned_taxi_data.csv.

## Statistical Approach

**Null Hypothesis (H0):**
There is no significant difference in average fare between credit card and cash payments.

**Alternative Hypothesis (H1):**
There is a significant difference in average fare between credit card and cash payments.

**Significance Level (α)** = 0.05

**Test Used:** Independent T-test

**Result:** p-value < 0.001

**Decision:** Reject H0

## Key Insight

The analysis shows a statistically significant difference in average fare between payment types. However, business decisions should also consider the practical magnitude of the difference before implementing operational changes.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- SciPy

## Files Included

*Yellow_trip_Statistics_project.ipynb* – Full analysis notebook

*cleaned_taxi_data.csv* – Cleaned dataset used for analysis
