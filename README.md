# HR Analytics Dashboard | Power BI | Sytecx Hub Project-2

##  Project Overview
This project analyzes employee attrition using IBM HR Analytics dataset (1470 employees) as per Sytecx Hub Project-2 visual PDF. The goal is to identify attrition reasons and build interactive dashboard.

##  Dataset
- **Files:** HR-Employee-Attrition.csv, hr_dashboard_visual.pdf
- **Records:** 1470 Employees, 35 Columns
- **Key Columns:** Age, Attrition, Department, JobRole, MonthlyIncome, JobSatisfaction, OverTime, BusinessTravel, YearsAtCompany, DistanceFromHome

##  KPIs (As per PDF Page 1)

| KPI | Value | DAX |
|-----|-------|-----|
| Total Employees | 1470 | COUNTROWS(HR Dataset) |
| Attrition Count | 237 | CALCULATE(COUNTROWS, Attrition="Yes") |
| Attrition Rate | 16.12% | DIVIDE(Attrition, Total) |
| Avg Monthly Income | $6502 | AVERAGE(MonthlyIncome) |
| Avg Age | 37 | AVERAGE(Age) |

##  Dashboard Structure

**Page 1 - Workforce Overview**
- 5 KPI Cards, Attrition by Department (Bar), Employee Attrition Left vs Stayed (Donut - 237 vs 1233)

**Page 2 - Attrition Breakdown**
- Attrition by Age Group (26-35 Highest)
- Attrition by Job Satisfaction (Low=High Attrition)
- Attrition by OverTime (Overtime Yes=2x Attrition)
- Attrition by Business Travel (Travel_Frequently=High Risk)

##  Key Insights (From Visual PDF)
1. Overall attrition 16.12% - Need retention strategy
2. Sales Department highest attrition 20.8%
3. Age Group 26-35 leaves most
4. Low Job Satisfaction + OverTime = Major reason
5. Employees with high DistanceFromHome (10+ km) leave more

##  Tools Used
Power BI Desktop, DAX Measures, Data Visualization, GitHub
#PowerBI #HRAnalytics #DAX #AttritionAnalysis
