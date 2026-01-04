## 1. Project Objective
•	The core purpose of this initiative was to engineer a suite of interactive Power BI business intelligence tools focused on two primary pillars: Credit Card Customer Profiles and Transactional Dynamics.

•	These dashboards serve as a strategic resource for stakeholders to decode complex demographic patterns, evaluate income-to-credit correlations, and monitor real time spending fluctuations.

•	Advanced interactivity was integrated through a series of global slicers including Gender, Age, and Card Category allowing users to pivot the data across different organizational needs.

________________________________________
## 2. Approach & Methodology
The development lifecycle was executed through a structured data to insight pipeline:

Phase 1: Data Engineering & Transformation
•	Executed the extraction of raw Customer and Transactional datasets into the Power BI ecosystem.

•	Leveraged Power Query to clean inconsistencies and standardize data types for reliable reporting.

•	Developed a robust DAX (Data Analysis Expressions) library to calculate high level business logic, including:

o	Dynamic Segmentation: Custom age brackets (e.g., 36-45, 46-55) and income tiers (High, Medium, Low).

o	Calculated KPIs: Total Revenue (45.52M), Revenue Growth (35%), and Average Utilization (0.27).

•	Established a "one to many" relationship model between customer IDs and transaction logs to ensure cross report filtering.

Phase 2: UI/UX Dashboard Design

•	Customer Analysis View: Prioritized demographic density, educational attainment, and credit limit benchmarking.

•	Transaction Analysis View: Focused on revenue velocity, preferred payment channels (Swipe, Chip, Online), and merchant category spending.

•	Implemented a cohesive visual identity using teal and slate palettes to ensure readability across all chart types.
________________________________________
## 3. Executive Insights

Customer Demographics & Profile

•	Age Dominance: The 46–55 age group represents the most significant customer volume with 4,171 individuals.

•	Gender Split: The portfolio is predominantly female-driven, accounting for 58% of the total customer base.
•	Income Limit Correlation: High-income earners command the highest credit availability, averaging a limit of 14.3K.

•	Top Profession: Business owners are the highest average earners, followed by white-collar professionals.

Transaction & Revenue Performance

•	Growth Momentum: The portfolio achieved a significant 35% growth rate, totaling 45.52M in revenue.

•	Top Spend Categories: Household "Bills" are the primary revenue driver, followed closely by "Entertainment" and "Fuel" expenses.

•	Tier Performance: The "Blue Card" remains the flagship product, generating the lion's share of transaction volume (38M).

•	Payment Trends: Traditional "Swipe" transactions lead the market at 66.94$, while "Online" transactions hold a solid 27.09% share.

________________________________________
## 4. Technical Challenges & Solutions

•	Complex Data Imputation: Addressed missing values in demographic fields through logical filtering to maintain the integrity of the total customer count (10.29K).

•	Time-Intelligence Modeling: Developed DAX measures to handle monthly revenue volatility, identifying key peaks in May (5.17M) and December (5.30M).

•	Visual Hierarchy: Optimized the layout of "Card" visuals to display five critical KPIs at a glance without cluttering the user interface.
________________________________________
## 5. Tools & Technologies

•	Analytical Engine: Power BI Desktop.

•	Data Processing: Power Query for ETL (Extract, Transform, Load).

•	Calculation Language: DAX for advanced measures and calculated columns.

•	Visual Library: Donut charts for gender/method splits, Gauge charts for utilization, and Line charts for revenue trends.

________________________________________
## 6. Strategic Conclusion
The project has successfully converted fragmented raw data into a cohesive visual narrative. By utilizing these dashboards, the business can now:

•	Pinpoint High-Value Segments: Target marketing efforts toward the 36–55 age demographic and business-owner segments.

•	Monitor Channel Shifts: Track the transition from physical swipe to online payment methods.

•	Optimize Credit Policy: Use the 0.27 utilization ratio to identify customers eligible for credit limit increases or tier upgrades.

