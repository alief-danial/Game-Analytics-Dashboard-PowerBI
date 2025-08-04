# Game-Analytics-Dashboard-PowerBI

## Project Overview
This project showcases a **Power BI dashboard** designed to analyze **player engagement metrics** for a simulated mobile/PC game. The dashboard provides actionable insights into player activity, in-game purchases, retention behavior, and community feedback sentiment — supporting data-driven decision-making for game operations and monetization strategies.
---
## Repo Folder Structure
Gaming-Analytics-Dashboard-PowerBI/
<pre>
├── Dataset/
│   └── player_engagement_data.csv
├── PowerBI_Report/
│   └── GamingAnalyticsDashboard.pbix
├── Screenshots/
│   └── dashboard_overview.pdf
├── README.md
</pre>

## Dataset
The dataset (**player_engagement_data.csv**) simulates **200 player activity logs** with the following attributes:
| Column Name               | Description                                       |
|---------------------------|---------------------------------------------------|
| Player_ID                  | Unique identifier for each player                |
| Region                     | Player's region (SEA, NA, EU)                    |
| Session_Date                | Date of gameplay session                         |
| Session_Duration (min)     | Duration of session in minutes                   |
| Purchase_Amount (USD)      | In-game purchase amount per session              |
| Feedback_Score             | Player feedback sentiment (Positive, Neutral, Negative) |
| Retention_Day              | Retention indicator (Day 1, Day 7, Day 30, Churned) |

---

## Dashboard Highlights
- 📈 **Daily Active Users (DAU) Trends** — Visualized user activity over time.
- 💰 **In-Game Purchase Revenue Analysis** — Tracks total revenue & purchasing behavior.
- ⏱️ **Average Session Duration by Region** — Highlights player engagement per region.
- 🔁 **Retention & Churn Breakdown** — Insights into player retention patterns.
- 😊 **Feedback Sentiment Analysis** — Breakdown of positive, neutral, and negative feedback.
- 🌍 **Regional Player Distribution** — Map visualization of active player locations.
- 📊 **Insight Cards/KPIs**:
  - Total Players
  - Total Revenue
  - Average Session Duration
  - Positive Feedback Percentage

---

## Key DAX Measures Used
- Total Players (Unique Player Count)
- Total Revenue (Sum of Purchase Amount)
- Average Session Time
- Positive Feedback Rate (%)
- Churn Rate (%)
- Average Revenue Per User (ARPU)

---

## Tools & Technologies
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query (Data Transformation)
- CSV Dataset Simulation (Python/Excel)

---

## Business Use Case
Gaming studios can utilize such dashboards to:
- Monitor player engagement and churn.
- Optimize monetization strategies based on real-time revenue insights.
- Track community sentiment to guide game updates and retention efforts.
- Analyze regional market performance for targeted campaigns.

---

## Author
**Muhammad Alief Danial Bin Mohd Fadzil**  
[LinkedIn Profile](https://www.linkedin.com/in/alieffadzil) | [GitHub Portfolio](https://github.com/alief-danial)

---

