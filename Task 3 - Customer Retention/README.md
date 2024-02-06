# Customer Retention Analysis for PhoneNow Services - PwC Switzerland Power BI Case Study

## Background

### Overview
- **Introduction**
- **Data Collection**
- **Preparing the Data**
- **Building the Model**
- **Visualization of Data**
- **Insights and Analysis**
- **Interactive Dashboard**

### Challenge Overview
- **Issue:** After customers cancel their PhoneNow service contracts, the Customer Retention team seeks to better understand the characteristics and preferences of these customers to prevent future cancellations.
- **Goal:** Develop a comprehensive Power BI dashboard for the Customer Retention Manager to display crucial metrics and insights that:
  - Enable self-service exploration of customer data.
  - Identify and proactively engage at-risk customers.
  - Present detailed business metrics for strategic discussions.
  - Facilitate straightforward navigation and interaction.
  - Offer recommendations to enhance customer retention strategies.

### Data Collection
The analysis utilizes a dataset provided by PwC Switzerland, accessible here: [Churn Dataset](Link-to-Dataset)

### Preparing the Data
After importing into Microsoft Power BI Desktop, the dataset underwent transformation in Power Query.

#### Dataset Overview
The `Churn` dataset contains:
- **Format:** .xlsx
- **Size:** 772KB
- **Columns:** 23
- **Records:** 7043

Each field within the `Churn` dataset provides specific customer information, ranging from personal demographics to service subscriptions and usage.

#### Data Cleaning Steps
- Ensured correct data types across all columns.
- Filled 11 missing `TotalCharges` entries with corresponding `MonthlyCharges`, assuming these customers are newly subscribed.

#### Data Transformation
Transformed the dataset to enhance analytical clarity, including unpivoting certain columns and replacing values to normalize the data. Additionally, predictive analysis was performed using Python, detailed in a [Jupyter notebook](Link-to-Jupyter-Notebook).

### Building the Model
The cleaned and transformed dataset facilitated the creation of a relational model within Power BI:
- Established relationships between tables based on `customerId`.
- Implemented DAX measures for dynamic data analysis.

### Visualization of Data
Developed a Power BI dashboard comprising three primary sections and additional tooltips for detailed insights:
- **Customer Profile Overview**
- **Churn Analysis**
- **Predictive Model Performance**

#### Dashboard Characteristics
- **Type:** Tactical, designed for exploratory use by the Customer Retention Manager.
- **Key Metrics:** Includes customer demographics, churn rates, service subscription details, and predictive churn indicators.

#### Measures and Calculations
Incorporated calculated measures to dynamically reflect customer metrics, such as churn rate and demographics distributions.

### Insights and Analysis
The dashboard reveals critical factors influencing customer churn, including contract types, service satisfaction levels, and demographic trends. Key findings suggest areas for strategic improvement to enhance customer loyalty.

