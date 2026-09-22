# Business Requirements — SwiftRoute Logistics Dashboard

This document defines the KPIs, visuals, and business use case behind every metric in the dashboard, organized by page.

---

## Dashboard 1: Overview

### KPIs

**1. Total Orders**
- Total orders for the selected Year and Month
- Total orders for the Previous Month
- Month-over-Month (MoM) growth / decline %

**2. On-Time Delivery Rate (%)**
- On-time delivery % for the selected Year and Month
- On-time delivery % for the Previous Month
- MoM change (%)

**3. Customer Satisfaction Score (CSAT %)**
- Overall CSAT % for the selected Year and Month
- CSAT % for the Previous Month
- MoM change (%)

**4. Average Delivery Time (Hours)**
- Average delivery time for the selected Year and Month
- Average delivery time for the Previous Month
- MoM change (%)

### Hub

| # | Metric | Chart Used | Business Use Case |
|---|---|---|---|
| 1 | Total Number of Hubs | KPI Card | Quick visibility into total operational hubs to assess network size and coverage |
| 2 | Orders Processed vs Hub Capacity | Clustered Column Chart | Identifies hubs operating above or below capacity, enabling better workload distribution and capacity planning |
| 3 | Hub Performance Ranking | Bar Chart (Ranked) | Enables comparison of hub efficiency; helps management identify top-performing and underperforming hubs |

### Drivers

| # | Metric | Chart Used | Business Use Case |
|---|---|---|---|
| 1 | Number of Drivers | KPI Card | Visibility into total active drivers to support workforce planning and capacity assessment |
| 2 | Experience vs Rating | Scatter Plot | Analyzes the relationship between driver experience and performance rating to identify skill gaps and training needs |
| 3 | Drivers with Most Delays | Bar Chart | Identifies drivers contributing to the highest number of delays, enabling targeted coaching |

### Vehicles

| # | Metric | Chart Used | Business Use Case |
|---|---|---|---|
| 1 | Number of Vehicles | KPI Card | Total fleet size to support high-level fleet capacity and planning decisions |
| 2 | Active Vehicles | Donut | Number of vehicles currently active, to monitor fleet availability and operational readiness |
| 3 | Total Orders by Vehicle Model | Bar Chart | Compares order volumes handled by different vehicle models to identify high-utilization vehicles |

---

## Dashboard 2: Hubs Overview

| # | Metric | Chart Used | Business Use Case |
|---|---|---|---|
| 1 | Total Number of Hubs | KPI Card | Quick visibility into total operational hubs to assess network size and coverage |
| 2 | Orders Processed vs Hub Capacity | Clustered Column Chart | Identifies hubs operating above or below capacity, enabling better workload distribution and capacity planning |
| 3 | Hub Performance Ranking | Bar Chart (Ranked) | Enables comparison of hub efficiency; helps identify top-performing and underperforming hubs |
| 4 | Hub Order Processing Time (Hours) | Matrix Chart | Shows how many hours each hub takes to process orders daily, helping identify slow-performing hubs and improve turnaround time |

---

## Dashboard 3: Drivers Overview

| # | Metric | Chart Used | Business Use Case |
|---|---|---|---|
| 1 | Number of Drivers | KPI Card | Visibility into total active drivers to support workforce planning and capacity assessment |
| 2 | Experience vs Rating | Scatter Plot | Analyzes the relationship between driver experience and performance rating to identify skill gaps and training needs |
| 3 | Drivers with Most Delays | Bar Chart | Identifies drivers contributing to the highest number of delays, enabling targeted coaching |
| 4 | Driver Profile Summary (by Driver Name) — Hire Date, Years of Experience, Star Rating, Deliveries for selected Month | KPI Card | Consolidated view of individual driver performance and experience for evaluation and decision-making |
| 5 | Monthly Trend of Orders | Line Chart | Displays month-wise delivery trends to analyze driver workload patterns and seasonal demand impact |

---

## Dashboard 4: Vehicle Overview

| # | Metric | Chart Used | Business Use Case |
|---|---|---|---|
| 1 | Number of Vehicles | KPI Card | Total fleet size to support high-level fleet capacity and planning decisions |
| 2 | Active Vehicles | Donut | Number of vehicles currently active, to monitor fleet availability and operational readiness |
| 3 | Total Orders by Vehicle Model | Bar Chart | Compares order volumes handled by different vehicle models to identify high-utilization vehicles |
| 4 | Vehicle Age vs Breakdown | Scatter Chart | Analyzes the relationship between vehicle age and breakdown count to identify aging vehicles with higher maintenance risk |
| 5 | Breakdown by Vehicle Code | Bar Chart | Identifies specific vehicles with frequent breakdowns to support targeted maintenance actions |
| 6 | Breakdown by Vehicle Model | Bar Chart | Compares breakdown frequency across vehicle models to evaluate model reliability |
| 7 | Orders by Vehicle Type | Donut Chart | Shows distribution of orders across vehicle types to understand fleet utilization patterns |
