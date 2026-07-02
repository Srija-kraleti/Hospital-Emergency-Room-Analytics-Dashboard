# 🏥 Hospital Emergency Room Analytics Dashboard

An end-to-end **Business Intelligence** solution developed using **Power BI** to analyze Emergency Room (ER) operations, monitor patient flow, evaluate departmental performance, and provide actionable insights for hospital administrators. This project follows a complete analytics workflow—from synthetic data generation and modeling to interactive dashboard development and business reporting.

---

## 📌 Project Overview

Emergency Rooms handle a large volume of patients daily, making it challenging for hospital administrators to monitor operational efficiency, patient flow, and resource utilization. This project provides an interactive Power BI dashboard that transforms healthcare data into meaningful insights, enabling stakeholders to make informed, data-driven decisions.

The solution consists of **three interactive dashboard pages**, each designed for a different level of hospital management.

---

## 🎯 Business Problem

Hospitals often face operational challenges such as:

- Long patient waiting times
- Uneven doctor workload
- High bed occupancy
- Department-level performance variations
- Limited visibility into patient outcomes
- Difficulty in monitoring key operational KPIs

This dashboard addresses these challenges by providing a centralized reporting solution for monitoring Emergency Room performance.

---

# 🎯 Objectives

- Analyze Emergency Room patient flow
- Monitor hospital operational performance
- Track waiting and treatment times
- Evaluate department-wise performance
- Analyze patient demographics and diagnoses
- Monitor patient satisfaction
- Support hospital resource planning through interactive analytics

---

# 🛠️ Tech Stack

- **Power BI**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **Data Modeling (Star Schema)**
- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**

---

# 📂 Dataset

The project uses a synthetic healthcare dataset generated using Python.

| Dataset | Description |
|----------|-------------|
| **Patients** | Patient demographics including age and gender |
| **Doctors** | Doctor details and department assignments |
| **Departments** | Hospital department information |
| **Beds** | Bed allocation and occupancy status |
| **ER Visits** | Emergency Room visit records including waiting time, treatment time, diagnosis, satisfaction, and outcomes |

---

# 🏗️ Data Generation

Since publicly available hospital datasets often contain privacy restrictions, a realistic synthetic dataset was generated using Python.

The data generation process includes:

- Random patient generation
- Doctor allocation
- Department creation
- Bed assignment
- ER visit simulation
- Patient satisfaction generation
- Waiting time simulation
- Treatment duration simulation
- Admission and discharge outcomes

---

# ⭐ Data Model

The dashboard follows a **Star Schema** consisting of:

```
                 Departments
                      │
                      │
Doctors ───────── ER Visits ───────── Patients
                      │
                      │
                    Beds
```

The data model is optimized using one-to-many relationships to improve reporting performance and simplify DAX calculations.

---

# 📊 Dashboard Pages

## 📄 Page 1 – Executive Overview

Provides a high-level summary of Emergency Room operations.

### KPIs

- Total ER Visits
- Total Patients
- Admission Rate
- Average Waiting Time
- Average Treatment Time
- Average Length of Stay
- Bed Occupancy Rate
- Patient Satisfaction

### Visualizations

- Monthly ER Visit Trend
- Department Distribution
- Arrival Mode Distribution
- Patient Outcomes
- Triage Level Distribution
- Top Diagnoses

---

## 📄 Page 2 – Operational Analysis

Designed for hospital operations managers to monitor department efficiency and resource utilization.

### Visualizations

- Top Doctors by Patient Volume
- Average Waiting Time by Department
- Treatment Time by Department
- Length of Stay by Department
- Bed Status Analysis
- Doctor Workload
- Department Performance Matrix

---

## 📄 Page 3 – Patient & Clinical Insights

Focuses on patient demographics and clinical trends.

### Visualizations

- Patient Age Distribution
- Gender Distribution
- Diagnosis Distribution
- Patient Satisfaction by Department
- Average Length of Stay by Diagnosis
- Average Waiting Time by Age Group

