# HR-Data-analytics-Project-Power-BI-
This project focuses on analyzing HR employee data to monitor attrition, retention, satisfaction, and workforce distribution. The dashboard provides HR managers and business leaders with insights to reduce employee turnover, improve retention, and optimize workforce planning.

<img width="1915" height="1079" alt="Screenshot 2025-09-10 113659" src="https://github.com/user-attachments/assets/46ed5325-ce97-48b9-841a-8939127b11e3" />
<img width="1919" height="1079" alt="Screenshot 2025-09-10 113713" src="https://github.com/user-attachments/assets/8fc7198a-270d-42df-8cc8-90ef6ff8ce11" />
<img width="1919" height="1079" alt="Screenshot 2025-09-10 113731" src="https://github.com/user-attachments/assets/6a4b0e7e-8eb6-4bae-904f-5b9e19c177c8" />
<img width="1919" height="1079" alt="Screenshot 2025-09-10 113748" src="https://github.com/user-attachments/assets/30b330f9-4f5b-4a10-91fa-1428ca1935d9" />
<img width="1919" height="1079" alt="Screenshot 2025-09-10 113802" src="https://github.com/user-attachments/assets/5eec6393-3471-42fe-bb6a-2eee0513aed1" />
<img width="1919" height="1078" alt="Screenshot 2025-09-10 113815" src="https://github.com/user-attachments/assets/9d02ca63-eacb-4a97-af74-1fa5f83f612c" />

**Project Overview:**

**Data Cleaning & Preparation**

Removed blanks, handled missing values, standardized categorical fields (Job Roles, Departments, Attrition Yes/No).

Converted date and numeric columns into proper formats for accurate calculations.

**Data Modeling**

Designed a star schema with Fact (Employee Details) and Dimensions (Job, Department, Reviews, Salary).

Created hierarchies for Department → Job Role → Employee drilldowns.

Applied Row-Level Security (RLS) for department-level views.

**Analysis & KPIs**

Attrition Metrics → Total Employees, Attrition Count, Attrition Rate %, Retention Rate %.

Demographics → Gender split, Age distribution, Education level.

Tenure Insights → Avg years at company, first-year attrition, promotion analysis.

Employee Reviews → Job Satisfaction, Work-Life Balance, Environment, Relationship Satisfaction, Performance Ratings.

Salary Insights → Avg salary by Job Level, Department, and Role.

**Visualizations**

KPI Cards → Attrition %, Retention %, Avg Tenure, Avg Salary.

Donut/Pie → Gender split, Attrition split (Yes/No).

Bar/Column Charts → Attrition by Department, Job Role, Age Group.

Line Chart → Attrition trend over tenure/years.

Review Dashboard → Ratings distribution (Good/Bad/Neutral) across satisfaction metrics.

**Business Value**
This HR Analytics dashboard enables HR teams to:

Monitor and reduce attrition by identifying at-risk departments and job roles.

Improve employee retention through review & satisfaction insights.

Track career progression (tenure, promotions, job levels).

Ensure pay equity by analyzing salary distribution across roles.

Support data-driven workforce planning and HR strategy.
