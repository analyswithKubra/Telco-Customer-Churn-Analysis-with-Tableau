# Telco Customer Churn Dashboard Report

**Created Date:** 12/02/2024  
**Company Name:** Telco Systems  
**Prepared By:** Kubra Dizlek  
**Dashboard Link:** [Telco Churn Dashboard](https://public.tableau.com/app/profile/kubra.dizlek/viz/TelcoChurnDashboard_17331624461710/Dashboard2)

*NOTE: If you want to see the interactive dashboard on the Tableau platform, please click the dashboard link. By using this link, you can see the whole dashboard and use filters. But if you want to have detailed insights and recommendations about each visualization, please keep scrolling.*

---


## Introduction

This dashboard was developed to analyze customer churn using a comprehensive dataset sourced from Kaggle. The dataset consisted of nine interconnected tables, covering various aspects of customer demographics, service usage, payment methods, and churn details.

To prepare the data for analysis, I utilized **Tableau Prep** to clean, transform, and integrate the data into a cohesive model. The resulting data model was then imported into **Tableau**, where I designed this interactive dashboard to uncover insights and trends driving customer churn.

Through detailed visualizations, this dashboard explores factors such as churn rates by category, geographical trends, payment methods, age groups, and contract types. The goal is to provide actionable insights that help businesses improve customer retention strategies and address specific churn drivers effectively.

This project demonstrates the power of Tableau as an end-to-end solution for data preparation, modeling, and visualization, enabling clear and actionable insights from complex datasets.

---
## Methodology

### Data Sources

We analyzed data from six key sources:
1. **CustomerChurn**: Customer demographics, subscription details, and churn status.
2. **Demographics**: Customer age, gender, marital status, and dependents.
3. **Location**: Geographical data such as state, city, and zip code.
4. **Population**: Population data by zip code.
5. **Services (Excel)**: Alternative format with service details.
6. **Status**: Churn scores, labels, and reasons.


### Data Preparation Steps
1. **Data Cleaning**: Removed duplicates, addressed missing values, and ensured consistency across all data sources.
2. **Data Integration**: Combined the six tables into a unified model using common identifiers like Customer ID.
3. **Feature Engineering**: Created new variables such as Age Groups, Churn Rates, and Tenure Categories to enhance analysis.
4. **Aggregation**: Grouped data by dimensions like age, state, and payment methods to identify trends and patterns.

---

## Insights and Recommendations

### 1. Churn by Category
**Insights:**  
- The largest contributor to customer churn is competition, accounting for 42.05% of the churn.  
- Other significant reasons include customer attitude (18.83%) and dissatisfaction with the service (16.21%).  
- Price and other factors contribute 12.20% and 10.70%, respectively.  

![Screenshot 2025-01-15 at 1 02 35 PM](https://github.com/user-attachments/assets/cf65c6c9-7ff6-4088-885e-fc5737f0a2e4)




**Recommendations:**  
- Introduce loyalty programs, discounts, or added-value services to retain customers and mitigate churn caused by competitors.  
- Conduct surveys to better understand customer attitudes and dissatisfaction to proactively address their concerns.

---

## 2. Churn by Reasons
### Insights
- The leading reason for customer churn is that competitors made better offers, accounting for 18.73% of churn cases.
- Poor attitude from support staff follows closely with 13.80%, highlighting a key service gap.
- Other significant reasons include better devices offered by competitors (9.84%) and better data options (7.12%).
- Reasons like high prices, poor product quality, and network reliability contribute smaller but notable shares.

![Screenshot 2025-01-15 at 1 07 33 PM](https://github.com/user-attachments/assets/4a3329d7-a0cd-460b-b2fb-5dd029d15c0c)


### Recommendations
**Improve Customer Retention Through Support and Offerings**
- Train customer support teams to enhance service quality and better address customer concerns.
- Regularly benchmark competitor offers to ensure competitive pricing, data options, and device upgrades.
- Highlight and promote unique service benefits that differentiate the company from competitors.

---
## 3. Churn Rate by States

### Insights
- The churn rate varies significantly across states, with Pennsylvania having the highest churn rate at 96%.
- States with large populations and high competition, such as California and Texas, also exhibit notable churn rates.
- Regions with lower churn rates may indicate stronger customer loyalty or less market competition.

![Screenshot 2025-01-15 at 1 10 47 PM](https://github.com/user-attachments/assets/9e493bfc-cf1a-47f7-be3c-55a307a080e3)


### Recommendations
**Target High-Churn States with Retention Strategies**
- Conduct deeper market research in Pennsylvania and other high-churn states to uncover specific local challenges or competitor influences.
- Introduce targeted offers or campaigns in high-churn states to retain customers.
- Leverage insights from low-churn regions to replicate successful retention strategies in higher-risk areas.

---


### 1. Churn by Category
**Insights:**  
- The largest contributor to customer churn is competition, accounting for 42.05% of the churn.  
- Other significant reasons include customer attitude (18.83%) and dissatisfaction with the service (16.21%).  
- Price and other factors contribute 12.20% and 10.70%, respectively.  

![Screenshot 2025-01-15 at 11 45 20 AM](https://github.com/user-attachments/assets/3ef77132-13b2-495b-847e-96d850a49b32)



**Recommendations:**  
- Introduce loyalty programs, discounts, or added-value services to retain customers and mitigate churn caused by competitors.  
- Conduct surveys to better understand customer attitudes and dissatisfaction to proactively address their concerns.

---

### 1. Churn by Category
**Insights:**  
- The largest contributor to customer churn is competition, accounting for 42.05% of the churn.  
- Other significant reasons include customer attitude (18.83%) and dissatisfaction with the service (16.21%).  
- Price and other factors contribute 12.20% and 10.70%, respectively.  

![Screenshot 2025-01-15 at 11 45 20 AM](https://github.com/user-attachments/assets/3ef77132-13b2-495b-847e-96d850a49b32)



**Recommendations:**  
- Introduce loyalty programs, discounts, or added-value services to retain customers and mitigate churn caused by competitors.  
- Conduct surveys to better understand customer attitudes and dissatisfaction to proactively address their concerns.

---



## Conclusion

This dashboard offers a clear view of what drives customer churn and highlights key areas for improvement. By analyzing age groups, locations, payment methods, and more, we’ve uncovered actionable insights to help reduce churn and improve customer satisfaction.

The findings show the importance of tailoring strategies for different customer segments, like addressing high churn among seniors and enhancing the Basic plan’s value. With interactive features, users can dive deeper into the data to understand customer behavior and identify opportunities to retain more customers.

This project shows how data and visualizations can help solve real business problems and improve decision-making for better results.
