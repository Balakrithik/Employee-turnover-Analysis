# **Employee Turnover Analysis** 📊

### **Project Overview**  
This project focuses on analyzing employee turnover data at **NewPort Tech** to identify factors influencing attrition. By using data exploration and visualization, it provides actionable insights to improve employee retention and streamline HR processes.

---
## **Project Problem**  
**NewPort Tech** is facing challenges with employee turnover, which impacts productivity and increases recruitment costs. The company evaluates employees periodically, gathering data on:
- Number of projects worked on  
- Average monthly working hours  
- Time spent in the company  
- Promotions in the last five years  
- Salary levels  
- Job satisfaction  

Despite these efforts, high turnover rates persist, suggesting that deeper insights into employee behavior and satisfaction are needed to address the root causes of attrition.

**Objective:**  
Identify patterns and factors contributing to employee turnover to inform data-driven decisions that improve retention and HR efficiency.

---

## **Solutions**  
Through a comprehensive analysis of the employee data, this project provides:
1. **Data-Driven Insights** 🧠:  
   Identifying key factors (e.g., low satisfaction, high workloads) that correlate with turnover.
   
2. **Process Improvement Recommendations** 🔧:  
   Suggestions for HR interventions, such as workload balancing, recognition programs, and targeted retention strategies.
   
3. **Visualization of Trends** 📊:  
   Clear, actionable visualizations to help HR managers understand turnover dynamics and make informed decisions.

---

## **Dataset**  
The dataset includes critical employee metrics such as satisfaction levels, work hours, and promotions. This dataset contains nearly 15004 rows and 11 columns.

| Column Name              | Description                                                     |
|--------------------------|-----------------------------------------------------------------|
| `satisfaction_level`     | Employee's job satisfaction score (0 - 1)                       |
| `last_evaluation`        | Last performance evaluation score                               |
| `number_project`         | Number of projects assigned to the employee                     |
| `average_monthly_hours`  | Average monthly hours worked                                    |
| `time_spent_company`     | Number of years spent at the company                            |
| `Work_accident`          | Whether the employee had a work accident (0: No, 1: Yes)        |
| `Quit_the_Company`       | Turnover indicator (0: Stayed, 1: Left)                         |
| `promotion_last_5years`  | Number of promotions in the last five years                     |
| `Departments`            | Employee's department                                           |
| `salary`                 | Salary level (Low, Medium, High)                                |

---

## **Key Analyses**  
### **1. Exploratory Data Analysis (EDA)**  
- **Satisfaction vs. Turnover:**  
  Analyzed satisfaction levels to determine their correlation with turnover. Lower satisfaction correlates with higher turnover.
  
- **Work Hours Analysis:**  
  Compared average monthly working hours between employees who left and those who stayed. Overworked or underutilized employees showed higher turnover rates.
  
- **Projects vs. Turnover:**  
  Examined the relationship between the number of projects and turnover. Both too many and too few projects increased turnover risk.

- **Tenure Impact:**  
  Analyzed the effect of tenure on turnover, with spikes observed around the 3-5 year mark, indicating possible career stagnation.

- **Department Breakdown:**  
  Visualized turnover rates across different departments to identify high-risk areas.

### **2. Feature Engineering**  
- **Binning Satisfaction Levels** 📊:  
  Grouped satisfaction scores into categories (Low, Medium, High) to simplify analysis.
  
- **Tenure Brackets** ⏳:  
  Categorized time spent in the company into meaningful intervals (e.g., 0-2, 3-5, 6+ years).
  
- **Work-Life Balance Index** ⚖️:  
  Created a ratio of average monthly hours to the number of projects to assess workload balance.

---

## **Insights and Recommendations**  
- **Low Satisfaction Drives Turnover** 💔:  
  Employees with satisfaction scores below 0.5 were significantly more likely to leave. Regular feedback sessions and personalized development plans could address this.
  
- **Optimal Workload Management** ⚖️:  
  Employees working either too few (< 100) or too many (> 250) hours per month showed higher turnover. Implementing workload balance strategies can improve retention.
  
- **Promotion and Recognition** 🎉:  
  Lack of promotions within five years correlated with higher turnover. Implementing career development programs could enhance engagement.
  
- **Department-Specific Strategies** 🏢:  
  Departments with higher turnover need targeted interventions, such as leadership training or team-building initiatives.

---

## **Technologies Used**  
- 🐍 **Python**: Data processing and analysis  
- 🐼 **Pandas & NumPy**: Data manipulation  
- 📈 **Seaborn & Matplotlib**: Visualization  
- 🧑‍💻 **Jupyter Notebook**: Analysis and report presentation

---

## **How to Run the Project**  
1. Clone this repository:  
   ```bash
   git clone https://github.com/Balakrithik/employee-turnover-analysis.git
   cd employee-turnover-analysis
