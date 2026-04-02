# Income Classification using Machine Learning

## Overview
This project focuses on predicting whether an individual's income exceeds $50K per year using the Adult dataset. The objective is to classify individuals into income groups based on demographic and employment-related features.

## Dataset
The dataset includes variables such as:
- Age
- Workclass
- Education
- Marital status
- Occupation
- Relationship
- Race
- Sex
- Capital gain/loss
- Hours per week

Missing values were handled and categorical variables were properly encoded.

## Methodology
The following steps were performed:
- Data cleaning and preprocessing
- Handling missing values
- Exploratory data analysis
- Splitting data into training and validation sets
- Model development using classification techniques
- Bootstrapping for model stability

## Models Developed
- **Logistic Regression**
- **Linear Discriminant Analysis (LDA)**
- **Decision Tree (CART)**

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Key Findings
- Logistic Regression performed the best overall
- Class imbalance affected recall for the minority class
- Model performance improved with proper preprocessing

## Files Included
- `Final_Report_Mithoon.pdf`
- `Classification_Project.Rmd`
- `Classification_Project.html`

## Conclusion
The study shows that classification models can effectively predict income categories, with Logistic Regression providing the most stable and interpretable results.
