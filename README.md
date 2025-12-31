# Strategic Analysis of Credit Card Transaction

# Executive Summary
This project showcases a dual-dashboard analytical solution designed to decode the complexities of credit card usage and customer demographics. By integrating disparate datasets, the study transforms raw financial records into a narrative that highlights revenue drivers, risk profiles, and market segmentation.

# 💡 Key Business Insights
Customer Demographics & Behavior
The Power Person: The core user base resides in the 36–55 age bracket, with women (58%) representing the majority of the portfolio.

Income & Credit: There is a direct correlation between professional status and credit accessibility; White-collar and Business professionals lead in earnings, which translates to high-income groups securing credit limits averaging 14K.

Tier Dominance: The "Blue" Card remains the foundational product, capturing the highest volume of users across all education levels.

Transactional Trends & Revenue Drivers
The Revenue Engine: The portfolio generated 45.52M in total revenue, bolstered by a significant 35.04% Week-over-Week growth rate.

Spending Velocity: Despite high female participation, male customers drive slightly higher total revenue, whereas female users exhibit higher efficiency in revenue-per-transaction.

Category Leaders: Consumer spending is heavily concentrated in essential bills, fuel, and entertainment, with Online transactions now accounting for over a quarter of all activity.

# 🛠 Technical Framework
The Data Ecosystem
The analysis was built upon two primary data streams:

Consumer Profiles: Comprehensive data on credit scores, job types, education, and card tiers.

Financial Activity: Granular transaction logs including date-stamped spending, transaction methods (Swipe/Chip/Online), and categorized expenses.

# Engineering & Modeling
To ensure the data was "analysis-ready," I utilized Power Query for rigorous cleaning and established a Star Schema by linking tables via a unique Customer_ID primary key.

Advanced DAX (Data Analysis Expressions) were used to engineer custom metrics:

Temporal Metrics: WoW Growth %, Week Number, and Revenue comparisons.

Segmentation Logic: Dynamic grouping for Age Brackets and Income Tiers.

Performance Indicators: Total Revenue, Credit Usage Ratios, and Transaction Counts.

# 📊 Dashboard Architecture
1. Customer Intelligence Hub
Goal: To profile the "who" behind the spending.

Visual Focus: Distribution of cardholders by gender and education; average income vs. job type; and credit limit benchmarking.

Interactive Slicers: Allows stakeholders to filter the entire view by card category or specific age groups to identify niche market opportunities.

2. Revenue & Transaction Dynamics
Goal: To monitor the "how" and "when" of financial flow.

Visual Focus: Monthly revenue trajectories; transaction splits by Card Category (Blue vs. Gold/Platinum); and a breakdown of payment methods.

Revenue Matrix: A summary table cross-referencing Gender and Age to pinpoint the most profitable segments at a glance.

# 🚀 Conclusion & Professional Growth
This project served as a comprehensive exercise in Data Storytelling. Beyond the technical execution of building a clean, interactive UI, it deepened my ability to:

Convert raw financial numbers into actionable business strategy.

Master complex DAX calculations for time-intelligence reporting.

Design user-centric layouts that prioritize the most critical KPIs for stakeholders.
