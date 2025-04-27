# HR-Department-Report with Power Bi and SQL

### Project Overview

This HR Department Report provides comprehensive insights into workforce data by leveraging  SQL for data extraction , data analysis and Power BI 
for dynamic visualization. The report includes key HR metrics such as headcount, employee demographics, recruitment status, turnover rates etc.
SQL queries are used to securely fetch and aggregate data from multiple HR-related database, ensuring accuracy and real-time updates.
Power BI presents this data through interactive dashboards and customizable reports, enable HR leaders to make data-driven desicion, monitor HR KPIs,
forecast workfore needs and optimize talent management strategies.

### Data Used 

Data - HR Data with over 22000 rows from 
the year 2000 to 2020

Data Cleaning & Analysis - MySQL Workbench

Data Visualization - PowerBI

### Questions 

1. What is the gender breakdown of employeees in the company ? 

2. What is the race/ethnicity breakdown of employees in the
company ?

3. What is the age distribution of employees in the company?

4. How many employees work at headquarters versus remote
 locations ?

5. What is the average length of employment for the employees
 who have been terminated ?

6.How does the gender distribution vary across
departments and job titles?

7. What is the distribution of job titles across the company?

8. Which department has the highest turnover rate?

9. What is the ddistribution of the employees across location by state?

10. How has the company's employee count changed over time
based on hire and term dates?

11.What is the tenure distribution for each department?

### Summary of Findings

*  There are more male employees

* White race is the most dominant while Native Hawaiian and
  Americe Indian are the least dominant.

* The youngest employee is 20 years old and the oldest is
  57 years old

* 5 age groups were created(18-24,25-34,35-44,45-54,55-64). A
  large number of employees were between 25-34 followed
  by 35-44 while the smallest group was 55-64.

* A large number of employees work at the headquaters versus
  remotely.

* The average length of employment for terminated employees is 
  around 7 years.

* The gender distribution across departments is fairly balanced but
  there are generally more male than female employees.

* The Marketing department has the highest turnover rate followed
  by training. The least turn over rate are in the Research and
  development,Support and Legal departments.

* A large number of employees come from the state of ohio.

* The net change in employees has increased over the years.

* The average tenure for each department is about 8 years with
  Legal and Auditing having the highest and Services,
  Sales and Marketing having the lowest.

## Summary

1. Demographics & Age:

   More male employees overall.Predominantly White employees; Native Hawaiian and American Indian are the least represented.
   Employee age ranges from 20 to 57, with the majority between 25–34 years, followed by 35–44 years. Few employees fall into the 55–64 age group.

2. Work Locations & Tenure:

   A large number of employees work at headquarters compared to remote work.
   Average tenure of terminated employees is 7 years.
   Average departmental tenure is 8 years, with Legal and Auditing departments having the highest tenure and Marketing, Sales, and Services departments having 
   the lowest.

3. Turnover:

   Marketing has the highest turnover, followed by Training.
   Lowest turnover is in Research & Development, Support, and Legal departments.

4. Regional Presence:

   Many employees come from Ohio.
   Net employee numbers have steadily increased over time.

## Insights for Improvement

== Based on the data, here are actionable insights to improve the company’s performance and culture:

1. Diversity and Inclusion:

  Introduce initiatives to hire and retain individuals from underrepresented racial groups (e.g., Native Hawaiian, American Indian). This can include outreach 
  programs, partnerships with minority-focused organizations, and diversity hiring goals.
  Offer training to managers and employees to foster an inclusive workplace.

2. Balanced Gender Representation:

   While departments are relatively balanced, address the gender disparity overall by targeting roles with fewer female employees. Mentorship programs for women 
   and gender-neutral hiring practices can help.

3. Employee Retention:

  Investigate why Marketing and Training departments have high turnover rates. Possible areas to explore include workload, leadership, career growth 
  opportunities, and team dynamics.
  Invest in employee engagement programs (e.g., team-building activities, growth opportunities) for high-turnover teams.

4. Encouraging Remote Work:

  If feasible, consider enabling more employees to work remotely or hybrid. This could enhance job satisfaction, attract diverse talent, and reduce the strain on 
  physical office space.

5. Focus on Aging Workforce:

  Employees aged 55–64 form a small group. To encourage longevity, consider flexible work hours, phased retirement plans, or wellness programs tailored for 
  senior employees.

 6. Enhancing Tenure:

   For Sales, Services, and Marketing (departments with the lowest tenure), evaluate workload and reward systems to encourage longer employee commitment. 
   Structured career paths, recognition programs, and skill development opportunities can help.

7.  Leveraging Ohio’s Talent Pool:

   Since many employees are from Ohio, invest in branding and partnerships with local universities or organizations to tap into the regional talent pool further

### Limitations

* Some records had negative ages and these were excluded during 
  quering(967 records).Ages used were 18 and above.

* Some termdates were far into the future and were not included in
  the analysis (1599 records).The only term dates used were those less
  than  or equal to the current date.




