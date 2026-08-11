# Marketing Campaign A/B Test Analysis
**Python · Pandas · Statsmodels · Matplotlib · Jupyter Notebook**

## Business Problem
A company ran two marketing campaigns targeting the same audience. 
The goal was to determine whether the new campaign genuinely improved 
conversion rates or whether the difference was due to random chance.

## Approach
- Cleaned and prepared campaign data for statistical analysis
- Defined null hypothesis: no difference in conversion rates between campaigns
- Applied Z-test for Proportions using Python's Statsmodels library
- Packaged findings into a formal PDF report with business recommendation

## Key Finding
The new campaign produced a **9.1% higher conversion rate** than the 
control group. With a p-value < 0.001, this result is statistically 
significant — meaning there is less than 0.1% probability this 
difference occurred by chance.

**Business Recommendation:** Adopt the new campaign strategy.

## Results
| Metric | Value |
|--------|-------|
| Conversion Lift | 9.1% |
| p-value | < 0.001 |
| Statistical Significance | Yes |
| Test Used | Z-test for Proportions |


## Tools Used
Python · Pandas · Statsmodels · Matplotlib · Jupyter Notebook

## Files:
* [View the Full Report (PDF)](AB_Testing.pdf)
* [View the Python Notebook](AB_Testing_Marketing_analysis.ipynb)
