# 🍷 Wine Quality Analysis — CRISP-DM Portfolio Project

## 📌 Project Overview
This project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology to perform a structured exploratory data analysis (EDA) on wine quality data.
The objective is to identify key physicochemical factors influencing wine quality and translate insights into business-relevant recommendations.

## 1️⃣ Business Understanding
Wine quality assessment is subjective and depends on expert tasting. This project aims to support data-driven quality control decisions.

## Business Problem

Wine quality assessment is largely subjective and dependent on expert tasting.
Organizations seek data-driven insights to understand what factors influence wine quality and to improve production consistency.

## Business Objective

Understand drivers of wine quality

Support quality control decisions with data

Create a foundation for future predictive analytics

## Business Success Criteria

Clear identification of influential variables

Actionable insights for production and quality teams

Transparent and reproducible analysis

## 2️⃣ Data Understanding
EDA performed to understand distributions, correlations, and key drivers of wine quality.

## Dataset Description

The dataset contains wine samples with physicochemical properties such as:

Acidity measures

pH

Alcohol

Sulphates
along with a quality score assigned by experts.

## Analysis Performed

Data structure and summary statistics

Missing value and data quality checks

Distribution analysis of key variables

Correlation analysis between chemical attributes and quality

## Key Insights

Alcohol content shows a strong positive association with wine quality

Volatile acidity negatively impacts quality

Quality scores are unevenly distributed

Wine Quality Distribution
<img width="712" height="520" alt="image" src="https://github.com/user-attachments/assets/dd11f5af-e7dc-49c6-b24f-f59b129e8c9a" />

Distribution of PH
<img width="716" height="548" alt="image" src="https://github.com/user-attachments/assets/295456af-ddd6-43b7-948e-aeab657a080b" />

Boxplot for Alcohol
<img width="713" height="557" alt="image" src="https://github.com/user-attachments/assets/e555cd41-ab7b-4038-a3e3-cdb96620e537" />



## 3️⃣ Data Preparation
Data cleaned and prepared for analytical exploration.

## Preparation Steps

Data cleaning and validation

Feature inspection and selection

Outlier analysis

Dataset prepared for deeper analytical exploration

## Outcome

A clean, analysis-ready dataset suitable for:

Business analytics

Statistical analysis

Future machine learning (optional extension)

## 4️⃣ Modeling
Not implemented. This project focuses strictly on EDA.

⚠️ Important Note
This project intentionally focuses on exploratory and descriptive analytics only.
No predictive or machine learning models are implemented at this stage.

## Future Scope

Wine quality classification

Regression-based quality prediction

Feature importance analysis

## 5️⃣ Evaluation
Insights evaluated using statistical and business interpretation.

Shapiro-Wilk Test for pH: Statistic=0.9921162007107959, p-value=8.67292819515674e-06
Kruskal-Wallis H Test for Alcohol: H-statistic=284.0973205779734, p-value=2.03727977956863e-62

Interpretation of Results:
If the p-value from the ANOVA or Kruskal-Wallis test is less than 0.05, we reject the null hypothesis, indicating that there is a significant difference in alcohol content among wines rated 5, 6, and 7.
If the p-value is greater than 0.05, we fail to reject the null hypothesis, indicating no significant difference

## Evaluation Approach

Analytical validation using statistical patterns

Business interpretation of relationships

Cross-checking insights with domain understanding

## 6️⃣ Deployment & Recommendations
Insights can support process improvements and future analytics initiatives.

## Practical Applications

Improve production parameters using data insights

Reduce subjectivity in quality checks

Establish quality benchmarks for future automation

## Business Impact

Better decision-making through analytics

Improved consistency across wine batches

Foundation for advanced analytics initiatives

## 🧰Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Jupyter Notebook
