# E-Commerce Logistics & Delivery Analytics 🚚
**A Power BI analytics solution for 'Swift-Route Logistics' - a multi-hub logistics network — tracking delivery performance, driver efficiency, hub throughput, and fleet health across 27K+ orders.**

> 📊 4-page interactive dashboard · 🏢 6 hubs · 🚐 45 vehicles · 🤠 55 drivers · 📦 27,979 orders (2023–2024)

---

## 📸 Preview

| Summary Overview | Drivers |
|---|---|
| ![Overview](assets/screenshots/01_Logistics_Summary.png) | ![Drivers](assets/screenshots/02_Drivers.png) |

| Hubs | Vehicles |
|---|---|
| ![Hubs](assets/screenshots/03_Hubs.png) | ![Vehicles](assets/screenshots/04_Vehicles.png) |

---

## 🎯 Business Problem

SwiftRoute operates delivery hubs across Texas and needed a single source of truth to answer:

- Are we hitting on-time delivery targets, and is that trending up or down month over month?
- Which hubs are over/under capacity, and which are slowest to process orders?
- Which drivers are high performers vs. contributing disproportionately to delays?
- Which vehicles/models are breaking down most, and how does age affect reliability?

This dashboard was built to give a month-by-month, drillable view into all four areas from one place instead of manually pulling reports from separate spreadsheets.

---

## 🧱 Data Model

Star Schema with `Orders` as the fact table, joined to 1 Date Table & 3 Dimension Tables: - Drivers - Hubs - Vehicles 

![Data Model](docs/data_model.png)

---

## 🗂️ Repository Structure

```
ecommerce-logistics-and-delivery-analytics/
│
├── assets/
│     └── screenshots/
│        ├── 01_Logistics_Summary.png
│        ├── 02_Drivers.png
│        ├── 03_Hubs.png
│        └── 04_Vehicles.png
├── data/
│     ├── # Drivers.xlsx, Hubs.xlsx, Orders.xlsx, Vehicles.xlsx
│     └── data_dictionary.md
├── docs/
│     ├── business_requirements.md
|     └── data_model.png
├── report/
│     ├── PBI Report.pbix
├── README.md

```

---

## 📚 Data Dictionary

See [`data/data_dictionary.md`](data/data_dictionary.md) for full field-level definitions across all four tables (Orders, Hubs, Drivers, Vehicles).

---

## 🛠️ Tech Stack

- **Power BI Desktop** — Data Modeling, DAX measures, Report Design
- **DAX** — MoM growth calculations, On-time/delay rate measures, Dynamic titles etc
- **Microsoft Excel** — Source data (Orders, Drivers, Hubs, Vehicles)
