# Personal Loan Campaign Optimization 🏦🚀 

---
## Project Overview 📈
In an effort to expand its asset customer base, AllLife Bank aims to convert existing depositors into personal loan customers. This repository houses a machine learning project designed to support the bank's marketing strategies by leveraging data from a previous successful campaign.


## **Objectives 🎯**
- Develop a predictive model to assess the likelihood of depositors accepting a personal loan.
- Identify key determinants that influence the decision to purchase a loan.
- Highlight customer segments with a higher propensity for loan conversion.
- Predict the likelihood of customers accepting a personal loan.
- Identify key variables influencing loan acceptance.
- Segment customers based on their probability of purchasing a personal loan.

## Data Insights
- The project analyzes **customer data, including demographics, financial behaviors, and previous interactions with loan offers**, to extract actionable insights.
- Key variables include age, income, education, and more, offering a multifaceted view of potential loan customers.


## **Mission**
By pinpointing the characteristics of likely loan purchasers, _this initiative seeks to guide targeted marketing efforts_, _ultimately enhancing the bank's loan conversion rates_ and _fostering growth in its borrower segment_.

Based on the comprehensive overview you've provided for Joyce Adarkwah's Project 3 on Loan Modeling, here's a structured way to present your GitHub repository. This format focuses on clarity and easy navigation for users, aligning with your project's objectives, data handling, and analysis techniques, including the logistic regression and decision tree models you've utilized.

---
 

## Data Dictionary 📚

The dataset includes customer demographic and financial attributes:
- **ID**: Customer ID (Dropped for analysis)
- **Age**: Customer's age in years
- **Experience**: Years of professional experience
- **Income**: Annual income (thousand dollars)
- **ZIP Code**: Home address ZIP code
- **Family**: Family size
- **CCAvg**: Monthly credit card spending (thousand dollars)
- **Education**: Education level (1: Undergrad, 2: Graduate, 3: Advanced/Professional)
- **Mortgage**: House mortgage value (thousand dollars)
- **Personal_Loan**: Acceptance of a personal loan in the last campaign (0: No, 1: Yes)
- **Securities_Account**: Securities account with the bank (0: No, 1: Yes)
- **CD_Account**: Certificate of deposit account with the bank (0: No, 1: Yes)
- **Online**: Uses internet banking (0: No, 1: Yes)
- **CreditCard**: Has a credit card issued by another bank (0: No, 1: Yes)

## Data Preparation  🛠️

- Data loading and initial analysis using `pandas` and `numpy`.
- Visualization of distributions and correlations with `matplotlib` and `seaborn`.
- Handling of outliers and incorrect data entries.
- Splitting data into training (70%) and testing (30%) sets.

## Models  📊

Two main models were developed and evaluated:
- Logistic Regression
To predict the probability of a customer buying a personal loan.

- Decision Tree Classifier
To understand the decision-making process behind loan purchases.



### Model Evaluation  📝

- Performance metrics including accuracy, recall, and the confusion matrix were used to evaluate each model.
- Feature importance analysis for decision tree to identify key predictors.

## Recommendations 💡
Based on model insights, customers were segmented into high, average, and low target profiles for targeted marketing strategies.

## Directory Structure 📁
```
Personal Loam Campaign Project
│   README.md
│   Notebook.html   
│
└───data
│   │   Problem Statement.pdf

```

## How to Use 🚀
1. **Data Preparation**: Process your data according to the steps outlined in the `loan_modeling_notebook.ipynb`.
2. **Model Training**: Follow the notebook to train the logistic regression and decision tree models.
3. **Model Evaluation**: Evaluate the models using the provided metrics and choose the best one for your use case.
4. **Application**: Apply the insights from the model evaluations to target potential loan customers effectively.

---
Visual Insights 🖼️
All visuals are included in the **Notebook.html** file
