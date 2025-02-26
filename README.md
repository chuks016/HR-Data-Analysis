# HR Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Dataset Description](#dataset-description)
- [Exploratory Data Analysis](exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendation](#recommendation)
- [Limitations](#limitations)
- [References](#references)

### Project Overview
This project is an HR data analysis conducted using Excel. The dataset contains various employee details such as satisfaction levels, evaluation scores, project numbers, working hours, service years, work accidents, promotions, department allocation, and salary categories. The analysis aims to derive insights that help HR professionals make data-driven decisions.


### Data Sources

The dataset used in this project is a simulated HR dataset, created for educational and analytical purposes. It does not contain real employee data but is structured to resemble real-world HR records for meaningful analysis.

### Tools

- Excel: Used for data cleaning, aggregation, and analysis. [Download here](https://www.microsoft.com/en-gb/microsoft-365/excel)

### Dataset Description

The dataset includes the following key columns:

- Emp ID: Unique identifier for employees.
- Full Name: Employee name.
- Satisfaction Level: Percentage representing employee satisfaction.
- Satisfaction Category: Categorised as Low, Mid, or High Satisfaction.
- Last Evaluation: Employee performance score.
- Average Number of Projects: Number of projects assigned on average.
- Average Monthly Hours: Monthly working hours of the employee.
- Service Years: Total years of service in the company.
- Work Accident: Whether the employee had a work accident (0 = No, 1 = Yes).
- Departed Staffs: Indicates whether the employee left the company.
- Last 5 Years Promotion: Whether the employee was promoted in the last five years.
- Department: Employee's department.
- Salary: Employee salary.
- Salary Category: Categorised as Low, Average, High, or Premium Income.

### Exploratory Data Analysis

EDA involved exploring the HR data to answer key questions such as:

- Total number of staff members.
- Total number of current staff members.
- Average satisfaction level of employees in each department.
- Number of employees in each salary category within each department.
- Average number of projects completed by employees in each department.
- Number of employees who left the company in each department (Attrition & Attrition Rate).
- Average monthly hours worked by employees in each department.
- Number of employees promoted in the last five years in each department.
- Number of work accidents in each department.

 ### Data Analysis

Step 1: Data Cleaning & Preparation

- Ensured there were no missing or duplicate records.
- Formatted numerical values properly.
- Categorised satisfaction levels and salary brackets.

Step 2: Data Aggregation

- Used Excel Pivot Tables to summarise data for each department.
- Calculated attrition rate by comparing the number of departed staff to the total staff per department.

Step 3: Data Analysis

- Analysed average satisfaction levels and categorised them into High, Mid, and Low satisfaction.
- Evaluated the correlation between employee evaluation scores, projects assigned, and satisfaction levels.
- Examined salary distribution across departments.
- Assessed work accidents and promotion trends.

Step 4: Visualisation & Insights

- Created pivot tables and charts to visualise trends.
- Derived insights to support HR decision-making, such as potential areas for employee engagement improvements and salary optimisation.

### Results

1. High Attrition Rate: The overall attrition rate is 36.32%, with some departments like Sales and Technical showing the highest numbers of departed staff.
2. Employee Satisfaction: Satisfaction levels vary across departments, with Human Resources and Management having relatively higher satisfaction rates, whereas Technical and Sales have a mix of high, mid, and low satisfaction levels.
3. Work Accidents & Promotions: There are minimal work accidents, with only a few departments reporting incidents. Promotions in the last five years are also limited, indicating potential areas for employee development.
4. Average Salary & Work Hours: The average employee salary and monthly hours worked differ across departments, with some like Sales and Technical showing higher figures, indicating a potential correlation between compensation and workload.

### Recommendation

- Implement Retention Programs: Focus on developing and implementing retention strategies, especially in high-attrition departments like Sales and Technical. This could include career development opportunities, mentorship programs, and clear career advancement paths.
- Enhance Employee Engagement: Address the varying levels of employee satisfaction by conducting regular surveys and feedback sessions. Use this data to tailor engagement initiatives that cater to the specific needs of each department.
- Promote Career Development: Increase opportunities for employee promotions by investing in training and development programs. Ensure that employees see a clear pathway to growth within the company.
- Balance Compensation and Workload: Review and adjust compensation and workload to ensure fairness and equity across departments. This could involve salary adjustments, bonuses, and work-life balance initiatives to reduce stress and burnout.
- Strengthen Safety Measures: Even though work accidents are minimal, continuously reinforce safety protocols and provide regular training to maintain a safe work environment.

### Limitations

1. Data Scope and Sample Size: The dataset is limited to a specific period and sample of employees, which may not fully represent the broader workforce trends.
2. Potential Bias: The data might contain biases due to self-reporting or incomplete records, which can affect the accuracy of the results.
3. External Factors: The analysis does not account for external factors like market conditions or industry trends, which can influence employee satisfaction and attrition rates.
4. Dynamic Nature of HR Metrics: Employee satisfaction, workload, and other HR metrics are dynamic and can change over time, making it important to continuously update and review the data.

### References

1. Data Analytics Made Accessible by Dr. Anil Maheshwari
2. Data Analysis Training/Mentorship by Webdeves Academy
3. [Data Analyst Bootcamp by Alex The Analyst](Data Analyst Bootcamp: http://www.youtube.com/playlist?list=PLUaB-1hjhk8FE_XZ87vPPSfHqb6OcM0cF)


