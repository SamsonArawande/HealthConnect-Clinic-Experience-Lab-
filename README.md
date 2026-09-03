# HealthConnect Clinic – Data Analytics Project

**Programme:** AnalystLab Africa – Experience Lab Internship
**Track:** Data Analytics
**Tools:** Microsoft Excel, Power BI

## Project Overview

HealthConnect Clinic is a fictional healthcare provider facing a high rate of missed
patient appointments. This project explores how data analysis can help the clinic
understand *why* patients miss appointments and where operational changes could
reduce the impact.

**Central question:** How can HealthConnect Clinic use data to reduce missed
appointments and improve the patient support experience?

## Dataset

- `HealthConnect_Appointment_Data.csv` — 5,000 anonymised appointment records
- `HealthConnect_Data_Dictionary.xlsx` — variable definitions and constraints

## Progress Log

### Week 4 — Problem Understanding & Initial Analysis
- Reviewed the dataset and data dictionary; ran a full data quality assessment
  (missing values, duplicates, logical consistency checks)
- Defined 6 business questions around appointment attendance
- Shortlisted 5 KPIs, each linked to a business question, with justification
- Identified assumptions, limitations, risks, and dependencies
- Key early signal: booking lead time and prior no-show history show the
  strongest relationship with no-shows in initial cross-tabulation
- 📄 [Week 4 Initial Analysis Document](./Week4/HealthConnect_Week4_DataAnalytics_InitialAnalysis.docx)

### Week 5 — Exploratory Analysis, KPI Development & Business Insights
- Completed full data preparation in Power Query: confirmed data types, zero
  duplicates, and only two genuine missing-data fields (`distance_to_clinic_km`,
  `waiting_time_minutes`) — corrected a Week 4 assumption along the way:
  `reminder_channel` is a valid 4-category field, not missing data
- Ran exploratory analysis across every relationship in the brief: appointment
  characteristics, patient history, reminders, waiting time, distance, and
  cancellations (analysed separately from no-shows)
- Calculated and interpreted all 5 shortlisted KPIs
- Built a two-page interactive Power BI dashboard (KPI drivers + a dedicated
  page for the weak/non-findings on day, time, age, and gender)
- Produced 6 business insights with clinic-facing recommendations
- Strongest confirmed drivers: booking lead time (27.8% → 67.7% no-show rate)
  and prior no-show history (43.5% → 68%); reminders (SMS most effective) and
  distance have real but smaller effects; day, time, age, gender, and
  appointment type show no meaningful variation
- 📄 [Week 5 Initial Analytics Report](./Week5/HealthConnect_Week5_DataAnalytics_AnalyticsReport.docx)

### Week 6 — Planned
- Investigate whether booking lead time and prior no-show history compound
  each other (interaction effect) as a potential 7th insight
- Refine the dashboard based on any feedback received
- Shape business recommendations into a prioritised rollout plan

## Repository Structure

```
/Week4
  HealthConnect_Week4_DataAnalytics_InitialAnalysis.docx
/Week5
  HealthConnect_Week5_DataAnalytics_AnalyticsReport.docx
README.md
```

---
*Part of the AnalystLab Africa Experience Lab programme. #AnalystLabAfrica*
