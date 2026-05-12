# Call Center Operations Performance Dashboard 📞📊

## 📌 Project Overview
This project delivers a comprehensive Power BI solution for a Call Center company to analyze operational efficiency and Sales Representative performance. The dashboard focuses on high-impact visualization and user experience (UX), allowing stakeholders to identify patterns in call volume, response speed, and customer wait times.

## 📊 Dataset Description
The analysis is based on call log data containing:
* **Call Metrics:** Incoming Calls, Outgoing Calls, Answered/Abandoned status.
* **Time Metrics:** Answer Speed (AVG), Talk Duration (AVG), Waiting Time (AVG).
* **Quality Metrics:** Service Level (20 Seconds), Answer Rate.
* **Personnel:** Sales Rep IDs.

## 🛠️ Tech Stack
* **Business Intelligence:** Power BI Desktop
* **Data Transformation:** Power Query (M Language)
* **Calculations:** DAX (Data Analysis Expressions)
* **Source:** CSV/Excel

## 🧠 Solution Architecture
### 1. Sales Rep Performance (Dashboard A)
* **Call Distribution:** A clustered bar chart showing Total Incoming vs. Total Outgoing calls per Rep.
* **Outbound Leaders:** A Top 3 ranking of representatives with the highest volume of outgoing calls.
* **Volume Analysis:** A Top 5 ranking of reps by overall call handling capacity.

### 2. Storytelling & KPI Deep-Dives
* Developed individualized report pages for Sales Reps to track personal KPIs over time.
* **Service Level Tracking:** Monitoring the percentage of calls answered within 20 seconds to ensure high customer satisfaction.

### 3. Pattern Discovery
* **Waiting Time vs. Abandonment:** Analyzed the correlation between increased waiting times and call abandonment rates.
* **Talk Duration Insight:** Identified that extended talk durations significantly impact the "Answer Rate" of incoming queues during peak hours.

## 💼 Business Impact
* **Productivity Benchmarking:** Clear visualization of top-performing vs. underperforming reps.
* **Operational Bottlenecks:** Identified specific time-based patterns where 'Waiting Time' exceeds thresholds, indicating a need for better shift scheduling.
* **Data-Driven Decision Making:** Transitioned the management team from anecdotal feedback to evidence-based performance reviews.




* `Call Center Data.csv`: The raw dataset.
* `README.md`: Project documentation.
