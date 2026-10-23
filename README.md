# Supway HR Analytics

An HR analytics dashboard in Power BI focused on employee attrition, workforce composition, and experience, built on a 1,480-record HR dataset.

## Overview

| Item | Detail |
|---|---|
| Dataset | 1,480 employee records, 38 fields |
| Tooling | Power BI Desktop, DAX, native visuals |
| Layout | Single-page HR dashboard |
| Visuals | 6 KPI cards, donut, bar, column, pie, area, funnel, pivot table, 2 slicers |

## What the dashboard covers

**Headline KPIs**

- Total employees and active employees.
- Attrition count and attrition rate.
- Average age and average experience.

**Attrition analysis**

- Attrition by department.
- Attrition by salary slab.
- Attrition by job role and job satisfaction.
- Attrition by gender.
- Attrition trend against years of experience.

**Workforce profile**

- Age group distribution.
- Department-wise employee count.
- A pivot table for detailed segment review.

The two slicers filter the full page, so a department or demographic selection updates every card and chart.

## Dataset

`data/HR_Analytics.csv` contains 1,480 records and 38 fields, including age group, attrition flag, business travel, department, education, job role, job satisfaction, salary slab, years at company, and years since last promotion.

The file uses employee IDs only; it contains no employee names or contact details.

## Repository contents

```text
supway-hr-analytics/
|-- Supway_HR_Analytics.pbix
|-- data/
|   `-- HR_Analytics.csv
`-- README.md
```

## How to open

1. Open `Supway_HR_Analytics.pbix` in Power BI Desktop.
2. Use the slicers to isolate a department or employee segment.
3. Hover over the KPI cards and charts for exact values.

## Data notes

- The report uses a representative HR dataset for analysis.
- No real employee records are published with this project.
- The project is independent and is not affiliated with any employer or brand.

## Author

**Mohamed Mahmoud Taha** - Financial Analyst | Data Analyst

GitHub: [momahmoud02](https://github.com/momahmoud02)
