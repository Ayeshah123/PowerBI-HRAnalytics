📊 #PowerBI-HRAnalytics
Interactive Power BI dashboard on HR Analytics showcasing Employee Overview and Demographics across 4 periods (2009–2017).

> **Note:** This project was created for **learning & practice purposes only**.

##Introduction
This project analyzes HR data to explore employee trends across demographics, hiring, and terminations from 2009–2017.

##Data Cleaning & Preparation
- Remove duplicate Values
- Ensures data consistency
- Create two seperate Data tables for Hiring and Termination (using Power Query Editor)
- Change data types and resolve errors

##Data Modeling (using Star Scehma)
👉 Dimension Tables:
- Employee: ID, Name, Salary, Position, State, Gender, Marital Status, Citizenship Status, Hispanic Latino, Race, Date of Birth, Age, Age Range
- Department: ID, Name
- State Lookup: State Code, Name
- Termination Table: Date ID, Date, Year, Month, Month Name, Month Year, Quarter, Period, Period Number
- Hiring Table: Date ID, Date, Year, Month, Month Name, Month Year, Quarter, Period, Period Number

👉 Fact Table:
- FactHR: ID, Dep ID, Hiring Date, Termination Date, Hiring ID, Termination ID, Termination Status, Performance Score, Termination Reason, Absences

---

##Dashboard Features:
👉 Employee Overview
- Headcount, Terminations & Current Working Employees (Graph and PTD % change)
- Working Employees by Age Range & Department
- Total Hires by Period and Department
- Termination Status

👉 Demographics Employee:
- Total Males, Females (Graph and PTD % Change)
- Avg. Income, Avg. Female Income and Avg. Male Income (Graph and PTD % change)
- Avg. Age (Graph and PTD % change) + Employees divison across Age Ranges
- Current Employees by Race
- Total Hires by Period and Department
- Employees Active Status and division of Hispanic Latino

---
👉 DAX Measure:
- Total Hires, Terminations and Current Working Employees
- PTD % Change of Hires, Terminations and Current Working Employees 
- Avg. Income, Avg. Female Income and Avg. Male Income
- PTD % Change ofAvg. Income, Avg. Female Income and Avg. Male Income
---

##Project Files
👯 Open to learning, sharing & collaboration

🌱LinkedIn
🌱E-mail
