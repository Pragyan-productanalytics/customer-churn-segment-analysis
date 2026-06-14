# Customer Churn & Segment Analysis

## What This Project Does

This Excel dashboard tracks user churn and 
retention performance across subscription 
plan segments. It helps product and growth 
teams identify which user segments are at 
highest risk of churning so retention 
strategies can be prioritized effectively.

## Business Questions Answered

1. Which subscription plan has the highest 
   churn rate?
2. What is the overall retention health 
   of the product?
3. Which user segments need immediate 
   retention intervention?

## Key Findings

- Premium users have only 13% churn rate 
  — healthy retention
- Free Tier users have 67% churn rate 
  — critical alert
- Basic plan users have 67% churn rate 
  — critical alert  
- Overall churn rate is 45% against 
  an average retention rate of 55%
- Free Tier and Basic segments together 
  account for 89% of all churned users

## Business Recommendation

Free Tier and Basic plan users are churning 
at 5x the rate of Premium users. Product 
team should investigate:
- What features are Premium users accessing 
  that Free/Basic users are not?
- Is the value gap between plans too wide?
- Would a mid-tier plan reduce churn 
  from Free/Basic users?

## Tech Stack

- Microsoft Excel — dashboard design, 
  conditional formatting, KPI tracking
- Churn rate formula: 
  Churned Users / Total Segment Users
- Retention Health Status — automated 
  conditional formatting rules:
  Below 30% churn = Optimal Retention
  Above 50% churn = Critical Churn Alert

## Dashboard Features

- Total Portfolio Users KPI card
- Overall Active Cohorts counter
- Average Retention Rate display
- Subscription segment breakdown table
- Automated Retention Health Status 
  with color coding
- Calculated churn rate per segment

## Status

Expanding to include monthly cohort 
retention curves and time-series churn 
trend analysis.
