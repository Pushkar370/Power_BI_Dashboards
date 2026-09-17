# 📊 Data Jobs Dashboard (Power BI)

This was my **first hands-on project in Power BI**. I used it as a learning exercise to explore and implement as many different visual types as possible in one place, rather than sticking to just a couple of chart types. The result is a 2-page interactive dashboard analyzing **479K+ data-related job postings** from 2024 — covering salaries, job trends, top-paying roles, hiring platforms, job types, and global job distribution.

## 🎯 Why I Built This

Coming in with no prior Power BI experience, my goal wasn't just to build one dashboard — it was to intentionally touch **every major visual category** Power BI offers (cards, trend lines, scatter plots, bar charts, gauges, donut charts, matrix tables with sparklines, maps, and more) so I'd walk away comfortable with the full toolkit, not just the basics.

## 📁 Repo Contents

| File | Description |
|---|---|
| `Dashboards_1.pbix` | Power BI report file containing both dashboard pages |
| `Screenshot 2026-09-17 164809.png` | Main "Data Jobs Dashboard" landing page |
| `Screenshot 2026-09-17 164934.png` | Job Title drill-through page (example: Data Scientist) |

## 🖥️ Page 1 — Dashboard Overview

The main page gives a high-level view of the job market, with a slicer to filter by **Job Title**.

![Data Jobs Dashboard Overview](Screenshot%202026-09-17%20164809.png)

**Visuals implemented on this page:**
- **KPI cards** — Job Count (479K), Median Yearly Salary ($113K), Median Hourly Salary ($47.62)
- **Custom rating visual** — Salary Star Rating
- **Line chart with trend line** — job count by year, quarter, and month across 2024
- **Scatter plot** — Hourly vs Yearly Salary across roles like Data Engineer, Data Scientist, Business Analyst, Cloud Engineer, and more
- **Horizontal bar chart** — highest paying jobs in data, ranked by job count
- **Matrix table with sparklines** — job count, yearly/hourly salary, and job trend per role
- **Slicer (dropdown)** — filter the whole page by Job Title
- **Drill-through button**

## 🔍 Page 2 — Job Title Drill-Through

Clicking into a specific role (e.g. **Data Scientist**) opens a dedicated drill-through page with deeper insights.

![Job Title Drill-Through — Data Scientist](Screenshot%202026-09-17%20164934.png)

**Visuals implemented on this page:**
- **Gauge charts** — Median Yearly Salary and Median Hourly Salary, with min–max range
- **Donut charts** — WFH %, Job Degree Mention %, Health Insurance %
- **Bing map (bubble map)** — global distribution of job postings
- **Horizontal bar chart** — top hiring platforms (LinkedIn, BeBee, Indeed, ZipRecruiter, and more)
- **Stacked bar / treemap** — job type breakdown (Full-time, Contractor, Internship, Part-time, Temp work)
- **Drill-through navigation button** — back to main dashboard

## 🧠 What I Learned

- Building KPI cards and combining them into a cohesive layout
- Adding trend lines and forecasting visuals to line charts
- Using scatter plots to compare two numeric measures across categories
- Formatting gauges and donut charts for at-a-glance metrics
- Working with Bing maps for geographic visualization
- Building drill-through pages and navigation buttons
- Using matrix tables with conditional formatting and sparklines
- General dashboard layout, theming, and slicer interactivity

## 🛠️ Tech Stack

- **Power BI Desktop** (`.pbix`)

## 🚀 How to Use

1. Clone/download this repo.
2. Open `Dashboards_1.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Use the **Job Title** slicer on the main page to filter the dashboard.
4. Right-click a job title in the table (or use the on-screen button) to access the **drill-through page** for role-specific details.

## 📌 Notes

- Data reflects job postings collected during 2024.
- Salary figures are shown in USD.
- As a first project, the focus was on breadth of visuals and learning the tool — future dashboards will build on this with cleaner DAX measures and more refined UX.