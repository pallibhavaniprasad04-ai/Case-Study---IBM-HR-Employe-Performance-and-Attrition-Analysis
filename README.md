# Case-Study---IBM-HR-Employe-Performance-and-Attrition-Analysis

📘 **Project Overview**

*This project explores employee attrition patterns using the IBM HR Analytics Employee Attrition Dataset.
The goal is to uncover why employees leave the organization and identify actionable insights to help HR improve retention.

#Rather than focusing on machine learning, the project emphasize:
#Data cleaning
#Exploratory Data Analysis (EDA)
#Visualization-driven insights**

🛠️ **Tech Stack & Libraries**
The following libraries are used in this project:

1.pandas → For data loading, cleaning, and manipulation

2.numpy → For numerical operations and summary statistics

3.matplotlib & seaborn → For data visualization (histograms, scatter plots, bar charts, heatmaps, etc.)

🧩 **Project Tasks**
🧹 1️⃣ Data Understanding & Cleaning

Loaded dataset and inspected structure

Removed unnecessary columns (EmployeeCount, Over18, StandardHours, etc.)

Checked for duplicates and missing values

Treated outliers in MonthlyIncome, YearsAtCompany, TotalWorkingYears

📊 2️⃣ Exploratory Data Analysis (EDA)

Univariate Analysis: Distribution of Age, MonthlyIncome, JobSatisfaction

Bivariate Analysis: Attrition vs JobRole, Department, OverTime, Salary

Multivariate Analysis: Combined influence of JobRole, Income & Satisfaction

📈 3️⃣ Visualization & Insight Generation

Created countplots, boxplots, and violinplots using Seaborn

Compared attrition patterns visually for HR decision-making

🔍 Key Questions
Question	Description
👥 What’s the average employee age?	Find workforce demographics
💼 Which job roles have the highest attrition?	Identify high-risk roles
💰 Does low income lead to higher attrition?	Analyze salary impact
⏱️ Does overtime increase attrition?	Check work pressure link
😀 Does job satisfaction reduce attrition?	Evaluate employee happiness
💡 Key Insights
Insight	Observation
OverTime Effect	Employees with OverTime = Yes have 4× higher attrition.
Salary Factor	Low-income employees are more likely to quit.
Age Group	Employees aged <30 years show highest attrition.
Department	Sales and Research roles have higher turnover.
Job Satisfaction	High satisfaction reduces attrition risk significantly.
