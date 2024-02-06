# Diversity & Inclusion Analysis - PwC Virtual Case Experience

## Overview

- **Problem Statement**
- **Data Sourcing**
- **Data Preparation**
- **Data Modeling**
- **Data Visualization**
- **Analysis and Insights**
- **Shareable Link**

### Problem Statement

**Issue:** The Human Resources department at our telecom client is committed to diversity and inclusion, focusing on improving gender balance at the executive management level, but progress has been slow.

**Objective:**
- Establish clear KPIs for hiring, promotion, performance, and turnover.
- Develop a visualization dashboard for HR managers showcasing all relevant Key Performance Indicators (KPIs) and metrics.
- Identify potential reasons for the slow progress in achieving gender balance at the executive management level.
- Ensure the dashboard is user-friendly with minimal interaction required.

### Data Sourcing

The analysis is based on a dataset provided by PwC Switzerland. 

### Data Preparation

The dataset was processed in Microsoft Power BI Desktop, starting with a transformation in Power Query.

**Metadata Overview:**
- **Dataset:** Diversity & Inclusion
- **Format:** .xlsx
- **Size:** 176 KB
- **Fields:** 32
- **Records:** 500

**Column Details:**
- **Employee ID:** Unique identifier for each employee.
- **Gender:** Employee's gender.
- **Job Level after FY20 Promotions:** Job level post FY20 promotion.
- **New Hire FY20?:** Indicates if the employee was hired in FY20.
- **FY20 Performance Rating:** Employee's performance rating for FY20.
- ... _[Additional column details as needed]_

**Data Cleaning:**
- Removed unnecessary columns and filtered out irrelevant rows.
- Verified the correct data type for each column.

**Data Transformation:**
- Applied text extraction for clarity in columns related to job level promotions.

### Data Modeling

The cleaned and transformed dataset was ready for modeling with a focus on organizing DAX measures for clarity.

### Data Visualization

The Power BI dashboard includes:
- **HR Overview**
- **Performance Analysis**
- **Hiring & Promotion Trends**

**Dashboard Characteristics:**
- **Type:** Operational, designed for exploratory use by HR Managers and Analysts.
- **Key Metrics:** Employee counts, leaver statistics, promotion and hiring rates, average performance, and demographic distributions.

### Analysis and Insights

Key observations suggest:
- Promoted employees within two years had lower performance ratings, while leavers showed higher ratings.
- A notable gender disparity exists in executive hires and promotions despite superior performance from female directors.
- Stagnation in job levels for over two years is common, particularly for female directors aiming for executive roles.
- Performance evaluations for management promotions may lack objectivity, potentially disadvantaging qualified female candidates.
