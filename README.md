# Hospital Emergency Room Capacity & Wait-Time BI Dashboard
**Clinical Patient Flow Analytics, Triage Priority Modeling & Staffing Optimization**

[![Status: Completed](https://img.shields.io/badge/Status-Completed-success.svg)](#) 
[![Tech Stack: Power BI / DAX / Power Query ETL](https://img.shields.io/badge/Stack-Power%20BI%20%7C%20DAX%20%7C%20PowerQuery-blue.svg)](#) 
[![AI Disclosure: AI Assisted](https://img.shields.io/badge/AI%20Disclosure-AI--Assisted%20Dev-orange.svg)](#)

---

## 📋 Overview

An executive Power BI reporting dashboard designed to analyze hospital Emergency Department patient flow, triage wait times, demographic trends, and peak arrival hours. The dashboard provides actionable insights to assist healthcare administrators in shift planning and triage queue management.

---

## 🎯 Business Problem

* **Context**: Regional hospital Emergency Rooms experience fluctuating patient volume, leading to unexpected bottleneck hours and extended triage wait times.
* **Pain Point**: Lack of centralized reporting obscured the relationship between patient arrival times, severity levels (1-5), and physician shift coverage.
* **Impact**: Unmanaged queue spikes increased patient wait times and reduced overall hospital satisfaction scores.

---

## 💡 Solution

Transformed raw clinical admission datasets into a dimensional Power BI data model. Built interactive visual layouts with dynamic slicers for age group, triage urgency score, admission status, and hourly arrival trends.

---

## 📐 Architecture Diagram

```
Raw Clinical Admission Logs (CSV / SQL)
                   ↓
        Power Query ETL Cleaning
  (Timestamp Normalization & Median Imputation)
                   ↓
         Dimensional Star Schema
  (Fact_Admissions ↔ Dim_Patient, Dim_Triage, Dim_Time)
                   ↓
             DAX Analytics
   (Avg Wait Time, % Admitted, Peak Hours)
                   ↓
   Power BI Executive Operational Dashboard
```

---

## ⚙️ Tech Stack

* **BI Platform**: Power BI Desktop
* **ETL & Data Prep**: Power Query (M Language)
* **Analytics Engine**: DAX (Data Analysis Expressions)
* **Data Schema**: Dimensional Star Schema
* **Development**: AI-assisted DAX pattern research with manual visual and filter context validation.

---

## 🚀 Key Features

* ✨ **Peak Arrival Hour Heatmaps**: Visualizes volume surges by hour of the day and day of the week.
* ✨ **Triage Severity Slicers**: Filters wait times across triage priority levels (1 = Immediate to 5 = Non-urgent).
* ✨ **KPI Cards**: Displays real-time aggregates for Total Patients, Average Wait Time (mins), and Admission Rate %.

---

## 📈 Business Impact

* 🏥 **Resource Allocation Insights**: Highlighted peak arrival windows (6 PM - 10 PM) to assist physician shift planning.
* ⏱️ **Operational Clarity**: Identified non-urgent triage categories contributing to room clutter.

---

## 👨‍💻 My Role & Contribution

* **Data Cleansing**: Normalized timestamp values, resolved missing triage entries, and shaped data in Power Query.
* **DAX Modeling**: Authored custom measures for Average Wait Time, % Admitted, and Hourly Density.
* **Dashboard Design**: Styled clean visual hierarchies using healthcare-focused color palettes.

---

## 🤖 AI Disclosure & Validation

Developed in Power BI using domain-specific DAX formulas. AI assistance was utilized for formula optimization, with all filter contexts, relationships, and visual metrics validated manually against clinical benchmarks.
