# 📊 Data Jobs Dashboard 2.0 (Power BI)

This is the second version of my Data Jobs Dashboard, built in Power BI. It explores a dataset of nearly **479K data-related job postings**, with a focus on the most requested skills, salary comparisons across roles, and interactive filtering by job title and country.

## 🎯 Project Focus

This version brings the job-market analysis into a focused overview page. It puts skills and compensation side by side so viewers can compare what employers request with salary levels across data roles.

## 📁 Repo Contents

| File | Description |
|---|---|
| `Data Job Dashboard.pbix` | Power BI report file for the Data Jobs Dashboard 2.0 |
| `../images/Screenshot 2026-09-25 234056.png` | Screenshot of the dashboard overview |

## 🖥️ Dashboard Overview

The page includes Job Title and Country slicers, plus a Clear slicers control. Summary metrics show job count, average skills per job, median yearly salary, and median hourly salary.

![Data Jobs Dashboard 2.0 overview](../images/Screenshot%202026-09-25%20234056.png)

**Visuals and controls on this page:**
- **Summary cards** — Job Count, Skill per job, Median Yearly Salary, and Median Hourly Salary
- **Top skills chart** — skills such as Python, SQL, AWS, Azure, and Tableau, with controls to compare job count and job percent
- **Salary-by-role chart** — median salary across roles such as Machine Learning Engineer, Software Engineer, Data Engineer, and Data Scientist, with yearly and hourly views
- **Slicers** — filter by Job Title and Country, with a control to clear selections

## 🛠️ Tech Stack

- **Power BI Desktop** (`.pbix`)

## 🚀 How to Use

1. Clone or download this repo.
2. Open `Data Job Dashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Use the Job Title and Country slicers to filter the dashboard.
4. Use the chart controls to compare skill counts or percentages and yearly or hourly salaries.

## 📌 Notes

- The displayed job count is approximately 479K.
- Salary values are shown in USD.
