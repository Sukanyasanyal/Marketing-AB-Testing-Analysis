# Marketing Campaign A/B Test Analysis

**Python · Pandas · Statsmodels · Matplotlib · Jupyter Notebook**

## Business Problem

A company runs two types of marketing campaigns: Awareness and Conversion. The question: does the Conversion campaign produce a genuinely higher conversion rate than the Awareness campaign, or could the gap be down to random chance?

## Data

A public digital marketing campaign dataset (`digital_marketing_campaign_dataset.csv`), filtered to the two campaign types being compared.

## Approach

- Cleaned and prepared the campaign data for statistical analysis
- Set the null hypothesis: no difference in conversion rates between the two campaign types
- Ran a Z-test for proportions with Python's Statsmodels library
- Calculated confidence intervals for each group
- Packaged the findings into a PDF report with a business recommendation

## Results

| Group | Users | Conversions | Conversion Rate |
| --- | --- | --- | --- |
| Awareness campaign | 1,988 | 1,701 | 85.6% |
| Conversion campaign | 2,077 | 1,939 | 93.4% |

| Metric | Value |
| --- | --- |
| Difference | 7.8 percentage points |
| Relative lift | 9.1% |
| Z-statistic | -8.12 (Awareness listed first) |
| p-value | < 0.001 |
| Statistically significant | Yes |

## Key Finding

The Conversion campaign converted 93.4% of users versus 85.6% for the Awareness campaign: a 7.8-point gap, or a 9.1% relative lift. With a p-value below 0.001, the difference is very unlikely to be random chance.

**Business Recommendation:** Prioritize Conversion-type campaigns.

## Limitations

This compares two campaign types in an existing dataset. It is not a randomized experiment, so the result shows a strong association, not proof of cause. A controlled test would be needed to confirm it.

## Files

- [Full report (PDF)](AB_Testing.pdf)
- [Python notebook](AB_Testing_Marketing_analysis.ipynb)
