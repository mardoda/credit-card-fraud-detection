# CSC5825 - Credit Card Fraud Detection Project

## Introduction
Credit card fraud is a significant concern for financial institutions globally. With the increase in online transactions and e-commerce, fraudulent activities have risen sharply. Early detection of such activities is critical to minimize potential financial losses.

## Problem Statement
Traditional rule-based systems are inadequate at detecting novel fraud patterns, prompting the need for advanced machine learning techniques. This project aims to leverage machine learning algorithms to predict and mitigate credit card fraud more effectively.

## Dataset Overview
- **Data Source**: Transactions by European Cardholders
- **Period**: Two days in September
- **Total Transactions**: 284,807
- **Fraudulent Transactions**: 492
- **Features**: 31 numerical features post-PCA transformation, with "Time" and "Amount" being the only untransformed features.
- **Class Imbalance**: 0.172% (highly imbalanced)

## Goals
- Develop models to predict fraudulent transactions using both supervised and unsupervised learning methods.
- Utilize visualization techniques to uncover hidden patterns within the data.

## Methods Employed
- **Supervised Learning**:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - Voting Classifier
- **Unsupervised Learning**:
  - K-means Clustering
  - BDS (Boundary-based Detection System)
  - Autoencoder Neural Networks
  - Local Outlier Factor (LOF)
  - Isolation Forest Algorithm

## Preliminary Results and Discussion
Initial explorations into the data involved analyzing the "Time" and "Amount" features through graphical representations, which proved challenging to interpret. To address this, a Robust Scaler was employed to scale these features, facilitating better integration with other scaled data. The generated heatmap provided insights into the relationships between features after scaling.

## Visualization
- Heatmap of scaled features to identify potential correlations and anomalies.

## Conclusion
This project is a comprehensive attempt to tackle the growing issue of credit card fraud using advanced machine learning and data visualization techniques. The findings and methodologies developed here aim to enhance the predictive capabilities of financial institutions in combating fraud.

Full Report Analysis: [Credit Card Fraud Detection.pdf](Credit%20Card%20Fraud%20Detection.pdf)
