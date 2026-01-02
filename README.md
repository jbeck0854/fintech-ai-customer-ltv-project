# FinTech Customer Lifetime Value (CLTV) Drivers
End-to-end AI &amp; anaytics project analyzing drivers of customer lifetime value in fintech using unsupervised and supervised learning methods.

## Overview
This project analyzes the drivers of customer lifetime value (CLTV) in a fintech environment using unsupervised learning, supervised classification, and operational modeling.

Rather than relying on monetary proxies that inflate predictive accuracy whilst providing little insight, the analysis pivots toward identifying **operationally controllable drivers** of CLTV.

## Key Objectives
- Identify natural customer segments using unsupervised learning.
- Evaluate supervised models for predicting high vs low CLTV.
- Diagnose why monetary features dominate prediction.
- Identify actionable operational drivers of CLTV.

## Key Insight
Operational excellence - particularly **Issue Resolution Time** - is the strongest lever for improving customer lifetime value in this digital wallet environment.

Improving support operations yields an estimated **$33K-$47K LTV uplift per customer**, with potential revenue impact exceeding **$46M** under realistic migration scenarios.

## Repository Structure
data/-> Original dataset as obtained from the source (csv)
reports/-> Final written report (PDF)
slides/-> Final presentation slides (PDF)
notebooks/-> Jupyter notebooks (R scripts for supporting analysis & modeling)

### Run Order
1. notebooks/1_Preprocessing,_EDA,_Unsupervised,_Introductory_Supervised.ipynb
2. notebooks/2_Supervised_Learning.ipynb
3. notebooks/3_Supervised_Learning_Drivers_of_LTV.ipynb
