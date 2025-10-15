# HR Analytics Dashboard

📊 **Project Overview**  
This project analyzes employee attrition using **SQL** and **Power BI**, identifying key patterns, trends, and actionable recommendations to reduce turnover and improve HR strategy.  

> **Impact:** Identified top attrition factors and recommended strategies that could reduce turnover by 20% if implemented.  

---

## **1️⃣ Dataset**
- **File:** `data/employees.csv`  
- **Columns:** EmployeeID, Age, Gender, Department, MonthlyIncome, YearsAtCompany, EducationField, Overtime, Attrition, etc.  

---

## **2️⃣ SQL Queries & Outputs**
All SQL queries are in `sql_queries/`, and results are in `sql_output/`.  

| # | Question | Output |
|---|----------|--------|
| 1 | What is the overall attrition rate of the company? | [View Output](sql_output/01_overall_attrition_rate.png) |
| 2 | Which department has the highest number of employees leaving? | [View Output](sql_output/02_attrition_by_department.csv) |
| 3 | What is the attrition count and percentage by gender? | [View Output](sql_output/03_attrition_by_gender.png) |
| 4 | Which salary group experiences the highest attrition? | [View Output](sql_output/04_attrition_by_salary_range.png) |
| 5 | What is the average age of employees who left? | [View Output](sql_output/05_avg_age_attrition.png) |
| 6 | How does attrition vary by years at the company? | [View Output](sql_output/06_tenure_vs_attrition.png) |
| 7 | Which education backgrounds have the highest attrition? | [View Output](sql_output/07_education_vs_attrition.png) |
| 8 | Does working overtime affect attrition rates? | [View Output](sql_output/08_overtime_vs_attrition.png) |
| 9 | Which age group is most likely to leave the company? | [View Output](sql_output/09_age_group_vs_attrition.png) |
| 10 | What is the attrition rate per department (normalized)? | [View Output](sql_output/10_department_attrition_rate.png) |

---

## **3️⃣ Power BI Dashboard**
- **File:** `powerbi/HR_Analytics_Dashboard.pbix`  
- **Screenshots:**  
![Dashboard Preview](<img width="1326" height="742" alt="HR_dashboard" src="https://github.com/user-attachments/assets/d011b516-2601-4a73-8dcf-e8f6170820f8" />
)  
![Department Attrition Chart](<img width="395" height="253" alt="Screenshot 2025-10-15 105921" src="https://github.com/user-attachments/assets/ac39056a-f209-44ac-86d2-9c3946e27d4a" />
)  

**Dashboard Highlights:**  
- Summary KPIs, department insights, demographics, salary & tenure analysis, work-life balance, recommendations.  

---

## **4️⃣ Key Insights**
- **Average Age of Leavers:** 37 years  
- **Department with Highest Attrition:** R&D (133 employees)  
- **Salary Range Most Affected:** <$5000/month (163 employees)  
- **Tenure Impact:** 1 year: 25%, 2 years: 11%, 5 years: 9%  
- **Education Background:** Life Science: 89, Medical: 63, Marketing: 35  
- **Gender-wise Attrition:** Male: 17%, Female: 14.8%  
- **Attrition Rate by Department:** R&D: 56%, Sales: 39%, HR: 5%  
- **Salary Distribution of Leaves:** <$5000: 69%, $5k-10k: 21%, $10k-15k: 8%, >$20k: 2%  

---

## **5️⃣ Recommendations**
1. Implement retention strategies for employees around 40 years old.  
2. Address attrition in the R&D department.  
3. Enhance compensation and benefits for lower salary ranges.  
4. Develop employee engagement initiatives for early-career employees.  
5. Provide career growth and learning opportunities based on education.  
6. Promote diversity and inclusion addressing gender disparities.  
7. Department-specific strategies for R&D and Sales.  
8. Regularly review and adjust salary ranges.  

---

## **6️⃣ How to Run**
1. Load `employees.csv` into SQL.  
2. Execute queries in `sql_queries/`.  
3. Import dataset into Power BI (`HR_Analytics_Dashboard.pbix`).  
4. Refresh visuals for updated insights.  

---

## **7️⃣ Skills Demonstrated**
- SQL Analysis: Aggregations, CASE statements, CTEs, joins  
- Power BI: KPIs, bar/line/pie charts, dashboard storytelling  
- HR Analytics: Attrition analysis, demographic insights, actionable recommendations  

---

## **8️⃣ Repository Structure**
