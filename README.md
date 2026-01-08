# Employee-Attrition-Dashboard-for-HR-Department
This project looks at why employees leave or stay, from the view of a junior business analyst working with the HR team. Using Tableau and a detailed dataset, it explores how factors like age, job role, income, and satisfaction influence attrition, aiming to help HR build better strategies to keep employees engaged.

# Executive Summary
Objective This analysis investigates the key drivers behind employee turnover to provide the HR department with data-driven insights for improving retention strategies. By examining a dataset of organizational health metrics, the study identifies high-risk demographics and departmental pain points.

# Business Problem

The organization is experiencing a noticeable shift in talent retention, impacting operational continuity and recruitment costs. While the company maintains a diverse workforce across various job roles and income levels, HR has identified an increasing trend of voluntary departures.

**Problem Statement**

The HR department lacks a clear understanding of the specific socio-economic and professional drivers contributing to employee attrition. Without identifying which demographics (age, income) and departments (job roles) are most at risk, the company cannot implement targeted retention strategies, leading to the potential loss of high-performing talent and increased turnover expenses.

**Goal** 

To analyze historical employee data using Tableau to identify high-risk attrition clusters and provide actionable recommendations to HR for improving job satisfaction and long-term employee engagement.

# Key Findings
‣ Demographic Vulnerability: Attrition is most prevalent among younger employees (ages 20–35), suggesting a need for better early-career engagement or clearer growth pathways.

‣ Role-Specific Turnover: Sales Executives, Research Scientists, and Laboratory Technicians exhibit the highest volume of departures. While these roles also have high headcount, the concentrated loss of talent in these areas suggests role-specific stressors.

‣ Financial & Growth Triggers: Lower-income brackets ($2,000–$2,999) show the highest attrition rates. Furthermore, while standard 13-14% salary hikes are common, they do not seem sufficient to retain top talent; only hikes exceeding 22% showed a definitive correlation with high retention.

‣ Training & Development: Frequent training (4+ sessions annually) correlates with higher retention, whereas minimal training or moderate training (2-3 sessions) saw higher turnover rates.

# Recommendations 
HR department in the company should focus on: 
‣ Structured mentorship for the 20-35 age bracket.

‣ Review the compensation competitiveness for laboratory and sales roles.

‣ Increase professional development opportunities to at least four sessions per year to foster long-term loyalty.

# Technical Toolkit
Data Visualization: Tableau Desktop (creating interactive dashboards, box plots, and dual-axis charts).

Data Analysis: Exploratory Data Analysis (EDA), Correlation Analysis, and Trend Identification.

Statistical Concepts: Distribution analysis, Outlier detection, and Quartile interpretation.

HR Analytics: Metric development for attrition rates, salary hike impacts, and training effectiveness.

# Insights and Analysis

**Age Distribution based on Employee Attrition**

![image](https://github.com/user-attachments/assets/3b33cefb-8888-4250-aede-c1a8836d16ad)

The age distribution analysis reveals a high propensity for attrition within the 25–35 age bins. While the total employee count peaks in the 30–35 age interval, this group also experiences the highest volume of departures. 

Interestingly, as employees age beyond 40, the likelihood of attrition drops significantly, showing a more stable and loyal workforce in senior age brackets.

**Attrition by Job Roles**

![image](https://github.com/user-attachments/assets/7947e5ec-e02b-42d1-a958-100d0b4e26ef)


This bar chart displays the attrition rate across different job roles. The job roles specified in the graph are: 
-	Healthcare Representative 
-	Human Resource 
-	Laboratory Technician 
-	Manager 
-	Manufacturing Director 
-	Research Director 
-	Research Scientist 
-	Sales Executive
-	Sales Representative 

![image](https://github.com/user-attachments/assets/ca6ca200-f123-4344-a4e8-24dc71f1d8db)


We can see in the below filtered (Yes) bar chart, that Sales Executive, Research Scientist, and Laboratory Technician display higher rate of attrition compared to the rest of the job roles.
Similarly most employees that worked as Sales Executive, Research Scientist, and Laboratory Technician also remained at the company. This can mean that each employee had a unique experience at these roles that influnenced some to leave and some to stay. 


**Income Range by Atrrition**


![image](https://github.com/user-attachments/assets/ae93c377-66a7-48f2-96a7-d97647ae8db5)


The income range and employee attrition is represented in the form of a box plot. 
For both employees who departed and those who stayed, the medians are essentially at the same level. This implies that there may not be noticeable variations in the two groups' median incomes.

But the leavers' (Yes) box is positioned a slightly lower than the stayers' (No) box. This might point to a pattern where employees who make a little less money are more inclined to quit the company.

For both boxes, the whisker lengths are comparable. This implies that there is similarity between the two groups in the income data scattered outside of the quartiles.

High-Attrition Outlier (Count: 95): Within the group of employees who left, this outlier represents a disproportionately high volume of departures. This likely corresponds to the $2,000–$2,999 income range, indicating a high-risk zone for the company.

Low-Headcount Retention Outlier (Count: 132): Within the group of employees who stayed, this outlier sits far below the main cluster. This represents a smaller, niche demographic—such as senior leadership—where retention is high, but the total number of staff is low.

**Job Satisfaction by Attrition**


![image](https://github.com/user-attachments/assets/53a9c236-892d-4efe-a624-996fe986d90b)


In a general overview, some employees that are least satisfied left the company as shown in the above Figure. While most employees that are least satisfied continued with the same company. As the satisfaction increases more employees stayed with the company. The age filter is also displayed to show the different age range of employees that are satisfied with their job in regard to the attrition rate. 


# Final Dashboard

![image](https://github.com/user-attachments/assets/9c5ae02a-8fc2-405d-85ba-7ea0698157e3)


Employees that earn $2000-$2999 have the highest attrition amongst other income groups. Meanwhile in the ‘No’ attrition bar chart, employees that earn from $3000-$4999 are most likely to stay in the company along with people earning from $2000-$2999 and from $10000-$12000 a month. 

Employees that left the company received a salary hike of 13%-14%, however most employees that stayed with the company also received a salary hike of 13%-14%. 
Employees that received a hike of 22%-26% are least likely to leave the company as demonstrated on the with the color blue.  

Majority of employees that left the company trained 2-3 times last year. Employees that trained more than 4 times, however, had lower rate of attrition. 
Most of the employees that stayed in the company also trained 2-3 but only 62 employees that trained only once has stayed with the company. 



**The repository contains two files**

⁃ Tableau Dashboard of the Employee-Attrition 

⁃ Report that includes findings, trends and written analysis with screenshots.


