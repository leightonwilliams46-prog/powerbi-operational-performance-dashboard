# Operational Performance Dashboard (Power BI)

This Power BI dashboard provides a consolidated view of operational performance across our global Quality & Accreditation function. The dashboard is designed to support senior leadership by tracking year‑on‑year workload volumes, turnaround times, submission/completion activity, and data quality indicators. It brings together multi‑year operational data into a clear, interactive reporting environment that helps stakeholders identify performance patterns, understand regional pressures, and support operational planning.

---

## 📊 Executive Summary

This dashboard was developed to improve visibility of operational performance across key review activities. It integrates submissions, pick‑ups, completions, and turnaround metrics into a unified reporting model, allowing decision‑makers to compare performance over time, evaluate KPI progress, and monitor regional workload distribution.

Multi‑year patterns highlight sustained improvements in throughput and stable turnaround times across several regions. The dashboard also surfaces data quality considerations through the Power Query transformations and modelling structure. Collectively, these insights support governance discussions, resource planning, and continuous performance improvement.

---

## 📁 Repository Structure

```text
powerbi-operational-performance-dashboard
│
├── README.md
├── dashboard/
│   └── operational_performance_dashboard.pbix
└── screenshots/
    ├── GitHub Dashboard OverView.png
    ├── GitHub DM Turnaround Time.png
    ├── GitHub Data Model View.png
    ├── GitHub Power Query Transformations.png
    └── GitHub Submissions Year On Year.png
```

---

## 📄 **Data Context**

The dashboard is built on multi‑year operational data covering:

- **Submissions received**
- **Reviews picked up**
- **Reviews completed**
- **Turnaround time**
- **Regional and process‑level breakdowns**

Data is sourced from internal operational systems and processed in Excel and Power Query prior to modelling in Power BI.  
Due to confidentiality, the underlying dataset cannot be included in this repository; however, the `.pbix` file contains the full data model structure, transformations, and measures.

---

## 🔧 **Methodology**

The development process included:

### **1. Data Preparation (Power Query)**
- Standardised date formats, category labels, and record structures  
- Removed duplicates and validated year‑on‑year consistency  
- Merged multiple source files into a clean, unified table  

### **2. Data Modelling**
- Designed a structured model linking activities, dates, and categories  
- Created relationships to enable cross‑filtering across processes and regions  
- Defined KPI measures using DAX, including year‑on‑year % changes, rolling metrics, and turnaround time calculations

### **3. Dashboard Design**
- Built multi‑year trend visuals for submissions, pick‑ups, completions  
- Created turnaround time monitoring pages  
- Designed an overview page summarising key performance actions  
- Ensured dashboards were aligned with the reporting needs of senior management  

---

## 🖼️ **Screenshots**

### **📊 Dashboard Overview**
Provides a high‑level view of operational workload and performance across the full review lifecycle.  
Shows multi‑year submission trends, completions, and KPI summary visuals.

<img width="1850" height="852" alt="GitHub Dashboard OverView" src="https://github.com/user-attachments/assets/41be03dc-cb20-4656-be1e-f7c69e03c96a" />

---

### **⏱ Turnaround Time View**
A focused view on weekly and regional turnaround trends, used to identify bottlenecks and efficiency improvements.  

<img width="498" height="335" alt="GitHub DM Turnaround Time" src="https://github.com/user-attachments/assets/574a97a0-eb2a-4307-a320-f9c4c7cec880" />

---

### **🧩 Data Model**
Displays the underlying relationship structure between tables, enabling flexible cross‑filtering across regions, activities and time periods. 

<img width="1889" height="802" alt="GitHub Data Model View" src="https://github.com/user-attachments/assets/dfd9b795-5e13-41f9-9605-33ea2da5c9a4" />

---

### **⚙️ Power Query Transformations**
Shows the transformation logic, data cleansing steps, and applied preprocessing.  

<img width="1912" height="1010" alt="GitHub Power Query Transformations" src="https://github.com/user-attachments/assets/ccb7abf6-90db-4be8-b041-ec38660f0dab" />

---

## 📈 **Key Insights & Interpretation**

Analysis from the dashboard highlights the following patterns:

- **Workload volumes show consistent year‑on‑year growth**, with submissions and completions steadily increasing across regions.  
- **Turnaround times remain stable**, with several regions showing improvements relative to previous years.  
- **Pick‑up rates have strengthened**, indicating improved allocation consistency and operational efficiency.  
- **Cross‑regional comparisons reveal variation in throughput**, helping identify where additional resources or process improvements may be needed.  
- **Data quality indicators surfaced through Power Query** highlight where upstream corrections or standardisation efforts may provide further efficiency gains.  

These insights provide operational managers with timely, data‑driven information to support planning, resource deployment, and performance monitoring.

---

## ▶️ **How to Use the Dashboard**

### **To open the dashboard locally:**

1. Download the `.pbix` file from the `/dashboard` folder  
2. Open it in **Power BI Desktop**  
3. Review the data model, transformations, and DAX measures  
4. Interact with:
   - slicers  
   - cross‑filters  
   - year‑on‑year trend visuals  
5. Use the Overview tab for senior‑level summaries, and drill into regional or metric‑specific pages for detailed analysis[1](https://github.com/leightonwilliams46-prog/faulty-medical-devices-analysis/blob/main/README.md)

---

## 🛠 **Tools Used**

- **Power BI Desktop**  
- **Power Query**  
- **DAX (measures, calculated columns)**  
- **Excel (pre‑processing)**  
- **Data modelling (relationships, schema design)**

---

## ✅ **Conclusion**

This dashboard provides a reliable and interactive reporting environment for reviewing multi‑year operational performance. By combining workload volumes, turnaround times, and regional patterns into a single reporting asset, it enables informed decision‑making, improved KPI tracking, and clearer identification of operational bottlenecks.

The structured data model, clean transformations, and DAX‑driven calculations ensure that stakeholders have access to accurate, consistent, and high‑value performance insights to support both tactical and strategic planning.  
