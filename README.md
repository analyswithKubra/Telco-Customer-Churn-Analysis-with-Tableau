![download](https://github.com/user-attachments/assets/ba5f9a83-7c2f-4cad-aacb-2c9f3bc8c1c1)






# Telco Customer Churn Dashboard Report

**Created Date:** 12/02/2024  
**Company Name:** Telco Systems  
**Prepared By:** Kubra Dizlek  
**Tableau Dashboard Link:** [Telco Churn Dashboard](https://public.tableau.com/app/profile/kubra.dizlek/viz/TelcoChurnDashboard_17331624461710/Dashboard2)

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

### 2. Churn by Reasons
**Insights**
- The leading reason for customer churn is that competitors made better offers, accounting for 18.73% of churn cases.
- Poor attitude from support staff follows closely with 13.80%, highlighting a key service gap.
- Other significant reasons include better devices offered by competitors (9.84%) and better data options (7.12%).
- Reasons like high prices, poor product quality, and network reliability contribute smaller but notable shares.

![Screenshot 2025-01-15 at 1 07 33 PM](https://github.com/user-attachments/assets/4a3329d7-a0cd-460b-b2fb-5dd029d15c0c)


**Recommendations**

- Train customer support teams to enhance service quality and better address customer concerns.
- Regularly benchmark competitor offers to ensure competitive pricing, data options, and device upgrades.
- Highlight and promote unique service benefits that differentiate the company from competitors.

---
### 3. Churn Rate by States

**Insights**
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

### 4. Churn Rate by Contract Type Over Tenure

**Insights**
- Month-to-month contracts consistently show the highest churn rates, reaching up to 70% during some tenure months.
- Customers on one-year contracts display moderate churn rates, staying below 40% throughout the tenure.
- Two-year contracts have the lowest churn rates, rarely exceeding 15%, indicating stronger customer retention.
- Churn rates for all contract types fluctuate over time but remain significantly higher for month-to-month customers.



![Screenshot 2025-01-15 at 1 12 02 PM](https://github.com/user-attachments/assets/cfabe2e5-d6b6-4abe-a3cd-efa3cd97c85b)




### Recommendations
**Encourage Long-Term Contracts to Reduce Churn**
- Incentivize month-to-month customers to switch to one-year or two-year contracts by offering discounts or exclusive benefits.
- Promote the value and savings of long-term contracts through targeted marketing campaigns.
- Identify key tenure periods where churn rates spike and implement retention strategies, such as personalized offers or proactive customer engagement.

---

### 5. Churn Rate by Payment Method

**Insights**
- Customers using Electronic Check as their payment method show the highest churn rate at 44.25%.
- Mailed Check, Bank Transfer (Automatic), and Credit Card (Automatic) have relatively lower churn rates, at 18.83%, 18.78%, and 18.14%, respectively.

![Screenshot 2025-01-15 at 1 12 23 PM](https://github.com/user-attachments/assets/63e091a2-cb13-446c-9141-de0bc76e6c8c)


### Recommendations
**Address Churn Among Electronic Check Users**
- Investigate why customers using Electronic Check have significantly higher churn rates—this could include issues like perceived complexity or dissatisfaction with the method.
- Promote automatic payment methods, such as Bank Transfer or Credit Card, by emphasizing their convenience and reliability.
- Offer incentives, such as discounts or rewards, for customers who switch to automatic payment methods.

---
### 6. Churn Rate vs Offer Type

**Insights**
- Customers on the Basic offer show the highest churn rate, with more than 50% of churners belonging to this category.
- The Premium, Offer D, and Offer B plans exhibit moderate churn rates, each around 25%–30%.
- Offer C and Offer A have the lowest churn rates, indicating better customer retention.

![Screenshot 2025-01-15 at 1 18 13 PM](https://github.com/user-attachments/assets/d2b63340-1492-4210-b7bf-9f90b77be48d)


### Recommendations
**Reevaluate the Basic Offer to Reduce Churn**
- Assess the features and pricing of the Basic offer to identify areas for improvement or additional value.
- Consider introducing incentives or loyalty benefits for customers on the Basic plan to encourage retention.
- Promote lower-churn offers like Offer C and Offer A to attract new customers and reduce churn rates.

---
### 7. Churn Rate by Age Groups

**Insights**
- Customers aged 16–20 have the lowest total count but relatively high churn rates, indicating retention challenges among younger customers.
- The churn rate stabilizes for age groups 21–25, 26–30, and 31–35, with consistent total customer counts and churn rates ranging between 20–30%.
- For age groups 61–65 and 66–70, churn rates spike significantly, reaching 40%, even though total customer counts are lower.

![Screenshot 2025-01-15 at 1 19 12 PM](https://github.com/user-attachments/assets/4617b6a2-868c-478f-969e-1f6ddf2d9f47)


### Recommendations
**Tailor Retention Strategies by Age Group**
- For younger customers (16–20): Introduce loyalty programs, discounts, or gamified experiences to enhance engagement.
- For older customers (61–65 and 66–70): Address churn factors through personalized support, simplified processes, or targeted promotions to encourage retention.
- Maintain consistent customer experience and value offerings for middle age groups (21–25, 26–30, 31–35) to keep churn rates stable.

---


## Conclusion

This dashboard offers a clear view of what drives customer churn and highlights key areas for improvement. By analyzing age groups, locations, payment methods, and more, we’ve uncovered actionable insights to help reduce churn and improve customer satisfaction.

The findings show the importance of tailoring strategies for different customer segments, like addressing high churn among seniors and enhancing the Basic plan’s value. With interactive features, users can dive deeper into the data to understand customer behavior and identify opportunities to retain more customers.

This project shows how data and visualizations can help solve real business problems and improve decision-making for better results.

### Files and Folders

- [collaboration.md](#collaboration)
  Please click if you want to collaborate with me. This file outlines how you can contribute and includes my contact information.

- [fqa.md](#fqa)
  Frequently asked questions about the project.

- [license.md](#license)
  Includes the license details for this project.

- [Telco Churn Dashboard.twbx](#tableau-workbook)
  Tableau workbook containing all visualizations and dashboards.

- [dataset/](#dataset-folder)
  Download the dataset used for the analysis. This folder contains all the raw and cleaned data files.

- [Image/](#images-folder)
  Stores visual assets or exported charts related to the analysis.

Feel free to click on any file to learn more about the project components. For questions or collaboration, check out [collaboration.md](#collaboration) or reach out to me directly!

