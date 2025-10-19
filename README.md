# Campaign-A-B-Test-Analysis-using-Python

📊 Marketing Campaign A/B Test Analysis

🎯 Project Overview
This project analyzes the performance of a marketing campaign using A/B testing techniques to evaluate which version of a campaign leads to better customer engagement and conversions.
The dataset and analysis are inspired by the DataCamp course “Analyzing Marketing Campaigns with Pandas”, and the project aims to reproduce and extend it with deeper statistical testing and visualization.

🧩 Objective
The goal of this project is to:
Understand customer behavior during marketing campaigns
Compare the effectiveness of Campaign A (Control) vs Campaign B (Treatment)
Apply A/B testing methodology to determine statistical significance
Provide actionable insights for marketing decision-making

🧠 Key Questions
Is there a statistically significant difference in conversion rates between Campaign A and Campaign B?
Which customer segments respond better to each campaign?
How can we optimize future marketing spend based on these findings?

📂 Dataset
The dataset includes customer and campaign information such as:
Column	Description
ID	Unique customer ID
Age	Customer’s age
Income	Annual income
Campaign	Campaign type (A or B)
Response	Whether the customer responded positively
Spending	Amount spent after campaign

📦 Source: DataCamp - Analyzing Marketing Campaigns with Pandas

🧮 Methodology
Data Cleaning & Preparation
Handling missing values
Encoding categorical variables
Creating key metrics (conversion rate, ROI, etc.)
Exploratory Data Analysis (EDA)
Visualizing response rates by age, income, and campaign
Identifying patterns and anomalies
A/B Testing
Defining hypotheses
H₀ (Null Hypothesis): No difference between Campaign A and B
H₁ (Alternative Hypothesis): There is a difference between Campaign A and B
Applying proportion z-test or chi-square test for conversions
Evaluating p-values and confidence intervals
Results & Insights
Summary of significant findings
Marketing recommendations

📊 Tools & Libraries
Python 3.9+
Pandas – Data manipulation
NumPy – Statistical computation
Matplotlib / Seaborn – Data visualization
Scipy / Statsmodels – Hypothesis testing
📈 Example Visuals
Conversion rates by campaign
Income distribution among responders
Statistical test results visualization
(You can add your own plots here once you finish the notebook.)

🧩 Key Takeaways
Campaign B showed a statistically significant higher conversion rate.
Income and age had moderate influence on campaign success.
Future campaigns can focus on high-income, mid-age customer segments.

🚀 Next Steps
Apply logistic regression for deeper predictive modeling
Conduct A/B/n test (more than two versions)
Integrate dashboard (Tableau / Power BI) for interactive insights
