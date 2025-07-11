Project Summary
This Power BI project analyzes a comprehensive retail marketing dataset containing customer profiles, transaction history, product purchases, churn probability, and recommendation insights over a 24-month period (Jan 2018 – Dec 2019). The report is structured using a star schema data model for optimized performance and clarity.

Dimension Tables

DimCustomer – Demographic & geographic details (name, age, city, gender, etc.)
Date_Master – Calendar table for time-based analysis (months, years)
DimProductCategory – Product groupings (e.g., MEN-JEANS, WOMAN-TOPS)
DimCampaignChannel – Marketing channel types (Email, SMS, Facebook, etc.)
DimChurnPrediction  - Recency, Churning Probability, Customer Rating.

Fact Tables

FactCustomerTransaction – Summary KPIs: total spend, units.
FactProductCategoryCount – Count of products purchased per category
FactDimRecommendations – Product recommendations with probability scores

Report Pages
Retail Sales Summary
MoM Sales Segment
Retail Product Summary
Product Segment
Top & Bottom Product
Churn

Tools & Technologies

Power BI Desktop
Power Query (M)
DAX Measures for KPIs and segmentation
Excel/CSV source files

