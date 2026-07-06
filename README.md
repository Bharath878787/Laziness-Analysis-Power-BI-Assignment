# Laziness-Analysis-Power-BI-Assignment

# Overview
This project uses **Power BI** to analyze employee productivity and laziness drivers.  
It explores how factors such as **department, work mode, salary level, social media usage, break time, and deadlines** influence performance.  
The dashboard highlights both **risk factors** (high laziness, social media usage) and **success cases** (perfect completion, zero missed deadlines).

# Dataset Columns
The dataset contains the following fields:

- **Employee_ID** – Unique identifier for each employee  
- **Department** – Department of the employee (Finance, HR, IT, Marketing, Sales)  
- **Work_Mode** – Work arrangement (Office / WFH)  
- **Salary_Level** – Salary category (High / Medium / Low)  
- **Active_Work_Hours** – Total hours actively spent on work  
- **Break_Time_Hours** – Hours spent on breaks during work  
- **Laziness_Index** – Calculated metric representing employee laziness level  
- **Task_Completion_%** – Percentage of tasks completed  
- **Tasks_Assigned** – Number of tasks assigned  
- **Tasks_Completed** – Number of tasks completed  
- **Meetings_Attended** – Count of meetings attended  
- **Deadline_Missed** – Whether deadlines were missed (Yes / No)  
- **Social_Media_Usage_Hours** – Hours spent on social media during work  
- **Login_Hours** – Total login hours recorded  
- **Productivity_Category** – Categorization (High Laziness / Moderate / Productive)

## 📑 Dashboard Pages

- **Employee Productivity & Laziness Dashboard**  
  KPIs, departmental breakdown, work mode comparison, social media vs task completion scatter plot, productivity distribution pie chart, and Top 10 Lazy Employees table.

- **Employee Details**  
  Detailed table of employee metrics (laziness index, active hours, break time, completion %, meetings, salary level).

- **Employee Highlights**  
  Spotlight groups:  
  - 10 employees with extremely high social media usage  
  - 15 employees with perfect completion rate  
  - Employees with zero missed deadlines  

- **Decomposition Tree**  
  Interactive breakdown of laziness drivers by department, work mode, salary, deadlines, and social media usage.

- **Break Time Simulation**  
  What‑If parameter to test how reduced break time impacts laziness index.

## 📷 Screenshots
Screenshots of each dashboard page are included in the `/Screenshots` folder:  
- Employee Productivity & Laziness Dashboard  
- Employee Details  
- Employee Highlights  
- Decomposition Tree  
- Break Time Simulation  

## 🔑 Insights
- Marketing shows the highest laziness index.  
- 15 employees achieved perfect completion.  
- Several employees never missed deadlines, showing strong discipline.  
- Social media usage correlates with higher laziness.  
- Break time reduction lowers laziness index in simulations.

##  Laziness Index Analytical Questions

1. **Which department has the highest average laziness?**  
   ✅ Sales Department has the highest average laziness.

2. **Is WFH more associated with laziness?**  
   ✅ WFH is slightly more associated with laziness, but the difference is marginal.

3. **Does salary level impact productivity?**  
   ✅ Yes. Low salary employees have a higher Laziness Index, while higher salary levels show slightly lower laziness, contributing to more productivity.

4. **What is the relationship between social media usage and missed deadlines?**  
   ✅ Social media usage hours generally impact missed deadlines. However, in this model, even employees who did not miss deadlines had high average social media usage hours.

5. **Who are the top 5 most productive employees?**  
   ✅ EMP130, EMP108, EMP003, EMP122, and EMP019 — they have high task completion and the lowest laziness index.

6. **Is meeting attendance affecting task completion?**  
   ✅ Employees with higher meeting attendance often show lower task completion. Excessive meetings reduce task completion efficiency.

7. **Which department needs HR intervention?**  
   ✅ Sales Department and HR Department need HR intervention because they show high laziness and missed deadlines.
