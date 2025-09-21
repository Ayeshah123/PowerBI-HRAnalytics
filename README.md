# 📊PowerBI-HRAnalytics
Interactive Power BI dashboard on HR Analytics showcasing Employee Overview and Demographics across 4 periods (2009–2017).

> **Note:** This project was created for **learning & practice purposes only**.

## Introduction
This project analyzes HR data to explore employee trends across demographics, hiring, and terminations from 2009–2017.

## Data Cleaning & Preparation
- Removed duplicate values  
- Ensured data consistency  
- Created two separate Date tables (Hiring & Termination) using Power Query  
- Changed data types and resolved errors  

## Data Modeling (using Star Scehma)
- Dimension Tables:
  👉 Employee: ID, Name, Salary, Position, State, Gender, Marital Status, Citizenship Status, Hispanic Latino, Race, Date of Birth, Age, Age Range
  👉 Department: ID, Name
  👉 State Lookup: State Code, Name
  👉 Termination Table: Date ID, Date, Year, Month, Month Name, Month Year, Quarter, Period, Period Number
  👉 Hiring Table: Date ID, Date, Year, Month, Month Name, Month Year, Quarter, Period, Period Number

- Fact Table:
  👉 FactHR: ID, Dep ID, Hiring Date, Termination Date, Hiring ID, Termination ID, Termination Status, Performance Score, Termination Reason, Absences

---

## Dashboard Features:
- Employee Overview
  👉 Headcount, Terminations & Current Working Employees (Graph and PTD % change)
  👉 Working Employees by Age Range & Department
  👉 Hires by Period and Department
  👉 Termination Status

- Demographics Employee:
  👉 Gender Split(Males and Females) Graph and PTD % Change
  👉 Avg. Income, Avg. Female Income and Avg. Male Income (Graph and PTD % change)
  👉 Avg. Income (Overall, Male, Female) with PTD % change
  👉 Current Employees by Race
  👉 Hires by Period and Department

---
- DAX Measure:
  👉 Total Hires, Terminations & Current Working Employees
  👉 PTD % Change (Hires, Terminations & Current Working Employees)
  👉 Avg. Income, Avg. Female Income & Avg. Male Income
  👉 PTD % Change of Avg. Income (Avg. Female Income & Avg. Male Income)
---

## Project Files
- 📊[Power BI File](https://github.com/Ayeshah123/PowerBI-HRAnalytics/blob/main/HR%20Analytics.pbix)
- 📊[Power BI PDF](https://github.com/Ayeshah123/PowerBI-HRAnalytics/blob/main/HR%20Analytics.pdf)
- 📊[Dataset](https://github.com/Ayeshah123/PowerBI-HRAnalytics/blob/main/HR_Dataset.csv)

---

👯 Open to learning, sharing & collaboration  

🌱 [LinkedIn](https://www.linkedin.com/in/ayeshabatool160/)  
🌱 [E-mail](mailto:ayeshabatool160@gmail.com)

