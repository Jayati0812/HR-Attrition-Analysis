# HR-Attrition-Analysis
### **1. Project Title** 
HR Attrition Analysis
Build an end to end HR Attrition Analysis solution in Microsoft Fabric, ingesting 1,470 employee records through Dataflow Gen2 and surfacing attrition drivers across department, salary abnd and age.

### **2. Short Description**
The HR Attrition Analysis is a analytical report designed to help HR understand why the attrition rate has crept up to ~16% annually over the last two years. This dashboard focuses on surfacing attrition drivers across department, salary band, age, business travel, education field and job role. This tool is intended for use by data analysts, HR Department and Management and data driven strategists who seek to understand attrition trends.

### **3. Tech Stack**
The dashboard was built using following tools and technologies:
1. Microsoft Fabric Pipeline: Ingesting 1,470 employee records through online dataset.
2. Microsoft Dataflow Gen2: Apply transformation using Power Query on the data.
3. Power Query: Data transformation, cleaning and feature engineering for preparing the data.
4. Microsoft Lakehouse: Primary data sorce with structured Delta tables in Table section.
5. Microsoft Fabric Semantic Model: Creating data model and building relationships.
6. DAX (Data Analysis Expression): used for calculated measures, dynamic visuals, and conditional logic.
7. Power BI Desktop: Main data visulaization platform used for report creation.
8. File Format: .pbix for development and .png for dashboards previews.

### **4. Data Source**
Source: IBM HR Analytics Attrition Dataset 
Link: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

Data of ~1,470 employee of the company, including details of their age, montly income, distance from home, department, travel etc. of year 2023-2024.

### **5. Feature Highlight**
**Business Problem** 
I used AI as a client in which AI was heading HR Ops for the company in which attrition rate has crept up to ~16% annually over the last two years, and it's not evenly spread — some teams are bleeding people while others are stable. Replacing a mid-level employee costs them roughly 6-9 months of their salary once they factor in recruitment, onboarding, and the productivity dip while a new hire ramps up. Last year alone, unplanned attrition cost them an estimated ₹14 crore.

Key Questions:
1. which department is bleeding the most?
2. which job role is being affected most by attrition?
3. what is the average tenure after which employees are leaving?
4. what is the salary band of the employees who left?
5. Does age group or marital status drives attrition?
6. what education field does employees who left had?
7. how does overtime affect attrition
8. does business travel play a role in driving attrition?

**Goal of the Dashboard**
The goal of this dashboard was to create an interactive report which helped HR understand what is the cause of such a high attrition rate as avg attrition in industry is around 10-15%. This dashboard helped HR Ops to tell the leadership teams or higher management what steps can be taken to reduce and manage attrition by understanding what are the drivers of attrition. 

**key visuals**
The Kpis used in this report :
1. Attrition rate: 16.12%
   Out of total headcount how many employees left in percent
2. Employees Left: 237
3. Total Headcount: 1,470
4. Average Income: 6,503
   Avg montly income of employees who left
5. Average Tenure of Leavers: 5.1
   Avg years at company

the slicers used :
1. department
2. salary band
3. gender

Attrition Decomposition (Decomposition chart):
in this chart a hierarchy is created of department, job role and salary band. To get a deep understanding of which
department was affected the most and how many employees in count left and out of that department which job role was causing
most attrition and what was the salary range of the employees who left in that role. 

Attrition Based on Age Group (Matrix):
this matrix helped in getting a analysis of which age group was driving attrition most.
there we created different age groups of 18-25, 26-35, 36-45 and above 45 and had headcount and employees left count and attrition rate to understand is age a driving factor in attrition.

Attrition Based on OverTime (Bar chart):
this chart was created against if the employees who worked overtime had a more rate of attrition or not.

Attrition Based on Business Travel (Bar Chart):
this chart helped in the analysis of employees had to travel frequently, rarely or not travel at all for business purposes doe that contribute to attrition rate.

### **6. Insights**
1. The Sales department is having the highest attrition rate and the job role that has suffered in the sales department is Sales Representative.
2. The employees that have low montly income have a higher risk of leaving.
3. The employees who are in a age group of 18-25 years are most likely to contribute to attrition.
4. the employees who are single are having the high attrition rate.
5. the employees who tend to work overtime are leaving the most.
6. the employees who have to travel frequently due to work are having high attrition rate.
7. the employees who are leaving out of them mostly they are male employees.
8. the employees who have human resource as their education field are leaving the most.

### **7. Business Impact**
1. The company needs to focus on not to ask employees for working overtime and maintain a good work life balance.
2. the company needs to equally distribute travels among the employees and not to burden some employees with frequent travel
3. the company should focus on young employees and make them have a good environment at work.
4. the company needs to focus on giving trainings more frequently to entry level jobs employee.
5. the company needs to give appraisals to employees and give bonus in order to increase monthly income.

### **9. Dashboard Screenshots**
![Overview](images/Overview.png)
![deep_dive](images/Deep_Dive.png)
