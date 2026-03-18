# coupon-acceptance-analysis
# Will the Customer Accept the Coupon?

## Overview
Analysis of driving coupon acceptance using 
survey data from UCI Machine Learning Repository.
Collected via Amazon Mechanical Turk survey.

## Key Findings

### Overall
- 56.84% of customers accepted coupons overall
- Coffee House was the most common coupon type
- Warm weather (80F) had the most survey responses

### Bar Coupons (41.19% acceptance rate)
- Frequent bar visitors (3+ times/month) accept 
  at 76% vs 37% for infrequent visitors
- Having kids in the car significantly reduces 
  acceptance
- Drivers over 25 who visit bars regularly 
  accept at 69% vs 34% for others
- Social lifestyle is the strongest predictor

### Coffee House Coupons (49.57% acceptance rate)
- Frequent visitors accept at 68% vs 17% 
  for people who never visit coffee houses
- Drivers under 21 have the highest acceptance
- Traveling with friends increases acceptance
- 10AM is the best time to deliver coupons
- Rainy weather increases acceptance

## Recommendations
- Target bar coupons at frequent bar goers 
  aged 25+ traveling without kids
- Deliver coffee house coupons at 10AM 
  to young frequent visitors on rainy days
- Avoid targeting people who never visit 
  the coupon venue — very low acceptance

## Next Steps
- Build a predictive ML model to classify 
  coupon acceptance
- Analyze remaining coupon types
- Investigate combinations of variables

## Files
- [coupon_acceptance_analysis.ipynb](coupon_acceptance_analysis.ipynb) — Full analysis notebook
- [coupons.csv](coupons.csv) — Dataset

## Tools Used
Python | Pandas | Matplotlib | Seaborn | Jupyter
