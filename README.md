# HealthConnect Clinic – Data Analytics Project

**Programme:** AnalystLab Africa – Experience Lab Internship
**Track:** Data Analytics
**Tools:** Microsoft Excel, Power Query and Power BI

## Project Overview

HealthConnect Clinic is a fictional healthcare provider facing a high rate of missed patient appointments. This project explores how data analysis can help the clinic understand *why* patients miss appointments and where operational changes could reduce the impact.

**Central question:** How can HealthConnect Clinic use data to reduce missed appointments and improve the patient support experience?

## Dataset

* `HealthConnect_Appointment_Data.csv` — 5,000 anonymized appointment records
* `HealthConnect_Data_Dictionary.xlsx` — variable definitions and constraints

## Progress Log

### Week 4 — Problem Understanding & Initial Analysis

* Reviewed the dataset and data dictionary; ran a full data quality assessment covering missing values, duplicates and logical consistency checks
* Defined 6 business questions around appointment attendance
* Shortlisted 5 KPIs, each linked to a business question, with justification
* Identified assumptions, limitations, risks and dependencies
* Key early signal: booking lead time and prior no-show history show the strongest relationship with no-shows in initial cross-tabulation
* Confirmed that `None` in `reminder_channel` is a valid category representing records where no reminder was sent, rather than a missing value
* 📄 [[Week 4 Initial Analysis Document](./Week4/HealthConnect_Week4_DataAnalytics_InitialAnalysis.docx)

### Week 5 — Planned

* Calculate the 5 shortlisted KPIs.
* Apply and document a treatment decision for missing values in `distance_to_clinic_km` and `waiting_time_minutes`
* Analyse `reminder_channel`, including the `None` category representing no reminder
* Build initial visualizations, then migrate the shortlisted KPIs into a Power BI dashboard

## Repository Structure

```text
/Week4
  HealthConnect_Week4_DataAnalytics_InitialAnalysis.docx

README.md
```

---

*Part of the AnalystLab Africa Experience Lab programme. #AnalystLabAfrica*
