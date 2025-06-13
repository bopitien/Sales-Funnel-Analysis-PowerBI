# 🎯 EduTrack Funnel Optimization Dashboard
**Analyzing and Improving Course Enrollment for LearnCore (An e-Learning Platform)**  
_By Brume Pascal_

---

## 📘 Project Overview

This case study focuses on identifying friction points within LearnCore’s enrollment funnel using Power BI. Although LearnCore ran a successful awareness campaign and attracted over 90K visitors, conversion into enrolled students remained extremely low (less than 1%).

This dynamic Power BI dashboard tracks the user journey across all funnel stages — from landing page to payment — helping stakeholders identify where most users drop off and what actions are needed to boost enrollments.

---

## 🔍 Business Context

LearnCore recently launched promotional campaigns offering free course access and heavily promoted content in tech communities. This generated high website traffic and user curiosity.

However, only a small percentage of users enrolled in courses, prompting the need to analyze:
- Where users lose interest
- Which devices and user types convert better
- What steps to take to optimize the funnel

---

## 🧪 Project Objectives

- Visualize LearnCore’s complete user funnel from Landing → Payment
- Calculate conversion and drop-off rates at each stage
- Analyze visitor behavior by device, type (new vs returning), and time
- Recommend actionable improvements for funnel performance
- Enable continuous monitoring via a dynamic Power BI dashboard

---

## 🗃️ Dataset Summary

The dataset includes 8 funnel-related logs and 1 user profile table. Each row represents a page visit, joined by `User ID`.

| Table Name           | Description                                 |
|----------------------|---------------------------------------------|
| Users                | Gender, device, and visit date per user     |
| Landing Page         | Who arrived on the site                     |
| Courses Exploration  | Who browsed courses                         |
| Signup               | Who initiated signup                        |
| Course Preview       | Who previewed course content                |
| Enrollment           | Who started course enrollment               |
| Payment Confirmation | Who completed payment                       |

---

## 🛠 Tools Used

- **Power BI** – dashboard design and visualization
- **Power Query** – data transformation and modeling
- **Excel** – raw data source

---

## 🧮 Key Metrics Calculated

- Total Visitors  
- Total Enrollments  
- Conversion Rate (%)  
- Drop-off Rate (%)  
- Stage-by-stage drop-off  
- Conversion by Device  
- Conversion by Visitor Type (New vs Returning)  
- Conversion Rate Trend Over Time  

---

## 📊 Dashboard Features

The dashboard is fully interactive and includes:

- 📌 KPI Summary Cards (Visitors, Enrollments, Conversion Rate, Drop-off Rate)
- 🔻 Funnel Chart: Retention Through Enrollment Funnel
- 🔥 Drop-off Rate Chart: Where We Are Losing Users
- 📈 Line Charts: Visitors by Device & Conversion Rate by Date
- 📱 Device-Level Conversion Breakdown
- 🔁 New vs Returning User Distribution
- 📅 Time-based performance trends

---

## 🧠 Insights

- 💡 **Only 0.48% of users completed enrollment** — a drop-off rate of 99.52%
- 🔻 **Highest drop-offs occur** after signup (69.9%) and at payment (92.3%)
- 🖥️ **Desktop converts better than mobile** (0.51% vs 0.43%)
- 🆕 **New users dominate traffic**, but few return — showing weak nurturing
- 📉 Conversion rates fluctuate over time with occasional spikes (Feb, Apr)

---

## ✅ Recommendations

- Simplify enrollment & payment flow to reduce friction
- Make course previews more accessible and persuasive earlier
- Optimize mobile UX for better conversion on mobile devices
- Implement remarketing or email recovery flows for drop-offs
- Recreate successful campaigns from past high-conversion periods

---

## 📎 Files in this Repository

| File | Description |
|------|-------------|
| `LearnCore-Funnel.pbix` | The full Power BI dashboard file |
| `User_Funnel_Data.xlsx` | Raw data used for the analysis |
| `LearnCore_Presentation.pptx` | Final PowerPoint report for stakeholders |
| `README.md` | This documentation file |

---

## 🔁 Use Case

This dashboard is built as a **dynamic, always-on tool** that enables the marketing and product teams at LearnCore to:
- Track conversion metrics continuously
- Identify trends and bottlenecks in real time
- Make data-driven adjustments to the user journey and campaigns

---

## 👨‍💻 Author

**Brume Pascal Opitien**  
[LinkedIn](linkedin.com/in/pascalbrume ) | [Email](mailto:brumepascal@gmail.com)

---

## 📌 Live Dashboard Link

> 🔗 [Click to Explore the Interactive Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNzk5NDU5NTgtZjY0Yy00NzQ3LTg3NzctNTc2YWIxNDY0YTM1IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

---

## 📄 License

This project is for demonstration, learning, and case study purposes only.
