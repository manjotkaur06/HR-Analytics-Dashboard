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

| # | Question | Output |
|---|----------|--------|
| 1 | What is the overall attrition rate of the company? | [View Output](https://github.com/user-attachments/assets/721f9a0a-9998-46b9-b01c-fef59acc8cd5) |
| 2 | Which department has the highest number of employees leaving? | [View Output](https://github.com/user-attachments/assets/078fa6ba-c885-4924-bd4f-c2b91398b763) |
| 3 | What is the attrition count and percentage by gender? | [View Output](https://github.com/user-attachments/assets/959b29b4-a541-429b-b635-16b0fdacb52a) |
| 4 | Which salary group experiences the highest attrition? | [View Output](sql_output/04_attrition_by_salary_range.png) |
| 5 | What is the average age of employees who left? | [View Output](https://github.com/user-attachments/assets/75c85a8d-f705-45fc-9dc4-efd2186c5459) |
| 6 | How does attrition vary by years at the company? | [View Output](https://github.com/user-attachments/assets/5e959024-476a-4e3e-8abe-d48ad2c8e819) |
| 7 | Which education backgrounds have the highest attrition? | [View Output](https://github.com/user-attachments/assets/dc877085-4a98-45e6-a595-71e1c2139b61) |
| 8 | Does working overtime affect attrition rates? | [View Output](https://github.com/user-attachments/assets/f94f1a43-c7b9-4e92-a552-6e28c5e43704) |
| 9 | Which age group is most likely to leave the company? | [View Output](https://github.com/user-attachments/assets/94840389-50ec-4b37-a7c3-c85a0b89ce85) |
| 10 | What is the attrition rate per department (normalized)? | [View Output](https://github.com/user-attachments/assets/00b7fa86-25d7-459e-a0f8-d794a071309c) |

---

## **3️⃣ Power BI Dashboard**
- **File:** `powerbi/HR_Analytics_Dashboard.pbix`  
- **Screenshots:**  
![Dashboard Preview]<img width="1326" height="742" alt="HR_dashboard" src="https://github.com/user-attachments/assets/d011b516-2601-4a73-8dcf-e8f6170820f8" />
  
![Department Attrition Chart]<img width="395" height="253" alt="Screenshot 2025-10-15 105921" src="https://github.com/user-attachments/assets/d9edf79e-70ff-452b-9652-581279dcaf91" />

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
