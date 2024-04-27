# Empower HR: Unveiling the Secrets of Attrition and Training Efficacy
## Description
This report aims to provide insights into two key aspects of human resource management: employee attrition and training program effectiveness. The analysis is based on HR data that includes various metrics like age, department, performance ratings, and more.
## Objective
The project focuses on two primary objectives:
- To determine the factors contributing to employee attrition and provide insights for reducing attrition rates.
- To analyze the effectiveness of training programs and recommend improvements.
## Data Preparation & Cleaning
The initial dataset contained several missing values and discrepancies. Data cleaning involved:
- For the Gender & Position column, the values were updated to a more concise format for easier handling in future analyses. Specifically, the transformations were:
  - 'Female' was replaced with 'F'
  - 'Male' was replaced with 'M
  - 'DataScientist' was replaced with 'Data Scientist'
  - 'Marketinganalyst' was replaced with 'Marketing Analyst'
- For the purpose of more detailed analysis, the Age and Salary columns were categorized into different groups. These categorizations were designed to facilitate subgroup analyses, enabling the identification of patterns or trends that might not be obvious when considering the entire data set.
  - Age Categories:
    - Less than or equal to 30 years
    - Greater than 30 years
  - Salary Categories:
    - 50K - 60K
    - 60K - 70K
    - 70K - 80K
    - 80K - 90K
    - 90K - 100K 
- Converting the Last Promotion Date to a standard date format.

## Analysis & Insights
#### Employee Attrition Analysis:
1.	Department-wise attrition rates
     ![image](https://github.com/bittu-data/Empower-HR/assets/168248769/af9ea64f-e7f0-4cc0-b35a-b081bf4f35b2)

   - The Finance department has the highest attrition rate at 53.57%, followed by IT at 35.29%.
   - The Sales department has the lowest attrition rate at 20.83%.

2.	Salary-wise attrition rates
     ![image](https://github.com/bittu-data/Empower-HR/assets/168248769/ecbec355-4970-4c64-8849-9618457b0ca0)

   - The 90K - 100K salary bucket shows an alarmingly high attrition rate of 85.71%. This is particularly concerning as these employees are likely to be in more senior or specialized roles where attrition can be especially costly for the company.
   - There seems to be a general trend that higher salaries correlate with higher attrition rates (from 21.43% in the 50K-60K range to 85.71% in the 90K-100K range). This is counterintuitive and suggests that factors other than salary may be driving employees to leave.
   - Employees in the 50K - 60K range seem to be the most stable, with an attrition rate of only 21.43%. This could suggest that employees in this range find the compensation satisfactory for their role, or it could be that other factors like job security are more important to them.

## Conclusion
- Given the high attrition rates in the Finance and IT departments, targeted retention programs may be effective. This could include mentorship programs, work-life balance initiatives, and career development plans.
- Employees with 2 years and those with 7-10 years of service are leaving at high rates. For newer employees, improved onboarding and mentorship could help. For veterans, new career growth opportunities or skill diversification may be beneficial.
