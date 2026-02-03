# Task 11: A/B Testing – Hypothesis Testing in Python

## Objective
To perform A/B testing on a marketing dataset to determine whether a new version (Test group) performs better than the existing version (Control group) using statistical hypothesis testing.

## Tools & Technologies
- Google Colab
- Python
- Libraries: pandas, numpy, scipy, matplotlib, seaborn

## Dataset
- File: ab_test_data.csv
- Columns:
  - user_id: Unique identifier
  - group: Control or Test
  - converted: 1 = conversion, 0 = no conversion

## Methodology
1. Loaded dataset and separated control and test groups.
2. Defined hypotheses:
   - H0: No difference in conversion rates
   - H1: Difference exists in conversion rates
3. Set significance level (α = 0.05).
4. Calculated conversion rates.
5. Performed Chi-Square test.
6. Evaluated statistical significance.
7. Calculated confidence intervals.
8. Visualized group comparison.
9. Provided business recommendation.

## Results
- Conversion rates compared between control and test groups.
- Statistical test used: Chi-Square Test
- P-value used to determine significance.

## Files Included
- task11_abtest.ipynb
- ab_test_data.csv
- ab_test_summary.csv
- final_recommendation.txt

## Conclusion
Based on statistical analysis, a business decision was made on whether to deploy the test version.

---
