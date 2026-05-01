# Swiggy Sales Analytics: Consumer & Revenue Insights

## Executive Summary
This project provides a data-driven deep dive into Swiggy’s sales ecosystem, analyzing over **197,000 orders** to optimize operational efficiency and revenue growth. By transforming raw transactional data into actionable intelligence, this analysis identifies key performance drivers across different regions, food categories, and timeframes. The final output includes an interactive dashboard that monitors essential KPIs like Total Sales (₹53M+), Average Order Value, and Customer Satisfaction.

---

## Business Problem
Swiggy operates in a high-volume, low-margin environment where understanding micro-trends is vital for maintaining a competitive edge. The core challenge addressed in this project is the need to visualize complex data to answer critical business questions regarding revenue leakage, regional performance, and product mix.

### Scenarios
*   **The Weekend Surge:** Identifying if logistical capacity needs to be increased based on "Weekly Trend Analysis."
*   **The Rating Gap:** Correlating "Ratings Count" with "Total Sales" to see if high-volume restaurants are maintaining quality.

### Business Requirement Documents (BRD)
The following requirements guided the development of this project:

#### 1. KPI Requirements
Referenced from **Screenshot 2026-04-27 at 10.34.33 AM.jpg**:
*   **Total Sales (₹):** Overall revenue generated from food orders.[cite: 1]
*   **Average Rating:** Customer satisfaction level across all restaurants.[cite: 1]
*   **Average Order Value (₹):** Revenue per order.[cite: 1]
*   **Ratings Count:** Total number of customer reviews.[cite: 1]
*   **Total Orders:** Number of food orders received.[cite: 1]

#### 2. Chart Requirements
Referenced from **Screenshot 2026-04-27 at 10.52.42 AM.jpg**:
*   **Monthly Sales Trend:** Shows how total sales fluctuate month by month.
*   **Daily Sales Trend:** Highlights order and revenue variations across days of the week.
*   **Total Sales by Food Type (Veg vs Non-Veg):** Compares revenue contribution by cuisine type.
*   **Total Sales by State (Map Visualization):** Displays state-wise revenue distribution.
*   **Quarterly Performance Summary:** Combines Sales, Ratings, and Orders by Quarter.
*   **Top 5 Cities by Sales:** Identifies leading cities contributing the most revenue.
*   **Weekly Trend Analysis:** Monitors weekly fluctuations in sales to identify consistency or peak periods.

---

## Methodology
The project followed a structured Data Analytics Life Cycle:
1.  **Requirement Gathering:** Defined Key Performance Indicators (KPIs) and required visualizations based on the BRD.
2.  **Data Extraction & Cleaning:** Handled a dataset of 197k+ rows, ensuring data consistency and handling missing values.
3.  **Exploratory Data Analysis (EDA):** Performed statistical summaries to understand the distribution of prices and ratings.
4.  **Feature Engineering:** Derived time-based features (Month, Day of Week, Quarter) to enable trend analysis.
5.  **Data Visualization:** Developed interactive charts to represent state-wise distribution and sales fluctuations.

---

## Skills & Tools
*   **Data Manipulation:** Python (Pandas, NumPy)
*   **Data Visualization:** Plotly Express, Seaborn, Matplotlib
*   **Geospatial Analysis:** Map visualizations for State-wise sales distribution
*   **Business Intelligence:** KPI development, Trend Analysis, Quarterly Performance Summaries
*   **Documentation:** Markdown, GitHub Version Control

---

## Results & Business Recommendations

### Key Findings
*   **Total Sales:** Generated ₹53.01M in revenue with an **Average Order Value (AOV) of ₹268.51**.
*   **Top Performers:** Identified the "Top 5 Cities" that contribute disproportionately to the total revenue.
*   **Customer Sentiment:** Maintained a strong average rating of 4.34 across the platform.

### Recommendations
*   **Targeted Promotions:** Increase marketing spend in states identified in the "Map Visualization" with high order counts but low AOV.
*   **Category Optimization:** Use the "Veg vs Non-Veg" revenue split to curate specialized "Food Type" festivals or discount periods.
*   **Retention Strategy:** Focus on restaurants with high "Ratings Count" but declining "Monthly Sales Trends" to prevent churn of top-tier partners.

---

## Next Steps
*   **Predictive Modeling:** Implement a Time-Series Forecasting model (like ARIMA or Prophet) to predict future sales peaks.
*   **Sentiment Analysis:** Perform Natural Language Processing (NLP) on customer reviews to move beyond numerical ratings.
*   **Real-time Integration:** Transition the static analysis into a real-time dashboard using Streamlit or Dash.
