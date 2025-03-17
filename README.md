# Capstone_project_HR_Data_driven_suggestions

# Employee Turnover Analysis

## Project Overview
This project analyzes employee turnover based on various factors such as satisfaction level, working hours, number of projects, and tenure. The goal is to identify key patterns and insights that contribute to employee attrition and satisfaction.

## Dataset
The dataset contains the following columns:
- **satisfaction_level**: Employee satisfaction score (0 to 1)
- **last_evaluation**: Last performance evaluation score
- **number_of_projects**: Total projects the employee worked on
- **average_monthly_hours**: Average number of hours worked per month
- **tenure**: Number of years at the company
- **work_accident**: Whether the employee had a work accident (0 = No, 1 = Yes)
- **left**: Whether the employee left the company (0 = No, 1 = Yes)
- **promotion_last_5years**: Whether the employee was promoted in the last 5 years (0 = No, 1 = Yes)
- **department**: Employee's department
- **salary**: Employee's salary category (low, medium, high)

## Key Findings
### Correlations and Observations
- Employees working on **more projects** generally worked **longer hours**.
- Two distinct groups of employees who left:
  - **Group A**: Worked fewer hours than peers, possibly fired or transitioning out.
  - **Group B**: Overworked employees who likely quit due to stress.
- **All employees with 7 projects left** the company, often working **255–295 hours/month**.
- Employees with **3–4 projects** had the lowest turnover rates.
- Employees working **240–315 hours/month** had **very low satisfaction**, indicating burnout.
- Employees with **normal working hours** but **low satisfaction (~0.4)** still left, possibly due to workplace pressure.
- **Unusual data distribution patterns** suggest possible data manipulation or synthetic data.
- **Four-year-tenured employees** had **abnormally low satisfaction**, suggesting a potential **policy change** at that stage.
- **Long-tenured employees rarely left**, possibly indicating they held **higher-ranking, higher-paid positions**.

## Next Steps
- Calculate **mean and median satisfaction scores** for employees who left vs. those who stayed.
- Investigate potential company policies affecting satisfaction at **the four-year tenure mark**.
- Perform additional **tenure-based analysis** to refine insights on employee retention.

## Tools Used
- **Python** (Pandas, Matplotlib, Seaborn)
- **Jupyter Notebook**

## How to Use
1. Load the dataset into a Pandas DataFrame.
2. Run exploratory data analysis (EDA) using provided visualizations.
3. Use insights to improve employee retention strategies.

## Contributors
- Derrick Fosu Adofo
- derrickfosuadofo@gmail.com

## License
This project is a part of the Advanced Google data analytics program offered on Coursera



