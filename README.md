Bank Marketing Campaign – ML-Focused Exploratory Analysis

Project Overview

This project analyzes a real-world banking marketing dataset to understand the factors influencing customer subscription to term deposits.
The primary objective is to perform detailed Exploratory Data Analysis (EDA), extract feature-level insights, and identify variables that can be used in predictive machine learning models.
This project serves as the foundation for building a term deposit subscription prediction system.

Problem Statement

A Portuguese banking institution conducted direct telemarketing campaigns to promote term deposits. The dataset contains customer demographic, financial, and campaign-related information.
The goal is to:
1.Understand customer behavior
2.Identify influential features
3.Detect class imbalance issues
4.Prepare the dataset for ML-based classification modeling

Dataset Information

45,211 customer records
18 input features
Target variable: y (Subscription: yes / no)
Features include:
Demographics (age, job, marital, education)
Financial attributes (balance, loan, housing)
Campaign attributes (contact type, duration, campaign count, previous outcome)

Exploratory Data Analysis (EDA)

The following analyses were performed:
Age distribution analysis (binned histogram)
Job and education segmentation
Loan and credit default analysis
Balance distribution (skewness & outliers)
Campaign frequency analysis
Previous campaign interaction analysis
Subscription class imbalance visualization

Key Findings

Only ~12% of customers subscribed, indicating strong class imbalance.
Most customers were first-time campaign targets (previous = 0, pdays = -1).
Call duration shows the strongest correlation with subscription but cannot be used for pre-call prediction (data leakage).
Customers with a previous successful campaign outcome show significantly higher subscription probability.
The majority of clients are middle-aged (30–50 years) and financially stable.

Important ML Considerations

The dataset is highly imbalanced (88% No, 12% Yes).
Accuracy alone is not a reliable evaluation metric.
Precision, Recall, F1-score, and ROC-AUC should be used for model evaluation.
Duration must be excluded from predictive modeling to avoid data leakage.

Learning Outcome

This project strengthened my understanding of:
Real-world structured datasets
Customer behavior analysis
Feature relevance in classification problems
Preparing datasets for ML pipelines

Author

Harnaaz Kaur

Aspiring AI/ML Engineer

Python | Machine Learning | Data Analysis

