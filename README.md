# 📝 Project Overview

Customer retention is critical in the banking sector. Acquiring new customers costs significantly more than retaining existing ones.
This project analyzes customer churn patterns to help banks identify at-risk segments and design strategies for improving retention.

The analysis was conducted using Python (Google Colab) for data cleaning & exploratory data analysis (EDA) and Power BI for building an interactive dashboard.

# ❓ Problem Statement

### What is the problem?
High customer churn increases acquisition costs and reduces profitability.

### Why does it matter?
Retaining loyal customers is cheaper and provides sustainable revenue growth.

### How to solve it?
By analyzing customer attributes (age, tenure, geography, membership, card type, activity level, etc.) to find churn patterns and provide actionable recommendations.

# 🔄 Data Analysis Lifecycle

Data Gathering → Banking customer dataset

Data Cleaning → Removed duplicates, handled missing values, reformatted variables

Exploratory Data Analysis (EDA) → Analyzed churn across demographic, geographic, and financial attributes

Calculations → Churn rate, tenure-based churn, churn by card/membership types

Insights → Identified high-risk segments and churn drivers

Recommendations → Retention strategies for different customer groups

# 📊 Dashboard Highlights

The Power BI dashboard includes:

KPI Cards: Total Customers, Churned Customers, Churn Rate, Active Members, Average Tenure, Average Age

Demographics:
- Churn by Age Group
- Churn by Gender

Geography:
- Churn by Country/Region

Customer Behavior:
- Churn by Tenure
- Churn by Active Member Status
- Churn by Balance & Products
- Churn by Card Type

📸 Dashboard Preview

<img width="1277" height="722" alt="customer churn dash1" src="https://github.com/user-attachments/assets/71e70966-c198-4fc6-b084-da53caec0675" />
<img width="1285" height="722" alt="customer churn dash2" src="https://github.com/user-attachments/assets/96f43771-34eb-459b-a577-d9d62db1c231" />


# 📈 Key Insights

Age & Churn: Middle-aged customers (35–54) have the highest churn.

Geography: Germany and France show higher churn compared to Spain.

Tenure: Customers with shorter tenure (<3 years) are more likely to leave.

Activity: Non-active members churn significantly more.

Card Types: Churn is distributed across all card types, but Platinum & Silver holders show higher proportions.

Balance & Products: Customers with fewer products and lower engagement churn more often.

# ✅ Recommendations

Strengthen early engagement for customers with <3 years tenure.

Target loyalty campaigns in high-churn regions (Germany, France).

Improve activity programs to reduce churn among inactive members.

Personalize offerings based on age groups and card type usage.

Cross-sell financial products to increase customer stickiness.

# 🛠️ Tools & Technologies

Google Colab (Python) → Pandas, Matplotlib, Seaborn

Power BI → Dashboarding & storytelling

Dataset → Banking customer churn data