---

# 📈 Key Performance Indicators (KPIs)

- Total ER Visits
- Total Patients
- Admission Rate
- Average Waiting Time
- Average Treatment Time
- Average Length of Stay (LOS)
- Bed Occupancy Rate
- Patient Satisfaction Score

---

# 📊 DAX Measures

The dashboard includes **25+ DAX measures** such as:

- Total ER Visits
- Total Patients
- Admission Rate
- Average Waiting Time
- Average Treatment Time
- Average Length of Stay
- Bed Occupancy Rate
- Average Satisfaction
- Occupied Beds
- Available Beds

Additionally, calculated columns were created for:

- Age Groups
- Year-Month
- Sorting Columns
- Dynamic Categorization

---

# 🔍 Key Business Insights

The dashboard enables stakeholders to answer questions such as:

- Which departments receive the highest number of patients?
- What is the average patient waiting time?
- Which doctors handle the highest workload?
- What are the most common diagnoses?
- Which age groups visit the ER most frequently?
- Which departments have the longest treatment duration?
- How satisfied are patients with hospital services?
- How effectively are hospital beds utilized?

---

# 🎨 Features

- Interactive KPI Cards
- Cross-filtering
- Slicers
- Multi-page dashboard
- Drill-down analysis
- Executive reporting
- Operational analytics
- Patient insights
- Star schema data model
- Interactive visualizations

---

# 📁 Repository Structure

```
Hospital-Emergency-Room-Analytics-Dashboard
│
├── Dashboard
│   ├── Hospital_ER_Analytics.pbix
│   └── Dashboard Screenshots
│
├── Data
│   ├── patients.csv
│   ├── doctors.csv
│   ├── departments.csv
│   ├── beds.csv
│   └── er_visits.csv
│
├── Data_Generation
│   ├── patients.ipynb
│   ├── doctors.ipynb
│   ├── departments.ipynb
│   ├── beds.ipynb
│   ├── helper.ipynb
│   └── config.ipynb
│
├── README.md
└── LICENSE
```

---

# 🚀 How to Run

1. Clone this repository.

```bash
git clone https://github.com/yourusername/Hospital-Emergency-Room-Analytics-Dashboard.git
```

2. Open the `.pbix` file using **Power BI Desktop**.

3. If required, refresh the data source.

4. Explore the interactive dashboard using the available slicers and filters.

---

# 📷 Dashboard Preview

## Executive Overview

<img width="737" height="413" alt="Screenshot 2026-07-02 154549" src="https://github.com/user-attachments/assets/6b8a9999-ff29-4c2b-be8c-6d0355279711" />


---

## Operational Analysis

<img width="735" height="413" alt="Screenshot 2026-07-02 154616" src="https://github.com/user-attachments/assets/18fb935d-f4f0-447c-beb7-69ab8a402a81" />


---

## Patient & Clinical Insights

<img width="735" height="413" alt="Screenshot 2026-07-02 154637" src="https://github.com/user-attachments/assets/c6158c71-28a4-4274-ab7a-a6104f8c4cb9" />


---

# 📌 Future Enhancements

- Real-time hospital data integration
- SQL database connectivity
- Predictive wait-time forecasting
- Bed occupancy prediction
- Azure deployment
- Automated report refresh
- Mobile-optimized dashboard
- Role-level security (RLS)

---

# 💼 Skills Demonstrated

- Business Intelligence
- Dashboard Design
- Data Visualization
- Healthcare Analytics
- Data Modeling
- DAX
- Power Query
- Python
- Pandas
- NumPy
- KPI Development
- Interactive Reporting
- Data Storytelling

---

# 👩‍💻 Author

**Kameswari Srija Kraleti**

📧 Email: *srijakraleti@gmail.com*

🔗 LinkedIn: *https://linkedin.com/in/kameswari-srija-kraleti*

💻 GitHub: *https://github.com/Srija-kraleti*

---

## ⭐ If you found this project useful, consider giving it a star!
