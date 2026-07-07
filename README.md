# BANK MARKETING CAMPAIGN ANALYSIS

## Project Overview

This project analyzes a bank marketing campaign dataset to identify the key factors influencing customer subscription to term deposits. The analysis combines SQL, Python, and Power BI to transform raw customer data into actionable business insights and recommendations.

The primary objective is to understand customer behavior, evaluate campaign effectiveness, and identify high-conversion customer segments that can improve future marketing performance and return on investment (ROI).

## Business Objective

The bank aims to improve the effectiveness of its direct marketing campaigns by identifying:

Customer segments with the highest Subscription Rates

Campaign characteristics that drive conversions
The impact of previous marketing efforts
Economic factors influencing customer decisions
Opportunities to optimize marketing resources and improve ROI

## Dataset Information

Dataset: Bank Marketing Dataset

             DATASET IS HIGHLY IMBALANCED

#### Target Variable:

y – Indicates whether the customer subscribed to a term deposit (Yes/No)

#### Key Features:

*Customer demographics (Age, Job, Marital Status, Education)
*Financial information (Housing Loan, Personal Loan)
*Campaign information (Contact Method, Duration, Campaign Calls)
*Previous campaign outcomes
*Economic indicators

## Tools & Technologies
#### Python
Pandas,
NumPy,
Matplotlib,
Seaborn,

#### SQL Server
Data extraction,
Aggregation,
Business KPI analysis

#### Power BI
Interactive dashboards,
KPI visualization,
Business reporting

#### Microsoft Excel
Initial data review

## Project Workflow
#### 1. Data Cleaning & Preparation
##### Removed duplicates -- There were 12 duplicate rows
<img width="222" height="60" alt="Image" src="https://github.com/user-attachments/assets/568c4d3f-e02d-482b-a553-649cb8192f4c" />

##### Handled missing and unknown values -- No missing values but unknown in categories were present
<img width="347" height="50" alt="Image" src="https://github.com/user-attachments/assets/229cd596-ffe5-4444-9b1b-b7c4e736ddf5" />

##### Standardized column names 
##### Created derived features
##### Categorized customer age groups -- Feature engineering for better understanding
<img width="375" height="96" alt="Image" src="https://github.com/user-attachments/assets/8d69f65b-d048-49b0-b43b-383198e4d900" />

##### Improved data consistency for analysis
#### 2. Exploratory Data Analysis (EDA)
##### Customer demographic analysis
##### Subscription behavior analysis
##### Campaign performance evaluation
##### Loan and financial profile assessment
Economic indicator analysis
#### 3. SQL Analysis

##### Key business questions answered:

##### 1.) What is the overall subscription rate?
<img width="287" height="38" alt="Image" src="https://github.com/user-attachments/assets/c0269b7a-b84e-4ae0-be80-ebc5a2829347" />

##### 2.) Which month generated the highest subscriptions?
<img width="348" height="180" alt="Image" src="https://github.com/user-attachments/assets/2adedccd-02b5-43c0-8a47-f46ef3b5387c" />

##### 3.) Which contact method achieved the highest conversion rate?
<img width="206" height="35" alt="Image" src="https://github.com/user-attachments/assets/efdbf487-c3c4-4817-8ad9-8fb131456173" />

##### 4.) Which customer segments performed best?
<img width="356" height="174" alt="Image" src="https://github.com/user-attachments/assets/f022dc6e-3614-4138-868a-65f81f346d1d" />

##### 5.)How does previous campaign outcome affect conversion?
<img width="112" height="231" alt="Image" src="https://github.com/user-attachments/assets/e173fc0a-fa3f-4ec3-9f99-c543578c5c8d" />

##### 6.) What percentage of customers have housing or personal loans?
<img width="206" height="36" alt="Image" src="https://github.com/user-attachments/assets/1f21d6ca-c1a1-4cdb-8aae-fbe6bdcd528b" />

<img width="187" height="71" alt="Image" src="https://github.com/user-attachments/assets/eaf76c7a-5dd5-4f16-ac89-178b05bbdcea" />


#### 4. Power BI Dashboard

##### Dashboard pages include:
##### Executive Overview
##### Customer Segmentation Analysis
##### Campaign Performance Analysis
##### Economic Factors & Business Insights

## Key Findings
##### -Call duration emerged as the strongest factor associated with successful subscriptions.
##### -Customer engagement plays a significant role in campaign success.
##### - Middle-aged and adult customers represent the most stable and valuable customer segments.
##### - Cellular contact methods outperform traditional telephone outreach.
##### - Customers with positive previous campaign outcomes show higher conversion rates.
##### - Repeated campaign contacts provide diminishing returns after a certain point.

## Business Recommendations
##### - Prioritize high-engagement customer segments.
##### - Increase focus on customers with a history of successful campaign responses.
##### - Use cellular communication channels where possible.
##### - Reduce excessive campaign contacts to improve efficiency.
##### - Focus marketing resources on high-conversion customer profiles.
##### - Implement data-driven targeting strategies to maximize ROI.

## Dashboard Preview

Executive Overview

<img width="767" height="428" alt="Image" src="https://github.com/user-attachments/assets/c19ae56c-4cea-4ea2-bc03-c579aa421870" />

Customer Segmentation

<img width="695" height="395" alt="Image" src="https://github.com/user-attachments/assets/5893e25e-db33-4abf-b193-317f3160127e" />

Campaign Performance

<img width="695" height="392" alt="Image" src="https://github.com/user-attachments/assets/c96507a5-8027-4b45-83f9-16518a2f2d6d" />

Business Insights

<img width="690" height="378" alt="Image" src="https://github.com/user-attachments/assets/6259ec26-126b-42d2-b9d5-9af33034391a" />

## Project Outcome

This project demonstrates an end-to-end data analytics workflow, including data cleaning, exploratory analysis, SQL-based business intelligence, dashboard development, and strategic recommendation generation. The insights generated can help financial institutions improve campaign effectiveness, optimize marketing spending, and enhance customer targeting strategies.

## Author
#### Simranjit Kaur
Aspiring Data Analyst | SQL | Python | Power BI | Data Visualization

LinkedIn:[Simranjit Kaur](https://www.linkedin.com/in/simranjit-kaur-5167823a8/)

E-Mail: simranjk.677@gmail.com
