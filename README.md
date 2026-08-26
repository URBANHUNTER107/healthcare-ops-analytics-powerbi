# 🏥 Healthcare Operations & Patient Analytics Dashboard

An interactive, multi-page Power BI dashboard built to help hospital management teams monitor patient activity, resource utilization, and departmental performance — enabling faster, data-driven operational decisions.

---

## 📌 Business Objective

Hospital administrators need a centralized view of patient flow and resource allocation to reduce bottlenecks and improve care delivery. This dashboard was built to answer:

- How are patient visits and revenue distributed across age groups and departments?
- Which departments/hospitals face the highest bed and staff utilization?
- Where are patients experiencing the longest appointment waiting times?
- How satisfied are patients with prescriptions and overall hospital service?

---

## 🗂️ Dataset

Source: `Hospital Health Care Management Data set.xlsx`

A relational dataset spanning multiple linked tables:

| Table | Description |
|---|---|
| Patient Details | Patient visits, demographics, age groups, appointment data |
| Bed Details | Bed availability and occupancy by department |
| Staff Details | Staff allocation and department assignment |
| Department | Department-level reference data |

---

## 🛠️ Tech Stack

- **Power BI Desktop** — report authoring and data modeling
- **Power Query (M)** — data cleaning and transformation (merge, remove, trim, type conversion)
- **DAX** — KPI measures and calculated logic
- **Data Modeling** — star-schema-style relationships between fact and dimension tables

---

## ⚙️ Key Features

- **Two-page report**: Hospital Summary + Patients Summary
- **KPI cards** for at-a-glance metrics (visits, revenue, wait times, satisfaction)
- **Drill-down & drill-through** for department → patient-level detail
- **Filters and slicers** for dynamic segmentation by age group, department, and hospital
- **Button-based navigation** between report pages
- Custom visuals for enhanced UX (rotating card, scroller)

---

## 📊 Dashboard Preview

### Hospital Summary
_Bed occupancy, staff allocation, and department-level performance._

![Hospital Summary](hospital_summary.png)

### Patients Summary
_Patient visits, revenue by age group, appointment wait times, and service feedback._

![Patients Summary](patients_summary.png)

---

## 🔍 Key Insights

## 🔍 Key Insights

- **1,679 of 2,506 patients were admitted**, representing approximately **67% of the recorded patient population**.

- **1,483 patients fell into the 1–2 day length-of-stay category**, accounting for approximately **85% of the displayed LOS distribution**, indicating that short stays dominate the dataset.

- **Older patients tend to have longer stays**, with the **60+ age group recording the highest average LOS at 2.00 days**, compared with 1.46 days for patients aged 21–40.

- **The 6–20 age group is the largest patient segment**, with **794 patients**, followed by the 41–60 age group with 695 patients.

- **Gender distribution is relatively balanced**, with approximately **51% male and 49% female patients**, while the dashboard also tracks department-level patient status, ICU activity, deaths, bed occupancy, and treatment revenue.

---

## 🚀 How to Run

1. Clone this repository
   ```bash
   git clone https://github.com/<your-username>/healthcare-ops-analytics-powerbi.git
   ```
2. Open `Healthcare Dashboard.pbix` in **Power BI Desktop**
3. If prompted, update the data source path to point to the local `.xlsx` file
4. Explore the report — use the navigation buttons to switch between pages, and click into any KPI card for drill-through detail

---

## 👤 Author

**Mohd Farhan Abbas**
[LinkedIn](#) · [GitHub](#) · [Portfolio](#)
