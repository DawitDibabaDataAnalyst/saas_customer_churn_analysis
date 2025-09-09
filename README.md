# saas_customer_churn_analysis
To build an interactive dashboard that models customer health, identifies users at risk of churning, and provides actionable insights to the Customer Success team to improve retention.

## Data Source
A sophisticated synthetic dataset was programmatically generated using Python's `Faker` and `NumPy` libraries to simulate real-world SaaS customer behavior over a 3-year period. The dataset includes:
- Customer demographics (signup date, region, subscription tier)
- Monthly behavioral metrics (login frequency, support tickets)
- Financial data (Monthly Recurring Revenue - MRR)
- Churn status indicator

## Tools Used
- **Python (Pandas, Faker, NumPy):** For generating a realistic synthetic dataset.
- **Power BI:** For data modeling, DAX measure creation, and building the interactive dashboard.
- **Power Query (M Language):** For data transformation and creating a date dimension table.

## Key Features of the Dashboard
- **Customer Health Scoring:** A calculated Churn Risk Score based on user activity.
- **RAG Status:** Customers are visually flagged (Red/Amber/Green) based on their risk level.
- **Trend Analysis:** Tracking of MRR and customer count over time.
- **Drill-through Capability:** Ability to click on a visual to see the underlying customers.

## How to Use
1. Use the filters on the right (Region, Subscription Tier) to focus on a specific segment.
2. The "Churn Analysis" page reveals correlations between low usage, high support tickets, and churn.
3. The "Customer Health" page provides a list view for the Customer Success team to prioritize outreach.
