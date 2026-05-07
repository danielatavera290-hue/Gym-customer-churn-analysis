# Gym Customer Churn Analysis

Predicting which gym members are likely to cancel 
their membership using machine learning.

---

## Business Problem
A gym chain needed to identify customers at risk of 
canceling before it happened, to take proactive 
retention actions.

## Objective
Build a predictive model for churn and segment 
customers into behavioral clusters to design targeted 
retention strategies.

## Dataset
10,000 gym members with 13 variables including contract 
length, visit frequency, age, group class participation, 
and lifetime as a member.

## Tools & Libraries
Python · Pandas · Matplotlib · Seaborn · Scikit-learn 
(LogisticRegression, RandomForest, KMeans) · SciPy

## Project Structure
1. Exploratory Data Analysis (EDA)
2. Correlation analysis
3. Predictive model — churn classification
4. Customer segmentation with K-Means clustering
5. Conclusions and business recommendations

## Model Results

| Model | Accuracy | Precision | Recall |
|---|---|---|---|
| Logistic Regression | 92.4% | 85.9% | 82.8% |
| Random Forest | 91.2% | 84.1% | 80.3% |

Logistic Regression outperformed Random Forest across 
all metrics.

## Key Findings
- **26.5%** overall churn rate
- Clusters 2 & 3 showed churn rates of **44–51%** 
  — highest risk segments
- Clusters 0 & 4 showed churn rates of only **3–7%** 
  — most loyal customers
- Top churn predictors: contract length, visit 
  frequency, and customer lifetime
- Group class participation strongly correlated 
  with retention

## Recommendations
1. Incentivize annual contracts at sign-up with 
   discounts or perks
2. Implement a 3-month onboarding program for 
   new members (most churn happens before month 5)
3. Offer a free group class at sign-up to build 
   the habit early
4. Use the predictive model to flag at-risk customers 
   and trigger personalized offers before they cancel

## Files
- `gym_churn_analysis.ipynb` — full analysis notebook
