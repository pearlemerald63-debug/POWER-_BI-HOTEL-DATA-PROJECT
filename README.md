# POWER-_BI-HOTEL-DATA-PROJECT

Interact with the final dashboard here:
Hotel data source: [Hotel data Folder](https://drive.google.com/drive/u/0/folders/1Hai-blNDz-knkoPCNGmf5h3ndN_JhKuH)

# Business Problem-

The hospitality industry faces high cancellation rates, seasonal demand fluctuations, revenue instabilityacross channels, and limited visibility into repeat guest behavior. This project provides data-driven insights to improve forecasting, pricing, retention and develop a comprehensive strategy to enhance customer satisfaction and optimize revenue.

# Dataset information

The dataset encompasses various aspects of hotel bookings, ranging from booking details to guest demographics. Each entry contains essential information like the Average Daily Rate (ADR), number of guests, booking agency, arrival details, room assignments, and more. Understanding and harnessing this data will allow us to uncover patterns, identify opportunities, and make informed decisions. For further details on the data table specification, consult the data dictionary document.

The successful execution of this project will empower the hotel management to make informed decisions, leading to substantial improvements in revenue optimization and guest satisfaction. This not only transforms traditional hotel management methods but also underscores the significance of a proactive, data-driven approach in addressing the evolving challenges of the hospitality industry.

Data Source: [Hotel_booking data](https://docs.google.com/spreadsheets/d/1z3xWzsY8ivHaJXFrrdWejgSS0VkThJ_p/edit?gid=60889679#gid=60889679)

# Project Overview

This project presents a comprehensive Power BI analysis of hotel booking data from 2018–2020. The objective was to transform raw booking data into a structured, analysis-ready dataset and develop an interactive dashboard to support:

- 📈 Revenue Optimization
- ⚠️ Cancellation Risk Management-
- 💰 Dynamic Pricing Strategy
- ⭐ Customer Retention & Loyalty

The project follows a complete Power BI workflow:
Data Sourcing → Data Transformation → Data Modeling → Data Analysis → Business Insights

# Understand Business Objectives and User Requirements
We tried to understand the specific requirements and objectives from the business problem. We identified key areas we want to focus on and the questions the business needs answers to.

# Define Business Questions and Metrics

Based on the discussions in Step 1, we defined specific business questions that the dashboard should answer. Example questions include:

- What factors contribute most to booking cancellations?
- How does booking lead time affect Average Daily Rate (ADR)?
- How does distribution channel impact cancellation rates and revenue?
- What is the relationship between previous cancellations and future cancellation likelihood?
- What are the seasonal trends in bookings across months and years?
- Do special requests influence repeat stays and guest loyalty?

# Define the metrics and Key Performance Indicators (KPIs) that will help answer the business questions.

Example metrics include:

- Total Bookings
- Cancelled Bookings
- Cancellation Rate
- Total Revenue
- Average Daily Rate (ADR)
- Total special request booking
- Booking Volume

# Data transformation and cleaning

The dataset was cleaned by removing duplicates, correcting any inconsistencies, and ensuring the data is in a suitable format for analysis and visualization. Concatenated the reports for all three years for better analysis. Annual datasets were appended and cleaned in Power Query. Steps included error removal, data type corrections, NULL handling, date consolidation, and external country data integration. Time intelligence fields (Year, Month, Week) were created for analysis

<img width="602" height="779" alt="image" src="https://github.com/user-attachments/assets/5752f488-51ae-46e6-bc39-612e06d39e73" />

#  Dataset after cleaning
<img width="1641" height="822" alt="image" src="https://github.com/user-attachments/assets/d1fe1828-b8ce-4d6e-a0e8-25021e92b19b" />

# Data modelling and relationships.
Dimensions with which to break down the analysis were identified. Hence, new tables for identified dimensions were created. These included:

- Date Dim
- Location Dim
- Hotel Dim
- Additional features were created to give more robustness to our analysis
  
The data model was designed using the Star Schema where the different dimensions were connected to the Facts table in a one-to-many relationship.
<img width="1162" height="754" alt="image" src="https://github.com/user-attachments/assets/9dee1ecf-fb40-4615-aba1-2c74c81309a3" />

# Data analysis and Visualization
Appropriate chart types (e.g., bar charts, line charts, pie charts) were used to represent the metrics and insights. Interactive features such as filters, drill-down options, and tooltips were used for detailed information.
<img width="1274" height="710" alt="image" src="https://github.com/user-attachments/assets/b1279900-a59a-4a2b-a497-cb61c1ed2e58" />
<img width="1406" height="788" alt="image" src="https://github.com/user-attachments/assets/68236743-9ff5-4a6a-bfd6-965cfe1c485b" />

# Insights
- Customers with prior cancellations exhibit higher future cancellation probability.
- Online travel agencies generate higher booking volume but also higher cancellation rates.
- Short lead-time bookings tend to have higher ADR, reflecting demand-based pricing.
- Booking patterns demonstrate strong seasonality across months and years.
- Guests who submit more special requests show stronger repeat behavior, indicating personalization influences loyalty.

# Recommendations
- Implement risk-based deposit policies for high-risk segments
- Encourage direct bookings to improve revenue stability
- Apply dynamic pricing strategies aligned with seasonality
- Develop customer reliability scoring models
- Enhance personalization to strengthen guest retention

# 👩🏽‍💻 About the Author
Favour
Aspiring Data Analyst | Business Analytics | Revenue Optimization
