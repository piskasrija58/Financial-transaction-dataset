Financial Transaction Dashboard – Power BI Project
📌 Project Overview
This project presents an interactive Financial Transaction Dashboard built using Microsoft Power BI.
The dashboard analyzes financial transaction data to provide insights into customer behavior, card usage, spending patterns, credit limits, and potential fraud indicators.
The main objective of this project is to transform raw transaction data into meaningful business insights using data visualization techniques.
🎯 Project Objectives
Analyze total transactions and transaction amounts
Monitor credit limit utilization over time
Identify high-value customers
Track card usage patterns (chip-enabled, card type, brand)
Detect cards exposed on the dark web
Analyze spending by state, merchant, and category (MCC)
Monitor monthly and yearly transaction trends
📂 Dataset Description
The project uses three main datasets:
1️⃣ Cards Data
Columns:
id
client_id
card_brand
card_type
card_number
expires
cvv
has_chip
num_cards_issued
credit_limit
acct_open_date
year_pin_last_changed
card_on_dark_web
2️⃣ Transaction Data
Columns:
id
date
client_id
card_id
amount
merchant_id
merchant_city
merchant_state
zip
mcc
3️⃣ Customer Data (if used)
Columns may include:
current_age
retirement_age
gender
per_capita_income
total_debt
credit_score
📊 Dashboard Features & Visualizations
The dashboard includes:
📈 Line Chart – Monthly Transaction Trend
📊 Bar Chart – Transactions by State
💳 Card Type Distribution
📋 Table – Dark Web Exposed Cards
📌 KPI Cards –
Total Transactions
Total Transaction Amount
Average Transaction Value
Total Credit Limit
🔍 Key Insights Generated
Spending trends across different months and years
Customers with high credit utilization
States with the highest transaction volume
Card types most frequently used
Detection of potentially risky cards (dark web exposure)
Correlation between credit score and transaction behavior
🛠 Tools & Technologies Used
Microsoft Power BI Desktop
Data Modeling & Relationships
DAX (Data Analysis Expressions)
Power Query (Data Transformation)
📈 Business Impact
This dashboard helps:
Financial institutions monitor customer spending patterns
Identify fraud risks and suspicious card activities
Improve credit risk management
Make data-driven business decisions
🚀 How to Use
Open the .pbix file in Power BI Desktop.
Refresh the dataset if required.
Use slicers (Date, State, Card Type, etc.) to filter the data.
Explore different visualizations for insights.
📌 Future Enhancements
Add predictive analytics for fraud detection
Implement real-time data integration
Add customer segmentation using clustering
Create mobile-optimized dashboard view
