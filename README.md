# 📞 Call Centre Trends Dashboard - Power BI



## 📊 Project Overview

This project visualizes **Call Center performance trends** using **Power BI**. The dashboard offers a comprehensive overview of call volume, agent performance, customer satisfaction levels, and call distribution across time and days of the week. The goal is to enable better decision-making by transforming raw call center data into meaningful and actionable insights.

---

## 📁 Dataset Description

**File Name:** `01 Call-Center-Dataset.csv`  
**Rows:** ~5000  
**Columns:**
- `Agent`
- `Call Date`
- `Call Time`
- `Satisfaction Rating`
- `Call Resolved`
- `Call Abandoned`
- `Call Duration (sec)`
- `CSAT` (Customer Satisfaction Score)

---

## 📌 Key Metrics Visualized

### 📈 KPIs (Cards)
- **CSAT**: Average customer satisfaction score
- **Call Resolved %**: Percentage of calls resolved
- **Call Abandoned %**: Percentage of calls not completed
- **Speed of Answer**: Time taken to answer calls (in seconds)
- **Avg Call Handling Time**: Average duration of calls (in seconds)
- **Total Call Volume**: Number of calls received

### 👤 Agent Analysis Table
- Total calls handled per agent
- Average speed of answer
- Call resolved percentage
- Call abandoned percentage
- CSAT per agent

### 📅 Time-Based Visuals
- **Count of Calls by Hour**: Shows peak hours of the day for call volume
- **Count of Calls by Day**: Identifies trends in call volume across weekdays

### 💬 Satisfaction Analysis
- **Count of Calls by Satisfaction Level**: Distribution of customer satisfaction ratings (Very Dissatisfied → Very Satisfied)

---

## 🛠️ Power BI Features Used

- **DAX Calculated Columns**:
  - Hour and Day extraction
  - Custom satisfaction level mapping using `SWITCH()` and `ISBLANK()`
- **Sorting Techniques**:
  - Corrected hour and day orders using numeric sorting columns
- **Slicers**:
  - Agent filter
  - Weekday filter
  - Topic (if available)
  - Month filter
- **Conditional Formatting**:
  - Used in Agent Performance Table for better visibility
- **Color Themes**:
  - PWC branding-inspired color palette
- **Line and Area Charts**:
  - Used to show trends over time

---

## 📷 Dashboard Screenshot

Here is the final Power BI Dashboard created:

![Dashboard Screenshot](https://github.com/Ritik250/pwc-dashboard/blob/main/pwc_dashboard.png)



---

## 🚀 How to Use

1. Clone this repository.
2. Open `Call Centre Dashboard.pbix` in Power BI Desktop.
3. Make sure `01 Call-Center-Dataset.csv` is placed in the same directory or reassign the data source.
4. Explore the visualizations and interact with slicers for dynamic filtering.

---

## 📈 Insights & Takeaways

- **Most calls were received between 09:00–17:00**, with a sharp drop after 18:00.
- **Monday and Saturday** were the busiest days for call volume.
- **Normal and Satisfied** are the most common satisfaction ratings.
- Agent performance varies significantly in terms of **CSAT** and **Call Abandonment Rate**, highlighting the need for training and performance management.

---

## 🧠 Future Enhancements

- Integrate monthly trends using `Month-Year` columns.
- Include call topic categorization.
- Add drill-through pages for individual agent deep-dive.
- Implement clustering to group customer types.

---

## 🤝 Acknowledgements

- Data is synthetic and used for educational/visualization purposes.
- Dashboard inspired by enterprise customer service analytics use-cases.

---

